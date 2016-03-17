#### Test 62509094764c200_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
03-17 06:44:19.573  2974  2974 D [0]UMC:DeviceInfo: USA==US==
03-17 06:44:19.573  1249  2973 D MediaScanner: Prescan. DB items number : 141 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
03-17 06:44:19.573  2434  2434 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
03-17 06:44:19.573  1018  1714 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:19.573  1018  1714 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:19.573  1018  1714 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 06:44:19.573  2991  3012 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
--------- beginning of system
03-17 06:44:19.573  1018  1714 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 06:44:19.583  1490  2127 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2434
03-17 06:44:19.583   352   352 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 2991
03-17 06:44:19.583   352   352 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
03-17 06:44:19.583  2991  3012 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
03-17 06:44:19.583  2991  3012 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
03-17 06:44:19.583   352   352 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 10003, gid 10003, pid 2991
03-17 06:44:19.583   352   352 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
03-17 06:44:19.583  1018  1513 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:19.583  1018  1513 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:19.583  1018  1513 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
03-17 06:44:19.583  1018  1513 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.transaction.SmsReceiverService; callingUser = 0; userId(target) = 0
03-17 06:44:19.593  3015  3015 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:19.593  3015  3015 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:19.593  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:19.593  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:19.593  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:19.593  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:19.603  1018  1496 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10085
03-17 06:44:19.613  3036  3036 E Zygote  : MountEmulatedStorage()
03-17 06:44:19.613  3036  3036 E Zygote  : v2
03-17 06:44:19.613  3036  3036 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 06:44:19.613  3036  3036 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 06:44:19.613  3036  3036 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:19.613  3036  3036 I libpersona: KNOX_SDCARD checking this for 10048
03-17 06:44:19.613  3036  3036 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:19.613  1018  1327 I ActivityManager: Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3036 uid=10048 gids={50048, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-17 06:44:19.623  1195  1195 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 06:44:19.623  1018  1042 D LocationProviderProxy: applying state to connected service
03-17 06:44:19.633  3036  3036 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:19.633  1490  1505 D TP/MmsSmsProvider: query,matched:200, calling pid = 2434
03-17 06:44:19.633  1490  1505 D TP/MmsSmsProvider: match 200:Elapsed time : 1.152 ms
03-17 06:44:19.633  3036  3036 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:19.633  1018  1042 W libprocessgroup: failed to open /acct/uid_10096/pid_1409/cgroup.procs: No such file or directory
03-17 06:44:19.643  2434  2434 D Mms/SmsReceiverService: onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
03-17 06:44:19.643  2434  3053 D Mms/TelephonyPermission: isDefault true
03-17 06:44:19.643  2434  3053 D Mms/SmsReceiverService: [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
03-17 06:44:19.643  2434  3053 D Mms/SmsReceiverService: [start]    handleBootCompleted() consume time = 141.195885
03-17 06:44:19.653  1490  1505 D TP/SmsProvider: query,matched:0, calling pid = 2434
03-17 06:44:19.663  1490  1505 D TP/SmsProvider: match 0:Elapsed time : 1.876 ms
03-17 06:44:19.663  2974  2974 D USER_AGENT: UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
03-17 06:44:19.663  3036  3036 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 06:44:19.663  3036  3036 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:19.663  3036  3036 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 06:44:19.663  1490  1720 D TP/MmsSmsProvider: getThreadUnReadCount unreadCount=0 imUnreadCount=0
03-17 06:44:19.663  1490  1720 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775806
03-17 06:44:19.673  1490  2127 D TP/SmsProvider: query,matched:51, calling pid = 2434
,03-17 06:44:19.673  1490  2127 D TP/SmsProvider: match 51:Elapsed time : 1.490 ms
03-17 06:44:19.673  1490  1720 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-17 06:44:19.673  1490  1720 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775806
03-17 06:44:19.673  1490  1720 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
03-17 06:44:19.673  1490  1720 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 06:44:19.673  1490  1720 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 06:44:19.673  1490  1720 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 06:44:19.673  1490  1720 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 06:44:19.673  1490  1720 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 06:44:19.673  1490  1720 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 06:44:19.703  2974  2974 D [0]UMC:AdminManager: init - start
03-17 06:44:19.703  2974  2974 D [0]UMC:AdminManager: loadAdmins
03-17 06:44:19.723  1195  1195 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 06:44:19.723  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 06:44:19.723  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:19.723  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:19.723  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:19.723  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:19.723  1490  1720 D TP/MmsSmsProvider: delete threadId: 9223372036854775806
03-17 06:44:19.723  1490  1720 D TP/MmsSmsProvider: need read changed broadcast:false
03-17 06:44:19.723  2434  3053 D Mms/Conversation: deleteTempConversation(),deleted=0
03-17 06:44:19.743  2974  2974 D [0]UMC:AdminManager: init - end
03-17 06:44:19.743  2974  2974 D GSLBManager: migrateStoredUrlFromOldPref
03-17 06:44:19.743  2939  2939 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 134.258ms
03-17 06:44:19.763  1490  2127 I art     : Explicit concurrent mark sweep GC freed 39553(2MB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 7MB/12MB, paused 1.141ms total 85.843ms
03-17 06:44:19.763  1490  1501 D SmsProvider: Update uri=content://sms/outbox, match=8
03-17 06:44:19.773  1490  1501 D TP/MmsSmsProvider: need read changed broadcast:false
03-17 06:44:19.783  2434  3053 D Mms/SmsReceiverService: moveOutboxMessagesToFailedBox messageCount: 0
03-17 06:44:19.783  2434  3053 D Mms/SmsReceiverService: handle boot completed, sendFirstQueuedMessage()
03-17 06:44:19.783  2434  3053 D Mms/SmsReceiverService: [SIM-1]sendFirstQueuedMessage()
03-17 06:44:19.783  1490  1720 D TP/SmsProvider: query,matched:26, calling pid = 2434
03-17 06:44:19.783  2434  3013 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
03-17 06:44:19.793  3015  3015 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
03-17 06:44:19.793  1589  1599 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
03-17 06:44:19.793  1490  1720 D TP/SmsProvider: match 26:Elapsed time : 11.022 ms
03-17 06:44:19.793  1018  1588 D SettingsProvider: name = block_emergency_message
03-17 06:44:19.793  1018  1588 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 06:44:19.793  1018  1588 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 06:44:19.803  1018  1588 D SettingsProvider: selectionArgs: false
03-17 06:44:19.803  1018  1588 D SettingsProvider: selectionArgs: 10048
03-17 06:44:19.803  1018  1588 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 06:44:19.803  1018  1588 D SettingsProvider: ret = -1
03-17 06:44:19.803  1018  1714 W ActivityManager: getTasks: caller 10048 is using old GET_TASKS but privileged; allowing
03-17 06:44:19.803  2434  3053 D Mms/SmsReceiver: unregisterForServiceStateChanges, already unregistered
03-17 06:44:19.803  2434  3053 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-17 06:44:19.803  2434  3053 D Mms/TelephonyPermission: isDefault true
03-17 06:44:19.813  1514  1514 D Launcher.Model: reloadBadges entered.
03-17 06:44:19.813  1589  1599 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-17 06:44:19.813  1589  1599 D BadgeProvider: sendNotify, [notify] : null
03-17 06:44:19.813  1589  1599 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 06:44:19.813  1589  1599 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 06:44:19.813  1589  1599 D BadgeProvider: update, [UpdateCount] : 1
03-17 06:44:19.813  1249  2973 V MediaScanner: processDirectory :  /system/media
03-17 06:44:19.813  1490  2127 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2434
03-17 06:44:19.843  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
03-17 06:44:19.843  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:19.843  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:19.843  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
03-17 06:44:19.843  1332  1332 I WifiCredService: onCreate
03-17 06:44:19.853  2434  3013 D Mms/MessagingNotification: setBadgeCount(), count=0
03-17 06:44:19.853  2974  2974 D GSLBManager:  key : segd-api
03-17 06:44:19.853  2974  2974 D GSLBManager:  value : https://eu-segd-api.secb2b.com:443/v2
03-17 06:44:19.853  2434  3013 D Mms/MessagingNotification: remove alarm
03-17 06:44:19.863  1332  1332 D WifiTimerReceiver: action: android.intent.action.BOOT_COMPLETED
03-17 06:44:19.863  1332  1332 D WifiTimerReceiver: extra: Bundle[mParcelledData.dataSize=84]
03-17 06:44:19.863  1332  1332 D MY_TAG  : Action boot completed received
03-17 06:44:19.863  1332  1332 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
03-17 06:44:19.863  1018  1135 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
03-17 06:44:19.863  1018  1135 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-17 06:44:19.863  1018  1135 E WifiNative-wlan0: invaild command id : 215
03-17 06:44:19.863  3015  3015 D DSM     : [Lines:107] Normal booted
03-17 06:44:19.863  3015  3015 D DSM     : [Lines:114] Boot completed
03-17 06:44:19.873   296   296 E USB_UICC: Timeout! No signal received. Retry num = 30
03-17 06:44:19.883   313   313 I ServiceManager: Waiting for service AtCmdFwd...
03-17 06:44:19.883  1249  2973 V MediaScanner:  prescan time: 366ms (DB items: 141)
03-17 06:44:19.883  1249  2973 V MediaScanner:     scan time: 230ms (Caching mode: true), (makeEntry time: 35ms ~15%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 06:44:19.883  1249  2973 V MediaScanner: postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-17 06:44:19.883  1249  2973 V MediaScanner:    total time: 596ms
03-17 06:44:19.883  1249  2973 V MediaScanner: checked files: 133  directories : 6  (I: 0, U: 0)
03-17 06:44:19.893  1249  2973 D MediaScanner: checkDefaultSounds
03-17 06:44:19.893  1249  2973 D MediaScanner: system alarm_alert  : Vwiurug_etwofi5wgg
03-17 06:44:19.893  2974  2974 D GSLBManager:  key : umc-cdn
03-17 06:44:19.893  2974  2974 D GSLBManager:  value : 
03-17 06:44:19.893  1018  1510 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 06:44:19.893  1249  2973 D MediaScanner: OK. alarm_alert is already exist in setting DB.
03-17 06:44:19.903  1018  1510 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:19.903  1249  2973 D MediaScanner: system notification_sound  : K_Oprkltf5wgg
03-17 06:44:19.903  1018  1510 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:19.903  1018  1510 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
03-17 06:44:19.903  1249  2973 D MediaScanner: OK. notification_sound is already exist in setting DB.
03-17 06:44:19.903  1249  2973 D MediaScanner: system ringtone  : Wmfi_lpf_pwirywu5wgg
03-17 06:44:19.903  1249  2973 D MediaScanner: OK. ringtone is already exist in setting DB.
03-17 06:44:19.903  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:19.903  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:19.903  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:19.903  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:19.913  1490  1501 D TP/SmsProvider: query,matched:0, calling pid = 2434
03-17 06:44:19.913  1490  1501 D TP/SmsProvider: match 0:Elapsed time : 4.091 ms
03-17 06:44:19.933  3066  3066 E Zygote  : MountEmulatedStorage()
03-17 06:44:19.933  3066  3066 E Zygote  : v2
03-17 06:44:19.933  3066  3066 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:19.933  3066  3066 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:19.933  3066  3066 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 06:44:19.933  3066  3066 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 06:44:19.933  1018  1030 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3066 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 06:44:19.933  3066  3066 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:19.943  2974  2974 D GSLBManager:  key : segp-api
03-17 06:44:19.943  2974  2974 D GSLBManager:  value : 
03-17 06:44:19.943  1332  1332 D NearbySettings: MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
03-17 06:44:19.943  1018  1587 D SettingsProvider: name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
03-17 06:44:19.943  1332  2607 V NearbySettings: MountReceiver.mPrefHandler - 7002
03-17 06:44:19.953  1687  1700 I NotificationStore: System rebooted after Notification storage file was last written
03-17 06:44:19.953  1687  1700 I NotificationStore: Deleting the file
03-17 06:44:19.963  3056  3056 D AndroidRuntime: 
03-17 06:44:19.963  3056  3056 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 06:44:19.963  3056  3056 D AndroidRuntime: CheckJNI is OFF
03-17 06:44:19.963  3056  3056 D AndroidRuntime: readGMSProperty: start
03-17 06:44:19.963  3056  3056 D AndroidRuntime: readGMSProperty: already setted!!
03-17 06:44:19.963  3056  3056 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 06:44:19.963  3056  3056 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 06:44:19.963  3056  3056 D AndroidRuntime: readGMSProperty: end
03-17 06:44:19.963  3056  3056 D AndroidRuntime: addProductProperty: start
03-17 06:44:19.983   296   296 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-17 06:44:19.983   296   296 E USB_UICC: usb_uicc_init_qmi failed ! 
03-17 06:44:19.983   296   296 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
03-17 06:44:19.983   296   296 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
03-17 06:44:19.993  2974  2974 D GSLBManager:  key : myknoxapi
03-17 06:44:19.993  2974  2974 D GSLBManager:  value : 
03-17 06:44:20.003  1332  1332 I NearbySettings: MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
03-17 06:44:20.003  1332  1332 I NearbySettings: MountReceiver.onReceive - Internal Path
03-17 06:44:20.003  2974  2974 D GSLBManager: migrateStoredUrlFromOldPref : Finished Migrating
03-17 06:44:20.003  2974  2974 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
03-17 06:44:20.013  1018  1327 I ActivityManager: Killing 1746:com.sec.android.widgetapp.samsungapps/u0a138 (adj 15): empty #31
03-17 06:44:20.013  1018  1042 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.sync.FitnessSyncAdapterService; callingUser = 0; userId(target) = 0
03-17 06:44:20.013  3066  3066 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:20.013  3066  3066 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:20.023  1195  1195 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 06:44:20.043  2974  2974 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
03-17 06:44:20.043  2974  2974 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-17 06:44:20.053  2974  2974 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-17 06:44:20.053  1018  1128 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
03-17 06:44:20.053  2974  2974 D [0]UMC:UMCAdmin: isContainer : 0
03-17 06:44:20.053  1249  2973 D MediaScannerService: !@done scanning volume internal
03-17 06:44:20.053  2434  3063 D Mms/MessagingNotification: updateAllHistoryAsRead()
03-17 06:44:20.063  1018  1714 D SettingsProvider: name = personal_mode_enabled
03-17 06:44:20.063  1018  1128 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:20.063  1018  1128 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:20.063  1018  1128 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 06:44:20.073  1018  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
03-17 06:44:20.073  1018  1496 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:20.073  1018  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:20.073  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 06:44:20.073  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.073  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.073  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.073  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.073  1249  2973 D MediaScannerService: !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
03-17 06:44:20.083  1018  1714 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
03-17 06:44:20.083  1018  1714 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
03-17 06:44:20.083  1018  1018 D WindowManager: showStatusBarByNotification() mOpenByNotification=false
03-17 06:44:20.093  1018  1031 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
03-17 06:44:20.093  2974  2974 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
03-17 06:44:20.093  2974  2974 D [0]UMC:UMCAdmin: isContainer : 0
03-17 06:44:20.093  2974  2974 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
03-17 06:44:20.093  3095  3095 E Zygote  : MountEmulatedStorage()
03-17 06:44:20.093  3095  3095 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:20.093  3095  3095 E Zygote  : v2
03-17 06:44:20.093  3095  3095 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:20.103  3095  3095 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 06:44:20.103  3095  3095 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 06:44:20.103  3095  3095 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:20.103  1018  1030 I ActivityManager: Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3095 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 06:44:20.103  1018  1030 I ActivityManager: Killing 1570:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
03-17 06:44:20.113  2691  2691 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2691) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 06:44:20.113  2691  2691 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2691) ACTION_MEDIA_SCANNER_FINISHED = /system/media
03-17 06:44:20.113  2691  2691 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2691) ACTION_MEDIA_SCANNER_FINISHED = Ignored
03-17 06:44:20.113  3056  3056 E AffinityControl: AffinityControl: registerfunction enter
03-17 06:44:20.113  1018  1496 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
03-17 06:44:20.113  1018  1018 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
03-17 06:44:20.123  1018  1496 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:20.123  1018  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:20.123  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
03-17 06:44:20.123  1195  1838 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 06:44:20.133  1195  1838 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-17 06:44:20.133  3056  3056 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 06:44:20.143  3095  3095 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:20.143  3095  3095 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:20.143  2974  2974 D [0]UMC:GuardService: @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
03-17 06:44:20.153  1018  1030 E PersonaManagerService: inState():  stateMachine is null !!
03-17 06:44:20.153  1018  1030 I PersonaManagerService: PersonaId don't exist
03-17 06:44:20.153  1018  1030 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-17 06:44:20.153  2974  2974 D [0]UMC:CoreReceiver: Intent : android.intent.action.BOOT_COMPLETED
03-17 06:44:20.153  1018  1610 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
03-17 06:44:20.153  2974  2974 D [0]UMC:CoreReceiver:  check PreETag 
03-17 06:44:20.153  1018  1610 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:20.153  1018  1610 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:20.153  1018  1610 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
03-17 06:44:20.163  3066  3066 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 06:44:20.163  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 06:44:20.183  1490  1490 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 06:44:20.183  1490  1490 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 06:44:20.183  1490  1490 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 06:44:20.183  1490  1490 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 06:44:20.183  1490  1490 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:20.183  1490  1490 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-17 06:44:20.183  1018  1030 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-17 06:44:20.183  1018  1030 W ActivityManager: mDVFSHelper.acquire()
03-17 06:44:20.193  1195  1195 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
03-17 06:44:20.203  1018  1030 D FocusedStackFrame: Set to : 0
03-17 06:44:20.203  1018  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 06:44:20.203  1018  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-17 06:44:20.213  1514  1514 D Launcher.HomeView: onPause
03-17 06:44:20.213  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 06:44:20.213  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 06:44:20.213  1018  1030 D InputDispatcher: Focused application set to: xxxx
03-17 06:44:20.213  1018  1030 D InputDispatcher: Focus left window: 1514
03-17 06:44:20.213  1514  1514 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-17 06:44:20.223  1018  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 06:44:20.223  1018  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 06:44:20.223  1018  1610 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 06:44:20.223  1195  1195 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
03-17 06:44:20.223   257   257 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-17 06:44:20.223  1018  1610 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:20.223  1018  1610 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:20.223  1018  1610 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
03-17 06:44:20.233  3056  3056 D AndroidRuntime: Shutting down VM
03-17 06:44:20.233  3066  3066 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-17 06:44:20.243  1195  1195 D PersonaManager: PersonaID is invalid or persona doesn't exists. : 0
03-17 06:44:20.253  2434  3013 D Mms/MessagingNotification: [end]    nonBlockingUpdateMessageIndicator() consume time = 605.548125
03-17 06:44:20.253  1249  2973 D MediaProvider: savePlaylistTableInBulkDeleter started
03-17 06:44:20.253  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 06:44:20.253  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 06:44:20.253  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.253  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.253  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.253  1249  2973 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
03-17 06:44:20.253  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
03-17 06:44:20.253  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
03-17 06:44:20.263  1332  1332 I SmartcardBootCompleteReceiver: SmartcardBootCompleteReceiver - onReceive() 
03-17 06:44:20.263  2974  2974 D [0]UMC:CoreReceiver: bulk enrolled package: null
03-17 06:44:20.263  2974  2974 V [0]UMC:ProfileStorage: Enter loadList
03-17 06:44:20.263  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.263  2974  2974 D [0]UMC:CoreReceiver: handleAutoEnrollmentAndUMCAdminDeactivation
03-17 06:44:20.263  2974  2974 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
03-17 06:44:20.263  2974  2974 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
03-17 06:44:20.263  2974  2974 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-17 06:44:20.263  2974  2974 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-17 06:44:20.263  2974  2974 D [0]UMC:UMCAdmin: isContainer : 0
03-17 06:44:20.263  1249  2973 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
03-17 06:44:20.263  3095  3095 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 06:44:20.263  3066  3066 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
03-17 06:44:20.263  1195  1195 D PersonaManager: isKioskContainerExistOnDevice
03-17 06:44:20.263  1195  1195 D PersonaManager: isKioskContainerExistOnDevice
03-17 06:44:20.273  1249  2973 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-17 06:44:20.273  1018  1031 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
03-17 06:44:20.273  1018  1496 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3116 uid=10174 gids={50174, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 06:44:20.283  2974  2974 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
03-17 06:44:20.283  2974  2974 D [0]UMC:UMCAdmin: isContainer : 0
03-17 06:44:20.283  3116  3116 I libpersona: KNOX_SDCARD checking this for 10174
03-17 06:44:20.283  3116  3116 E Zygote  : MountEmulatedStorage()
03-17 06:44:20.283  3116  3116 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:20.283  1195  1195 I PhoneStatusBar: Icon Only
03-17 06:44:20.283  3116  3116 E Zygote  : v2
03-17 06:44:20.283  1195  1195 I StatusBar: Icon Only
03-17 06:44:20.283  1195  1195 D PanelView: There is/are notification(s) 
03-17 06:44:20.293  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
03-17 06:44:20.283  1195  1195 D PanelView: kidsfalse mQsExpansionEnabled:true
03-17 06:44:20.283  3116  3116 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 06:44:20.283  2974  2974 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
03-17 06:44:20.283  1195  1195 D PersonaManager: isKioskContainerExistOnDevice
03-17 06:44:20.293  1332  1332 I SmartcardBootCompleteReceiver: Received intent with action - android.intent.action.BOOT_COMPLETED
03-17 06:44:20.293  1195  1195 I PhoneStatusBar: Icon Only
03-17 06:44:20.293  1195  1195 I StatusBar: Icon Only
03-17 06:44:20.293  1195  1195 D PanelView: There is/are notification(s) 
03-17 06:44:20.293  1195  1195 D PanelView: kidsfalse mQsExpansionEnabled:true
03-17 06:44:20.293  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:20.293  3116  3116 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 06:44:20.293  3116  3116 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 06:44:20.303  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:20.303  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 06:44:20.333  2066  2066 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
03-17 06:44:20.333  2066  2066 I dhcpcd  : wlan0: no IPv6 Routers available
03-17 06:44:20.333  2974  2974 D [0]UMC:ByodSetupStarter: Container ID : 0
03-17 06:44:20.353  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
03-17 06:44:20.353  1018  1325 I art     : Explicit concurrent mark sweep GC freed 141272(7MB) AllocSpace objects, 6(1846KB) LOS objects, 33% free, 26MB/40MB, paused 5.438ms total 324.843ms
03-17 06:44:20.363  2974  2974 V [0]UMC:Utils: checkAppScreen() : com.test.thalitest
03-17 06:44:20.363  2974  2974 I [0]UMC:Core: shutdown
03-17 06:44:20.363  1249  2973 D MediaProvider: savePlaylistTableInBulkDeleter started
03-17 06:44:20.363  3116  3116 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:20.363  1018  1588 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
03-17 06:44:20.363  1249  2973 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
03-17 06:44:20.363  3116  3116 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:20.363  1249  2973 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
03-17 06:44:20.373  1018  1588 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:20.373  1018  1588 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:20.373  1018  1588 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
03-17 06:44:20.373  1514  1514 V ActivityThread: updateVisibility : ActivityRecord{1c6676f8 token=android.os.BinderProxy@29e612fd {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-17 06:44:20.373  2974  2974 D [0]UMC:GuardService: @GuardService - stopService Result = true
03-17 06:44:20.383  1195  1195 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
03-17 06:44:20.383  1018  1042 W libprocessgroup: failed to open /acct/uid_10057/pid_1570/cgroup.procs: No such file or directory
03-17 06:44:20.383  1018  1042 W libprocessgroup: failed to open /acct/uid_10138/pid_1746/cgroup.procs: No such file or directory
03-17 06:44:20.393  1018  1715 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 06:44:20.393  1018  1715 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 06:44:20.393  1018  1715 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 06:44:20.393  2974  2974 I art     : System.exit called, status: 0
03-17 06:44:20.393  2974  2974 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
03-17 06:44:20.393  1514  1514 D Launcher.HomeView: onStop
03-17 06:44:20.393  1514  1514 V ActivityThread: updateVisibility : ActivityRecord{1c6676f8 token=android.os.BinderProxy@29e612fd {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-17 06:44:20.403  1332  1332 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
03-17 06:44:20.403  1490  1505 D TP/MmsSmsProvider: query,matched:200, calling pid = 2434
03-17 06:44:20.403   352   352 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
03-17 06:44:20.403  1490  1505 D TP/MmsSmsProvider: match 200:Elapsed time : 6.945 ms
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
03-17 06:44:20.413  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
03-17 06:44:20.413  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
03-17 06:44:20.423  1687  1825 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-17 06:44:20.423  1687  1825 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-17 06:44:20.423  1687  1825 I GLSUser : [GLSUser] Extracting token using key: Auth
03-17 06:44:20.423  1687  1825 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-17 06:44:20.423  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
03-17 06:44:20.423  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
03-17 06:44:20.423  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
03-17 06:44:20.423  1018  1715 D PersonaManager: isKioskContainerExistOnDevice
03-17 06:44:20.423  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
03-17 06:44:20.423  3066  3066 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
03-17 06:44:20.423  1249  2973 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-17 06:44:20.433  3066  3066 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
03-17 06:44:20.433  1018  1714 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
03-17 06:44:20.443  3056  3056 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-17 06:44:20.443  1249  2973 D MediaScanner: Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,03-17 06:44:20.453  1018  1714 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:20.453  1018  1714 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:20.453  1018  1714 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:20.463  1332  1332 I SmartcardBootCompleteReceiver: Broadcast sent with current lockscreen type
,03-17 06:44:20.463  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.463  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.463  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.463  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.463  2991  3012 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,03-17 06:44:20.463  2991  3012 I SecureStorage: [INFO]: SPID(0x00000002)Skip using SecureStorageExceptionJNI
,03-17 06:44:20.483  3141  3141 E Zygote  : MountEmulatedStorage()
03-17 06:44:20.483  3141  3141 E Zygote  : v2
03-17 06:44:20.483  3141  3141 I libpersona: KNOX_SDCARD checking this for 10086
03-17 06:44:20.483  3141  3141 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:20.483  3141  3141 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:20.483  3141  3141 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:20.483  3141  3141 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 06:44:20.503  1249  2973 V MediaScanner: processDirectory :  /storage/emulated/0,
,03-17 06:44:20.503  1018  1031 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3141 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a,
03-17 06:44:20.503  1018  1031 I ActivityManager: Killing 2176:com.vlingo.midas/u0a31 (adj 15): empty #31
03-17 06:44:20.503  1018  1030 I ActivityManager: Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2974)(adj 0) has died(71,1078)
,03-17 06:44:20.513  1687  1825 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 06:44:20.513  1514  1514 D Launcher: onTrimMemory. Level: 20
,03-17 06:44:20.513  1018  1610 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 06:44:20.523  1018  1610 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:20.523  1018  1610 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:20.523  1018  1610 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:20.523  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.523  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.523  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.523  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.523  1249  2973 D MediaScanner: Skipping:
03-17 06:44:20.523  1249  2973 D MediaScanner: 7klwibgf7fvntblfd7(75ebcf7
,03-17 06:44:20.533  1249  2973 D MediaScanner: Skipping:
03-17 06:44:20.533  1249  2973 D MediaScanner: 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,03-17 06:44:20.533  3141  3141 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:20.533  3141  3141 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:20.543  3157  3157 E Zygote  : MountEmulatedStorage()
03-17 06:44:20.543  3157  3157 E Zygote  : v2
03-17 06:44:20.543  3157  3157 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:20.543  3157  3157 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:20.543  3157  3157 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:20.553  3157  3157 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:20.553  3157  3157 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:20.563  1018  1031 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3157 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:20.563  1249  2973 V MediaScanner: processDirectory :  /storage/extSdCard
,03-17 06:44:20.563  1018  1031 I ActivityManager: Killing 2208:com.sec.android.app.videoplayer/u0a50 (adj 15): empty #31
03-17 06:44:20.563  1249  2973 W MediaScanner: Error opening directory, reason : Permission denied.
,03-17 06:44:20.563  1249  2973 W MediaScanner: 7klwibgf7fxlKdCbid7
,03-17 06:44:20.563  1018  1610 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 06:44:20.573  1018  1610 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:20.573  1018  1610 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:20.573  1018  1610 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:20.573  1249  2973 V MediaScanner:  prescan time: 73ms (DB items: 27)
,03-17 06:44:20.573  1249  2973 V MediaScanner:     scan time: 68ms (Caching mode: true), (makeEntry time: 53ms ~77%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 06:44:20.573  1249  2973 V MediaScanner: postscan time: 7ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
,03-17 06:44:20.583  1249  2973 V MediaScanner:    total time: 148ms
03-17 06:44:20.583  1249  2973 V MediaScanner: checked files: 10  directories : 17  (I: 0, U: 0)
,03-17 06:44:20.583  1018  1714 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,03-17 06:44:20.583  1018  1714 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:20.583  1018  1714 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:20.583  1018  1714 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 06:44:20.583  3157  3157 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:20.593  3157  3157 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:20.603  1249  2973 D MediaScannerService: !@done scanning volume external
,03-17 06:44:20.603  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,03-17 06:44:20.603  1018  1018 D SensorService: [SO] activate (ident=0xb7bd9088, enabled=0)
03-17 06:44:20.603  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-17 06:44:20.613  2691  2691 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2691) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 06:44:20.613  2691  2691 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2691) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
03-17 06:44:20.613  2691  2691 D FactoryTestApp: [DummyFtClient$sendBootCompletedAndFinish](2691) ...
03-17 06:44:20.613  2691  2691 D FactoryTestApp: [Support$Values.getString](2691) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 06:44:20.613  2691  2691 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2691) mConnectionMode = gsm
,03-17 06:44:20.613  2691  2691 D FactoryTestApp: [IPCWriterToSecPhoneService$ResponseWriter](2691) Create IPCWriterToSecPhoneService
03-17 06:44:20.613  2691  2691 I FactoryTestApp: [IPCWriterToSecPhoneService$connectToSecPhoneService](2691)  
,03-17 06:44:20.613  2691  2691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,03-17 06:44:20.613  1018  1714 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,03-17 06:44:20.623  1018  1714 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:20.623  1018  1714 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:20.623  1018  1714 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
03-17 06:44:20.623  1018  1018 D SensorManager: unregisterListener ::   
,03-17 06:44:20.623  1018  1018 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-17 06:44:20.623  1305  1305 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 06:44:20.623  1305  1305 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 06:44:20.623  1018  1018 D SensorService: [SO] changed settle time [1]
03-17 06:44:20.623  1018  1018 D SensorService: [SO] setDelay [66000000]
03-17 06:44:20.623  1018  1018 D SensorService: [SO] activate (ident=0xb7a46788, enabled=1)
03-17 06:44:20.623  1018  1018 D SensorService: [SO] AR_init
03-17 06:44:20.623  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-17 06:44:20.633  1018  1018 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-17 06:44:20.633  1490  1720 D TP/SmsProvider: query,matched:0, calling pid = 2434
,03-17 06:44:20.633  1305  1305 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 06:44:20.653  1305  1305 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 06:44:20.653  1490  1720 D TP/SmsProvider: match 0:Elapsed time : 13.230 ms
03-17 06:44:20.653  1305  1305 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
03-17 06:44:20.663  2709  2802 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
03-17 06:44:20.673  2765  2932 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-17 06:44:20.673  1305  1305 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
03-17 06:44:20.673  1305  1305 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 06:44:20.673  1305  1305 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,03-17 06:44:20.673  1305  1305 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-17 06:44:20.673  1305  1305 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 06:44:20.673  1305  1305 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-17 06:44:20.673  1305  1305 D daemonapp: [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,03-17 06:44:20.683  3116  3116 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,03-17 06:44:20.683  1018  1513 D SettingsProvider: name = aw_daemon_service_key_version_check
,03-17 06:44:20.683  1018  1513 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-17 06:44:20.683  1018  1513 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 06:44:20.683  1018  1513 D SettingsProvider: selectionArgs: false
03-17 06:44:20.683  1018  1513 D SettingsProvider: selectionArgs: 10162
03-17 06:44:20.683  1018  1513 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 06:44:20.683  1018  1513 D SettingsProvider: ret = -1
,03-17 06:44:20.693  2709  2802 D BluetoothMediaBrowser: no now playing list
03-17 06:44:20.693  2709  2802 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,03-17 06:44:20.703  1018  1040 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 06:44:20.703  3116  3116 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6933-6936)
03-17 06:44:20.703  3116  3116 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 06:44:20.703  1490  1505 D TP/SmsProvider: query,matched:51, calling pid = 2434
,03-17 06:44:20.713  2691  2691 I FactoryTestApp: [IPCWriterToSecPhoneService$onServiceConnected](2691) connected done
03-17 06:44:20.713  2691  2691 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2691) Send Response Message to SecPhone
03-17 06:44:20.713  2691  2691 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2691) Response ��
,03-17 06:44:20.713  1490  1505 D TP/SmsProvider: match 51:Elapsed time : 12.450 ms
,03-17 06:44:20.723   308  1075 D AT_Distributor: Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-17 06:44:20.733  2691  2691 D FactoryTestApp: [IPCWriterToSecPhoneService$handleMessage](2691) Send BOOTING COMPLETED done
,03-17 06:44:20.733  1195  1195 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 06:44:20.733  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 06:44:20.733  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:20.733  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:20.733  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:20.733  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:20.733  2434  3053 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
,03-17 06:44:20.743  1589  3060 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,03-17 06:44:20.753  1018  1042 W libprocessgroup: failed to open /acct/uid_10050/pid_2208/cgroup.procs: No such file or directory
,03-17 06:44:20.753  1018  1042 W libprocessgroup: failed to open /acct/uid_10031/pid_2176/cgroup.procs: No such file or directory
,03-17 06:44:20.773  3116  3116 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b183d50},
03-17 06:44:20.773  3116  3116 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 06:44:20.773  3116  3116 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-17 06:44:20.773  1018  1040 D SensorService: [SO] 0.172 0.421 10.247
03-17 06:44:20.773  1018  1040 D SensorService: [SO] [100 -> 255]
,03-17 06:44:20.793  3157  3157 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-17 06:44:20.803  3116  3116 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-17 06:44:20.803  3116  3116 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 06:44:20.803  3116  3116 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 06:44:20.803  3141  3141 E UpdateRequestReceiver: ignoring update request
,03-17 06:44:20.813  1018  1513 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10162
,03-17 06:44:20.823  1514  1514 D Launcher.Model: reloadBadges entered.
,03-17 06:44:20.823  1332  1332 D [SBeam] : SBeamEnabler.initPreferenceForSbeam : 0
,03-17 06:44:20.823  1589  1599 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
,03-17 06:44:20.823  1305  1305 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 06:44:20.823  1589  1599 D BadgeProvider: sendNotify, [notify] : null
03-17 06:44:20.823  1589  1599 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 06:44:20.823  1589  1599 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 06:44:20.823  1589  1599 D BadgeProvider: update, [UpdateCount] : 1
,03-17 06:44:20.823   308  1075 D AT_Distributor: SetAtdStatus(), 1_1_0
03-17 06:44:20.823   308  1075 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-17 06:44:20.833  3141  3141 E UpdateRequestReceiver: ignoring update request
,03-17 06:44:20.833  2004  3126 I iu.UploadsManager: #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,03-17 06:44:20.833  2434  3053 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-17 06:44:20.833  3116  3116 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-17 06:44:20.843  3116  3116 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-17 06:44:20.843  3116  3116 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 06:44:20.843  3116  3116 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 06:44:20.843  3116  3116 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 06:44:20.843  3116  3116 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 06:44:20.843  3116  3116 I Adreno-EGL: Local Branch: 
03-17 06:44:20.843  3116  3116 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 06:44:20.843  3116  3116 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 06:44:20.843  3116  3116 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 06:44:20.843  2765  2841 E BooksSync: Soft error
03-17 06:44:20.843  2765  2841 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-17 06:44:20.843  2765  2841 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-17 06:44:20.843  2765  2841 E BooksSync: Sync error
03-17 06:44:20.843  2765  2841 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-17 06:44:20.843  2765  2841 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-17 06:44:20.843  2765  2841 I BooksSync: Finished books sync
,03-17 06:44:20.843  1305  1305 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-17 06:44:20.843   288   288 E SMD     : DCD OFF
,03-17 06:44:20.853  1305  1305 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 06:44:20.853  1305  1305 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 06:44:20.853  1305  1305 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-17 06:44:20.853  1305  1305 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 06:44:20.863  2434  3053 D Mms/MessagingNotification: remove alarm
,03-17 06:44:20.873  1332  1332 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
03-17 06:44:20.873  1332  1332 I SettingSearch/SearchIntentReceiver: search setting db init!!
,03-17 06:44:20.873  1305  1305 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
03-17 06:44:20.873  1305  1305 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-17 06:44:20.873  3141  3141 E UpdateRequestReceiver: ignoring update request
,03-17 06:44:20.873  1018  1042 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 24965, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-17 06:44:20.873  1305  1305 D daemonapp: [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1458193460876
03-17 06:44:20.873  1305  1305 D daemonapp: [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1458215040000
,03-17 06:44:20.873  1305  1305 D daemonapp: [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
03-17 06:44:20.873  1305  1305 D daemonapp: [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,03-17 06:44:20.873  1332  1332 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,03-17 06:44:20.883   313   313 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 06:44:20.883  1332  3191 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
,03-17 06:44:20.893  2434  3188 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-17 06:44:20.893  1195  1195 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:20.903  1305  1305 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458215040000
,03-17 06:44:20.913   257   430 I SurfaceFlinger: id=8 Removed Mauncher (5/8)
,03-17 06:44:20.913   257  1058 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
,03-17 06:44:20.913  1490  1505 D TP/SmsProvider: query,matched:0, calling pid = 2434
,03-17 06:44:20.913  1305  1305 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,03-17 06:44:20.913  1305  1305 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458215040000
,03-17 06:44:20.933  1490  1505 D TP/SmsProvider: match 0:Elapsed time : 16.915 ms
,03-17 06:44:20.933  3141  3141 E UpdateRequestReceiver: ignoring update request
,03-17 06:44:20.943  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.943  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.943  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.943  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.953  3202  3202 E Zygote  : MountEmulatedStorage(),
03-17 06:44:20.953  3202  3202 E Zygote  : v2
03-17 06:44:20.953  3202  3202 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:20.953  1305  1305 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED,
03-17 06:44:20.953  3202  3202 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:20.963  1305  1305 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
03-17 06:44:20.963  3202  3202 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 06:44:20.963  3202  3202 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 06:44:20.963  3202  3202 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:20.963  1018  1714 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3202 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 06:44:20.973  1018  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.973  1018  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.973  1018  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:20.973  1018  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:20.973  3157  3157 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-17 06:44:20.983  3157  3157 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
03-17 06:44:20.983  3202  3202 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-17 06:44:20.983  3157  3157 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
03-17 06:44:20.983  3157  3157 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-17 06:44:20.983  3202  3202 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:20.983  3157  3157 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
03-17 06:44:20.983  3157  3157 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
03-17 06:44:20.983  1018  1588 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3214 uid=10150 gids={50150, 9997} abi=armeabi-v7a
,03-17 06:44:20.993  3214  3214 E Zygote  : MountEmulatedStorage()
03-17 06:44:20.993  3214  3214 E Zygote  : v2
03-17 06:44:20.993  3214  3214 I libpersona: KNOX_SDCARD checking this for 10150
03-17 06:44:20.993  3214  3214 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:20.993  3214  3214 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:20.993  3214  3214 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 06:44:20.993  3214  3214 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 06:44:21.003  1018  1030 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-17 06:44:21.003  1018  1030 D SecContentProvider2: mCursor = null
,03-17 06:44:21.013   303   303 I art     : Explicit concurrent mark sweep GC freed 8762(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 22.101ms
,03-17 06:44:21.023  1919  1919 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,03-17 06:44:21.033  1018  1513 D ActivityManager: retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
,03-17 06:44:21.033  1018  1513 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:21.033   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 19.391ms
,03-17 06:44:21.033  1018  1513 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 06:44:21.033  1018  1513 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,03-17 06:44:21.033  1919  1919 D SecUISvc: Service started flags 0 startId 1
,03-17 06:44:21.043  1018  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.043  1018  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.043  1018  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.043  1018  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:21.043  3202  3202 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 06:44:21.043  1919  3236 D SecUISvc: Thread created.
,03-17 06:44:21.043  3141  3141 E UpdateRequestReceiver: ignoring update request
,03-17 06:44:21.053   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 627us total 18.364ms
,03-17 06:44:21.053  3214  3214 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:21.053  3214  3214 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:21.073  3239  3239 E Zygote  : MountEmulatedStorage()
,03-17 06:44:21.073  3239  3239 E Zygote  : v2
03-17 06:44:21.073  3239  3239 I libpersona: KNOX_SDCARD checking this for 10028
03-17 06:44:21.073  3239  3239 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:21.073  3239  3239 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 06:44:21.073  3239  3239 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 06:44:21.073  3239  3239 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 06:44:21.073  1018  3139 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3239 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 06:44:21.083  1018  1496 I ActivityManager: Killing 2223:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
,03-17 06:44:21.083  2434  3053 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 834.767864
,03-17 06:44:21.103  2991  2991 E BluetoothHeadset: BTStateChangeCB is registed
,03-17 06:44:21.103  1018  1610 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.103  1018  1610 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.103  1018  1610 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.103  1018  1610 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:21.103  2991  2991 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,03-17 06:44:21.113  3239  3239 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:21.113  3239  3239 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:21.113  3254  3254 E Zygote  : MountEmulatedStorage()
03-17 06:44:21.113  3254  3254 E Zygote  : v2
03-17 06:44:21.113  3254  3254 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:21.113  3254  3254 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:21.123  3254  3254 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 06:44:21.123  1018  1610 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3254 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:21.123  3254  3254 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:21.123  3254  3254 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 06:44:21.133  1018  1587 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,03-17 06:44:21.133  1018  1587 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:21.133  1018  1587 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:21.133  1018  1587 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,03-17 06:44:21.143  2991  2991 E BluetoothHeadset: BluetoothHeadset service is binded
03-17 06:44:21.143  3141  3141 E UpdateRequestReceiver: ignoring update request
,03-17 06:44:21.143  3202  3202 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,03-17 06:44:21.143  2991  2991 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,03-17 06:44:21.153  1018  1513 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.153  1018  1513 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.153  1018  1513 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.153  1018  1513 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:21.163  3254  3254 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:21.163  3254  3254 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:21.163  3272  3272 E Zygote  : MountEmulatedStorage()
03-17 06:44:21.163  3272  3272 I libpersona: KNOX_SDCARD checking this for 10094
03-17 06:44:21.163  3272  3272 E Zygote  : v2
03-17 06:44:21.163  3272  3272 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:21.173  3272  3272 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 06:44:21.173  3272  3272 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-17 06:44:21.173  3272  3272 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:21.183  1018  1513 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3272 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,03-17 06:44:21.183  1018  1513 I ActivityManager: Killing 1529:com.android.printspooler/u0a136 (adj 15): empty #31
03-17 06:44:21.183  1018  1513 I ActivityManager: Killing 2393:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,03-17 06:44:21.193  1018  1714 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,03-17 06:44:21.193  1018  1714 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:21.193  1018  1714 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:21.193  1018  1714 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,03-17 06:44:21.203  1018  1042 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.sync.FitnessSyncAdapterService; callingUser = 0; userId(target) = 0
,03-17 06:44:21.203  3272  3272 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:21.203  3272  3272 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:21.233  2004  3126 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 398 ms
,03-17 06:44:21.273  2991  2991 D BluetoothA2dp: Proxy object connected
,03-17 06:44:21.283  3272  3272 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-17 06:44:21.283  3272  3272 D elm:15183: ELMEngine.ELMEngine( context ).
,03-17 06:44:21.283  3272  3272 D elm:15183: MDMBridge.setEnterpriseBridge()
,03-17 06:44:21.283  1018  1587 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,03-17 06:44:21.283  1018  1587 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:21.283  1018  1587 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:21.283  1018  1587 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-17 06:44:21.293  3272  3272 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-17 06:44:21.293  3272  3272 D elm:15183: ElmAgentService : onCreate()
,03-17 06:44:21.293  1428  1428 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,03-17 06:44:21.293  3272  3290 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,03-17 06:44:21.293  3272  3272 D elm:15183: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
03-17 06:44:21.293  3272  3272 D elm:15183: BootCompletedState : startBootCompleted() call
,03-17 06:44:21.293  3272  3272 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 06:44:21.303  3272  3272 I elm:15183: Get License : 0
03-17 06:44:21.303  3272  3272 D elm:15183: ElmAgentService : onDestroy().
,03-17 06:44:21.303  1018  1510 I ActivityManager: Killing 2415:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,03-17 06:44:21.313  3116  3116 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 06:44:21.313  1018  1042 W libprocessgroup: failed to open /acct/uid_10113/pid_2223/cgroup.procs: No such file or directory
,03-17 06:44:21.333  3116  3116 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 06:44:21.333  1018  1042 W libprocessgroup: failed to open /acct/uid_10142/pid_2393/cgroup.procs: No such file or directory
,03-17 06:44:21.333  1018  1042 W libprocessgroup: failed to open /acct/uid_10136/pid_1529/cgroup.procs: No such file or directory
,03-17 06:44:21.333  3116  3116 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 06:44:21.333  3116  3116 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-17 06:44:21.343  1428  1428 V EmergencyMode: [EmergencyBase] setBootTime
03-17 06:44:21.343  3116  3116 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
03-17 06:44:21.343  1428  1428 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
,03-17 06:44:21.343  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:21.353  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.353  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:21.353  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:21.353  3202  3202 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,03-17 06:44:21.363  3202  3202 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
03-17 06:44:21.363  3295  3295 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:21.363  3295  3295 E Zygote  : MountEmulatedStorage()
03-17 06:44:21.363  3295  3295 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:21.363  3295  3295 E Zygote  : v2
03-17 06:44:21.363  3202  3202 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
03-17 06:44:21.363  3295  3295 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:21.373  3295  3295 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:21.373  1018  1327 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3295 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:21.373  3295  3295 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:21.373  3116  3116 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 06:44:21.373  3116  3116 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 06:44:21.393  3295  3295 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:21.393  3295  3295 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:21.403  1018  1042 W libprocessgroup: failed to open /acct/uid_10139/pid_2415/cgroup.procs: No such file or directory
,03-17 06:44:21.453  3295  3295 I CameraApp: CameraApp.onCreate()... mFeature : null
,03-17 06:44:21.453  3295  3295 I testFeature: Feature.Feature(context)
03-17 06:44:21.453  3295  3295 I testFeature: Feature.readInternalDefaultXml()
,03-17 06:44:21.453  3295  3295 I testFeature: ResetFeatureValue
,03-17 06:44:21.463  3295  3295 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
,03-17 06:44:21.463  3295  3295 I CameraApp: CameraApp.getAppFeature()...
,03-17 06:44:21.463  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:21.463  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.463  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:21.463  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:21.473  3315  3315 E Zygote  : MountEmulatedStorage()
03-17 06:44:21.473  3315  3315 I libpersona: KNOX_SDCARD checking this for 10100
03-17 06:44:21.473  3315  3315 E Zygote  : v2
03-17 06:44:21.473  3315  3315 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:21.483  3315  3315 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:21.483  3315  3315 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:21.483  3315  3315 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:21.483  1018  1496 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3315 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
03-17 06:44:21.483  1018  1496 I ActivityManager: Killing 2495:com.wsomacp/u0a25 (adj 15): empty #31
,03-17 06:44:21.493  1018  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.493  1018  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.493  1018  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.493  1018  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:21.503  3116  3331 D OpenGLRenderer: Render dirty regions requested: true
,03-17 06:44:21.513  3333  3333 E Zygote  : MountEmulatedStorage(),
03-17 06:44:21.513  3333  3333 E Zygote  : v2
03-17 06:44:21.513  3333  3333 I libpersona: KNOX_SDCARD checking this for 10009
03-17 06:44:21.513  3333  3333 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:21.513  3315  3315 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:21.513  3333  3333 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:21.513  3315  3315 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:21.513  3333  3333 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 06:44:21.513  3333  3333 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 06:44:21.513  1018  3139 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3333 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 06:44:21.523  1018  1610 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 06:44:21.523  1018  1610 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 06:44:21.523  1018  1610 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 06:44:21.523  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 06:44:21.523  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 06:44:21.523  3116  3198 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-17 06:44:21.523  3116  3116 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 06:44:21.523  3116  3116 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-17 06:44:21.543  3333  3333 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:21.543  3333  3333 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:21.543   257   257 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,03-17 06:44:21.543  3315  3315 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
,03-17 06:44:21.553  3315  3315 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,03-17 06:44:21.553  1018  1128 I ActivityManager: Killing 1718:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,03-17 06:44:21.553  1018  1325 D ActivityManager: retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,03-17 06:44:21.563  1018  1715 D InputDispatcher: Focus entered window: 3116
,03-17 06:44:21.563  1018  1325 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:21.563  1018  1325 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:21.563  1018  1325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,03-17 06:44:21.563  3254  3254 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,03-17 06:44:21.563  1018  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:21.563  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-17 06:44:21.563  3254  3254 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-17 06:44:21.573  3116  3116 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-17 06:44:21.573  3116  3331 I OpenGLRenderer: Initialized EGL, version 1.4
03-17 06:44:21.573  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 06:44:21.573  1018  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:21.573  1018  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.573  1018  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:21.573  1687  3352 I GoogleHttpClient: GMS http client unavailable, use old client
,03-17 06:44:21.583  3116  3331 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096,
03-17 06:44:21.583  3116  3331 D OpenGLRenderer: Enabling debug mode 0,
,03-17 06:44:21.583  3254  3349 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
03-17 06:44:21.583  3254  3254 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,03-17 06:44:21.593  3254  3254 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-17 06:44:21.593  3254  3349 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,03-17 06:44:21.593  3254  3254 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,03-17 06:44:21.593  3254  3254 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,03-17 06:44:21.603  3254  3254 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,03-17 06:44:21.603  3254  3254 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
,03-17 06:44:21.603  3254  3254 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-17 06:44:21.603  3254  3349 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
03-17 06:44:21.603  3254  3254 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-17 06:44:21.603  3254  3254 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,03-17 06:44:21.613  3254  3254 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,03-17 06:44:21.613  3254  3254 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,03-17 06:44:21.613  3358  3358 E Zygote  : MountEmulatedStorage()
,03-17 06:44:21.613  3358  3358 E Zygote  : v2
03-17 06:44:21.613  3358  3358 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:21.613  3358  3358 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:21.613  3358  3358 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:21.613  1018  1588 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3358 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:21.623  3358  3358 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:21.623  3358  3358 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:21.623  1018  1042 W libprocessgroup: failed to open /acct/uid_10015/pid_1718/cgroup.procs: No such file or directory
,03-17 06:44:21.623  1018  1042 W libprocessgroup: failed to open /acct/uid_10025/pid_2495/cgroup.procs: No such file or directory
,03-17 06:44:21.633  3358  3358 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:21.633  3358  3358 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:21.723  1195  1195 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 06:44:21.723  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 06:44:21.723  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:21.723  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:21.723  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:21.723  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:21.803  3202  3202 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,03-17 06:44:21.803  3202  3202 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,03-17 06:44:21.803  1018  1587 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 06:44:21.813  3202  3202 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,03-17 06:44:21.813  1018  1610 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,03-17 06:44:21.813  1018  1610 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:21.813  1018  1610 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:21.813  1018  1610 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 06:44:21.823  1195  1195 I StatusBar: Icon Only
,03-17 06:44:21.823  1195  1195 D PanelView: There is/are notification(s) 
,03-17 06:44:21.823  1018  3375 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 06:44:21.823  3239  3239 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-17 06:44:21.823  3202  3202 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,03-17 06:44:21.823  1018  1128 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.823  1018  1128 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.823  1018  1128 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.823  1018  1128 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:21.833  3202  3202 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,03-17 06:44:21.833  3202  3202 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,03-17 06:44:21.843  1782  1782 I SamsungIME: getCurrentCandidateView
,03-17 06:44:21.843  3116  3116 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@5ebe30a time:38072
,03-17 06:44:21.843  3380  3380 E Zygote  : MountEmulatedStorage()
,03-17 06:44:21.843  3380  3380 E Zygote  : v2
03-17 06:44:21.843  3380  3380 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:21.843  3380  3380 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:21.843  3202  3202 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,03-17 06:44:21.843  3380  3380 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:21.843  3202  3202 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,03-17 06:44:21.853  3380  3380 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:21.853  3380  3380 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:21.853  3202  3202 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
03-17 06:44:21.853  1018  1128 I ActivityManager: Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=3380 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 06:44:21.853  3202  3202 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
03-17 06:44:21.853  1018  1128 I ActivityManager: Killing 2524:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
03-17 06:44:21.853  3202  3202 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
03-17 06:44:21.853  3202  3202 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,03-17 06:44:21.853  3202  3202 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,03-17 06:44:21.863  1195  1195 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
,03-17 06:44:21.863  1195  1195 D OverheatReceiver: into the SAFE_MODE_ACTION
03-17 06:44:21.863  1195  1195 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
,03-17 06:44:21.863  1195  1195 D OverheatReceiver: isSafeMode = false
,03-17 06:44:21.873  3202  3202 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,03-17 06:44:21.873  3202  3202 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
03-17 06:44:21.873  3202  3293 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,03-17 06:44:21.873  1018  1049 I ActivityManager: Displayed Component not be shown by security: +1s621ms
,03-17 06:44:21.883  1018  1049 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 06:44:21.883  3202  3202 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
03-17 06:44:21.883  1018  1043 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 06:44:21.883  1490  1490 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
,03-17 06:44:21.883  1018  1049 D CustomFrequencyManagerService: FrequencyrequestList.getNextMaxCPUCoreRequest, index: 1
,03-17 06:44:21.883  1018  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{15f46cd5 u0 com.test.thalitest/.MainActivity t236} time:38114
03-17 06:44:21.883  1018  1049 W ActivityManager: mDVFSHelper.release()
03-17 06:44:21.883   313   313 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
03-17 06:44:21.883  1018  1587 D SettingsProvider: name = internet_call_settings_visibility
03-17 06:44:21.883  1018  1587 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 06:44:21.883  1018  1587 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 06:44:21.883  1018  1587 D SettingsProvider: selectionArgs: false
03-17 06:44:21.883  1018  1587 D SettingsProvider: selectionArgs: 1001
03-17 06:44:21.883  1018  1587 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 06:44:21.883  1018  1587 D SettingsProvider: ret = -1
03-17 06:44:21.883  1490  1490 D PhoneUtilsCommon: isSupportVoLTE is false.
,03-17 06:44:21.883  3202  3202 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,03-17 06:44:21.893  3202  3202 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,03-17 06:44:21.893  3202  3202 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,03-17 06:44:21.893  3202  3202 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,03-17 06:44:21.893  3380  3380 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:21.893  3202  3202 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
,03-17 06:44:21.893  3380  3380 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:21.893  1455  1455 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,03-17 06:44:21.903  3202  3293 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,03-17 06:44:21.903  1018  1715 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,03-17 06:44:21.903  1018  1715 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:21.903  3202  3293 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
03-17 06:44:21.903  1018  1715 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:21.903  1018  1715 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 06:44:21.913  1455  1455 I Telecom : InCallController: Attempting to bind to InCall com.google.android.gms, is dupe? false 
,03-17 06:44:21.913  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,03-17 06:44:21.913  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:21.913  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:21.913  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 06:44:21.913  1018  1325 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = -2
,03-17 06:44:21.913  1018  1325 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:21.913  1018  1325 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-17 06:44:21.913  1018  1325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.google.android.gms
,03-17 06:44:21.913  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.913  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.913  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:21.913  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:21.923  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2524/cgroup.procs: No such file or directory
,03-17 06:44:21.933  3400  3400 E Zygote  : MountEmulatedStorage()
03-17 06:44:21.933  3400  3400 E Zygote  : v2
03-17 06:44:21.933  3400  3400 I libpersona: KNOX_SDCARD checking this for 10012
03-17 06:44:21.933  3400  3400 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:21.933  3400  3400 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:21.933  3400  3400 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:21.933  3400  3400 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 06:44:21.943  1018  1325 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=3400 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,03-17 06:44:21.943  1018  1128 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,03-17 06:44:21.943  1018  1128 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:21.943  1018  1128 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:21.943  1018  1128 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 06:44:21.943  3202  3202 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
03-17 06:44:21.943  1455  1455 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,03-17 06:44:21.943  1455  1455 I Telecom : InCallController: Unbinding from InCallService unbind
,03-17 06:44:21.963  1782  1782 D SamsungIME: Dismiss ExpandCandiate
,03-17 06:44:21.963  3400  3400 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:21.963  3400  3400 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:21.983  3400  3400 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 06:44:21.983  3400  3400 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 06:44:22.003  3380  3380 D KnoxSetupWizardDbHelper: dbMigrationFlag : false
,03-17 06:44:22.003  3202  3293 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,03-17 06:44:22.003  3202  3202 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
03-17 06:44:22.003  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.003  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.003  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.003  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:22.023  3400  3400 I MultiDex: VM with version 2.1.0 has multidex support
03-17 06:44:22.023  3400  3400 I MultiDex: install
03-17 06:44:22.023  3400  3400 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-17 06:44:22.023  3420  3420 E Zygote  : MountEmulatedStorage()
03-17 06:44:22.023  3420  3420 I libpersona: KNOX_SDCARD checking this for 10003
03-17 06:44:22.023  3420  3420 E Zygote  : v2
03-17 06:44:22.023  3420  3420 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:22.023  3420  3420 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:22.023  3420  3420 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:22.023  3420  3420 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:22.033  1018  1018 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3420 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,03-17 06:44:22.043  1782  1782 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 06:44:22.053  3380  3380 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,03-17 06:44:22.063  3420  3420 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:22.063  3420  3420 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:22.073  3400  3400 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-17 06:44:22.083   257   430 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
,03-17 06:44:22.083   257   435 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
,03-17 06:44:22.093  3254  3269 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 06:44:22.103  3254  3269 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 06:44:22.103  3254  3269 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 06:44:22.113  3254  3265 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 06:44:22.113  3254  3265 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 06:44:22.113  3254  3265 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 06:44:22.123  3380  3380 D KnoxShortcutUtil: getIsShortcutMigrationFor_2_3_0_Done true
,03-17 06:44:22.123  3380  3380 D ShortcutReceiver:  KnoxContainerVersion 2.4.0
03-17 06:44:22.123  3380  3380 D ShortcutReceiver:  shortcut migration not required 
,03-17 06:44:22.123  1018  1610 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:22.123  1018  1610 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.123  1018  1610 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.123  1018  1610 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:22.133  3400  3400 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@222fc7a4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 06:44:22.133  3400  3400 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-17 06:44:22.133  3400  3400 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 06:44:22.133   283   794 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
,03-17 06:44:22.133   283   794 D audio_hw_extn: audio_extn_get_parameters: returns 
03-17 06:44:22.133   283   794 V msm8974_platform: platform_get_parameters: exit: returns - 
03-17 06:44:22.133   283   794 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-17 06:44:22.133   283   794 I str_params: key: 'call_forwarding' value: ''
03-17 06:44:22.133  1927  1927 V InCall  : ProximitySensor -  - screenonImmediately: false
03-17 06:44:22.133  1927  1927 V InCall  : ProximitySensor -  - mFromRcsShare: false
03-17 06:44:22.133  3439  3439 E Zygote  : MountEmulatedStorage()
03-17 06:44:22.133  3439  3439 E Zygote  : v2
03-17 06:44:22.133  3439  3439 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:22.133  3439  3439 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:22.133  3439  3439 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:22.143  1927  1927 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
03-17 06:44:22.143  1018  1610 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3439 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 06:44:22.143  3439  3439 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:22.143  3439  3439 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:22.143  1018  1610 I ActivityManager: Killing 2543:com.sec.android.omc/1000 (adj 15): empty #31
,03-17 06:44:22.143  1927  1927 D ScoverManager: serviceVersion : 16908288
,03-17 06:44:22.143  1018  1327 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 06:44:22.153  1927  1927 D InCall  : InCallUtils - isCoverClosed false
03-17 06:44:22.153  1455  1455 I Telecom : ProximitySensorManager: Proximity wake lock already released
03-17 06:44:22.153  1018  1714 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 06:44:22.153  1927  1927 D InCall  : InCallUtils - isCoverClosed false
03-17 06:44:22.153  1927  1927 I InCall  : InCallPresenter -  - InCallState = NO_CALLS
03-17 06:44:22.153  1927  1927 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
03-17 06:44:22.153  1927  1927 D InCall  : InCallPresenter -  - dismissCoverDialog()...
03-17 06:44:22.163  3439  3439 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:22.163  3439  3439 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:22.173   303   303 I art     : Explicit concurrent mark sweep GC freed 8776(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 659us total 30.447ms
03-17 06:44:22.173  1927  1927 I InCall  : CallSContextMotion - stopPutDownListening
03-17 06:44:22.173  1927  1927 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,03-17 06:44:22.183  1018  1018 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 06:44:22.183  1018  1714 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 06:44:22.183  1927  1927 D InCall  : InCallUtils - isCoverClosed false
03-17 06:44:22.193   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 613us total 16.861ms
,03-17 06:44:22.193  1195  1195 D PhoneStatusBarView: setCallBackground:0
,03-17 06:44:22.203  3439  3439 E KnoxSetupWizardClient: isShipMode : 1
,03-17 06:44:22.203  3439  3439 I KnoxSetupWizardClient: onReceive : android.intent.action.BOOT_COMPLETED
,03-17 06:44:22.203   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 16.979ms
,03-17 06:44:22.223  1018  1587 I ActivityManager: Killing 2560:com.sec.modem.settings/1000 (adj 15): empty #31
,03-17 06:44:22.233  3420  3420 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-17 06:44:22.243  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.243  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.243  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.243  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:22.243  3239  3239 W art     : Verification of android.content.Intent com.google.android.finsky.utils.NotificationManager.createDefaultClickIntent(android.content.Context, java.lang.String, java.lang.String, java.lang.String, java.lang.String) took 122.496ms
,03-17 06:44:22.253  3116  3116 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3116
,03-17 06:44:22.273  3458  3458 E Zygote  : MountEmulatedStorage()
03-17 06:44:22.273  3458  3458 E Zygote  : v2
03-17 06:44:22.273  3458  3458 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:22.273  3458  3458 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:22.273  3458  3458 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 06:44:22.273  3458  3458 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 06:44:22.273  3458  3458 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:22.273  1018  1327 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3458 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:22.283  1018  1327 I ActivityManager: Killing 2609:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #31
,03-17 06:44:22.283  1018  1327 I ActivityManager: Killing 2575:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #32
,03-17 06:44:22.283  1018  1327 I ActivityManager: Killing 2585:com.sec.tcpdumpservice/1000 (adj 15): empty #33
,03-17 06:44:22.313  1927  1927 D VideoCallManager: Instantiating VideoCallManager
,03-17 06:44:22.313  1927  1927 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 06:44:22.313  3458  3458 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:22.313  1927  1927 I GFX construct_block_size_descriptor_2d second part: took 2.486511ms for 0*0 texture 0
,03-17 06:44:22.323  2511  2511 D StatusChecker: onReceive : android.intent.action.BOOT_COMPLETED
03-17 06:44:22.323  3458  3458 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:22.323  2511  2511 I StatusChecker: onReceive : net.mt.init : DONE
,03-17 06:44:22.323  1927  1927 I GFX generate_partition_tables: took 5.317239ms for 0*0 texture 0
,03-17 06:44:22.323  1927  1927 I GFX raster: took 11.562396ms for 176*144 texture 0
03-17 06:44:22.323  1927  1927 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb760bda8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb760b678 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 06:44:22.343  1927  1927 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,03-17 06:44:22.343  1927  1927 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 06:44:22.343  1927  1927 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 06:44:22.343  1927  1927 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 06:44:22.343  1927  1927 I Adreno-EGL: Local Branch: 
03-17 06:44:22.343  1927  1927 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 06:44:22.343  1927  1927 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 06:44:22.343  1927  1927 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 06:44:22.363  1927  1927 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 06:44:22.363  1018  1587 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.363  1927  1927 I glCompressedTexImage2D: took 0.250365ms for 320*61440 texture 37809
03-17 06:44:22.363  1018  1587 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.363  1018  1587 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.363  1018  1587 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:22.373  1927  1927 I draw setup: took 10.284011ms for 320*240 texture 37809
03-17 06:44:22.373  1927  1927 E GFX GPU raster: drawn
,03-17 06:44:22.383  1927  1927 I GFX GPU raster ASTC: took 38.946875ms for 320*240 texture 12
03-17 06:44:22.383  1927  1927 I GFX raster: took 39.031094ms for 320*240 texture 0
03-17 06:44:22.383  1927  1927 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb760bd28 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb760b890 counterpartCT=4 counterpartW=320 counterparth=240
,03-17 06:44:22.393  1018  1587 I ActivityManager: Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=3479 uid=10116 gids={50116, 9997} abi=armeabi-v7a
,03-17 06:44:22.393  1018  1587 I ActivityManager: Killing 2625:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,03-17 06:44:22.393  3479  3479 E Zygote  : MountEmulatedStorage()
03-17 06:44:22.393  3479  3479 I libpersona: KNOX_SDCARD checking this for 10116
,03-17 06:44:22.393  3479  3479 E Zygote  : v2
03-17 06:44:22.393  3479  3479 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:22.393  3479  3479 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:22.393  3479  3479 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:22.403  3479  3479 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:22.403  1927  1927 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
03-17 06:44:22.413  1927  1927 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 06:44:22.413  1927  1927 I glCompressedTexImage2D: took 0.545729ms for 480*122880 texture 37813
03-17 06:44:22.413  1927  1927 I draw setup: took 0.895313ms for 480*640 texture 37813
03-17 06:44:22.413  1927  1927 E GFX GPU raster: drawn
,03-17 06:44:22.413  3439  3455 W System.err: java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
03-17 06:44:22.413  3439  3455 W System.err: 	at android.os.Parcel.readException(Parcel.java:1544)
03-17 06:44:22.413  3439  3455 W System.err: 	at android.os.Parcel.readException(Parcel.java:1493)
03-17 06:44:22.413  3439  3455 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
03-17 06:44:22.413  3439  3455 W System.err: 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
03-17 06:44:22.413  3439  3455 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
03-17 06:44:22.413  3439  3455 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,03-17 06:44:22.413  1927  1927 I GFX GPU raster ASTC: took 8.398334ms for 480*640 texture 12
03-17 06:44:22.413  1927  1927 I GFX raster: took 8.472031ms for 480*640 texture 0
03-17 06:44:22.413  1927  1927 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb760b890 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb7838f40 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 06:44:22.433  3479  3479 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:22.433  3479  3479 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:22.443  3254  3349 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-17 06:44:22.453  3254  3349 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 06:44:22.463  1018  1030 I ActivityManager: Killing 2476:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,03-17 06:44:22.463  1927  1927 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,03-17 06:44:22.463  1927  1927 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 06:44:22.463  1927  1927 I glCompressedTexImage2D: took 0.328854ms for 440*116864 texture 37809,
03-17 06:44:22.463  1927  1927 I draw setup: took 0.687604ms for 440*330 texture 37809
03-17 06:44:22.463  1927  1927 E GFX GPU raster: drawn
,03-17 06:44:22.473  1927  1927 I GFX GPU raster ASTC: took 4.613333ms for 440*330 texture 12
03-17 06:44:22.473  1927  1927 I GFX raster: took 4.711145ms for 440*330 texture 0
03-17 06:44:22.473  1927  1927 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb783d198 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb783d558 counterpartCT=4 counterpartW=440 counterparth=330
,03-17 06:44:22.473  3254  3349 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,03-17 06:44:22.473  3254  3349 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7,
,03-17 06:44:22.473  3254  3349 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7,
,03-17 06:44:22.513  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2543/cgroup.procs: No such file or directory
,03-17 06:44:22.523  1927  1927 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-17 06:44:22.523  1927  1927 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 06:44:22.523  1927  1927 I glCompressedTexImage2D: took 0.537552ms for 480*163840 texture 37811
03-17 06:44:22.523  1927  1927 I draw setup: took 0.966771ms for 480*640 texture 37811
03-17 06:44:22.523  1927  1927 E GFX GPU raster: drawn
,03-17 06:44:22.543  1927  1927 I GFX GPU raster ASTC: took 6.639531ms for 480*640 texture 12
03-17 06:44:22.543  1927  1927 I GFX raster: took 6.725417ms for 480*640 texture 0
03-17 06:44:22.543  1927  1927 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb787cb68 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb7838cf8 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 06:44:22.593  3458  3458 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false,
,03-17 06:44:22.613  3458  3458 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,03-17 06:44:22.613  1782  1782 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 06:44:22.613  3458  3458 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-17 06:44:22.613  3458  3458 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-17 06:44:22.623  1018  1715 I art     : Explicit concurrent mark sweep GC freed 25250(1248KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 26MB/40MB, paused 2.760ms total 201.177ms
,03-17 06:44:22.633  1927  1927 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 06:44:22.633  1018  1715 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,03-17 06:44:22.633  1018  1327 E Tethering: No numeric data
03-17 06:44:22.633  1018  1715 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:22.633  1018  1715 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:22.633  1018  1715 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-17 06:44:22.633  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.633  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.633  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.633  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:22.643  1927  1927 I GFX construct_block_size_descriptor_2d second part: took 2.568125ms for 0*0 texture 0,
03-17 06:44:22.653  2765  2797 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
03-17 06:44:22.653  1927  1927 I GFX generate_partition_tables: took 7.378959ms for 0*0 texture 0,
,03-17 06:44:22.653  1927  1927 I GFX raster: took 12.018072ms for 176*144 texture 0,
03-17 06:44:22.653  1927  1927 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb783d118 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb7836758 counterpartCT=4 counterpartW=176 counterparth=144,
,03-17 06:44:22.663  1018  1510 E Tethering: No numeric data,
,03-17 06:44:22.673  3503  3503 E Zygote  : MountEmulatedStorage(),
03-17 06:44:22.673  3503  3503 E Zygote  : v2
03-17 06:44:22.673  3503  3503 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:22.673  3503  3503 I libpersona: KNOX_SDCARD not a persona,
03-17 06:44:22.673  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2560/cgroup.procs: No such file or directory
03-17 06:44:22.673  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2585/cgroup.procs: No such file or directory
,03-17 06:44:22.673  1018  1325 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3503 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 06:44:22.673  3254  3349 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString,
,03-17 06:44:22.673  1927  1927 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144,
,03-17 06:44:22.683  1927  1927 I GFX construct_block_size_descriptor_2d second part: took 2.272917ms for 0*0 texture 0
,03-17 06:44:22.683  1927  1927 I GFX generate_partition_tables: took 6.145573ms for 0*0 texture 0
,03-17 06:44:22.693  1927  1927 I GFX raster: took 10.764791ms for 176*144 texture 0
,03-17 06:44:22.693  1927  1927 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb78367c0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb7836948 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 06:44:22.693  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2476/cgroup.procs: No such file or directory
03-17 06:44:22.693  1018  1042 W libprocessgroup: failed to open /acct/uid_10131/pid_2575/cgroup.procs: No such file or directory
03-17 06:44:22.693  1018  1042 W libprocessgroup: failed to open /acct/uid_10068/pid_2609/cgroup.procs: No such file or directory
03-17 06:44:22.693  1018  1042 W libprocessgroup: failed to open /acct/uid_10069/pid_2625/cgroup.procs: No such file or directory
,03-17 06:44:22.693  3503  3503 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:22.693  1927  1927 D ScoverManager: registerListener
03-17 06:44:22.693  3503  3503 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:22.693  1018  1513 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 06:44:22.693  1782  1782 I SamsungIME: KeybaordView init() : load resources
03-17 06:44:22.693  1018  1587 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 06:44:22.693  1018  1587 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@387e0509, pid : 1927, uid : 1001, type : 1
,03-17 06:44:22.703  3503  3503 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:22.703  1018  1588 E Tethering: No numeric data
,03-17 06:44:22.703  1018  1714 E Tethering: No numeric data
,03-17 06:44:22.703  3420  3420 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-17 06:44:22.703  2004  2004 I GAv4-SVC: Google Analytics 7.8.99 is starting up.
03-17 06:44:22.703  3420  3420 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-17 06:44:22.703  3420  3420 D UserAnalysis: Create SecureDbHelper
,03-17 06:44:22.713  3479  3479 I PageBuddyNotiSvc: Intent received : action=android.intent.action.BOOT_COMPLETED
,03-17 06:44:22.713  1018  1587 E Tethering: No numeric data
,03-17 06:44:22.713  1927  1927 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
03-17 06:44:22.713  3254  3349 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-17 06:44:22.713  1018  1128 E Tethering: No numeric data
,03-17 06:44:22.723  1195  1195 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-17 06:44:22.723  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 06:44:22.723  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:22.733  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:22.733  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:22.733  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:22.733  3254  3349 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-17 06:44:22.733  3254  3349 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,03-17 06:44:22.743  3254  3349 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,03-17 06:44:22.753  3254  3349 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/18/13:15:33
,03-17 06:44:22.753  3254  3349 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/17/06:44:22
03-17 06:44:22.753  3254  3350 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
03-17 06:44:22.753  3254  3349 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,03-17 06:44:22.753  3420  3420 D IntelligenceServiceApplication: onCreate(),
03-17 06:44:22.753  3503  3503 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:22.753  3420  3420 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.,
03-17 06:44:22.763  3503  3503 D ActivityThread: Added TimaKeyStore provider,
03-17 06:44:22.763  3254  3349 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,03-17 06:44:22.763  3254  3350 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 06:44:22.773  3479  3479 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
03-17 06:44:22.773  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.773  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.773  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.773  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:22.773  3254  3350 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
03-17 06:44:22.773  3420  3420 D IntelligenceServiceApplication: no applications having user consent for prediction
03-17 06:44:22.773  3254  3350 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-17 06:44:22.783  3202  3293 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,03-17 06:44:22.793  3526  3526 E Zygote  : MountEmulatedStorage()
,03-17 06:44:22.793  3526  3526 E Zygote  : v2
03-17 06:44:22.793  3526  3526 I libpersona: KNOX_SDCARD checking this for 10060,
,03-17 06:44:22.793  3526  3526 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:22.793  3254  3350 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-17 06:44:22.793  3526  3526 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:22.793  1018  1030 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3526 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-17 06:44:22.793  3254  3350 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
03-17 06:44:22.793  3254  3350 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-17 06:44:22.793  3254  3350 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
03-17 06:44:22.793  3526  3526 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 06:44:22.803  1018  1030 I ActivityManager: Killing 2647:com.android.calendar/u0a135 (adj 15): empty #31
,03-17 06:44:22.803  3526  3526 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:22.803  1018  3139 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:22.803  1018  3139 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:22.803  1018  3139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:22.803  1018  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,03-17 06:44:22.813  3479  3479 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,03-17 06:44:22.813  3254  3350 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,03-17 06:44:22.813  3254  3350 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-17 06:44:22.813  1018  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.813  1018  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.813  1018  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:22.813  1018  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:22.833  3116  3116 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-17 06:44:22.843  3536  3536 E Zygote  : MountEmulatedStorage()
03-17 06:44:22.843  3536  3536 E Zygote  : v2
03-17 06:44:22.843  3536  3536 I libpersona: KNOX_SDCARD checking this for 10125
03-17 06:44:22.843  3536  3536 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:22.843  3536  3536 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 06:44:22.843  1018  1588 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=3536 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 06:44:22.843  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,03-17 06:44:22.853  3536  3536 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:22.853  3536  3536 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:22.853  3420  3420 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-17 06:44:22.873  3202  3293 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-17 06:44:22.883  1018  2806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-17 06:44:22.883  3526  3526 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:22.893  3526  3526 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:22.893  3420  3420 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-17 06:44:22.893  3420  3420 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
,03-17 06:44:22.893  3254  3350 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-17 06:44:22.923  1782  1782 I SamsungIME: getCurrentKeyboard
03-17 06:44:22.923  1782  1782 I SamsungIME: getTextKeyboard
,03-17 06:44:22.933  3536  3536 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:22.933  3202  3293 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
03-17 06:44:22.933  3536  3536 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:22.953  3202  3293 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,03-17 06:44:22.953  3503  3503 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-17 06:44:22.953  3503  3503 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-17 06:44:22.963  3503  3503 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-17 06:44:22.973  3254  3350 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,03-17 06:44:22.983  3239  3239 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,03-17 06:44:22.983  3536  3536 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 06:44:22.983  3536  3536 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-17 06:44:22.983  3536  3536 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 06:44:22.993  3254  3349 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,03-17 06:44:22.993  1782  1782 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 06:44:23.003  1332  3191 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
,03-17 06:44:23.023  1332  3191 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
,03-17 06:44:23.033  1018  2859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 06:44:23.043  1018  1042 W libprocessgroup: failed to open /acct/uid_10135/pid_2647/cgroup.procs: No such file or directory
,03-17 06:44:23.053  1018  1587 E Tethering: No numeric data
,03-17 06:44:23.053  1018  1513 E Tethering: No numeric data
,03-17 06:44:23.053  1018  1327 E Tethering: No numeric data
,03-17 06:44:23.053  3116  3377 D jxcore_app_log: JniHelper::setJavaVM(0xb7267450), pthread_self() = -1216776264
,03-17 06:44:23.063  3536  3536 D QuickConnect: PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,03-17 06:44:23.063  3536  3536 D QuickConnect: Util.setSCRunningSetting - [value]0
,03-17 06:44:23.063  3116  3377 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 06:44:23.063  3116  3377 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 06:44:23.063  3116  3377 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 06:44:23.063  3116  3377 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 06:44:23.063  3116  3377 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-17 06:44:23.073  3116  3377 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21f64d61 added. We now have 1 listener(s)
,03-17 06:44:23.073  1018  1715 D SettingsProvider: name = scon_is_running
,03-17 06:44:23.073  1018  1715 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 06:44:23.073  1018  1715 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-17 06:44:23.073  1018  1715 D SettingsProvider: selectionArgs: false
03-17 06:44:23.073  1018  1715 D SettingsProvider: selectionArgs: 10125
03-17 06:44:23.073  3116  3377 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:51:18:22
,03-17 06:44:23.073  1018  1715 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 06:44:23.073  3116  3377 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:51:18:22"}
,03-17 06:44:23.073  1018  1715 D SettingsProvider: ret = -1
,03-17 06:44:23.073  3116  3377 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:51:18:22"}
03-17 06:44:23.073  3116  3377 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-17 06:44:23.073  3116  3377 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 06:44:23.083  3116  3377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 06:44:23.083  3116  3377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 06:44:23.083  3116  3377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 06:44:23.083  3116  3377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:51:18:22
03-17 06:44:23.083  3116  3377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 06:44:23.083  3116  3377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 06:44:23.083  3116  3377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 06:44:23.083  3116  3377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 06:44:23.083  3116  3377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 06:44:23.083  3116  3377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-17 06:44:23.083  3116  3377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13591974 added. We now have 1 listener(s)
,03-17 06:44:23.083  3116  3377 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 06:44:23.083  1018  1715 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,03-17 06:44:23.093  3536  3536 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,03-17 06:44:23.093  3503  3517 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 06:44:23.093  1195  1195 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:23.103  3116  3377 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-17 06:44:23.103  3536  3536 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
03-17 06:44:23.103  3116  3377 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-17 06:44:23.103  3116  3377 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,03-17 06:44:23.103  3116  3377 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-17 06:44:23.103  3116  3377 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-17 06:44:23.103  1018  1510 E Tethering: No numeric data
,03-17 06:44:23.103  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:23.103  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:23.103  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:23.103  1018  1327 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:23.133  3566  3566 E Zygote  : MountEmulatedStorage()
,03-17 06:44:23.133  3566  3566 E Zygote  : v2
03-17 06:44:23.133  3566  3566 I libpersona: KNOX_SDCARD checking this for 10131
03-17 06:44:23.133  3566  3566 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:23.133  1018  1327 I ActivityManager: Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=3566 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
03-17 06:44:23.133  3566  3566 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:23.133  3566  3566 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:23.133  1018  1327 I ActivityManager: Killing 2748:com.android.keychain/1000 (adj 15): empty #31
,03-17 06:44:23.143  3566  3566 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:23.143  3116  3377 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-17 06:44:23.153  3116  3377 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:51:18:22
,03-17 06:44:23.153  1018  1513 V VibratorService: hasVibrator - useVibetonz: true
,03-17 06:44:23.163  1332  3191 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,03-17 06:44:23.163  3254  3349 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,03-17 06:44:23.163  3566  3566 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:23.163  3566  3566 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:23.163  1018  1513 V VibratorService: hasVibrator - useVibetonz: true
,03-17 06:44:23.163  3116  3377 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 06:44:23.163  3116  3377 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 06:44:23.163  3116  3377 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 06:44:23.163  3116  3377 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 06:44:23.163  3116  3377 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 06:44:23.163  3116  3377 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 06:44:23.163  3116  3377 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 06:44:23.163  3116  3377 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-17 06:44:23.163  3116  3377 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 06:44:23.163  3116  3377 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 06:44:23.183  3116  3116 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 06:44:23.183  3116  3116 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 06:44:23.193  1018  1587 V VibratorService: hasVibrator - useVibetonz: true
,03-17 06:44:23.203  3458  3458 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
03-17 06:44:23.203  1332  3191 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 06:44:23.203  3116  3116 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
03-17 06:44:23.203  3458  3458 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
03-17 06:44:23.203  3458  3458 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 06:44:23.213  1018  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:23.213  1018  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:23.213  1018  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:23.213  1018  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:23.213  3254  3349 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
03-17 06:44:23.213  3566  3566 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 06:44:23.213  3566  3566 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:23.213  3566  3566 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 06:44:23.213  3566  3566 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 06:44:23.223  3583  3583 E Zygote  : MountEmulatedStorage()
03-17 06:44:23.223  3583  3583 E Zygote  : v2
03-17 06:44:23.223  3583  3583 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:23.223  3583  3583 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:23.223  3583  3583 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:23.233  3583  3583 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:23.233  3583  3583 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:23.233  1018  1588 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3583 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:23.233  1018  1588 I ActivityManager: Killing 2889:flipboard.boxer.app/u0a99 (adj 15): empty #31
,03-17 06:44:23.233  1018  1588 I ActivityManager: Killing 2817:com.android.email/u0a145 (adj 15): empty #32
,03-17 06:44:23.273  3583  3583 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:23.273  3583  3583 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:23.303  1018  1128 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:23.303  1018  1128 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:23.303  1018  1128 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:23.303  1018  1128 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-17 06:44:23.303  3566  3566 D SBrowserFeatureFlag: initialized in static block : loadCscFeatureValue() succeed! 
,03-17 06:44:23.323  3116  3131 I art     : Background sticky concurrent mark sweep GC freed 28531(1835KB) AllocSpace objects, 4(64KB) LOS objects, 7% free, 10MB/11MB, paused 11.215ms total 81.856ms
,03-17 06:44:23.333  3566  3566 D ManifestProvider: onCreate()
,03-17 06:44:23.333  3526  3526 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.8.KK_APP
,03-17 06:44:23.363  3566  3566 E NetworkSettingsReceiver: onReceive: android.intent.action.BOOT_COMPLETED
,03-17 06:44:23.363  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:23.363  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:23.363  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:23.363  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:23.383  3602  3602 E Zygote  : MountEmulatedStorage(),
03-17 06:44:23.383  3602  3602 E Zygote  : v2
,03-17 06:44:23.383  3602  3602 I libpersona: KNOX_SDCARD checking this for 10062
03-17 06:44:23.383  3602  3602 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 06:44:23.383  3602  3602 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:23.383  3602  3602 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:23.383  3602  3602 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:23.383  1018  1714 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3602 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 06:44:23.393  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2748/cgroup.procs: No such file or directory
03-17 06:44:23.393  1018  1042 W libprocessgroup: failed to open /acct/uid_10099/pid_2889/cgroup.procs: No such file or directory
,03-17 06:44:23.403  3583  3583 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-17 06:44:23.403  1018  1042 W libprocessgroup: failed to open /acct/uid_10145/pid_2817/cgroup.procs: No such file or directory
,03-17 06:44:23.403  3583  3583 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-17 06:44:23.413  3239  3239 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 06:44:23.413  3239  3239 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 06:44:23.423  3602  3602 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:23.423  3602  3602 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:23.433  1332  3191 D ScoverManager: serviceVersion : 16908288
,03-17 06:44:23.443  3566  3566 E SBrowserFeatureFlag: initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@3c3e416f
,03-17 06:44:23.443  3566  3566 D SBrowserFeatureFlag: initialize : initSupportedPkg() succeed! 
03-17 06:44:23.443  3566  3566 I VerificationLog: SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,03-17 06:44:23.493  3503  3517 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2,
,03-17 06:44:23.503  1018  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:23.503  1018  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:23.503  1018  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:23.503  1018  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:23.513  3621  3621 E Zygote  : MountEmulatedStorage()
03-17 06:44:23.513  3621  3621 E Zygote  : v2
03-17 06:44:23.513  3621  3621 I libpersona: KNOX_SDCARD checking this for 10135
03-17 06:44:23.513  3621  3621 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:23.513  3621  3621 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:23.523  3621  3621 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:23.523  3621  3621 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:23.523  1018  1510 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3621 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,03-17 06:44:23.533  3583  3583 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-17 06:44:23.553  3583  3583 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-17 06:44:23.553  3621  3621 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:23.553  3621  3621 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:23.583  3602  3602 I ExternalOEMControlProvider: onCreate
,03-17 06:44:23.583  3254  3350 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,03-17 06:44:23.633  3621  3621 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 06:44:23.633  3621  3621 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 06:44:23.633  3621  3621 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 06:44:23.643  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:23.643  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:23.643  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:23.643  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:23.653  1018  1325 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3638 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:23.653  3638  3638 E Zygote  : MountEmulatedStorage(),
03-17 06:44:23.653  1018  1325 I ActivityManager: Killing 2281:flipboard.app/u0a98 (adj 15): empty #31
03-17 06:44:23.663  3638  3638 E Zygote  : v2
03-17 06:44:23.663  3638  3638 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:23.663  3638  3638 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:23.663  3638  3638 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 06:44:23.663  3638  3638 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 06:44:23.663  3638  3638 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:23.673  1018  1496 D SettingsProvider: name = PREVIOUS_SYS_TIME
,03-17 06:44:23.673  1018  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 06:44:23.673  1018  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 06:44:23.673  1018  1496 D SettingsProvider: selectionArgs: false
03-17 06:44:23.673  1018  1496 D SettingsProvider: selectionArgs: 10062
03-17 06:44:23.673  1018  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 06:44:23.673  1018  1496 D SettingsProvider: ret = -1
,03-17 06:44:23.683  1018  1496 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,03-17 06:44:23.703  1018  1031 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
03-17 06:44:23.703  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 06:44:23.703  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 06:44:23.703  1018  1031 D SettingsProvider: selectionArgs: false
03-17 06:44:23.703  1018  1031 D SettingsProvider: selectionArgs: 10062
03-17 06:44:23.703  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 06:44:23.703  1018  1031 D SettingsProvider: ret = -1
,03-17 06:44:23.703  1018  1031 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,03-17 06:44:23.713  2691  3176 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3176)  
,03-17 06:44:23.723  1195  1195 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:23.723  1018  1128 I ActivityManager: Killing 2946:com.sec.usbsettings/1000 (adj 15): empty #31
,03-17 06:44:23.733  3638  3638 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:23.733  3638  3638 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:23.743  1018  1128 I ActivityManager: Killing 2369:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,03-17 06:44:23.743  3239  3521 D Volley  : [408] DiskBasedCache.clear: Cache cleared.
,03-17 06:44:23.753  3239  3395 D Volley  : [401] DiskBasedCache.clear: Cache cleared.
,03-17 06:44:23.773  1195  1195 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:23.773  1018  1588 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,03-17 06:44:23.773  3254  3350 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 06:44:23.783  1018  1588 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:23.783  1018  1588 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:23.783  1018  1588 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 06:44:23.783  1018  1587 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,03-17 06:44:23.793  1195  1195 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-17 06:44:23.793  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 06:44:23.793  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:23.793  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:23.793  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:23.793  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:23.803  1018  1587 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:23.803  1018  1587 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:23.803  1018  1587 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-17 06:44:23.803  3638  3638 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 06:44:23.813  1305  1678 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 06:44:23.813  1687  1687 V GLSUser : [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
,03-17 06:44:23.813  1018  1128 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,03-17 06:44:23.823  1018  1128 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:23.823  1018  1128 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:23.823  1018  1128 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 06:44:23.833  1018  1587 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,03-17 06:44:23.833  1018  1587 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:23.833  1018  1587 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:23.833  1018  1587 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-17 06:44:23.843  2004  2004 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,03-17 06:44:23.843  1018  1715 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,03-17 06:44:23.843  1018  1715 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:23.843  1018  1715 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:23.843  1018  1715 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:23.843   288   288 E SMD     : DCD OFF
,03-17 06:44:23.853  1018  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:23.863  3239  3239 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-17 06:44:23.863  3239  3239 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,03-17 06:44:23.863  3254  3350 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,03-17 06:44:23.863  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:23.873  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:23.873  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 06:44:23.873  3638  3638 I ServiceMode: received = ACTION_BOOT_COMPLETED
03-17 06:44:23.873  3638  3638 I ServiceMode: setReferenceIsDumpState : 0
,03-17 06:44:23.883  1018  1496 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:23.883  1018  1496 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:23.883  1018  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:23.883  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:23.913  1018  1714 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:23.913  1018  1714 W ActivityManager: userId = 0, bbcId = -10000,
03-17 06:44:23.913  1018  1714 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:23.913  1018  1714 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-17 06:44:23.923  1018  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:23.923  1018  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:23.923  1018  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:23.923  1018  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:23.923  1018  1042 W libprocessgroup: failed to open /acct/uid_10044/pid_2369/cgroup.procs: No such file or directory
,03-17 06:44:23.933  3667  3667 E Zygote  : MountEmulatedStorage()
03-17 06:44:23.933  3667  3667 E Zygote  : v2
03-17 06:44:23.933  3667  3667 I libpersona: KNOX_SDCARD checking this for 10042
03-17 06:44:23.933  3667  3667 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:23.933  3667  3667 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:23.943  3667  3667 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:23.943  3667  3667 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 06:44:23.963  1018  1588 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3667 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-17 06:44:23.963  3583  3583 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized,
,03-17 06:44:23.963  3583  3583 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W,
03-17 06:44:23.973  3583  3583 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
03-17 06:44:23.973  1018  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:23.973  1018  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:23.973  1018  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:23.973  1018  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:23.973  3583  3583 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
03-17 06:44:23.973  3583  3583 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
03-17 06:44:23.973  3583  3583 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
03-17 06:44:23.973  3583  3583 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
03-17 06:44:23.973  3239  3239 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-17 06:44:23.973   303   303 I art     : Explicit concurrent mark sweep GC freed 8752(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 652us total 29.415ms
,03-17 06:44:23.993   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 621us total 17.068ms
,03-17 06:44:23.993  3667  3667 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:24.003  3667  3667 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:24.013   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 597us total 17.754ms
,03-17 06:44:24.023  1332  3191 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 06:44:24.023  3686  3686 E Zygote  : MountEmulatedStorage()
,03-17 06:44:24.023  3686  3686 E Zygote  : v2
03-17 06:44:24.023  3686  3686 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:24.023  3686  3686 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:24.033  3686  3686 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 06:44:24.033  1018  1510 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3686 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:24.033  3686  3686 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 06:44:24.033  1332  3191 D Settings_Utils: isSupportVNFestival SM-A500FU XEO
03-17 06:44:24.033  3686  3686 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:24.043  1018  1510 I ActivityManager: Killing 1893:com.android.defcontainer/u0a4 (adj 15): empty #31
,03-17 06:44:24.043  1018  1714 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,03-17 06:44:24.043  1018  1714 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:24.043  1018  1714 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:24.043  1018  1714 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-17 06:44:24.053  3202  3293 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-17 06:44:24.053  1018  1513 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,03-17 06:44:24.063  1018  1513 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:24.063  1018  1513 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:24.063  1018  1513 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-17 06:44:24.063  3686  3686 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:24.063  3686  3686 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:24.073  3333  3333 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 06:44:24.073  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:24.073  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:24.073  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:24.073  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:24.083  3116  3581 W jxcore-log: Initializing JXcore engine
03-17 06:44:24.083  3116  3581 W jxcore-log: JXcore engine is ready
,03-17 06:44:24.103  3704  3704 E Zygote  : MountEmulatedStorage()
,03-17 06:44:24.103  3704  3704 E Zygote  : v2
03-17 06:44:24.103  3704  3704 I libpersona: KNOX_SDCARD checking this for 10139
03-17 06:44:24.103  3704  3704 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:24.103  3704  3704 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:24.103  3704  3704 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 06:44:24.113  3704  3704 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:24.113  1018  1714 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=3704 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,03-17 06:44:24.123  1018  1325 I ActivityManager: Killing 2434:com.android.mms/u0a46 (adj 15): empty #31
,03-17 06:44:24.153  3704  3704 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:24.153  3704  3704 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:24.163  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2946/cgroup.procs: No such file or directory
03-17 06:44:24.163  1018  1042 W libprocessgroup: failed to open /acct/uid_10098/pid_2281/cgroup.procs: No such file or directory
,03-17 06:44:24.163  1018  1042 W libprocessgroup: failed to open /acct/uid_10004/pid_1893/cgroup.procs: No such file or directory
,03-17 06:44:24.173  1883  1883 E audit   : type=1400 msg=audit(1458193464.173:205): avc:  denied  { ioctl } for  pid=3581 comm="Thread-395" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-17 06:44:24.173  1883  1883 E audit   :  SEPF_SM-A500FU_5.0.2_0027
03-17 06:44:24.173  1883  1883 E audit   : type=1300 msg=audit(1458193464.173:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9f5968f8 items=0 ppid=303 ppcomm=main pid=3581 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="Thread-395" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-17 06:44:24.173  1883  1883 E audit   : type=1320 msg=audit(1458193464.173:205): 
,03-17 06:44:24.173  1687  1687 D PersistentNotificationBroadcastReceiver: Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,03-17 06:44:24.173  3333  3333 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-17 06:44:24.183  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:24.183  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:24.183  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:24.183  1018  1496 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:24.193  3667  3667 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
03-17 06:44:24.193  3116  3581 W jxcore-log: Starting JXcore engine
,03-17 06:44:24.193  3239  3239 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-17 06:44:24.203  3720  3720 E Zygote  : MountEmulatedStorage(),
03-17 06:44:24.203  3720  3720 I libpersona: KNOX_SDCARD checking this for 10014
03-17 06:44:24.203  3720  3720 E Zygote  : v2
03-17 06:44:24.203  3720  3720 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:24.203  3704  3704 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 06:44:24.203  3720  3720 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 06:44:24.203  3704  3704 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
03-17 06:44:24.203  3704  3704 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 06:44:24.203  3704  3704 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 06:44:24.203  3704  3704 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.,
,03-17 06:44:24.203  3720  3720 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 06:44:24.213  3720  3720 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,03-17 06:44:24.213  1018  1496 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3720 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,03-17 06:44:24.223  1018  1496 I ActivityManager: Killing 3036:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
,03-17 06:44:24.253  1018  1496 D CountryDetector: No listener is left
,03-17 06:44:24.263  3720  3720 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:24.263  3720  3720 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:24.293  1018  1715 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:24.293  1018  1715 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:24.303  1018  1715 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:24.303  1018  1715 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:24.313  1018  1042 W libprocessgroup: failed to open /acct/uid_10046/pid_2434/cgroup.procs: No such file or directory
,03-17 06:44:24.313  1018  1042 W libprocessgroup: failed to open /acct/uid_10048/pid_3036/cgroup.procs: No such file or directory
,03-17 06:44:24.323  3116  3581 W jxcore-log: Platform android
03-17 06:44:24.323  3116  3581 W jxcore-log: 
,03-17 06:44:24.323  3116  3581 W jxcore-log: Process ARCH arm
03-17 06:44:24.323  3116  3581 W jxcore-log: 
,03-17 06:44:24.333  1018  3139 I ActivityManager: Killing 1589:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,03-17 06:44:24.343  1018  1128 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:24.343  1018  1128 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:24.343  1018  1128 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:24.343  1018  1128 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:24.353  3667  3667 I CalendarProvider2: CalendarProvider2.onCreate() called,
,03-17 06:44:24.353  3738  3738 E Zygote  : MountEmulatedStorage(),
03-17 06:44:24.353  3738  3738 E Zygote  : v2
03-17 06:44:24.353  3738  3738 I libpersona: KNOX_SDCARD checking this for 10145
03-17 06:44:24.353  3738  3738 I libpersona: KNOX_SDCARD not a persona,
03-17 06:44:24.353  3738  3738 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:24.363  3738  3738 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-17 06:44:24.363  3738  3738 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:24.363  1018  1128 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=3738 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,03-17 06:44:24.383  3738  3738 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:24.383  3738  3738 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:24.403  1018  1042 W libprocessgroup: failed to open /acct/uid_10072/pid_1589/cgroup.procs: No such file or directory
,03-17 06:44:24.413  3738  3738 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 06:44:24.413  3738  3738 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 06:44:24.413  3738  3738 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 06:44:24.413  3738  3738 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:24.413  3738  3738 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 06:44:24.423  3686  3686 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
,03-17 06:44:24.423  3686  3686 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,03-17 06:44:24.423  1018  1714 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-17 06:44:24.423  1018  1714 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:24.423  1018  1714 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:24.423  1018  1714 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 06:44:24.433  3686  3686 D NPS_WSSNPS: [] Service onCreate!!
,03-17 06:44:24.433  1018  1610 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:24.433  1018  1610 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:24.433  1018  1610 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:24.433  1018  1610 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:24.443  3754  3754 E Zygote  : MountEmulatedStorage()
,03-17 06:44:24.453  3754  3754 E Zygote  : v2
03-17 06:44:24.453  3754  3754 I libpersona: KNOX_SDCARD checking this for 1000
,03-17 06:44:24.453  3754  3754 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:24.453  3754  3754 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 06:44:24.453  3754  3754 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-17 06:44:24.453  3754  3754 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-17 06:44:24.453  1018  1610 I ActivityManager: Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3754 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:24.463  1018  1610 I ActivityManager: Killing 2939:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,03-17 06:44:24.483  3754  3754 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:24.483  3754  3754 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:24.533  1018  1327 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:24.543  3686  3769 D NPS_WSSNPS: [50.150321] NpsServiceTask Start
,03-17 06:44:24.543  3686  3686 D NPS_WSSNPS: [50.150321] smlDBHelper
,03-17 06:44:24.573  1018  1610 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:24.573  3720  3720 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
,03-17 06:44:24.573  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,03-17 06:44:24.583  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:24.583  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:24.583  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,03-17 06:44:24.583  3116  3581 I jxcore-log: JXcore Cordova bridge is ready!
03-17 06:44:24.583  3116  3581 I jxcore-log: 
,03-17 06:44:24.593  3116  3581 W jxcore-log: JXcore engine is started
,03-17 06:44:24.593  1018  1042 W libprocessgroup: failed to open /acct/uid_10085/pid_2939/cgroup.procs: No such file or directory
,03-17 06:44:24.593  1018  1325 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:24.593  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:24.593  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:24.593  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:24.593  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:24.603  3116  3377 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 06:44:24.603  3686  3686 I NPS_WSSNPS: [50.150321] AsyncBulkFlagCheck
,03-17 06:44:24.613  3116  3116 I chromium: [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,03-17 06:44:24.613  3782  3782 E Zygote  : MountEmulatedStorage()
,03-17 06:44:24.613  3782  3782 I libpersona: KNOX_SDCARD checking this for 10015
03-17 06:44:24.613  3782  3782 E Zygote  : v2
03-17 06:44:24.613  3782  3782 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:24.613  3782  3782 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:24.613  3782  3782 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-17 06:44:24.613  3782  3782 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 06:44:24.613  1018  1714 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3782 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,03-17 06:44:24.623  3720  3778 V OneTimeService: OneTimeService.onHandleIntent
,03-17 06:44:24.623  3239  3239 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-17 06:44:24.633  3116  3581 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-17 06:44:24.633  3116  3581 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-17 06:44:24.633  1018  1714 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:24.643  3116  3116 I chromium: [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,03-17 06:44:24.643  3116  3116 I chromium: [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,03-17 06:44:24.643  1018  1715 D FocusedStackFrame: Set to : 0
03-17 06:44:24.643  1018  1715 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 06:44:24.643  1018  1715 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 06:44:24.643  1018  1715 D InputDispatcher: Focused application set to: xxxx
03-17 06:44:24.653  1018  1715 D InputDispatcher: Focus left window: 3116
03-17 06:44:24.653  3686  3787 I NPS_WSSNPS: [50.150321] IsRemain_AsyncBulkCheck
03-17 06:44:24.653  3686  3787 I NPS_WSSNPS: [50.150321] IsRemain_Asyncing nothing
03-17 06:44:24.653  3686  3787 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
03-17 06:44:24.663  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 06:44:24.663  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 06:44:24.663   257   430 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (162 us)
,03-17 06:44:24.673  3782  3782 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:24.673  3782  3782 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:24.693  3116  3377 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 48ms. Plugin should use CordovaInterface.getThreadPool().
,03-17 06:44:24.693  1018  1496 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-17 06:44:24.703  1018  1327 D SettingsProvider: name = access_control_enabled
,03-17 06:44:24.703  1018  1496 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:24.703  1018  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:24.703  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 06:44:24.713  3686  3686 D NPS_WSSNPS: [50.150321] Service onDestroy
,03-17 06:44:24.713  3686  3686 I NPS_WSSNPS: [50.150321] smlBRConfigurationDelete
,03-17 06:44:24.713  1018  1031 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:24.713  1018  1325 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-17 06:44:24.713  1018  1325 W ActivityManager: mDVFSHelper.acquire()
,03-17 06:44:24.723  3686  3686 I NPS_WSSNPS: [50.150321] smlBRMessageDelete
03-17 06:44:24.723  3686  3686 I NPS_WSSNPS: [50.150321] smlBREmailDelete
,03-17 06:44:24.723  3686  3686 I NPS_WSSNPS: [50.150321] smlBRNetworkDelete
,03-17 06:44:24.723  3686  3686 I NPS_WSSNPS: [50.150321] smlBRCallLogDelete
03-17 06:44:24.723  3686  3686 I NPS_WSSNPS: [50.150321] smlBRMiniDiaryDelete
,03-17 06:44:24.723  3686  3686 I NPS_WSSNPS: [50.150321] smlBRPenMemoMDelete
03-17 06:44:24.723  3686  3686 I NPS_WSSNPS: [50.150321] smlBRSMemoDelete
,03-17 06:44:24.723  3686  3686 I NPS_WSSNPS: [50.150321] cpuBooster release : false
03-17 06:44:24.723  1018  1325 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-17 06:44:24.723  1018  1325 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 06:44:24.723  1018  1325 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-17 06:44:24.723  1018  1030 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:24.733  1195  1195 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-17 06:44:24.733  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 06:44:24.733  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:24.733  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:24.733  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:24.733  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:24.743  1018  1714 V VibratorService: hasVibrator - useVibetonz: true
,03-17 06:44:24.743  2004  3736 D FileApkUtils: Spent 46ms computing apk sha1.
,03-17 06:44:24.743  2004  3736 D FileApkUtils: Module already staged or being staged:chimera-modules/MapsModule.apk
03-17 06:44:24.743  2004  3736 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,03-17 06:44:24.753  1514  1514 D Launcher: onRestart, Launcher: 1010712943
,03-17 06:44:24.763  1018  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:24.763  1018  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:24.763  1018  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:24.763  1018  1510 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:24.783  3805  3805 E Zygote  : MountEmulatedStorage()
03-17 06:44:24.783  3805  3805 E Zygote  : v2
03-17 06:44:24.783  3805  3805 I libpersona: KNOX_SDCARD checking this for 10069
03-17 06:44:24.783  3805  3805 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:24.783  1018  1510 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3805 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 06:44:24.783  1018  1510 I ActivityManager: Killing 3015:com.sec.dsm.system/1000 (adj 15): empty #31
,03-17 06:44:24.783  3805  3805 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 06:44:24.783  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-17 06:44:24.793  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:24.793  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:24.793  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,03-17 06:44:24.793  1514  1514 D Launcher: onStart, Launcher: 1010712943
03-17 06:44:24.793  1514  1514 D Launcher.HomeView: onStart
03-17 06:44:24.793  1514  1514 D Launcher: onResume, Launcher: 1010712943
,03-17 06:44:24.793  1018  1327 D SettingsProvider: name = kids_home_mode
03-17 06:44:24.793  1018  1327 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 06:44:24.793  1018  1327 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 06:44:24.793  1018  1327 D SettingsProvider: selectionArgs: false
03-17 06:44:24.793  1018  1327 D SettingsProvider: selectionArgs: 10007
03-17 06:44:24.793  1018  1327 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 06:44:24.793  1018  1327 D SettingsProvider: ret = -1
03-17 06:44:24.793  2004  3736 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk appears to be unoptimized.
03-17 06:44:24.793  2004  3736 D DexOptUtils: Lollipop platform, using <isa> directory.
03-17 06:44:24.793  3805  3805 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:24.793  2004  3736 D DexOptUtils: Instantiating DexClassLoader to force creation of odex.
03-17 06:44:24.793  2004  3736 D DexOptUtils: Primary ABI of odexing process is armeabi-v7a
03-17 06:44:24.793  1514  1514 D Launcher.HomeView: onResume
03-17 06:44:24.793  3805  3805 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:24.793  1018  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:24.793  1018  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:24.793  1018  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:24.793  1018  1715 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:24.803  1514  1514 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 06:44:24.813  3817  3817 E Zygote  : MountEmulatedStorage()
03-17 06:44:24.813  3817  3817 I libpersona: KNOX_SDCARD checking this for 10072
03-17 06:44:24.813  3817  3817 E Zygote  : v2
03-17 06:44:24.813  3817  3817 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:24.813  3817  3817 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 06:44:24.813  1018  1715 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=3817 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,03-17 06:44:24.823  3817  3817 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:24.823  2709  2787 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-17 06:44:24.823  3817  3817 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 06:44:24.833  1514  1514 D MenuAppsGridFragment: onResume
03-17 06:44:24.833  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 06:44:24.833  1018  1610 D ActivityManager: handle home activity for 0
03-17 06:44:24.833  1018  1610 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-17 06:44:24.833  1018  1610 D KnoxTimeoutHandler: post home show event for user 0
03-17 06:44:24.833  1018  1610 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 06:44:24.833  1018  1610 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 06:44:24.833  1018  1610 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 06:44:24.833  1018  1018 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-17 06:44:24.833  1018  1018 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-17 06:44:24.833  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 06:44:24.833   257   257 I SurfaceFlinger: id=12 createSurf (720x1280),1 flag=4, Mauncher
,03-17 06:44:24.843  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 06:44:24.843  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-17 06:44:24.843  1018  1018 D SensorService: [SO] activate (ident=0xb7a46788, enabled=0)
03-17 06:44:24.843  3686  3686 D NPS_WSSNPS: [50.150321] dsServerSocket close
03-17 06:44:24.843  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-17 06:44:24.843  3817  3817 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:24.843  1018  1510 I ActivityManager: Killing 3066:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
03-17 06:44:24.853  3817  3817 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:24.853  1018  1510 I ActivityManager: Killing 3095:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
03-17 06:44:24.853  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 06:44:24.873  3805  3805 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:24.873  3805  3805 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:24.873  1018  1018 D SensorManager: unregisterListener ::   
03-17 06:44:24.873  1018  1018 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-17 06:44:24.873  1018  1018 D SensorService: [SO] changed settle time [0]
03-17 06:44:24.873  1018  1018 D SensorService: [SO] setDelay [200000000]
03-17 06:44:24.873  1018  1018 D SensorService: [SO] activate (ident=0xb7a46788, enabled=1)
03-17 06:44:24.873  1018  1018 D SensorService: [SO] AR_init
03-17 06:44:24.873  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-17 06:44:24.883  1018  1714 D InputDispatcher: Focus entered window: 1514
,03-17 06:44:24.883  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 06:44:24.883  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 06:44:24.883  1514  1514 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 06:44:24.883  1018  1018 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,03-17 06:44:24.903  1018  1587 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:24.903  1018  1587 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:24.903  1018  1587 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:24.903  1018  1587 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:24.913  1514  1514 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0,
,03-17 06:44:24.913  1018  1031 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 06:44:24.913  1018  3845 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 06:44:24.923  3846  3846 E Zygote  : MountEmulatedStorage(),
03-17 06:44:24.923  3846  3846 E Zygote  : v2
03-17 06:44:24.923  3846  3846 I libpersona: KNOX_SDCARD checking this for 10146,
,03-17 06:44:24.923  3846  3846 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 06:44:24.923  3846  3846 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:24.923  3846  3846 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:24.933  3846  3846 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:24.933  1195  1195 I StatusBar: Icon Only
03-17 06:44:24.933  1195  1195 D PanelView: There is/are notification(s) 
,03-17 06:44:24.933  1018  1587 I ActivityManager: Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=3846 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-17 06:44:24.933  3817  3817 D BadgeProvider: onCreate
03-17 06:44:24.943  1018  1587 I ActivityManager: Killing 2128:com.google.android.gms.wearable/u0a12 (adj 15): empty #31
03-17 06:44:24.943  3817  3817 D BadgeProvider: DatabaseHelper
,03-17 06:44:24.943  1782  1782 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-17 06:44:24.943  1018  1587 I ActivityManager: Killing 3157:com.sec.android.diagmonagent/1000 (adj 15): empty #32
,03-17 06:44:24.963  3116  3116 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection,
03-17 06:44:24.963  2004  2004 W InstanceID/Rpc: Found 10012
,03-17 06:44:24.983  1018  3139 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,03-17 06:44:24.983  1018  3139 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:24.983  1018  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:24.983  1018  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 06:44:25.003  3846  3846 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:25.003  3846  3846 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:25.053  3202  3293 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,03-17 06:44:25.083  1018  1040 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 06:44:25.083  3816  3816 I dex2oat : ----------------------------------------------------
03-17 06:44:25.083  3816  3816 I dex2oat : <SS>: S T A R T I N G . . .
03-17 06:44:25.083  3816  3816 I dex2oat : <SS>: Zip is absent. Canceled.
,03-17 06:44:25.083  3816  3816 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk --oat-fd=94 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-17 06:44:25.123  1332  3191 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 06:44:25.143  3802  3802 D AndroidRuntime: 
03-17 06:44:25.143  3802  3802 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-17 06:44:25.143  3802  3802 D AndroidRuntime: CheckJNI is OFF
,03-17 06:44:25.143  3802  3802 D AndroidRuntime: readGMSProperty: start
03-17 06:44:25.143  3802  3802 D AndroidRuntime: readGMSProperty: already setted!!
03-17 06:44:25.143  3802  3802 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 06:44:25.143  3802  3802 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 06:44:25.143  3802  3802 D AndroidRuntime: readGMSProperty: end
03-17 06:44:25.143  3802  3802 D AndroidRuntime: addProductProperty: start
,03-17 06:44:25.163  1018  3139 I art     : Explicit concurrent mark sweep GC freed 22863(1182KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 30MB/45MB, paused 2.921ms total 161.215ms
,03-17 06:44:25.163  1018  1587 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,03-17 06:44:25.163  1514  1514 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@29e612fd time:41395
,03-17 06:44:25.163  3817  3843 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
03-17 06:44:25.173  1018  1587 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:25.173  1018  1587 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
03-17 06:44:25.173  1018  1587 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 06:44:25.173  1018  1049 D PersonaManager: isKioskContainerExistOnDevice
,03-17 06:44:25.183  1018  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,03-17 06:44:25.183  1018  1496 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:25.183  1018  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:25.183  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 06:44:25.213  1018  3139 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,03-17 06:44:25.213  1018  1043 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 06:44:25.223  1018  1043 W ActivityManager: mDVFSHelper.release()
03-17 06:44:25.223  1018  1043 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 06:44:25.223  1018  3139 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:25.223  1018  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:25.223  1018  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 06:44:25.233  3846  3846 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 06:44:25.233  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3015/cgroup.procs: No such file or directory
03-17 06:44:25.233  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3066/cgroup.procs: No such file or directory
03-17 06:44:25.233  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3095/cgroup.procs: No such file or directory
03-17 06:44:25.233  1018  1042 W libprocessgroup: failed to open /acct/uid_10012/pid_2128/cgroup.procs: No such file or directory
03-17 06:44:25.233  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3157/cgroup.procs: No such file or directory
,03-17 06:44:25.243  1018  1049 I ActivityManager: Displayed Component not be shown by security: +516ms
,03-17 06:44:25.243  1018  1610 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,03-17 06:44:25.243  3805  3805 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,03-17 06:44:25.263  1018  1610 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:25.263  1018  1610 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:25.263  1018  1610 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-17 06:44:25.273  3817  3839 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-17 06:44:25.273  3817  3839 D BadgeProvider: sendNotify, [notify] : null
03-17 06:44:25.273  3817  3839 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-17 06:44:25.273  1514  1514 D Launcher.Model: reloadBadges entered.
,03-17 06:44:25.273  3817  3839 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 06:44:25.273  3817  3839 D BadgeProvider: update, [UpdateCount] : 1
,03-17 06:44:25.283  1018  1327 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
03-17 06:44:25.283  1018  1327 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-17 06:44:25.283  1018  1513 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0,
,03-17 06:44:25.283  1018  1040 D SensorService: [SO] currT = 41511132000, prevT = 41061121000, diff = 450011000, [0.172 0.421 10.247],
03-17 06:44:25.283  1018  1040 D SensorService: [SO] 0.172 0.421 10.247,
03-17 06:44:25.283  1018  1040 D SensorService: [SO] [100 -> 255]
,03-17 06:44:25.293  1018  1510 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-17 06:44:25.293  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
03-17 06:44:25.293  1018  1031 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-17 06:44:25.313  1018  1513 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,03-17 06:44:25.323  1018  1513 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:25.323  1018  1513 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:25.323  1018  1513 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 06:44:25.323  1018  1128 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-17 06:44:25.343  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-17 06:44:25.343  1018  1610 W ActivityManager: getTasks: caller 10145 does not hold GET_TASKS; limiting output
,03-17 06:44:25.353  1018  1587 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 06:44:25.353  1018  1587 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:25.353  1018  1587 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 06:44:25.353  1018  1587 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 06:44:25.353  3738  3829 I Process : Sending signal. PID: 3738 SIG: 9
,03-17 06:44:25.353  2458  2458 I Hs20UtilService: Starting #3
,03-17 06:44:25.353  2458  2475 I Hs20UtilService: Message received 5003
,03-17 06:44:25.363  1018  1513 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:25.363  1018  1513 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:25.363  1018  1513 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:25.363  1018  1513 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:25.373  3802  3802 E AffinityControl: AffinityControl: registerfunction enter
,03-17 06:44:25.383  3889  3889 E Zygote  : MountEmulatedStorage()
,03-17 06:44:25.383  3889  3889 I libpersona: KNOX_SDCARD checking this for 10019
03-17 06:44:25.383  3889  3889 E Zygote  : v2
03-17 06:44:25.383  3889  3889 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:25.383  3889  3889 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:25.383  1018  1513 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3889 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-17 06:44:25.383  3889  3889 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:25.383  3889  3889 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:25.433  3802  3802 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-17 06:44:25.443  1018  1128 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,03-17 06:44:25.453  1018  1128 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:25.453  1018  1128 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:25.453  1018  1128 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 06:44:25.453  1018  1327 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
,03-17 06:44:25.453  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:25.453  1018  1327 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:25.453  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
03-17 06:44:25.453  1018  3866 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-17 06:44:25.453  1018  3866 D PackageManager: START PACKAGE DELETE: observer{81090390}
03-17 06:44:25.453  1018  3866 D PackageManager: pkg{<packageName>}
03-17 06:44:25.453  1018  3866 D PackageManager: user{0}
03-17 06:44:25.453  1018  3866 D PackageManager: caller{2000}
03-17 06:44:25.453  1018  3866 D PackageManager: flags{2}
03-17 06:44:25.453  1018  3866 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-17 06:44:25.453  1018  3866 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-17 06:44:25.453  1018  3866 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-17 06:44:25.453  1018  3866 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,03-17 06:44:25.453  3889  3889 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:25.463  1018  1061 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-17 06:44:25.463  1018  1061 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-17 06:44:25.463  1018  1061 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-17 06:44:25.463  1018  1061 D ApplicationPolicy: getApplicationUninstallationEnabled
03-17 06:44:25.463  1018  1061 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-17 06:44:25.463  1018  1061 D PackageManager: !@killApplicatoin: 10174, uninstall pkg
,03-17 06:44:25.473  3889  3889 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:25.493  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,03-17 06:44:25.523  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:25.523  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:25.523  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:25.523  1018  1018 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 06:44:25.533  1687  1822 I art     : Explicit concurrent mark sweep GC freed 24704(1521KB) AllocSpace objects, 7(172KB) LOS objects, 39% free, 10MB/17MB, paused 1.410ms total 75.849ms
,03-17 06:44:25.633  1018  1061 W PackageSettings: Skipping PackageSetting{47f1089 com.example.hello/10175} due to missing metadata
,03-17 06:44:25.663  1018  3863 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:25.663  1018  1043 I ActivityManager: Force stopping com.test.thalitest appid=10174 user=-1: uninstall pkg
,03-17 06:44:25.663  1018  1043 I ActivityManager: Killing 3116:com.test.thalitest/u0a174 (adj 1): stop com.test.thalitest cause uninstall pkg
,03-17 06:44:25.673   257   430 I SurfaceFlinger: id=11 Removed NainActivit (7/8)
,03-17 06:44:25.673   257   435 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-17 06:44:25.693  1018  1510 I ActivityManager: Process com.android.email (pid 3738)(adj 9) has died(53,1082)
,03-17 06:44:25.693  1332  3191 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,03-17 06:44:25.703  1018  3139 D ActivityManager: retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-17 06:44:25.703  1018  3139 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:25.703  1018  3139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:25.703  1018  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,03-17 06:44:25.713  1018  1018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,03-17 06:44:25.713  1018  1018 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,03-17 06:44:25.713  2691  2691 D FactoryTestApp: [DummyFtClient$onDestroy](2691) Destroy DummyFtClient service
,03-17 06:44:25.713  1332  3191 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,03-17 06:44:25.723  3889  3889 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 06:44:25 GMT+01:00 2016
,03-17 06:44:25.723  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:25.723  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:25.723  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:25.723  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:25.733  3912  3912 E Zygote  : MountEmulatedStorage(),
03-17 06:44:25.733  3912  3912 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:25.733  3912  3912 E Zygote  : v2
03-17 06:44:25.733  3912  3912 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:25.733  3912  3912 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 06:44:25.743  1018  1325 I ActivityManager: Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=3912 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 06:44:25.743  1018  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{26c50ad7 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t235} time:41971
03-17 06:44:25.743  1018  1018 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 06:44:25.743  3912  3912 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:25.743  3912  3912 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:25.763  3912  3912 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:25.763   303   303 I art     : Explicit concurrent mark sweep GC freed 8724(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 636us total 24.334ms
03-17 06:44:25.763  3912  3912 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:25.763  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:25.763  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:25.763  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:25.763  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:25.783   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 588us total 18.372ms
,03-17 06:44:25.803   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 598us total 16.849ms
,03-17 06:44:25.813  3928  3928 E Zygote  : MountEmulatedStorage()
03-17 06:44:25.813  3928  3928 E Zygote  : v2
03-17 06:44:25.813  3928  3928 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:25.813  3928  3928 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:25.813  3928  3928 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:25.813  3928  3928 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-17 06:44:25.813  1018  1018 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3928 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:25.823  3928  3928 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:25.823  1018  3139 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-17 06:44:25.823  1332  3191 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
03-17 06:44:25.823  1018  1018 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
03-17 06:44:25.823  1195  1195 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 06:44:25.823  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 06:44:25.823  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:25.823  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:25.823  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:25.823  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:25.823  1018  3139 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:25.823  1018  3139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:25.823  1018  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 06:44:25.833  2691  2691 D FactoryTestApp: [Support$Values.getString](2691) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 06:44:25.833  2691  2691 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2691) mConnectionMode = gsm
03-17 06:44:25.833  2691  2691 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2691) RUNNING_FTCLIENT : false
03-17 06:44:25.833  2691  2691 D FactoryTestApp: [DummyFtClient$onDestroy](2691) kill process
03-17 06:44:25.833  2691  2691 I Process : Sending signal. PID: 2691 SIG: 9
,03-17 06:44:25.833  1018  1061 I ActivityManager: Force stopping com.test.thalitest appid=10174 user=0: pkg removed
,03-17 06:44:25.833  3889  3889 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-17 06:44:25.843  3889  3889 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-17 06:44:25.843  3928  3928 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:25.853  3928  3928 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:25.853  3889  3889 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 06:44:25.863  1018  1061 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,03-17 06:44:25.863  3889  3889 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 06:44:25.863  1018  1061 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,03-17 06:44:25.863  3889  3938 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-17 06:44:25.873  1018  1610 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:25.873  1018  1610 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:25.873  1018  1610 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:25.873  1018  1610 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:25.883  3889  3938 I KLMS-2.5.183: : KLMSIntentService(): BOOT_COMPLETED,
,03-17 06:44:25.883  3944  3944 E Zygote  : MountEmulatedStorage(),
03-17 06:44:25.883  3944  3944 E Zygote  : v2
03-17 06:44:25.883  3944  3944 I libpersona: KNOX_SDCARD checking this for 10145
03-17 06:44:25.883  3944  3944 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:25.883  3944  3944 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:25.893  3944  3944 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:25.893  3944  3944 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 06:44:25.903  1018  1610 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=3944 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,03-17 06:44:25.903  1018  1128 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,03-17 06:44:25.903  1018  1128 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:25.903  1018  1128 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:25.903  1018  1128 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:25.923  3944  3944 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:25.923  3944  3944 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:25.933  1018  1104 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-17 06:44:25.943  1018  1042 E libprocessgroup: failed to kill 1 processes for processgroup 3116
,03-17 06:44:25.953  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,03-17 06:44:25.953  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:25.953  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:25.953  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:25.963  1782  1782 E SamsungIME: mOCRHelper is null
,03-17 06:44:25.963  1814  2094 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-17 06:44:25.973  1490  1490 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 06:44:25.983  3889  3889 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-17 06:44:26.033  1018  3139 I ActivityManager: Process com.sec.factory (pid 2691)(adj 0) has died(97,1080)
,03-17 06:44:26.033  1018  1325 I ActivityManager: Killing 3214:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,03-17 06:44:26.033  1018  1325 I ActivityManager: Killing 2765:com.google.android.apps.books/u0a75 (adj 15): empty #32
,03-17 06:44:26.053  3202  3293 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,03-17 06:44:26.073  3944  3944 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 06:44:26.073  3944  3944 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 06:44:26.073  3944  3944 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 06:44:26.073  3944  3944 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:26.073  3944  3944 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 06:44:26.083  1018  1715 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-17 06:44:26.083  1018  1715 D SecContentProvider2: mCursor = null
,03-17 06:44:26.093  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:26.093  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:26.093  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:26.093  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:26.113  3963  3963 E Zygote  : MountEmulatedStorage()
03-17 06:44:26.113  3963  3963 E Zygote  : v2
03-17 06:44:26.113  3963  3963 I libpersona: KNOX_SDCARD checking this for 10022
03-17 06:44:26.113  3963  3963 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:26.113  1018  1130 V NetworkStats: removeUidsLocked() for UIDs [10174]
03-17 06:44:26.113  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 06:44:26.113  1018  1130 V NetworkStats: performPollLocked(flags=0x3)
03-17 06:44:26.113  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
03-17 06:44:26.113  1018  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-17 06:44:26.113  3963  3963 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:26.123  1018  1325 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3963 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
,03-17 06:44:26.123  3963  3963 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:26.123  3963  3963 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:26.123  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 06:44:26.123  1018  1130 V NetworkStats: performPollLocked() took 12ms
,03-17 06:44:26.143  1471  1471 D RegisteredComponentCache: Collect Tech packages for Knox
,03-17 06:44:26.173  3928  3928 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,03-17 06:44:26.173  3963  3963 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:26.173  3963  3963 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:26.193  1471  1471 D PersonaManager: isKioskContainerExistOnDevice
,03-17 06:44:26.193  1018  1018 D RCPManagerService: PackageReceiver onReceive()
,03-17 06:44:26.193  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-17 06:44:26.213  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-17 06:44:26.213  1018  1018 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,03-17 06:44:26.213  1018  1018 D OTPFW   : OtpDbHelper::getInstance New instance created
,03-17 06:44:26.213  1018  1018 D OTPFW   : DBIntegrity::getInstance - New instance created
,03-17 06:44:26.213  1018  1496 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,03-17 06:44:26.213  1018  1018 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10174 container id = 0
,03-17 06:44:26.223  1018  1018 I OTPFW   : ProvisionData::getAllEntries Enter
,03-17 06:44:26.223  1018  1018 E OTPFW   : ProvisionData::getAllEntries Table is empty
,03-17 06:44:26.223  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-17 06:44:26.223  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-17 06:44:26.223  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-17 06:44:26.223  1018  1018 V EnterpriseBillingPolicy: uID is 10174
03-17 06:44:26.223  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 06:44:26.223  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-17 06:44:26.223  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-17 06:44:26.223  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 06:44:26.223  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-17 06:44:26.223  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-17 06:44:26.223  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-17 06:44:26.233  1018  1496 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:26.233  1018  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 06:44:26.233  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-17 06:44:26.263  1018  1587 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.sharing.service.NearbySharingService; callingUser = 0; userId(target) = 0
,03-17 06:44:26.263  3667  3667 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-17 06:44:26.273  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-17 06:44:26.273  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-17 06:44:26.273  1018  1018 V EnterpriseBillingPolicy: uID is 10174
03-17 06:44:26.273  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 06:44:26.273  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-17 06:44:26.273  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-17 06:44:26.273  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 06:44:26.273  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-17 06:44:26.273  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-17 06:44:26.273  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-17 06:44:26.273  1018  2806 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
,03-17 06:44:26.283  3254  3349 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 06:44:26.293  1018  1131 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 06:44:26.293  1018  1131 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 06:44:26.313  1471  1471 D PersonaManager: isKioskContainerExistOnDevice
,03-17 06:44:26.313  1471  1471 D RegisteredServicesCache: empty dynamic service
,03-17 06:44:26.313  3782  3782 I RlzPingService: Setting next ping for 1458798266274
,03-17 06:44:26.323  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:26.333  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:26.333  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:26.333  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:26.343  3985  3985 E Zygote  : MountEmulatedStorage()
,03-17 06:44:26.343  3985  3985 E Zygote  : v2
03-17 06:44:26.343  3985  3985 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:26.343  3985  3985 I libpersona: KNOX_SDCARD not a persona,
,03-17 06:44:26.343  3985  3985 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:26.353  1018  1325 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=3985 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:26.353  3985  3985 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:26.353  1018  1325 I ActivityManager: Killing 3141:com.google.android.configupdater/u0a86 (adj 15): empty #31
,03-17 06:44:26.353  1018  3139 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
03-17 06:44:26.353  3985  3985 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:26.363  1018  3139 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:26.363  1018  3139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 06:44:26.363  1018  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-17 06:44:26.363  1018  1325 I ActivityManager: Killing 3254:com.policydm/1000 (adj 15): empty #31
,03-17 06:44:26.383  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:26.383  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:26.383  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:26.383  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:26.393  4000  4000 E Zygote  : MountEmulatedStorage(),
03-17 06:44:26.393  4000  4000 E Zygote  : v2
03-17 06:44:26.393  4000  4000 I libpersona: KNOX_SDCARD checking this for 1000
,03-17 06:44:26.393  4000  4000 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:26.393  1018  3863 D PowerManagerService: [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1195 (0x0)
,03-17 06:44:26.393  4000  4000 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:26.403  4000  4000 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:26.403  4000  4000 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:26.403  1018  1325 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=4000 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:26.403  3985  3985 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:26.403  3985  3985 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:26.423  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:26.423  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:26.423  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:26.423  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:26.433  4015  4015 E Zygote  : MountEmulatedStorage()
03-17 06:44:26.433  4015  4015 E Zygote  : v2
03-17 06:44:26.433  4015  4015 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:26.433  1018  3139 D RCPManagerService: exchangeData() failure , invalid userId
03-17 06:44:26.433  4015  4015 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:26.433  4015  4015 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-17 06:44:26.433  4000  4000 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:26.443  4000  4000 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:26.443  1018  1325 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4015 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 06:44:26.443  1018  1325 I ActivityManager: Killing 3272:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,03-17 06:44:26.443  4015  4015 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:26.443  4015  4015 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:26.453  1018  1325 I ActivityManager: Killing 3295:com.sec.factory.camera/1000 (adj 15): empty #31
,03-17 06:44:26.453  1018  1715 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:26.473  1018  3863 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:26.483  1018  3863 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:26.503  4000  4000 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,03-17 06:44:26.503  4015  4015 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:26.503  4015  4015 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:26.563  1018  1183 D TaskPersister: removeObsoleteFile: deleting file=236_task.xml
,03-17 06:44:26.563  1018  1183 D TaskPersister: removeObsoleteFile: deleting file=236_task_thumbnail.png
,03-17 06:44:26.563  3816  3885 W dex2oat : Verification of void com.google.maps.api.android.lib6.gmm6.e.f.a(java.nio.IntBuffer) took 172.962ms
,03-17 06:44:26.583  1018  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,03-17 06:44:26.603  1018  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
03-17 06:44:26.603  1018  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
03-17 06:44:26.603  1018  1042 W TextServicesManagerService: no available spell checker services found
,03-17 06:44:26.603  1018  1496 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:26.603  1018  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:26.603  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:26.653  1814  2164 I art     : Explicit concurrent mark sweep GC freed 12557(778KB) AllocSpace objects, 5(80KB) LOS objects, 40% free, 10MB/17MB, paused 985us total 69.962ms
,03-17 06:44:26.663  3985  3985 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-17 06:44:26.663  3985  3985 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-17 06:44:26.663  3985  3985 D SecurityLogAgent: StateMachine : Current State = 1
,03-17 06:44:26.663  3985  3985 D SecurityLogAgent: BootReceiver : completed task. Failed to return wakelock . 
,03-17 06:44:26.673  1018  1128 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
,03-17 06:44:26.673  4015  4015 E MTPRx   : In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,03-17 06:44:26.683  1018  1128 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:26.683  1018  1128 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:26.683  1018  1128 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:26.703  2004  4037 I CheckinService: Disabling old GoogleServicesFramework version
,03-17 06:44:26.723  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:44:26.723  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:44:26.723  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:44:26.733  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:44:26.743  1018  3139 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:26.743  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:26.743  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:26.743  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:26.743  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:26.753  2004  3906 D GCM     : COMPAT: Multi user not supported
,03-17 06:44:26.753  4042  4042 E Zygote  : MountEmulatedStorage(),
03-17 06:44:26.753  4042  4042 E Zygote  : v2
,03-17 06:44:26.753  4042  4042 I libpersona: KNOX_SDCARD checking this for 10152
03-17 06:44:26.753  4042  4042 I libpersona: KNOX_SDCARD not a persona,
03-17 06:44:26.753  1018  1031 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4042 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,03-17 06:44:26.763  4042  4042 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-17 06:44:26.763  1018  1031 I ActivityManager: Killing 3315:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,03-17 06:44:26.763  4042  4042 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:26.763  4042  4042 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:26.773  1018  1031 D TimaService: TIMA: in getTimaVersion
,03-17 06:44:26.773  1018  1587 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 06:44:26.773  1018  3863 D TimaService: TIMA3: KeyStore3_init
03-17 06:44:26.773  1018  3863 D TimaService: TIMA: in getTimaVersion
,03-17 06:44:26.773  1018  3863 E TLC_TZ_KEYSTORE: : Inside TZ_KEYSTORE_initialize()
03-17 06:44:26.773  1018  3863 I TLC_TZ_KEYSTORE: : creating new keystore context...
03-17 06:44:26.773  1018  3863 I TLC_TZ_KEYSTORE: : initializing ccm context...
03-17 06:44:26.773  1018  3863 I TLC_TZ_KEYSTORE: : root = /firmware/image, root_strlen = 15
03-17 06:44:26.773  1018  3863 I TLC_TZ_KEYSTORE: : process = tima_key, process_strlen = 8
,03-17 06:44:26.793  1018  3863 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15,
03-17 06:44:26.793  1018  3863 I TZ: qc_tlc_communication: process = tima_key, process_strlen = 8
03-17 06:44:26.793  1018  3863 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 1088 = 0x440
03-17 06:44:26.793  1018  3863 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 1088 = 0x440
03-17 06:44:26.793  1018  1031 D SecContentProvider2: uri = 14 selection = getSealedState
03-17 06:44:26.793  1018  1031 D SecContentProvider2: mCursor = null,
,03-17 06:44:26.793  1018  3863 I TZ: qc_tlc_communication: max_message_size = 2176 = 0x880
,03-17 06:44:26.803  1018  3863 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x880
,03-17 06:44:26.803  1018  3863 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 06:44:26.803  4042  4042 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:26.803  4042  4042 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:26.803  1018  3139 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-17 06:44:26.803  1018  3139 D SecContentProvider2: mCursor = null
,03-17 06:44:26.803  4015  4015 V MTPRx   : sealedState: false
03-17 06:44:26.803  4015  4015 V MTPRx   : sealedUsbMassStorageState: false
,03-17 06:44:26.813  3817  3843 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-17 06:44:26.823  1018  1128 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-17 06:44:26.823  1018  1128 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:26.823  1018  1128 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:26.823  1018  1128 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:26.823  1018  3863 D QSEECOMAPI: : Loaded image: APP id = 9
,03-17 06:44:26.823  1018  3863 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
03-17 06:44:26.823  1018  3863 I TLC_TZ_KEYSTORE: : ctx = 0xb79bd920, comm = 0xb7a89538, sendmsg = 0x994a8000, recvmsg = 0x994a8440
03-17 06:44:26.823  1018  3863 I TZ_init: : TZ_init: sending initialization request...
,03-17 06:44:26.833  1018  3863 E TZ_init: : TZ_init Process: Secure memory is not initialized!
,03-17 06:44:26.833  1018  3863 E TZ_init: : trustlet initialization failed
,03-17 06:44:26.833  1018  3863 I TZ_init: : TZ_init_START...
,03-17 06:44:26.833  1687  4057 D GCM     : GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,03-17 06:44:26.833  1018  3863 I TZ_init: : TZ_init_with_data: sending initialization request...
,03-17 06:44:26.843  1018  3863 I TZ_init: : TZ_init: successful initialization
,03-17 06:44:26.843  1018  3863 D QSEECOMAPI: : QSEECom_dealloc_memory 
,03-17 06:44:26.843  1018  3863 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 9
,03-17 06:44:26.853   288   288 E SMD     : DCD OFF
,03-17 06:44:26.853  1018  3863 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
,03-17 06:44:26.853  1018  1030 D SettingsProvider: name = mtp_usb_connection_status
,03-17 06:44:26.853  1018  3866 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,03-17 06:44:26.863  1018  3866 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:26.863  1018  3866 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:26.863  1018  3866 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:26.863  1018  1715 D SettingsProvider: name = media_player_mode
,03-17 06:44:26.883  1018  1714 I ActivityManager: Killing 3358:com.samsung.helphub/1000 (adj 15): empty #31
,03-17 06:44:26.893  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,03-17 06:44:26.893  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:26.893  1195  1195 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:26.893  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:26.893  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:26.943  1018  3866 W ActivityManager: getTasks: caller 10146 does not hold GET_TASKS; limiting output
,03-17 06:44:26.943  1018  1496 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 06:44:26.943  3817  3839 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,03-17 06:44:26.943  3817  3839 D BadgeProvider: sendNotify, [notify] : null
,03-17 06:44:26.943  3817  3839 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-17 06:44:26.943  3817  3839 D BadgeProvider: update, [BadgeCount] : badgecount=0
,03-17 06:44:26.943  3817  3839 D BadgeProvider: update, [UpdateCount] : 1
,03-17 06:44:26.983  1195  1195 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:26.993  1018  1715 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 06:44:26.993  1018  1715 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:26.993  1018  1715 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:26.993  1018  1715 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:26.993  3846  3918 I Process : Sending signal. PID: 3846 SIG: 9
,03-17 06:44:26.993  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,03-17 06:44:26.993  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:26.993  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:26.993  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:27.003  1018  3139 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-17 06:44:27.003  1018  3139 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:27.003  1018  1031 D SettingsProvider: name = mtp_running_status
,03-17 06:44:27.013  1018  3139 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:27.013  1018  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:27.013  2004  3906 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,03-17 06:44:27.013  1018  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,03-17 06:44:27.013  1018  1496 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:27.013  1018  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:27.013  1018  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:27.013  1195  1195 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:27.023  1018  3866 D SettingsProvider: name = media_mount_count
,03-17 06:44:27.033  1018  1128 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
03-17 06:44:27.033  1018  1128 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:27.033  1018  1128 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:27.033  1018  1128 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:27.033  2004  2004 D SystemUpdateService: onCreate
,03-17 06:44:27.043  1195  1195 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:27.053  1018  1587 D SettingsProvider: name = mtp_sync_alive
,03-17 06:44:27.053  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
03-17 06:44:27.053  3928  3979 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:27.053  3928  3979 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 06:44:27.053  3928  3979 I AMMetaDataParserService: getResourcePackageName:assistantlist
03-17 06:44:27.053  3928  3979 I AMMetaDataParserService: Resource data:2131165186
,03-17 06:44:27.053  1018  3139 D SettingsProvider: name = sdcard_launch
,03-17 06:44:27.053  3202  3293 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,03-17 06:44:27.053  3928  3979 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 06:44:27.053  3928  3979 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:27.063  3928  3979 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 06:44:27.063  3928  3979 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 06:44:27.063  3928  3979 I AMMetaDataParserService: getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
03-17 06:44:27.063  3928  3979 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 06:44:27.063  4042  4042 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,03-17 06:44:27.073  1018  1496 D SettingsProvider: name = boot_time_connected
,03-17 06:44:27.073  3928  3979 I AMMetaDataParserService: Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,03-17 06:44:27.083  1195  1195 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:27.093  1195  1195 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:27.093  1018  1325 I ActivityManager: Process com.android.exchange (pid 3846)(adj 13) has died(101,1085)
,03-17 06:44:27.103  1814  1814 I GCoreUlr: DispatchingService.onCreate()
,03-17 06:44:27.113  2004  2004 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-17 06:44:27.113  2004  4059 I CheckinService: Checking schedule, now: 1458193467115 next: 1458225725438
03-17 06:44:27.113  2004  4059 I CheckinService: active receiver: disabled
,03-17 06:44:27.113  1195  1195 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:27.123  4000  4000 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
,03-17 06:44:27.123  3928  3979 I AMMetaDataParserService: Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,03-17 06:44:27.133  1018  1327 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,03-17 06:44:27.133  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:27.133  1018  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:27.133  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,03-17 06:44:27.133  1018  3139 D SettingsProvider: name = mtp_open_session
,03-17 06:44:27.133  3928  3979 I AMMetaDataParserService: Icon data: ResourceNew Tab2131755458android.intent.action.doNewWindow2130837510
,03-17 06:44:27.143  1018  1587 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
03-17 06:44:27.143  3928  3979 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.,SelectBookmarkFolderActivity
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
,03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
03-17 06:44:27.143  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,03-17 06:44:27.163  1018  1587 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:27.163  1018  1587 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:27.163  1018  1587 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,03-17 06:44:27.173  1018  1513 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:27.173  1018  1513 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:27.173  1018  1513 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:27.173  1018  1513 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:27.173  1195  1195 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 06:44:27.183  2004  2004 I ConfigFetchService: onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,03-17 06:44:27.183  1018  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:27.183  1687  1687 I ConfigService: onCreate
,03-17 06:44:27.193  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:27.193  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:27.193  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:27.193  1018  1061 I art     : Explicit concurrent mark sweep GC freed 43630(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 30MB/46MB, paused 4.026ms total 1.167s
,03-17 06:44:27.203  2004  4077 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
,03-17 06:44:27.203  2004  4077 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED
,03-17 06:44:27.223  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.223  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.223  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.223  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:27.233  3816  3816 I dex2oat : dex2oat took 2.150s (threads: 4)
,03-17 06:44:27.233  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
03-17 06:44:27.233  3928  3979 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:27.233  3928  3979 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 06:44:27.233  3928  3979 I AMMetaDataParserService: Resource data:2131034113
,03-17 06:44:27.243  4079  4079 E Zygote  : MountEmulatedStorage()
03-17 06:44:27.243  4079  4079 E Zygote  : v2
03-17 06:44:27.243  4079  4079 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:27.243  4079  4079 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:27.243  3928  3979 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 06:44:27.243  3928  3979 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:27.243  3928  3979 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 06:44:27.243  4079  4079 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 06:44:27.243  3928  3979 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-17 06:44:27.243  3928  3979 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 06:44:27.243  4079  4079 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:27.243  4079  4079 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:27.243  1018  1714 I ActivityManager: Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4079 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 06:44:27.243  3928  3979 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:27.253  3928  3979 I GFX construct_block_size_descriptor_2d second part: took 2.866614ms for 0*0 texture 0
,03-17 06:44:27.253  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:27.253  3503  3503 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 06:44:27.253  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.253  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:27.253  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.253  3503  3503 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 06:44:27.253  3503  3503 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 06:44:27.253  3503  3503 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.BOOT_COMPLETED
03-17 06:44:27.253  3503  3503 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Version: 4.82
03-17 06:44:27.253  3503  3503 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Push type: [SPP, GCM]
,03-17 06:44:27.263  1514  1514 D Launcher.Model: reloadBadges entered.
,03-17 06:44:27.263  1514  1514 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true,
,03-17 06:44:27.263  2004  3736 D DexOptUtils: Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex
03-17 06:44:27.263  2004  3736 D DexOptUtils: Set odex to world readable.
03-17 06:44:27.263  2004  3736 D DexOptUtils: Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.odex
03-17 06:44:27.263  2004  3736 D FileApkUtils: Keeping up-to-date module: module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc
03-17 06:44:27.263  3928  3979 I GFX generate_partition_tables: took 7.592449ms for 0*0 texture 0
,03-17 06:44:27.273  3928  3979 I GFX raster: took 11.836095ms for 96*96 texture 0
03-17 06:44:27.273  3928  3979 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7632438 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7638f10 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:27.273  1514  1514 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-17 06:44:27.273  3928  3979 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-17 06:44:27.283  4095  4095 E Zygote  : MountEmulatedStorage()
03-17 06:44:27.283  4079  4079 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:27.283  4095  4095 E Zygote  : v2
03-17 06:44:27.283  4095  4095 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:27.283  4095  4095 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:27.283  4079  4079 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:27.283  4095  4095 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-17 06:44:27.293  1018  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75),
03-17 06:44:27.293  4095  4095 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 06:44:27.293  4095  4095 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:27.293  1018  1714 I ActivityManager: Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=4095 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:27.293  3503  3503 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account,
,03-17 06:44:27.323  1018  1061 D PackageManager: delete codoeFile: 
,03-17 06:44:27.323  3928  3979 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:27.323  1018  1030 W SEAMService:  hashset_to_int_array returning null
,03-17 06:44:27.323  3928  3979 I GFX raster: took 0.816146ms for 96*96 texture 0
03-17 06:44:27.323  3928  3979 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7632438 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7641078 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:27.333  4095  4095 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:27.333  1018  3139 W SEAMService:  hashset_to_int_array returning null
,03-17 06:44:27.333  4095  4095 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:27.333  3928  3979 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 06:44:27.333  4000  4000 E SQLiteLog: (284) automatic index on seams_container_info(seams_container_id)
,03-17 06:44:27.333  1018  1327 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 06:44:27.333  1018  1061 D AASAuninstall: userId = 0, info.removedAppID = 10174, info.uid = 10174, packageName = com.test.thalitest
03-17 06:44:27.333  4000  4000 E SQLiteLog: (284) automatic index on seams_container_info(sp_id)
,03-17 06:44:27.333  1018  1061 I AASA_removePackage: UID=10174 Target=com.test.thalitest
03-17 06:44:27.333  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:27.333  1018  1327 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:27.333  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:27.343  1018  1061 D PackageManager: result of delete: 1{81090390}
,03-17 06:44:27.343  1018  3866 W SEAMService:  hashset_to_int_array returning null
,03-17 06:44:27.353  1018  1128 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:27.353  3802  3802 D AndroidRuntime: Shutting down VM
03-17 06:44:27.353  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:44:27.353  2004  3736 D GmsModuleFndr: Beginning GMS chimera module scan
,03-17 06:44:27.363  3503  3503 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-17 06:44:27.363  1018  1128 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:27.363  1018  1128 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:27.363  1018  1128 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:27.363  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:44:27.373  3503  3503 I ReactiveServiceManager: Supported : 1
,03-17 06:44:27.373  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:44:27.373  1018  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 06:44:27.373  1018  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 06:44:27.373  1018  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:27.373  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:44:27.383  2004  3736 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
,03-17 06:44:27.383  2004  3736 D ChimeraCfgMgr: Beginning module configuration check
,03-17 06:44:27.393  2004  3736 D ChimeraCfgMgr: Module APKs unchanged, check complete
03-17 06:44:27.393  3928  3979 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:27.393  1018  1588 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
03-17 06:44:27.393  1018  1588 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 06:44:27.393  3928  3979 I GFX construct_block_size_descriptor_2d second part: took 2.570417ms for 0*0 texture 0
,03-17 06:44:27.393  4095  4095 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 06:44:27.403  3928  3979 I GFX generate_partition_tables: took 7.616095ms for 0*0 texture 0
,03-17 06:44:27.403  3928  3979 I GFX raster: took 11.138646ms for 96*96 texture 0
03-17 06:44:27.403  3928  3979 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb763d978 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb763da40 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:27.403  1018  1610 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:27.413  1018  1610 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:27.413  1018  1610 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:27.413  1018  1610 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:27.413  4095  4095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,03-17 06:44:27.413  3928  3979 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
03-17 06:44:27.413  1018  1327 D ActivityManager: retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,03-17 06:44:27.413  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:27.413  1018  1327 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:27.413  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,03-17 06:44:27.423  1018  1610 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 06:44:27.423  1018  1610 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:27.423  1018  1610 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:27.423  1018  1610 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:27.433  1018  1588 D QSEECOMAPI: : Loaded image: APP id = 10
,03-17 06:44:27.433  3928  3979 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:27.433  3928  3979 I GFX raster: took 0.604635ms for 96*96 texture 0
03-17 06:44:27.433  3928  3979 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7642438 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7642500 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:27.443  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:44:27.443  1018  1714 I ActivityManager: Killing 3380:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,03-17 06:44:27.443  1018  1588 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-17 06:44:27.443  1018  1588 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 10
,03-17 06:44:27.443  1018  1588 E terrier : handleString: Failed to handle string(-4)
03-17 06:44:27.443  1018  1588 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
03-17 06:44:27.443  3503  3503 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-17 06:44:27.443  3503  3503 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,03-17 06:44:27.443  4095  4095 I F_PHONE : [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,03-17 06:44:27.443  4095  4095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,03-17 06:44:27.443  3503  3503 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 06:44:27.443  3503  3503 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 06:44:27.443  3503  3503 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 06:44:27.443  3503  3503 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,03-17 06:44:27.443  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:44:27.443  3928  3979 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 06:44:27.453  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 06:44:27.453  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 06:44:27.453  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:44:27.453  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.453  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.453  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.453  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:27.453  3928  3979 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:27.453  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 06:44:27.453  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-17 06:44:27.453  3928  3979 I GFX raster: took 0.844011ms for 96*96 texture 0
03-17 06:44:27.453  3928  3979 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb763dba8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb763ded0 counterpartCT=4 counterpartW=96 counterparth=96
03-17 06:44:27.463  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 06:44:27.463  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 06:44:27.463  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
03-17 06:44:27.463  3928  3979 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532,
,03-17 06:44:27.473  4116  4116 E Zygote  : MountEmulatedStorage()
03-17 06:44:27.473  4116  4116 I libpersona: KNOX_SDCARD checking this for 1101
03-17 06:44:27.473  4116  4116 E Zygote  : v2
03-17 06:44:27.473  4116  4116 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:27.473  4116  4116 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:27.473  1018  1714 I ActivityManager: Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=4116 uid=1101 gids={41101, 9997} abi=armeabi-v7a
,03-17 06:44:27.473  4116  4116 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 06:44:27.473  1018  1714 I ActivityManager: Killing 3420:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,03-17 06:44:27.473  4116  4116 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:27.473  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.473  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.473  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.473  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:27.493  3928  3979 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:27.493  3928  3979 I GFX raster: took 0.626406ms for 96*96 texture 0
,03-17 06:44:27.493  3928  3979 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb763d0c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb763d188 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:27.493  3928  3979 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 06:44:27.493  4125  4125 E Zygote  : MountEmulatedStorage()
03-17 06:44:27.493  1018  1714 I ActivityManager: Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=4125 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 06:44:27.493  4125  4125 E Zygote  : v2
03-17 06:44:27.493  4125  4125 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:27.493  4125  4125 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:27.503  4125  4125 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:27.503  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
03-17 06:44:27.503  1018  1031 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-17 06:44:27.503  4125  4125 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 06:44:27.503  3928  3979 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:27.503  4125  4125 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:44:27.503  3928  3979 I GFX raster: took 0.692552ms for 96*96 texture 0
03-17 06:44:27.503  3928  3979 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb763ded0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb763e188 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:27.513  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.513  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.513  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.513  1018  1714 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:27.513  3928  3979 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 06:44:27.523  4116  4116 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:27.523   303   303 I art     : Explicit concurrent mark sweep GC freed 8786(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 659us total 23.563ms
03-17 06:44:27.523  2004  2004 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-17 06:44:27.523  4116  4116 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:27.533  4125  4125 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:27.533  4125  4125 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:27.533  3928  3979 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 06:44:27.533  3928  3979 I GFX raster: took 0.512344ms for 96*96 texture 0
03-17 06:44:27.533  3928  3979 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb763faa0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb763fd88 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:27.543  3928  3979 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 06:44:27.543   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 760us total 18.359ms
,03-17 06:44:27.543  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
03-17 06:44:27.543  3928  3979 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 06:44:27.543  3928  3979 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 06:44:27.543  3928  3979 I AMMetaDataParserService: Resource data:2131034113
,03-17 06:44:27.543  3928  3979 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-17 06:44:27.543  3928  3979 I AMMetaDataParserService: getResourceTypeNamexml
03-17 06:44:27.543  3928  3979 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 06:44:27.543  3928  3979 I GFX raster: took 0.793854ms for 96*96 texture 0
03-17 06:44:27.543  3928  3979 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7632438 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb763d220 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:27.553  3928  3979 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
03-17 06:44:27.553   303   303 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 605us total 17.134ms
,03-17 06:44:27.563  3928  3979 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:27.563  3928  3979 I GFX raster: took 0.967813ms for 96*96 texture 0
03-17 06:44:27.573  4146  4146 I libpersona: KNOX_SDCARD checking this for 10031
03-17 06:44:27.563  3928  3979 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7632438 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb763c598 counterpartCT=4 counterpartW=96 counterparth=96
03-17 06:44:27.573  4146  4146 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:27.573  4146  4146 E Zygote  : MountEmulatedStorage()
03-17 06:44:27.573  4146  4146 E Zygote  : v2
03-17 06:44:27.573  4146  4146 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 06:44:27.573  3802  3802 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-17 06:44:27.573  3928  3979 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 06:44:27.583  4146  4146 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-17 06:44:27.583  1018  1714 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=4146 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
03-17 06:44:27.583  4146  4146 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 06:44:27.583  1018  1714 I ActivityManager: Killing 3439:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,03-17 06:44:27.583  1018  1513 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,03-17 06:44:27.583  1018  1513 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:27.583  1018  1513 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:27.583  1018  1513 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
03-17 06:44:27.583  1018  1061 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-17 06:44:27.583  1018  1061 D PackageManager: userId{-1}
03-17 06:44:27.583  1018  1061 D PackageManager: andCode{true}
,03-17 06:44:27.593  1018  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
03-17 06:44:27.593  1018  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,03-17 06:44:27.593  2004  4077 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 06:44:27.593  1018  3866 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-17 06:44:27.603  1018  1042 W libprocessgroup: failed to open /acct/uid_10075/pid_2765/cgroup.procs: No such file or directory
03-17 06:44:27.603  1018  1042 W libprocessgroup: failed to open /acct/uid_10150/pid_3214/cgroup.procs: No such file or directory
,03-17 06:44:27.603  3928  3979 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:27.603  3928  3979 I GFX raster: took 0.643647ms for 96*96 texture 0
03-17 06:44:27.603  3928  3979 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb763d978 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb763bd20 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:27.613  1018  1325 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-17 06:44:27.613  1018  1061 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,03-17 06:44:27.613  2004  4069 I SystemUpdateService: cancelUpdate (empty URL)
03-17 06:44:27.613  2004  4069 I SystemUpdateService: active receiver: disabled
,03-17 06:44:27.613  4146  4146 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:27.623  4146  4146 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:27.623  3928  3979 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 06:44:27.623  1018  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.623  1018  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.623  1018  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.623  1018  1061 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:27.633  4125  4125 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 06:44:27.633  4116  4116 W ResourcesManager: Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.,
,03-17 06:44:27.643  4166  4166 E Zygote  : MountEmulatedStorage()
,03-17 06:44:27.643  4166  4166 E Zygote  : v2
03-17 06:44:27.643  4166  4166 I libpersona: KNOX_SDCARD checking this for 10004
,03-17 06:44:27.643  4166  4166 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:27.643  1018  1061 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=4166 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,03-17 06:44:27.643  4166  4166 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:27.653  4095  4095 D F_PHONE : [[com.sec.bcservice]] onServiceConnected()
03-17 06:44:27.653  4095  4095 I F_PHONE : default registerAction()
03-17 06:44:27.653  4095  4095 I F_PHONE : [[com.sec.bcservice]] sendPendingMessage()
,03-17 06:44:27.653  4166  4166 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:27.653  4166  4166 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:27.673  4166  4166 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:27.673  4166  4166 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:27.683  2004  2004 I Kids    : [GCoreUtils] Current gmscore version, 7899436 is smaller than the required version 8400000
,03-17 06:44:27.693  3928  3979 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:27.693  3928  3979 I GFX raster: took 0.608697ms for 96*96 texture 0
03-17 06:44:27.693  3928  3979 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7642438 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7642500 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:27.703  4116  4116 V SmartcardService: main Received broadcast
03-17 06:44:27.703  4116  4116 V SmartcardService: Starting smartcard service after boot completed
,03-17 06:44:27.703  1018  3139 D ActivityManager: retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
,03-17 06:44:27.703  1018  3139 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:27.703  1018  3139 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:27.703  1018  3139 W ActivityManager: NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
03-17 06:44:27.703  3928  3979 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 06:44:27.713  4146  4146 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 06:44:27.723  1018  1588 D ActivityManager: retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
,03-17 06:44:27.723  1018  1588 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:27.723  1018  1588 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:27.723  1018  1588 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-17 06:44:27.723  4125  4125 D BluetoothBDAdrressReceiver: onReceive(), action: android.intent.action.BOOT_COMPLETED
03-17 06:44:27.723  2004  4077 I GLSUser : [ChannelManager] Attempting to channel bind connection HttpClient.
,03-17 06:44:27.723  4125  4125 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,03-17 06:44:27.723  1018  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.723  1018  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:27.723  1018  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.723  1018  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:27.733  3928  3979 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,03-17 06:44:27.733  3928  3979 I GFX raster: took 0.840417ms for 96*96 texture 0
03-17 06:44:27.733  3928  3979 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb763dba8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7642500 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:27.733  3928  3979 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 06:44:27.743  4183  4183 E Zygote  : MountEmulatedStorage()
03-17 06:44:27.743  4183  4183 E Zygote  : v2
03-17 06:44:27.743  4183  4183 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:44:27.743  4183  4183 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:27.743  4183  4183 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:27.743  1018  3139 I ActivityManager: Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=4183 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 06:44:27.743  4183  4183 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:27.753  4183  4183 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:27.753  1018  3863 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
03-17 06:44:27.753  1018  3863 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:27.753  1018  3863 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 06:44:27.753  1018  3863 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
03-17 06:44:27.753  1018  3139 I ActivityManager: Killing 2511:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-17 06:44:27.763  1018  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.763  1018  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.763  1018  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.763  1018  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:27.773  4197  4197 E Zygote  : MountEmulatedStorage(),
03-17 06:44:27.783  4197  4197 E Zygote  : v2
03-17 06:44:27.783  4197  4197 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 06:44:27.783  1018  3139 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=4197 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 06:44:27.783  4197  4197 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-17 06:44:27.783  4197  4197 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:27.783  1018  3139 I ActivityManager: Killing 3458:com.fmm.dm/1000 (adj 15): empty #31
03-17 06:44:27.783  4197  4197 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:27.783  4197  4197 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:27.783  2004  2004 I ConfigFetchService: service connected
03-17 06:44:27.793  1018  1588 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
03-17 06:44:27.793  4183  4183 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:27.793  4183  4183 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:27.793  1018  1588 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:27.793  1018  1588 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:27.793  1018  1588 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:27.813  1018  3866 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.813  1018  3866 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.813  1018  3866 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.813  1018  3866 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:27.813  1814  4070 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,03-17 06:44:27.823  4197  4197 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:27.823  4197  4197 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:27.823  3928  3979 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:27.823  3928  3979 I GFX raster: took 0.834167ms for 96*96 texture 0
03-17 06:44:27.823  3928  3979 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb763d0c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7642500 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:27.833  1195  1195 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
03-17 06:44:27.833  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 06:44:27.833  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:27.833  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:27.833  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 06:44:27.833  1195  1195 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 06:44:27.833  3928  3979 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528,
03-17 06:44:27.833  4215  4215 E Zygote  : MountEmulatedStorage()
03-17 06:44:27.833  4215  4215 I libpersona: KNOX_SDCARD checking this for 10104
03-17 06:44:27.833  4215  4215 E Zygote  : v2
03-17 06:44:27.833  4215  4215 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:27.833  4215  4215 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 06:44:27.843  2004  4077 I GLSUser : [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,03-17 06:44:27.843  1018  3866 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4215 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-17 06:44:27.843  4215  4215 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:27.843  4215  4215 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 06:44:27.863  4183  4183 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
,03-17 06:44:27.863  1018  2806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,03-17 06:44:27.863  1018  1610 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.sysscope/com.sec.android.app.sysscope.service.SysScopeService; callingUser = 0; userId(target) = 0
,03-17 06:44:27.863  1018  1610 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:44:27.863  1018  1610 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:44:27.863  1018  1610 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
03-17 06:44:27.863  4197  4197 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 06:44:27.883  3503  3516 D PCWCLIENTTRACE_AccountAppFacade2_0: unregister AuthInfo UpdateReceiver v2.0
,03-17 06:44:27.883  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.883  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.883  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:27.883  1018  1325 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:27.893  4215  4215 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:44:27.893  4215  4215 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:27.903  3928  3979 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,03-17 06:44:27.903  3928  3979 I GFX raster: took 0.683437ms for 96*96 texture 0
03-17 06:44:27.903  3928  3979 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb763ded0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7642500 counterpartCT=4 counterpartW=96 counterparth=96
03-17 06:44:27.903  4236  4236 E Zygote  : MountEmulatedStorage(),
03-17 06:44:27.903  4236  4236 I libpersona: KNOX_SDCARD checking this for 10157
03-17 06:44:27.903  4236  4236 E Zygote  : v2
03-17 06:44:27.903  4236  4236 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:27.903  4236  4236 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:27.903  1018  1325 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4236 uid=10157 gids={50157, 9997} abi=armeabi-v7a
03-17 06:44:27.903  4236  4236 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:27.903  4236  4236 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:27.903  3928  3979 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 06:44:27.913  1018  1042 W libprocessgroup: failed to open /acct/uid_10094/pid_3272/cgroup.procs: No such file or directory
03-17 06:44:27.913  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3295/cgroup.procs: No such file or directory
,03-17 06:44:27.913  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3254/cgroup.procs: No such file or directory
03-17 06:44:27.913  1018  1042 W libprocessgroup: failed to open /acct/uid_10086/pid_3141/cgroup.procs: No such file or directory
03-17 06:44:27.913  1018  1042 W libprocessgroup: failed to open /acct/uid_10100/pid_3315/cgroup.procs: No such file or directory
03-17 06:44:27.913  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3358/cgroup.procs: No such file or directory
,03-17 06:44:27.913  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3380/cgroup.procs: No such file or directory
03-17 06:44:27.913  1018  1042 W libprocessgroup: failed to open /acct/uid_10003/pid_3420/cgroup.procs: No such file or directory
03-17 06:44:27.913  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3439/cgroup.procs: No such file or directory
,03-17 06:44:27.913  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_2511/cgroup.procs: No such file or directory
03-17 06:44:27.913  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3458/cgroup.procs: No such file or directory
,03-17 06:44:27.923  1490  1490 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 06:44:27.933  2004  2197 I art     : Explicit concurrent mark sweep GC freed 34782(2MB) AllocSpace objects, 40(640KB) LOS objects, 40% free, 11MB/19MB, paused 2.989ms total 132.016ms
,03-17 06:44:27.933  1490  1490 D BluetoothBDTestService: onCreate()
,03-17 06:44:27.933  1490  1490 E BluetoothBDTestService: onStart(), extra_type: BOOT_COMPLETED
,03-17 06:44:27.953  1490  1490 E BluetoothBDTestService: bd_address_path: /efs/bluetooth/bt_addr
,03-17 06:44:27.953  1490  1490 E BluetoothBDTestService: already exist!( /efs/bluetooth/bt_addr ), file length: 17
,03-17 06:44:27.963  1018  1513 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:27.963  1018  3866 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 06:44:27.973  1018  1513 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:27.973  1018  1513 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 06:44:27.973  1018  1513 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:27.973  4215  4215 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 06:44:27.973  4236  4236 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:27.973  4236  4236 D ActivityThread: Added TimaKeyStore provider
03-17 06:44:27.973  4197  4197 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,03-17 06:44:27.983  4197  4252 I KnoxUsageLogPro: savePreference: key = previous_sys_time value = 1458193467986
,03-17 06:44:27.993  1018  2806 D SSRM:n  : SIOP:: AP = 400
,03-17 06:44:27.993  1018  3863 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:27.993  1018  3863 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:27.993  1018  3863 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:27.993  1018  3863 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:28.013  4197  4197 I KnoxUsageLogPro: premStatus:2
,03-17 06:44:28.013  3928  3979 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:28.013  3928  3979 I GFX raster: took 0.537292ms for 96*96 texture 0
03-17 06:44:28.013  3928  3979 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb763faa0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7642500 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:28.013  2004  2004 D SystemUpdateService: onDestroy
03-17 06:44:28.013  3928  3979 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
03-17 06:44:28.023  4236  4236 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactShortcut
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activityalias.DialShortcut
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activityalias.MessageShortcut
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:Inside bundl,e  check
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 06:44:28.023  3928  3979 I AMMetaDataParserService: Resource data:2131034112
03-17 06:44:28.023  2004  4077 I AuthZen : Fetching signing key...
03-17 06:44:28.023  4197  4197 I KnoxUsageLogPro: isEulaShown : false
03-17 06:44:28.023  4197  4197 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,03-17 06:44:28.033  2004  2004 D ConfigFetchService: ConfigApi connection successful.
,03-17 06:44:28.033  1018  1030 I ActivityManager: Killing 3526:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,03-17 06:44:28.033  4197  4252 I KnoxUsageLogPro: savePreference: key = previous_elapsed_time value = 44211
,03-17 06:44:28.033  1018  1325 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:28.033  1018  2859 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 06:44:28.043  1018  1325 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:28.043  3928  3979 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_detail
03-17 06:44:28.043  3928  3979 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 06:44:28.043  3928  3979 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:28.043  1018  1325 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:28.043  3928  3979 I GFX raster: took 0.603750ms for 96*96 texture 0
03-17 06:44:28.043  3928  3979 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7642438 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7642500 counterpartCT=4 counterpartW=96 counterparth=96
03-17 06:44:28.043  1018  1325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-17 06:44:28.043  4146  4146 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
,03-17 06:44:28.053  3928  3979 I AMMetaDataParserService: Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,03-17 06:44:28.063  3202  3293 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,03-17 06:44:28.073  1018  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:28.073  1018  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:28.073  1018  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:28.073  1018  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:28.083  4259  4259 E Zygote  : MountEmulatedStorage()
03-17 06:44:28.083  1018  3139 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=4259 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 06:44:28.083  4259  4259 E Zygote  : v2
03-17 06:44:28.083  4259  4259 I libpersona: KNOX_SDCARD checking this for 10159
03-17 06:44:28.083  4259  4259 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 06:44:28.083  4259  4259 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:28.093  1018  3139 I ActivityManager: Killing 3536:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
,03-17 06:44:28.093  4259  4259 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:28.093  4259  4259 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,03-17 06:44:28.103  4146  4146 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
,03-17 06:44:28.113  4259  4259 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:28.113  4259  4259 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:28.163  4146  4146 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,03-17 06:44:28.173  4146  4146 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,03-17 06:44:28.173  4259  4259 I Intent to TravelDirActivity: inside TravelBroadcastReceiver
,03-17 06:44:28.173  4146  4146 D DialogFlow: initQueue()
,03-17 06:44:28.203  1018  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:28.203  1018  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:28.203  1018  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:28.203  1018  3139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:28.203  1018  1042 W libprocessgroup: failed to open /acct/uid_10060/pid_3526/cgroup.procs: No such file or directory
03-17 06:44:28.203  1018  1042 W libprocessgroup: failed to open /acct/uid_10125/pid_3536/cgroup.procs: No such file or directory
,03-17 06:44:28.213  4277  4277 E Zygote  : MountEmulatedStorage()
,03-17 06:44:28.213  4277  4277 E Zygote  : v2
03-17 06:44:28.213  4277  4277 I libpersona: KNOX_SDCARD checking this for 10032
03-17 06:44:28.213  4277  4277 I libpersona: KNOX_SDCARD not a persona
,03-17 06:44:28.213  4277  4277 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-17 06:44:28.213  1018  3139 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4277 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
03-17 06:44:28.213  1018  3139 I ActivityManager: Killing 3566:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
03-17 06:44:28.223  4277  4277 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-17 06:44:28.223  4277  4277 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:44:28.223  1018  1496 I ActivityManager: Killing 3583:com.fmm.ds/1000 (adj 15): empty #31
,03-17 06:44:28.243  4277  4277 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:28.253  4277  4277 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:28.253  2004  4077 I AuthZen : Signing key fetched successfully!
,03-17 06:44:28.263  2004  4077 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 06:44:28.333  2004  4077 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/databases/keys.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,03-17 06:44:28.343  2004  4256 E SQLiteLog: (10) unixWrite() File Descriptor : 94 gets errno : 30
,03-17 06:44:28.343  3928  3979 E SQLiteLog: (10) unixWrite() File Descriptor : 37 gets errno : 30
,03-17 06:44:28.343  2004  4077 I AuthZen : Starting Enrollment...
,03-17 06:44:28.343  3928  3979 E SQLiteDatabase: Error inserting actname=com.android.contacts.activities.ContactDetailActivity amicon=[B@171f4a5e appname=com.android.contacts id=1458193468056 amtitle=Add to Favourites amstate=1 amintent=android.intent.assistant.detail.favorite amlabel=2131690170
03-17 06:44:28.343  3928  3979 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
03-17 06:44:28.343  3928  3979 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-17 06:44:28.343  3928  3979 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-17 06:44:28.343  3928  3979 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-17 06:44:28.343  3928  3979 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-17 06:44:28.343  3928  3979 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-17 06:44:28.343  3928  3979 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-17 06:44:28.343  3928  3979 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:77)
03-17 06:44:28.343  3928  3979 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
03-17 06:44:28.343  3928  3979 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
03-17 06:44:28.343  3928  3979 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 06:44:28.343  3928  3979 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:44:28.343  3928  3979 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 06:44:28.343  3928  3979 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 06:44:28.343  3928  3979 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 06:44:28.343  2004  4256 E AndroidRuntime: FATAL EXCEPTION: IntentService[CredentialSyncReceiverService]
03-17 06:44:28.343  2004  4256 E AndroidRuntime: Process: com.google.android.gms, PID: 2004
03-17 06:44:28.343  2004  4256 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
03-17 06:44:28.343  2004  4256 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-17 06:44:28.343  2004  4256 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
03-17 06:44:28.343  2004  4256 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
03-17 06:44:28.343  2004  4256 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
03-17 06:44:28.343  2004  4256 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:527)
03-17 06:44:28.343  2004  4256 E AndroidRuntime: 	at com.google.android.gms.auth.api.credentials.be.persistence.e.a(SourceFile:74)
03-17 06:44:28.343  2004  4256 E AndroidRuntime: 	at com.google.android.gms.auth.api.credentials.be.persistence.ae.a(SourceFile:182)
03-17 06:44:28.343  2004  4256 E AndroidRuntime: 	at com.google.android.gms.auth.api.credentials.sync.b.a(SourceFile:114)
03-17 06:44:28.343  2004  4256 E AndroidRuntime: 	at com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService.a(SourceFile:184)
03-17 06:44:28.343  2004  4256 E AndroidRuntime: 	at com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService.onHandleIntent(SourceFile:97)
03-17 06:44:28.343  2004  4256 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 06:44:28.343  2004  4256 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:44:28.343  2004  4256 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-17 06:44:28.343  2004  4256 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 06:44:28.343  3928  3979 I GFX raster: took 0.652551ms for 96*96 texture 0
03-17 06:44:28.343  3928  3979 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7642438 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7642500 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 06:44:28.343  1018  1714 W SyncManager: Error writing status
03-17 06:44:28.343  1018  1714 W SyncManager: java.io.IOException: write failed: EROFS (Read-only file system)
03-17 06:44:28.343  1018  1714 W SyncManager: 	at libcore.io.IoBridge.write(IoBridge.java:502)
03-17 06:44:28.343  1018  1714 W SyncManager: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
03-17 06:44:28.343  1018  1714 W SyncManager: 	at java.io.OutputStream.write(OutputStream.java:82)
03-17 06:44:28.343  1018  1714 W SyncManager: 	at com.android.server.content.SyncStorageEngine.writeStatusLocked(SyncStorageEngine.java:2417)
03-17 06:44:28.343  1018  1714 W SyncManager: 	at com.android.server.content.SyncStorageEngine.updateOrAddPeriodicSync(SyncStorageEngine.java:959)
03-17 06:44:28.343  1018  1714 W SyncManager: 	at com.android.server.content.ContentService.addPeriodicSync(ContentService.java:641)
03-17 06:44:28.343  1018  1714 W SyncManager: 	at android.content.IContentService$Stub.onTransact(IContentService.java:333)
03-17 06:44:28.343  1018  1714 W SyncManager: 	at com.android.server.content.ContentService.onTransact(ContentService.java:149)
03-17 06:44:28.343  1018  1714 W SyncManager: 	at android.os.Binder.execTransact(Binder.java:461)
03-17 06:44:28.343  1018  1714 W SyncManager: Caused by: android.system.ErrnoException: write failed: EROFS (Read-only file system)
03-17 06:44:28.343  1018  1714 W SyncManager: 	at libcore.io.Posix.writeBytes(Native Method)
03-17 06:44:28.343  1018  1714 W SyncManager: 	at libcore.io.Posix.write(Posix.java:223)
03-17 06:44:28.343  1018  1714 W SyncManager: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
03-17 06:44:28.343  1018  1714 W SyncManager: 	at libcore.io.IoBridge.write(IoBridge.java:497)
03-17 06:44:28.343  1018  1714 W SyncManager: 	... 8 more
,03-17 06:44:28.343  1018  3863 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,03-17 06:44:28.353  1018  4293 E DropBoxManagerService: Can't write: system_app_crash
03-17 06:44:28.353  1018  4293 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop170.tmp: open failed: EROFS (Read-only file system)
03-17 06:44:28.353  1018  4293 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-17 06:44:28.353  1018  4293 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-17 06:44:28.353  1018  4293 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-17 06:44:28.353  1018  4293 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-17 06:44:28.353  1018  4293 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-17 06:44:28.353  1018  4293 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
03-17 06:44:28.353  1018  4293 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-17 06:44:28.353  1018  4293 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-17 06:44:28.353  1018  4293 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-17 06:44:28.353  1018  4293 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-17 06:44:28.353  1018  4293 E DropBoxManagerService: 	... 5 more
,03-17 06:44:28.363  3928  3979 I AMMetaDataParserService: Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,03-17 06:44:28.363  3928  3979 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
,03-17 06:44:28.363  3928  3979 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
03-17 06:44:28.363  3928  3979 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 06:44:28.363  3928  3979 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 06:44:28.363  3928  3979 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 06:44:28.363  3928  3979 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 06:44:28.363  3928  3979 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 06:44:28.363  3928  3979 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 06:44:28.363  3928  3979 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 06:44:28.363  3928  3979 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 06:44:28.363  3928  3979 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 06:44:28.363  3928  3979 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 06:44:28.363  3928  3979 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 06:44:28.363  3928  3979 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 06:44:28.363  3928  3979 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 06:44:28.363  3928  3979 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 06:44:28.363  3928  3979 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
03-17 06:44:28.363  3928  3979 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
03-17 06:44:28.363  3928  3979 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
03-17 06:44:28.363  3928  3979 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 06:44:28.363  3928  3979 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:44:28.363  3928  3979 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 06:44:28.363  3928  3979 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 06:44:28.363  3928  3979 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 06:44:28.363  3928  3979 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 06:44:28.363  3928  3979 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 06:44:28.363  3928  3979 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 06:44:28.363  3928  3979 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 06:44:28.363  3928  3979 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 06:44:28.363  3928  3979 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 06:44:28.363  3928  3979 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 06:44:28.363  3928  3979 W System.err: 	at andro,id.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 06:44:28.363  3928  3979 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 06:44:28.363  3928  3979 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 06:44:28.363  3928  3979 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 06:44:28.363  3928  3979 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 06:44:28.363  3928  3979 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 06:44:28.363  3928  3979 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
03-17 06:44:28.363  3928  3979 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
03-17 06:44:28.363  3928  3979 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
03-17 06:44:28.363  3928  3979 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 06:44:28.363  3928  3979 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:44:28.363  3928  3979 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-17 06:44:28.363  3928  3979 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 06:44:28.363  1018  1043 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 06:44:28.363  1018  1043 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 06:44:28.373  1018  1043 D PhoneWindow: *FMB* installDecor mIsFloating : true
03-17 06:44:28.373  1018  1043 D PhoneWindow: *FMB* installDecor flags : 8519682
,03-17 06:44:28.393  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 06:44:28.393  1018  1043 D InputDispatcher: Focus left window: 1514
03-17 06:44:28.393  1018  1043 D InputDispatcher: Focus entered window: 1018
03-17 06:44:28.393  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 06:44:28.393  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 06:44:28.403  1018  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:28.403  4277  4277 E SharedPreferencesImpl: Couldn't rename file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/pref_tagservice_state.xml to backup file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/pref_tagservice_state.xml.bak
,03-17 06:44:28.403  1018  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:28.403  1018  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:44:28.403  1018  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:44:28.413  1018  1588 I ActivityManager: Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4296 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 06:44:28.413  1018  1588 I ActivityManager: Killing 3602:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,03-17 06:44:28.423  4296  4296 E Zygote  : MountEmulatedStorage(),
,03-17 06:44:28.423  1018  1588 I ActivityManager: Killing 3638:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
03-17 06:44:28.423  4296  4296 E Zygote  : v2
03-17 06:44:28.423  4296  4296 I libpersona: KNOX_SDCARD checking this for 10033
,03-17 06:44:28.423  2004  3906 E SQLiteLog: (10) unixWrite() File Descriptor : 102 gets errno : 30
03-17 06:44:28.423  4296  4296 I libpersona: KNOX_SDCARD not a persona
03-17 06:44:28.423  4296  4296 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-17 06:44:28.423  1814  4070 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/gcore_ulr_UlrLocation.db" with flag (131138) and mode_t (0) due to error (30)
,03-17 06:44:28.423  4296  4296 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-17 06:44:28.423  4296  4296 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
03-17 06:44:28.423  1018  1043 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 06:44:28.423  1018  1043 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-17 06:44:28.433  1814  4070 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/gcore_ulr_UlrLocation.db'.
03-17 06:44:28.433  1814  4070 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 06:44:28.433  1814  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 06:44:28.433  1814  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-17 06:44:28.433  1814  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-17 06:44:28.433  1814  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-17 06:44:28.433  1814  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-17 06:44:28.433  1814  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-17 06:44:28.433  1814  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-17 06:44:28.433  1814  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-17 06:44:28.433  1814  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-17 06:44:28.433  1814  4070 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-17 06:44:28.433  1814  4070 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-17 06:44:28.433  1814  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 06:44:28.433  1814  4070 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 06:44:28.433  1814  4070 E SQLiteDatabase: 	at com.google.android.location.reporting.e.a(SourceFile:514)
03-17 06:44:28.433  1814  4070 E SQLiteDatabase: 	at com.google.android.location.reporting.d.v.a(SourceFile:137)
03-17 06:44:28.433  1814  4070 E SQLiteDatabase: 	at com.google.android.location.reporting.s.a(SourceFile:205)
03-17 06:44:28.433  1814  4070 E SQLiteDatabase: 	at com.google.android.location.reporting.service.d.a(SourceFile:619)
03-17 06:44:28.433  1814  4070 E SQLiteDatabase: 	at com.google.android.location.reporting.service.c.handleMessage(SourceFile:479)
03-17 06:44:28.433  1814  4070 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:44:28.433  1814  4070 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 06:44:28.433  1814  4070 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 06:44:28.433  2004  4077 D AuthZen : getting auth token. Attempt 0
,03-17 06:44:28.433  1018  1327 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-17 06:44:28.433  1018  1327 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:28.433  1018  1327 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:28.433  1018  1327 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 06:44:28.453  1018  1042 W libprocessgroup: failed to open /acct/uid_10131/pid_3566/cgroup.procs: No such file or directory
,03-17 06:44:28.453   257   257 I SurfaceFlinger: id=13 createSurf (97x97),1 flag=4, hms
,03-17 06:44:28.453  1018  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3583/cgroup.procs: No such file or directory
,03-17 06:44:28.463  4296  4296 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:44:28.463  4296  4296 D ActivityThread: Added TimaKeyStore provider
,03-17 06:44:28.483  1018  1043 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 06:44:28.483  1018  1325 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 06:44:28.483  1018  1182 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 06:44:28.483  1018  1182 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 06:44:28.483  1018  1182 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 06:44:28.483  1018  1182 I Adreno-EGL: Local Branch: 
03-17 06:44:28.483  1018  1182 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 06:44:28.483  1018  1182 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 06:44:28.483  1018  1182 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 06:44:28.483  1018  1325 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:44:28.483  1018  1325 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 06:44:28.483  1018  1325 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
03-17 06:44:28.483  1018  1182 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 06:44:28.503  1687  4258 E SQLiteLog: (10) unixWrite() File Descriptor : 44 gets errno : 30
,03-17 06:44:28.503  1687  4258 E PlayLogIntentService: --> failed to write: java.io.IOException: Could not end transaction after writing to SQLite
,03-17 06:44:28.523  1018  1182 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,03-17 06:44:28.523  1018  1182 D OpenGLRenderer: Enabling debug mode 0

```
