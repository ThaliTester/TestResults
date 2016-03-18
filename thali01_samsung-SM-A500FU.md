#### Test 63377149f0d5e10_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
03-18 15:47:53.045  2368  3001 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
03-18 15:47:53.045  1238  2965 V MediaScanner: processDirectory :  /storage/extSdCard
03-18 15:47:53.045  1238  2965 W MediaScanner: Error opening directory, reason : Permission denied.
03-18 15:47:53.045  1238  2965 W MediaScanner: 7klwibgf7fxlKdCbid7
03-18 15:47:53.045  1467  2280 D SmsProvider: Update uri=content://sms/outbox, match=8
--------- beginning of system
03-18 15:47:53.045  1016  1702 D ActivityManager: startProcessLocked calleePkgName: com.sec.dsm.system, hostingType: broadcast
03-18 15:47:53.045  1016  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.045  1016  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.045  1016  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.045  1016  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.045  1238  2965 V MediaScanner:  prescan time: 63ms (DB items: 27)
03-18 15:47:53.045  1238  2965 V MediaScanner:     scan time: 25ms (Caching mode: true), (makeEntry time: 19ms ~76%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-18 15:47:53.045  1238  2965 V MediaScanner: postscan time: 3ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-18 15:47:53.045  1238  2965 V MediaScanner:    total time: 91ms
03-18 15:47:53.045  1238  2965 V MediaScanner: checked files: 10  directories : 17  (I: 0, U: 0)
03-18 15:47:53.055  1467  2280 D TP/MmsSmsProvider: need read changed broadcast:false
03-18 15:47:53.055  3029  3098 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
03-18 15:47:53.065  1016  1041 W libprocessgroup: failed to open /acct/uid_10113/pid_2285/cgroup.procs: No such file or directory
03-18 15:47:53.075  3105  3105 E Zygote  : MountEmulatedStorage()
03-18 15:47:53.075  3105  3105 E Zygote  : v2
03-18 15:47:53.075  3105  3105 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-18 15:47:53.075  3105  3105 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-18 15:47:53.075  3105  3105 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:53.075  3105  3105 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:53.075  3105  3105 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:53.075  1016  1702 I ActivityManager: Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3105 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-18 15:47:53.085  2368  3068 D Mms/SmsReceiverService: moveOutboxMessagesToFailedBox messageCount: 0
03-18 15:47:53.085  2368  3068 D Mms/SmsReceiverService: handle boot completed, sendFirstQueuedMessage()
03-18 15:47:53.085  2368  3068 D Mms/SmsReceiverService: [SIM-1]sendFirstQueuedMessage()
03-18 15:47:53.085  3029  3098 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
03-18 15:47:53.085  1016  1496 D SettingsProvider: name = block_emergency_message
03-18 15:47:53.085  1016  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-18 15:47:53.085  1016  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-18 15:47:53.085  1016  1496 D SettingsProvider: selectionArgs: false
03-18 15:47:53.085  1016  1496 D SettingsProvider: selectionArgs: 10048
03-18 15:47:53.085  1016  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-18 15:47:53.085  1016  1496 D SettingsProvider: ret = -1
03-18 15:47:53.085  1571  1579 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
03-18 15:47:53.085  1016  1041 W libprocessgroup: failed to open /acct/uid_10015/pid_1633/cgroup.procs: No such file or directory
03-18 15:47:53.085  1238  2965 D MediaScannerService: !@done scanning volume external
03-18 15:47:53.095  2634  2634 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2634) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-18 15:47:53.095  2634  2634 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2634) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
03-18 15:47:53.095  2634  2634 D FactoryTestApp: [DummyFtClient$sendBootCompletedAndFinish](2634) ...
03-18 15:47:53.095  2634  2634 D FactoryTestApp: [Support$Values.getString](2634) id=MODEL_COMMUNICATION_MODE, value=gsm
03-18 15:47:53.095  2634  2634 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2634) mConnectionMode = gsm
03-18 15:47:53.095   356   356 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 10003, gid 10003, pid 3029
03-18 15:47:53.095   356   356 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
03-18 15:47:53.095  3029  3098 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
03-18 15:47:53.095  2634  2634 D FactoryTestApp: [IPCWriterToSecPhoneService$ResponseWriter](2634) Create IPCWriterToSecPhoneService
03-18 15:47:53.095  2634  2634 I FactoryTestApp: [IPCWriterToSecPhoneService$connectToSecPhoneService](2634)  
03-18 15:47:53.095  3029  3098 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
03-18 15:47:53.095  1016  1229 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:53.095  1016  1229 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:53.095  1016  1229 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
03-18 15:47:53.095  1016  1029 W ActivityManager: getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
03-18 15:47:53.095  2634  2634 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
03-18 15:47:53.095  1016  1229 D ActivityManager: bindService callerProcessName:com.sec.factory, calleePkgName: com.sec.phone, action: null
03-18 15:47:53.095  1016  1229 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
03-18 15:47:53.105   356   356 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 10003, gid 10003, pid 3029
03-18 15:47:53.105   356   356 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
03-18 15:47:53.105  3105  3105 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:53.115  3105  3105 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:53.115  1467  1479 D TP/SmsProvider: query,matched:26, calling pid = 2368
03-18 15:47:53.135  1571  1579 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-18 15:47:53.135  1488  1488 D Launcher.Model: reloadBadges entered.
03-18 15:47:53.135  1571  1579 D BadgeProvider: sendNotify, [notify] : null
03-18 15:47:53.135  1571  1579 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-18 15:47:53.135  1571  1579 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-18 15:47:53.135  1571  1579 D BadgeProvider: update, [UpdateCount] : 1
03-18 15:47:53.135  2368  3001 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-18 15:47:53.145  1467  1479 D TP/SmsProvider: match 26:Elapsed time : 43.549 ms
03-18 15:47:53.145  2634  2634 I FactoryTestApp: [IPCWriterToSecPhoneService$onServiceConnected](2634) connected done
03-18 15:47:53.145  2634  2634 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2634) Send Response Message to SecPhone
03-18 15:47:53.145  2634  2634 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2634) Response ��
03-18 15:47:53.155  1016  2905 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
03-18 15:47:53.155  1016  2905 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.155  1016  2905 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.155  1016  2905 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.155  1016  2905 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.165  3130  3130 E Zygote  : MountEmulatedStorage()
03-18 15:47:53.165  3130  3130 E Zygote  : v2
03-18 15:47:53.175  3130  3130 I libpersona: KNOX_SDCARD checking this for 10160
03-18 15:47:53.175  3130  3130 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:53.175  3130  3130 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-18 15:47:53.175  3130  3130 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-18 15:47:53.175  3130  3130 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:53.175  2368  3001 D Mms/MessagingNotification: remove alarm
03-18 15:47:53.175   310  1074 D AT_Distributor: Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
03-18 15:47:53.185  1016  2905 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3130 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
03-18 15:47:53.185  1016  1142 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
03-18 15:47:53.185  1016  1142 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
03-18 15:47:53.185  1016  1142 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:53.185  1016  1142 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:53.185  1016  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
03-18 15:47:53.195  2634  2634 D FactoryTestApp: [IPCWriterToSecPhoneService$handleMessage](2634) Send BOOTING COMPLETED done
03-18 15:47:53.195  1306  1306 I WifiCredService: onCreate
03-18 15:47:53.195  2368  3125 D Mms/MessagingNotification: updateAllHistoryAsRead()
03-18 15:47:53.205  3130  3130 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:53.205  3130  3130 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:53.235  1467  1479 D TP/SmsProvider: query,matched:0, calling pid = 2368
03-18 15:47:53.235  1467  1479 D TP/SmsProvider: match 0:Elapsed time : 2.172 ms
03-18 15:47:53.235  1306  1306 D WifiTimerReceiver: action: android.intent.action.BOOT_COMPLETED
03-18 15:47:53.235  1306  1306 D WifiTimerReceiver: extra: Bundle[mParcelledData.dataSize=84]
03-18 15:47:53.235  1306  1306 D MY_TAG  : Action boot completed received
03-18 15:47:53.235  2368  3068 D Mms/SmsReceiver: unregisterForServiceStateChanges, already unregistered
03-18 15:47:53.235  2368  3068 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-18 15:47:53.235  2368  3068 D Mms/TelephonyPermission: isDefault true
03-18 15:47:53.235  2368  3001 D Mms/MessagingNotification: [end]    nonBlockingUpdateMessageIndicator() consume time = 326.018281
03-18 15:47:53.245  1467  2280 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2368
03-18 15:47:53.245  3130  3130 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-18 15:47:53.255  1306  1306 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
03-18 15:47:53.255  1016  1143 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
03-18 15:47:53.265  1016  1143 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-18 15:47:53.265  1016  1143 E WifiNative-wlan0: invaild command id : 215
03-18 15:47:53.265  2993  2993 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 216.991ms
03-18 15:47:53.285   310  1074 D AT_Distributor: SetAtdStatus(), 1_1_0
03-18 15:47:53.285   310  1074 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
03-18 15:47:53.285  3105  3105 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
03-18 15:47:53.305  3105  3105 D DSM     : [Lines:107] Normal booted
03-18 15:47:53.305  3105  3105 D DSM     : [Lines:114] Boot completed
03-18 15:47:53.305   277  1009 D EnterpriseController: uids 10120
03-18 15:47:53.305   277  1009 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-18 15:47:53.305   277  1009 D Netd    : getNetworkForDns: using netid 502 for uid 10120
03-18 15:47:53.305  1016  1702 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.factorykeystring, hostingType: broadcast
03-18 15:47:53.305  1016  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.305  1016  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.305  1016  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.305  1016  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.345  3156  3156 E Zygote  : MountEmulatedStorage()
03-18 15:47:53.345  3156  3156 E Zygote  : v2
03-18 15:47:53.355  3156  3156 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:53.355  3156  3156 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:53.355  1016  1702 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3156 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-18 15:47:53.355  1016  1702 I ActivityManager: Killing 2354:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
03-18 15:47:53.355  3156  3156 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-18 15:47:53.365  3156  3156 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-18 15:47:53.365  3156  3156 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:53.385  3156  3156 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:53.385  3156  3156 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:53.385   305   305 I art     : Explicit concurrent mark sweep GC freed 8736(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 32.515ms
03-18 15:47:53.405   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 19.411ms
03-18 15:47:53.415  2658  2738 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
03-18 15:47:53.425   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 17.974ms
03-18 15:47:53.425  2658  2738 D BluetoothMediaBrowser: no now playing list
03-18 15:47:53.425  2658  2738 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
03-18 15:47:53.435  1306  1306 D NearbySettings: MountReceiver.onReceive - Create HandlerThread
03-18 15:47:53.435  1306  1306 D NearbySettings: MountReceiver.onReceive - Start HandlerThread
03-18 15:47:53.435  1306  1306 D NearbySettings: MountReceiver.onReceive - Create mPrefHandler
03-18 15:47:53.435  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
03-18 15:47:53.435  1016  1496 D SettingsProvider: name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
03-18 15:47:53.435  3141  3141 D AndroidRuntime: 
03-18 15:47:53.435  3141  3141 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-18 15:47:53.435  1306  3170 V NearbySettings: MountReceiver.mPrefHandler - 7002
03-18 15:47:53.435  3141  3141 D AndroidRuntime: CheckJNI is OFF
03-18 15:47:53.435  3141  3141 D AndroidRuntime: readGMSProperty: start
03-18 15:47:53.435  3141  3141 D AndroidRuntime: readGMSProperty: already setted!!
03-18 15:47:53.435  3141  3141 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-18 15:47:53.435  3141  3141 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-18 15:47:53.435  3141  3141 D AndroidRuntime: readGMSProperty: end
03-18 15:47:53.435  3141  3141 D AndroidRuntime: addProductProperty: start
03-18 15:47:53.445  3156  3156 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-18 15:47:53.455  3130  3130 D [0]UMC:UMCContentProvider: @onCreate
03-18 15:47:53.455  1467  2280 I art     : Explicit concurrent mark sweep GC freed 39944(2MB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 7MB/13MB, paused 962us total 157.229ms
03-18 15:47:53.465  3130  3130 D [0]UMC:Core: onCreate(): 
03-18 15:47:53.465  3130  3130 D [0]UMC:Core: @isManagedProfileUser
03-18 15:47:53.465  3130  3130 D [0]UMC:Core: userId: 0
03-18 15:47:53.465  3130  3130 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
03-18 15:47:53.465  3130  3130 D [0]UMC:Core: userInfo.isManagedProfile() : false
03-18 15:47:53.475  1467  2280 D TP/MmsSmsProvider: query,matched:200, calling pid = 2368
03-18 15:47:53.475  1467  2280 D TP/MmsSmsProvider: match 200:Elapsed time : 2.102 ms
03-18 15:47:53.485  1306  1306 I NearbySettings: MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
03-18 15:47:53.495  1306  1306 I NearbySettings: MountReceiver.onReceive - Internal Path
03-18 15:47:53.495  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-18 15:47:53.495  1016  2905 D SettingsProvider: name = personal_mode_enabled
03-18 15:47:53.495  3156  3156 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-18 15:47:53.505  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
03-18 15:47:53.505  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
03-18 15:47:53.515  3156  3156 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
03-18 15:47:53.525  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
03-18 15:47:53.535  3130  3130 D [0]UMC:DeviceInfo: USA==US==
03-18 15:47:53.545  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-18 15:47:53.545  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-18 15:47:53.545  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-18 15:47:53.545  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-18 15:47:53.545  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-18 15:47:53.545  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-18 15:47:53.545  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-18 15:47:53.545  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-18 15:47:53.545  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
03-18 15:47:53.545  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
03-18 15:47:53.545  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-18 15:47:53.545  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
03-18 15:47:53.545  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
03-18 15:47:53.545  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
03-18 15:47:53.545  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
03-18 15:47:53.545  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-18 15:47:53.545  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
03-18 15:47:53.545  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
03-18 15:47:53.545  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
03-18 15:47:53.545  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
03-18 15:47:53.545  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
03-18 15:47:53.545  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
03-18 15:47:53.555  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
03-18 15:47:53.555  1467  1467 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-18 15:47:53.555  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
03-18 15:47:53.555  1467  1467 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-18 15:47:53.555  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
03-18 15:47:53.555  1467  1467 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-18 15:47:53.555  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
03-18 15:47:53.555  1467  1467 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-18 15:47:53.555  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
03-18 15:47:53.555  1467  1467 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-18 15:47:53.555  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
03-18 15:47:53.555  1467  1467 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-18 15:47:53.555  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
03-18 15:47:53.555  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
03-18 15:47:53.555  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
03-18 15:47:53.555  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
03-18 15:47:53.555  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
03-18 15:47:53.555  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
03-18 15:47:53.555  3156  3156 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
03-18 15:47:53.555  3156  3156 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
03-18 15:47:53.555  1016  1229 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
03-18 15:47:53.565  1016  1229 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.565  1016  1229 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.565  1016  1229 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.565  1016  1229 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.575  3182  3182 E Zygote  : MountEmulatedStorage()
03-18 15:47:53.575  3182  3182 E Zygote  : v2
03-18 15:47:53.575  3182  3182 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:53.575  3182  3182 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:53.575  3182  3182 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-18 15:47:53.575  1016  1229 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3182 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-18 15:47:53.585  1016  1229 I ActivityManager: Killing 2387:com.sec.android.omc/1000 (adj 15): empty #31
03-18 15:47:53.585  3182  3182 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-18 15:47:53.585  3182  3182 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:53.605  1306  1306 I SmartcardBootCompleteReceiver: SmartcardBootCompleteReceiver - onReceive() 
03-18 15:47:53.605  1306  1306 I SmartcardBootCompleteReceiver: Received intent with action - android.intent.action.BOOT_COMPLETED
03-18 15:47:53.605  3141  3141 E AffinityControl: AffinityControl: registerfunction enter
03-18 15:47:53.615  3182  3182 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:53.615  3182  3182 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:53.615   314   314 I ServiceManager: Waiting for service AtCmdFwd...
03-18 15:47:53.615   298   298 E USB_UICC: Timeout! No signal received. Retry num = 30
03-18 15:47:53.625  1306  1306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
03-18 15:47:53.625  1306  1306 I SmartcardBootCompleteReceiver: Broadcast sent with current lockscreen type
03-18 15:47:53.635  3141  3141 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-18 15:47:53.645  1016  1041 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
03-18 15:47:53.645  1016  1041 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
03-18 15:47:53.645  1016  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2354/cgroup.procs: No such file or directory
03-18 15:47:53.655  1016  1097 V AlarmManager: waitForAlarm result :8
03-18 15:47:53.665  1016  1337 E PersonaManagerService: inState():  stateMachine is null !!
03-18 15:47:53.665  1016  1337 I PersonaManagerService: PersonaId don't exist
03-18 15:47:53.665  1016  1337 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-18 15:47:53.665  1016  1097 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-18 15:47:53.665  1016  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2387/cgroup.procs: No such file or directory
03-18 15:47:53.675  1016  1337 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-18 15:47:53.685  1016  1337 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-18 15:47:53.685  1016  1337 W ActivityManager: mDVFSHelper.acquire()
03-18 15:47:53.695  1016  1337 D FocusedStackFrame: Set to : 0
03-18 15:47:53.695  1488  1488 D Launcher.HomeView: onPause
03-18 15:47:53.695  1488  1488 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-18 15:47:53.695  1016  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-18 15:47:53.695  1016  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-18 15:47:53.705  1016  1337 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-18 15:47:53.705  1016  1337 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-18 15:47:53.705  1016  1337 D InputDispatcher: Focused application set to: xxxx
03-18 15:47:53.705  1016  1337 D InputDispatcher: Focus left window: 1488
03-18 15:47:53.705  1016  1496 I art     : Explicit concurrent mark sweep GC freed 138349(7MB) AllocSpace objects, 5(1829KB) LOS objects, 33% free, 26MB/40MB, paused 3.209ms total 207.931ms
03-18 15:47:53.705  3141  3141 D AndroidRuntime: Shutting down VM
03-18 15:47:53.715  1016  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-18 15:47:53.715  1016  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-18 15:47:53.715   257   257 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-18 15:47:53.725  1467  2280 D TP/SmsProvider: query,matched:0, calling pid = 2368
03-18 15:47:53.725  1467  2280 D TP/SmsProvider: match 0:Elapsed time : 2.136 ms
03-18 15:47:53.735   298   298 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-18 15:47:53.735   298   298 E USB_UICC: usb_uicc_init_qmi failed ! 
03-18 15:47:53.735   298   298 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
03-18 15:47:53.735   298   298 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
03-18 15:47:53.755  1306  1306 D [SBeam] : SBeamEnabler.initPreferenceForSbeam : 0
03-18 15:47:53.765  1016  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-18 15:47:53.765  1016  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-18 15:47:53.765  1016  1229 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.765  1016  1229 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.765  1016  1229 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.765  1016  1229 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.785  1188  1188 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-18 15:47:53.785  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-18 15:47:53.785  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-18 15:47:53.785  1016  1229 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3208 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-18 15:47:53.785  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-18 15:47:53.795  3208  3208 I libpersona: KNOX_SDCARD checking this for 10155
03-18 15:47:53.785  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-18 15:47:53.795  3208  3208 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:53.785  1188  1188 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-18 15:47:53.795  3208  3208 E Zygote  : MountEmulatedStorage()
03-18 15:47:53.795  3208  3208 E Zygote  : v2
03-18 15:47:53.795  3208  3208 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-18 15:47:53.805  3208  3208 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-18 15:47:53.805  3208  3208 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-18 15:47:53.815  1306  1306 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
03-18 15:47:53.815  1306  1306 I SettingSearch/SearchIntentReceiver: search setting db init!!
03-18 15:47:53.825  1016  2904 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.colorblind, hostingType: broadcast
03-18 15:47:53.825  1016  2904 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.825  1016  2904 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.825  1016  2904 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.825  1016  2904 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.835  1488  1488 V ActivityThread: updateVisibility : ActivityRecord{1f9794a1 token=android.os.BinderProxy@3a75ec93 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-18 15:47:53.835  1467  1484 D TP/SmsProvider: query,matched:51, calling pid = 2368
03-18 15:47:53.835  3221  3221 E Zygote  : MountEmulatedStorage()
03-18 15:47:53.835  3221  3221 E Zygote  : v2
03-18 15:47:53.835  3221  3221 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:53.835  3221  3221 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:53.835  3221  3221 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-18 15:47:53.835  1016  2904 I ActivityManager: Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3221 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-18 15:47:53.845  3221  3221 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-18 15:47:53.845  3221  3221 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:53.845  1306  1306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
03-18 15:47:53.845  1467  1484 D TP/SmsProvider: match 51:Elapsed time : 16.782 ms
03-18 15:47:53.855  3182  3182 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
03-18 15:47:53.865  1306  3236 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
03-18 15:47:53.865  3208  3208 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:53.865  3208  3208 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:53.875  1016  1700 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-18 15:47:53.875  1016  1700 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-18 15:47:53.875  1016  1700 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-18 15:47:53.875  1488  1488 D Launcher.HomeView: onStop
03-18 15:47:53.885  1488  1488 V ActivityThread: updateVisibility : ActivityRecord{1f9794a1 token=android.os.BinderProxy@3a75ec93 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-18 15:47:53.885  3221  3221 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:53.885  3221  3221 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:53.885  1016  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-18 15:47:53.895  1016  1700 D PersonaManager: isKioskContainerExistOnDevice
03-18 15:47:53.905  1016  1142 D ActivityManager: startProcessLocked calleePkgName: com.wssyncmldm, hostingType: broadcast
03-18 15:47:53.915  1016  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.915  1016  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.915  1016  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.915  1016  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.915  3130  3130 D USER_AGENT: UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
03-18 15:47:53.915  3141  3141 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-18 15:47:53.945  3241  3241 E Zygote  : MountEmulatedStorage(),
03-18 15:47:53.945  1016  1142 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3241 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-18 15:47:53.945  3241  3241 E Zygote  : v2
03-18 15:47:53.945  3241  3241 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:53.945  3241  3241 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-18 15:47:53.945  3241  3241 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:53.945  3241  3241 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-18 15:47:53.945  1016  1496 D ActivityManager: getContentProviderImpl callerProcessName:com.android.settings, calleePkgName: com.sec.providers.settingsearch
,03-18 15:47:53.945  3241  3241 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:53.945  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-18 15:47:53.945  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.945  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:53.945  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:53.965  3256  3256 E Zygote  : MountEmulatedStorage()
03-18 15:47:53.965  3256  3256 E Zygote  : v2
,03-18 15:47:53.965  3256  3256 I libpersona: KNOX_SDCARD checking this for 10150
03-18 15:47:53.965  3256  3256 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:53.975  3256  3256 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-18 15:47:53.975  3256  3256 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-18 15:47:53.975  1016  1496 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3256 uid=10150 gids={50150, 9997} abi=armeabi-v7a
03-18 15:47:53.975  3256  3256 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-18 15:47:53.985  3221  3221 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-18 15:47:53.985  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-18 15:47:53.985  3130  3130 D [0]UMC:AdminManager: init - start
,03-18 15:47:53.995  1016  1016 D SensorService: [SO] activate (ident=0xb8046058, enabled=0)
03-18 15:47:53.995  1016  1016 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-18 15:47:54.005  1016  1016 D SensorManager: unregisterListener ::   
,03-18 15:47:54.005  1016  1016 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-18 15:47:54.005  1016  1016 D SensorService: [SO] changed settle time [1]
,03-18 15:47:54.005  3241  3241 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:54.005  3241  3241 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:54.005  1016  1016 D SensorService: [SO] setDelay [66000000],
03-18 15:47:54.005  1016  1016 D SensorService: [SO] activate (ident=0xb8282398, enabled=1)
03-18 15:47:54.005  1016  1016 D SensorService: [SO] AR_init
03-18 15:47:54.005  1016  1016 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-18 15:47:54.015  3256  3256 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:54.015  3256  3256 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:54.015  2368  3068 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
,03-18 15:47:54.025  1016  1016 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-18 15:47:54.025  3241  3241 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-18 15:47:54.055  3208  3208 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-18 15:47:54.055  3130  3130 D [0]UMC:AdminManager: loadAdmins
,03-18 15:47:54.085   356   356 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,03-18 15:47:54.085  3130  3130 D [0]UMC:AdminManager: init - end
,03-18 15:47:54.095  1016  1039 D SensorService: [SO] currT = 36990093735, prevT = 36690090089, diff = 300003646, [0.134 0.402 10.113]
,03-18 15:47:54.095  1016  1039 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-18 15:47:54.095  3130  3130 D GSLBManager: migrateStoredUrlFromOldPref
,03-18 15:47:54.105  1571  1581 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge',
,03-18 15:47:54.105  3130  3130 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
03-18 15:47:54.105  3130  3130 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-18 15:47:54.105  3130  3130 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-18 15:47:54.115  3130  3130 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-18 15:47:54.115  3130  3130 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-18 15:47:54.115  3208  3208 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7009-7011)
03-18 15:47:54.115  3130  3130 D [0]UMC:UMCAdmin: isContainer : 0
03-18 15:47:54.115  3208  3208 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-18 15:47:54.115  1016  2904 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-18 15:47:54.115  3130  3130 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
03-18 15:47:54.115  3130  3130 D [0]UMC:UMCAdmin: isContainer : 0
,03-18 15:47:54.115  3130  3130 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-18 15:47:54.125  1016  2905 D ActivityManager: startProcessLocked calleePkgName: com.google.android.configupdater, hostingType: broadcast
,03-18 15:47:54.125  1016  2905 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:54.125  1016  2905 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.125  1016  2905 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.125  1016  2905 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:54.135  1488  1488 D Launcher: onTrimMemory. Level: 20
,03-18 15:47:54.145  3208  3208 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {311782de}
,03-18 15:47:54.145  3208  3208 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-18 15:47:54.145  3275  3275 E Zygote  : MountEmulatedStorage()
03-18 15:47:54.145  3275  3275 E Zygote  : v2
03-18 15:47:54.145  3275  3275 I libpersona: KNOX_SDCARD checking this for 10086
03-18 15:47:54.145  3208  3208 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
03-18 15:47:54.145  3275  3275 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:54.155  1016  2905 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3275 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
,03-18 15:47:54.155  3275  3275 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-18 15:47:54.155  3029  3098 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
03-18 15:47:54.155  3029  3098 I SecureStorage: [INFO]: SPID(0x00000004)Skip using SecureStorageExceptionJNI
,03-18 15:47:54.155  3275  3275 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-18 15:47:54.155  1016  2905 I ActivityManager: Killing 2417:com.sec.tcpdumpservice/1000 (adj 15): empty #31
03-18 15:47:54.155  3275  3275 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-18 15:47:54.155  1016  2904 D ActivityManager: startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
,03-18 15:47:54.155  1016  2904 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
03-18 15:47:54.155  1016  2904 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:54.155  1016  2904 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:54.155  1016  2904 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-18 15:47:54.165  1016  1039 D SensorService: [SO] currT = 37060598526, prevT = 36690090089, diff = 370508437, [0.134 0.402 10.132]
,03-18 15:47:54.165  1016  1039 D SensorService: [SO] 0.134 0.402 10.132
03-18 15:47:54.165  1016  1039 D SensorService: [SO] [100 -> 255]
,03-18 15:47:54.175  1571  1581 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-18 15:47:54.175  1571  1581 D BadgeProvider: sendNotify, [notify] : null
03-18 15:47:54.175  1571  1581 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-18 15:47:54.175  1571  1581 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-18 15:47:54.175  1571  1581 D BadgeProvider: update, [UpdateCount] : 1
,03-18 15:47:54.175  3130  3130 D [0]UMC:GuardService: @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
,03-18 15:47:54.175  3130  3130 D [0]UMC:CoreReceiver: Intent : android.intent.action.BOOT_COMPLETED
03-18 15:47:54.175  3130  3130 D [0]UMC:CoreReceiver:  check PreETag 
03-18 15:47:54.175  1016  1142 I ActivityManager: Killing 2431:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
03-18 15:47:54.185  2368  3068 D Mms/MessagingNotification: setBadgeCount(), count=0
03-18 15:47:54.185  3208  3208 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-18 15:47:54.185  3208  3208 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-18 15:47:54.185  3275  3275 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:54.195  3275  3275 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:54.195  3208  3208 E SysUtils: ApplicationContext is null in ApplicationStatus
03-18 15:47:54.205  2368  3292 D Mms/MessagingNotification: updateAllHistoryAsRead()
03-18 15:47:54.205  1488  1488 D Launcher.Model: reloadBadges entered.
,03-18 15:47:54.215  2368  3068 D Mms/MessagingNotification: remove alarm
,03-18 15:47:54.225  3130  3130 D [0]UMC:CoreReceiver: bulk enrolled package: null
,03-18 15:47:54.225  3208  3208 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,03-18 15:47:54.235  3208  3208 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
03-18 15:47:54.235  3208  3208 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,03-18 15:47:54.235  3130  3130 V [0]UMC:ProfileStorage: Enter loadList
03-18 15:47:54.235  3130  3130 D [0]UMC:CoreReceiver: handleAutoEnrollmentAndUMCAdminDeactivation
03-18 15:47:54.235  3130  3130 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-18 15:47:54.235  3208  3208 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-18 15:47:54.235  3208  3208 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-18 15:47:54.235  3208  3208 I Adreno-EGL: Build Date: 04/06/15 Mon
03-18 15:47:54.235  3208  3208 I Adreno-EGL: Local Branch: 
03-18 15:47:54.235  3208  3208 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-18 15:47:54.235  3208  3208 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-18 15:47:54.235  3208  3208 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-18 15:47:54.255  3130  3130 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
03-18 15:47:54.255  3182  3182 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-18 15:47:54.255  3130  3130 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-18 15:47:54.265  3130  3130 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-18 15:47:54.265  3130  3130 D [0]UMC:UMCAdmin: isContainer : 0
,03-18 15:47:54.265  1016  1496 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-18 15:47:54.265  3130  3130 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
03-18 15:47:54.265  3130  3130 D [0]UMC:UMCAdmin: isContainer : 0
,03-18 15:47:54.265  3130  3130 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-18 15:47:54.275  1467  1479 D TP/SmsProvider: query,matched:0, calling pid = 2368
,03-18 15:47:54.275  3241  3241 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,03-18 15:47:54.285  3182  3182 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-18 15:47:54.295  1467  1479 D TP/SmsProvider: match 0:Elapsed time : 19.909 ms
,03-18 15:47:54.305  3130  3130 D [0]UMC:ByodSetupStarter: Container ID : 0
,03-18 15:47:54.305  3182  3182 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,03-18 15:47:54.305  3182  3182 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
,03-18 15:47:54.305  3182  3182 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
,03-18 15:47:54.305  3182  3182 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-18 15:47:54.315  3130  3130 V [0]UMC:Utils: checkAppScreen() : com.test.thalitest
,03-18 15:47:54.315  3130  3130 I [0]UMC:Core: shutdown
,03-18 15:47:54.315  1016  1702 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,03-18 15:47:54.325  1016  1702 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:54.325  1016  1702 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:54.325  1016  1702 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-18 15:47:54.335  3130  3130 D [0]UMC:GuardService: @GuardService - stopService Result = true
,03-18 15:47:54.335  3130  3130 I art     : System.exit called, status: 0
,03-18 15:47:54.335  3130  3130 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,03-18 15:47:54.345  3275  3275 E UpdateRequestReceiver: ignoring update request
,03-18 15:47:54.345  2368  3068 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 1110.136353
,03-18 15:47:54.355  1016  1029 I ActivityManager: Killing 2339:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-18 15:47:54.365  3275  3275 E UpdateRequestReceiver: ignoring update request
,03-18 15:47:54.365   257  1038 I SurfaceFlinger: id=8 Removed Mauncher (5/8)
,03-18 15:47:54.365   257   439 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
,03-18 15:47:54.395  3241  3241 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,03-18 15:47:54.415  3208  3304 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,03-18 15:47:54.425  3275  3275 E UpdateRequestReceiver: ignoring update request
,03-18 15:47:54.425  1016  1702 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.policydm
,03-18 15:47:54.435  1016  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.435  1016  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.435  1016  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.435  1016  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:54.435  3275  3275 E UpdateRequestReceiver: ignoring update request
,03-18 15:47:54.445  3323  3323 E Zygote  : MountEmulatedStorage()
03-18 15:47:54.445  3323  3323 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:54.445  3323  3323 E Zygote  : v2
03-18 15:47:54.445  3323  3323 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:54.445  1016  1702 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3323 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-18 15:47:54.455  1016  2904 I ActivityManager: Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3130)(adj 0) has died(240,1056)
,03-18 15:47:54.455  3275  3275 E UpdateRequestReceiver: ignoring update request
,03-18 15:47:54.455  3241  3241 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,03-18 15:47:54.455  3323  3323 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-18 15:47:54.465  3241  3241 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
03-18 15:47:54.465  3323  3323 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-18 15:47:54.465  3323  3323 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:54.475  1016  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2417/cgroup.procs: No such file or directory
03-18 15:47:54.475  1016  1041 W libprocessgroup: failed to open /acct/uid_10131/pid_2431/cgroup.procs: No such file or directory
,03-18 15:47:54.475  1330  1330 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-18 15:47:54.475  1330  1330 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-18 15:47:54.475  1330  1330 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-18 15:47:54.475  3275  3275 E UpdateRequestReceiver: ignoring update request
,03-18 15:47:54.475  1016  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2339/cgroup.procs: No such file or directory
,03-18 15:47:54.475  1016  2904 D ActivityManager: startProcessLocked calleePkgName: com.dropbox.android, hostingType: broadcast
,03-18 15:47:54.475  1016  2904 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.475  1016  2904 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.475  1016  2904 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.475  1016  2904 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:54.495  1330  1330 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-18 15:47:54.495  3339  3339 E Zygote  : MountEmulatedStorage()
03-18 15:47:54.495  3339  3339 E Zygote  : v2
03-18 15:47:54.495  3339  3339 I libpersona: KNOX_SDCARD checking this for 10092
03-18 15:47:54.495  3339  3339 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:54.495  3339  3339 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-18 15:47:54.495  3208  3208 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,03-18 15:47:54.495  3339  3339 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-18 15:47:54.495  1016  2904 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3339 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-18 15:47:54.505  1330  1330 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo,
,03-18 15:47:54.505  3339  3339 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-18 15:47:54.515  1016  1496 I ActivityManager: Killing 2476:com.wsomacp/u0a25 (adj 15): empty #31
,03-18 15:47:54.525  1330  1330 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
03-18 15:47:54.525  1330  1330 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-18 15:47:54.525  1330  1330 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-18 15:47:54.525  1330  1330 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-18 15:47:54.525  1330  1330 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-18 15:47:54.525  1330  1330 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,03-18 15:47:54.525  1330  1330 D daemonapp: [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
03-18 15:47:54.525  3323  3323 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:54.525  3323  3323 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:54.535  3208  3208 W AwContents: onDetachedFromWindow called when already detached. Ignoring
03-18 15:47:54.535  1016  1028 D SettingsProvider: name = aw_daemon_service_key_version_check
03-18 15:47:54.535  1016  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-18 15:47:54.535  1016  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-18 15:47:54.535  1016  1028 D SettingsProvider: selectionArgs: false
03-18 15:47:54.535  1016  1028 D SettingsProvider: selectionArgs: 10162
03-18 15:47:54.535  1016  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-18 15:47:54.535  1016  1028 D SettingsProvider: ret = -1
,03-18 15:47:54.535  1016  1028 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10162
,03-18 15:47:54.545  3208  3208 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-18 15:47:54.545  3208  3208 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-18 15:47:54.545  3339  3339 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:54.545  3339  3339 D ActivityThread: Added TimaKeyStore provider
03-18 15:47:54.545  1330  1330 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-18 15:47:54.555  3208  3208 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-18 15:47:54.555  1330  1330 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-18 15:47:54.555  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-18 15:47:54.555  1330  1330 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-18 15:47:54.555  1330  1330 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-18 15:47:54.555  1330  1330 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-18 15:47:54.565  3208  3208 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-18 15:47:54.565  3208  3208 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-18 15:47:54.575  1330  1330 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-18 15:47:54.575  1330  1330 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-18 15:47:54.575  1330  1330 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-18 15:47:54.585  1330  1330 D daemonapp: [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1458312474586
,03-18 15:47:54.585  1330  1330 D daemonapp: [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1458334020000
03-18 15:47:54.585  1330  1330 D daemonapp: [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
,03-18 15:47:54.585  1330  1330 D daemonapp: [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,03-18 15:47:54.585  1330  1330 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458334020000
,03-18 15:47:54.595   287   287 E SMD     : DCD OFF
,03-18 15:47:54.605  1016  1041 W libprocessgroup: failed to open /acct/uid_10025/pid_2476/cgroup.procs: No such file or directory
,03-18 15:47:54.615   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,03-18 15:47:54.645  3208  3364 D OpenGLRenderer: Render dirty regions requested: true
,03-18 15:47:54.645  1016  1496 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-18 15:47:54.645  1016  1496 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-18 15:47:54.645  1016  1496 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-18 15:47:54.645  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-18 15:47:54.645  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,03-18 15:47:54.645  1016  1029 I ActivityManager: Killing 2501:com.sec.android.widgetapp.digitalclock/u0a88 (adj 15): empty #31
,03-18 15:47:54.655  3208  3208 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-18 15:47:54.655  3208  3208 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-18 15:47:54.655   257   257 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,03-18 15:47:54.675  1016  1700 D InputDispatcher: Focus entered window: 3208,
,03-18 15:47:54.685  1016  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-18 15:47:54.685  1016  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-18 15:47:54.685  3208  3208 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-18 15:47:54.685  3208  3364 I OpenGLRenderer: Initialized EGL, version 1.4
,03-18 15:47:54.695  3208  3364 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-18 15:47:54.695  3208  3364 D OpenGLRenderer: Enabling debug mode 0
,03-18 15:47:54.725  1016  2905 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-18 15:47:54.725  1188  1188 D PanelView: There is/are notification(s) 
,03-18 15:47:54.735  1016  3367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-18 15:47:54.735  1016  1049 I ActivityManager: Displayed Component not be shown by security: +972ms
,03-18 15:47:54.735  1016  1049 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@7
,03-18 15:47:54.735  1016  1049 W ActivityManager: mDVFSHelper.release()
03-18 15:47:54.735  3208  3208 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2fa74bcb time:37638
03-18 15:47:54.735  1016  1042 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-18 15:47:54.735  1016  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{10797d1d u0 com.test.thalitest/.MainActivity t12} time:37638
,03-18 15:47:54.745  1780  1780 I SamsungIME: getCurrentCandidateView
,03-18 15:47:54.745  1016  1700 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,03-18 15:47:54.755  1016  1700 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:54.755  1016  1700 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.755  1016  1700 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.755  1016  1700 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:54.755  1016  1041 W libprocessgroup: failed to open /acct/uid_10088/pid_2501/cgroup.procs: No such file or directory
,03-18 15:47:54.765  3323  3323 I DBG_POLICYDM: [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,03-18 15:47:54.765  3375  3375 E Zygote  : MountEmulatedStorage()
,03-18 15:47:54.765  3375  3375 E Zygote  : v2
03-18 15:47:54.765  3375  3375 I libpersona: KNOX_SDCARD checking this for 10009
03-18 15:47:54.765  3375  3375 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:54.765  3375  3375 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-18 15:47:54.765  3375  3375 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-18 15:47:54.775  3323  3323 I DBG_POLICYDM: [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-18 15:47:54.775  3375  3375 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-18 15:47:54.775  1016  1700 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3375 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-18 15:47:54.785  1330  1330 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 193
,03-18 15:47:54.785  1330  1330 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458334020000
,03-18 15:47:54.785  3323  3370 I DBG_POLICYDM: [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,03-18 15:47:54.785  3323  3323 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,03-18 15:47:54.795  1016  1337 E Tethering: No numeric data
,03-18 15:47:54.795  1016  1504 E Tethering: No numeric data
,03-18 15:47:54.795  3323  3323 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-18 15:47:54.795  3375  3375 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:54.805  1016  1337 E Tethering: No numeric data
,03-18 15:47:54.805  3375  3375 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:54.815  1016  1028 E Tethering: No numeric data
03-18 15:47:54.815  1016  1229 E Tethering: No numeric data
,03-18 15:47:54.825  1016  1337 E Tethering: No numeric data
,03-18 15:47:54.825  3323  3370 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,03-18 15:47:54.835  3323  3323 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-18 15:47:54.835  3323  3323 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-18 15:47:54.835  3323  3323 I DBG_POLICYDM: [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,03-18 15:47:54.835  3323  3323 I DBG_POLICYDM: [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,03-18 15:47:54.845  3323  3323 I DBG_POLICYDM: [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,03-18 15:47:54.935   257   432 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
,03-18 15:47:54.935   257  1038 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
,03-18 15:47:54.985  1330  1330 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
03-18 15:47:54.985  1330  1330 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-18 15:47:54.985  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.google.android.youtube, hostingType: broadcast
,03-18 15:47:54.985  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:54.985  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.985  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:54.985  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:54.995  1306  3236 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
,03-18 15:47:54.995  3241  3241 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,03-18 15:47:54.995  1306  3236 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
,03-18 15:47:54.995  3241  3241 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,03-18 15:47:54.995  3241  3241 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,03-18 15:47:55.005  3396  3396 E Zygote  : MountEmulatedStorage()
03-18 15:47:55.005  3396  3396 E Zygote  : v2
03-18 15:47:55.005  3396  3396 I libpersona: KNOX_SDCARD checking this for 10166
03-18 15:47:55.005  3396  3396 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:55.005  3396  3396 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-18 15:47:55.005  3396  3396 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-18 15:47:55.005  1016  1029 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3396 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-18 15:47:55.005  3396  3396 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-18 15:47:55.005  1016  1702 D ActivityManager: startService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm
03-18 15:47:55.005  1016  1702 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,03-18 15:47:55.005  1016  1702 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:55.005  1016  1702 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:55.005  1016  1702 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-18 15:47:55.015  3241  3241 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,03-18 15:47:55.015  3241  3241 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,03-18 15:47:55.015  3241  3241 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,03-18 15:47:55.015  1780  1780 D SamsungIME: Dismiss ExpandCandiate
,03-18 15:47:55.025  3029  3029 E BluetoothHeadset: BTStateChangeCB is registed
,03-18 15:47:55.025  3029  3029 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,03-18 15:47:55.025  1016  2905 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
03-18 15:47:55.025  1016  2905 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,03-18 15:47:55.025  1016  2905 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:55.025  1016  2905 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:55.025  1016  2905 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,03-18 15:47:55.025  1188  1188 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
03-18 15:47:55.025  1188  1188 D OverheatReceiver: into the SAFE_MODE_ACTION
03-18 15:47:55.025  1188  1188 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
,03-18 15:47:55.025  1188  1188 D OverheatReceiver: isSafeMode = false
,03-18 15:47:55.035  3029  3029 E BluetoothHeadset: BluetoothHeadset service is binded
,03-18 15:47:55.035  3029  3029 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,03-18 15:47:55.035  1016  1337 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,03-18 15:47:55.035  1016  1337 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,03-18 15:47:55.035  1016  1337 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:55.035  1016  1337 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:55.035  1016  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,03-18 15:47:55.035  1016  1016 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@11
,03-18 15:47:55.045  1467  1467 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
,03-18 15:47:55.045  1016  2905 D SettingsProvider: name = internet_call_settings_visibility
,03-18 15:47:55.045  1016  2905 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-18 15:47:55.045  1016  2905 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-18 15:47:55.045  1016  2905 D SettingsProvider: selectionArgs: false
03-18 15:47:55.045  1016  2905 D SettingsProvider: selectionArgs: 1001
,03-18 15:47:55.045  1016  2905 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-18 15:47:55.045  1016  2905 D SettingsProvider: ret = -1
,03-18 15:47:55.045  1467  1467 D PhoneUtilsCommon: isSupportVoLTE is false.
,03-18 15:47:55.065  3241  3241 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,03-18 15:47:55.065  3241  3241 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,03-18 15:47:55.065  3241  3241 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,03-18 15:47:55.065  3241  3241 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,03-18 15:47:55.065  3396  3396 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:55.065  3241  3241 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
03-18 15:47:55.065  3396  3396 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:55.065  1016  1700 E Tethering: No numeric data
,03-18 15:47:55.075  1436  1436 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,03-18 15:47:55.075  3323  3370 I DBG_POLICYDM: [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,03-18 15:47:55.075  1016  1343 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: android.telecom.InCallService
,03-18 15:47:55.075  1016  1343 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,03-18 15:47:55.085  1016  1343 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:55.085  1016  1343 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:55.085  1016  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-18 15:47:55.085  1016  1700 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: com.samsung.incallui.SEC_IN_CALL_SERVICE
03-18 15:47:55.085  1016  1700 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,03-18 15:47:55.085  1016  1700 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:55.085  1016  1229 E Tethering: No numeric data
03-18 15:47:55.085  1016  1700 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:55.085  1016  1700 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-18 15:47:55.085  1016  2905 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,03-18 15:47:55.085  1016  2904 E Tethering: No numeric data
,03-18 15:47:55.085  1016  2905 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:55.085  1016  2905 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:55.085  1016  2905 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:55.085  1016  2905 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-18 15:47:55.095  3241  3241 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,03-18 15:47:55.095  3241  3241 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
03-18 15:47:55.095  3241  3241 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
03-18 15:47:55.095  3241  3241 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
,03-18 15:47:55.105  3241  3316 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED,
,03-18 15:47:55.105  3415  3415 E Zygote  : MountEmulatedStorage()
03-18 15:47:55.105  3415  3415 I libpersona: KNOX_SDCARD checking this for 10057
03-18 15:47:55.105  3415  3415 E Zygote  : v2
03-18 15:47:55.105  3415  3415 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:55.115  1016  2905 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3415 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,03-18 15:47:55.115  3415  3415 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-18 15:47:55.115  3208  3208 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3208
,03-18 15:47:55.115  3415  3415 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-18 15:47:55.115  3415  3415 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-18 15:47:55.115  1016  1702 E Tethering: No numeric data
,03-18 15:47:55.125  1436  1436 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,03-18 15:47:55.145   305   305 I art     : Explicit concurrent mark sweep GC freed 8745(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.629ms total 27.575ms
,03-18 15:47:55.165  3415  3415 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:55.165   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 657us total 21.620ms
03-18 15:47:55.165  3415  3415 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:55.185   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 646us total 20.334ms
,03-18 15:47:55.185  1016  1337 D ActivityManager: startProcessLocked calleePkgName: com.fmm.dm, hostingType: broadcast
03-18 15:47:55.195  1016  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:55.195  1016  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:55.195  1016  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:55.195  1016  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:55.205  3431  3431 E Zygote  : MountEmulatedStorage()
,03-18 15:47:55.205  3431  3431 E Zygote  : v2
03-18 15:47:55.205  3431  3431 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:55.205  3431  3431 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:55.205  3431  3431 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-18 15:47:55.215  3431  3431 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-18 15:47:55.215  3431  3431 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:55.225  1016  1337 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3431 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-18 15:47:55.225  1016  1337 I ActivityManager: Killing 2585:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
03-18 15:47:55.225  1016  1337 I ActivityManager: Killing 2555:com.sec.android.app.camera/u0a139 (adj 15): empty #32,
03-18 15:47:55.225  1016  1337 I ActivityManager: Killing 2518:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #33
,03-18 15:47:55.225  1016  1496 V VibratorService: hasVibrator - useVibetonz: true
,03-18 15:47:55.225  3241  3241 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,03-18 15:47:55.235  3241  3316 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,03-18 15:47:55.255  3241  3316 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,03-18 15:47:55.255  1016  1702 D ActivityManager: bindService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm, action: null
03-18 15:47:55.255  1016  1702 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,03-18 15:47:55.255  1016  1702 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:55.255  1016  1702 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:55.255  1016  1702 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-18 15:47:55.265  1306  3236 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,03-18 15:47:55.285  3241  3241 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,03-18 15:47:55.285  3241  3241 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,03-18 15:47:55.295  3241  3241 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,03-18 15:47:55.295  3241  3241 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,03-18 15:47:55.295  1016  1700 D ActivityManager: startService callerProcessName:com.dropbox.android, calleePkgName: com.dropbox.android
03-18 15:47:55.295  1016  1700 D ActivityManager: retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,03-18 15:47:55.295  1016  1700 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:55.305  1016  1700 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-18 15:47:55.305  1016  1700 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-18 15:47:55.305  1016  1504 V VibratorService: hasVibrator - useVibetonz: true
,03-18 15:47:55.305  3431  3431 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:55.305  3431  3431 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:55.305  1016  1700 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:55.305  1016  1700 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:55.305  1016  1700 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:55.305  1016  1700 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:55.315  1016  1229 V VibratorService: hasVibrator - useVibetonz: true
,03-18 15:47:55.315  3241  3241 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
,03-18 15:47:55.325   282  1005 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
03-18 15:47:55.325   282  1005 D audio_hw_extn: audio_extn_get_parameters: returns 
03-18 15:47:55.325   282  1005 V msm8974_platform: platform_get_parameters: exit: returns - 
03-18 15:47:55.325   282  1005 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-18 15:47:55.325   282  1005 I str_params: key: 'call_forwarding' value: ''
03-18 15:47:55.325  1956  1956 V InCall  : ProximitySensor -  - screenonImmediately: false
03-18 15:47:55.325  1956  1956 V InCall  : ProximitySensor -  - mFromRcsShare: false
03-18 15:47:55.325  1956  1956 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,03-18 15:47:55.335  3447  3447 E Zygote  : MountEmulatedStorage(),
03-18 15:47:55.335  1306  3236 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-18 15:47:55.335  3447  3447 E Zygote  : v2
03-18 15:47:55.335  3447  3447 I libpersona: KNOX_SDCARD checking this for 10092
03-18 15:47:55.335  3447  3447 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-18 15:47:55.335  3447  3447 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:55.335  1016  1700 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3447 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-18 15:47:55.335  3447  3447 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-18 15:47:55.335  3447  3447 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-18 15:47:55.345  1956  1956 D ScoverManager: serviceVersion : 16908288
,03-18 15:47:55.345  1016  1028 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-18 15:47:55.345  1956  1956 D InCall  : InCallUtils - isCoverClosed false
,03-18 15:47:55.355  1016  1229 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-18 15:47:55.355  1436  1436 I Telecom : ProximitySensorManager: Proximity wake lock already released
03-18 15:47:55.355  1956  1956 D InCall  : InCallUtils - isCoverClosed false
03-18 15:47:55.355  1956  1956 I InCall  : InCallPresenter -  - InCallState = NO_CALLS
,03-18 15:47:55.365  1956  1956 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
,03-18 15:47:55.365  1956  1956 D InCall  : InCallPresenter -  - dismissCoverDialog()...
,03-18 15:47:55.375  1956  1956 I InCall  : CallSContextMotion - stopPutDownListening
,03-18 15:47:55.375  1956  1956 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,03-18 15:47:55.385  3447  3447 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:55.385  3447  3447 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:55.395  3208  3208 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-18 15:47:55.405  1188  1188 D PhoneStatusBarView: setCallBackground:0
,03-18 15:47:55.415  1016  2905 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-18 15:47:55.415  1956  1956 D InCall  : InCallUtils - isCoverClosed false
,03-18 15:47:55.455  1016  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2585/cgroup.procs: No such file or directory
03-18 15:47:55.455  1016  1041 W libprocessgroup: failed to open /acct/uid_10142/pid_2518/cgroup.procs: No such file or directory
03-18 15:47:55.455  1016  1041 W libprocessgroup: failed to open /acct/uid_10139/pid_2555/cgroup.procs: No such file or directory
,03-18 15:47:55.465  3241  3241 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-18 15:47:55.465  3241  3241 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,03-18 15:47:55.495  1016  2745 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.cB:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-18 15:47:55.515  3431  3431 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,03-18 15:47:55.585  1956  1956 D VideoCallManager: Instantiating VideoCallManager
,03-18 15:47:55.605  1956  1956 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-18 15:47:55.605  1956  1956 I GFX construct_block_size_descriptor_2d second part: took 2.781562ms for 0*0 texture 0
,03-18 15:47:55.605  3431  3431 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,03-18 15:47:55.615  3029  3029 D BluetoothA2dp: Proxy object connected
03-18 15:47:55.615  1956  1956 I GFX generate_partition_tables: took 5.875156ms for 0*0 texture 0
,03-18 15:47:55.615  3241  3316 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,03-18 15:47:55.615   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-18 15:47:55.625  1956  1956 I GFX raster: took 13.032396ms for 176*144 texture 0
03-18 15:47:55.625  1956  1956 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7c0ff50 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb7c1e2d0 counterpartCT=4 counterpartW=176 counterparth=144
,03-18 15:47:55.635  1956  1956 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,03-18 15:47:55.635  1956  1956 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-18 15:47:55.635  1956  1956 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-18 15:47:55.635  1956  1956 I Adreno-EGL: Build Date: 04/06/15 Mon
03-18 15:47:55.635  1956  1956 I Adreno-EGL: Local Branch: 
03-18 15:47:55.635  1956  1956 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-18 15:47:55.635  1956  1956 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-18 15:47:55.635  1956  1956 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-18 15:47:55.645  3431  3431 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-18 15:47:55.645  3431  3431 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-18 15:47:55.665  1956  1956 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-18 15:47:55.675  1956  1956 I glCompressedTexImage2D: took 0.338020ms for 320*61440 texture 37809
,03-18 15:47:55.685  1016  2904 D ActivityManager: getContentProviderImpl callerProcessName:com.fmm.dm, calleePkgName: com.sec.pcw.device
,03-18 15:47:55.685  1956  1956 I draw setup: took 11.420833ms for 320*240 texture 37809
03-18 15:47:55.685  1956  1956 E GFX GPU raster: drawn
,03-18 15:47:55.685  1956  1956 I GFX GPU raster ASTC: took 43.124583ms for 320*240 texture 12
03-18 15:47:55.685  1956  1956 I GFX raster: took 43.217604ms for 320*240 texture 0
03-18 15:47:55.685  1956  1956 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7c1d868 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb7c0fd68 counterpartCT=4 counterpartW=320 counterparth=240
,03-18 15:47:55.695  1016  2904 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:55.695  1016  2904 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:55.695  1016  2904 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:55.695  1016  2904 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:55.705  2171  2171 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
03-18 15:47:55.705  2171  2171 I dhcpcd  : wlan0: no IPv6 Routers available
,03-18 15:47:55.705  1956  1956 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-18 15:47:55.705  1956  1956 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-18 15:47:55.705  3323  3370 I DBG_POLICYDM: [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-18 15:47:55.705  1306  3236 D ScoverManager: serviceVersion : 16908288
,03-18 15:47:55.705  1956  1956 I glCompressedTexImage2D: took 0.438802ms for 480*122880 texture 37813
03-18 15:47:55.705  1956  1956 I draw setup: took 0.922291ms for 480*640 texture 37813
03-18 15:47:55.705  1956  1956 E GFX GPU raster: drawn
,03-18 15:47:55.715  3323  3370 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-18 15:47:55.715  3470  3470 E Zygote  : MountEmulatedStorage()
03-18 15:47:55.715  3470  3470 E Zygote  : v2
03-18 15:47:55.715  3470  3470 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:55.715  3470  3470 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:55.715  1956  1956 I GFX GPU raster ASTC: took 8.812865ms for 480*640 texture 12
03-18 15:47:55.715  3470  3470 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-18 15:47:55.715  1956  1956 I GFX raster: took 8.962084ms for 480*640 texture 0
03-18 15:47:55.715  1956  1956 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7c0fd68 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb7e4cf88 counterpartCT=4 counterpartW=480 counterparth=640
,03-18 15:47:55.715  3470  3470 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-18 15:47:55.715  3470  3470 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:55.735  1016  2904 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3470 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-18 15:47:55.735  1780  1780 I SamsungIME: getDebugLevel  : 0x4f4c
,03-18 15:47:55.775  3208  3388 D jxcore_app_log: JniHelper::setJavaVM(0xb7837450), pthread_self() = -1210454288,
,03-18 15:47:55.785  3208  3388 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-18 15:47:55.785  3208  3388 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-18 15:47:55.785  3208  3388 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-18 15:47:55.785  3208  3388 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-18 15:47:55.785  3208  3388 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,03-18 15:47:55.785  3208  3388 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@236ca116 added. We now have 1 listener(s)
,03-18 15:47:55.785  3470  3470 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:55.785  3470  3470 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:55.795  3208  3388 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,03-18 15:47:55.805  3208  3388 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,03-18 15:47:55.805  1956  1956 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,03-18 15:47:55.815  1956  1956 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-18 15:47:55.815  3208  3388 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,03-18 15:47:55.815  1956  1956 I glCompressedTexImage2D: took 0.439062ms for 440*116864 texture 37809
03-18 15:47:55.815  1956  1956 I draw setup: took 0.956406ms for 440*330 texture 37809
03-18 15:47:55.815  1956  1956 E GFX GPU raster: drawn
,03-18 15:47:55.815  3208  3388 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-18 15:47:55.815  1956  1956 I GFX GPU raster ASTC: took 5.434582ms for 440*330 texture 12
03-18 15:47:55.815  1956  1956 I GFX raster: took 5.538905ms for 440*330 texture 0
03-18 15:47:55.815  1956  1956 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7e610a8 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb7e613d0 counterpartCT=4 counterpartW=440 counterparth=330
,03-18 15:47:55.835  3208  3388 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-18 15:47:55.835  3208  3388 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-18 15:47:55.835  3208  3388 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-18 15:47:55.835  3208  3388 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
03-18 15:47:55.835  3208  3388 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-18 15:47:55.835  3208  3388 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-18 15:47:55.835  3208  3388 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-18 15:47:55.835  3208  3388 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-18 15:47:55.835  3208  3388 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-18 15:47:55.835  3208  3388 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-18 15:47:55.835  3208  3388 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-18 15:47:55.835  3208  3388 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20dc346d added. We now have 1 listener(s)
,03-18 15:47:55.835  3208  3388 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-18 15:47:55.835  3208  3388 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-18 15:47:55.835  3208  3388 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,03-18 15:47:55.845  3208  3388 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-18 15:47:55.845  3208  3388 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-18 15:47:55.845  3208  3388 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-18 15:47:55.845  3208  3388 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-18 15:47:55.845  3208  3388 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,03-18 15:47:55.855  3208  3388 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-18 15:47:55.855  3208  3388 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-18 15:47:55.855  3208  3388 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-18 15:47:55.855  3208  3388 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-18 15:47:55.855  3208  3388 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-18 15:47:55.855  3208  3388 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-18 15:47:55.855  3208  3388 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-18 15:47:55.855  3208  3388 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-18 15:47:55.855  3208  3388 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-18 15:47:55.855  3208  3388 D io.jxcore.node.ConnectivityMonitor: start: OK
03-18 15:47:55.855  3339  3339 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
,03-18 15:47:55.855  3208  3388 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-18 15:47:55.875  3323  3370 I DBG_POLICYDM: [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,03-18 15:47:55.895  3323  3370 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,03-18 15:47:55.925  3323  3370 I DBG_POLICYDM: [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,03-18 15:47:55.935  1956  1956 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-18 15:47:55.935  1956  1956 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-18 15:47:55.935  1956  1956 I glCompressedTexImage2D: took 0.608073ms for 480*163840 texture 37811
03-18 15:47:55.935  1956  1956 I draw setup: took 0.986927ms for 480*640 texture 37811
03-18 15:47:55.935  1956  1956 E GFX GPU raster: drawn
,03-18 15:47:55.945  1956  1956 I GFX GPU raster ASTC: took 6.605417ms for 480*640 texture 12
03-18 15:47:55.945  1956  1956 I GFX raster: took 6.685834ms for 480*640 texture 0
03-18 15:47:55.945  1956  1956 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7e75e60 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb7e51560 counterpartCT=4 counterpartW=480 counterparth=640
,03-18 15:47:55.955  1016  1029 I art     : Explicit concurrent mark sweep GC freed 21935(1109KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 26MB/40MB, paused 12.259ms total 185.252ms
,03-18 15:47:55.955  3470  3470 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-18 15:47:55.955  1016  1028 I ActivityManager: Killing 2601:com.android.calendar/u0a135 (adj 15): empty #31
03-18 15:47:55.955  3470  3470 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-18 15:47:55.985  3470  3470 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-18 15:47:56.025  1956  1956 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-18 15:47:56.025  1956  1956 I GFX construct_block_size_descriptor_2d second part: took 2.552239ms for 0*0 texture 0
03-18 15:47:56.025  3323  3370 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,03-18 15:47:56.045  3470  3482 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-18 15:47:56.055  1956  1956 I GFX generate_partition_tables: took 7.919946ms for 0*0 texture 0
,03-18 15:47:56.055  1956  1956 I GFX raster: took 12.731613ms for 176*144 texture 0
03-18 15:47:56.055  1956  1956 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7e4a828 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb7e4a928 counterpartCT=4 counterpartW=176 counterparth=144
,03-18 15:47:56.065  3339  3339 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,03-18 15:47:56.075  1956  1956 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-18 15:47:56.075  3323  3370 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-18 15:47:56.075  1956  1956 I GFX construct_block_size_descriptor_2d second part: took 2.488333ms for 0*0 texture 0
,03-18 15:47:56.075  1016  1041 W libprocessgroup: failed to open /acct/uid_10135/pid_2601/cgroup.procs: No such file or directory
,03-18 15:47:56.085  3208  3208 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-18 15:47:56.095  3208  3208 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-18 15:47:56.095  3208  3208 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-18 15:47:56.095  1956  1956 I GFX generate_partition_tables: took 6.276771ms for 0*0 texture 0
,03-18 15:47:56.095  1956  1956 I GFX raster: took 11.028334ms for 176*144 texture 0
03-18 15:47:56.095  1956  1956 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7e4a710 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb7e4cf88 counterpartCT=4 counterpartW=176 counterparth=144
,03-18 15:47:56.105  3431  3431 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-18 15:47:56.105  1016  2849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-18 15:47:56.105  1956  1956 D ScoverManager: registerListener
,03-18 15:47:56.105  3431  3431 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
03-18 15:47:56.105  3431  3431 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-18 15:47:56.105  1016  2905 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-18 15:47:56.105  1016  1504 D ActivityManager: startProcessLocked calleePkgName: com.fmm.ds, hostingType: broadcast
,03-18 15:47:56.105  1016  1337 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-18 15:47:56.105  1016  1337 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@1bac62c8, pid : 1956, uid : 1001, type : 1
03-18 15:47:56.105  1016  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:56.115  1016  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:56.115  1016  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:56.115  1016  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:56.115  3323  3370 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-18 15:47:56.115  3323  3371 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
03-18 15:47:56.115  3323  3370 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,03-18 15:47:56.115  3323  3370 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,03-18 15:47:56.135  3492  3492 E Zygote  : MountEmulatedStorage()
03-18 15:47:56.135  3492  3492 E Zygote  : v2
03-18 15:47:56.135  3492  3492 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:56.135  3492  3492 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:56.135  3492  3492 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-18 15:47:56.135  3492  3492 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-18 15:47:56.135  3492  3492 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:56.135  1016  1504 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3492 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-18 15:47:56.145  3339  3339 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,03-18 15:47:56.145  1016  1504 I ActivityManager: Killing 2746:com.android.email/u0a145 (adj 15): empty #31
,03-18 15:47:56.145  1016  1504 I ActivityManager: Killing 2675:com.android.keychain/1000 (adj 15): empty #32
,03-18 15:47:56.155  1780  1780 I SamsungIME: getDebugLevel  : 0x4f4c
,03-18 15:47:56.155  3339  3339 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,03-18 15:47:56.165  3339  3339 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,03-18 15:47:56.165  2634  3129 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3129)  
,03-18 15:47:56.185  3492  3492 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:56.185  3492  3492 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:56.185  1780  1780 I SamsungIME: KeybaordView init() : load resources
,03-18 15:47:56.195  1016  1700 I ActivityManager: Killing 2494:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
03-18 15:47:56.195  3323  3371 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-18 15:47:56.195  1956  1956 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-18 15:47:56.205  3323  3370 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/03/18/16:12:11
,03-18 15:47:56.205  1016  1504 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,03-18 15:47:56.205  3323  3370 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/03/18/15:47:56
,03-18 15:47:56.205  1016  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:56.205  1016  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:56.205  1016  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:56.205  1016  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:56.205  3323  3370 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,03-18 15:47:56.255  3510  3510 E Zygote  : MountEmulatedStorage()
03-18 15:47:56.255  3510  3510 E Zygote  : v2
03-18 15:47:56.255  3510  3510 I libpersona: KNOX_SDCARD checking this for 10015
03-18 15:47:56.255  3510  3510 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:56.255  3339  3339 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
03-18 15:47:56.255  3510  3510 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-18 15:47:56.255  3510  3510 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-18 15:47:56.255  1016  1504 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3510 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
03-18 15:47:56.255  3510  3510 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-18 15:47:56.265  3339  3339 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,03-18 15:47:56.295  3323  3370 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,03-18 15:47:56.295  3323  3371 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-18 15:47:56.305  3323  3371 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-18 15:47:56.305  3323  3371 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-18 15:47:56.305  3323  3371 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-18 15:47:56.305  3323  3371 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-18 15:47:56.305  3323  3371 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,03-18 15:47:56.315  1016  1702 D LocationManagerService: getProviders()=[passive]
03-18 15:47:56.315  3396  3467 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-18 15:47:56.315  3396  3467 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-18 15:47:56.365  3510  3510 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:56.365  3510  3510 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:56.395  3323  3371 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,03-18 15:47:56.395  3323  3371 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-18 15:47:56.395  3492  3492 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-18 15:47:56.405  3323  3370 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,03-18 15:47:56.415  1780  1780 I SamsungIME: getCurrentKeyboard
03-18 15:47:56.415  1780  1780 I SamsungIME: getTextKeyboard
,03-18 15:47:56.415  3492  3492 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-18 15:47:56.435  1016  1041 E libprocessgroup: failed to kill 1 processes for processgroup 2746
,03-18 15:47:56.435  1016  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2675/cgroup.procs: No such file or directory
03-18 15:47:56.435  1016  1041 W libprocessgroup: failed to open /acct/uid_10044/pid_2494/cgroup.procs: No such file or directory
,03-18 15:47:56.475  3339  3339 I com.dropbox.sync.android.a: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,03-18 15:47:56.495  3241  3316 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,03-18 15:47:56.505  3323  3371 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-18 15:47:56.505  1780  1780 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-18 15:47:56.515  3470  3482 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-18 15:47:56.515  1306  3236 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-18 15:47:56.535  3396  3467 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
03-18 15:47:56.535  1306  3236 D Settings_Utils: isSupportVNFestival SM-A500FU XEO
,03-18 15:47:56.555  3492  3492 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-18 15:47:56.565  3492  3492 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-18 15:47:56.575  3241  3316 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-18 15:47:56.605  3339  3339 I com.dropbox.sync.android.ad: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
,03-18 15:47:56.635  3396  3467 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-18 15:47:56.635  3396  3467 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@356d7bc6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-18 15:47:56.635  3396  3467 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-18 15:47:56.645  1016  1142 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-18 15:47:56.645  1016  1142 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:56.645  1016  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-18 15:47:56.645  1016  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-18 15:47:56.665  3241  3316 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,03-18 15:47:56.665  3241  3316 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,03-18 15:47:56.665  3323  3371 I DBG_POLICYDM: [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,03-18 15:47:56.725  3323  3370 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,03-18 15:47:56.755  3323  3370 I DBG_POLICYDM: [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-18 15:47:56.795  1016  2905 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-18 15:47:56.805  1016  2905 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:56.805  1016  2905 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-18 15:47:56.805  1016  2905 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-18 15:47:56.845  1016  1702 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,03-18 15:47:56.845  1016  1702 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,03-18 15:47:56.845  1016  1702 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:56.845  1016  1702 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-18 15:47:56.845  1016  1702 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-18 15:47:56.875  3208  3489 W jxcore-log: Initializing JXcore engine
03-18 15:47:56.875  3208  3489 W jxcore-log: JXcore engine is ready
,03-18 15:47:56.905  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,03-18 15:47:56.905  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:56.905  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:56.905  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:56.905  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:56.915  3552  3552 E Zygote  : MountEmulatedStorage(),
03-18 15:47:56.915  3552  3552 E Zygote  : v2
03-18 15:47:56.915  3552  3552 I libpersona: KNOX_SDCARD checking this for 10003,
03-18 15:47:56.915  3552  3552 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:56.925  3552  3552 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-18 15:47:56.925  1016  1016 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3552 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,03-18 15:47:56.925  3552  3552 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-18 15:47:56.935  3552  3552 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-18 15:47:56.955  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,03-18 15:47:56.955  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:56.955  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:56.955  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:56.955  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:56.965  3562  3562 E Zygote  : MountEmulatedStorage(),
03-18 15:47:56.965  3562  3562 I libpersona: KNOX_SDCARD checking this for 10094
03-18 15:47:56.965  3562  3562 E Zygote  : v2
03-18 15:47:56.965  3562  3562 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:56.965  3562  3562 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-18 15:47:56.965  3562  3562 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-18 15:47:56.975  3562  3562 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:56.975  1016  1028 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3562 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,03-18 15:47:56.985  1868  1868 E audit   : type=1400 msg=audit(1458312476.985:205): avc:  denied  { ioctl } for  pid=3489 comm="Thread-423" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-18 15:47:56.985  1868  1868 E audit   :  SEPF_SM-A500FU_5.0.2-1_0038
03-18 15:47:56.985  1868  1868 E audit   : type=1300 msg=audit(1458312476.985:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=4 a3=9bfbe8f8 items=0 ppid=305 ppcomm=main pid=3489 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-423" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
,03-18 15:47:56.985  1868  1868 E audit   : type=1320 msg=audit(1458312476.985:205): 
,03-18 15:47:56.995  1016  1028 I ActivityManager: Killing 2764:com.samsung.android.sm/1000 (adj 15): empty #31
,03-18 15:47:57.005  3552  3552 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:57.005  3552  3552 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:57.005  3208  3489 W jxcore-log: Starting JXcore engine
,03-18 15:47:57.015  3562  3562 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:57.015  3562  3562 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:57.025  3492  3492 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,03-18 15:47:57.055  3492  3492 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-18 15:47:57.055  3492  3492 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-18 15:47:57.055  3492  3492 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-18 15:47:57.055  3492  3492 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-18 15:47:57.065  3492  3492 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,03-18 15:47:57.065  3492  3492 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,03-18 15:47:57.075  1016  1496 I ActivityManager: Killing 2873:flipboard.boxer.app/u0a99 (adj 15): empty #31
,03-18 15:47:57.115  3375  3375 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-18 15:47:57.115  3375  3375 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-18 15:47:57.125  3375  3375 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-18 15:47:57.125  3562  3562 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-18 15:47:57.135  3562  3562 D elm:15183: ELMEngine.ELMEngine( context ).
,03-18 15:47:57.135  3562  3562 D elm:15183: MDMBridge.setEnterpriseBridge()
,03-18 15:47:57.135  1016  1337 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,03-18 15:47:57.135  1016  1337 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,03-18 15:47:57.145  1016  1337 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:57.145  1016  1337 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:57.145  1016  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-18 15:47:57.145  3562  3562 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-18 15:47:57.155  1427  1427 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,03-18 15:47:57.155  3562  3562 D elm:15183: ElmAgentService : onCreate()
,03-18 15:47:57.165  3208  3489 W jxcore-log: Platform android
03-18 15:47:57.165  3208  3489 W jxcore-log: 
,03-18 15:47:57.165  3208  3489 W jxcore-log: Process ARCH arm
03-18 15:47:57.165  3208  3489 W jxcore-log: 
,03-18 15:47:57.165  3562  3591 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,03-18 15:47:57.165  3375  3375 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-18 15:47:57.165  3552  3552 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-18 15:47:57.165  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.google.android.onetimeinitializer, hostingType: broadcast
,03-18 15:47:57.175  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.175  3562  3562 D elm:15183: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,03-18 15:47:57.175  3562  3562 D elm:15183: BootCompletedState : startBootCompleted() call
03-18 15:47:57.175  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.175  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.175  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.185  3593  3593 E Zygote  : MountEmulatedStorage(),
,03-18 15:47:57.185  3593  3593 E Zygote  : v2
03-18 15:47:57.185  3593  3593 I libpersona: KNOX_SDCARD checking this for 10014
03-18 15:47:57.185  3593  3593 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:57.185  3593  3593 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-18 15:47:57.185  1016  1028 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3593 uid=10014 gids={50014, 9997} abi=armeabi-v7a,
,03-18 15:47:57.195  1016  1028 I ActivityManager: Killing 2237:flipboard.app/u0a98 (adj 15): empty #31
,03-18 15:47:57.195  3593  3593 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-18 15:47:57.195  3593  3593 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-18 15:47:57.215  1427  1427 V EmergencyMode: [EmergencyBase] setBootTime
03-18 15:47:57.215  1427  1427 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
,03-18 15:47:57.215  1016  1343 D ActivityManager: startProcessLocked calleePkgName: com.sec.factory.camera, hostingType: broadcast
,03-18 15:47:57.215  1016  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.215  1016  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.215  1016  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.215  1016  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.225  3593  3593 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:57.225  3593  3593 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:57.235  3608  3608 E Zygote  : MountEmulatedStorage(),
03-18 15:47:57.235  3608  3608 E Zygote  : v2
03-18 15:47:57.235  3608  3608 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:57.235  1016  1343 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3608 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
03-18 15:47:57.235  3608  3608 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:57.235  3608  3608 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-18 15:47:57.245  3562  3562 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK(),
,03-18 15:47:57.245  3562  3562 I elm:15183: Get License : 0,
03-18 15:47:57.245  3562  3562 D elm:15183: ElmAgentService : onDestroy().
03-18 15:47:57.245  1016  1343 I ActivityManager: Killing 2909:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31,
,03-18 15:47:57.245  3608  3608 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-18 15:47:57.245  3608  3608 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:57.265  3552  3552 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-18 15:47:57.275  3552  3552 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-18 15:47:57.275  3552  3552 D UserAnalysis: Create SecureDbHelper
,03-18 15:47:57.285  3608  3608 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:57.285  3608  3608 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:57.295  3552  3552 D IntelligenceServiceApplication: onCreate()
,03-18 15:47:57.295  3552  3552 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,03-18 15:47:57.295  1016  1142 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,03-18 15:47:57.305  1016  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.305  1016  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.305  1016  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.305  1016  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.315  3323  3371 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-18 15:47:57.325  3624  3624 E Zygote  : MountEmulatedStorage()
,03-18 15:47:57.325  3624  3624 E Zygote  : v2,
03-18 15:47:57.325  1016  1142 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3624 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-18 15:47:57.325  3624  3624 I libpersona: KNOX_SDCARD checking this for 10060
03-18 15:47:57.325  3624  3624 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:57.325  1016  1142 I ActivityManager: Killing 2929:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31,
,03-18 15:47:57.325  3624  3624 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-18 15:47:57.335  3624  3624 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-18 15:47:57.335  3624  3624 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:57.365  3552  3552 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-18 15:47:57.375  3624  3624 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:57.375  3624  3624 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:57.395  2658  2720 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-18 15:47:57.395  1016  1229 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,03-18 15:47:57.395  3552  3552 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-18 15:47:57.435  3208  3489 I jxcore-log: JXcore Cordova bridge is ready!
03-18 15:47:57.435  3208  3489 I jxcore-log: 
,03-18 15:47:57.435  3208  3489 W jxcore-log: JXcore engine is started
,03-18 15:47:57.445  3208  3388 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-18 15:47:57.445  3208  3208 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-18 15:47:57.455  3608  3608 I CameraApp: CameraApp.onCreate()... mFeature : null
,03-18 15:47:57.455  3608  3608 I testFeature: Feature.Feature(context)
,03-18 15:47:57.455  3608  3608 I testFeature: Feature.readInternalDefaultXml()
03-18 15:47:57.455  3608  3608 I testFeature: ResetFeatureValue
,03-18 15:47:57.455  3208  3489 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-18 15:47:57.455  3208  3489 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-18 15:47:57.455  3608  3608 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
03-18 15:47:57.455  3608  3608 I CameraApp: CameraApp.getAppFeature()...
,03-18 15:47:57.455  1016  1504 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,03-18 15:47:57.465  1016  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.465  1016  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.465  1016  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.465  1016  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.465  3593  3593 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
,03-18 15:47:57.475  3208  3208 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,03-18 15:47:57.475  3208  3208 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-18 15:47:57.475  3323  3371 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
03-18 15:47:57.475  3641  3641 E Zygote  : MountEmulatedStorage()
03-18 15:47:57.475  3641  3641 I libpersona: KNOX_SDCARD checking this for 10100
03-18 15:47:57.475  3641  3641 E Zygote  : v2
03-18 15:47:57.475  3641  3641 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:57.475  3641  3641 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-18 15:47:57.485  3641  3641 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-18 15:47:57.485  1016  1504 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3641 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
03-18 15:47:57.485  3641  3641 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:57.485  3339  3560 I System.out: Thread-440(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
03-18 15:47:57.485  1016  1504 I ActivityManager: Killing 2399:com.sec.modem.settings/1000 (adj 15): empty #31
03-18 15:47:57.485  3339  3560 I System.out: Thread-440(ApacheHTTPLog):isSBSettingEnabled false
03-18 15:47:57.485  1016  1702 D FocusedStackFrame: Set to : 0
03-18 15:47:57.485  3339  3560 I System.out: Thread-440(ApacheHTTPLog):isShipBuild true
03-18 15:47:57.485  3339  3560 I System.out: Thread-440(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-18 15:47:57.485  1016  1702 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-18 15:47:57.485  3339  3560 I System.out: Thread-440(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-18 15:47:57.485  1016  1702 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-18 15:47:57.485  1016  1702 D InputDispatcher: Focused application set to: xxxx
,03-18 15:47:57.485  1016  1702 D InputDispatcher: Focus left window: 3208
,03-18 15:47:57.495   277  1009 D EnterpriseController: uids 10092
03-18 15:47:57.495   277  1009 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-18 15:47:57.495   277  1009 D Netd    : getNetworkForDns: using netid 502 for uid 10092
03-18 15:47:57.495  3415  3542 W art     : Verification of void com.google.android.apps.gsa.extradex.attemptedsearchhistory.i.run() took 356.062ms
03-18 15:47:57.495  3552  3552 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-18 15:47:57.495  1016  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-18 15:47:57.495  1016  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-18 15:47:57.505   257   432 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (151 us)
,03-18 15:47:57.505  3552  3552 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
,03-18 15:47:57.515   305   305 I art     : Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 652us total 27.349ms
,03-18 15:47:57.525  3641  3641 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:57.525  3641  3641 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:57.525   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 17.256ms
,03-18 15:47:57.535  3208  3208 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,03-18 15:47:57.535  1016  1028 D ActivityManager: startService callerProcessName:com.google.android.onetimeinitializer, calleePkgName: com.google.android.onetimeinitializer
03-18 15:47:57.535  3208  3208 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
03-18 15:47:57.535  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
03-18 15:47:57.535  3208  3388 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 64ms. Plugin should use CordovaInterface.getThreadPool().
03-18 15:47:57.555  1016  1029 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-18 15:47:57.545  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:57.555  1016  1029 W ActivityManager: mDVFSHelper.acquire()
03-18 15:47:57.545  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-18 15:47:57.545  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
03-18 15:47:57.545   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 18.370ms
,03-18 15:47:57.565  1016  1029 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-18 15:47:57.565  1016  1029 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-18 15:47:57.565  1016  1029 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-18 15:47:57.565  1488  1488 D Launcher: onRestart, Launcher: 940895978
,03-18 15:47:57.575  3593  3661 V OneTimeService: OneTimeService.onHandleIntent
,03-18 15:47:57.605   287   287 E SMD     : DCD OFF
,03-18 15:47:57.605  3415  3542 W art     : Verification of void com.google.android.apps.gsa.extradex.attemptedsearchhistory.a.vQ() took 107.930ms
,03-18 15:47:57.615  1488  1488 D Launcher: onStart, Launcher: 940895978
03-18 15:47:57.615  1488  1488 D Launcher.HomeView: onStart
,03-18 15:47:57.615  1488  1488 D Launcher: onResume, Launcher: 940895978
,03-18 15:47:57.615  1016  1700 D SettingsProvider: name = kids_home_mode
,03-18 15:47:57.615  1016  1700 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-18 15:47:57.615  1016  1700 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-18 15:47:57.615  1016  1700 D SettingsProvider: selectionArgs: false
03-18 15:47:57.615  1016  1700 D SettingsProvider: selectionArgs: 10007
03-18 15:47:57.615  1016  1700 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-18 15:47:57.615  1016  1700 D SettingsProvider: ret = -1
,03-18 15:47:57.615  1488  1488 D Launcher.HomeView: onResume
,03-18 15:47:57.625  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-18 15:47:57.625  1016  1016 D SensorService: [SO] activate (ident=0xb8282398, enabled=0)
03-18 15:47:57.625  1016  1016 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-18 15:47:57.635  3624  3624 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.8.KK_APP
,03-18 15:47:57.635  1488  1488 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-18 15:47:57.645  1016  1337 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-18 15:47:57.645  1016  1337 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,03-18 15:47:57.645  1016  1016 D SensorManager: unregisterListener ::   
,03-18 15:47:57.645  1016  1016 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-18 15:47:57.645  1016  1337 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:57.645  1016  1337 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-18 15:47:57.645  1016  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-18 15:47:57.645  1016  1016 D SensorService: [SO] changed settle time [0]
03-18 15:47:57.645  1016  1016 D SensorService: [SO] setDelay [200000000]
03-18 15:47:57.645  1016  1016 D SensorService: [SO] activate (ident=0xb8282398, enabled=1)
03-18 15:47:57.645  1016  1016 D SensorService: [SO] AR_init
03-18 15:47:57.645  1016  1016 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-18 15:47:57.645  1488  1488 D MenuAppsGridFragment: onResume
,03-18 15:47:57.655  1016  2905 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-18 15:47:57.655  1016  2905 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,03-18 15:47:57.655  1016  2905 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:57.655  1016  2905 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-18 15:47:57.655  1016  2905 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-18 15:47:57.655  1016  1702 D ActivityManager: handle home activity for 0
,03-18 15:47:57.655  1016  1702 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,03-18 15:47:57.655  1016  1016 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,03-18 15:47:57.655  1016  1016 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
,03-18 15:47:57.655  1016  1702 D KnoxTimeoutHandler: post home show event for user 0
,03-18 15:47:57.655  1016  1016 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
,03-18 15:47:57.655  1016  1702 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-18 15:47:57.655  1016  1702 D KnoxTimeoutHandler: postActiveUserChange for user 0
,03-18 15:47:57.655  1016  1702 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-18 15:47:57.655  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-18 15:47:57.655  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,03-18 15:47:57.655  1016  1504 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-18 15:47:57.655  1016  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,03-18 15:47:57.665  1016  1504 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:57.665  1016  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-18 15:47:57.665   257   257 I SurfaceFlinger: id=12 createSurf (720x1280),1 flag=4, Mauncher
,03-18 15:47:57.665  1016  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-18 15:47:57.665  1016  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-18 15:47:57.675  1016  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-18 15:47:57.675  3641  3641 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
,03-18 15:47:57.675  1016  1142 D InputDispatcher: Focus entered window: 1488
,03-18 15:47:57.675  1488  1488 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-18 15:47:57.675  1016  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-18 15:47:57.675  1016  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-18 15:47:57.685  1016  1028 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-18 15:47:57.685  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,03-18 15:47:57.685  3641  3641 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,03-18 15:47:57.695  3396  3411 W art     : Suspending all threads took: 299.515ms
03-18 15:47:57.695  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:57.695  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-18 15:47:57.695  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-18 15:47:57.695  1488  1488 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-18 15:47:57.695  1016  1702 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,03-18 15:47:57.695  1016  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.695  1016  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.695  1016  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.695  1016  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.705  3667  3667 E Zygote  : MountEmulatedStorage()
,03-18 15:47:57.705  3667  3667 E Zygote  : v2
03-18 15:47:57.705  3667  3667 I libpersona: KNOX_SDCARD checking this for 10062
03-18 15:47:57.715  3667  3667 I libpersona: KNOX_SDCARD not a persona,
,03-18 15:47:57.715  3667  3667 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-18 15:47:57.715  1016  1702 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3667 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-18 15:47:57.715  1016  1702 I ActivityManager: Killing 2950:com.sec.knox.bridge/1000 (adj 15): empty #31
,03-18 15:47:57.715  1016  1337 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
03-18 15:47:57.725  3241  3316 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-18 15:47:57.725  3667  3667 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-18 15:47:57.725  3667  3667 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:57.735  1016  3674 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-18 15:47:57.735  1016  1702 D ActivityManager: startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
,03-18 15:47:57.735  1188  1188 D PanelView: There is/are notification(s) 
03-18 15:47:57.735  1016  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.735  1016  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.735  1016  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.735  1016  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.755  3683  3683 E Zygote  : MountEmulatedStorage(),
03-18 15:47:57.755  1016  1702 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3683 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-18 15:47:57.755  3683  3683 E Zygote  : v2
03-18 15:47:57.755  3683  3683 I libpersona: KNOX_SDCARD checking this for 10101,
03-18 15:47:57.755  3683  3683 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:57.755  1016  1702 I ActivityManager: Killing 2969:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,03-18 15:47:57.755  3208  3208 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-18 15:47:57.755  3683  3683 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-18 15:47:57.755  3683  3683 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-18 15:47:57.765  1780  1780 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-18 15:47:57.765  3659  3659 D AndroidRuntime: 
03-18 15:47:57.765  3659  3659 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-18 15:47:57.775  3659  3659 D AndroidRuntime: CheckJNI is OFF
,03-18 15:47:57.775  3659  3659 D AndroidRuntime: readGMSProperty: start
03-18 15:47:57.775  3659  3659 D AndroidRuntime: readGMSProperty: already setted!!
03-18 15:47:57.775  3659  3659 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-18 15:47:57.775  3659  3659 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-18 15:47:57.775  3659  3659 D AndroidRuntime: readGMSProperty: end
03-18 15:47:57.775  3659  3659 D AndroidRuntime: addProductProperty: start
,03-18 15:47:57.775  3683  3683 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-18 15:47:57.775  3415  3542 W art     : Verification of void com.google.android.apps.gsa.extradex.attemptedsearchhistory.a.e(byte[]) took 168.131ms
,03-18 15:47:57.795  3667  3667 D TimaKeyStoreProvider: TimaSignature is unavailable,
,03-18 15:47:57.795  3667  3667 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:57.805  1488  1488 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3a75ec93 time:40700
,03-18 15:47:57.805  1016  1049 D PersonaManager: isKioskContainerExistOnDevice
,03-18 15:47:57.815  3683  3683 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:57.815  3683  3683 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:57.845  1016  1049 I ActivityManager: Displayed Component not be shown by security: +282ms
,03-18 15:47:57.855  1016  1039 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-18 15:47:57.875  1016  1700 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-18 15:47:57.875  1016  1700 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,03-18 15:47:57.875  1016  1700 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:57.875  1016  1700 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-18 15:47:57.875  1016  1700 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-18 15:47:57.895  1306  3236 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-18 15:47:57.915  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.hs20settings, hostingType: broadcast
,03-18 15:47:57.925  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.925  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.925  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:57.925  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:57.925  3415  3542 W art     : Verification of com.google.m.a.a.a.f com.google.android.apps.gsa.extradex.attemptedsearchhistory.a.vI() took 147.305ms
,03-18 15:47:57.945  3659  3659 E AffinityControl: AffinityControl: registerfunction enter,
,03-18 15:47:57.945  3711  3711 E Zygote  : MountEmulatedStorage(),
,03-18 15:47:57.955  3711  3711 E Zygote  : v2
03-18 15:47:57.955  3711  3711 I libpersona: KNOX_SDCARD checking this for 1000,
03-18 15:47:57.955  3711  3711 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:57.955  3711  3711 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-18 15:47:57.955  3711  3711 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-18 15:47:57.965  3711  3711 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:57.965  1016  1028 I ActivityManager: Start proc com.samsung.hs20settings for broadcast com.samsung.hs20settings/.WifiHs20BroadcastReceiver: pid=3711 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-18 15:47:57.975  3659  3659 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-18 15:47:57.985  3711  3711 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:57.985  3711  3711 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:57.995  3415  3542 I SearchServiceFactory: refreshing internal icing corpora
,03-18 15:47:57.995  3415  3542 I SearchServiceFactory: checking for language pack updates
,03-18 15:47:58.005  1016  1700 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-18 15:47:58.005  1016  1700 D PackageManager: START PACKAGE DELETE: observer{846733676}
03-18 15:47:58.005  1016  1700 D PackageManager: pkg{<packageName>}
03-18 15:47:58.005  1016  1700 D PackageManager: user{0}
03-18 15:47:58.005  1016  1700 D PackageManager: caller{2000}
03-18 15:47:58.005  1016  1700 D PackageManager: flags{2}
03-18 15:47:58.005  1016  1700 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-18 15:47:58.005  1016  1700 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-18 15:47:58.005  1016  1700 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-18 15:47:58.005  1016  1700 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,03-18 15:47:58.015  1016  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,03-18 15:47:58.015  1016  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,03-18 15:47:58.035  1016  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-18 15:47:58.035  1016  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
03-18 15:47:58.035  1016  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-18 15:47:58.035  1016  1057 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,03-18 15:47:58.035  1016  1042 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,03-18 15:47:58.035  1016  1042 I ActivityManager: Killing 3208:com.test.thalitest/u0a155 (adj 1): stop com.test.thalitest cause uninstall pkg
,03-18 15:47:58.055  1016  1039 D SensorService: [SO] currT = 40950106493, prevT = 40490411233, diff = 459695260, [0.134 0.402 10.113]
,03-18 15:47:58.055  1016  1229 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
03-18 15:47:58.055  1016  1229 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
03-18 15:47:58.055  1016  1039 D SensorService: [SO] 0.134 0.402 10.113
,03-18 15:47:58.055  1016  1039 D SensorService: [SO] [100 -> 255]
03-18 15:47:58.055  1016  1229 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:58.055  1016  1229 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:58.055  1016  1229 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-18 15:47:58.055  3711  3711 I Hs20UtilService: onCreate
,03-18 15:47:58.065  1016  1099 W InputDispatcher: channel ~ Consumer closed input channel or an error occurred.  events=0x9
03-18 15:47:58.065  1016  1099 E InputDispatcher: channel ~ Channel is unrecoverably broken and will be disposed!
,03-18 15:47:58.075  1016  1042 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@7
,03-18 15:47:58.075  1016  1702 I WindowState: WIN DEATH: Window{3d09a231 u0 com.test.thalitest/com.test.thalitest.MainActivity EXITING}
03-18 15:47:58.075  1016  1702 W InputDispatcher: Attempted to unregister already unregistered input channel
,03-18 15:47:58.075  1016  1042 W ActivityManager: mDVFSHelper.release()
,03-18 15:47:58.085  3711  3711 I Hs20UtilService: Starting #1
,03-18 15:47:58.085  3711  3731 I Hs20UtilService: Message received 5003
,03-18 15:47:58.195  3667  3667 I ExternalOEMControlProvider: onCreate
,03-18 15:47:58.255   257   439 I SurfaceFlinger: id=11 Removed NainActivit (7/8)
,03-18 15:47:58.255   257  1038 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-18 15:47:58.255   257   432 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-18 15:47:58.275  1780  3533 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-18 15:47:58.355  1016  1496 D ActivityManager: startProcessLocked calleePkgName: com.samsung.klmsagent, hostingType: broadcast
,03-18 15:47:58.355  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:58.355  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:58.355  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:58.355  1016  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:58.365  3396  3588 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-18 15:47:58.365  3396  3588 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-18 15:47:58.375  3741  3741 E Zygote  : MountEmulatedStorage()
,03-18 15:47:58.375  3741  3741 E Zygote  : v2
03-18 15:47:58.375  3741  3741 I libpersona: KNOX_SDCARD checking this for 10019
03-18 15:47:58.375  3741  3741 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:58.375  3741  3741 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-18 15:47:58.375  1016  1496 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3741 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-18 15:47:58.375  3741  3741 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-18 15:47:58.375  3741  3741 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:58.375  2634  2634 D FactoryTestApp: [DummyFtClient$onDestroy](2634) Destroy DummyFtClient service
,03-18 15:47:58.395  3741  3741 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:58.395  3741  3741 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:58.395  1016  1057 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,03-18 15:47:58.435  1016  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,03-18 15:47:58.445  1016  1042 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-18 15:47:58.445  1016  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3c8cefe7 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t11} time:41343
,03-18 15:47:58.445  1016  1504 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-18 15:47:58.445  1016  1504 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-18 15:47:58.445  2634  2634 D FactoryTestApp: [Support$Values.getString](2634) id=MODEL_COMMUNICATION_MODE, value=gsm
,03-18 15:47:58.445  2634  2634 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2634) mConnectionMode = gsm
,03-18 15:47:58.455  3747  3747 I dex2oat : ----------------------------------------------------
03-18 15:47:58.455  3747  3747 I dex2oat : <SS>: S T A R T I N G . . .
03-18 15:47:58.455  3747  3747 I dex2oat : <SS>: Zip is absent. Canceled.
,03-18 15:47:58.455  3747  3747 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-591555030.jar --oat-fd=33 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads-591555030.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-18 15:47:58.465  2634  2634 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2634) RUNNING_FTCLIENT : false
03-18 15:47:58.465  2634  2634 D FactoryTestApp: [DummyFtClient$onDestroy](2634) kill process
03-18 15:47:58.465  2634  2634 I Process : Sending signal. PID: 2634 SIG: 9
,03-18 15:47:58.465  1016  2905 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
03-18 15:47:58.465  1016  2905 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
,03-18 15:47:58.475  1016  2905 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:58.475  1016  2905 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-18 15:47:58.475  1016  2905 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-18 15:47:58.505  3415  3759 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[refresh_search_history]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-18 15:47:58.505  3415  3759 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[update_hotword_models]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-18 15:47:58.505  3415  3759 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[update_icing_corpora]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
03-18 15:47:58.505  3415  3759 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[log_attempted_searches_to_kansas]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-18 15:47:58.505  3415  3759 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[update_language_packs]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-18 15:47:58.505  3415  3759 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[refresh_doodle]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-18 15:47:58.515  3415  3759 E TRThreadPoolExecutor: Queue length for executor Background Blocking with unbounded threads is now 4. Perhaps some tasks are too long, or the pool is too small.
,03-18 15:47:58.515  3415  3759 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[refresh_search_domain_and_cookies]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-18 15:47:58.515  3415  3759 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[refresh_auth_tokens]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
03-18 15:47:58.515  3415  3761 I SearchServiceFactory: refreshing search history.
,03-18 15:47:58.525  1823  2092 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-18 15:47:58.535  1780  1780 E SamsungIME: mOCRHelper is null
,03-18 15:47:58.535  1467  1467 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-18 15:47:58.555  1016  1137 V NetworkStats: removeUidsLocked() for UIDs [10155]
03-18 15:47:58.555  1016  1137 D NtpTrustedTime: currentTimeMillis() cache hit
03-18 15:47:58.555  1016  1137 V NetworkStats: performPollLocked(flags=0x3)
,03-18 15:47:58.555  1016  1137 D NetworkStatsFactory: UpdateStatsForKnox updated
03-18 15:47:58.555  1016  1137 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-18 15:47:58.565  1016  1137 V NetworkStats: performPollLocked() took 6ms
03-18 15:47:58.565  1016  1137 D NtpTrustedTime: currentTimeMillis() cache hit
,03-18 15:47:58.575  1016  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-18 15:47:58.585  1016  3735 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.servicemodeapp, hostingType: broadcast
,03-18 15:47:58.585  3741  3741 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Mar 18 15:47:58 GMT+01:00 2016
,03-18 15:47:58.585  1016  3735 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:58.585  1016  3735 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:58.595  1016  3735 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:58.595  1016  3735 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:58.605  3773  3773 E Zygote  : MountEmulatedStorage(),
03-18 15:47:58.605  3773  3773 E Zygote  : v2
03-18 15:47:58.605  3773  3773 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:58.605  3773  3773 I libpersona: KNOX_SDCARD not a persona,
03-18 15:47:58.605  3773  3773 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-18 15:47:58.615  3773  3773 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-18 15:47:58.615  3773  3773 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-18 15:47:58.615  1016  3735 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3773 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-18 15:47:58.625  1016  1343 I ActivityManager: Process com.sec.factory (pid 2634)(adj 0) has died(118,1126)
,03-18 15:47:58.625  3747  3747 I dex2oat : dex2oat took 162.964ms (threads: 4)
,03-18 15:47:58.635  1016  1337 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-18 15:47:58.635  1016  1337 D SecContentProvider2: mCursor = null
,03-18 15:47:58.645  3773  3773 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:58.655  3773  3773 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:58.675  1016  1028 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
03-18 15:47:58.675  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-18 15:47:58.675  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:58.675  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:58.675  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-18 15:47:58.675  3415  3765 W TRThreadPoolExecutor: Task "p[Get token]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-18 15:47:58.675  1016  2905 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
03-18 15:47:58.675  1016  2905 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,03-18 15:47:58.675  1016  1496 D SettingsProvider: name = PREVIOUS_SYS_TIME
03-18 15:47:58.675  1016  2905 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:58.675  1016  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-18 15:47:58.675  1016  2905 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-18 15:47:58.675  1016  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-18 15:47:58.675  1016  2905 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
03-18 15:47:58.675  1016  1496 D SettingsProvider: selectionArgs: false
03-18 15:47:58.675  1016  1496 D SettingsProvider: selectionArgs: 10062
03-18 15:47:58.675  1016  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-18 15:47:58.675  1016  1496 D SettingsProvider: ret = -1
,03-18 15:47:58.685  1016  1016 D RCPManagerService: PackageReceiver onReceive(),
03-18 15:47:58.685  1016  1016 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
03-18 15:47:58.695  1016  1496 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,03-18 15:47:58.695  1448  1448 D RegisteredComponentCache: Collect Tech packages for Knox
03-18 15:47:58.695  1016  1016 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-18 15:47:58.695  1016  1016 I OTPFW   : PackageRemovalReceiver::onReceive Enter
03-18 15:47:58.695  1016  1016 D OTPFW   : OtpDbHelper::getInstance New instance created
03-18 15:47:58.695  1016  1016 D OTPFW   : DBIntegrity::getInstance - New instance created
03-18 15:47:58.705  1016  2905 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
03-18 15:47:58.705  1016  2905 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-18 15:47:58.705  1016  2905 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-18 15:47:58.705  1016  2905 D SettingsProvider: selectionArgs: false
03-18 15:47:58.705  1016  2905 D SettingsProvider: selectionArgs: 10062
03-18 15:47:58.705  1016  2905 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-18 15:47:58.705  1016  2905 D SettingsProvider: ret = -1
,03-18 15:47:58.705  3741  3741 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-18 15:47:58.705  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-18 15:47:58.715  1448  1448 D PersonaManager: isKioskContainerExistOnDevice
,03-18 15:47:58.715  1016  2905 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,03-18 15:47:58.725  3241  3316 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,03-18 15:47:58.725  1016  1016 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,03-18 15:47:58.725  1016  1016 I OTPFW   : ProvisionData::getAllEntries Enter
,03-18 15:47:58.725  1016  1016 E OTPFW   : ProvisionData::getAllEntries Table is empty
,03-18 15:47:58.725  1016  1016 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-18 15:47:58.725  3773  3773 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-18 15:47:58.725  1016  1138 D NtpTrustedTime: currentTimeMillis() cache hit
,03-18 15:47:58.725  1016  1138 D NtpTrustedTime: currentTimeMillis() cache hit
,03-18 15:47:58.725  1016  1702 D ActivityManager: startProcessLocked calleePkgName: com.android.managedprovisioning, hostingType: broadcast
,03-18 15:47:58.735  1016  1016 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-18 15:47:58.735  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-18 15:47:58.735  1016  1016 V EnterpriseBillingPolicy: uID is 10155
03-18 15:47:58.735  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
03-18 15:47:58.735  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-18 15:47:58.735  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-18 15:47:58.735  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-18 15:47:58.735  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-18 15:47:58.735  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-18 15:47:58.735  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-18 15:47:58.735  3741  3741 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-18 15:47:58.735  1016  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:58.735  1016  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:58.735  3741  3741 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-18 15:47:58.735  1016  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:58.735  1016  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:58.745  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-18 15:47:58.765  3795  3795 E Zygote  : MountEmulatedStorage()
03-18 15:47:58.765  3795  3795 E Zygote  : v2
03-18 15:47:58.765  3795  3795 I libpersona: KNOX_SDCARD checking this for 10022
03-18 15:47:58.765  3795  3795 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:58.765  3795  3795 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-18 15:47:58.765  3795  3795 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-18 15:47:58.765  1016  1702 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3795 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
03-18 15:47:58.765  3741  3741 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-18 15:47:58.765  3795  3795 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:58.775  3741  3794 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-18 15:47:58.785  1016  1016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-18 15:47:58.795  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-18 15:47:58.795  1016  1016 V EnterpriseBillingPolicy: uID is 10155
03-18 15:47:58.795  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
03-18 15:47:58.795  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-18 15:47:58.795  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-18 15:47:58.795  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-18 15:47:58.795  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-18 15:47:58.795  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-18 15:47:58.795  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-18 15:47:58.795  1016  2745 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
,03-18 15:47:58.795  1016  1016 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,03-18 15:47:58.805  3795  3795 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:58.815  3795  3795 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:58.815  3741  3794 I KLMS-2.5.183: : KLMSIntentService(): BOOT_COMPLETED
,03-18 15:47:58.825  1016  1016 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@11
,03-18 15:47:58.835  3396  3396 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-18 15:47:58.845  3415  3766 I UpdateLanguagePacksTask: Checking for language pack updates.
,03-18 15:47:58.845  1016  1029 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-18 15:47:58.845  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
03-18 15:47:58.845  3773  3773 I ServiceMode: received = ACTION_BOOT_COMPLETED
03-18 15:47:58.845  3773  3773 I ServiceMode: setReferenceIsDumpState : 0
,03-18 15:47:58.845  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:58.845  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-18 15:47:58.845  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-18 15:47:58.855  1016  3772 D ActivityManager: startProcessLocked calleePkgName: com.wssnps, hostingType: broadcast
,03-18 15:47:58.855  1016  3772 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:58.855  1016  3772 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:58.855  1016  3772 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:58.855  1016  3772 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:58.875  3812  3812 E Zygote  : MountEmulatedStorage()
,03-18 15:47:58.875  3812  3812 E Zygote  : v2
03-18 15:47:58.875  3812  3812 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:58.875  3812  3812 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-18 15:47:58.875  3812  3812 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:58.875  3812  3812 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-18 15:47:58.875  1016  3772 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3812 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-18 15:47:58.875  1016  3772 I ActivityManager: Killing 1899:com.android.defcontainer/u0a4 (adj 15): empty #31,
03-18 15:47:58.875  3812  3812 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:58.895  1448  1448 D PersonaManager: isKioskContainerExistOnDevice
,03-18 15:47:58.905  1448  1448 D RegisteredServicesCache: empty dynamic service
03-18 15:47:58.905  1306  3236 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,03-18 15:47:58.905  1645  2861 I art     : Explicit concurrent mark sweep GC freed 3309(133KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.121ms total 56.819ms
,03-18 15:47:58.925  3812  3812 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:58.935  3812  3812 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:58.935  1016  1496 I ActivityManager: Killing 3011:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,03-18 15:47:58.935  1306  3236 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,03-18 15:47:58.945  1306  3236 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
,03-18 15:47:58.955  1016  1041 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
03-18 15:47:58.955  1016  1041 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.EsSyncAdapterService; callingUser = 0; userId(target) = 0
,03-18 15:47:58.965  3396  3396 I System.out: YouTube MDX: MDX video stage moved to NEW
,03-18 15:47:58.965  3396  3396 I System.out: YouTube MDX: MDX video player state moved to UNSTARTED
,03-18 15:47:58.995  3415  3542 W art     : Verification of void com.google.m.a.a.a.f.a(com.google.i.a.b) took 365.036ms
,03-18 15:47:59.005  3396  3396 I System.out: YouTube MDX: MDX ad player state moved to UNSTARTED
,03-18 15:47:59.025  1016  1343 D ActivityManager: bindService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.gms, action: null
,03-18 15:47:59.025  1016  1343 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-18 15:47:59.025  1016  1343 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:59.035  1016  1343 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-18 15:47:59.035  1016  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-18 15:47:59.035  1823  1823 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-18 15:47:59.035  1823  1823 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-18 15:47:59.045  3510  3510 I RlzPingService: Setting next ping for 1458917279051
,03-18 15:47:59.055  1016  1172 D TaskPersister: removeObsoleteFile: deleting file=12_task.xml
,03-18 15:47:59.055  1016  1172 D TaskPersister: removeObsoleteFile: deleting file=12_task_thumbnail.png
,03-18 15:47:59.065  1016  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2764/cgroup.procs: No such file or directory
03-18 15:47:59.065  1016  1041 W libprocessgroup: failed to open /acct/uid_10099/pid_2873/cgroup.procs: No such file or directory
,03-18 15:47:59.065  3812  3812 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
,03-18 15:47:59.065  3415  3833 I UpdateIcingCorporaServi: Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
,03-18 15:47:59.065  3812  3812 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,03-18 15:47:59.075  3339  3560 I System.out: pool-10-thread-1 calls detatch()
,03-18 15:47:59.085  1016  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2909/cgroup.procs: No such file or directory
03-18 15:47:59.085  1016  1041 W libprocessgroup: failed to open /acct/uid_10152/pid_2929/cgroup.procs: No such file or directory
,03-18 15:47:59.085  1016  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2399/cgroup.procs: No such file or directory
,03-18 15:47:59.085  3415  3764 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-18 15:47:59.085  3741  3741 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-18 15:47:59.095  1016  1229 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,03-18 15:47:59.095  1016  1041 W libprocessgroup: failed to open /acct/uid_1000/pid_2950/cgroup.procs: No such file or directory
03-18 15:47:59.095  1016  1041 W libprocessgroup: failed to open /acct/uid_1101/pid_2969/cgroup.procs: No such file or directory
,03-18 15:47:59.095  1016  1041 W libprocessgroup: failed to open /acct/uid_10098/pid_2237/cgroup.procs: No such file or directory
,03-18 15:47:59.095  1016  1229 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:59.095  1016  1229 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:59.095  1016  1229 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:59.105  1016  1229 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:59.115  3840  3840 E Zygote  : MountEmulatedStorage()
03-18 15:47:59.115  3840  3840 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:59.115  3840  3840 E Zygote  : v2
03-18 15:47:59.115  3840  3840 I libpersona: KNOX_SDCARD not a persona
03-18 15:47:59.115  3840  3840 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-18 15:47:59.115  3840  3840 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-18 15:47:59.125  1016  1229 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3840 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-18 15:47:59.125  3840  3840 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:59.125  1016  1337 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-18 15:47:59.135  1016  1337 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:59.135  1016  1337 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-18 15:47:59.135  1016  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-18 15:47:59.145  1016  2905 D ActivityManager: startService callerProcessName:com.wssnps, calleePkgName: com.wssnps
,03-18 15:47:59.145  1016  2905 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-18 15:47:59.155  3840  3840 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:59.155  3840  3840 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:59.155  3683  3838 I Gmail   : getAccountsCursor
,03-18 15:47:59.155  1016  2905 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:59.155  1016  2905 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-18 15:47:59.155  1016  2905 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-18 15:47:59.165  3415  3541 E File    : fail readDirectory() errno=2
,03-18 15:47:59.185  1016  3735 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,03-18 15:47:59.185  3812  3812 D NPS_WSSNPS: [] Service onCreate!!
,03-18 15:47:59.185   256   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.googlequicksearchbox/files/download_cache/
03-18 15:47:59.185   256   527 W Vold    : Returning OperationFailed - no handler for errno 0
,03-18 15:47:59.195  1016  3735 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:59.195  1016  3735 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:59.195  1016  3735 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:59.195  1016  3735 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:59.215  3859  3859 E Zygote  : MountEmulatedStorage(),
03-18 15:47:59.215  3859  3859 E Zygote  : v2
03-18 15:47:59.215  3859  3859 I libpersona: KNOX_SDCARD checking this for 1000
03-18 15:47:59.215  3859  3859 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:59.215  3859  3859 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-18 15:47:59.215  1016  3735 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=3859 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-18 15:47:59.225  3415  3430 W art     : Suspending all threads took: 15.867ms
,03-18 15:47:59.225  3859  3859 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-18 15:47:59.225  1016  1142 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-18 15:47:59.225  3859  3859 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-18 15:47:59.225  1016  1142 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-18 15:47:59.235  3812  3867 D NPS_WSSNPS: [] NpsServiceTask Start
,03-18 15:47:59.245  3859  3859 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:59.245  3859  3859 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:59.245  3415  3764 I LibraryLoader: Time to load native libraries: 24 ms (timestamps 2124-2148)
03-18 15:47:59.245  3415  3764 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-18 15:47:59.255  3415  3542 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.googlequicksearchbox/files/download_cache
,03-18 15:47:59.265  1823  1823 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-18 15:47:59.275  1016  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-18 15:47:59.275  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:59.275  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-18 15:47:59.275  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-18 15:47:59.275  1016  3772 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-18 15:47:59.285  1016  3772 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:59.285  1016  3772 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-18 15:47:59.285  1016  3772 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-18 15:47:59.285  1016  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
,03-18 15:47:59.285  3840  3840 E MTPRx   : In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,03-18 15:47:59.285  3859  3859 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-18 15:47:59.295  1016  1029 D SecContentProvider2: uri = 14 selection = getSealedState
03-18 15:47:59.295  1016  1029 D SecContentProvider2: mCursor = null
,03-18 15:47:59.295  1016  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,03-18 15:47:59.295  1016  1041 W TextServicesManagerService: no available spell checker services found
,03-18 15:47:59.295  1016  3772 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-18 15:47:59.295  1016  3772 D SecContentProvider2: mCursor = null
,03-18 15:47:59.295  3840  3840 V MTPRx   : sealedState: false
03-18 15:47:59.295  3840  3840 V MTPRx   : sealedUsbMassStorageState: false
,03-18 15:47:59.305  1016  1142 D SettingsProvider: name = mtp_usb_connection_status
,03-18 15:47:59.305  3415  3764 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-18 15:47:59.305  1488  1488 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-18 15:47:59.305  3415  3764 W TRThreadPoolExecutor: Task "b[Get cookie call]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
03-18 15:47:59.305  1488  1488 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-18 15:47:59.305  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-18 15:47:59.305  1488  1488 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-18 15:47:59.315  3812  3812 D NPS_WSSNPS: [50.150621] smlDBHelper
,03-18 15:47:59.325  1016  1057 I art     : Explicit concurrent mark sweep GC freed 48956(3MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 30MB/46MB, paused 9.515ms total 882.040ms
03-18 15:47:59.325  1016  2904 I art     : WaitForGcToComplete blocked for 111.601ms for cause Explicit
,03-18 15:47:59.335  3683  3683 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-18 15:47:59.335  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-18 15:47:59.355  3415  3761 W TRThreadPoolExecutor: Task "b[Get cookie call]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-18 15:47:59.365  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-18 15:47:59.365  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-18 15:47:59.385  1016  3735 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,03-18 15:47:59.385  1016  3735 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,03-18 15:47:59.395  1016  3735 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:59.395  1016  3735 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-18 15:47:59.395  1016  3735 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-18 15:47:59.405  1016  1028 D SettingsProvider: name = media_player_mode
,03-18 15:47:59.405  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-18 15:47:59.415  1016  1702 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,03-18 15:47:59.415  1016  1702 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,03-18 15:47:59.415  1016  1702 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:59.415  1016  1702 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-18 15:47:59.415  1016  1702 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-18 15:47:59.425  3415  3765 W TRThreadPoolExecutor: Task "p[Get token]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-18 15:47:59.425  1016  1702 D SettingsProvider: name = mtp_usb_conditions_met
,03-18 15:47:59.435  3812  3812 I NPS_WSSNPS: [50.150621] AsyncBulkFlagCheck
,03-18 15:47:59.445  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-18 15:47:59.445  1016  3772 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-18 15:47:59.445  1016  3772 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-18 15:47:59.445  1016  3735 D SettingsProvider: name = mtp_running_status
,03-18 15:47:59.455  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-18 15:47:59.465  1016  1504 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-18 15:47:59.465  3812  3891 I NPS_WSSNPS: [50.150621] IsRemain_AsyncBulkCheck
,03-18 15:47:59.465  1016  1504 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:59.465  1016  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-18 15:47:59.465  1016  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-18 15:47:59.465  3812  3891 I NPS_WSSNPS: [50.150621] IsRemain_Asyncing nothing
,03-18 15:47:59.465  3812  3891 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,03-18 15:47:59.475  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-18 15:47:59.475  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:59.475  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-18 15:47:59.475  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-18 15:47:59.485  1016  1057 D PackageManager: delete codoeFile: 
,03-18 15:47:59.485  1016  1496 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,03-18 15:47:59.485  1016  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,03-18 15:47:59.495  1016  1057 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
,03-18 15:47:59.495  1016  2904 I art     : Explicit concurrent mark sweep GC freed 12613(631KB) AllocSpace objects, 1(1650KB) LOS objects, 33% free, 28MB/42MB, paused 3.119ms total 164.870ms
,03-18 15:47:59.495  3683  3889 E Gmail   : Error finding the version of the Email provider.....
03-18 15:47:59.495  3683  3889 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-18 15:47:59.495  3683  3889 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
03-18 15:47:59.495  3683  3889 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
03-18 15:47:59.495  3683  3889 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
03-18 15:47:59.495  3683  3889 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:47:59.495  3683  3889 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:47:59.495  3683  3889 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
03-18 15:47:59.495  3683  3889 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-18 15:47:59.495  3683  3889 W EmailMigration: We do not support migrating this version of the Email provider.
,03-18 15:47:59.495  3812  3812 D NPS_WSSNPS: [50.150621] Service onDestroy
,03-18 15:47:59.495  1016  1496 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:59.495  1016  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-18 15:47:59.495  1016  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-18 15:47:59.495  1016  1057 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,03-18 15:47:59.495  1016  2905 D SettingsProvider: name = media_mount_count
,03-18 15:47:59.505  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-18 15:47:59.505  1016  1057 D PackageManager: result of delete: 1{846733676}
,03-18 15:47:59.515  3659  3659 D AndroidRuntime: Shutting down VM
,03-18 15:47:59.515  1016  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-18 15:47:59.515  1016  1057 D PackageManager: userId{-1}
03-18 15:47:59.515  1016  1057 D PackageManager: andCode{true}
,03-18 15:47:59.525  1016  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,03-18 15:47:59.535  1016  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:59.535  1016  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:59.535  1016  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:59.535  1016  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:59.545  3683  3898 I Gmail   : getAccountsCursor
03-18 15:47:59.545  3899  3899 E Zygote  : MountEmulatedStorage()
03-18 15:47:59.545  3899  3899 E Zygote  : v2
03-18 15:47:59.545  3899  3899 I libpersona: KNOX_SDCARD checking this for 10004
03-18 15:47:59.545  3899  3899 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:59.545  1016  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=3899 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,03-18 15:47:59.555  1016  3782 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-18 15:47:59.555  1016  3782 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-18 15:47:59.555  1016  1142 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-18 15:47:59.555  1016  1142 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-18 15:47:59.555  1823  1823 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-18 15:47:59.585  3899  3899 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-18 15:47:59.585  1016  1142 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,03-18 15:47:59.585  3812  3812 I NPS_WSSNPS: [50.150621] smlBRConfigurationDelete
,03-18 15:47:59.585  1016  1142 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
03-18 15:47:59.585  3812  3812 I NPS_WSSNPS: [50.150621] smlBRMessageDelete
03-18 15:47:59.585  3812  3812 I NPS_WSSNPS: [50.150621] smlBREmailDelete
03-18 15:47:59.585  1016  1142 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:59.585  1016  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-18 15:47:59.585  1016  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
03-18 15:47:59.585  3812  3812 I NPS_WSSNPS: [50.150621] smlBRNetworkDelete
03-18 15:47:59.585  3812  3812 I NPS_WSSNPS: [50.150621] smlBRCallLogDelete
,03-18 15:47:59.585  3812  3812 I NPS_WSSNPS: [50.150621] smlBRMiniDiaryDelete
,03-18 15:47:59.585  3899  3899 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-18 15:47:59.595  3812  3812 I NPS_WSSNPS: [50.150621] smlBRPenMemoMDelete
,03-18 15:47:59.595  3812  3812 I NPS_WSSNPS: [50.150621] smlBRSMemoDelete
,03-18 15:47:59.595  3812  3812 I NPS_WSSNPS: [50.150621] verifier installed? false
,03-18 15:47:59.595  1016  1229 D SettingsProvider: name = mtp_sync_alive
,03-18 15:47:59.595  3899  3899 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:47:59.605  3812  3812 I NPS_WSSNPS: [50.150621] cpuBooster release : false
,03-18 15:47:59.605  1016  1496 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,03-18 15:47:59.605  3812  3812 D NPS_WSSNPS: [50.150621] dsServerSocket close
,03-18 15:47:59.605  1016  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,03-18 15:47:59.615  1016  1496 W ActivityManager: userId = 0, bbcId = -10000
,03-18 15:47:59.615  1016  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-18 15:47:59.615  1016  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-18 15:47:59.615  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-18 15:47:59.615  1016  2904 I ActivityManager: Killing 2368:com.android.mms/u0a46 (adj 15): empty #31
,03-18 15:47:59.625  1016  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-18 15:47:59.635  1016  2904 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.syncadapters.contacts
,03-18 15:47:59.635  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-18 15:47:59.635  1016  2904 D ActivityManager: retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,03-18 15:47:59.635  1016  2904 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:59.635  3899  3899 D TimaKeyStoreProvider: TimaSignature is unavailable
03-18 15:47:59.635  1016  2904 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-18 15:47:59.635  1016  2904 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,03-18 15:47:59.635  3899  3899 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:59.635  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-18 15:47:59.635  1016  3735 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,03-18 15:47:59.635  1016  3735 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:59.645  1016  3735 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:59.645  1016  3735 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:47:59.645  1016  3735 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:47:59.655  3919  3919 E Zygote  : MountEmulatedStorage()
03-18 15:47:59.655  3919  3919 E Zygote  : v2
03-18 15:47:59.655  3919  3919 I libpersona: KNOX_SDCARD checking this for 10104
03-18 15:47:59.655  3919  3919 I libpersona: KNOX_SDCARD not a persona
,03-18 15:47:59.655  3919  3919 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-18 15:47:59.655  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-18 15:47:59.665  1016  3735 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3919 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
03-18 15:47:59.655  3919  3919 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-18 15:47:59.655  3919  3919 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-18 15:47:59.665  1645  3917 I GoogleHttpClient: GMS http client unavailable, use old client
,03-18 15:47:59.665  3415  3833 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 596 ms] updated apps [took 596 ms] 
,03-18 15:47:59.675  3415  3764 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-18 15:47:59.675  1016  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-18 15:47:59.675  1016  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-18 15:47:59.675  1016  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-18 15:47:59.675  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-18 15:47:59.685   305   305 I art     : Explicit concurrent mark sweep GC freed 8740(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 643us total 24.970ms
,03-18 15:47:59.685  1016  3738 D SettingsProvider: name = sdcard_launch
,03-18 15:47:59.685  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-18 15:47:59.695  3919  3919 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-18 15:47:59.695  3919  3919 D ActivityThread: Added TimaKeyStore provider
,03-18 15:47:59.705  1016  2905 D SettingsProvider: name = boot_time_connected
,03-18 15:47:59.705   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 24.204ms
,03-18 15:47:59.705  1016  1700 D CountryDetector: No listener is left
,03-18 15:47:59.715  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-18 15:47:59.725  3241  3316 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
03-18 15:47:59.725  1016  1142 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-18 15:47:59.725  3659  3659 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-18 15:47:59.725  1016  1142 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
03-18 15:47:59.725   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.195ms total 20.193ms
,03-18 15:47:59.735  1823  1823 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-18 15:47:59.745  1016  3738 D SettingsProvider: name = mtp_open_session
,03-18 15:47:59.755  1016  2905 I ActivityManager: Killing 3047:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,03-18 15:47:59.765  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-18 15:47:59.765  1823  1841 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
03-18 15:47:59.765  1823  1841 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-18 15:47:59.765  1823  1841 I System.out: (HTTPLog)-Static: isShipBuild true
03-18 15:47:59.765  1823  1841 I System.out: (HTTPLog)-Thread-154-442941850: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-18 15:47:59.765  1823  1841 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-18 15:47:59.765   277  1009 D EnterpriseController: uids 10012
03-18 15:47:59.765   277  1009 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-18 15:47:59.765   277  1009 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,03-18 15:47:59.765  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-18 15:47:59.775  3919  3919 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-18 15:47:59.775  1016  1343 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-18 15:47:59.775  1016  1343 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-18 15:47:59.785  1016  2904 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
03-18 15:47:59.785  1016  2904 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-18 15:47:59.795  1016  1028 D ActivityManager: bindService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube, action: null
03-18 15:47:59.795  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-18 15:47:59.795  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:47:59.795  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-18 15:47:59.795  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-18 15:47:59.805  3683  3945 I Gmail   : Observing account changes for notifications
,03-18 15:47:59.805  1016  2905 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-18 15:47:59.805  1016  2905 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-18 15:47:59.815  1016  3772 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-18 15:47:59.815  1016  3772 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-18 15:47:59.815  3323  3370 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-18 15:47:59.825  3323  3370 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-18 15:47:59.825  3683  3683 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@2006bdbb that was originally bound here
03-18 15:47:59.825  3683  3683 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@2006bdbb that was originally bound here
03-18 15:47:59.825  3683  3683 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
03-18 15:47:59.825  3683  3683 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
03-18 15:47:59.825  3683  3683 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
03-18 15:47:59.825  3683  3683 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
03-18 15:47:59.825  3683  3683 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
03-18 15:47:59.825  3683  3683 E ActivityThread: 	at com.android.emailcommon.service.ah.a(SourceFile:181)
03-18 15:47:59.825  3683  3683 E ActivityThread: 	at com.android.emailcommon.service.ah.e(SourceFile:224)
03-18 15:47:59.825  3683  3683 E ActivityThread: 	at com.android.email.service.n.c(SourceFile:161)
03-18 15:47:59.825  3683  3683 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:173)
03-18 15:47:59.825  3683  3683 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:117)
03-18 15:47:59.825  3683  3683 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:318)
03-18 15:47:59.825  3683  3683 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1308)
03-18 15:47:59.825  3683  3683 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-18 15:47:59.825  3683  3683 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-18 15:47:59.825  3683  3683 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-18 15:47:59.825  3683  3683 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-18 15:47:59.825  3323  3370 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
03-18 15:47:59.825  1016  1700 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@203645a
,03-18 15:47:59.825  3323  3370 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-18 15:47:59.825  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-18 15:47:59.825  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-18 15:47:59.825  3323  3370 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-18 15:47:59.825  3323  3370 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-18 15:47:59.835  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-18 15:47:59.835  3323  3370 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-18 15:47:59.835  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-18 15:47:59.835  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-18 15:47:59.835  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-18 15:47:59.835  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-18 15:47:59.835  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-18 15:47:59.845  1016  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
03-18 15:47:59.845  1016  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,03-18 15:47:59.845  1016  1041 W libprocessgroup: failed to open /acct/uid_10004/pid_1899/cgroup.procs: No such file or directory
,03-18 15:47:59.845  1016  1041 W libprocessgroup: failed to open /acct/uid_10157/pid_3011/cgroup.procs: No such file or directory
,03-18 15:47:59.855   256   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-18 15:47:59.855   256   527 W Vold    : Returning OperationFailed - no handler for errno 0
,03-18 15:47:59.855  3396  3396 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-18 15:47:59.865  3683  3897 E SQLiteLog: (283) recovered 87 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-18 15:47:59.875  1823  1841 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-18 15:47:59.875  1823  1841 I qtaguid : Tagging socket 54 with tag 3000040100000000{805307393,0} for uid 10012, pid: 1823, getuid(): 10012
,03-18 15:47:59.885   277  1009 D EnterpriseController: uids 10057
03-18 15:47:59.885   277  1009 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-18 15:47:59.885   277  1009 D Netd    : getNetworkForDns: using netid 502 for uid 10057
,03-18 15:47:59.925  1016  1041 W libprocessgroup: failed to open /acct/uid_10046/pid_2368/cgroup.procs: No such file or directory
,03-18 15:47:59.925  1016  1041 W libprocessgroup: failed to open /acct/uid_10159/pid_3047/cgroup.procs: No such file or directory
,03-18 15:47:59.935  1016  1700 I ActivityManager: Killing 3056:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
,03-18 15:47:59.965  1823  1841 I qtaguid : Tagging socket 67 with tag 3000040100000000{805307393,0} for uid 10012, pid: 1823, getuid(): 10012
,03-18 15:47:59.995  1016  1097 V AlarmManager: waitForAlarm result :8
,03-18 15:48:00.005  1188  1188 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-18 15:48:00.005  1188  1188 D KeyguardUpdateMonitor: handleTimeUpdate
,03-18 15:48:00.015  1188  1188 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-18 15:48:00.025  1188  1188 D SecKeyguardClockView: HomeTimezone(): 1
,03-18 15:48:00.035  1188  1188 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-18 15:48:00.035  1188  1188 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-18 15:48:00.035  1188  1188 I KeyguardEffectViewController: *** don't update sliding image ***
,03-18 15:48:00.055  1016  1041 W libprocessgroup: failed to open /acct/uid_10048/pid_3056/cgroup.procs: No such file or directory
,03-18 15:48:00.075  1188  1188 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-18 15:48:00.095  1188  1188 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-18 15:48:00.095  1188  1188 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-18 15:48:00.105  3470  3470 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-18 15:48:00.105  3470  3470 I PCWCLIENTTRACE_PushUtil: sales region : global
,03-18 15:48:00.105  3470  3470 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-18 15:48:00.105  3470  3470 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.BOOT_COMPLETED
03-18 15:48:00.105  3470  3470 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Version: 4.82
03-18 15:48:00.105  3470  3470 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Push type: [SPP, GCM]
03-18 15:48:00.105  3683  3897 E File    : fail readDirectory() errno=2
,03-18 15:48:00.115  1188  1188 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-18 15:48:00.125  1729  1729 D accuweather: [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,03-18 15:48:00.125  1729  1729 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,03-18 15:48:00.125  1729  1729 D accuweather: [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,03-18 15:48:00.125  1729  1729 D accuweather: [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,03-18 15:48:00.125  1729  1729 D accuweather: [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,03-18 15:48:00.125  1729  1729 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,03-18 15:48:00.135  1729  1729 D accuweather: [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,03-18 15:48:00.135  1729  1729 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,03-18 15:48:00.135  1729  1729 D accuweather: [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,03-18 15:48:00.145  1729  1729 E accuweather: [KK AccuPhone]>>> UIM:1488 [0:0] bTM 15 48,
,03-18 15:48:00.145  3683  3937 I Gmail   : notifyAccountChanged
,03-18 15:48:00.155  3683  3966 I Gmail   : getAccountsCursor
,03-18 15:48:00.155  1016  2904 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,03-18 15:48:00.165  2617  3240 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-18 15:48:00.165  2617  3240 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-18 15:48:00.165  2617  3240 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-18 15:48:00.165  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-18 15:48:00.165  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-18 15:48:00.165  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-18 15:48:00.165  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-18 15:48:00.165  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-18 15:48:00.165  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-18 15:48:00.165  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-18 15:48:00.165  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-18 15:48:00.165  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-18 15:48:00.165  2617  3240 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-18 15:48:00.165  2617  3240 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-18 15:48:00.165  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-18 15:48:00.165  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-18 15:48:00.165  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-18 15:48:00.165  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-18 15:48:00.165  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-18 15:48:00.165  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-18 15:48:00.165  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-18 15:48:00.165  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-18 15:48:00.165  2617  3240 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-18 15:48:00.165  2617  3240 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-18 15:48:00.165  2617  3240 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-18 15:48:00.165  2617  3240 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-18 15:48:00.165  3470  3470 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,03-18 15:48:00.165  2617  3240 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-18 15:48:00.165  1016  2904 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-18 15:48:00.175  2617  3240 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-18 15:48:00.175  2617  3240 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPoo,l.openConnectionLocked(SQLiteConnectionPool.java:512)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-18 15:48:00.175  2617  3240 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-18 15:48:00.175  3683  3937 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-18 15:48:00.175  2617  3240 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-18 15:48:00.185  1823  1823 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-18 15:48:00.185  2617  3240 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-18 15:48:00.185  2617  3240 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-18 15:48:00.185  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-18 15:48:00.185  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-18 15:48:00.185  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-18 15:48:00.185  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-18 15:48:00.185  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-18 15:48:00.185  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-18 15:48:00.185  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-18 15:48:00.185  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-18 15:48:00.185  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-18 15:48:00.185  2617  3240 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-18 15:48:00.185  2617  3240 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-18 15:48:00.185  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-18 15:48:00.185  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-18 15:48:00.185  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-18 15:48:00.185  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-18 15:48:00.185  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-18 15:48:00.185  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-18 15:48:00.185  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-18 15:48:00.185  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-18 15:48:00.185  2617  3240 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-18 15:48:00.185  2617  3240 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-18 15:48:00.185  2617  3240 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-18 15:48:00.185  2617  3240 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-18 15:48:00.185  1188  1188 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-18 15:48:00.195  2617  3240 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-18 15:48:00.195  2617  3240 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.,
03-18 15:48:00.195  2617  3240 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-18 15:48:00.195  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-18 15:48:00.195  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-18 15:48:00.195  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-18 15:48:00.195  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-18 15:48:00.195  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-18 15:48:00.195  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-18 15:48:00.195  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-18 15:48:00.195  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
,03-18 15:48:00.195  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-18 15:48:00.195  2617  3240 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-18 15:48:00.195  2617  3240 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-18 15:48:00.195  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-18 15:48:00.195  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-18 15:48:00.195  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-18 15:48:00.195  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-18 15:48:00.195  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-18 15:48:00.195  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-18 15:48:00.195  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-18 15:48:00.195  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-18 15:48:00.195  2617  3240 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-18 15:48:00.195  2617  3240 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-18 15:48:00.195  2617  3240 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-18 15:48:00.195  2617  3240 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-18 15:48:00.205  2617  3240 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-18 15:48:00.205  1016  1337 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.accesscontrol, hostingType: broadcast
,03-18 15:48:00.205  1016  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:48:00.205  1016  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:48:00.205  1016  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-18 15:48:00.205  1016  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-18 15:48:00.215  1488  1766 W OpenGLRenderer: SFEffectCache::get: create texture(0xa1153724): name, size, mSize = 35, 146076, 313320
,03-18 15:48:00.215  2617  3240 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-18 15:48:00.215  2617  3240 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-18 15:48:00.215  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-18 15:48:00.215  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-18 15:48:00.215  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-18 15:48:00.215  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-18 15:48:00.215  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-18 15:48:00.215  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-18 15:48:00.215  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-18 15:48:00.215  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-18 15:48:00.215  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-18 15:48:00.215  2617  3240 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-18 15:48:00.215  2617  3240 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-18 15:48:00.215  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-18 15:48:00.215  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-18 15:48:00.215  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-18 15:48:00.215  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-18 15:48:00.215  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-18 15:48:00.215  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-18 15:48:00.215  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-18 15:48:00.215  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-18 15:48:00.215  2617  3240 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-18 15:48:00.215  2617  3240 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-18 15:48:00.215  2617  3240 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-18 15:48:00.215  2617  3240 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-18 15:48:00.225  3968  3968 E Zygote  : MountEmulatedStorage()
,03-18 15:48:00.225  3968  3968 E Zygote  : v2
03-18 15:48:00.225  3968  3968 I libpersona: KNOX_SDCARD checking this for 1000,
03-18 15:48:00.225  3968  3968 I libpersona: KNOX_SDCARD not a persona,
,03-18 15:48:00.235  3968  3968 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-18 15:48:00.235  3968  3968 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-18 15:48:00.235  1016  1337 I ActivityManager: Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3968 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-18 15:48:00.235  1016  1337 I ActivityManager: Killing 3081:com.sec.usbsettings/1000 (adj 15): empty #31
,03-18 15:48:00.235  3968  3968 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-18 15:48:00.235  2617  3240 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
03-18 15:48:00.235  2617  3240 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-18 15:48:00.235  2617  3240 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-18 15:48:00.235  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-18 15:48:00.235  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-18 15:48:00.235  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-18 15:48:00.235  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-18 15:48:00.235  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-18 15:48:00.235  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-18 15:48:00.235  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-18 15:48:00.235  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-18 15:48:00.235  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-18 15:48:00.235  2617  3240 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-18 15:48:00.235  2617  3240 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-18 15:48:00.235  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-18 15:48:00.235  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-18 15:48:00.235  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-18 15:48:00.235  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-18 15:48:00.235  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-18 15:48:00.235  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-18 15:48:00.235  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-18 15:48:00.235  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-18 15:48:00.235  2617  3240 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-18 15:48:00.235  2617  3240 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-18 15:48:00.235  2617  3240 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-18 15:48:00.235  2617  3240 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-18 15:48:00.235  2617  3240 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)
,03-18 15:48:00.245  2617  3240 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.app.sysscope/databases/SysScope.db'.
03-18 15:48:00.245  2617  3240 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-18 15:48:00.245  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-18 15:48:00.245  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-18 15:48:00.245  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-18 15:48:00.245  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-18 15:48:00.245  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-18 15:48:00.245  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-18 15:48:00.245  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-18 15:48:00.245  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-18 15:48:00.245  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-18 15:48:00.245  2617  3240 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-18 15:48:00.245  2617  3240 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-18 15:48:00.245  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-18 15:48:00.245  2617  3240 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-18 15:48:00.245  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.c.a(Unknown Source)
03-18 15:48:00.245  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.a.b.a(Unknown Source)
03-18 15:48:00.245  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.job.g.a(Unknown Source)
03-18 15:48:00.245  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-18 15:48:00.245  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.a(Unknown Source)
03-18 15:48:00.245  2617  3240 E SQLiteDatabase: 	at com.sec.android.app.sysscope.engine.c.call(Unknown Source)
03-18 15:48:00.245  2617  3240 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-18 15:48:00.245  2617  3240 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-18 15:48:00.245  2617  3240 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-18 15:48:00.245  2617  3240 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,03-18 15:48:00.245  1016  1700 D ActivityManager: bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
03-18 15:48:00.245  1016  1700 W ActivityManager: userId = 0, bbcId = -10000
03-18 15:48:00.245  1016  1700 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
03-18 15:48:00.245  1016  1700 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-18 15:48:00.245  1016  1700 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-18 15:48:00.245  2617  3240 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.app.sysscope/databases/SysScope.db" with flag (131138) and mode_t (0) due to error (30)

```
