#### Test 62509094141ff10_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
03-17 11:16:36.723  1746  1865 I art     : Explicit concurrent mark sweep GC freed 7409(368KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 793us total 36.698ms
--------- beginning of system
03-17 11:16:36.723  2971  2971 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 11:16:36.733  2896  2896 E ActivityThread: Failed to find provider info for flipboard.auth.internal.debug
03-17 11:16:36.743  1019  1359 D SettingsProvider: name = next_alarm_formatted
03-17 11:16:36.743  1019  1359 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 11:16:36.743  1019  1359 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 11:16:36.743  1019  1359 D SettingsProvider: selectionArgs: false
03-17 11:16:36.743  1019  1359 D SettingsProvider: selectionArgs: 10081
03-17 11:16:36.743  1019  1359 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 11:16:36.743  1019  1359 D SettingsProvider: ret = -1
03-17 11:16:36.743  1019  1044 W libprocessgroup: failed to open /acct/uid_10026/pid_1815/cgroup.procs: No such file or directory
03-17 11:16:36.743  1019  1044 W libprocessgroup: failed to open /acct/uid_10134/pid_1927/cgroup.procs: No such file or directory
03-17 11:16:36.743  2896  2896 E ActivityThread: Failed to find provider info for flipboard.auth.internal
03-17 11:16:36.753  1019  1019 I DrmEventReceiver: DrmEventReceiver : onReceive
03-17 11:16:36.753  1019  1019 I DrmEventReceiver: DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
03-17 11:16:36.753  1019  1019 I DrmEventReceiver: DrmEventReceiver : beginStartingService
03-17 11:16:36.753  1019  1019 I System.out: start Service
03-17 11:16:36.753  1019  1019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
03-17 11:16:36.753  1019  1359 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10081
03-17 11:16:36.753  1019  1032 I ActivityManager: Killing 2222:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #31
03-17 11:16:36.763  1177  1177 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 11:16:36.763  1019  1386 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:36.763  1019  1386 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:36.763  1019  1386 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:36.763  1019  1386 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:36.783  2996  2996 E Zygote  : MountEmulatedStorage()
03-17 11:16:36.783  2996  2996 E Zygote  : v2
03-17 11:16:36.783  2996  2996 I libpersona: KNOX_SDCARD checking this for 1000
03-17 11:16:36.783  2996  2996 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:36.793  2996  2996 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 11:16:36.793  2996  2996 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 11:16:36.793  2996  2996 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 11:16:36.793  1019  1386 I ActivityManager: Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=2996 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 11:16:36.793  1019  1386 I ActivityManager: Killing 2237:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
03-17 11:16:36.803  2164  2948 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.a,ndroid.gms/files
03-17 11:16:36.803   258   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
03-17 11:16:36.803   258   518 W Vold    : Returning OperationFailed - no handler for errno 0
03-17 11:16:36.813  2996  2996 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 11:16:36.813  2996  2996 D ActivityThread: Added TimaKeyStore provider
03-17 11:16:36.823  1229  2990 D MediaScannerService: !@start scanning volume internal: [/system/media, /oem/media]
03-17 11:16:36.833  1019  1359 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:36.833  1019  1359 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 11:16:36.833  1019  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
03-17 11:16:36.843  1229  1229 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
03-17 11:16:36.843   284   508 D WVMDrmPlugIn: WVMDrmPlugin::onInitialize : 3065
03-17 11:16:36.843   284   508 D WVMDrmPlugIn: WVMDrmPlugin::onSetOnInfoListener : add 3065
03-17 11:16:36.843  1019  1044 W libprocessgroup: failed to open /acct/uid_10064/pid_2222/cgroup.procs: No such file or directory
03-17 11:16:36.843  1019  1044 W libprocessgroup: failed to open /acct/uid_10065/pid_2237/cgroup.procs: No such file or directory
03-17 11:16:36.853  1482  1920 D TP/MmsProvider: Update uri=content://mms, match=0
03-17 11:16:36.853  1482  1920 D TP/MmsProvider: update , handleReadChangedBroadcast
03-17 11:16:36.863  1482  1920 D TP/MmsSmsProvider: need read changed broadcast:false
03-17 11:16:36.863  2478  2478 I Mms:transaction: [MmsSystemEventReceiver] restorePduNotificationStatus count=0
03-17 11:16:36.863  2478  2478 D Mms/MessagingNotification: [start]    nonBlockingUpdateMessageIndicator() consume time = 4002.51578
03-17 11:16:36.863  2478  2478 I Mms/ReservationManager: resetAfterConnected()
03-17 11:16:36.863  1482  2067 D TP/MmsSmsProvider: query,matched:7, calling pid = 2478
03-17 11:16:36.873  2478  3015 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-17 11:16:36.873  2478  3015 D Mms/TelephonyPermission: isDefault true
03-17 11:16:36.873  1482  2067 D TP/MmsSmsProvider: match 7:Elapsed time : 4.780 ms
03-17 11:16:36.873  1019  3016 I DrmEventService: action event :android.intent.action.BOOT_COMPLETED
03-17 11:16:36.883  1019  1019 I TimaServiceEventReceiver: TimaServiceEventReceiver : onReceive
03-17 11:16:36.893  1482  1509 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2478
03-17 11:16:36.893  1019  1403 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:36.893  1019  1403 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:36.893  1019  1403 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:36.893  1019  1403 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:36.893   284   284 I ANDROID_DRM_FRWORKS_DrmManager: DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
03-17 11:16:36.913  1229  2990 E SQLiteLog: (283) recovered 368 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
03-17 11:16:36.913  3019  3019 E Zygote  : MountEmulatedStorage()
03-17 11:16:36.913  3019  3019 E Zygote  : v2
03-17 11:16:36.913  3019  3019 I libpersona: KNOX_SDCARD checking this for 10155
03-17 11:16:36.913  3019  3019 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:36.913  3019  3019 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 11:16:36.913  3019  3019 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 11:16:36.913  1019  1403 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3019 uid=10155 gids={50155, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
03-17 11:16:36.923  3019  3019 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 11:16:36.933  1482  1482 E CscReceiver: onReceive android.intent.action.BOOT_COMPLETED
03-17 11:16:36.933  2913  2913 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 141.787ms
03-17 11:16:36.943   331   331 I ServiceManager: Waiting for service AtCmdFwd...
03-17 11:16:36.943  1019  1851 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:36.943  1019  1851 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 11:16:36.943  1019  1851 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
03-17 11:16:36.943   306   306 E USB_UICC: Timeout! No signal received. Retry num = 29
03-17 11:16:36.943  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:36.943  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:36.953  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:36.953  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:36.953  3019  3019 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 11:16:36.953  3019  3019 D ActivityThread: Added TimaKeyStore provider
03-17 11:16:36.953  1482  1482 D CscUpdateService: onStart
03-17 11:16:36.953  1482  1482 E CscUpdateService: costomer file is exists : it has been preconfiged.
03-17 11:16:36.953  1482  1482 I CscUpdateService: set_CSC_version
03-17 11:16:36.953  1482  1482 E CscParser: update(): xml file exist
03-17 11:16:36.963  3034  3034 E Zygote  : MountEmulatedStorage()
03-17 11:16:36.963  3034  3034 E Zygote  : v2
03-17 11:16:36.963  3034  3034 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 11:16:36.963  3034  3034 I libpersona: KNOX_SDCARD checking this for 10002
03-17 11:16:36.963  3034  3034 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:36.973  3034  3034 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 11:16:36.973  3034  3034 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 11:16:36.973  1019  1141 I ActivityManager: Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=3034 uid=10002 gids={50002, 9997, 3002, 3003, 1028} abi=armeabi-v7a
03-17 11:16:36.993  1482  1482 I CscUtil : isWifiOnly = false
03-17 11:16:36.993  1482  1482 I System.out: HandDataNode = null
03-17 11:16:36.993  1482  1482 I CscUpdateService: PATH_CSCNAME =CustomerDataSet.CSCName
03-17 11:16:37.003  2478  2478 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
03-17 11:16:37.003  1482  1482 I CscUpdateService: This is normal boot : CSC not updated
03-17 11:16:37.003  1482  3055 E CscParser: update(): xml file exist
03-17 11:16:37.013  3034  3034 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 11:16:37.013  3034  3034 D ActivityThread: Added TimaKeyStore provider
03-17 11:16:37.013  1229  2990 D MediaScanner: Prescan. DB items number : 138 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
03-17 11:16:37.013  1482  3055 D CscGPS  : CSCGPS.updateParameters
03-17 11:16:37.013  1482  3055 D CscGPS  : supl host : null
03-17 11:16:37.013  1482  3055 D CscGPS  : SUPL Host is null or invalid
03-17 11:16:37.013  1482  3055 D CscGPS  : supl_ver : null
03-17 11:16:37.013  1482  3055 D CscGPS  : SUPL Ver is null or invalid
03-17 11:16:37.013  1482  3055 D CscGPS  : supl port : null
03-17 11:16:37.013  1482  3055 D CscGPS  : SUPL PORT is null or invalid
03-17 11:16:37.013  1482  3055 D CscGPS  : LPP : null
03-17 11:16:37.013  1482  3055 D CscGPS  : LPP is null or invalid
03-17 11:16:37.013  1482  3055 D CscGPS  : CSC don't have any AGPS value.
03-17 11:16:37.023  1019  1386 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:37.023  1019  1386 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 11:16:37.023  1019  1386 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
03-17 11:16:37.023  1482  1509 D TP/MmsSmsProvider: query,matched:200, calling pid = 2478
03-17 11:16:37.023  1482  1509 D TP/MmsSmsProvider: match 200:Elapsed time : 0.780 ms
03-17 11:16:37.033  1019  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:37.033  1019  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:37.033  1019  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:37.033  1019  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:37.033  3019  3019 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 11:16:37.033  2164  2948 W DriveInitializer: Background init thread ended
03-17 11:16:37.043  1482  1482 I CscUpdateService: same CSC Version
03-17 11:16:37.043  1482  1482 D CscUtil : Set Build Fingerprint to samsung/a3ultexx/a3ulte:5.0.2/LRX22G/A300FUXXU1BOEC:user/release-keys
03-17 11:16:37.043  2748  2873 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 11:16:37.053  3065  3065 E Zygote  : MountEmulatedStorage()
03-17 11:16:37.053  3065  3065 E Zygote  : v2
03-17 11:16:37.053  3065  3065 I libpersona: KNOX_SDCARD checking this for 10043
03-17 11:16:37.053  3065  3065 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:37.053  3065  3065 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 11:16:37.053  1019  1525 I ActivityManager: Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3065 uid=10043 gids={50043, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-17 11:16:37.053  3065  3065 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 11:16:37.053  3065  3065 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 11:16:37.073  1482  1920 D TP/SmsProvider: query,matched:0, calling pid = 2478
03-17 11:16:37.073  1482  1920 D TP/SmsProvider: match 0:Elapsed time : 2.322 ms
03-17 11:16:37.083  3065  3065 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 11:16:37.083  3065  3065 D ActivityThread: Added TimaKeyStore provider
03-17 11:16:37.093  2478  2478 D Mms/SmsReceiverService: onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
03-17 11:16:37.093  2478  3074 D Mms/TelephonyPermission: isDefault true
03-17 11:16:37.093  2478  3074 D Mms/SmsReceiverService: [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
03-17 11:16:37.093  2478  3074 D Mms/SmsReceiverService: [start]    handleBootCompleted() consume time = 232.365625
03-17 11:16:37.103  1019  1615 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:37.103  1019  1615 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 11:16:37.103  1019  1615 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
03-17 11:16:37.113  1019  1626 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:37.113  1482  1503 D TP/MmsSmsProvider: getThreadUnReadCount unreadCount=0 imUnreadCount=0
03-17 11:16:37.113  1482  1503 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775806
03-17 11:16:37.113  1019  1626 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 11:16:37.113  3065  3065 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 11:16:37.113  1019  1626 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
03-17 11:16:37.113  3065  3065 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 11:16:37.113  3065  3065 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 11:16:37.113  1482  1503 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-17 11:16:37.113  1482  1503 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775806
03-17 11:16:37.113  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:37.113  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:37.113  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:37.113  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:37.113  1482  1503 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
03-17 11:16:37.123  1482  1503 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 11:16:37.123  1482  1503 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 11:16:37.123  1482  1503 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 11:16:37.123  1482  1503 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 11:16:37.123  1482  1503 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 11:16:37.123  1482  1503 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 11:16:37.123  3081  3081 E Zygote  : MountEmulatedStorage()
03-17 11:16:37.123  3081  3081 E Zygote  : v2
03-17 11:16:37.123  3081  3081 I libpersona: KNOX_SDCARD checking this for 1000
03-17 11:16:37.123  3081  3081 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:37.133  3081  3081 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 11:16:37.133  3081  3081 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 11:16:37.133  1019  1031 I ActivityManager: Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3081 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 11:16:37.133  3081  3081 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 11:16:37.133  1482  1503 D TP/MmsSmsProvider: delete threadId: 9223372036854775806
03-17 11:16:37.133  1482  1503 D TP/MmsSmsProvider: need read changed broadcast:false
03-17 11:16:37.133  2478  3074 D Mms/Conversation: deleteTempConversation(),deleted=0
03-17 11:16:37.153  3081  3081 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 11:16:37.153  3081  3081 D ActivityThread: Added TimaKeyStore provider
03-17 11:16:37.163  3019  3019 D [0]UMC:Core: onCreate(): 
03-17 11:16:37.193  1019  1031 D SettingsProvider: name = block_emergency_message
03-17 11:16:37.193  1019  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 11:16:37.193  1019  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 11:16:37.193  1019  1031 D SettingsProvider: selectionArgs: false
03-17 11:16:37.193  1019  1031 D SettingsProvider: selectionArgs: 10043
03-17 11:16:37.193  1019  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 11:16:37.193  1019  1031 D SettingsProvider: ret = -1
03-17 11:16:37.193  1019  1382 W ActivityManager: getTasks: caller 10043 is using old GET_TASKS but privileged; allowing
03-17 11:16:37.213  1482  1920 D SmsProvider: Update uri=content://sms/outbox, match=8
03-17 11:16:37.233  1019  1382 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:37.233  1019  1382 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 11:16:37.233  1019  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
03-17 11:16:37.243  1019  1045 I ActivityManager: Waited long enough for: ServiceRecord{2b661677 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
03-17 11:16:37.243  1321  1321 I WifiCredService: onCreate
03-17 11:16:37.253  1482  1920 D TP/MmsSmsProvider: need read changed broadcast:false
03-17 11:16:37.253  2478  3074 D Mms/SmsReceiverService: moveOutboxMessagesToFailedBox messageCount: 0
03-17 11:16:37.263  2478  3074 D Mms/SmsReceiverService: handle boot completed, sendFirstQueuedMessage()
03-17 11:16:37.273  2478  3074 D Mms/SmsReceiverService: [SIM-1]sendFirstQueuedMessage()
03-17 11:16:37.273  1482  1509 I art     : Explicit concurrent mark sweep GC freed 40361(2MB) AllocSpace objects, 11(176KB) LOS objects, 45% free, 4MB/8MB, paused 1.441ms total 175.902ms
03-17 11:16:37.273  1482  1509 D TP/SmsProvider: query,matched:51, calling pid = 2478
03-17 11:16:37.273  1482  1509 D TP/SmsProvider: match 51:Elapsed time : 2.227 ms
03-17 11:16:37.283  3019  3019 D [0]UMC:DeviceInfo: USA==US==
03-17 11:16:37.293  1482  2067 D TP/SmsProvider: query,matched:26, calling pid = 2478
03-17 11:16:37.313   280   989 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 11:16:37.313   280   989 D Netd    : getNetworkForDns: using netid 502 for uid 10117
03-17 11:16:37.343  3019  3019 D USER_AGENT: UMC/1.3.23 (SM-A300FU) SAFE-5.3 KNOX-2.3 en_US
03-17 11:16:37.353  3019  3019 D [0]UMC:AdminManager: init - start
03-17 11:16:37.353  3019  3019 D [0]UMC:AdminManager: loadAdmins
03-17 11:16:37.363  3019  3019 D [0]UMC:AdminManager: init - end
03-17 11:16:37.363  3019  3019 D GSLBManager: migrateStoredUrlFromOldPref
03-17 11:16:37.383  3019  3019 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
03-17 11:16:37.383  3019  3019 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
03-17 11:16:37.383  3019  3019 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
03-17 11:16:37.383  3019  3019 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-17 11:16:37.383  3019  3019 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-17 11:16:37.393  3019  3019 D [0]UMC:UMCAdmin: isContainer : 0
03-17 11:16:37.403  1019  1142 I ActivityManager: Killing 2252:com.vlingo.midas/u0a28 (adj 15): empty #31
03-17 11:16:37.413  1019  1031 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
03-17 11:16:37.413  3019  3019 E [0]UMC:UMCAdmin: No active admin owned by uid 10155
03-17 11:16:37.413  3019  3019 D [0]UMC:UMCAdmin: isContainer : 0
03-17 11:16:37.423  3019  3019 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
03-17 11:16:37.423  3019  3019 D [0]UMC:CoreReceiver: Intent : android.intent.action.BOOT_COMPLETED
03-17 11:16:37.423  3019  3019 D [0]UMC:CoreReceiver:  check PreETag 
03-17 11:16:37.443  1019  1851 I art     : Explicit concurrent mark sweep GC freed 28005(1423KB) AllocSpace objects, 6(319KB) LOS objects, 33% free, 22MB/33MB, paused 3.579ms total 160.573ms
03-17 11:16:37.443  1482  2067 D TP/SmsProvider: match 26:Elapsed time : 152.522 ms
03-17 11:16:37.443  1019  1359 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:37.443  1019  1359 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:37.443  1019  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 11:16:37.443  1019  1403 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:37.453  1019  1403 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:37.453  1019  1403 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:37.453  1019  1403 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:37.453  1321  1321 D WifiTimerReceiver: action: android.intent.action.BOOT_COMPLETED
03-17 11:16:37.453  1321  1321 D WifiTimerReceiver: extra: Bundle[mParcelledData.dataSize=84]
03-17 11:16:37.453  1321  1321 D MY_TAG  : Action boot completed received
03-17 11:16:37.453  1229  2990 V MediaScanner: processDirectory :  /system/media
03-17 11:16:37.463  3118  3118 E Zygote  : MountEmulatedStorage()
03-17 11:16:37.463  3118  3118 E Zygote  : v2
03-17 11:16:37.463  3118  3118 I libpersona: KNOX_SDCARD checking this for 1000
03-17 11:16:37.463  3118  3118 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:37.463  1019  1403 I ActivityManager: Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3118 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 11:16:37.473  3118  3118 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 11:16:37.473  3118  3118 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 11:16:37.473  3118  3118 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 11:16:37.473  1019  1403 I ActivityManager: Killing 1536:com.android.printspooler/u0a132 (adj 15): empty #31
03-17 11:16:37.473  1321  1321 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
03-17 11:16:37.483  1019  1133 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
03-17 11:16:37.483  1019  1133 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-17 11:16:37.483  1019  1133 E WifiNative-wlan0: invaild command id : 215
03-17 11:16:37.493  2478  3015 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
03-17 11:16:37.493  1321  1321 D NearbySettings: MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
03-17 11:16:37.503  3017  3017 D AndroidRuntime: 
03-17 11:16:37.503  3017  3017 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 11:16:37.503  1019  1359 D SettingsProvider: name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
03-17 11:16:37.503  1019  1525 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:37.503  1019  1525 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:37.503  1019  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 11:16:37.503  3118  3118 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 11:16:37.503  3118  3118 D ActivityThread: Added TimaKeyStore provider
03-17 11:16:37.503  3017  3017 D AndroidRuntime: CheckJNI is OFF
03-17 11:16:37.503  3017  3017 D AndroidRuntime: readGMSProperty: start
03-17 11:16:37.503  3017  3017 D AndroidRuntime: readGMSProperty: already setted!!
03-17 11:16:37.503  3017  3017 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 11:16:37.503  3017  3017 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 11:16:37.503  3017  3017 D AndroidRuntime: readGMSProperty: end
03-17 11:16:37.503  3017  3017 D AndroidRuntime: addProductProperty: start
03-17 11:16:37.503  3019  3019 D [0]UMC:ByodSetupStarter: Container ID : 0
03-17 11:16:37.513  1321  2220 V NearbySettings: MountReceiver.mPrefHandler - 7002
03-17 11:16:37.513  1019  1403 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:37.513  1019  1403 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:37.513  3019  3019 V [0]UMC:Utils: checkAppScreen() : com.sec.android.app.launcher
03-17 11:16:37.513  1019  1403 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 11:16:37.513  3019  3019 I [0]UMC:Core: shutdown
03-17 11:16:37.523  3019  3019 I art     : System.exit called, status: 0
03-17 11:16:37.523  3019  3019 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
03-17 11:16:37.523  1229  2990 V MediaScanner:  prescan time: 588ms (DB items: 138)
03-17 11:16:37.523  1229  2990 V MediaScanner:     scan time: 78ms (Caching mode: true), (makeEntry time: 24ms ~30%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 11:16:37.523  1229  2990 V MediaScanner: postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-17 11:16:37.523  1229  2990 V MediaScanner:    total time: 666ms
03-17 11:16:37.523  1229  2990 V MediaScanner: checked files: 130  directories : 6  (I: 0, U: 0)
03-17 11:16:37.523  1229  2990 D MediaScanner: checkDefaultSounds
03-17 11:16:37.523  1229  2990 D MediaScanner: system alarm_alert  : Vwiurug_etwofi5wgg
03-17 11:16:37.543  1608  1619 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
03-17 11:16:37.543  1229  2990 D MediaScanner: OK. alarm_alert is already exist in setting DB.
03-17 11:16:37.543  1321  1321 I NearbySettings: MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
03-17 11:16:37.543  1321  1321 I NearbySettings: MountReceiver.onReceive - Internal Path
03-17 11:16:37.553  3118  3118 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 11:16:37.553  1229  2990 D MediaScanner: system notification_sound  : K_Oprkltf5wgg
03-17 11:16:37.563  2478  3074 D Mms/SmsReceiver: unregisterForServiceStateChanges, already unregistered
03-17 11:16:37.563  2478  3074 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-17 11:16:37.563  2478  3074 D Mms/TelephonyPermission: isDefault true
03-17 11:16:37.563  1229  2990 D MediaScanner: OK. notification_sound is already exist in setting DB.
03-17 11:16:37.563  1019  1044 W libprocessgroup: failed to open /acct/uid_10028/pid_2252/cgroup.procs: No such file or directory
03-17 11:16:37.563  1019  1044 W libprocessgroup: failed to open /acct/uid_10132/pid_1536/cgroup.procs: No such file or directory
03-17 11:16:37.573  1177  1177 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 11:16:37.573  1229  2990 D MediaScanner: system ringtone  : Wmfi_lpf_pwirywu5wgg
03-17 11:16:37.573  1229  2990 D MediaScanner: OK. ringtone is already exist in setting DB.
03-17 11:16:37.573  1019  1403 I ActivityManager: Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3019)(adj 0) has died(56,663)
03-17 11:16:37.583  1482  1509 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2478
03-17 11:16:37.583  1229  2990 D MediaScannerService: !@done scanning volume internal
03-17 11:16:37.583  2636  2636 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2636) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 11:16:37.583  2636  2636 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2636) ACTION_MEDIA_SCANNER_FINISHED = /system/media
03-17 11:16:37.583  2636  2636 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2636) ACTION_MEDIA_SCANNER_FINISHED = Ignored
03-17 11:16:37.593  1229  2990 D MediaScannerService: !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
03-17 11:16:37.593  1713  1713 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-17 11:16:37.593  1713  1713 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 11:16:37.593  1713  1713 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-17 11:16:37.603  1019  1626 D SettingsProvider: name = personal_mode_enabled
03-17 11:16:37.603  3081  3081 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
03-17 11:16:37.603  1019  1525 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:37.603  1019  1525 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:37.603  1019  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
03-17 11:16:37.603  1019  1851 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:37.603  1019  1851 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:37.613  1229  2990 D MediaProvider: savePlaylistTableInBulkDeleter started
03-17 11:16:37.603  1019  1851 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:37.603  1019  1851 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:37.613  1229  2990 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
03-17 11:16:37.613  1713  1713 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-17 11:16:37.613  1608  1625 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-17 11:16:37.613  1608  1625 D BadgeProvider: sendNotify, [notify] : null
03-17 11:16:37.613  1608  1625 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 11:16:37.613  1608  1625 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 11:16:37.613  1608  1625 D BadgeProvider: update, [UpdateCount] : 1
03-17 11:16:37.613  1511  1511 D Launcher.Model: reloadBadges entered.
03-17 11:16:37.613  1229  2990 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
03-17 11:16:37.623  1713  1713 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
03-17 11:16:37.623  3146  3146 E Zygote  : MountEmulatedStorage()
03-17 11:16:37.623  3146  3146 E Zygote  : v2
03-17 11:16:37.623  3146  3146 I libpersona: KNOX_SDCARD checking this for 10082
03-17 11:16:37.623  3146  3146 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:37.623  3146  3146 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 11:16:37.623  3146  3146 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 11:16:37.633  3146  3146 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 11:16:37.633  1229  2990 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-17 11:16:37.633  1229  2990 D MediaProvider: savePlaylistTableInBulkDeleter started
03-17 11:16:37.633  1229  2990 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
03-17 11:16:37.633  1019  1851 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3146 uid=10082 gids={50082, 9997, 3003} abi=armeabi-v7a
03-17 11:16:37.633  1229  2990 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
03-17 11:16:37.633  1229  2990 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-17 11:16:37.633  1713  1713 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
03-17 11:16:37.643  1713  1713 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 11:16:37.643  1713  1713 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-17 11:16:37.643  1713  1713 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-17 11:16:37.643  1713  1713 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 11:16:37.643  1713  1713 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-17 11:16:37.643  1713  1713 D daemonapp: [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
03-17 11:16:37.643  1019  1626 D SettingsProvider: name = aw_daemon_service_key_version_check
03-17 11:16:37.643  1019  1626 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 11:16:37.643  1019  1626 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 11:16:37.643  1019  1626 D SettingsProvider: selectionArgs: false
03-17 11:16:37.643  1019  1626 D SettingsProvider: selectionArgs: 10157
03-17 11:16:37.643  1019  1626 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 11:16:37.643  1019  1626 D SettingsProvider: ret = -1
03-17 11:16:37.653  1229  2990 D MediaScanner: Prescan. DB items number : 26 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
03-17 11:16:37.663  2478  3015 D Mms/MessagingNotification: setBadgeCount(), count=0
03-17 11:16:37.663  2478  3015 D Mms/MessagingNotification: remove alarm
03-17 11:16:37.673  3146  3146 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 11:16:37.673  3146  3146 D ActivityThread: Added TimaKeyStore provider
03-17 11:16:37.683  1482  1509 D TP/MmsSmsProvider: query,matched:200, calling pid = 2478
03-17 11:16:37.683  1482  1509 D TP/MmsSmsProvider: match 200:Elapsed time : 2.276 ms
03-17 11:16:37.683  3081  3081 D DSM     : [Lines:107] Normal booted
03-17 11:16:37.683  3081  3081 D DSM     : [Lines:114] Boot completed
03-17 11:16:37.683  1019  1032 I ActivityManager: Killing 2281:com.sec.android.app.videoplayer/u0a45 (adj 15): empty #31
03-17 11:16:37.693  1019  1626 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10157
03-17 11:16:37.693  2478  3161 D Mms/MessagingNotification: updateAllHistoryAsRead()
03-17 11:16:37.693  1229  2990 V MediaScanner: processDirectory :  /storage/emulated/0
03-17 11:16:37.703  1229  2990 D MediaScanner: Skipping:
03-17 11:16:37.703  1229  2990 D MediaScanner: 7klwibgf7fvntblfd7(75ebcf7
03-17 11:16:37.703  1713  1713 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
03-17 11:16:37.703  1713  1713 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
03-17 11:16:37.713  1482  2067 D TP/SmsProvider: query,matched:0, calling pid = 2478
03-17 11:16:37.713  1482  2067 D TP/SmsProvider: match 0:Elapsed time : 0.917 ms
03-17 11:16:37.713  1177  1177 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 11:16:37.713  1713  1713 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-17 11:16:37.713  1713  1713 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 11:16:37.713  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:37.713  1713  1713 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
03-17 11:16:37.713  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:37.713  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:37.713  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:37.713  1713  1713 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
03-17 11:16:37.723  1229  2990 D MediaScanner: Skipping:
03-17 11:16:37.723  1229  2990 D MediaScanner: 7klwibgf7fvntblfd7(7Budiwrd7dblb7
03-17 11:16:37.723  1229  2990 V MediaScanner: processDirectory :  /storage/extSdCard
03-17 11:16:37.723  1229  2990 W MediaScanner: Error opening directory, reason : Permission denied.
03-17 11:16:37.723  1229  2990 W MediaScanner: 7klwibgf7fxlKdCbid7
03-17 11:16:37.723  1713  1713 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
03-17 11:16:37.723  1713  1713 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-17 11:16:37.723  3162  3162 E Zygote  : MountEmulatedStorage()
03-17 11:16:37.723  3162  3162 E Zygote  : v2
03-17 11:16:37.723  3162  3162 I libpersona: KNOX_SDCARD checking this for 1000
03-17 11:16:37.723  3162  3162 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:37.733  3162  3162 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 11:16:37.733  1229  2990 V MediaScanner:  prescan time: 62ms (DB items: 26)
03-17 11:16:37.733  1229  2990 V MediaScanner:     scan time: 27ms (Caching mode: true), (makeEntry time: 16ms ~59%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 11:16:37.733  1229  2990 V MediaScanner: postscan time: 9ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-17 11:16:37.733  1229  2990 V MediaScanner:    total time: 98ms
03-17 11:16:37.733  1713  1713 D daemonapp: [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1458209797737
03-17 11:16:37.733  1229  2990 V MediaScanner: checked files: 10  directories : 16  (I: 0, U: 0)
03-17 11:16:37.733  1713  1713 D daemonapp: [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1458231360000
03-17 11:16:37.733  1713  1713 D daemonapp: [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
03-17 11:16:37.733  1713  1713 D daemonapp: [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
03-17 11:16:37.733  3162  3162 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 11:16:37.733  3162  3162 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 11:16:37.743  1019  1141 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3162 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 11:16:37.743  1019  1141 I ActivityManager: Killing 2339:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
03-17 11:16:37.763  1482  1482 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 11:16:37.763  1482  1482 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 11:16:37.763  1482  1482 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 11:16:37.763  1482  1482 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 11:16:37.763  1482  1482 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 11:16:37.763  1482  1482 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-17 11:16:37.773  3162  3162 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 11:16:37.773  3162  3162 D ActivityThread: Added TimaKeyStore provider
03-17 11:16:37.773   321   321 I art     : Explicit concurrent mark sweep GC freed 8706(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 686us total 23.648ms
03-17 11:16:37.773  1713  1713 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458231360000
03-17 11:16:37.783  1019  1525 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-17 11:16:37.783  1019  1525 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4308, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-17 11:16:37.783  1019  1525 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-17 11:16:37.783  1019  1019 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-17 11:16:37.783  2478  3015 D Mms/MessagingNotification: [end]    nonBlockingUpdateMessageIndicator() consume time = 687.169635
03-17 11:16:37.783  1019  1019 I MotionRecognitionService: Plugged
03-17 11:16:37.783  1019  1019 I MotionRecognitionService: mGripSensorEnabled= false
03-17 11:16:37.783  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-17 11:16:37.783  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
03-17 11:16:37.783  1482  2067 D TP/SmsProvider: query,matched:0, calling pid = 2478
03-17 11:16:37.783  1177  1177 D PowerUI : Cable  true --> true mBootCompleted : true
03-17 11:16:37.783  1177  1177 D PowerUI : Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
03-17 11:16:37.793   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.941ms
03-17 11:16:37.793  1482  2067 D TP/SmsProvider: match 0:Elapsed time : 3.269 ms
03-17 11:16:37.793  1448  1448 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 11:16:37.793  1448  1448 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-17 11:16:37.793  3162  3162 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 11:16:37.803  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-17 11:16:37.803  2656  2764 D HeadsetStateMachine: Disconnected process message: 10
03-17 11:16:37.803  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 11:16:37.803  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 11:16:37.803  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 11:16:37.803  1177  1177 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-17 11:16:37.803  1177  1177 D SViewCoverView: level :100 plugged : 2
03-17 11:16:37.803   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 16.719ms
03-17 11:16:37.813  1482  1920 D TP/SmsProvider: query,matched:51, calling pid = 2478
03-17 11:16:37.813  1482  1920 D TP/SmsProvider: match 51:Elapsed time : 1.415 ms
03-17 11:16:37.823  1019  1044 W libprocessgroup: failed to open /acct/uid_10045/pid_2281/cgroup.procs: No such file or directory
03-17 11:16:37.823  1019  1044 W libprocessgroup: failed to open /acct/uid_10110/pid_2339/cgroup.procs: No such file or directory
03-17 11:16:37.833  2478  3074 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
03-17 11:16:37.843  1608  1619 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
03-17 11:16:37.853  1713  1713 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 74
03-17 11:16:37.853  1713  1713 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458231360000
03-17 11:16:37.893  1511  1511 D Launcher.Model: reloadBadges entered.
03-17 11:16:37.893  1608  1625 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-17 11:16:37.893  1608  1625 D BadgeProvider: sendNotify, [notify] : null
03-17 11:16:37.893  1608  1625 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 11:16:37.893  1608  1625 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 11:16:37.893  1608  1625 D BadgeProvider: update, [UpdateCount] : 1
03-17 11:16:37.893  1713  1713 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
03-17 11:16:37.893  1713  1713 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
03-17 11:16:37.893  2478  3074 D Mms/MessagingNotification: setBadgeCount(), count=0
03-17 11:16:37.893  2636  2636 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2636) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 11:16:37.893  2636  2636 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2636) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
03-17 11:16:37.893  2636  2636 D FactoryTestApp: [DummyFtClient$sendBootCompletedAndFinish](2636) ...
03-17 11:16:37.893  2636  2636 D FactoryTestApp: [Support$Values.getString](2636) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 11:16:37.893  2636  2636 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2636) mConnectionMode = gsm
03-17 11:16:37.893  2636  2636 D FactoryTestApp: [IPCWriterToSecPhoneService$ResponseWriter](2636) Create IPCWriterToSecPhoneService
03-17 11:16:37.893  2636  2636 I FactoryTestApp: [IPCWriterToSecPhoneService$connectToSecPhoneService](2636)  
03-17 11:16:37.903  2478  3074 D Mms/MessagingNotification: remove alarm
03-17 11:16:37.903  1229  2990 D MediaScannerService: !@done scanning volume external
03-17 11:16:37.903  2636  2636 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
03-17 11:16:37.903  1321  1321 I SmartcardBootCompleteReceiver: SmartcardBootCompleteReceiver - onReceive() 
03-17 11:16:37.903  1321  1321 I SmartcardBootCompleteReceiver: Received intent with action - android.intent.action.BOOT_COMPLETED
03-17 11:16:37.913  2478  3177 D Mms/MessagingNotification: updateAllHistoryAsRead()
03-17 11:16:37.913  1019  1359 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:37.913  1019  1359 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:37.913  1019  1359 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:37.913  1019  1359 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:37.913  1482  1503 D TP/SmsProvider: query,matched:0, calling pid = 2478
03-17 11:16:37.913  1482  1503 D TP/SmsProvider: match 0:Elapsed time : 1.798 ms
03-17 11:16:37.923  3180  3180 E Zygote  : MountEmulatedStorage()
03-17 11:16:37.923  3180  3180 E Zygote  : v2
03-17 11:16:37.923  3180  3180 I libpersona: KNOX_SDCARD checking this for 10161
03-17 11:16:37.923  3180  3180 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:37.933  3180  3180 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 11:16:37.933  1019  1359 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3180 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 11:16:37.933  3180  3180 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 11:16:37.933  3180  3180 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 11:16:37.943  1019  1615 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:37.943  1019  1615 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 11:16:37.943  1019  1615 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
03-17 11:16:37.943   331   331 I ServiceManager: Waiting for service AtCmdFwd...
03-17 11:16:37.943  3162  3162 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-17 11:16:37.943   306   306 E USB_UICC: Timeout! No signal received. Retry num = 30
03-17 11:16:37.953  2478  3074 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 169.925677
03-17 11:16:37.953  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a300fu.dat
03-17 11:16:37.953  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a3ulte.dat
03-17 11:16:37.963  3180  3180 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 11:16:37.963  3146  3146 E UpdateRequestReceiver: ignoring update request
03-17 11:16:37.963  3180  3180 D ActivityThread: Added TimaKeyStore provider
03-17 11:16:37.963  3162  3162 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a300fu.dat
03-17 11:16:37.963  3146  3146 E UpdateRequestReceiver: ignoring update request
03-17 11:16:37.983  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
03-17 11:16:37.983  1321  1321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
03-17 11:16:37.983  1321  1321 I SmartcardBootCompleteReceiver: Broadcast sent with current lockscreen type
03-17 11:16:37.993  1019  1142 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:37.993  1019  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:37.993  1019  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
03-17 11:16:38.003  2636  2636 I FactoryTestApp: [IPCWriterToSecPhoneService$onServiceConnected](2636) connected done
03-17 11:16:38.003  2636  2636 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2636) Send Response Message to SecPhone
03-17 11:16:38.003  2636  2636 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2636) Response ��
03-17 11:16:38.013   327  1076 D AT_Distributor: Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
03-17 11:16:38.023  3146  3146 E UpdateRequestReceiver: ignoring update request
03-17 11:16:38.023  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-17 11:16:38.023  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-17 11:16:38.023  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-17 11:16:38.023  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-17 11:16:38.023  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-17 11:16:38.023  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-17 11:16:38.023  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-17 11:16:38.023  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-17 11:16:38.023  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
03-17 11:16:38.023  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
03-17 11:16:38.023  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-17 11:16:38.023  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
03-17 11:16:38.023  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_RUN_REF
03-17 11:16:38.023  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
03-17 11:16:38.023  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
03-17 11:16:38.023  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
03-17 11:16:38.023  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-17 11:16:38.023  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
03-17 11:16:38.023  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
03-17 11:16:38.033  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
03-17 11:16:38.033  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
03-17 11:16:38.033  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
03-17 11:16:38.033  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
03-17 11:16:38.033  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
03-17 11:16:38.033  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
03-17 11:16:38.033  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
03-17 11:16:38.033  2636  2636 D FactoryTestApp: [IPCWriterToSecPhoneService$handleMessage](2636) Send BOOTING COMPLETED done
03-17 11:16:38.033  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
03-17 11:16:38.033  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
03-17 11:16:38.033  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
03-17 11:16:38.033  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
03-17 11:16:38.033  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
03-17 11:16:38.033  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
03-17 11:16:38.033  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
03-17 11:16:38.033  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
03-17 11:16:38.033  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
03-17 11:16:38.033  3162  3162 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
03-17 11:16:38.043  3162  3162 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
03-17 11:16:38.043  3146  3146 E UpdateRequestReceiver: ignoring update request
03-17 11:16:38.043  1019  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.043  1019  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.043  1019  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.043  1019  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.053   306   306 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-17 11:16:38.053   306   306 E USB_UICC: usb_uicc_init_qmi failed ! 
03-17 11:16:38.053   306   306 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
03-17 11:16:38.053   306   306 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
03-17 11:16:38.063  3209  3209 E Zygote  : MountEmulatedStorage()
03-17 11:16:38.063  3209  3209 E Zygote  : v2
03-17 11:16:38.063  3209  3209 I libpersona: KNOX_SDCARD checking this for 1000
03-17 11:16:38.063  3209  3209 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:38.063  1019  1527 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3209 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 11:16:38.063  1019  1527 I ActivityManager: Killing 2438:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
03-17 11:16:38.073  3146  3146 E UpdateRequestReceiver: ignoring update request
03-17 11:16:38.093  3146  3146 E UpdateRequestReceiver: ignoring update request
03-17 11:16:38.093  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.093  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.093  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.093  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.093  2656  2776 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
03-17 11:16:38.103  3222  3222 E Zygote  : MountEmulatedStorage()
03-17 11:16:38.103  3222  3222 E Zygote  : v2
03-17 11:16:38.103  3222  3222 I libpersona: KNOX_SDCARD checking this for 10088
03-17 11:16:38.103  3222  3222 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:38.113  3209  3209 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 11:16:38.113  3222  3222 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 11:16:38.113  3222  3222 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 11:16:38.113  3209  3209 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 11:16:38.113   327  1076 D AT_Distributor: SetAtdStatus(), 1_1_0
03-17 11:16:38.113   327  1076 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
03-17 11:16:38.113  3222  3222 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 11:16:38.113  3209  3209 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 11:16:38.123  1019  1141 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3222 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 11:16:38.123  1019  1141 I ActivityManager: Killing 2460:com.sec.android.app.camera/u0a135 (adj 15): empty #31
03-17 11:16:38.133  2656  2776 D BluetoothMediaBrowser: no now playing list
03-17 11:16:38.133  2656  2776 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
03-17 11:16:38.153  3222  3222 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 11:16:38.153  3209  3209 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 11:16:38.153  3222  3222 D ActivityThread: Added TimaKeyStore provider
03-17 11:16:38.153  3209  3209 D ActivityThread: Added TimaKeyStore provider
03-17 11:16:38.163  1321  1321 D [SBeam] : SBeamEnabler.initPreferenceForSbeam : 0
03-17 11:16:38.183  1019  1626 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:38.183  1019  1626 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:38.183  1019  1626 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 11:16:38.303  3209  3209 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
03-17 11:16:38.323  3180  3249 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 11:16:38.323  3180  3249 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-17 11:16:38.353  1019  1044 W libprocessgroup: failed to open /acct/uid_10139/pid_2438/cgroup.procs: No such file or directory
03-17 11:16:38.353  1019  1044 W libprocessgroup: failed to open /acct/uid_10135/pid_2460/cgroup.procs: No such file or directory
03-17 11:16:38.363  3180  3249 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
03-17 11:16:38.383  3017  3017 E AffinityControl: AffinityControl: registerfunction enter
03-17 11:16:38.383  1321  1321 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
03-17 11:16:38.383  1321  1321 I SettingSearch/SearchIntentReceiver: search setting db init!!
03-17 11:16:38.393  1321  1321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
03-17 11:16:38.403  1321  3252 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
03-17 11:16:38.413  1019  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.413  1019  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.413  1019  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.413  1019  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.423  3180  3249 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-17 11:16:38.423  3180  3249 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@bbf3093: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 11:16:38.423  3180  3249 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-17 11:16:38.423  3253  3253 E Zygote  : MountEmulatedStorage()
03-17 11:16:38.423  3253  3253 E Zygote  : v2
03-17 11:16:38.423  3253  3253 I libpersona: KNOX_SDCARD checking this for 1000
03-17 11:16:38.423  3253  3253 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:38.423  1019  1142 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3253 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 11:16:38.433  3253  3253 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 11:16:38.433  3253  3253 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 11:16:38.433  3253  3253 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 11:16:38.443  3017  3017 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 11:16:38.453  3253  3253 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 11:16:38.453  3253  3253 D ActivityThread: Added TimaKeyStore provider
03-17 11:16:38.453  1019  1525 E PersonaManagerService: inState():  stateMachine is null !!
03-17 11:16:38.453  1019  1525 I PersonaManagerService: PersonaId don't exist
03-17 11:16:38.453  1019  1525 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-17 11:16:38.473  1019  1525 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 11:16:38.473  3253  3253 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 11:16:38.483  1019  15,25 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-17 11:16:38.483  1019  1525 W ActivityManager: mDVFSHelper.acquire()
03-17 11:16:38.483  1019  1525 D FocusedStackFrame: Set to : 0
03-17 11:16:38.493  1019  1525 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 11:16:38.493  1019  1525 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 11:16:38.493  1019  1525 D InputDispatcher: Focused application set to: xxxx
03-17 11:16:38.493  1019  1525 D InputDispatcher: Focus left window: 1511
03-17 11:16:38.493  3017  3017 D AndroidRuntime: Shutting down VM
03-17 11:16:38.493  1019  1050 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 11:16:38.493  1019  1050 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-17 11:16:38.493  1019  1615 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.493  1019  1615 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.493  1019  1615 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.493  1019  1615 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.503  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 11:16:38.503  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 11:16:38.513  1019  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 11:16:38.513  1019  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 11:16:38.513   259   259 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, uhalitest
03-17 11:16:38.513  3271  3271 E Zygote  : MountEmulatedStorage()
03-17 11:16:38.513  3271  3271 E Zygote  : v2
03-17 11:16:38.513  3271  3271 I libpersona: KNOX_SDCARD checking this for 10146
03-17 11:16:38.513  3271  3271 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:38.513  1019  1615 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3271 uid=10146 gids={50146, 9997} abi=armeabi-v7a
03-17 11:16:38.583  3271  3271 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 11:16:38.583  3271  3271 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 11:16:38.583  3271  3271 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 11:16:38.593  1511  1511 D Launcher.HomeView: onPause
03-17 11:16:38.603  1511  1511 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-17 11:16:38.603  1019  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.603  1019  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.603  1019  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.603  1019  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.613  3271  3271 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 11:16:38.613  3253  3253 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
03-17 11:16:38.613  3271  3271 D ActivityThread: Added TimaKeyStore provider
03-17 11:16:38.623  3287  3287 E Zygote  : MountEmulatedStorage()
03-17 11:16:38.623  3287  3287 E Zygote  : v2
03-17 11:16:38.623  3287  3287 I libpersona: KNOX_SDCARD checking this for 10167
03-17 11:16:38.623  3287  3287 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:38.633  1019  1527 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3287 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 11:16:38.633  3287  3287 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 11:16:38.633  3287  3287 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 11:16:38.633  3287  3287 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 11:16:38.663  1511  1511 V ActivityThread: updateVisibility : ActivityRecord{12f43c82 token=android.os.BinderProxy@1ef6acb2 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-17 11:16:38.663  3209  3209 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
03-17 11:16:38.673  3287  3287 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 11:16:38.673  3287  3287 D ActivityThread: Added TimaKeyStore provider
03-17 11:16:38.673  1019  1525 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 11:16:38.673  1019  1525 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 11:16:38.673  1019  1525 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 11:16:38.673  3209  3209 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
03-17 11:16:38.673  1511  1511 D Launcher.HomeView: onStop
03-17 11:16:38.683  1511  1511 V ActivityThread: updateVisibility : ActivityRecord{12f43c82 token=android.os.BinderProxy@1ef6acb2 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-17 11:16:38.683  1019  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 11:16:38.683  1019  1525 D PersonaManager: isKioskContainerExistOnDevice
03-17 11:16:38.713  3017  3017 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-17 11:16:38.713  3209  3209 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
03-17 11:16:38.713  3209  3209 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-17 11:16:38.713  3209  3209 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
03-17 11:16:38.713  3209  3209 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
03-17 11:16:38.713  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-17 11:16:38.723  1019  1019 D SensorService: [SO] activate (ident=0xb76d10e0, enabled=0)
03-17 11:16:38.723  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-17 11:16:38.723  1019  1527 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:38.723  1019  1527 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
03-17 11:16:38.723  1019  1527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
03-17 11:16:38.723  1019  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.723  1019  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.723  1019  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.723  1019  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.723  1511  1511 D Launcher: onTrimMemory. Level: 20
03-17 11:16:38.743  3303  3303 E Zygote  : MountEmulatedStorage(),
03-17 11:16:38.743  3303  3303 E Zygote  : v2
03-17 11:16:38.743  3303  3303 I libpersona: KNOX_SDCARD checking this for 10088
03-17 11:16:38.743  1019  1019 D SensorManager: unregisterListener ::   
03-17 11:16:38.743  3303  3303 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:38.743  1019  1019 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns),
,03-17 11:16:38.743  3303  3303 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 11:16:38.743  1019  1527 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3303 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 11:16:38.753  3303  3303 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 11:16:38.753  1019  1019 D SensorService: [SO] changed settle time [1]
03-17 11:16:38.753  1019  1019 D SensorService: [SO] setDelay [66000000]
03-17 11:16:38.753  1019  1019 D SensorService: [SO] activate (ident=0xb797ff68, enabled=1)
03-17 11:16:38.753  1019  1019 D SensorService: [SO] AR_init
03-17 11:16:38.753  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-17 11:16:38.753  3303  3303 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 11:16:38.763  1019  1019 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-17 11:16:38.773  3253  3253 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,03-17 11:16:38.783  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.783  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.783  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:38.783  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:38.803  3320  3320 E Zygote  : MountEmulatedStorage()
03-17 11:16:38.803  3320  3320 I libpersona: KNOX_SDCARD checking this for 1000
03-17 11:16:38.803  3320  3320 E Zygote  : v2
03-17 11:16:38.803  3320  3320 I libpersona: KNOX_SDCARD not a persona
,03-17 11:16:38.803  3320  3320 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 11:16:38.803  1019  1032 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3320 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 11:16:38.803  3253  3253 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
03-17 11:16:38.803  3320  3320 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:38.803  3320  3320 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 11:16:38.803  3253  3253 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,03-17 11:16:38.813  3303  3303 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:38.813  3303  3303 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:38.833  1019  1042 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 11:16:38.853  3320  3320 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:38.853  3320  3320 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:38.873  3222  3222 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
,03-17 11:16:38.893  3287  3287 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,03-17 11:16:38.903  1019  1042 D SensorService: [SO] -0.460 0.192 9.883
03-17 11:16:38.903  1019  1042 D SensorService: [SO] [100 -> 255]
,03-17 11:16:38.913  3287  3287 I LibraryLoader: Loading: webviewchromium
,03-17 11:16:38.913  3287  3287 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 6959-6965)
03-17 11:16:38.913  3287  3287 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 11:16:38.923   295   295 E SMD     : DCD OFF
,03-17 11:16:38.923  3222  3222 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,03-17 11:16:38.943   331   331 I ServiceManager: Waiting for service AtCmdFwd...,
,03-17 11:16:38.993  3287  3287 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {246fa81a}
,03-17 11:16:38.993  3287  3287 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 11:16:39.003  3287  3287 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,03-17 11:16:39.003  1019  1386 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:39.003  1019  1386 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:39.003  1019  1386 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:39.003  1019  1386 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:39.003  3222  3222 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,03-17 11:16:39.003  3253  3253 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,03-17 11:16:39.003  3253  3253 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,03-17 11:16:39.003  3253  3253 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,03-17 11:16:39.013  3222  3222 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,03-17 11:16:39.023  1019  1386 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3347 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 11:16:39.033  3222  3222 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,03-17 11:16:39.033  3347  3347 E Zygote  : MountEmulatedStorage(),
03-17 11:16:39.033  3320  3320 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
03-17 11:16:39.033  3347  3347 E Zygote  : v2
03-17 11:16:39.033  3347  3347 I libpersona: KNOX_SDCARD checking this for 10008
03-17 11:16:39.033  3347  3347 I libpersona: KNOX_SDCARD not a persona,
,03-17 11:16:39.033  3320  3320 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-17 11:16:39.033  3287  3287 I BrowserStartupController: Initializing chromium process, renderers=0
,03-17 11:16:39.033  3347  3347 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 11:16:39.033  3287  3287 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 11:16:39.043  3347  3347 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 11:16:39.043   258   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 11:16:39.043   258   518 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 11:16:39.043  3180  3180 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
03-17 11:16:39.043  3347  3347 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 11:16:39.043  3320  3320 I DBG_POLICYDM: [com.policydm.eng.core.XDMMsg(70/xdmSendMessage)] waiting for DM_TaskHandler create
,03-17 11:16:39.063  3347  3347 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:39.063  3347  3347 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:39.073  1019  1525 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:39.073  1019  1525 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 11:16:39.073  1019  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 11:16:39.073  3287  3287 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,03-17 11:16:39.083  3287  3287 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,03-17 11:16:39.083  3287  3287 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,03-17 11:16:39.083  3222  3222 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
03-17 11:16:39.093  3253  3253 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
03-17 11:16:39.103  3253  3253 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
03-17 11:16:39.103  3253  3253 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
03-17 11:16:39.103  3287  3287 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 11:16:39.103  3287  3287 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 11:16:39.103  3287  3287 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 11:16:39.103  3287  3287 I Adreno-EGL: Local Branch: 
03-17 11:16:39.103  3287  3287 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 11:16:39.103  3287  3287 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 11:16:39.103  3287  3287 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
03-17 11:16:39.113  1177  1177 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
,03-17 11:16:39.113  1019  1359 I ActivityManager: Killing 1735:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,03-17 11:16:39.123  3253  3253 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
03-17 11:16:39.123  3253  3253 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
03-17 11:16:39.123  3253  3253 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
03-17 11:16:39.123  3253  3253 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
03-17 11:16:39.123  3253  3253 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
03-17 11:16:39.123  3253  3253 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
03-17 11:16:39.133  3253  3253 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
03-17 11:16:39.133  3253  3253 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,03-17 11:16:39.133  3253  3304 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,03-17 11:16:39.143  1177  1177 D OverheatReceiver: into the SAFE_MODE_ACTION
,03-17 11:16:39.143  1177  1177 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
03-17 11:16:39.143  3253  3253 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
03-17 11:16:39.143  1177  1177 D OverheatReceiver: isSafeMode = false
,03-17 11:16:39.143  3222  3222 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,03-17 11:16:39.153  1482  1482 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
,03-17 11:16:39.153  1019  1382 D SettingsProvider: name = internet_call_settings_visibility
03-17 11:16:39.153  1019  1382 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 11:16:39.153  1019  1382 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 11:16:39.153  1019  1382 D SettingsProvider: selectionArgs: false
03-17 11:16:39.153  1019  1382 D SettingsProvider: selectionArgs: 1001
03-17 11:16:39.153  1019  1382 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 11:16:39.153  1019  1382 D SettingsProvider: ret = -1
,03-17 11:16:39.153  1482  1482 D PhoneUtilsCommon: isSupportVoLTE is false.
,03-17 11:16:39.163  3253  3253 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,03-17 11:16:39.163   259  1100 I SurfaceFlinger: id=8 Removed Mauncher (5/8)
,03-17 11:16:39.163   259   451 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
,03-17 11:16:39.173  3253  3253 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,03-17 11:16:39.173  3253  3304 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,03-17 11:16:39.173  3253  3253 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,03-17 11:16:39.183  3253  3253 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,03-17 11:16:39.183  3253  3253 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,03-17 11:16:39.183  3253  3304 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,03-17 11:16:39.223  3222  3222 I com.dropbox.sync.android.a: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,03-17 11:16:39.233  3253  3253 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
,03-17 11:16:39.243  1019  1382 W ActivityManager: userId = 0, bbcId = -10000
,03-17 11:16:39.243  1019  1382 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 11:16:39.243  1019  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 11:16:39.243  1019  1615 I art     : Explicit concurrent mark sweep GC freed 16752(827KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/33MB, paused 54.403ms total 279.682ms
,03-17 11:16:39.243  1019  1044 W libprocessgroup: failed to open /acct/uid_10014/pid_1735/cgroup.procs: No such file or directory
,03-17 11:16:39.253  1460  1460 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,03-17 11:16:39.263  1019  1851 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:39.263  1019  1851 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 11:16:39.263  1019  1851 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 11:16:39.263  1019  3388 W ActivityManager: userId = 0, bbcId = -10000
,03-17 11:16:39.263  1019  3388 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 11:16:39.263  1019  3388 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 11:16:39.273  3253  3253 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-17 11:16:39.273  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:39.273  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:39.273  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:39.273  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:39.273  1019  1527 E Tethering: No numeric data
,03-17 11:16:39.283  1019  3388 E Tethering: No numeric data
,03-17 11:16:39.283  1019  1142 E Tethering: No numeric data
,03-17 11:16:39.283  3391  3391 E Zygote  : MountEmulatedStorage()
03-17 11:16:39.283  3391  3391 E Zygote  : v2
03-17 11:16:39.283  3391  3391 I libpersona: KNOX_SDCARD checking this for 10052
03-17 11:16:39.283  3391  3391 I libpersona: KNOX_SDCARD not a persona
,03-17 11:16:39.283  3391  3391 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 11:16:39.293  1019  1626 E Tethering: No numeric data
,03-17 11:16:39.293  3253  3253 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,03-17 11:16:39.293  3391  3391 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:39.293  3391  3391 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 11:16:39.293  1019  1527 E Tethering: No numeric data
03-17 11:16:39.293  1019  1032 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3391 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,03-17 11:16:39.303  1019  3388 E Tethering: No numeric data
,03-17 11:16:39.303  1019  1525 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:39.303  1019  1525 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:39.303  1019  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-17 11:16:39.303  1959  1959 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 11:16:39.313  1460  1460 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,03-17 11:16:39.323  3391  3391 D TimaKeyStoreProvider: TimaSignature is unavailable,
,03-17 11:16:39.323  3391  3391 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:39.323  1959  1959 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 11:16:39.323  3253  3304 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,03-17 11:16:39.353  3287  3377 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,03-17 11:16:39.353  1321  3252 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
,03-17 11:16:39.353  1321  3252 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
,03-17 11:16:39.363  3287  3287 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,03-17 11:16:39.383  1019  1403 E Tethering: No numeric data
,03-17 11:16:39.383  1019  1386 E Tethering: No numeric data
,03-17 11:16:39.383  1019  1851 E Tethering: No numeric data
,03-17 11:16:39.393  1019  1403 E Tethering: No numeric data
,03-17 11:16:39.403  3320  3336 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 11:16:39.403  3287  3287 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 11:16:39.403  3320  3336 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 11:16:39.403  3287  3287 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 11:16:39.403  3320  3336 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 11:16:39.413  3287  3287 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 11:16:39.413  3287  3287 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-17 11:16:39.413  3320  3331 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-17 11:16:39.413  3320  3331 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-17 11:16:39.413  3320  3331 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-17 11:16:39.423  3287  3287 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-17 11:16:39.433  3287  3287 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 11:16:39.433  3287  3287 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 11:16:39.463  1019  1615 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:39.463  1019  1615 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:39.463  1019  1615 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:39.463  1019  1615 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:39.463   285   717 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
,03-17 11:16:39.463   285   717 D audio_hw_extn: audio_extn_get_parameters: returns 
03-17 11:16:39.463   285   717 V msm8974_platform: platform_get_parameters: exit: returns - 
03-17 11:16:39.463   285   717 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-17 11:16:39.463   285   717 I str_params: key: 'call_forwarding' value: ''
03-17 11:16:39.463  1993  1993 V InCall  : ProximitySensor -  - screenonImmediately: false
03-17 11:16:39.463  1993  1993 V InCall  : ProximitySensor -  - mFromRcsShare: false
,03-17 11:16:39.473  1019  1142 V VibratorService: hasVibrator - useVibetonz: true
,03-17 11:16:39.483  1993  1993 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
03-17 11:16:39.483  3422  3422 I libpersona: KNOX_SDCARD checking this for 1000
03-17 11:16:39.483  3422  3422 E Zygote  : MountEmulatedStorage()
03-17 11:16:39.483  3422  3422 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:39.483  3422  3422 E Zygote  : v2
03-17 11:16:39.483  3422  3422 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 11:16:39.483  1993  1993 D ScoverManager: serviceVersion : 16908288
03-17 11:16:39.483  3253  3304 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
03-17 11:16:39.483  3422  3422 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 11:16:39.483  1019  3388 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 11:16:39.483  3422  3422 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 11:16:39.493  1019  1615 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3422 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 11:16:39.493  1019  1615 I ActivityManager: Killing 2554:com.sec.tcpdumpservice/1000 (adj 15): empty #31
03-17 11:16:39.493  1019  1615 I ActivityManager: Killing 2534:com.sec.modem.settings/1000 (adj 15): empty #32
03-17 11:16:39.493  1019  1615 I ActivityManager: Killing 2506:com.wsomacp/u0a23 (adj 15): empty #33
,03-17 11:16:39.503  1321  3252 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,03-17 11:16:39.503  1993  1993 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
03-17 11:16:39.503  1019  1382 V VibratorService: hasVibrator - useVibetonz: true
,03-17 11:16:39.503  1019  1525 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 11:16:39.503  1460  1460 I Telecom : ProximitySensorManager: Proximity wake lock already released
03-17 11:16:39.503  1993  1993 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
03-17 11:16:39.503  1993  1993 I InCall  : InCallPresenter -  - InCallState = NO_CALLS
,03-17 11:16:39.503  1019  1527 V VibratorService: hasVibrator - useVibetonz: true
,03-17 11:16:39.513  1993  1993 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
03-17 11:16:39.513  1993  1993 D InCall  : InCallPresenter -  - dismissCoverDialog()...
,03-17 11:16:39.523  3287  3431 D OpenGLRenderer: Render dirty regions requested: true
,03-17 11:16:39.523   321   321 I art     : Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 644us total 27.677ms
,03-17 11:16:39.523  1019  3389 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:39.523  1019  3389 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:39.523  1019  3389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 11:16:39.533  1019  1525 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 11:16:39.533  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 11:16:39.533  1019  1525 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 11:16:39.533  1019  1525 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 11:16:39.533  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-17 11:16:39.533  3287  3287 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 11:16:39.533  3287  3287 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-17 11:16:39.543  3422  3422 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 11:16:39.543   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 687us total 19.341ms
,03-17 11:16:39.543  3422  3422 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:39.543  1321  3252 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 11:16:39.543  3320  3320 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
03-17 11:16:39.543  3320  3345 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,03-17 11:16:39.553  3320  3345 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,03-17 11:16:39.553  3320  3320 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-17 11:16:39.553  3320  3320 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,03-17 11:16:39.553  3320  3320 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
03-17 11:16:39.563   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 626us total 18.945ms
03-17 11:16:39.563  3320  3320 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
03-17 11:16:39.563  3320  3320 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
03-17 11:16:39.563  3320  3320 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
03-17 11:16:39.563  3320  3320 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-17 11:16:39.563  3320  3320 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,03-17 11:16:39.563  3320  3320 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,03-17 11:16:39.573  3320  3320 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,03-17 11:16:39.573  3320  3345 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,03-17 11:16:39.603  3422  3422 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,03-17 11:16:39.613  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:39.613  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:39.613  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:39.613  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:39.633  3446  3446 E Zygote  : MountEmulatedStorage()
,03-17 11:16:39.633  3446  3446 E Zygote  : v2
03-17 11:16:39.633  3446  3446 I libpersona: KNOX_SDCARD checking this for 10014
03-17 11:16:39.633  3446  3446 I libpersona: KNOX_SDCARD not a persona
,03-17 11:16:39.633  3446  3446 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 11:16:39.633  1019  1141 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3446 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,03-17 11:16:39.643  3446  3446 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:39.643  3446  3446 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 11:16:39.643  1019  1044 W libprocessgroup: failed to open /acct/uid_10023/pid_2506/cgroup.procs: No such file or directory
03-17 11:16:39.643  1019  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2534/cgroup.procs: No such file or directory
,03-17 11:16:39.643  1019  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2554/cgroup.procs: No such file or directory
,03-17 11:16:39.663  3446  3446 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:39.663  3446  3446 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:39.683  1993  1993 I InCall  : CallSContextMotion - stopPutDownListening
,03-17 11:16:39.683  3222  3222 I com.dropbox.sync.android.ad: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A300FU armeabi-v7a; en_US))
03-17 11:16:39.683  1993  1993 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,03-17 11:16:39.693  1019  1359 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 11:16:39.693  1993  1993 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
,03-17 11:16:39.693  1177  1177 D PhoneStatusBarView: setCallBackground:0
,03-17 11:16:39.703  1019  1403 D LocationManagerService: getProviders()=[passive]
03-17 11:16:39.703  3253  3304 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-17 11:16:39.713  3253  3304 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,03-17 11:16:39.713  3253  3304 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,03-17 11:16:39.713  3422  3422 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
03-17 11:16:39.713  3422  3422 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-17 11:16:39.713  3422  3422 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-17 11:16:39.713  2748  2873 E AclDataUtils: Circle ID not found for type: 9
,03-17 11:16:39.723  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:39.723  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:39.723  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:39.723  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:39.743  3467  3467 E Zygote  : MountEmulatedStorage(),
03-17 11:16:39.743  3467  3467 I libpersona: KNOX_SDCARD checking this for 1000
03-17 11:16:39.743  3467  3467 E Zygote  : v2
03-17 11:16:39.743  3467  3467 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:39.743  3467  3467 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 11:16:39.743  1019  1032 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3467 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 11:16:39.743  3467  3467 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:39.743  3467  3467 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 11:16:39.763   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
,03-17 11:16:39.773  1019  1403 D InputDispatcher: Focus entered window: 3287
,03-17 11:16:39.773  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 11:16:39.773  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 11:16:39.773  3287  3287 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-17 11:16:39.773  3287  3431 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 11:16:39.783  3467  3467 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-17 11:16:39.783  3467  3467 D ActivityThread: Added TimaKeyStore provider
03-17 11:16:39.783  1993  1993 D VideoCallManager: Instantiating VideoCallManager
,03-17 11:16:39.783  3287  3431 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-17 11:16:39.783  3287  3431 D OpenGLRenderer: Enabling debug mode 0,
,03-17 11:16:39.793  1321  3252 D ScoverManager: serviceVersion : 16908288
,03-17 11:16:39.803  1019  1527 W ActivityManager: userId = 0, bbcId = -10000
,03-17 11:16:39.803  1019  1527 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:39.803  1019  1527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 11:16:39.813  1019  2785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-17 11:16:39.833  3467  3467 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,03-17 11:16:39.833  3467  3467 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-17 11:16:39.843  3467  3467 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-17 11:16:39.843  3391  3490 I ContactAccountLoggerTas: canRun() : Opted Out
,03-17 11:16:39.843  1019  3388 W ActivityManager: userId = 0, bbcId = -10000
,03-17 11:16:39.843  1019  3388 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:39.843  1019  3388 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-17 11:16:39.863  1019  1142 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 11:16:39.863  1993  1993 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 11:16:39.873  1177  1177 I StatusBar: Icon Only
,03-17 11:16:39.873  1177  1177 D PanelView: There is/are notification(s) 
,03-17 11:16:39.873  1019  1403 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:39.873  1019  1403 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:39.873  1019  1403 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:39.873  1019  1403 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:39.873  1993  1993 I GFX construct_block_size_descriptor_2d second part: took 2.600887ms for 0*0 texture 0
,03-17 11:16:39.883  1019  3494 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 11:16:39.883  1993  1993 I GFX generate_partition_tables: took 5.419743ms for 0*0 texture 0
,03-17 11:16:39.883  1993  1993 I GFX raster: took 11.815839ms for 176*144 texture 0
03-17 11:16:39.883  1993  1993 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7330358 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb732fc28 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 11:16:39.893  3287  3287 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@31be15b1 time:37943
,03-17 11:16:39.903  3495  3495 E Zygote  : MountEmulatedStorage()
03-17 11:16:39.903  3495  3495 I libpersona: KNOX_SDCARD checking this for 10090
03-17 11:16:39.903  3495  3495 E Zygote  : v2
03-17 11:16:39.903  3495  3495 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:39.903  3495  3495 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 11:16:39.903  3320  3345 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-17 11:16:39.903  3495  3495 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:39.903  3320  3345 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected,
,03-17 11:16:39.903  3495  3495 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 11:16:39.913  1019  1403 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3495 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,03-17 11:16:39.913  1993  1993 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,03-17 11:16:39.913  1993  1993 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 11:16:39.913  1993  1993 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 11:16:39.913  1993  1993 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 11:16:39.913  1993  1993 I Adreno-EGL: Local Branch: 
03-17 11:16:39.913  1993  1993 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 11:16:39.913  1993  1993 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 11:16:39.913  1993  1993 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 11:16:39.923  1019  1527 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:39.923  1019  1527 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:39.923  1019  1527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-17 11:16:39.923  1019  1050 I ActivityManager: Displayed Component not be shown by security: +1s322ms
,03-17 11:16:39.933  1019  1050 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 11:16:39.933  1019  1050 W ActivityManager: mDVFSHelper.release()
03-17 11:16:39.933  1019  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{134e2887 u0 com.test.thalitest/.MainActivity t11} time:37984
,03-17 11:16:39.933  1019  1045 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 11:16:39.943   331   331 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-17 11:16:39.953  1019  1626 I ActivityManager: Killing 2570:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
,03-17 11:16:39.953  1993  1993 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 11:16:39.963  3320  3345 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,03-17 11:16:39.973  3495  3495 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:39.973  3320  3345 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,03-17 11:16:39.973  3495  3495 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:39.973  1993  1993 I glCompressedTexImage2D: took 0.451146ms for 320*61440 texture 37809
,03-17 11:16:39.993  1993  1993 I draw setup: took 11.430156ms for 320*240 texture 37809
,03-17 11:16:39.993  1993  1993 E GFX GPU raster: drawn
,03-17 11:16:39.993  3467  3482 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 11:16:40.003  1993  1993 I GFX GPU raster ASTC: took 42.551874ms for 320*240 texture 12
03-17 11:16:40.003  1993  1993 I GFX raster: took 42.643280ms for 320*240 texture 0
03-17 11:16:40.003  1993  1993 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb73302d8 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb732fe40 counterpartCT=4 counterpartW=320 counterparth=240
,03-17 11:16:40.003  3320  3345 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,03-17 11:16:40.013  3391  3490 I Velvet.VelvetFactory: refreshing search history.
,03-17 11:16:40.013  3422  3422 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-17 11:16:40.023  3422  3422 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 11:16:40.023  1802  1802 I SamsungIME: getCurrentCandidateView
03-17 11:16:40.023  3422  3422 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 11:16:40.023  1019  1525 I ActivityManager: Killing 2587:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,03-17 11:16:40.033  1993  1993 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-17 11:16:40.033  1993  1993 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS,
,03-17 11:16:40.033  1993  1993 I glCompressedTexImage2D: took 0.440990ms for 480*122880 texture 37813
03-17 11:16:40.033  1019  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:40.033  1993  1993 I draw setup: took 0.994063ms for 480*640 texture 37813
03-17 11:16:40.033  1019  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:40.033  1993  1993 E GFX GPU raster: drawn
03-17 11:16:40.033  1019  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:40.033  1019  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:40.033  3180  3180 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-17 11:16:40.043  1993  1993 I GFX GPU raster ASTC: took 10.243229ms for 480*640 texture 12
03-17 11:16:40.043  1993  1993 I GFX raster: took 10.361979ms for 480*640 texture 0
03-17 11:16:40.043  1993  1993 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb732fe40 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb7571898 counterpartCT=4 counterpartW=480 counterparth=640
03-17 11:16:40.043  3320  3345 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,03-17 11:16:40.053  3518  3518 E Zygote  : MountEmulatedStorage(),
03-17 11:16:40.053  3518  3518 E Zygote  : v2
03-17 11:16:40.053  3518  3518 I libpersona: KNOX_SDCARD checking this for 1000
,03-17 11:16:40.053  3518  3518 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 11:16:40.053  3518  3518 I libpersona: KNOX_SDCARD not a persona
,03-17 11:16:40.053  3518  3518 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:40.053  3518  3518 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 11:16:40.053  1019  1382 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3518 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 11:16:40.063  1019  1382 I ActivityManager: Killing 2521:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-17 11:16:40.063  3320  3345 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-17 11:16:40.083  3518  3518 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:40.083  3518  3518 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:40.093  1993  1993 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,03-17 11:16:40.093  1993  1993 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS,
03-17 11:16:40.093  1993  1993 I glCompressedTexImage2D: took 0.411719ms for 440*116864 texture 37809
03-17 11:16:40.093  1993  1993 I draw setup: took 0.964062ms for 440*330 texture 37809
,03-17 11:16:40.103  1993  1993 E GFX GPU raster: drawn
,03-17 11:16:40.103  1993  1993 I GFX GPU raster ASTC: took 5.281717ms for 440*330 texture 12
03-17 11:16:40.103  1993  1993 I GFX raster: took 5.361093ms for 440*330 texture 0
03-17 11:16:40.103  1993  1993 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7571878 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb7571c48 counterpartCT=4 counterpartW=440 counterparth=330
,03-17 11:16:40.133  3320  3345 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-17 11:16:40.143  3320  3346 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-17 11:16:40.143  3320  3345 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,03-17 11:16:40.143  3320  3346 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 11:16:40.143   259  1101 I SurfaceFlinger: id=11 Removed uhalitest (7/8)
03-17 11:16:40.143   259   454 I SurfaceFlinger: id=11 Removed uhalitest (-2/8)
,03-17 11:16:40.143  3320  3345 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,03-17 11:16:40.153  3320  3345 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/20/16:34:31
,03-17 11:16:40.163  3320  3345 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/17/11:16:40
,03-17 11:16:40.163  3320  3346 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
03-17 11:16:40.163  3320  3345 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,03-17 11:16:40.163  3320  3345 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,03-17 11:16:40.163  3320  3346 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-17 11:16:40.163  3320  3346 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-17 11:16:40.173  3320  3346 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-17 11:16:40.173  3320  3346 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-17 11:16:40.173  3320  3346 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,03-17 11:16:40.173  3320  3346 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,03-17 11:16:40.173  3320  3346 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-17 11:16:40.193  3518  3518 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-17 11:16:40.193  1321  3252 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 11:16:40.203  3518  3518 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-17 11:16:40.203  1019  2834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 11:16:40.203  1993  1993 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-17 11:16:40.213  1993  1993 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 11:16:40.213  1993  1993 I glCompressedTexImage2D: took 0.446927ms for 480*163840 texture 37811
03-17 11:16:40.213  1993  1993 I draw setup: took 0.828177ms for 480*640 texture 37811
03-17 11:16:40.213  1993  1993 E GFX GPU raster: drawn
,03-17 11:16:40.223  1993  1993 I GFX GPU raster ASTC: took 8.770260ms for 480*640 texture 12
03-17 11:16:40.223  1993  1993 I GFX raster: took 8.877655ms for 480*640 texture 0
03-17 11:16:40.223  1993  1993 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb75716b8 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb75846e0 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 11:16:40.223  1802  1802 D SamsungIME: Dismiss ExpandCandiate
,03-17 11:16:40.223  3320  3345 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,03-17 11:16:40.233  1019  3389 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 11:16:40.233  1019  1044 W libprocessgroup: failed to open /acct/uid_10127/pid_2570/cgroup.procs: No such file or directory
03-17 11:16:40.233  1019  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2587/cgroup.procs: No such file or directory
,03-17 11:16:40.233  1019  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2521/cgroup.procs: No such file or directory
,03-17 11:16:40.233  1019  1019 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 11:16:40.233  1321  3252 D Settings_Utils: isSupportVNFestival SM-A300FU XEO
,03-17 11:16:40.233  3495  3495 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-17 11:16:40.243  3495  3495 D elm:15121: ELMEngine.ELMEngine( context ).
,03-17 11:16:40.243  3495  3495 D elm:15121: MDMBridge.setEnterpriseBridge()
,03-17 11:16:40.253  1019  1142 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:40.253  1019  1142 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 11:16:40.253  1019  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-17 11:16:40.253  3287  3287 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-17 11:16:40.253  3467  3482 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 11:16:40.253  3495  3495 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-17 11:16:40.263  3518  3518 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-17 11:16:40.263  3518  3518 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-17 11:16:40.273  1019  1403 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
03-17 11:16:40.273  3495  3495 D elm:15121: ElmAgentService : onCreate()
,03-17 11:16:40.273  1993  1993 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
03-17 11:16:40.273  3495  3542 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,03-17 11:16:40.273  3495  3495 D elm:15121: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
03-17 11:16:40.273  3495  3495 D elm:15121: BootCompletedState : startBootCompleted() call
,03-17 11:16:40.273  1993  1993 I GFX construct_block_size_descriptor_2d second part: took 2.145885ms for 0*0 texture 0
,03-17 11:16:40.273  1019  1525 I AudioService: getStreamVolume 3 index 0
,03-17 11:16:40.273  3222  3492 I System.out: Thread-414(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 11:16:40.273  3495  3495 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 11:16:40.283  3222  3492 I System.out: Thread-414(ApacheHTTPLog):isSBSettingEnabled false
03-17 11:16:40.283  3222  3492 I System.out: Thread-414(ApacheHTTPLog):isShipBuild true
03-17 11:16:40.283  3222  3492 I System.out: Thread-414(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 11:16:40.283  3222  3492 I System.out: Thread-414(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 11:16:40.283  1993  1993 I GFX generate_partition_tables: took 7.540988ms for 0*0 texture 0
,03-17 11:16:40.293  1993  1993 I GFX raster: took 11.738227ms for 176*144 texture 0
03-17 11:16:40.293  1993  1993 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb75617c8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb7584700 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 11:16:40.293  1802  1802 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 11:16:40.303   280   989 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 11:16:40.303   280   989 D Netd    : getNetworkForDns: using netid 502 for uid 10088
,03-17 11:16:40.303  1448  1448 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,03-17 11:16:40.323  3320  3346 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-17 11:16:40.333  1993  1993 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 11:16:40.333  1993  1993 I GFX construct_block_size_descriptor_2d second part: took 2.502917ms for 0*0 texture 0
,03-17 11:16:40.333  1019  1527 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:40.333  1019  1527 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:40.333  1019  1527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 11:16:40.333  3495  3495 I elm:15121: Get License : 0
,03-17 11:16:40.333  3495  3495 D elm:15121: ElmAgentService : onDestroy().
,03-17 11:16:40.343  3391  3489 W GAV2    : Thread[Background Non-Blocking-0,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-17 11:16:40.343  1993  1993 I GFX generate_partition_tables: took 6.327811ms for 0*0 texture 0
,03-17 11:16:40.343  1993  1993 I GFX raster: took 10.957186ms for 176*144 texture 0
03-17 11:16:40.343  1993  1993 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7571d28 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb75863f0 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 11:16:40.343  1321  3252 W ResourceType: Failure getting entry for 0x7f0202b4 (t=1 e=692) (error -75)
,03-17 11:16:40.343   258   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 11:16:40.343   258   518 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 11:16:40.343  1993  1993 D ScoverManager: registerListener
,03-17 11:16:40.353  1019  1626 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 11:16:40.353  1019  1141 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 11:16:40.353  1019  1141 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@4cdb22, pid : 1993, uid : 1001, type : 1
,03-17 11:16:40.363  3180  3180 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 11:16:40.363  3320  3346 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,03-17 11:16:40.363  1993  1993 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-17 11:16:40.363  1321  3252 W ResourceType: Failure getting entry for 0x7f020510 (t=1 e=1296) (error -75)
,03-17 11:16:40.373   258   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 11:16:40.373   258   518 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 11:16:40.373  3180  3180 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-17 11:16:40.373   258   518 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 11:16:40.373   258   518 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 11:16:40.373  3180  3180 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-17 11:16:40.383  3320  3345 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,03-17 11:16:40.383  1019  1142 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:40.383  1019  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:40.383  1019  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 11:16:40.393  3391  3489 W GAV2    : Thread[Background Non-Blocking-0,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,03-17 11:16:40.393  3391  3515 I ContactAccountLoggerTas: canRun() : Opted Out
,03-17 11:16:40.393  3320  3345 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-17 11:16:40.403  1448  1448 V EmergencyMode: [EmergencyBase] setBootTime,
03-17 11:16:40.403  1448  1448 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.,
,03-17 11:16:40.403  1019  1403 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:40.403  1019  1403 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:40.403  1019  1403 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:40.403  1019  1403 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:40.423  3561  3561 E Zygote  : MountEmulatedStorage()
03-17 11:16:40.423  3561  3561 I libpersona: KNOX_SDCARD checking this for 1000
03-17 11:16:40.423  3561  3561 E Zygote  : v2
03-17 11:16:40.423  3561  3561 I libpersona: KNOX_SDCARD not a persona
,03-17 11:16:40.423  3561  3561 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 11:16:40.423  3561  3561 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:40.423  1019  1403 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3561 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 11:16:40.433  3561  3561 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 11:16:40.453  3561  3561 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:40.463  3561  3561 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:40.473  1802  1802 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 11:16:40.483  3518  3518 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,03-17 11:16:40.493  1802  1802 I SamsungIME: KeybaordView init() : load resources
,03-17 11:16:40.503  1019  1851 W ActivityManager: userId = 0, bbcId = -10000
,03-17 11:16:40.503  1019  1851 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:40.503  1019  1851 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 11:16:40.513  3287  3513 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
03-17 11:16:40.513  3287  3513 I chromium: 
,03-17 11:16:40.533  1019  1382 W ActivityManager: userId = 0, bbcId = -10000
,03-17 11:16:40.533  1019  1382 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:40.533  1019  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-17 11:16:40.533  3518  3518 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-17 11:16:40.533  3518  3518 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-17 11:16:40.533  3518  3518 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-17 11:16:40.543  3518  3518 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-17 11:16:40.543  1019  1142 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 11:16:40.543  3518  3518 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,03-17 11:16:40.543  3518  3518 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,03-17 11:16:40.553  2748  2851 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-17 11:16:40.563  3561  3561 I CameraApp: CameraApp.onCreate()... mFeature : null
,03-17 11:16:40.563  3561  3561 I testFeature: Feature.Feature(context)
,03-17 11:16:40.563  3561  3561 I testFeature: Feature.readInternalDefaultXml()
03-17 11:16:40.563  3561  3561 I testFeature: ResetFeatureValue
,03-17 11:16:40.573  3561  3561 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
,03-17 11:16:40.573  3561  3561 I CameraApp: CameraApp.getAppFeature()...
,03-17 11:16:40.573  1019  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:40.573  1019  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:40.573  1019  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:40.573  1019  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:40.583  3599  3599 E Zygote  : MountEmulatedStorage(),
03-17 11:16:40.583  3599  3599 E Zygote  : v2
03-17 11:16:40.593  3599  3599 I libpersona: KNOX_SDCARD checking this for 10095
,03-17 11:16:40.593  3599  3599 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:40.593  3599  3599 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 11:16:40.593  1019  1527 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for broadcast com.samsung.android.provider.filterprovider/.FilterProviderReceiver: pid=3599 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
03-17 11:16:40.593  3599  3599 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 11:16:40.593  1019  1527 I ActivityManager: Killing 1681:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
03-17 11:16:40.593  3599  3599 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 11:16:40.593  1019  1525 I ActivityManager: Killing 2617:com.android.calendar/u0a131 (adj 15): empty #31
,03-17 11:16:40.613  3320  3346 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
03-17 11:16:40.633  3347  3347 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 11:16:40.633  3347  3347 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-17 11:16:40.643  3347  3347 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-17 11:16:40.643  3599  3599 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:40.643  3599  3599 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:40.663  3320  3346 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 11:16:40.673  1019  1527 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
03-17 11:16:40.673  3347  3347 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-17 11:16:40.683  1802  1802 I SamsungIME: getCurrentKeyboard
,03-17 11:16:40.683  1802  1802 I SamsungIME: getTextKeyboard
,03-17 11:16:40.683  1019  3388 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:40.683  1019  3388 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:40.683  1019  3388 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:40.683  1019  3388 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:40.693  3320  3346 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false,
,03-17 11:16:40.723  3623  3623 E Zygote  : MountEmulatedStorage(),
03-17 11:16:40.723  3623  3623 E Zygote  : v2
03-17 11:16:40.723  3623  3623 I libpersona: KNOX_SDCARD checking this for 10013
03-17 11:16:40.723  3623  3623 I libpersona: KNOX_SDCARD not a persona
,03-17 11:16:40.723  3623  3623 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-17 11:16:40.723  1019  3388 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3623 uid=10013 gids={50013, 9997} abi=armeabi-v7a
,03-17 11:16:40.733  3623  3623 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:40.733  3623  3623 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 11:16:40.733  1019  1386 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:40.733  1019  1386 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:40.733  1019  1386 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 11:16:40.743  1019  1142 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:40.743  1019  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:40.743  1019  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 11:16:40.753  1019  1525 W ActivityManager: userId = 0, bbcId = -10000
,03-17 11:16:40.753  1019  1525 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:40.753  1019  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 11:16:40.763  1019  1382 I ActivityManager: Killing 2673:com.android.keychain/1000 (adj 15): empty #31
,03-17 11:16:40.773  3253  3304 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-17 11:16:40.803  3180  3597 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
,03-17 11:16:40.803  3180  3597 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,03-17 11:16:40.803  1802  1802 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 11:16:40.803  1019  1403 V VibratorService: hasVibrator - useVibetonz: true
,03-17 11:16:40.803  3180  3597 I System.out: Thread-448(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 11:16:40.813  3180  3597 I System.out: Thread-448(ApacheHTTPLog):isSBSettingEnabled false
,03-17 11:16:40.813  3180  3597 I System.out: Thread-448(ApacheHTTPLog):isShipBuild true
03-17 11:16:40.813  3180  3597 I System.out: Thread-448(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 11:16:40.813  3180  3597 I System.out: Thread-448(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 11:16:40.813  1019  1142 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 11:16:40.813   280   989 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 11:16:40.813   280   989 D Netd    : getNetworkForDns: using netid 502 for uid 10161
,03-17 11:16:40.823  1019  1032 I AudioService: getStreamVolume 3 index 0
,03-17 11:16:40.823  3623  3623 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:40.823  3623  3623 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:40.823  3287  3618 D jxcore_app_log: JniHelper::setJavaVM(0xb6f84448), pthread_self() = -1218496952
,03-17 11:16:40.833  3391  3391 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,03-17 11:16:40.833  3599  3599 D PreloadFilterInstaller: uses FILTER_DB_VER_1
,03-17 11:16:40.833  3287  3618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 11:16:40.833  3287  3618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 11:16:40.833  3287  3618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 11:16:40.833  3287  3618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 11:16:40.833  3287  3618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-17 11:16:40.833  3287  3618 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23bc6c34 added. We now have 1 listener(s)
,03-17 11:16:40.843  1019  3388 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:40.843  1019  3388 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:40.843  1019  3388 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 11:16:40.843  1019  1615 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:40.843  1019  1615 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:40.843  1019  1615 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-17 11:16:40.853  3599  3599 E SQLiteLog: (284) automatic index on titles(filter_id)
,03-17 11:16:40.853  1019  1382 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:40.853  1019  1382 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:40.853  1019  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 11:16:40.863  1019  1044 W libprocessgroup: failed to open /acct/uid_10131/pid_2617/cgroup.procs: No such file or directory
03-17 11:16:40.863  1019  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_1681/cgroup.procs: No such file or directory
,03-17 11:16:40.863  3287  3618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,03-17 11:16:40.863  3287  3618 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
,03-17 11:16:40.863  3287  3618 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
03-17 11:16:40.863  3287  3618 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-17 11:16:40.863  3287  3618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 11:16:40.873  3287  3618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 11:16:40.873  3287  3618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 11:16:40.873  3287  3618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 11:16:40.873  3287  3618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
03-17 11:16:40.873  3287  3618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 11:16:40.873  3287  3618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 11:16:40.873  3287  3618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 11:16:40.873  3287  3618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 11:16:40.873  3287  3618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 11:16:40.873  3287  3618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-17 11:16:40.873  3287  3618 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2016d8a3 added. We now have 1 listener(s)
03-17 11:16:40.873  3287  3618 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
03-17 11:16:40.873  1019  1032 I ActivityManager: Killing 2786:com.android.email/u0a141 (adj 15): empty #31
,03-17 11:16:40.873  1019  1032 I ActivityManager: Killing 2714:com.android.chrome/u0a77 (adj 15): empty #32
,03-17 11:16:40.883  1019  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2673/cgroup.procs: No such file or directory
,03-17 11:16:40.883  3287  3618 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-17 11:16:40.883  3287  3618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-17 11:16:40.883  3287  3618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,03-17 11:16:40.893  3287  3618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,03-17 11:16:40.893  3287  3618 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-17 11:16:40.893  3599  3599 I FilterProviderReceiver: onReceive in FilterProviderReceiver
03-17 11:16:40.893  3599  3599 I FilterProviderReceiver: onReceive in FilterProviderReceiver when ACTION_BOOT_COMPLETED
,03-17 11:16:40.893  1019  3388 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:40.893  1019  3388 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:40.893  1019  3388 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:40.893  1019  3388 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:40.893  3391  3391 I FavoriteContactNamesSup: get() : Execute runnable (UI thread)
03-17 11:16:40.893  3391  3391 I ContactLabelSupplier: get() : Execute runnable (UI thread)
,03-17 11:16:40.903  1976  1976 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,03-17 11:16:40.913  3646  3646 E Zygote  : MountEmulatedStorage(),
03-17 11:16:40.913  3646  3646 E Zygote  : v2
03-17 11:16:40.913  3646  3646 I libpersona: KNOX_SDCARD checking this for 10098
03-17 11:16:40.913  3646  3646 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 11:16:40.913  3646  3646 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:40.913  1019  3388 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3646 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
03-17 11:16:40.913  1019  3388 I ActivityManager: Killing 2412:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,03-17 11:16:40.913  3646  3646 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:40.913  3646  3646 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 11:16:40.923  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:40.923  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 11:16:40.923  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,03-17 11:16:40.923  1976  3655 D SecUISvc: Thread created.
03-17 11:16:40.923  1019  1386 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:40.923  1019  1386 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:40.923  1019  1386 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:40.923  1019  1386 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:40.933  3646  3646 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:40.933  3623  3623 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
,03-17 11:16:40.933  3646  3646 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:40.933  1976  1976 D SecUISvc: Service started flags 0 startId 1
,03-17 11:16:40.943  3661  3661 E Zygote  : MountEmulatedStorage()
,03-17 11:16:40.943  3661  3661 E Zygote  : v2
03-17 11:16:40.943  3661  3661 I libpersona: KNOX_SDCARD checking this for 10026
03-17 11:16:40.943  3661  3661 I libpersona: KNOX_SDCARD not a persona
,03-17 11:16:40.943  3661  3661 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 11:16:40.953  3661  3661 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 11:16:40.953  1019  1386 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3661 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 11:16:40.953  3661  3661 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 11:16:40.953  3287  3618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-17 11:16:40.963  3287  3618 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,03-17 11:16:40.963  1019  1142 W ActivityManager: userId = 0, bbcId = -10000,
03-17 11:16:40.963  1019  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:40.963  1019  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,03-17 11:16:40.983  3661  3661 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:40.983  3661  3661 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:40.983  3623  3674 V OneTimeService: OneTimeService.onHandleIntent
,03-17 11:16:40.993  3287  3618 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 11:16:40.993  3287  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 11:16:40.993  3287  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 11:16:40.993  3287  3618 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 11:16:40.993  3287  3618 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 11:16:40.993  3287  3618 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 11:16:40.993  3287  3618 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 11:16:40.993  3287  3618 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-17 11:16:40.993  3287  3618 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 11:16:40.993  3287  3618 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 11:16:40.993  1019  1359 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:40.993  1019  1359 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:40.993  1019  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 11:16:41.003  3287  3287 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 11:16:41.003  2636  3203 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3203)  
,03-17 11:16:41.003  3391  3489 I ContactLabelSupplier: get() : OptedIn = false
,03-17 11:16:41.013  1019  1141 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:41.013  1019  1141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:41.013  1019  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
03-17 11:16:41.013  3287  3287 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 11:16:41.013  1019  1615 I ActivityManager: Killing 1410:com.android.defcontainer/u0a3 (adj 15): empty #31
03-17 11:16:41.013  1019  1615 I ActivityManager: Killing 2879:com.mobeam.barcodeService/1000 (adj 15): empty #31
,03-17 11:16:41.013  1019  3389 W ActivityManager: userId = 0, bbcId = -10000
,03-17 11:16:41.013  1019  3389 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:41.013  1019  3389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 11:16:41.023  3646  3646 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
,03-17 11:16:41.023  1019  1359 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:41.023  1019  1359 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:41.023  1019  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 11:16:41.043  1019  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:41.043  1019  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:41.043  1019  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:41.043  1019  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:41.053  3684  3684 E Zygote  : MountEmulatedStorage()
03-17 11:16:41.053  3684  3684 E Zygote  : v2
03-17 11:16:41.053  3684  3684 I libpersona: KNOX_SDCARD checking this for 10055
03-17 11:16:41.053  3684  3684 I libpersona: KNOX_SDCARD not a persona
,03-17 11:16:41.053  3684  3684 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 11:16:41.063  3646  3646 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,03-17 11:16:41.063  3684  3684 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 11:16:41.063  1019  1382 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3684 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,03-17 11:16:41.063  3684  3684 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 11:16:41.073  1019  1527 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 11:16:41.073  1019  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:41.073  1019  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:41.073  1019  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:41.073  1019  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:41.093  3695  3695 E Zygote  : MountEmulatedStorage()
03-17 11:16:41.093  3695  3695 I libpersona: KNOX_SDCARD checking this for 10099
03-17 11:16:41.093  3695  3695 E Zygote  : v2
03-17 11:16:41.093  3695  3695 I libpersona: KNOX_SDCARD not a persona
,03-17 11:16:41.093  3695  3695 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 11:16:41.093  3695  3695 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 11:16:41.093  3695  3695 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 11:16:41.103  1019  1382 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3695 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 11:16:41.123  1019  1359 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:41.123  1019  1359 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:41.123  1019  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 11:16:41.133  3684  3684 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 11:16:41.133  1019  1044 W libprocessgroup: failed to open /acct/uid_10077/pid_2714/cgroup.procs: No such file or directory
,03-17 11:16:41.133  3684  3684 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:41.153   321   321 I art     : Explicit concurrent mark sweep GC freed 8688(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 658us total 37.620ms,
,03-17 11:16:41.173   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 19.085ms
,03-17 11:16:41.173  1019  1626 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:41.173  1019  1626 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 11:16:41.173  1019  1626 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 11:16:41.173  3695  3695 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:41.173  3695  3695 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:41.183   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 817us total 19.062ms
,03-17 11:16:41.203  1629  1629 I Hs20UtilService: Starting #7
,03-17 11:16:41.203  1629  1667 I Hs20UtilService: Message received 5003
,03-17 11:16:41.213  3287  3287 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-17 11:16:41.223  1019  1403 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-17 11:16:41.223  1019  1403 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:41.223  1019  1403 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:41.223  1019  1044 W libprocessgroup: failed to open /acct/uid_10039/pid_2412/cgroup.procs: No such file or directory
03-17 11:16:41.233  1019  1403 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:41.233  1019  1044 W libprocessgroup: failed to open /acct/uid_10141/pid_2786/cgroup.procs: No such file or directory
,03-17 11:16:41.243  1019  1044 W libprocessgroup: failed to open /acct/uid_10003/pid_1410/cgroup.procs: No such file or directory
,03-17 11:16:41.243  3391  3490 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,03-17 11:16:41.253  3718  3718 E Zygote  : MountEmulatedStorage()
03-17 11:16:41.253  3718  3718 E Zygote  : v2
03-17 11:16:41.253  3718  3718 I libpersona: KNOX_SDCARD checking this for 10018
03-17 11:16:41.253  3718  3718 I libpersona: KNOX_SDCARD not a persona,
03-17 11:16:41.253  1019  1403 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3718 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
03-17 11:16:41.253  3718  3718 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 11:16:41.263  3718  3718 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:41.263  3718  3718 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 11:16:41.273  1019  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2879/cgroup.procs: No such file or directory
,03-17 11:16:41.323  3718  3718 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:41.323  3718  3718 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:41.323  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-17 11:16:41.323  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:41.323  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 11:16:41.343  3446  3446 I RlzPingService: Setting next ping for 1458814601359
,03-17 11:16:41.353  3684  3684 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-17 11:16:41.383  3287  3302 I art     : Background partial concurrent mark sweep GC freed 8116(564KB) AllocSpace objects, 5(166KB) LOS objects, 39% free, 7MB/12MB, paused 53.300ms total 102.282ms
,03-17 11:16:41.403  1019  1615 I ActivityManager: Killing 2896:flipboard.boxer.app/u0a97 (adj 15): empty #31
,03-17 11:16:41.433  3391  3490 I LibraryLoader: Loading: webviewchromium
,03-17 11:16:41.443  3718  3718 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 11:16:41 GMT+01:00 2016
,03-17 11:16:41.443  1321  3252 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
03-17 11:16:41.443  3391  3490 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 9486-9494)
03-17 11:16:41.443  3391  3490 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 11:16:41.473  1019  1044 W libprocessgroup: failed to open /acct/uid_10097/pid_2896/cgroup.procs: No such file or directory
,03-17 11:16:41.513  3180  3597 I System.out: Thread-448 calls detatch()
,03-17 11:16:41.523  3684  3684 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-17 11:16:41.523  3684  3684 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-17 11:16:41.523  3684  3684 D UserAnalysis: Create SecureDbHelper
,03-17 11:16:41.523  3391  3490 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 11:16:41.543  1019  1386 I art     : Explicit concurrent mark sweep GC freed 24154(1340KB) AllocSpace objects, 3(54KB) LOS objects, 33% free, 22MB/33MB, paused 2.489ms total 152.198ms,
,03-17 11:16:41.553  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:41.553  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 11:16:41.553  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 11:16:41.563  3684  3684 D IntelligenceServiceApplication: onCreate()
,03-17 11:16:41.563  3684  3684 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,03-17 11:16:41.563  3718  3718 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-17 11:16:41.563  1019  1386 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:41.563  1019  1386 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:41.563  1019  1386 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:41.563  1019  1386 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:41.573  3718  3718 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-17 11:16:41.573  3739  3739 E Zygote  : MountEmulatedStorage()
03-17 11:16:41.573  3739  3739 E Zygote  : v2,
03-17 11:16:41.573  3739  3739 I libpersona: KNOX_SDCARD checking this for 10056
03-17 11:16:41.573  3739  3739 I libpersona: KNOX_SDCARD not a persona
,03-17 11:16:41.583  3739  3739 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 11:16:41.583  3684  3684 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-17 11:16:41.583  3739  3739 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:41.583  3739  3739 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 11:16:41.583  1019  1386 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3739 uid=10056 gids={50056, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 11:16:41.583  3718  3718 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 11:16:41.583  3718  3718 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-17 11:16:41.593  1019  1386 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:41.593  1019  1386 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:41.593  1019  1386 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:41.593  1019  1386 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:41.593  3718  3738 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-17 11:16:41.603  3718  3738 I KLMS-2.5.123: : KLMSIntentService(): BOOT_COMPLETED
03-17 11:16:41.603  3751  3751 I libpersona: KNOX_SDCARD checking this for 10020
03-17 11:16:41.603  3751  3751 E Zygote  : MountEmulatedStorage()
03-17 11:16:41.603  3751  3751 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:41.603  3751  3751 E Zygote  : v2
03-17 11:16:41.603  1019  1386 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3751 uid=10020 gids={50020, 9997, 1028, 3003} abi=armeabi-v7a
03-17 11:16:41.603  3751  3751 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 11:16:41.603  3739  3739 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:41.603  3739  3739 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:41.613  3751  3751 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:41.613  3751  3751 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 11:16:41.623  3684  3684 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-17 11:16:41.633  3751  3751 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:41.643  3751  3751 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:41.693  3684  3684 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-17 11:16:41.693  3684  3684 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
,03-17 11:16:41.713  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:41.713  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:41.713  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:41.713  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:41.723  3779  3779 E Zygote  : MountEmulatedStorage()
03-17 11:16:41.723  3779  3779 E Zygote  : v2
03-17 11:16:41.723  3779  3779 I libpersona: KNOX_SDCARD checking this for 1000
03-17 11:16:41.723  3779  3779 I libpersona: KNOX_SDCARD not a persona
,03-17 11:16:41.723  3779  3779 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 11:16:41.723  1019  1141 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3779 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 11:16:41.733  3779  3779 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:41.733  3779  3779 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 11:16:41.733  1019  1141 I ActivityManager: Killing 2932:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,03-17 11:16:41.753  2656  2742 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-17 11:16:41.773  3253  3304 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,03-17 11:16:41.783  3779  3779 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:41.783  3779  3779 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:41.803  1019  1044 W libprocessgroup: failed to open /acct/uid_1101/pid_2932/cgroup.procs: No such file or directory
,03-17 11:16:41.813  3661  3661 I Finsky  : [1] com.google.android.finsky.FinskyApp.onCreate(358): Initializing network with DFE https://android.clients.google.com/fdfe/
,03-17 11:16:41.833  3718  3718 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-17 11:16:41.883  3779  3779 E MTPRx   : In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,03-17 11:16:41.883  1019  1626 D SecContentProvider2: uri = 14 selection = getSealedState
03-17 11:16:41.883  1019  1626 D SecContentProvider2: mCursor = null
,03-17 11:16:41.893  1019  1386 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-17 11:16:41.893  1019  1386 D SecContentProvider2: mCursor = null
,03-17 11:16:41.903  3779  3779 V MTPRx   : sealedState: false
,03-17 11:16:41.903  3779  3779 V MTPRx   : sealedUsbMassStorageState: false
,03-17 11:16:41.903  1019  1359 D SettingsProvider: name = mtp_usb_connection_status
,03-17 11:16:41.913  1019  1141 D SettingsProvider: name = media_player_mode
,03-17 11:16:41.923   295   295 E SMD     : DCD OFF
,03-17 11:16:41.923  1177  1177 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 11:16:41.933  3222  3492 I System.out: pool-10-thread-1 calls detatch(),
,03-17 11:16:41.943  1019  1382 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 11:16:41.943  1177  1177 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 11:16:41.963   280   989 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-17 11:16:41.963   280   989 D Netd    : getNetworkForDns: using netid 502 for uid 10052
,03-17 11:16:41.983  1019  1031 D SettingsProvider: name = mtp_running_status
,03-17 11:16:41.993  1321  3252 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,03-17 11:16:41.993  1321  3252 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,03-17 11:16:41.993  1019  1386 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 11:16:42.003  1019  1142 D SettingsProvider: name = media_mount_count
,03-17 11:16:42.003  1321  3252 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
,03-17 11:16:42.003  1177  1177 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 11:16:42.013  1019  1403 I ActivityManager: Killing 2971:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
,03-17 11:16:42.023  1177  1177 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 11:16:42.023  3739  3739 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.7.KK_APP
,03-17 11:16:42.023  1019  1141 D SettingsProvider: name = mtp_sync_alive
,03-17 11:16:42.033  1177  1177 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 11:16:42.033  1019  1851 D SettingsProvider: name = sdcard_launch
,03-17 11:16:42.043  1019  1382 D SettingsProvider: name = boot_time_connected
,03-17 11:16:42.043  1177  1177 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 11:16:42.053  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:42.053  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:42.053  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:42.053  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:42.063  1019  3389 D SettingsProvider: name = mtp_open_session,
,03-17 11:16:42.063  3391  3490 I qtaguid : Tagging socket 39 with tag 100000000{1,0} for uid -1, pid: 3391, getuid(): 10052
,03-17 11:16:42.073  3810  3810 E Zygote  : MountEmulatedStorage()
03-17 11:16:42.073  3810  3810 I libpersona: KNOX_SDCARD checking this for 10058
03-17 11:16:42.073  3810  3810 E Zygote  : v2
03-17 11:16:42.073  3810  3810 I libpersona: KNOX_SDCARD not a persona
,03-17 11:16:42.073  1177  1177 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 11:16:42.073  3810  3810 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 11:16:42.073  1019  1141 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3810 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 11:16:42.073  3810  3810 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:42.083  3810  3810 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 11:16:42.083  1019  1386 I ActivityManager: Killing 2297:flipboard.app/u0a96 (adj 15): empty #31
,03-17 11:16:42.093  1177  1177 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 11:16:42.103  3810  3810 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 11:16:42.103  3810  3810 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:42.113  3467  3467 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-17 11:16:42.113  3467  3467 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 11:16:42.113  3467  3467 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,03-17 11:16:42.113  3467  3467 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.BOOT_COMPLETED
03-17 11:16:42.113  3467  3467 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Version: 4.82
03-17 11:16:42.113  3467  3467 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Push type: [SPP, GCM]
03-17 11:16:42.113  3287  3680 W jxcore-log: Initializing JXcore engine
03-17 11:16:42.113  3287  3680 W jxcore-log: JXcore engine is ready
,03-17 11:16:42.133  3467  3467 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,03-17 11:16:42.143  3661  3661 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.a(122): No need to run daily hygiene.
,03-17 11:16:42.163  3467  3467 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-17 11:16:42.163  3661  3661 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 11:16:42.163  3661  3661 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 11:16:42.173  1019  1032 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 11:16:42.183  1019  1615 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-17 11:16:42.193  3467  3467 I ReactiveServiceManager: Supported : 1
,03-17 11:16:42.203  1019  1142 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:42.203  1019  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:42.203  1019  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 11:16:42.203  3695  3839 I Gmail   : Observing account changes for notifications
,03-17 11:16:42.213  1959  1959 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 11:16:42.213  1959  1959 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 11:16:42.223  1019  1044 W libprocessgroup: failed to open /acct/uid_10153/pid_2971/cgroup.procs: No such file or directory
03-17 11:16:42.223  1019  1044 W libprocessgroup: failed to open /acct/uid_10096/pid_2297/cgroup.procs: No such file or directory
,03-17 11:16:42.233  3695  3842 I Gmail   : getAccountsCursor
,03-17 11:16:42.243  1950  1950 E audit   : type=1400 msg=audit(1458209802.243:205): avc:  denied  { ioctl } for  pid=3680 comm="Thread-442" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-17 11:16:42.243  1950  1950 E audit   :  SEPF_SM-A300FU_5.0.2_0027
03-17 11:16:42.243  1950  1950 E audit   : type=1300 msg=audit(1458209802.243:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=4 a3=931d08f8 items=0 ppid=321 ppcomm=main pid=3680 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-442" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-17 11:16:42.243  1950  1950 E audit   : type=1320 msg=audit(1458209802.243:205): 
,03-17 11:16:42.243  1959  1959 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 11:16:42.253  3287  3680 W jxcore-log: Starting JXcore engine
,03-17 11:16:42.263  1019  1851 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,03-17 11:16:42.263  1019  1851 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 11:16:42.283  1019  1851 D QSEECOMAPI: : Loaded image: APP id = 9
,03-17 11:16:42.283  1019  1626 I ActivityManager: Killing 2996:com.sec.usbsettings/1000 (adj 15): empty #31
,03-17 11:16:42.293  1019  1851 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-17 11:16:42.293  1019  1851 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 9
,03-17 11:16:42.293  1019  1851 E terrier : handleString: Failed to handle string(-4)
03-17 11:16:42.293  1019  1851 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,03-17 11:16:42.293  3467  3467 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-17 11:16:42.293  3467  3467 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,03-17 11:16:42.293  3467  3467 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 11:16:42.293  3467  3467 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 11:16:42.293  3467  3467 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 11:16:42.293  3467  3467 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,03-17 11:16:42.293  3661  3799 D Volley  : [495] g.b: Cache cleared.
,03-17 11:16:42.293  3810  3810 I ExternalOEMControlProvider: onCreate
,03-17 11:16:42.303  3661  3661 I Finsky  : [1] com.google.android.finsky.receivers.h.a(1107): Installer kick - no action, not running yet
,03-17 11:16:42.303  3695  3695 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
03-17 11:16:42.303  1019  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:42.303  1019  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:42.303  1019  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:42.303  1019  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:42.303  3661  3846 D Ads     : Skipping gmscore version check
,03-17 11:16:42.313  3661  3827 D Volley  : [501] g.b: Cache cleared.
,03-17 11:16:42.313  3847  3847 E Zygote  : MountEmulatedStorage()
03-17 11:16:42.313  3847  3847 E Zygote  : v2
,03-17 11:16:42.323  3847  3847 I libpersona: KNOX_SDCARD checking this for 10028,
,03-17 11:16:42.323  1019  1142 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3847 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
03-17 11:16:42.323  1019  1142 I ActivityManager: Killing 2478:com.android.mms/u0a41 (adj 15): empty #31
,03-17 11:16:42.323  3847  3847 I libpersona: KNOX_SDCARD not a persona
,03-17 11:16:42.323  3847  3847 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 11:16:42.323  3847  3847 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:42.323  1019  1525 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:42.323  1019  1525 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:42.323  1019  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-17 11:16:42.323  3847  3847 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 11:16:42.333  1019  1851 W ActivityManager: userId = 0, bbcId = -10000
,03-17 11:16:42.333  1019  1851 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 11:16:42.333  1019  1851 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-17 11:16:42.353  1019  3388 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:42.353  1019  3388 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:42.353  1019  3388 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:42.353  1019  3388 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:42.353  3661  3661 I Finsky  : [1] com.google.android.finsky.g.j.run(208): Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-17 11:16:42.353  3661  3661 I Finsky  : [1] com.google.android.finsky.g.j.run(214): Finished loading 1 libraries.
,03-17 11:16:42.363  3847  3847 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:42.363  3847  3847 D ActivityThread: Added TimaKeyStore provider,
,03-17 11:16:42.383  1019  3388 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3865 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 11:16:42.383  3865  3865 E Zygote  : MountEmulatedStorage(),
03-17 11:16:42.383  3865  3865 E Zygote  : v2
03-17 11:16:42.383  3865  3865 I libpersona: KNOX_SDCARD checking this for 1000
03-17 11:16:42.383  3865  3865 I libpersona: KNOX_SDCARD not a persona
,03-17 11:16:42.383  3865  3865 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 11:16:42.383  3287  3680 W jxcore-log: Platform android
03-17 11:16:42.383  3287  3680 W jxcore-log: 
03-17 11:16:42.383  3287  3680 W jxcore-log: Process ARCH arm
03-17 11:16:42.383  3287  3680 W jxcore-log: 
,03-17 11:16:42.383  3661  3661 I Finsky  : [1] com.google.android.finsky.b.j.a(273): result=false type=4
03-17 11:16:42.383  3865  3865 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:42.393  3865  3865 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 11:16:42.403  1019  1626 D SettingsProvider: name = PREVIOUS_SYS_TIME
03-17 11:16:42.403  1019  1626 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 11:16:42.403  1019  1626 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 11:16:42.403  1019  1626 D SettingsProvider: selectionArgs: false
03-17 11:16:42.403  1019  1626 D SettingsProvider: selectionArgs: 10058
03-17 11:16:42.403  1019  1626 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 11:16:42.403  1019  1626 D SettingsProvider: ret = -1
,03-17 11:16:42.403  1019  1403 W ActivityManager: userId = 0, bbcId = -10000
,03-17 11:16:42.403  1019  1403 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 11:16:42.403  1019  1403 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 11:16:42.403  1019  1626 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,03-17 11:16:42.413  1019  1386 W ActivityManager: userId = 0, bbcId = -10000
,03-17 11:16:42.413  1019  1386 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 11:16:42.413  1019  1386 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
03-17 11:16:42.413  1019  1525 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
03-17 11:16:42.413  1019  1525 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 11:16:42.413  1019  1525 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 11:16:42.413  1019  1525 D SettingsProvider: selectionArgs: false
03-17 11:16:42.413  1019  1525 D SettingsProvider: selectionArgs: 10058
03-17 11:16:42.413  1019  1525 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 11:16:42.413  1019  1525 D SettingsProvider: ret = -1
,03-17 11:16:42.413  1019  1626 D CountryDetector: No listener is left
,03-17 11:16:42.423  1177  1177 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 11:16:42.423  1019  1525 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,03-17 11:16:42.433  1177  1177 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 11:16:42.443  3865  3865 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:42.443  3865  3865 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:42.453  1019  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2996/cgroup.procs: No such file or directory
,03-17 11:16:42.453  1019  1044 W libprocessgroup: failed to open /acct/uid_10041/pid_2478/cgroup.procs: No such file or directory
,03-17 11:16:42.473  1019  1615 W ActivityManager: userId = 0, bbcId = -10000
,03-17 11:16:42.473  1019  1615 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:42.473  1019  1615 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 11:16:42.483  3661  3661 I Finsky  : [1] com.google.android.finsky.services.ar.a(1049): Restore complete with 0 success and 0 failed.
,03-17 11:16:42.483  3865  3865 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 11:16:42.493  3391  3490 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3391, getuid(): 10052
,03-17 11:16:42.493  3391  3490 I qtaguid : Untagging socket 43
,03-17 11:16:42.503  3391  3490 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3391, getuid(): 10052
,03-17 11:16:42.503  3391  3490 I qtaguid : Untagging socket 43
,03-17 11:16:42.503  3391  3490 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3391, getuid(): 10052
03-17 11:16:42.503  3391  3490 I qtaguid : Untagging socket 43
,03-17 11:16:42.503  3391  3490 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3391, getuid(): 10052
,03-17 11:16:42.503  3391  3490 I qtaguid : Untagging socket 43
,03-17 11:16:42.503  3391  3490 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3391, getuid(): 10052
03-17 11:16:42.503  3391  3490 I qtaguid : Untagging socket 43
,03-17 11:16:42.503  3391  3490 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3391, getuid(): 10052
,03-17 11:16:42.503  3391  3490 I qtaguid : Untagging socket 43
,03-17 11:16:42.503  3391  3490 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3391, getuid(): 10052
03-17 11:16:42.503  3391  3490 I qtaguid : Untagging socket 43
,03-17 11:16:42.503  3391  3490 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3391, getuid(): 10052
,03-17 11:16:42.503  3391  3490 I qtaguid : Untagging socket 43
,03-17 11:16:42.503  3391  3490 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3391, getuid(): 10052
03-17 11:16:42.503  3391  3490 I qtaguid : Untagging socket 43
,03-17 11:16:42.503  3391  3490 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3391, getuid(): 10052
,03-17 11:16:42.503  3391  3490 I qtaguid : Untagging socket 43
,03-17 11:16:42.503  3391  3490 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3391, getuid(): 10052
,03-17 11:16:42.513  3391  3490 I qtaguid : Untagging socket 43
,03-17 11:16:42.513  3391  3490 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3391, getuid(): 10052
,03-17 11:16:42.513  3391  3490 I qtaguid : Untagging socket 43
,03-17 11:16:42.513  3391  3490 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3391, getuid(): 10052
,03-17 11:16:42.513  3391  3490 I qtaguid : Untagging socket 43
,03-17 11:16:42.553  3865  3865 I ServiceMode: received = ACTION_BOOT_COMPLETED
,03-17 11:16:42.553  3865  3865 I ServiceMode: setReferenceIsDumpState : 0
,03-17 11:16:42.563  1019  1403 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:42.563  1019  1403 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:42.563  1019  1403 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:42.563  1019  1403 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:42.573  3886  3886 E Zygote  : MountEmulatedStorage(),
03-17 11:16:42.573  3886  3886 E Zygote  : v2
03-17 11:16:42.573  3886  3886 I libpersona: KNOX_SDCARD checking this for 1000
03-17 11:16:42.573  3886  3886 I libpersona: KNOX_SDCARD not a persona
,03-17 11:16:42.573  3886  3886 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 11:16:42.573  1019  1403 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3886 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 11:16:42.573  1019  1403 I ActivityManager: Killing 2913:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
,03-17 11:16:42.573  3886  3886 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:42.583  3886  3886 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 11:16:42.583  1019  3389 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:42.583  1019  3389 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:42.583  1019  3389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 11:16:42.603  1019  1142 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 11:16:42.603  2164  3881 D FileApkUtils: Optimizing (staging complete)
,03-17 11:16:42.613  2164  3881 D FileApkUtils: Optimizing: DynamiteModules-prod.apk [1dad65bca29c108ad7dad5d3707435ff0555d8adf974340225c102890df71a23]
,03-17 11:16:42.613  1019  3389 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:42.613  1019  3389 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:42.613  1019  3389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 11:16:42.623  2164  3881 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
,03-17 11:16:42.623  3886  3886 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:42.623  3886  3886 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:42.623  2164  3881 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk is already optimized. Bailing.
,03-17 11:16:42.633  3287  3680 I jxcore-log: JXcore Cordova bridge is ready!
03-17 11:16:42.633  3287  3680 I jxcore-log: 
,03-17 11:16:42.633  3287  3680 W jxcore-log: JXcore engine is started
,03-17 11:16:42.633  3695  3902 E Gmail   : Error finding the version of the Email provider.....
03-17 11:16:42.633  3695  3902 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-17 11:16:42.633  3695  3902 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
03-17 11:16:42.633  3695  3902 E Gmail   : 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
03-17 11:16:42.633  3695  3902 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
03-17 11:16:42.633  3695  3902 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 11:16:42.633  3695  3902 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 11:16:42.633  3695  3902 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
03-17 11:16:42.633  3695  3902 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 11:16:42.633  1019  1032 I ActivityManager: Killing 3065:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
03-17 11:16:42.633  3695  3902 W EmailMigration: We do not support migrating this version of the Email provider.
,03-17 11:16:42.643  1019  1359 W ActivityManager: userId = 0, bbcId = -10000,
03-17 11:16:42.643  1019  1359 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:42.643  1019  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
03-17 11:16:42.643  3287  3618 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 11:16:42.643  1019  1044 W libprocessgroup: failed to open /acct/uid_10081/pid_2913/cgroup.procs: No such file or directory
,03-17 11:16:42.643  3695  3807 I Gmail   : getAccountsCursor
,03-17 11:16:42.643  3287  3287 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-17 11:16:42.653  3287  3680 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-17 11:16:42.653  3287  3680 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-17 11:16:42.663  1019  1386 W ActivityManager: userId = 0, bbcId = -10000
,03-17 11:16:42.663  1019  1386 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:42.663  1019  1386 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 11:16:42.663  3287  3287 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,03-17 11:16:42.663  3287  3287 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-17 11:16:42.673  1019  3389 D FocusedStackFrame: Set to : 0
03-17 11:16:42.673  1019  3389 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 11:16:42.673  1019  3389 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 11:16:42.673  1019  3389 D InputDispatcher: Focused application set to: xxxx
03-17 11:16:42.673  1019  3389 D InputDispatcher: Focus left window: 3287
03-17 11:16:42.683   259  1101 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (120 us)
,03-17 11:16:42.693  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 11:16:42.693  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 11:16:42.703  3287  3618 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 29ms. Plugin should use CordovaInterface.getThreadPool().
,03-17 11:16:42.703  1019  1851 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-17 11:16:42.703  1019  1851 W ActivityManager: mDVFSHelper.acquire()
,03-17 11:16:42.703  1019  1851 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 11:16:42.703  1019  1851 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 11:16:42.703  1019  1851 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-17 11:16:42.713  1019  1403 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 11:16:42.733  1019  1359 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 11:16:42.733  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
03-17 11:16:42.733  1019  1019 D SensorService: [SO] activate (ident=0xb797ff68, enabled=0)
03-17 11:16:42.733  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-17 11:16:42.733  3695  3695 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@10ce17a0 that was originally bound here
03-17 11:16:42.733  3695  3695 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@10ce17a0 that was originally bound here
03-17 11:16:42.733  3695  3695 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
03-17 11:16:42.733  3695  3695 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
03-17 11:16:42.733  3695  3695 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
03-17 11:16:42.733  3695  3695 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
03-17 11:16:42.733  3695  3695 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
03-17 11:16:42.733  3695  3695 E ActivityThread: 	at com.android.emailcommon.service.H.a(SourceFile:181)
03-17 11:16:42.733  3695  3695 E ActivityThread: 	at com.android.emailcommon.service.H.mb(SourceFile:224)
03-17 11:16:42.733  3695  3695 E ActivityThread: 	at com.android.email.service.n.j(SourceFile:160)
03-17 11:16:42.733  3695  3695 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:171)
03-17 11:16:42.733  3695  3695 E ActivityThread: 	at com.android.email.provider.b.F(SourceFile:115)
03-17 11:16:42.733  3695  3695 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
03-17 11:16:42.733  3695  3695 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
03-17 11:16:42.733  3695  3695 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 11:16:42.733  3695  3695 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 11:16:42.733  3695  3695 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 11:16:42.733  3695  3695 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 11:16:42.733  1019  3389 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@19ce12d8
,03-17 11:16:42.733  1511  1511 D Launcher: onRestart, Launcher: 47197158
03-17 11:16:42.733  1511  1511 D Launcher: onStart, Launcher: 47197158
03-17 11:16:42.743  1511  1511 D Launcher.HomeView: onStart
,03-17 11:16:42.743  1511  1511 D Launcher: onResume, Launcher: 47197158
,03-17 11:16:42.743  1019  1525 D SettingsProvider: name = kids_home_mode
03-17 11:16:42.743  1019  1525 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 11:16:42.743  1019  1525 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 11:16:42.743  1019  1525 D SettingsProvider: selectionArgs: false
03-17 11:16:42.743  1019  1525 D SettingsProvider: selectionArgs: 10006
03-17 11:16:42.743  1019  1525 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 11:16:42.743  1019  1525 D SettingsProvider: ret = -1
,03-17 11:16:42.743  1511  1511 D Launcher.HomeView: onResume
,03-17 11:16:42.743  1019  1019 D SensorManager: unregisterListener ::   
03-17 11:16:42.743  1019  1019 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-17 11:16:42.743  1019  1019 D SensorService: [SO] changed settle time [0]
03-17 11:16:42.743  1019  1019 D SensorService: [SO] setDelay [200000000]
03-17 11:16:42.743  1019  1019 D SensorService: [SO] activate (ident=0xb75a7d18, enabled=1)
03-17 11:16:42.743  1019  1019 D SensorService: [SO] AR_init
03-17 11:16:42.743  1019  1019 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-17 11:16:42.753  1511  1511 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 11:16:42.753  1019  3388 W ActivityManager: userId = 0, bbcId = -10000
,03-17 11:16:42.753  1019  3388 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:42.753  1019  3388 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
03-17 11:16:42.753  1019  1019 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,03-17 11:16:42.753  1019  1044 W libprocessgroup: failed to open /acct/uid_10043/pid_3065/cgroup.procs: No such file or directory
03-17 11:16:42.763  1511  1511 D MenuAppsGridFragment: onResume
,03-17 11:16:42.763  1019  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:42.763  1019  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:42.763  1019  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:42.763  1019  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:42.773  3391  3490 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3391, getuid(): 10052
,03-17 11:16:42.773  3911  3911 E Zygote  : MountEmulatedStorage()
,03-17 11:16:42.773  3911  3911 E Zygote  : v2
03-17 11:16:42.773  3911  3911 I libpersona: KNOX_SDCARD checking this for 10102
03-17 11:16:42.773  3911  3911 I libpersona: KNOX_SDCARD not a persona,
,03-17 11:16:42.773  3911  3911 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 11:16:42.773  3253  3304 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,03-17 11:16:42.773  1019  1525 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3911 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
03-17 11:16:42.783  1019  1141 D ActivityManager: handle home activity for 0
,03-17 11:16:42.783  1019  1141 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-17 11:16:42.783  1019  1141 D KnoxTimeoutHandler: post home show event for user 0
03-17 11:16:42.783  1019  1141 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 11:16:42.783  1019  1141 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 11:16:42.783  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 11:16:42.783  1019  1141 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 11:16:42.783  1019  1019 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-17 11:16:42.783  1019  1019 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-17 11:16:42.783  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-17 11:16:42.783  3911  3911 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:42.783  3911  3911 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 11:16:42.783   259   259 I SurfaceFlinger: id=13 createSurf (540x960),1 flag=4, Mauncher
,03-17 11:16:42.793  1019  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 11:16:42.793  1019  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 11:16:42.793  1019  1615 D InputDispatcher: Focus entered window: 1511
,03-17 11:16:42.803  1019  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 11:16:42.803  1019  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 11:16:42.803  1511  1511 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 11:16:42.813  1746  3910 I GoogleHttpClient: GMS http client unavailable, use old client
,03-17 11:16:42.813  1511  1511 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 11:16:42.823  1019  1382 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 11:16:42.823  1177  1177 I StatusBar: Icon Only
03-17 11:16:42.823  1177  1177 D PanelView: There is/are notification(s) 
,03-17 11:16:42.823  3287  3287 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 11:16:42.823  1019  3926 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 11:16:42.833  1802  1802 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-17 11:16:42.833  3911  3911 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 11:16:42.843  3911  3911 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:42.863  1511  1511 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1ef6acb2 time:40912
,03-17 11:16:42.863  1019  1050 D PersonaManager: isKioskContainerExistOnDevice
,03-17 11:16:42.873  3886  3886 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
,03-17 11:16:42.873  3886  3886 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,03-17 11:16:42.873  1019  1626 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:42.873  1019  1626 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:42.873  1019  1626 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 11:16:42.883  1019  3389 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:42.883  1019  3389 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 11:16:42.883  1019  3389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 11:16:42.903  1019  1050 I ActivityManager: Displayed Component not be shown by security: +195ms
,03-17 11:16:42.903  3886  3886 D NPS_WSSNPS: [] Service onCreate!!
,03-17 11:16:42.913  1019  1851 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:42.913  1019  1851 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:42.913  1019  1851 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:42.913  1019  1851 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:42.923  1746  3910 I art     : Explicit concurrent mark sweep GC freed 3624(157KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 4MB/6MB, paused 11.088ms total 54.696ms
,03-17 11:16:42.933  3391  3515 I ContactAccountLoggerTas: canRun() : Opted Out
,03-17 11:16:42.933  3931  3931 E Zygote  : MountEmulatedStorage()
03-17 11:16:42.933  3931  3931 E Zygote  : v2
03-17 11:16:42.933  3931  3931 I libpersona: KNOX_SDCARD checking this for 1000
03-17 11:16:42.933  3931  3931 I libpersona: KNOX_SDCARD not a persona
,03-17 11:16:42.933  3931  3931 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 11:16:42.933  1019  1851 I ActivityManager: Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3931 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 11:16:42.933  3931  3931 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:42.933  3931  3931 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 11:16:42.943  1019  1386 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:42.943  1019  1386 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:42.943  1019  1386 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 11:16:42.943  1746  1759 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-17 11:16:42.943  3847  3847 I System.out: Inside onCreate() of WakeupTriggerProvide
03-17 11:16:42.943  3847  3847 I System.out: Inside WakeupProvider
,03-17 11:16:42.953  1019  1042 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 11:16:42.953  3911  3911 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 11:16:42.963  2636  2636 D FactoryTestApp: [DummyFtClient$onDestroy](2636) Destroy DummyFtClient service
,03-17 11:16:42.973  3931  3931 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 11:16:42.973  3931  3931 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:42.973  2636  2636 D FactoryTestApp: [Support$Values.getString](2636) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 11:16:42.973  2636  2636 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2636) mConnectionMode = gsm
03-17 11:16:42.973  2636  2636 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2636) RUNNING_FTCLIENT : false
03-17 11:16:42.973  2636  2636 D FactoryTestApp: [DummyFtClient$onDestroy](2636) kill process
03-17 11:16:42.973  2636  2636 I Process : Sending signal. PID: 2636 SIG: 9
,03-17 11:16:42.983  3886  3949 D NPS_WSSNPS: [50.150321] NpsServiceTask Start
,03-17 11:16:43.003  1019  1403 W ActivityManager: userId = 0, bbcId = -10000
,03-17 11:16:43.003  1019  1403 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:43.003  1019  1403 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 11:16:43.013  3886  3886 D NPS_WSSNPS: [50.150321] smlDBHelper
03-17 11:16:43.013  3907  3907 D AndroidRuntime: 
03-17 11:16:43.013  3907  3907 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-17 11:16:43.013  3907  3907 D AndroidRuntime: CheckJNI is OFF
,03-17 11:16:43.013  1959  1959 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-17 11:16:43.013  3907  3907 D AndroidRuntime: readGMSProperty: start
03-17 11:16:43.013  3907  3907 D AndroidRuntime: readGMSProperty: already setted!!
03-17 11:16:43.013  3907  3907 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 11:16:43.013  3907  3907 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 11:16:43.013  3907  3907 D AndroidRuntime: readGMSProperty: end
03-17 11:16:43.013  3907  3907 D AndroidRuntime: addProductProperty: start
,03-17 11:16:43.033  1959  1959 D ChimeraCfgMgr: Reading stored module config
,03-17 11:16:43.053  3886  3886 I NPS_WSSNPS: [50.150321] AsyncBulkFlagCheck,
,03-17 11:16:43.083  1019  3389 I ActivityManager: Process com.sec.factory (pid 2636)(adj 0) has died(18,639)
,03-17 11:16:43.123  1019  1142 D SettingsProvider: name = access_control_enabled
,03-17 11:16:43.133  1959  1959 D WearableService: callingUid 10011, callindPid: 1959
03-17 11:16:43.133  1019  1615 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:43.133  1019  1615 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:43.133  1019  1615 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:43.133  1019  1615 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:43.153  3965  3965 E Zygote  : MountEmulatedStorage()
,03-17 11:16:43.153  3965  3965 E Zygote  : v2
,03-17 11:16:43.153  1019  1042 D SensorService: [SO] currT = 41201065000, prevT = 40741065000, diff = 460000000, [-0.460 0.211 9.902]
03-17 11:16:43.153  3965  3965 I libpersona: KNOX_SDCARD checking this for 10065
03-17 11:16:43.153  1019  1042 D SensorService: [SO] -0.460 0.211 9.902
03-17 11:16:43.153  3965  3965 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:43.153  1019  1042 D SensorService: [SO] [100 -> 255]
,03-17 11:16:43.153  3965  3965 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 11:16:43.153  1019  1615 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3965 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 11:16:43.153  1959  1959 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-17 11:16:43.153  3965  3965 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:43.163  3965  3965 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 11:16:43.163  3886  3955 I NPS_WSSNPS: [50.150321] IsRemain_AsyncBulkCheck
,03-17 11:16:43.163  3886  3955 I NPS_WSSNPS: [50.150321] IsRemain_Asyncing nothing
03-17 11:16:43.163  3886  3955 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
03-17 11:16:43.163  1959  1959 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 11:16:43.163  1019  3389 W ActivityManager: userId = 0, bbcId = -10000
,03-17 11:16:43.163  1019  3389 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 11:16:43.163  1019  3389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps,
,03-17 11:16:43.173  3907  3907 E AffinityControl: AffinityControl: registerfunction enter
,03-17 11:16:43.173  3847  3847 W art     : Verification of java.util.Map com.vlingo.midas.settings.MidasSettings.getInitiallyDisabledFeatures() took 179.520ms
,03-17 11:16:43.183  3965  3965 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 11:16:43.183  3965  3965 D ActivityThread: Added TimaKeyStore provider
03-17 11:16:43.183   321   321 I art     : Explicit concurrent mark sweep GC freed 8711(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 27.569ms
,03-17 11:16:43.193  1959  1959 E GmsWearableNodeHelper: GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-17 11:16:43.203  1019  1045 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 11:16:43.203  1019  1045 W ActivityManager: mDVFSHelper.release()
,03-17 11:16:43.203  3907  3907 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
03-17 11:16:43.203  1019  1045 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 11:16:43.203  3886  3886 D NPS_WSSNPS: [50.150321] Service onDestroy
03-17 11:16:43.203   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 16.633ms
,03-17 11:16:43.253   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 33.573ms
,03-17 11:16:43.283  1019  1386 D PackageManager: START PACKAGE DELETE: observer{343191671}
03-17 11:16:43.283  1019  1386 D PackageManager: pkg{<packageName>}
03-17 11:16:43.283  1019  1386 D PackageManager: user{0}
03-17 11:16:43.283  1019  1386 D PackageManager: caller{2000}
03-17 11:16:43.283  1019  1386 D PackageManager: flags{2}
03-17 11:16:43.283  1019  1386 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-17 11:16:43.283  1019  1386 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-17 11:16:43.283  1019  1386 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-17 11:16:43.283  1019  1386 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-17 11:16:43.283  1019  1386 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,03-17 11:16:43.283  1019  1059 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-17 11:16:43.283  1019  1059 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-17 11:16:43.283  1019  1059 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,03-17 11:16:43.283  3886  3886 I NPS_WSSNPS: [50.150321] smlBRConfigurationDelete
03-17 11:16:43.283  3886  3886 I NPS_WSSNPS: [50.150321] smlBRMessageDelete
,03-17 11:16:43.283  1019  1059 D ApplicationPolicy: getApplicationUninstallationEnabled
03-17 11:16:43.283  1019  1059 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-17 11:16:43.283  2164  2164 W InstanceID/Rpc: Found 10011
,03-17 11:16:43.283  3695  3904 E SQLiteLog: (283) recovered 88 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-17 11:16:43.293  3886  3886 I NPS_WSSNPS: [50.150321] smlBREmailDelete
,03-17 11:16:43.293  3886  3886 I NPS_WSSNPS: [50.150321] smlBRNetworkDelete
03-17 11:16:43.293  3886  3886 I NPS_WSSNPS: [50.150321] smlBRCallLogDelete
03-17 11:16:43.293  1019  1059 D PackageManager: !@killApplicatoin: 10167, uninstall pkg
,03-17 11:16:43.293  3886  3886 I NPS_WSSNPS: [50.150321] smlBRMiniDiaryDelete
03-17 11:16:43.293  3886  3886 I NPS_WSSNPS: [50.150321] smlBRPenMemoMDelete
03-17 11:16:43.293  3886  3886 I NPS_WSSNPS: [50.150321] smlBRSMemoDelete
03-17 11:16:43.293  3886  3886 I NPS_WSSNPS: [50.150321] cpuBooster release : false
,03-17 11:16:43.323  1019  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{95781b4 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t10} time:41374
,03-17 11:16:43.323   259  1100 I SurfaceFlinger: id=12 Removed NainActivit (7/8),
,03-17 11:16:43.323   259   454 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
,03-17 11:16:43.333  1019  1045 I ActivityManager: Killing 3118:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,03-17 11:16:43.343  1019  1045 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
,03-17 11:16:43.343  1019  1045 I ActivityManager: Killing 3287:com.test.thalitest/u0a167 (adj 9): stop com.test.thalitest cause uninstall pkg
,03-17 11:16:43.443  1019  1527 I art     : Explicit concurrent mark sweep GC freed 27235(1557KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 5.114ms total 180.215ms
,03-17 11:16:43.453  3695  3904 E File    : fail readDirectory() errno=2
,03-17 11:16:43.453  3695  3974 I Gmail   : notifyAccountChanged
,03-17 11:16:43.453  1019  1059 W PackageSettings: Skipping PackageSetting{2c8a6c7c com.example.hello/10168} due to missing metadata
,03-17 11:16:43.463  3695  3808 I Gmail   : getAccountsCursor
,03-17 11:16:43.463  3695  3974 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 11:16:43.473  3695  3974 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 11:16:43.503  1019  3389 D PowerManagerService: [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1177 (0x0)
,03-17 11:16:43.503  1019  1019 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1019  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 11:16:43.503  3847  3847 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
,03-17 11:16:43.503  3320  3345 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-17 11:16:43.503  1019  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3118/cgroup.procs: No such file or directory
03-17 11:16:43.513  3695  3974 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 11:16:43.513  3695  3974 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 11:16:43.513  1019  1527 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:43.513  1019  1527 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:43.513  1019  1527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 11:16:43.533  1019  1059 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=0: pkg removed
,03-17 11:16:43.533  1959  1959 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 11:16:43.533  3320  3345 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-17 11:16:43.533  3320  3345 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-17 11:16:43.533  3320  3345 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-17 11:16:43.543  3320  3345 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-17 11:16:43.543  3320  3345 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-17 11:16:43.543  3320  3345 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-17 11:16:43.543  3320  3345 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-17 11:16:43.553  1019  1059 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,03-17 11:16:43.563  3886  3886 D NPS_WSSNPS: [50.150321] dsServerSocket close
,03-17 11:16:43.573  3965  3965 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,03-17 11:16:43.583  1019  1103 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-17 11:16:43.583  1802  1802 E SamsungIME: mOCRHelper is null
,03-17 11:16:43.583  1959  2200 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-17 11:16:43.593  1482  1482 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 11:16:43.603  1019  1527 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:43.603  1019  1527 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:43.603  1019  1527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 11:16:43.633  1019  1019 D RCPManagerService: PackageReceiver onReceive()
03-17 11:16:43.633  1019  1019 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-17 11:16:43.633  1019  1019 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,03-17 11:16:43.643  1019  1130 V NetworkStats: removeUidsLocked() for UIDs [10167]
,03-17 11:16:43.643  1019  1130 V NetworkStats: performPollLocked(flags=0x3)
,03-17 11:16:43.653  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 11:16:43.653  1019  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
03-17 11:16:43.653  1019  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-17 11:16:43.673  1019  1130 V NetworkStats: performPollLocked() took 21ms
03-17 11:16:43.673  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 11:16:43.683  3847  3847 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
,03-17 11:16:43.703  1019  1142 I ActivityManager: Killing 3081:com.sec.dsm.system/1000 (adj 15): empty #31
,03-17 11:16:43.713  1019  1044 D EnterpriseDeviceManagerService: Package has changed for user 0
,03-17 11:16:43.723  1019  1044 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,03-17 11:16:43.723  1019  1044 W TextServicesManagerService: no available spell checker services found
,03-17 11:16:43.723  1473  1473 D RegisteredServicesCache: empty dynamic service
,03-17 11:16:43.743  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 11:16:43.743  1019  1382 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-17 11:16:43.743  1019  1382 D SecContentProvider2: mCursor = null
,03-17 11:16:43.753  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 11:16:43.763  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 11:16:43.773  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 11:16:43.783  3253  3304 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,03-17 11:16:43.823  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-17 11:16:43.823  1019  1019 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-17 11:16:43.823  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-17 11:16:43.823  1019  1019 V EnterpriseBillingPolicy: uID is 10167
03-17 11:16:43.823  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 11:16:43.823  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-17 11:16:43.823  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-17 11:16:43.823  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 11:16:43.823  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-17 11:16:43.823  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-17 11:16:43.823  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-17 11:16:43.823  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-17 11:16:43.823  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-17 11:16:43.823  1019  1019 V EnterpriseBillingPolicy: uID is 10167
03-17 11:16:43.823  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 11:16:43.823  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-17 11:16:43.833  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,03-17 11:16:43.833  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 11:16:43.833  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
,03-17 11:16:43.833  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-17 11:16:43.833  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-17 11:16:43.833  1019  2785 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
,03-17 11:16:43.843  1019  1131 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 11:16:43.843  1019  1131 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 11:16:43.883  1019  1059 W art     : Suspending all threads took: 14.780ms
,03-17 11:16:43.893  3911  4002 I Babel   : MmsConfig: mnc/mcc: 0/0
,03-17 11:16:43.903  3911  4002 I Babel   : MmsConfig.loadMmsSettings
,03-17 11:16:43.903  3911  4002 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
03-17 11:16:43.903  3911  4002 I Babel   : MmsConfig.loadFromDatabase
,03-17 11:16:43.913  1019  1044 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-17 11:16:43.923  1019  1059 I art     : Explicit concurrent mark sweep GC freed 19004(1335KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 24MB/37MB, paused 31.876ms total 303.359ms
,03-17 11:16:43.923  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 11:16:43.923  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 11:16:43.943  3695  3843 I Gmail   : getAccountsCursor
,03-17 11:16:43.953  1019  1059 D PackageManager: delete codoeFile: 
,03-17 11:16:43.953  1019  1059 D AASAuninstall: userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
,03-17 11:16:43.953  1019  1059 I AASA_removePackage: UID=10167 Target=com.test.thalitest
,03-17 11:16:43.953  1959  1959 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 11:16:43.963  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 11:16:43.973  1019  1386 W ActivityManager: userId = 0, bbcId = -10000
,03-17 11:16:43.973  1019  1386 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:43.973  1019  1386 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 11:16:43.973  1019  1044 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 11:16:43.973  1019  1044 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 11:16:43.973  1019  1044 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 11:16:43.973  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 11:16:43.983  1019  1163 D TaskPersister: removeObsoleteFile: deleting file=11_task.xml
,03-17 11:16:43.983  1019  1163 D TaskPersister: removeObsoleteFile: deleting file=11_task_thumbnail.png
,03-17 11:16:43.983  1019  1059 D PackageManager: result of delete: 1{343191671}
,03-17 11:16:43.993  3907  3907 D AndroidRuntime: Shutting down VM
,03-17 11:16:44.003  2164  3987 I Icing   : Storage manager: low false usage 2.12MB avail 9.97GB capacity 11.63GB
,03-17 11:16:44.003  1019  1059 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-17 11:16:44.003  1019  1059 D PackageManager: userId{-1}
03-17 11:16:44.003  1019  1059 D PackageManager: andCode{true}
,03-17 11:16:44.013  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 11:16:44.013  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:44.013  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:44.013  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:44.023  1019  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:44.023  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 11:16:44.023  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 11:16:44.023  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 11:16:44.033  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 11:16:44.033  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 11:16:44.033  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 11:16:44.033  4009  4009 E Zygote  : MountEmulatedStorage()
03-17 11:16:44.033  4009  4009 E Zygote  : v2
03-17 11:16:44.033  4009  4009 I libpersona: KNOX_SDCARD checking this for 10003
03-17 11:16:44.033  4009  4009 I libpersona: KNOX_SDCARD not a persona
,03-17 11:16:44.033  4009  4009 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 11:16:44.033  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 11:16:44.033  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 11:16:44.043  4009  4009 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 11:16:44.043  3911  4002 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,03-17 11:16:44.043  4009  4009 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 11:16:44.043  3911  4002 I Babel   : MmsConfig.loadFromResources
03-17 11:16:44.043  3911  4002 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
03-17 11:16:44.043  1019  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
03-17 11:16:44.043  3911  4002 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
03-17 11:16:44.043  1019  1059 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=4009 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,03-17 11:16:44.043  1019  1386 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:44.043  1019  1386 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:44.043  1019  1386 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 11:16:44.043  3911  4000 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 11:16:44.053  3911  4000 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 11:16:44.053  3911  4000 W AudioCapabilities: Unsupported mime audio/qcelp
,03-17 11:16:44.053  1019  1044 D UsbSettingsManager: clearDefaults: com.test.thalitest
03-17 11:16:44.053  1019  1044 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,03-17 11:16:44.063  3911  3911 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-17 11:16:44.063  1019  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3081/cgroup.procs: No such file or directory
,03-17 11:16:44.073  4009  4009 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:44.073  4009  4009 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:44.093  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:44.093  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:44.093  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 11:16:44.093  3911  4000 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,03-17 11:16:44.093  3911  4000 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,03-17 11:16:44.113  3911  4000 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,03-17 11:16:44.113  3911  4000 W AudioCapabilities: Unsupported mime audio/x-ima
,03-17 11:16:44.123  3911  4000 W AudioCapabilities: Unsupported mime audio/qcelp
,03-17 11:16:44.133  3847  3847 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,03-17 11:16:44.143  3911  4000 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 11:16:44.143  3847  3847 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,03-17 11:16:44.163  3911  4000 W VideoCapabilities: Unsupported mime video/wvc1
,03-17 11:16:44.163  1019  3985 I ActivityManager: Killing 3162:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,03-17 11:16:44.163  3911  4000 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 11:16:44.173  3847  3847 D DialogFlow: initQueue()
,03-17 11:16:44.173  1019  1382 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:44.173  1019  1382 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:44.173  1019  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 11:16:44.183  3911  4000 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,03-17 11:16:44.203  3911  4000 W VideoCapabilities: Unsupported mime video/wvc1
,03-17 11:16:44.203  3907  3907 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,03-17 11:16:44.213  3911  4000 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 11:16:44.213  3911  4000 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,03-17 11:16:44.213  3911  4000 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,03-17 11:16:44.213  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:44.213  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:44.213  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:44.213  1019  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:44.223  3911  4000 W VideoCapabilities: Unsupported mime video/mp43
,03-17 11:16:44.233  3911  4000 W VideoCapabilities: Unsupported mime video/sorenson
,03-17 11:16:44.233  4030  4030 E Zygote  : MountEmulatedStorage(),
03-17 11:16:44.233  4030  4030 I libpersona: KNOX_SDCARD checking this for 10029
03-17 11:16:44.233  4030  4030 E Zygote  : v2
03-17 11:16:44.233  4030  4030 I libpersona: KNOX_SDCARD not a persona
,03-17 11:16:44.233  1019  1141 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4030 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,03-17 11:16:44.233  4030  4030 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 11:16:44.233  4030  4030 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:44.243  4030  4030 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 11:16:44.243  1019  1141 I ActivityManager: Killing 1608:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,03-17 11:16:44.253  1511  1511 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-17 11:16:44.253  1511  1511 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-17 11:16:44.263  4030  4030 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:44.263  4030  4030 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:44.283  1019  1142 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:44.283  1019  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:44.283  1019  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 11:16:44.283  3911  4000 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,03-17 11:16:44.293  1019  1382 W ActivityManager: userId = 0, bbcId = -10000
,03-17 11:16:44.293  1019  1382 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:44.293  1019  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 11:16:44.313  3911  3911 V Babel   : babel boot account: SMS
,03-17 11:16:44.313  3911  3911 V Babel   : babel boot account: thalitester@gmail.com
,03-17 11:16:44.313  3911  4000 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-17 11:16:44.313  1019  1851 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:44.313  1019  1851 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:44.313  1019  1851 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:44.313  1019  1851 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:44.323  4048  4048 E Zygote  : MountEmulatedStorage(),
03-17 11:16:44.323  4048  4048 I libpersona: KNOX_SDCARD checking this for 1000
,03-17 11:16:44.323  4048  4048 E Zygote  : v2,
03-17 11:16:44.323  4048  4048 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:44.323  4048  4048 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 11:16:44.333  1019  1851 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4048 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 11:16:44.333  1019  1851 I ActivityManager: Killing 3146:com.google.android.configupdater/u0a82 (adj 15): empty #31
,03-17 11:16:44.333  4048  4048 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 11:16:44.333  4048  4048 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 11:16:44.343  1019  1098 V AlarmManager: waitForAlarm result :4
,03-17 11:16:44.363  4048  4048 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:44.363  4048  4048 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:44.363  1019  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3162/cgroup.procs: No such file or directory
,03-17 11:16:44.373  1019  1098 V AlarmManager: waitForAlarm result :4
,03-17 11:16:44.373  2164  4005 D GCM     : COMPAT: Multi user not supported
,03-17 11:16:44.383  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-17 11:16:44.383  1019  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:44.383  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 11:16:44.383  1019  1044 W libprocessgroup: failed to open /acct/uid_10068/pid_1608/cgroup.procs: No such file or directory
03-17 11:16:44.383  1019  1044 W libprocessgroup: failed to open /acct/uid_10082/pid_3146/cgroup.procs: No such file or directory
,03-17 11:16:44.393  1019  1359 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:44.393  1019  1359 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:44.393  1019  1359 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 11:16:44.393  1959  1959 D GCM     : COMPAT: Multi user not supported
,03-17 11:16:44.403  1019  1851 W ActivityManager: userId = 0, bbcId = -10000
,03-17 11:16:44.403  1019  1851 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 11:16:44.403  1019  1851 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 11:16:44.413  1019  1615 W ActivityManager: userId = 0, bbcId = -10000
,03-17 11:16:44.413  1019  1615 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-17 11:16:44.413  1019  1615 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 11:16:44.423  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:44.423  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:44.423  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 11:16:44.473  1019  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:44.473  1019  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:44.473  1019  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:44.473  1019  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:44.483  4069  4069 E Zygote  : MountEmulatedStorage()
,03-17 11:16:44.483  4069  4069 E Zygote  : v2
03-17 11:16:44.483  4069  4069 I libpersona: KNOX_SDCARD checking this for 10030
03-17 11:16:44.483  4069  4069 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:44.483  4069  4069 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 11:16:44.493  4069  4069 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:44.493  1019  1142 I ActivityManager: Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4069 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-17 11:16:44.493  4069  4069 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
03-17 11:16:44.493  1019  1142 I ActivityManager: Killing 3209:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,03-17 11:16:44.493  2164  4067 I CheckinService: Disabling old GoogleServicesFramework version
,03-17 11:16:44.513  4069  4069 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:44.513  4069  4069 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:44.523  1019  1382 W ActivityManager: userId = 0, bbcId = -10000
,03-17 11:16:44.523  1019  1382 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:44.523  1019  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 11:16:44.523  1177  1177 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 11:16:44.523  1177  1177 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 11:16:44.523  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 11:16:44.533  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 11:16:44.533  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 11:16:44.533  1177  1177 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 11:16:44.543  1019  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3209/cgroup.procs: No such file or directory
,03-17 11:16:44.553  1019  3389 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:44.553  1019  3389 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:44.553  1019  3389 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:44.553  1019  3389 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:44.563  2164  4005 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,03-17 11:16:44.563  2164  2164 D ChimeraCfgMgr: Reading stored module config
,03-17 11:16:44.573  4086  4086 E Zygote  : MountEmulatedStorage(),
03-17 11:16:44.573  4086  4086 E Zygote  : v2
03-17 11:16:44.573  4086  4086 I libpersona: KNOX_SDCARD checking this for 1000
03-17 11:16:44.573  4086  4086 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:44.573  4086  4086 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 11:16:44.573  1019  3389 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4086 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 11:16:44.583  4086  4086 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:44.583  4086  4086 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 11:16:44.583  1019  3389 I ActivityManager: Killing 3222:com.dropbox.android/u0a88 (adj 15): empty #31
,03-17 11:16:44.583  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:44.583  1019  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:44.583  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 11:16:44.603  4086  4086 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:44.603  4086  4086 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:44.633  1019  1615 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:44.633  1019  1615 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:44.633  1019  1615 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 11:16:44.653  1019  1851 I ActivityManager: Killing 3271:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,03-17 11:16:44.653  4086  4086 E KnoxSetupWizardClient: isShipMode : 1
03-17 11:16:44.653  4086  4086 I KnoxSetupWizardClient: onReceive : android.intent.action.BOOT_COMPLETED
,03-17 11:16:44.663  1019  1019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,03-17 11:16:44.663  1019  1019 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,03-17 11:16:44.663  2164  2164 D BootCompletedReceiver: Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,03-17 11:16:44.673  2164  2164 D BootCompletedReceiver: Got an BootCompleted event.
,03-17 11:16:44.673  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:44.673  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:44.673  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:44.673  1019  1019 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:44.683  4105  4105 E Zygote  : MountEmulatedStorage()
,03-17 11:16:44.683  4105  4105 E Zygote  : v2
,03-17 11:16:44.683  4105  4105 I libpersona: KNOX_SDCARD checking this for 1000
03-17 11:16:44.683  4105  4105 I libpersona: KNOX_SDCARD not a persona
,03-17 11:16:44.683  1019  1019 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=4105 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,03-17 11:16:44.683  4105  4105 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 11:16:44.693  4105  4105 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:44.693  4105  4105 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 11:16:44.703  1019  3389 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:44.703  1019  3389 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:44.703  1019  3389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 11:16:44.713  2164  2164 D BootCompletedReceiver: Will NOT schedule AdAttestation signal task because it's disabled.
,03-17 11:16:44.713  2164  2164 D SystemUpdateService: onCreate
,03-17 11:16:44.723  4105  4105 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:44.723  4105  4105 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:44.723  1019  1044 W libprocessgroup: failed to open /acct/uid_10088/pid_3222/cgroup.procs: No such file or directory
,03-17 11:16:44.723  1019  1044 W libprocessgroup: failed to open /acct/uid_10146/pid_3271/cgroup.procs: No such file or directory
,03-17 11:16:44.733  2164  4084 I CheckinService: Checking schedule, now: 1458209804751 next: 1458299986961
,03-17 11:16:44.743  2164  4084 I CheckinService: active receiver: disabled
,03-17 11:16:44.753  4086  4103 W System.err: java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,03-17 11:16:44.753  4086  4103 W System.err: 	at android.os.Parcel.readException(Parcel.java:1544)
03-17 11:16:44.753  4086  4103 W System.err: 	at android.os.Parcel.readException(Parcel.java:1493)
03-17 11:16:44.753  4086  4103 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
03-17 11:16:44.753  4086  4103 W System.err: 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
03-17 11:16:44.753  4086  4103 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
03-17 11:16:44.753  4086  4103 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,03-17 11:16:44.783  3253  3304 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,03-17 11:16:44.803  3467  3481 D PCWCLIENTTRACE_AccountAppFacade2_0: unregister AuthInfo UpdateReceiver v2.0
,03-17 11:16:44.803  4105  4105 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,03-17 11:16:44.813  1019  1142 W ActivityManager: userId = 0, bbcId = -10000
,03-17 11:16:44.813  1019  1142 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 11:16:44.813  1019  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-17 11:16:44.813  4086  4086 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
03-17 11:16:44.813  1019  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:44.813  1019  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:44.813  1019  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:44.813  1019  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:44.823  4069  4069 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,03-17 11:16:44.833  4086  4086 D KnoxShortcutUtil: getIsShortcutMigrationFor_2_3_0_Done true
03-17 11:16:44.833  4086  4086 D ShortcutReceiver:  KnoxContainerVersion 2.3.0
03-17 11:16:44.833  4086  4086 D ShortcutReceiver:  shortcut migration not required 
,03-17 11:16:44.833  4128  4128 E Zygote  : MountEmulatedStorage()
03-17 11:16:44.833  4128  4128 E Zygote  : v2
03-17 11:16:44.833  4128  4128 I libpersona: KNOX_SDCARD checking this for 1000
03-17 11:16:44.833  4128  4128 I libpersona: KNOX_SDCARD not a persona
03-17 11:16:44.833  4128  4128 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 11:16:44.833  1019  1382 I ActivityManager: Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=4128 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 11:16:44.833  2164  2164 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-17 11:16:44.833  4128  4128 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:44.833  1019  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:44.833  1019  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:44.833  1019  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:44.833  1019  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:44.843  4128  4128 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 11:16:44.843  2164  4136 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
,03-17 11:16:44.853  4147  4147 E Zygote  : MountEmulatedStorage()
03-17 11:16:44.853  4147  4147 E Zygote  : v2
03-17 11:16:44.853  4147  4147 I libpersona: KNOX_SDCARD checking this for 1000
03-17 11:16:44.853  4147  4147 I libpersona: KNOX_SDCARD not a persona
,03-17 11:16:44.853  1019  1382 I ActivityManager: Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4147 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 11:16:44.853  1019  1382 I ActivityManager: Killing 3303:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
,03-17 11:16:44.863  4147  4147 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 11:16:44.863  4128  4128 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-17 11:16:44.863  4128  4128 D ActivityThread: Added TimaKeyStore provider
03-17 11:16:44.863  4147  4147 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 11:16:44.863  4147  4147 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 11:16:44.863  4069  4069 E SQLiteLog: (10) unixWrite() File Descriptor : 26 gets errno : 30
,03-17 11:16:44.873  4105  4127 E SQLiteLog: (10) unixWrite() File Descriptor : 29 gets errno : 30
03-17 11:16:44.873  4105  4127 E SQLiteLog: (778) statement aborts at 2: [DELETE FROM AMData] 
,03-17 11:16:44.873  4069  4069 W System.err: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
,03-17 11:16:44.873  4105  4127 E SQLiteLog: (10) unixWrite() File Descriptor : 29 gets errno : 30
,03-17 11:16:44.873  4105  4127 W System.err: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
,03-17 11:16:44.883  4105  4127 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-17 11:16:44.883  4105  4127 W System.err: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
03-17 11:16:44.883  4105  4127 W System.err: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-17 11:16:44.883  4105  4127 W System.err: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-17 11:16:44.883  4105  4127 W System.err: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
03-17 11:16:44.883  4105  4127 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAllAMdata(DatabaseHandler.java:169)
03-17 11:16:44.883  4105  4127 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:60)
03-17 11:16:44.883  4105  4127 W System.err: ,	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 11:16:44.883  4105  4127 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 11:16:44.883  4105  4127 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-17 11:16:44.883  4105  4127 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 11:16:44.883  4069  4069 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-17 11:16:44.883  4069  4069 W System.err: 	,at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
03-17 11:16:44.883  4069  4069 W System.err: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-17 11:16:44.883  1019  1403 I ActivityManager: Killing 3320:com.policydm/1000 (adj 15): empty #31
03-17 11:16:44.883  4069  4069 W System.err: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-17 11:16:44.883  4128  4128 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 11:16:44.883  4069  4069 W System.err: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
03-17 11:16:44.883  4069  4069 W System.err: 	at com.sec.android.app.sns3.agent.db.SnsDBWrapper.onDelete(SnsDBWrapper.java:44)
03-17 11:16:44.883  4069  4069 W System.err: 	at com.sec.android.app.sns3.agent.db.SnsSvcContentProvider.deleteSSOAccount(SnsSvcContentProvider.java:192)
03-17 11:16:44.883  4069  4069 W System.err: 	at com.sec.android.app.sns3.agent.db.SnsSvcContentProvider.initSSOAccounts(SnsSvcContentProvider.java:86)
03-17 11:16:44.883  4069  4069 W System.err: 	at com.sec.android.app.sns3.agent.db.SnsSvcContentProvider.onCreate(SnsSvcContentProvider.java:68)
03-17 11:16:44.883  4069  4069 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
03-17 11:16:44.883  4069  4069 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
03-17 11:16:44.883  4069  4069 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
03-17 11:16:44.883  4069  4069 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
03-17 11:16:44.883  4069  4069 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
03-17 11:16:44.883  4069  4069 W System.err: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
,03-17 11:16:44.883  4069  4069 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 11:16:44.883  4069  4069 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 11:16:44.883  4069  4069 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-17 11:16:44.883  4069  4069 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 11:16:44.883  4069  4069 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 11:16:44.883  4069  4069 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 11:16:44.883  4069  4069 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 11:16:44.883  4069  4069 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-17 11:16:44.893  4069  4069 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 11:16:44.893  4069  4069 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 11:16:44.893  4069  4069 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 11:16:44.903  4147  4147 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 11:16:44.903  4128  4128 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
03-17 11:16:44.903  4147  4147 D ActivityThread: Added TimaKeyStore provider
,03-17 11:16:44.903  1019  3389 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:44.903  1019  3389 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 11:16:44.903  1019  3389 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,03-17 11:16:44.913  1019  3388 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:44.913  1019  3388 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:44.913  1019  3388 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 11:16:44.913  1019  3388 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 11:16:44.923  4128  4128 I F_PHONE : [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
03-17 11:16:44.923  1019  1403 F PackageManager: Package Manager Crash
03-17 11:16:44.923  1019  1403 F PackageManager: java.lang.NullPointerException: Attempt to invoke virtual method 'void android.util.XmlMoreAtomicFile.failWrite(java.io.FileOutputStream)' on a null object reference
03-17 11:16:44.923  1019  1403 F PackageManager: 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1668)
03-17 11:16:44.923  1019  1403 F PackageManager: 	at com.android.server.pm.PackageManagerService.setEnabledSetting(PackageManagerService.java:17048)
03-17 11:16:44.923  1019  1403 F PackageManager: 	at com.android.server.pm.PackageManagerService.setComponentEnabledSetting(PackageManagerService.java:16893)
03-17 11:16:44.923  1019  1403 F PackageManager: 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1429)
03-17 11:16:44.923  1019  1403 F PackageManager: 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2985)
03-17 11:16:44.923  1019  1403 F PackageManager: 	at android.os.Binder.execTransact(Binder.java:461)
,03-17 11:16:44.923  4128  4128 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,03-17 11:16:44.923   295   295 E SMD     : DCD OFF,
,03-17 11:16:44.943  4163  4163 E Zygote  : MountEmulatedStorage()
03-17 11:16:44.943  4163  4163 I libpersona: KNOX_SDCARD checking this for 1000
03-17 11:16:44.943  4163  4163 E Zygote  : v2
03-17 11:16:44.943  4163  4163 I libpersona: KNOX_SDCARD not a persona
,03-17 11:16:44.943  4163  4163 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 11:16:44.943  1019  3388 I ActivityManager: Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=4163 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 11:16:44.943  4163  4163 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 11:16:44.943  4163  4163 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 11:16:44.953  2164  4135 I SystemUpdateService: cancelUpdate (empty URL)
03-17 11:16:44.953  2164  4135 I SystemUpdateService: active receiver: disabled
03-17 11:16:44.953  1019  1044 W libprocessgroup: failed to open /acct/uid_10088/pid_3303/cgroup.procs: No such file or directory
03-17 11:16:44.953  4069  4069 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 11:16:44.953  4069  4069 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 11:16:44.953  4069  4069 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 11:16:44.963  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:44.963  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 11:16:44.963  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,03-17 11:16:44.973  1019  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3320/cgroup.procs: No such file or directory
,03-17 11:16:44.973  1019  1045 E DropBoxManagerService: Can't write: system_server_wtf
03-17 11:16:44.973  1019  1045 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop29.tmp: open failed: EROFS (Read-only file system)
03-17 11:16:44.973  1019  1045 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-17 11:16:44.973  1019  1045 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-17 11:16:44.973  1019  1045 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-17 11:16:44.973  1019  1045 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-17 11:16:44.973  1019  1045 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-17 11:16:44.973  1019  1045 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
03-17 11:16:44.973  1019  1045 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:15891)
03-17 11:16:44.973  1019  1045 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:15704)
03-17 11:16:44.973  1019  1045 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15676)
03-17 11:16:44.973  1019  1045 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 11:16:44.973  1019  1045 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 11:16:44.973  1019  1045 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:145)
03-17 11:16:44.973  1019  1045 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 11:16:44.973  1019  1045 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
03-17 11:16:44.973  1019  1045 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-17 11:16:44.973  1019  1045 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-17 11:16:44.973  1019  1045 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-17 11:16:44.973  1019  1045 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-17 11:16:44.973  1019  1045 E DropBoxManagerService: 	... 13 more
,03-17 11:16:44.983  4163  4163 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 11:16:44.983  4163  4163 D ActivityThread: Added TimaKeyStore provider
03-17 11:16:44.983  1019  1403 W ActivityManager: userId = 0, bbcId = -10000
03-17 11:16:44.983  1019  1403 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-17 11:16:44.983  1019  1403 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 11:16:44.983  2164  4005 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
03-17 11:16:44.983  2164  4005 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM0KRjS36UR
03-17 11:16:44.983  2164  4005 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
03-17 11:16:44.983  2164  4005 I GCore-Chimera-Crash: ==
03-17 11:16:44.983  2164  4005 I GCore-Chimera-Crash: GCore-Chimera-Crash
,03-17 11:16:44.993  4128  4128 D F_PHONE : [[com.sec.bcservice]] onServiceConnected()
03-17 11:16:44.993  4128  4128 I F_PHONE : default registerAction()
03-17 11:16:44.993  4069  4069 W ResourcesManager: Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
03-17 11:16:44.993  4128  4128 I F_PHONE : [[com.sec.bcservice]] sendPendingMessage()
03-17 11:16:44.993  4069  4069 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 11:16:44.993  2164  4005 E AndroidRuntime: FATAL EXCEPTION: IntentService[BootCompletedBroadcastService]
03-17 11:16:44.993  2164  4005 E AndroidRuntime: Process: com.google.android.gms, PID: 2164
03-17 11:16:44.993  2164  4005 E AndroidRuntime: java.lang.NullPointerException: Attempt to invoke virtual method 'void android.util.XmlMoreAtomicFile.failWrite(java.io.FileOutputStream)' on a null object reference
03-17 11:16:44.993  2164  4005 E AndroidRuntime: 	at android.os.Parcel.readException(Parcel.java:1546)
03-17 11:16:44.993  2164  4005 E AndroidRuntime: 	at android.os.Parcel.readException(Parcel.java:1493)
03-17 11:16:44.993  2164  4005 E AndroidRuntime: 	at android.content.pm.IPackageManager$Stub$Proxy.setComponentEnabledSetting(IPackageManager.java:4113)
03-17 11:16:44.993  2164  4005 E AndroidRuntime: 	at android.app.ApplicationPackageManager.setComponentEnabledSetting(ApplicationPackageManager.java:1905)
03-17 11:16:44.993  2164  4005 E AndroidRuntime: 	at com.google.android.gms.common.util.c.a(:com.google.android.gms:767)
03-17 11:16:44.993  2164  4005 E AndroidRuntime: 	at com.google.android.gms.common.util.c.a(:com.google.android.gms:785)
03-17 11:16:44.993  2164  4005 E AndroidRuntime: 	at com.google.android.gms.f.c.a(:com.google.android.gms:20)
03-17 11:16:44.993  2164  4005 E AndroidRuntime: 	at com.google.android.gms.f.b.a(:com.google.android.gms:70)
03-17 11:16:44.993  2164  4005 E AndroidRuntime: 	at com.google.android.gms.app.service.BootCompletedBroadcastService.onHandleIntent(:com.google.android.gms:107)
03-17 11:16:44.993  2164  4005 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 11:16:44.993  2164  4005 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 11:16:44.993  2164  4005 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
03-17 11:16:44.993  2164  4005 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 11:16:44.993  4163  4163 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.

```
