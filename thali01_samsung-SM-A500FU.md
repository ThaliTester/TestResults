#### Test 63036995fb62ea7_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
03-17 07:10:34.334  1238  2976 D MediaScanner: Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
03-17 07:10:34.334  1020  2934 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:34.334  1020  2934 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:34.334  1020  2934 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
--------- beginning of system
03-17 07:10:34.334  1020  2934 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
03-17 07:10:34.334  1020  2934 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
03-17 07:10:34.354  1311  1311 I WifiCredService: onCreate
03-17 07:10:34.354  1020  1307 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:34.354  1020  1307 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:34.354  1020  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
03-17 07:10:34.354  3090  3090 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:34.354  3090  3090 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:34.354  1020  1307 D ActivityManager: startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
03-17 07:10:34.354  1020  1307 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
03-17 07:10:34.374  1238  2976 V MediaScanner: processDirectory :  /storage/emulated/0
03-17 07:10:34.374  1020  1344 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:34.374  1020  1344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:34.374  1020  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.samsung.android.providers.context
03-17 07:10:34.374  1020  1344 D ActivityManager: startService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.samsung.android.providers.context
03-17 07:10:34.374  1020  1344 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.providers.context/com.samsung.android.providers.context.ContextService; callingUser = 0; userId(target) = 0
03-17 07:10:34.374  1020  1130 D ActivityManager: startProcessLocked calleePkgName: com.sec.dsm.system, hostingType: broadcast
03-17 07:10:34.384  1238  2976 D MediaScanner: Skipping:
03-17 07:10:34.384  1238  2976 D MediaScanner: 7klwibgf7fvntblfd7(75ebcf7
03-17 07:10:34.384  1238  2976 D MediaScanner: Skipping:
03-17 07:10:34.384  1238  2976 D MediaScanner: 7klwibgf7fvntblfd7(7Budiwrd7dblb7
03-17 07:10:34.384  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.384  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.384  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.384  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.394  3116  3116 E Zygote  : MountEmulatedStorage()
03-17 07:10:34.394  3116  3116 E Zygote  : v2
03-17 07:10:34.394  3116  3116 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 07:10:34.394  3116  3116 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:34.394  3116  3116 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:34.404  3116  3116 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:34.404  3116  3116 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:34.404  1238  2976 V MediaScanner: processDirectory :  /storage/extSdCard
03-17 07:10:34.404  1238  2976 W MediaScanner: Error opening directory, reason : Permission denied.
,03-17 07:10:34.404  1238  2976 W MediaScanner: 7klwibgf7fxlKdCbid7
03-17 07:10:34.404  1020  1130 I ActivityManager: Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3116 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 07:10:34.404  1238  2976 V MediaScanner:  prescan time: 65ms (DB items: 27)
03-17 07:10:34.404  1238  2976 V MediaScanner:     scan time: 35ms (Caching mode: true), (makeEntry time: 26ms ~74%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-17 07:10:34.404  1238  2976 V MediaScanner: postscan time: 2ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-17 07:10:34.404  1238  2976 V MediaScanner:    total time: 102ms
03-17 07:10:34.404  1238  2976 V MediaScanner: checked files: 10  directories : 17  (I: 0, U: 0)
03-17 07:10:34.414  1470  1774 I art     : Explicit concurrent mark sweep GC freed 34727(2MB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 7MB/13MB, paused 1.012ms total 153.003ms
03-17 07:10:34.414  1238  2976 D MediaScannerService: !@done scanning volume external
03-17 07:10:34.424  1470  1470 I CscUtil : isWifiOnly = false
03-17 07:10:34.424  2663  2663 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2663) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-17 07:10:34.424  1470  1774 D TP/SmsProvider: query,matched:51, calling pid = 2333
03-17 07:10:34.424  2663  2663 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2663) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
03-17 07:10:34.424  2663  2663 D FactoryTestApp: [DummyFtClient$sendBootCompletedAndFinish](2663) ...
03-17 07:10:34.424  2663  2663 D FactoryTestApp: [Support$Values.getString](2663) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 07:10:34.424  2663  2663 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2663) mConnectionMode = gsm
03-17 07:10:34.424  2663  2663 D FactoryTestApp: [IPCWriterToSecPhoneService$ResponseWriter](2663) Create IPCWriterToSecPhoneService
03-17 07:10:34.424  2663  2663 I FactoryTestApp: [IPCWriterToSecPhoneService$connectToSecPhoneService](2663)  
03-17 07:10:34.424  2663  2663 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
03-17 07:10:34.424  1470  1470 I System.out: HandDataNode = null
03-17 07:10:34.424  1020  1491 D ActivityManager: bindService callerProcessName:com.sec.factory, calleePkgName: com.sec.phone, action: null
03-17 07:10:34.424  1470  1470 I CscUpdateService: PATH_CSCNAME =CustomerDataSet.CSCName
03-17 07:10:34.424  1020  1491 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
03-17 07:10:34.424  3090  3090 I Intent to TravelDirActivity: inside TravelBroadcastReceiver
03-17 07:10:34.434  1311  1311 D WifiTimerReceiver: action: android.intent.action.BOOT_COMPLETED
03-17 07:10:34.434  1311  1311 D WifiTimerReceiver: extra: Bundle[mParcelledData.dataSize=84]
03-17 07:10:34.434  1311  1311 D MY_TAG  : Action boot completed received
03-17 07:10:34.434  1470  1490 D TP/SmsProvider: query,matched:26, calling pid = 2333
03-17 07:10:34.434  1470  1470 I CscUpdateService: This is normal boot : CSC not updated
03-17 07:10:34.434  1470  1774 D TP/SmsProvider: match 51:Elapsed time : 1.604 ms
03-17 07:10:34.434  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:34.434  1020  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:34.434  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
03-17 07:10:34.444  3034  3108 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
03-17 07:10:34.454  1470  3132 E CscParser: update(): xml file exist
03-17 07:10:34.454  2076  3085 I iu.UploadsManager: #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
03-17 07:10:34.464  1470  3132 D CscGPS  : CSCGPS.updateParameters
03-17 07:10:34.464  1470  3132 D CscGPS  : supl host : null
03-17 07:10:34.464  1470  3132 D CscGPS  : SUPL Host is null or invalid
03-17 07:10:34.464  1470  3132 D CscGPS  : supl_ver : null
03-17 07:10:34.464  1470  3132 D CscGPS  : SUPL Ver is null or invalid
03-17 07:10:34.464  1470  3132 D CscGPS  : supl port : null
03-17 07:10:34.464  1470  3132 D CscGPS  : SUPL PORT is null or invalid
03-17 07:10:34.464  1470  3132 D CscGPS  : LPP : null
03-17 07:10:34.464  1470  3132 D CscGPS  : LPP is null or invalid
03-17 07:10:34.464  1470  3132 D CscGPS  : CSC don't have any AGPS value.
03-17 07:10:34.464  1311  1311 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
03-17 07:10:34.464  1470  1490 D TP/SmsProvider: match 26:Elapsed time : 30.693 ms
03-17 07:10:34.464  1020  2880 D ActivityManager: startProcessLocked calleePkgName: com.sec.usbsettings, hostingType: broadcast
03-17 07:10:34.464  1020  1135 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
03-17 07:10:34.464  1020  1135 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-17 07:10:34.464  1020  1135 E WifiNative-wlan0: invaild command id : 215
03-17 07:10:34.474  1470  1470 I CscUpdateService: same CSC Version
03-17 07:10:34.474  1470  1470 D CscUtil : Set Build Fingerprint to samsung/a5ultexx/a5ulte:5.0.2/LRX22G/A500FUXXU1BOH2:user/release-keys
03-17 07:10:34.474  3034  3108 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
03-17 07:10:34.474   385   385 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 10003, gid 10003, pid 3034
03-17 07:10:34.474   385   385 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
03-17 07:10:34.474  3034  3108 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
03-17 07:10:34.474  3034  3108 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
03-17 07:10:34.484   385   385 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 10003, gid 10003, pid 3034
03-17 07:10:34.484   385   385 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
03-17 07:10:34.494  3116  3116 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:34.494  3116  3116 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:34.494  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.494  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.494  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.494  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.504  3143  3143 E Zygote  : MountEmulatedStorage()
03-17 07:10:34.504  3143  3143 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:34.504  3143  3143 E Zygote  : v2
03-17 07:10:34.504  3143  3143 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:34.504  3143  3143 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 07:10:34.514  1020  2880 I ActivityManager: Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=3143 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 07:10:34.514  3143  3143 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:34.514  3143  3143 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:34.544  3016  3016 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 226.590ms
03-17 07:10:34.554  3143  3143 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:34.554  2663  2663 I FactoryTestApp: [IPCWriterToSecPhoneService$onServiceConnected](2663) connected done
03-17 07:10:34.554  2663  2663 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2663) Send Response Message to SecPhone
03-17 07:10:34.554  2663  2663 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2663) Response ��
03-17 07:10:34.554  3143  3143 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:34.574  1311  1311 D NearbySettings: MountReceiver.onReceive - Create HandlerThread
03-17 07:10:34.574  1311  1311 D NearbySettings: MountReceiver.onReceive - Start HandlerThread
03-17 07:10:34.574  1311  1311 D NearbySettings: MountReceiver.onReceive - Create mPrefHandler
03-17 07:10:34.574  2333  3042 D Mms/SmsReceiver: unregisterForServiceStateChanges, already unregistered
03-17 07:10:34.574  2333  3042 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-17 07:10:34.574  2333  3042 D Mms/TelephonyPermission: isDefault true
03-17 07:10:34.584  2333  3003 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
03-17 07:10:34.594   319  1077 D AT_Distributor: Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
03-17 07:10:34.604  1311  1311 D NearbySettings: MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
03-17 07:10:34.604  1311  3159 V NearbySettings: MountReceiver.mPrefHandler - 7002
03-17 07:10:34.604  1020  2934 D SettingsProvider: name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
03-17 07:10:34.614  2663  2663 D FactoryTestApp: [IPCWriterToSecPhoneService$handleMessage](2663) Send BOOTING COMPLETED done
03-17 07:10:34.634  1577  1585 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
03-17 07:10:34.634  1470  1484 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2333
03-17 07:10:34.634  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 07:10:34.654  1020  1344 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
03-17 07:10:34.664  1020  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.664  1492  1492 D Launcher.Model: reloadBadges entered.
03-17 07:10:34.664  1577  1585 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-17 07:10:34.664  1020  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.664  1020  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.664  1020  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.664  1577  1585 D BadgeProvider: sendNotify, [notify] : null
03-17 07:10:34.664  1577  1585 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 07:10:34.664  1577  1585 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 07:10:34.664  1577  1585 D BadgeProvider: update, [UpdateCount] : 1
03-17 07:10:34.684  1311  1311 I NearbySettings: MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
03-17 07:10:34.684  1311  1311 I NearbySettings: MountReceiver.onReceive - Internal Path
03-17 07:10:34.684  3161  3161 E Zygote  : MountEmulatedStorage()
03-17 07:10:34.684  3161  3161 E Zygote  : v2
03-17 07:10:34.684  3161  3161 I libpersona: KNOX_SDCARD checking this for 10160
03-17 07:10:34.684  3161  3161 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:34.684  3161  3161 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 07:10:34.694  1020  1344 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3161 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
03-17 07:10:34.694  1020  1344 I ActivityManager: Killing 2249:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
03-17 07:10:34.694  2687  2765 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
03-17 07:10:34.704   319  1077 D AT_Distributor: SetAtdStatus(), 1_1_0
03-17 07:10:34.704   319  1077 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
03-17 07:10:34.704  3161  3161 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:34.704  3161  3161 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:34.704  3141  3141 D AndroidRuntime: 
03-17 07:10:34.704  3141  3141 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 07:10:34.714  3141  3141 D AndroidRuntime: CheckJNI is OFF
03-17 07:10:34.714  3141  3141 D AndroidRuntime: readGMSProperty: start
03-17 07:10:34.714  3141  3141 D AndroidRuntime: readGMSProperty: already setted!!
03-17 07:10:34.714  3141  3141 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 07:10:34.714  3141  3141 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 07:10:34.714  3141  3141 D AndroidRuntime: readGMSProperty: end
03-17 07:10:34.714  3141  3141 D AndroidRuntime: addProductProperty: start
03-17 07:10:34.724   309   309 I art     : Explicit concurrent mark sweep GC freed 8733(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 636us total 39.786ms
03-17 07:10:34.744  3161  3161 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:34.744  3161  3161 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:34.744  1020  1130 D SettingsProvider: name = personal_mode_enabled
03-17 07:10:34.754   296   296 E USB_UICC: Timeout! No signal received. Retry num = 30
03-17 07:10:34.754   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 616us total 21.101ms
03-17 07:10:34.754  2687  2765 D BluetoothMediaBrowser: no now playing list
03-17 07:10:34.754  2687  2765 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
03-17 07:10:34.764  2333  3003 D Mms/MessagingNotification: setBadgeCount(), count=0
03-17 07:10:34.764   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 17.287ms
03-17 07:10:34.764  1020  2934 I ActivityManager: Killing 1625:com.google.android.partnersetup/u0a15 (adj 15): empty #31
03-17 07:10:34.774  2076  3085 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 324 ms
03-17 07:10:34.784   327   327 I ServiceManager: Waiting for service AtCmdFwd...
03-17 07:10:34.794  2333  3003 D Mms/MessagingNotification: remove alarm
03-17 07:10:34.804  3161  3161 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 07:10:34.804  1470  1800 D TP/MmsSmsProvider: query,matched:200, calling pid = 2333
03-17 07:10:34.814  1470  1800 D TP/MmsSmsProvider: match 200:Elapsed time : 4.808 ms
03-17 07:10:34.824  2333  3185 D Mms/MessagingNotification: updateAllHistoryAsRead()
03-17 07:10:34.834  1470  1470 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 07:10:34.834  1470  1470 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 07:10:34.834  1470  1470 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 07:10:34.834  1470  1470 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:34.834  1470  1470 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:34.834  1470  1470 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-17 07:10:34.854  1311  1311 I SmartcardBootCompleteReceiver: SmartcardBootCompleteReceiver - onReceive() 
03-17 07:10:34.854  1311  1311 I SmartcardBootCompleteReceiver: Received intent with action - android.intent.action.BOOT_COMPLETED
03-17 07:10:34.864  3116  3116 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
03-17 07:10:34.884  3141  3141 E AffinityControl: AffinityControl: registerfunction enter
03-17 07:10:34.904  1311  1311 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
03-17 07:10:34.904  1311  1311 I SmartcardBootCompleteReceiver: Broadcast sent with current lockscreen type
03-17 07:10:34.904  3141  3141 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 07:10:34.914   296   296 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-17 07:10:34.914   296   296 E USB_UICC: usb_uicc_init_qmi failed ! 
03-17 07:10:34.914   296   296 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
03-17 07:10:34.914   296   296 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
03-17 07:10:34.924  1020  1032 E PersonaManagerService: inState():  stateMachine is null !!
03-17 07:10:34.924  1020  1032 I PersonaManagerService: PersonaId don't exist
03-17 07:10:34.924  1020  1032 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-17 07:10:34.934  3116  3116 D DSM     : [Lines:107] Normal booted
03-17 07:10:34.944  3116  3116 D DSM     : [Lines:114] Boot completed
03-17 07:10:34.944  1020  1044 W libprocessgroup: failed to open /acct/uid_10015/pid_1625/cgroup.procs: No such file or directory
03-17 07:10:34.944  1020  1044 W libprocessgroup: failed to open /acct/uid_10113/pid_2249/cgroup.procs: No such file or directory
03-17 07:10:34.944  1020  1032 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 07:10:34.954  1020  1032 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-17 07:10:34.954  1020  1032 W ActivityManager: mDVFSHelper.acquire()
03-17 07:10:34.974  1020  1032 D FocusedStackFrame: Set to : 0
03-17 07:10:34.974  1492  1492 D Launcher.HomeView: onPause
03-17 07:10:34.974  1020  1032 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 07:10:34.974  1020  1032 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 07:10:34.974  1020  1032 D InputDispatcher: Focused application set to: xxxx
03-17 07:10:34.974  1020  1032 D InputDispatcher: Focus left window: 1492
03-17 07:10:34.974  1492  1492 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-17 07:10:34.974  1020  2880 I art     : Explicit concurrent mark sweep GC freed 20185(1026KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 26MB/39MB, paused 4.363ms total 159.391ms
03-17 07:10:34.984  3141  3141 D AndroidRuntime: Shutting down VM
03-17 07:10:34.984  1020  1130 D ActivityManager: bindService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.gms, action: null
03-17 07:10:34.984  1020  1130 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
03-17 07:10:34.984  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:34.984  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:34.984  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
03-17 07:10:34.994  1020  1052 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 07:10:34.994  1020  1052 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-17 07:10:34.994  1470  1702 D TP/SmsProvider: query,matched:0, calling pid = 2333
03-17 07:10:34.994  1020  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.994  1020  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.994  1020  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:34.994  1020  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.004  1020  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 07:10:35.004  1020  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 07:10:35.004  1311  1311 D [SBeam] : SBeamEnabler.initPreferenceForSbeam : 0
03-17 07:10:35.004  1020  1052 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 07:10:35.004  1020  1052 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 07:10:35.004  1470  1702 D TP/SmsProvider: match 0:Elapsed time : 6.629 ms
03-17 07:10:35.004   257   257 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-17 07:10:35.014  3196  3196 E Zygote  : MountEmulatedStorage()
03-17 07:10:35.014  3196  3196 I libpersona: KNOX_SDCARD checking this for 10155
03-17 07:10:35.014  3196  3196 E Zygote  : v2
03-17 07:10:35.014  3196  3196 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:35.014  3196  3196 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 07:10:35.014  3161  3161 D [0]UMC:UMCContentProvider: @onCreate
03-17 07:10:35.024  3196  3196 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:35.024  3196  3196 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 07:10:35.024  1020  1516 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3196 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 07:10:35.024  1020  2880 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.factorykeystring, hostingType: broadcast
03-17 07:10:35.034  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.034  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.034  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.034  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.054  3207  3207 E Zygote  : MountEmulatedStorage()
03-17 07:10:35.054  3207  3207 E Zygote  : v2
03-17 07:10:35.054  3207  3207 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:35.054  3207  3207 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:35.054  3207  3207 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 07:10:35.054  1020  2880 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3207 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 07:10:35.054  3207  3207 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:35.054  1020  2880 I ActivityManager: Killing 2314:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
03-17 07:10:35.054  3207  3207 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:35.054  3196  3196 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:35.054  3196  3196 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:35.064  1492  1492 V ActivityThread: updateVisibility : ActivityRecord{2e23df12 token=android.os.BinderProxy@23a6a89a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-17 07:10:35.074  1020  2933 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 07:10:35.074  1020  2933 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 07:10:35.074  1020  2933 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 07:10:35.074  1470  1800 D TP/SmsProvider: query,matched:0, calling pid = 2333
03-17 07:10:35.074  1470  1800 D TP/SmsProvider: match 0:Elapsed time : 1.159 ms
03-17 07:10:35.074  1311  1311 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
03-17 07:10:35.074  1311  1311 I SettingSearch/SearchIntentReceiver: search setting db init!!
03-17 07:10:35.084  1492  1492 D Launcher.HomeView: onStop
03-17 07:10:35.084  1020  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 07:10:35.084  1492  1492 D Launcher: onTrimMemory. Level: 20
03-17 07:10:35.084  1492  1492 V ActivityThread: updateVisibility : ActivityRecord{2e23df12 token=android.os.BinderProxy@23a6a89a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-17 07:10:35.084  1311  1311 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
03-17 07:10:35.084  3207  3207 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:35.084  3207  3207 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:35.084  1020  2933 D PersonaManager: isKioskContainerExistOnDevice
03-17 07:10:35.094  1020  2880 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.colorblind, hostingType: broadcast
03-17 07:10:35.094  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.094  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.094  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.094  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.114  3226  3226 E Zygote  : MountEmulatedStorage()
03-17 07:10:35.114  3226  3226 E Zygote  : v2
03-17 07:10:35.114  3226  3226 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:35.114  3226  3226 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:35.114  3226  3226 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 07:10:35.124  1020  2880 I ActivityManager: Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3226 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 07:10:35.124  3226  3226 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:35.124  1020  2880 I ActivityManager: Killing 2352:com.sec.android.omc/1000 (adj 15): empty #31
03-17 07:10:35.124  3226  3226 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:35.134  1311  3234 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
03-17 07:10:35.144  2333  3003 D Mms/MessagingNotification: [end]    nonBlockingUpdateMessageIndicator() consume time = 1033.959427
03-17 07:10:35.144  1020  1344 I ActivityManager: Killing 2382:com.sec.tcpdumpservice/1000 (adj 15): empty #31
03-17 07:10:35.154  1020  1020 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-17 07:10:35.154  1020  1020 D SensorService: [SO] activate (ident=0xb883cd88, enabled=0)
03-17 07:10:35.154  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-17 07:10:35.154  3161  3161 D [0]UMC:Core: onCreate(): 
03-17 07:10:35.154  3161  3161 D [0]UMC:Core: @isManagedProfileUser
03-17 07:10:35.154  3161  3161 D [0]UMC:Core: userId: 0
03-17 07:10:35.154  1020  1020 D SensorManager: unregisterListener ::   
03-17 07:10:35.154  1020  1020 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
03-17 07:10:35.164  1020  1020 D SensorService: [SO] changed settle time [1]
03-17 07:10:35.164  1020  1020 D SensorService: [SO] setDelay [66000000]
03-17 07:10:35.164  1020  1020 D SensorService: [SO] activate (ident=0xb84b2270, enabled=1)
03-17 07:10:35.164  1020  1020 D SensorService: [SO] AR_init
03-17 07:10:35.164  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
03-17 07:10:35.164  3207  3207 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 07:10:35.164  3226  3226 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:35.164  3226  3226 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:35.164  3161  3161 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
03-17 07:10:35.164  3161  3161 D [0]UMC:Core: userInfo.isManagedProfile() : false
03-17 07:10:35.164  1020  1020 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
03-17 07:10:35.184  1020  1098 V AlarmManager: waitForAlarm result :8
03-17 07:10:35.194  3141  3141 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-17 07:10:35.194  3161  3161 D [0]UMC:DeviceInfo: USA==US==
,03-17 07:10:35.224  3207  3207 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 07:10:35.234  1020  1042 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 07:10:35.234  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
,03-17 07:10:35.234  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
,03-17 07:10:35.234  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2314/cgroup.procs: No such file or directory
03-17 07:10:35.234  3207  3207 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
,03-17 07:10:35.254  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,03-17 07:10:35.264  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-17 07:10:35.264  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-17 07:10:35.264  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-17 07:10:35.264  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-17 07:10:35.264  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-17 07:10:35.264  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
,03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
,03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
,03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
,03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
,03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
,03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT,
03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV,
03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
,03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
,03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
,03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
,03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
,03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
,03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
,03-17 07:10:35.274  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
03-17 07:10:35.284  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
,03-17 07:10:35.284  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA,
,03-17 07:10:35.284  3207  3207 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
03-17 07:10:35.284   385   385 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,03-17 07:10:35.284  3207  3207 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N,
,03-17 07:10:35.304  1020  1042 D SensorService: [SO] 0.134 0.402 10.113
,03-17 07:10:35.304  1020  1042 D SensorService: [SO] [100 -> 255]
,03-17 07:10:35.324  3034  3108 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
,03-17 07:10:35.324  3034  3108 I SecureStorage: [INFO]: SPID(0x00000004)Skip using SecureStorageExceptionJNI
,03-17 07:10:35.344  1020  1344 D ActivityManager: startProcessLocked calleePkgName: com.wssyncmldm, hostingType: broadcast
,03-17 07:10:35.344  1020  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.344  1020  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.344  1020  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.344  1020  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:35.364  3226  3226 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
,03-17 07:10:35.364  3245  3245 E Zygote  : MountEmulatedStorage()
03-17 07:10:35.364  3245  3245 E Zygote  : v2
03-17 07:10:35.364  3245  3245 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:35.364  3245  3245 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:35.364  3245  3245 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:35.374  1020  1344 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3245 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:35.374  3161  3161 D USER_AGENT: UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
03-17 07:10:35.374  3245  3245 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:35.374  3245  3245 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:35.394  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2382/cgroup.procs: No such file or directory
,03-17 07:10:35.394  1020  1098 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:35.394  1020  1130 D ActivityManager: getContentProviderImpl callerProcessName:com.android.settings, calleePkgName: com.sec.providers.settingsearch
,03-17 07:10:35.404  3161  3161 D [0]UMC:AdminManager: init - start
,03-17 07:10:35.414  1470  2140 D TP/SmsProvider: query,matched:51, calling pid = 2333
03-17 07:10:35.414  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.414  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.414  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.414  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:35.414  3196  3196 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-17 07:10:35.414  1470  2140 D TP/SmsProvider: match 51:Elapsed time : 2.584 ms
,03-17 07:10:35.424  3260  3260 E Zygote  : MountEmulatedStorage()
,03-17 07:10:35.424  3260  3260 E Zygote  : v2
03-17 07:10:35.424  3260  3260 I libpersona: KNOX_SDCARD checking this for 10150
03-17 07:10:35.424  3260  3260 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:35.424  3260  3260 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:35.424  3260  3260 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:35.424  1020  1130 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3260 uid=10150 gids={50150, 9997} abi=armeabi-v7a
03-17 07:10:35.424  3260  3260 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 07:10:35.434  3245  3245 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:35.434  3245  3245 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:35.434  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2352/cgroup.procs: No such file or directory
,03-17 07:10:35.434  1020  1344 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
03-17 07:10:35.434  1020  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.434  1020  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.434  1020  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.434  1020  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:35.434  3161  3161 D [0]UMC:AdminManager: loadAdmins
,03-17 07:10:35.454  3161  3161 D [0]UMC:AdminManager: init - end
03-17 07:10:35.454  3161  3161 D GSLBManager: migrateStoredUrlFromOldPref
03-17 07:10:35.454  3274  3274 E Zygote  : MountEmulatedStorage()
03-17 07:10:35.454  3274  3274 E Zygote  : v2
03-17 07:10:35.454  3274  3274 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:35.454  3274  3274 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:35.454  3274  3274 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 07:10:35.454  3274  3274 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:35.454  3274  3274 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:35.464  1020  1344 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3274 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 07:10:35.474  3161  3161 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
03-17 07:10:35.474  3260  3260 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:35.474  3260  3260 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:35.474  3161  3161 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-17 07:10:35.484  1020  1491 I ActivityManager: Killing 2397:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,03-17 07:10:35.484  3196  3196 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 7456-7462)
03-17 07:10:35.484  3196  3196 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 07:10:35.484  3161  3161 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-17 07:10:35.494  3161  3161 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-17 07:10:35.494  3161  3161 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-17 07:10:35.494  3161  3161 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 07:10:35.494  3274  3274 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:35.504  3274  3274 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:35.504  1020  1491 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-17 07:10:35.504  3161  3161 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
03-17 07:10:35.504  3161  3161 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 07:10:35.514  3161  3161 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-17 07:10:35.514  1020  1362 D ActivityManager: startProcessLocked calleePkgName: com.google.android.configupdater, hostingType: broadcast
,03-17 07:10:35.514  2333  3042 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
,03-17 07:10:35.514  3245  3245 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:35.514  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.514  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.514  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.514  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:35.534  3294  3294 E Zygote  : MountEmulatedStorage()
03-17 07:10:35.534  3294  3294 E Zygote  : v2
03-17 07:10:35.534  3294  3294 I libpersona: KNOX_SDCARD checking this for 10086
03-17 07:10:35.534  3294  3294 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:35.534  3294  3294 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:35.534  3294  3294 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:35.534  3294  3294 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,03-17 07:10:35.544  1020  1362 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3294 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a,
,03-17 07:10:35.544  3196  3196 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {197f509b},
,03-17 07:10:35.544  3196  3196 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 07:10:35.544  3196  3196 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,03-17 07:10:35.544   257   451 I SurfaceFlinger: id=9 Removed Mauncher (5/8)
,03-17 07:10:35.544   257   802 I SurfaceFlinger: id=9 Removed Mauncher (-2/8)
,03-17 07:10:35.544  1020  1044 W libprocessgroup: failed to open /acct/uid_10131/pid_2397/cgroup.procs: No such file or directory
,03-17 07:10:35.564  3294  3294 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:35.564  3294  3294 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:35.584  3196  3196 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-17 07:10:35.584  3196  3196 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 07:10:35.584  3196  3196 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 07:10:35.594  1020  1344 D ActivityManager: startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
,03-17 07:10:35.594  1020  1344 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,03-17 07:10:35.594  1020  1344 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:35.594  1020  1344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:35.594  1020  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-17 07:10:35.604  3161  3161 D [0]UMC:GuardService: @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
,03-17 07:10:35.604  1577  1585 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
03-17 07:10:35.604  3161  3161 D [0]UMC:CoreReceiver: Intent : android.intent.action.BOOT_COMPLETED
03-17 07:10:35.604  3161  3161 D [0]UMC:CoreReceiver:  check PreETag 
,03-17 07:10:35.614  3196  3196 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,03-17 07:10:35.614  3196  3196 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
03-17 07:10:35.614  3196  3196 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,03-17 07:10:35.624  3196  3196 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 07:10:35.624  3196  3196 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 07:10:35.624  3196  3196 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 07:10:35.624  3196  3196 I Adreno-EGL: Local Branch: 
03-17 07:10:35.624  3196  3196 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 07:10:35.624  3196  3196 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 07:10:35.624  3196  3196 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 07:10:35.634  1020  1032 I ActivityManager: Killing 2304:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-17 07:10:35.674  3161  3161 D [0]UMC:CoreReceiver: bulk enrolled package: null
,03-17 07:10:35.674  3161  3161 V [0]UMC:ProfileStorage: Enter loadList
,03-17 07:10:35.674  3161  3161 D [0]UMC:CoreReceiver: handleAutoEnrollmentAndUMCAdminDeactivation
03-17 07:10:35.674  3161  3161 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-17 07:10:35.674  3161  3161 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-17 07:10:35.674  3161  3161 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
,03-17 07:10:35.674  3161  3161 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-17 07:10:35.674  3161  3161 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 07:10:35.684  1020  2931 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-17 07:10:35.684  3161  3161 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
,03-17 07:10:35.684  3161  3161 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 07:10:35.684  3161  3161 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-17 07:10:35.714  3161  3161 D [0]UMC:ByodSetupStarter: Container ID : 0
,03-17 07:10:35.714  3161  3161 V [0]UMC:Utils: checkAppScreen() : com.test.thalitest
,03-17 07:10:35.714  3161  3161 I [0]UMC:Core: shutdown
,03-17 07:10:35.714  1020  1516 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,03-17 07:10:35.714  1020  1516 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:35.714  1020  1516 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
03-17 07:10:35.714  1020  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-17 07:10:35.714  3161  3161 D [0]UMC:GuardService: @GuardService - stopService Result = true
,03-17 07:10:35.724  3161  3161 I art     : System.exit called, status: 0
03-17 07:10:35.724  3161  3161 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,03-17 07:10:35.724  2851  3110 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 07:10:35.724  1492  1492 D Launcher.Model: reloadBadges entered.
,03-17 07:10:35.734  3034  3034 E BluetoothHeadset: BTStateChangeCB is registed
,03-17 07:10:35.734   287   287 E SMD     : DCD OFF
,03-17 07:10:35.734  1577  1585 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-17 07:10:35.734  1577  1585 D BadgeProvider: sendNotify, [notify] : null
03-17 07:10:35.734  1577  1585 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 07:10:35.734  1577  1585 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 07:10:35.734  1577  1585 D BadgeProvider: update, [UpdateCount] : 1
03-17 07:10:35.734  2333  3042 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-17 07:10:35.754  3034  3034 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,03-17 07:10:35.754  1020  1362 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
03-17 07:10:35.754  1020  1362 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,03-17 07:10:35.754  1020  1362 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:35.754  1020  1362 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:35.754  1020  1362 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
03-17 07:10:35.754  3034  3034 E BluetoothHeadset: BluetoothHeadset service is binded
03-17 07:10:35.754  3034  3034 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
03-17 07:10:35.754  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2304/cgroup.procs: No such file or directory
03-17 07:10:35.754  2333  3334 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-17 07:10:35.754  1020  1033 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,03-17 07:10:35.754  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,03-17 07:10:35.754  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:35.754  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:35.754  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
03-17 07:10:35.754  2333  3042 D Mms/MessagingNotification: remove alarm
,03-17 07:10:35.774  1470  1800 D TP/SmsProvider: query,matched:0, calling pid = 2333
,03-17 07:10:35.774  1470  1800 D TP/SmsProvider: match 0:Elapsed time : 3.103 ms
,03-17 07:10:35.774  1020  2934 I ActivityManager: Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3161)(adj 0) has died(245,1048)
,03-17 07:10:35.784   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 07:10:35.794  2333  3042 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 646.130937
,03-17 07:10:35.794  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 07:10:35.794  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-17 07:10:35.794  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 07:10:35.804  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 07:10:35.804  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-17 07:10:35.804   277  1015 D EnterpriseController: uids 10120
03-17 07:10:35.804   277  1015 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 07:10:35.804   277  1015 D Netd    : getNetworkForDns: using netid 502 for uid 10120
,03-17 07:10:35.814  1329  1329 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,03-17 07:10:35.814  1329  1329 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 07:10:35.814  1329  1329 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,03-17 07:10:35.814  1329  1329 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-17 07:10:35.814  1329  1329 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 07:10:35.814  1329  1329 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-17 07:10:35.814  1329  1329 D daemonapp: [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,03-17 07:10:35.814  1020  2931 D SettingsProvider: name = aw_daemon_service_key_version_check
,03-17 07:10:35.814  1020  2931 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-17 07:10:35.814  1020  2931 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-17 07:10:35.814  1020  2931 D SettingsProvider: selectionArgs: false
03-17 07:10:35.814  1020  2931 D SettingsProvider: selectionArgs: 10162
03-17 07:10:35.814  1020  2931 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:35.814  1020  2931 D SettingsProvider: ret = -1
,03-17 07:10:35.814  1020  2931 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10162
,03-17 07:10:35.824  3274  3274 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-17 07:10:35.824  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 07:10:35.824  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-17 07:10:35.824  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:35.834  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 07:10:35.834  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 07:10:35.834  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-17 07:10:35.834  3294  3294 E UpdateRequestReceiver: ignoring update request
03-17 07:10:35.834  3034  3034 D BluetoothA2dp: Proxy object connected
,03-17 07:10:35.834  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 07:10:35.844  3294  3294 E UpdateRequestReceiver: ignoring update request
,03-17 07:10:35.844  3245  3245 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,03-17 07:10:35.844  1329  1329 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-17 07:10:35.844  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 07:10:35.854  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1458195035862
,03-17 07:10:35.854  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1458216600000
03-17 07:10:35.854  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
,03-17 07:10:35.854  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,03-17 07:10:35.854  1329  1329 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458216600000
,03-17 07:10:35.884  3196  3322 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,03-17 07:10:35.894  3294  3294 E UpdateRequestReceiver: ignoring update request
,03-17 07:10:35.904  3294  3294 E UpdateRequestReceiver: ignoring update request
,03-17 07:10:35.904  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 47
,03-17 07:10:35.904  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458216600000
,03-17 07:10:35.924  3294  3294 E UpdateRequestReceiver: ignoring update request
,03-17 07:10:35.924  1329  1329 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,03-17 07:10:35.924  1329  1329 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-17 07:10:35.934  1020  2931 D ActivityManager: startProcessLocked calleePkgName: com.google.android.youtube, hostingType: broadcast
,03-17 07:10:35.934  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:35.934  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.934  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:35.934  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:35.944  3294  3294 E UpdateRequestReceiver: ignoring update request
,03-17 07:10:35.954  3357  3357 E Zygote  : MountEmulatedStorage(),
03-17 07:10:35.954  3196  3196 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 07:10:35.954  3357  3357 E Zygote  : v2,
,03-17 07:10:35.954  1020  2931 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3357 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 07:10:35.954  3357  3357 I libpersona: KNOX_SDCARD checking this for 10166
03-17 07:10:35.954  3357  3357 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:35.964  1020  2931 D ActivityManager: startProcessLocked calleePkgName: com.dropbox.android, hostingType: broadcast,
03-17 07:10:35.964  3357  3357 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 07:10:35.964  3357  3357 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:35.964  3357  3357 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 07:10:35.964  3245  3245 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,03-17 07:10:35.974  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.974  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.974  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:35.974  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:35.984  3196  3196 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 07:10:35.984  3357  3357 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:35.994  3357  3357 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:35.994  3370  3370 E Zygote  : MountEmulatedStorage()
,03-17 07:10:35.994  3370  3370 E Zygote  : v2
03-17 07:10:35.994  3370  3370 I libpersona: KNOX_SDCARD checking this for 10092
03-17 07:10:35.994  3370  3370 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:35.994  1020  2931 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3370 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-17 07:10:35.994  3196  3196 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 07:10:35.994  3196  3196 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-17 07:10:35.994  1020  2931 I ActivityManager: Killing 2426:com.wsomacp/u0a25 (adj 15): empty #31
03-17 07:10:35.994  3245  3245 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true,
03-17 07:10:36.004  3245  3245 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
03-17 07:10:36.004  3370  3370 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 07:10:36.004  3370  3370 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:36.004  3196  3196 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-17 07:10:36.004  3370  3370 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 07:10:36.014  3196  3196 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 07:10:36.014  3196  3196 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 07:10:36.034  3274  3274 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-17 07:10:36.044  3370  3370 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:36.044  3370  3370 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:36.054  3274  3274 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-17 07:10:36.084  1020  1044 W libprocessgroup: failed to open /acct/uid_10025/pid_2426/cgroup.procs: No such file or directory
,03-17 07:10:36.124  3274  3274 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,03-17 07:10:36.124  3274  3274 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
,03-17 07:10:36.124  3274  3274 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
,03-17 07:10:36.124  3274  3274 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-17 07:10:36.144  3245  3245 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,03-17 07:10:36.144  3245  3245 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,03-17 07:10:36.144  3245  3245 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,03-17 07:10:36.144  1020  1516 D ActivityManager: startService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm
03-17 07:10:36.144  1020  1516 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,03-17 07:10:36.144  1020  1516 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:36.154  1020  1516 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:36.154  1020  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 07:10:36.154  3245  3245 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,03-17 07:10:36.154  3245  3245 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,03-17 07:10:36.154  3245  3245 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,03-17 07:10:36.164  3245  3245 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,03-17 07:10:36.164  1187  1187 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
,03-17 07:10:36.164  3245  3245 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
03-17 07:10:36.164  1187  1187 D OverheatReceiver: into the SAFE_MODE_ACTION
,03-17 07:10:36.164  1187  1187 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
,03-17 07:10:36.164  3245  3245 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
03-17 07:10:36.164  1187  1187 D OverheatReceiver: isSafeMode = false
,03-17 07:10:36.164  3245  3245 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,03-17 07:10:36.174  3245  3245 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,03-17 07:10:36.174  3245  3245 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,03-17 07:10:36.174  3245  3245 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,03-17 07:10:36.174  3245  3245 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,03-17 07:10:36.174  3245  3245 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
,03-17 07:10:36.174  1470  1470 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
,03-17 07:10:36.184  3245  3353 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
03-17 07:10:36.184  1020  1516 D SettingsProvider: name = internet_call_settings_visibility
03-17 07:10:36.184  1020  1516 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:36.184  1020  1516 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:36.184  1020  1516 D SettingsProvider: selectionArgs: false
03-17 07:10:36.184  1020  1516 D SettingsProvider: selectionArgs: 1001
03-17 07:10:36.184  1020  1516 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:36.184  1020  1516 D SettingsProvider: ret = -1
03-17 07:10:36.184  1470  1470 D PhoneUtilsCommon: isSupportVoLTE is false.
,03-17 07:10:36.184  3245  3245 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,03-17 07:10:36.194  3196  3393 D OpenGLRenderer: Render dirty regions requested: true
,03-17 07:10:36.194  3245  3245 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,03-17 07:10:36.194  3245  3245 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
03-17 07:10:36.194  1445  1445 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,03-17 07:10:36.194  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:36.194  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:36.194  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:36.194  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:36.194  3245  3245 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,03-17 07:10:36.194  1020  2934 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: android.telecom.InCallService
03-17 07:10:36.194  1020  2934 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,03-17 07:10:36.194  1020  2934 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:36.194  1020  2934 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:36.194  1020  2934 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 07:10:36.194  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:36.204  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:36.204  3245  3245 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,03-17 07:10:36.204  1020  2880 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-17 07:10:36.204  1020  2880 D KnoxTimeoutHandler: postActiveUserChange for user 0
,03-17 07:10:36.204  1020  2880 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-17 07:10:36.204  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-17 07:10:36.204  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 07:10:36.204  1020  2883 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: com.samsung.incallui.SEC_IN_CALL_SERVICE
,03-17 07:10:36.204  1020  2883 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,03-17 07:10:36.204  3245  3245 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
,03-17 07:10:36.204  1020  2883 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:36.204  1020  2883 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:36.204  1020  2883 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 07:10:36.214  1020  1516 I ActivityManager: Killing 2472:com.sec.android.widgetapp.digitalclock/u0a88 (adj 15): empty #31
,03-17 07:10:36.214  1020  1344 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.policydm
,03-17 07:10:36.214  3196  3196 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 07:10:36.214  3196  3196 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-17 07:10:36.214  1020  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.214  1020  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.214  1020  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.214  1020  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.224  3394  3394 E Zygote  : MountEmulatedStorage()
,03-17 07:10:36.224  3394  3394 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:36.224  3394  3394 E Zygote  : v2
03-17 07:10:36.224  3394  3394 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:36.224  3394  3394 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:36.234  3394  3394 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:36.234  1020  1344 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3394 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:36.234  3394  3394 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:36.234   257   257 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,03-17 07:10:36.234  1020  1362 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,03-17 07:10:36.234  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.234  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.234  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.234  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.254  3403  3403 E Zygote  : MountEmulatedStorage()
03-17 07:10:36.254  1020  2880 D InputDispatcher: Focus entered window: 3196
03-17 07:10:36.254  3403  3403 E Zygote  : v2
03-17 07:10:36.254  3403  3403 I libpersona: KNOX_SDCARD checking this for 10057
03-17 07:10:36.254  3403  3403 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:36.254  3403  3403 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:36.254  3403  3403 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:36.254  3394  3394 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:36.254  3403  3403 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:36.264  1020  1362 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3403 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
03-17 07:10:36.264  3394  3394 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:36.264  1020  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 07:10:36.264  1020  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 07:10:36.264  3196  3196 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-17 07:10:36.264  3196  3393 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 07:10:36.264  3196  3393 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-17 07:10:36.264  3196  3393 D OpenGLRenderer: Enabling debug mode 0
,03-17 07:10:36.274  3245  3353 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,03-17 07:10:36.274  3245  3353 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
03-17 07:10:36.274  1020  1516 D ActivityManager: bindService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm, action: null
03-17 07:10:36.274  1020  1516 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,03-17 07:10:36.284  1020  1516 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:36.284  1020  1516 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:36.284  1020  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
03-17 07:10:36.284  3245  3245 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-17 07:10:36.284   309   309 I art     : Explicit concurrent mark sweep GC freed 8745(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 759us total 26.261ms
,03-17 07:10:36.304   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 654us total 18.023ms
,03-17 07:10:36.304  3403  3403 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:36.304  3403  3403 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:36.314  2142  2142 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
03-17 07:10:36.314  2142  2142 I dhcpcd  : wlan0: no IPv6 Routers available
,03-17 07:10:36.324  1020  2933 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 07:10:36.324   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 18.633ms
,03-17 07:10:36.324  1020  1044 W libprocessgroup: failed to open /acct/uid_10088/pid_2472/cgroup.procs: No such file or directory
,03-17 07:10:36.324  1187  1187 I StatusBar: Icon Only
03-17 07:10:36.324  1187  1187 D PanelView: There is/are notification(s) 
,03-17 07:10:36.334  1020  3426 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 07:10:36.334  1020  1052 I ActivityManager: Displayed Component not be shown by security: +1s343ms
,03-17 07:10:36.334  3196  3196 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@391d8e14 time:38317
,03-17 07:10:36.344  1020  1052 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 07:10:36.344  1020  1045 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 07:10:36.344  1020  1052 D CustomFrequencyManagerService: FrequencyrequestList.getNextMaxCPUCoreRequest, index: 1
,03-17 07:10:36.344  1020  1052 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{23939729 u0 com.test.thalitest/.MainActivity t12} time:38324
03-17 07:10:36.344  1020  1052 W ActivityManager: mDVFSHelper.release()
,03-17 07:10:36.344  3245  3245 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,03-17 07:10:36.344  1824  1824 I SamsungIME: getCurrentCandidateView
,03-17 07:10:36.354  1445  1445 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,03-17 07:10:36.354  1020  1032 I ActivityManager: Killing 2491:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,03-17 07:10:36.374  3245  3353 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,03-17 07:10:36.414  1020  1044 W libprocessgroup: failed to open /acct/uid_10142/pid_2491/cgroup.procs: No such file or directory
,03-17 07:10:36.554  3357  3431 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 07:10:36.554  3357  3431 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 07:10:36.564   257   802 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
,03-17 07:10:36.564   257   451 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
,03-17 07:10:36.564  1020  2934 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,03-17 07:10:36.564  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.564  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.564  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.564  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.584  1020  1307 D LocationManagerService: getProviders()=[passive],
,03-17 07:10:36.584  3436  3436 E Zygote  : MountEmulatedStorage()
03-17 07:10:36.584  3436  3436 E Zygote  : v2
03-17 07:10:36.584  3436  3436 I libpersona: KNOX_SDCARD checking this for 10015
03-17 07:10:36.584  3436  3436 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:36.584  3436  3436 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:36.594  3436  3436 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:36.594  3436  3436 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,03-17 07:10:36.594  1020  2934 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3436 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,03-17 07:10:36.614  3436  3436 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:36.614  3436  3436 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:36.624  3357  3431 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 07:10:36.644  1020  1020 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 07:10:36.684  3357  3431 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 07:10:36.684  3357  3431 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@22d007e3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 07:10:36.684  3357  3431 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 07:10:36.694  1020  1307 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,03-17 07:10:36.694  1020  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.704  1020  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.704  1020  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.704  1020  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.714  3463  3463 E Zygote  : MountEmulatedStorage(),
,03-17 07:10:36.714  3463  3463 E Zygote  : v2
,03-17 07:10:36.714  3463  3463 I libpersona: KNOX_SDCARD checking this for 10009
03-17 07:10:36.714  3463  3463 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:36.714  1020  1307 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3463 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:36.714  3463  3463 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:36.714  3463  3463 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:36.714  3463  3463 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 07:10:36.724  1020  1344 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
03-17 07:10:36.724  1020  1344 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,03-17 07:10:36.734  1020  1344 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:36.734  1020  1344 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:36.734  1020  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-17 07:10:36.744  1020  1130 I ActivityManager: Killing 2523:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,03-17 07:10:36.744  3463  3463 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:36.754  3463  3463 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:36.764  3394  3394 I DBG_POLICYDM: [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,03-17 07:10:36.774  3394  3394 I DBG_POLICYDM: [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-17 07:10:36.784   327   327 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-17 07:10:36.794  1824  1824 D SamsungIME: Dismiss ExpandCandiate
,03-17 07:10:36.794  3245  3353 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,03-17 07:10:36.824  1020  1044 W libprocessgroup: failed to open /acct/uid_10139/pid_2523/cgroup.procs: No such file or directory
,03-17 07:10:36.884  3245  3353 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-17 07:10:36.914  3245  3353 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,03-17 07:10:36.914  3245  3353 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,03-17 07:10:36.924  1020  1033 I art     : Explicit concurrent mark sweep GC freed 17648(898KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 26MB/39MB, paused 2.670ms total 145.088ms
,03-17 07:10:36.924  1020  1033 E Tethering: No numeric data
,03-17 07:10:36.924  1020  2883 D ActivityManager: startService callerProcessName:com.dropbox.android, calleePkgName: com.dropbox.android
,03-17 07:10:36.924  1020  2883 D ActivityManager: retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,03-17 07:10:36.924  1020  1130 E Tethering: No numeric data
,03-17 07:10:36.924  1020  2883 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:36.924  1020  2883 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,03-17 07:10:36.924  1020  1362 E Tethering: No numeric data
03-17 07:10:36.924  1020  2883 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-17 07:10:36.934  1020  1033 E Tethering: No numeric data
,03-17 07:10:36.934  1020  2883 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.934  1020  2883 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.944  1020  2883 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.944  1020  2883 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.944  3196  3196 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3196
,03-17 07:10:36.954  1020  2931 E Tethering: No numeric data
,03-17 07:10:36.954  3488  3488 E Zygote  : MountEmulatedStorage(),
,03-17 07:10:36.954  3488  3488 E Zygote  : v2,
03-17 07:10:36.954  1020  2883 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3488 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 07:10:36.954  3488  3488 I libpersona: KNOX_SDCARD checking this for 10092,
03-17 07:10:36.964  3488  3488 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:36.964  3488  3488 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 07:10:36.964  1020  2934 I ActivityManager: Killing 2551:com.samsung.android.securitylogagent/1000 (adj 15): empty #31,
03-17 07:10:36.964  3394  3478 I DBG_POLICYDM: [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,03-17 07:10:36.964  3488  3488 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 07:10:36.974  3488  3488 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL,
03-17 07:10:36.974   282  2141 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
03-17 07:10:36.974   282  2141 D audio_hw_extn: audio_extn_get_parameters: returns 
03-17 07:10:36.974   282  2141 V msm8974_platform: platform_get_parameters: exit: returns - ,
03-17 07:10:36.974   282  2141 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-17 07:10:36.974   282  2141 I str_params: key: 'call_forwarding' value: ''
03-17 07:10:36.974  3394  3394 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
03-17 07:10:36.974  1020  1130 E Tethering: No numeric data,
03-17 07:10:36.974  1993  1993 V InCall  : ProximitySensor -  - screenonImmediately: false
03-17 07:10:36.974  1993  1993 V InCall  : ProximitySensor -  - mFromRcsShare: false
03-17 07:10:36.974  1993  1993 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,03-17 07:10:36.984  1020  1020 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,03-17 07:10:36.984  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.984  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.984  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:36.984  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:36.994  1993  1993 D ScoverManager: serviceVersion : 16908288
,03-17 07:10:36.994  1020  2793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.cB:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-17 07:10:36.994  3394  3478 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
03-17 07:10:36.994  1020  2880 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 07:10:36.994  1993  1993 D InCall  : InCallUtils - isCoverClosed false,
03-17 07:10:36.994  1020  1491 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH,
03-17 07:10:36.994  1445  1445 I Telecom : ProximitySensorManager: Proximity wake lock already released
03-17 07:10:36.994  1993  1993 D InCall  : InCallUtils - isCoverClosed false
03-17 07:10:36.994  1993  1993 I InCall  : InCallPresenter -  - InCallState = NO_CALLS,
,03-17 07:10:36.994  3488  3488 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:36.994  1993  1993 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
,03-17 07:10:36.994  1993  1993 D InCall  : InCallPresenter -  - dismissCoverDialog()...
,03-17 07:10:36.994  3488  3488 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:37.004  1020  1020 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3501 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a,
,03-17 07:10:37.004  3501  3501 E Zygote  : MountEmulatedStorage()
03-17 07:10:37.004  3501  3501 E Zygote  : v2
03-17 07:10:37.004  3501  3501 I libpersona: KNOX_SDCARD checking this for 10003
,03-17 07:10:37.004  3501  3501 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:37.014  3501  3501 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 07:10:37.014  3394  3394 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-17 07:10:37.014  3501  3501 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:37.024  3501  3501 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:37.024  1993  1993 I InCall  : CallSContextMotion - stopPutDownListening
03-17 07:10:37.024  1993  1993 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
03-17 07:10:37.034  1187  1187 D PhoneStatusBarView: setCallBackground:0
,03-17 07:10:37.054  1020  1033 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 07:10:37.054  1993  1993 D InCall  : InCallUtils - isCoverClosed false
,03-17 07:10:37.064  3501  3501 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:37.064  3501  3501 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:37.074  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2551/cgroup.procs: No such file or directory
,03-17 07:10:37.124  1311  3234 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
,03-17 07:10:37.124  1311  3234 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
,03-17 07:10:37.144  3501  3501 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-17 07:10:37.164  3394  3394 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-17 07:10:37.174  3394  3394 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-17 07:10:37.174  3394  3394 I DBG_POLICYDM: [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,03-17 07:10:37.184  1020  1362 E Tethering: No numeric data
,03-17 07:10:37.184  1020  2880 E Tethering: No numeric data
,03-17 07:10:37.184  1020  2933 E Tethering: No numeric data
,03-17 07:10:37.184  3394  3478 I DBG_POLICYDM: [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,03-17 07:10:37.184  3394  3394 I DBG_POLICYDM: [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,03-17 07:10:37.194  3394  3394 I DBG_POLICYDM: [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,03-17 07:10:37.234  3501  3501 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-17 07:10:37.234  3501  3501 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-17 07:10:37.234  3501  3501 D UserAnalysis: Create SecureDbHelper
,03-17 07:10:37.254  1993  1993 D VideoCallManager: Instantiating VideoCallManager
,03-17 07:10:37.254  1993  1993 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 07:10:37.254  1993  1993 I GFX construct_block_size_descriptor_2d second part: took 2.029219ms for 0*0 texture 0
,03-17 07:10:37.264  1993  1993 I GFX generate_partition_tables: took 5.172448ms for 0*0 texture 0
,03-17 07:10:37.264  1993  1993 I GFX raster: took 10.958489ms for 176*144 texture 0
03-17 07:10:37.264  1993  1993 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83ddf60 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb83ec2e0 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 07:10:37.274  1993  1993 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,03-17 07:10:37.274  1993  1993 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 07:10:37.274  1993  1993 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 07:10:37.274  1993  1993 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 07:10:37.274  1993  1993 I Adreno-EGL: Local Branch: 
03-17 07:10:37.274  1993  1993 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 07:10:37.274  1993  1993 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 07:10:37.274  1993  1993 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 07:10:37.284  3501  3501 D IntelligenceServiceApplication: onCreate()
,03-17 07:10:37.284  3501  3501 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,03-17 07:10:37.284  1020  1516 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,03-17 07:10:37.284  1020  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.284  1020  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.284  1020  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.284  1020  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.294  1993  1993 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 07:10:37.304  3534  3534 E Zygote  : MountEmulatedStorage()
,03-17 07:10:37.304  3534  3534 E Zygote  : v2
03-17 07:10:37.304  3534  3534 I libpersona: KNOX_SDCARD checking this for 10060
03-17 07:10:37.304  3534  3534 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:37.304  1993  1993 I glCompressedTexImage2D: took 0.290156ms for 320*61440 texture 37809,
,03-17 07:10:37.304  3534  3534 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:37.304  3534  3534 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:37.304  3534  3534 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:37.314  1020  1516 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3534 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 07:10:37.314  1993  1993 I draw setup: took 11.573333ms for 320*240 texture 37809
03-17 07:10:37.314  1993  1993 E GFX GPU raster: drawn
,03-17 07:10:37.314  1020  1516 I ActivityManager: Killing 2604:com.example.hello/u0a174 (adj 15): empty #31
,03-17 07:10:37.314  1993  1993 I GFX GPU raster ASTC: took 41.017864ms for 320*240 texture 12
03-17 07:10:37.314  1993  1993 I GFX raster: took 41.092864ms for 320*240 texture 0
03-17 07:10:37.314  1993  1993 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83eb878 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb83ddd78 counterpartCT=4 counterpartW=320 counterparth=240
,03-17 07:10:37.334  3501  3501 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-17 07:10:37.334  1993  1993 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-17 07:10:37.344  1993  1993 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 07:10:37.344  1993  1993 I glCompressedTexImage2D: took 0.365886ms for 480*122880 texture 37813
03-17 07:10:37.344  1993  1993 I draw setup: took 0.746094ms for 480*640 texture 37813
03-17 07:10:37.344  1993  1993 E GFX GPU raster: drawn
,03-17 07:10:37.344  1993  1993 I GFX GPU raster ASTC: took 7.321717ms for 480*640 texture 12
03-17 07:10:37.344  1993  1993 I GFX raster: took 7.424009ms for 480*640 texture 0
03-17 07:10:37.344  1993  1993 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83ddd78 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb861af98 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 07:10:37.354  3534  3534 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:37.354  3534  3534 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:37.354  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,03-17 07:10:37.354  3501  3501 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-17 07:10:37.364  3196  3196 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-17 07:10:37.374  1020  2934 E Tethering: No numeric data,
,03-17 07:10:37.394  1824  1824 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 07:10:37.394  1993  1993 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,03-17 07:10:37.404  1993  1993 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 07:10:37.404  1993  1993 I glCompressedTexImage2D: took 0.337969ms for 440*116864 texture 37809
03-17 07:10:37.404  1993  1993 I draw setup: took 0.714427ms for 440*330 texture 37809
03-17 07:10:37.404  1993  1993 E GFX GPU raster: drawn
,03-17 07:10:37.404  1993  1993 I GFX GPU raster ASTC: took 4.710001ms for 440*330 texture 12
03-17 07:10:37.404  1993  1993 I GFX raster: took 4.793802ms for 440*330 texture 0
03-17 07:10:37.404  1993  1993 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb862f0b8 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb862f3e0 counterpartCT=4 counterpartW=440 counterparth=330
,03-17 07:10:37.404  3501  3501 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-17 07:10:37.404  3501  3501 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
,03-17 07:10:37.424  1020  2931 V VibratorService: hasVibrator - useVibetonz: true
,03-17 07:10:37.424  1311  3234 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,03-17 07:10:37.434  1020  2934 D ActivityManager: startProcessLocked calleePkgName: com.fmm.dm, hostingType: broadcast
,03-17 07:10:37.434  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.434  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.434  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.434  1020  1344 V VibratorService: hasVibrator - useVibetonz: true
,03-17 07:10:37.434  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.434  1020  2875 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 07:10:37.444  3553  3553 E Zygote  : MountEmulatedStorage()
03-17 07:10:37.444  3553  3553 E Zygote  : v2
03-17 07:10:37.444  3553  3553 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:37.444  3553  3553 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:37.444  3553  3553 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:37.454  1020  2934 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3553 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:37.454  3553  3553 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:37.454  3553  3553 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:37.454  1020  2934 I ActivityManager: Killing 2777:com.android.email/u0a145 (adj 15): empty #31
,03-17 07:10:37.454  1020  2934 I ActivityManager: Killing 2709:com.android.keychain/1000 (adj 15): empty #32
,03-17 07:10:37.454  1020  1032 V VibratorService: hasVibrator - useVibetonz: true
,03-17 07:10:37.464  1993  1993 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-17 07:10:37.464  1993  1993 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-17 07:10:37.464  1020  2934 I ActivityManager: Killing 2568:com.android.calendar/u0a135 (adj 15): empty #33
,03-17 07:10:37.464  1993  1993 I glCompressedTexImage2D: took 0.473386ms for 480*163840 texture 37811
03-17 07:10:37.464  1993  1993 I draw setup: took 0.914479ms for 480*640 texture 37811
03-17 07:10:37.464  1993  1993 E GFX GPU raster: drawn
,03-17 07:10:37.474  1993  1993 I GFX GPU raster ASTC: took 6.082293ms for 480*640 texture 12
03-17 07:10:37.474  1993  1993 I GFX raster: took 6.162397ms for 480*640 texture 0
03-17 07:10:37.474  1993  1993 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8643e70 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb861f570 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 07:10:37.494  3370  3370 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
,03-17 07:10:37.504  3553  3553 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:37.504  3553  3553 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:37.534  2851  2864 W art     : Suspending all threads took: 91.398ms
,03-17 07:10:37.544  1311  3234 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 07:10:37.554  3357  3377 W art     : Suspending all threads took: 29.716ms
,03-17 07:10:37.554  1993  1993 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 07:10:37.554  1993  1993 I GFX construct_block_size_descriptor_2d second part: took 2.138386ms for 0*0 texture 0
,03-17 07:10:37.554  2663  3158 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3158)  
,03-17 07:10:37.564  1020  2931 I ActivityManager: Killing 2461:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,03-17 07:10:37.564  1993  1993 I GFX generate_partition_tables: took 7.478386ms for 0*0 texture 0
,03-17 07:10:37.564  1993  1993 I GFX raster: took 11.621616ms for 176*144 texture 0
03-17 07:10:37.564  1993  1993 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8618838 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb8618938 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 07:10:37.634  3357  3487 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 07:10:37.634  3357  3487 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 07:10:37.654  1020  1491 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:37.654  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:37.654  1020  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:37.654  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-17 07:10:37.684  1311  3234 D ScoverManager: serviceVersion : 16908288
,03-17 07:10:37.694  1020  1044 W libprocessgroup: failed to open /acct/uid_10174/pid_2604/cgroup.procs: No such file or directory
,03-17 07:10:37.694  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2709/cgroup.procs: No such file or directory
03-17 07:10:37.694  1020  1044 W libprocessgroup: failed to open /acct/uid_10145/pid_2777/cgroup.procs: No such file or directory
03-17 07:10:37.694  1020  1044 W libprocessgroup: failed to open /acct/uid_10135/pid_2568/cgroup.procs: No such file or directory
03-17 07:10:37.694  1020  1044 W libprocessgroup: failed to open /acct/uid_10044/pid_2461/cgroup.procs: No such file or directory
,03-17 07:10:37.704  3553  3553 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,03-17 07:10:37.714  1993  1993 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 07:10:37.724  1993  1993 I GFX construct_block_size_descriptor_2d second part: took 2.459063ms for 0*0 texture 0
,03-17 07:10:37.724  3553  3553 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,03-17 07:10:37.724  3553  3553 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-17 07:10:37.724  3553  3553 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-17 07:10:37.734  1993  1993 I GFX generate_partition_tables: took 6.189584ms for 0*0 texture 0
,03-17 07:10:37.734  1993  1993 I GFX raster: took 10.808386ms for 176*144 texture 0
03-17 07:10:37.734  1993  1993 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8618720 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb861af98 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 07:10:37.744  1993  1993 D ScoverManager: registerListener
,03-17 07:10:37.744  1020  2880 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 07:10:37.744  3370  3370 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
03-17 07:10:37.744  1020  1307 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 07:10:37.744  1020  1307 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@3efec1c7, pid : 1993, uid : 1001, type : 1
,03-17 07:10:37.754  1993  1993 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-17 07:10:37.774  3370  3370 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,03-17 07:10:37.794  3196  3429 D jxcore_app_log: JniHelper::setJavaVM(0xb8009450), pthread_self() = -1202259216
,03-17 07:10:37.794  1824  1824 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 07:10:37.804  1020  2880 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:37.804  1020  2880 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:37.804  1020  2880 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:37.804  1020  2880 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:37.814  3196  3429 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 07:10:37.814  3196  3429 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 07:10:37.814  3196  3429 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 07:10:37.814  3196  3429 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 07:10:37.814  3196  3429 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,03-17 07:10:37.814  3196  3429 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@203bf3 added. We now have 1 listener(s)
,03-17 07:10:37.824  3370  3370 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,03-17 07:10:37.824  3196  3429 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,03-17 07:10:37.824  3370  3370 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,03-17 07:10:37.834  3196  3429 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
,03-17 07:10:37.834  3196  3429 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
03-17 07:10:37.834  3196  3429 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-17 07:10:37.834  3196  3429 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 07:10:37.844  3196  3429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 07:10:37.844  3196  3429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 07:10:37.844  3196  3429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 07:10:37.844  3196  3429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
03-17 07:10:37.844  3196  3429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 07:10:37.844  3196  3429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 07:10:37.844  3196  3429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 07:10:37.844  3196  3429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 07:10:37.844  3196  3429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 07:10:37.844  3196  3429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-17 07:10:37.844  3196  3429 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f7bfeae added. We now have 1 listener(s)
,03-17 07:10:37.844  3196  3429 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 07:10:37.854  1824  1824 I SamsungIME: KeybaordView init() : load resources
,03-17 07:10:37.854  3196  3429 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-17 07:10:37.854  3196  3429 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-17 07:10:37.854  3196  3429 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-17 07:10:37.854  3370  3370 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
03-17 07:10:37.854  3196  3429 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-17 07:10:37.854  3196  3429 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-17 07:10:37.864  3196  3429 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-17 07:10:37.864  3196  3429 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,03-17 07:10:37.864  3370  3370 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,03-17 07:10:37.874  3196  3429 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 07:10:37.874  3196  3429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 07:10:37.874  3196  3429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 07:10:37.874  3196  3429 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 07:10:37.874  3196  3429 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 07:10:37.874  3196  3429 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 07:10:37.874  3196  3429 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 07:10:37.874  3196  3429 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-17 07:10:37.874  3196  3429 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 07:10:37.874  3196  3429 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 07:10:37.884  1020  1032 D ActivityManager: getContentProviderImpl callerProcessName:com.fmm.dm, calleePkgName: com.sec.pcw.device
,03-17 07:10:37.884  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.884  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.884  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:37.884  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:37.904  3578  3578 E Zygote  : MountEmulatedStorage()
03-17 07:10:37.904  3578  3578 E Zygote  : v2
03-17 07:10:37.904  3578  3578 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:37.904  3578  3578 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:37.904  3578  3578 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:37.914  3578  3578 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:37.914  3578  3578 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:37.924  1020  1032 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3578 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 07:10:37.924  1824  1824 I SamsungIME: getCurrentKeyboard
,03-17 07:10:37.924  1824  1824 I SamsungIME: getTextKeyboard
,03-17 07:10:37.974  3245  3353 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-17 07:10:37.994  3578  3578 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:37.994  3578  3578 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:38.014  3394  3478 I DBG_POLICYDM: [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-17 07:10:38.024  3370  3370 I com.dropbox.sync.android.a: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,03-17 07:10:38.024  3196  3196 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 07:10:38.034  3394  3478 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 07:10:38.034  1824  1824 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 07:10:38.054  3196  3196 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 07:10:38.054  3196  3196 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-17 07:10:38.084  3394  3478 I DBG_POLICYDM: [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,03-17 07:10:38.084  3394  3478 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,03-17 07:10:38.084  3394  3478 I DBG_POLICYDM: [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,03-17 07:10:38.094  3570  3570 I dex2oat : ----------------------------------------------------
03-17 07:10:38.094  3570  3570 I dex2oat : <SS>: S T A R T I N G . . .
03-17 07:10:38.094  3570  3570 I dex2oat : <SS>: Zip is absent. Canceled.
,03-17 07:10:38.094  3570  3570 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads281601623.jar --oat-fd=31 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads281601623.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-17 07:10:38.114  3578  3578 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,03-17 07:10:38.124  3578  3578 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-17 07:10:38.124  3370  3370 I com.dropbox.sync.android.ad: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
,03-17 07:10:38.124  3578  3578 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-17 07:10:38.134  1020  2931 I ActivityManager: Killing 2799:com.samsung.android.sm/1000 (adj 15): empty #31
,03-17 07:10:38.144  3578  3590 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 07:10:38.164  3534  3534 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.8.KK_APP
,03-17 07:10:38.164  3553  3553 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-17 07:10:38.174  3553  3553 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 07:10:38.174  3553  3553 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 07:10:38.174  1020  2880 D ActivityManager: startProcessLocked calleePkgName: com.fmm.ds, hostingType: broadcast
,03-17 07:10:38.184  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.184  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.184  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.184  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.194  3604  3604 E Zygote  : MountEmulatedStorage()
,03-17 07:10:38.194  3604  3604 E Zygote  : v2
,03-17 07:10:38.194  3604  3604 I libpersona: KNOX_SDCARD checking this for 1000
,03-17 07:10:38.204  3604  3604 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:38.204  3604  3604 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 07:10:38.214  1020  2880 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3604 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 07:10:38.214  3604  3604 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:38.214  1020  2880 I ActivityManager: Killing 2202:flipboard.app/u0a98 (adj 15): empty #31,
,03-17 07:10:38.214  1020  2880 I ActivityManager: Killing 2894:flipboard.boxer.app/u0a99 (adj 15): empty #32
,03-17 07:10:38.214  3604  3604 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:38.234  3394  3478 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,03-17 07:10:38.244  3604  3604 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:38.244  3604  3604 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:38.264  1020  2931 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,03-17 07:10:38.274  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.274  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.274  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.274  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.294  1020  2931 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3621 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:38.294  3394  3478 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-17 07:10:38.294  1020  2931 I ActivityManager: Killing 2942:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,03-17 07:10:38.294  3621  3621 E Zygote  : MountEmulatedStorage(),
03-17 07:10:38.294  3621  3621 I libpersona: KNOX_SDCARD checking this for 10062
03-17 07:10:38.294  3621  3621 E Zygote  : v2
03-17 07:10:38.294  3621  3621 I libpersona: KNOX_SDCARD not a persona,
03-17 07:10:38.294  3621  3621 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 07:10:38.294  3621  3621 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:38.294  3621  3621 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:38.324  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2799/cgroup.procs: No such file or directory,
,03-17 07:10:38.334  1311  3234 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 07:10:38.344  3621  3621 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:38.344  3394  3478 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-17 07:10:38.344  3621  3621 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:38.344  3394  3480 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
03-17 07:10:38.344  3394  3478 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,03-17 07:10:38.354  3394  3478 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,03-17 07:10:38.364  3394  3480 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 07:10:38.374  1311  3234 D Settings_Utils: isSupportVNFestival SM-A500FU XEO
,03-17 07:10:38.384  3394  3480 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 07:10:38.384  3394  3480 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-17 07:10:38.394  3394  3478 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/03/18/16:12:11
,03-17 07:10:38.394  3394  3478 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/03/17/07:10:38
,03-17 07:10:38.394  3394  3478 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,03-17 07:10:38.394  3394  3478 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,03-17 07:10:38.404  3394  3480 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-17 07:10:38.404  3394  3480 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-17 07:10:38.404  3394  3480 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-17 07:10:38.404  3394  3480 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,03-17 07:10:38.404  3394  3480 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,03-17 07:10:38.404  3394  3480 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-17 07:10:38.434  3604  3604 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-17 07:10:38.434  3604  3604 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-17 07:10:38.444  3357  3357 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-17 07:10:38.444  1020  1044 W libprocessgroup: failed to open /acct/uid_10099/pid_2894/cgroup.procs: No such file or directory
,03-17 07:10:38.474  3394  3478 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,03-17 07:10:38.484  3578  3590 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 07:10:38.494  3357  3357 I System.out: YouTube MDX: MDX video stage moved to NEW
,03-17 07:10:38.514  3604  3604 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-17 07:10:38.524  3357  3357 I System.out: YouTube MDX: MDX video player state moved to UNSTARTED
,03-17 07:10:38.524  3394  3480 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-17 07:10:38.524  3604  3604 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-17 07:10:38.544  1020  1362 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
03-17 07:10:38.544  3357  3357 I System.out: YouTube MDX: MDX ad player state moved to UNSTARTED
,03-17 07:10:38.544  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.554  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.554  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.554  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.564  3621  3621 I ExternalOEMControlProvider: onCreate,
,03-17 07:10:38.564  3650  3650 E Zygote  : MountEmulatedStorage(),
03-17 07:10:38.564  3650  3650 I libpersona: KNOX_SDCARD checking this for 10094
03-17 07:10:38.564  3650  3650 E Zygote  : v2
03-17 07:10:38.564  3650  3650 I libpersona: KNOX_SDCARD not a persona,
03-17 07:10:38.564  3650  3650 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:38.564  3650  3650 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 07:10:38.574  3650  3650 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:38.574  1020  1362 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3650 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,03-17 07:10:38.574  1020  1491 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.servicemodeapp, hostingType: broadcast
,03-17 07:10:38.584  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.584  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.584  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.584  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.604  1020  1491 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3664 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 07:10:38.604  1020  1491 I ActivityManager: Killing 1956:com.android.defcontainer/u0a4 (adj 15): empty #31
,03-17 07:10:38.604  3394  3480 I DBG_POLICYDM: [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,03-17 07:10:38.614  3664  3664 E Zygote  : MountEmulatedStorage()
03-17 07:10:38.614  3664  3664 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:38.614  3664  3664 E Zygote  : v2
03-17 07:10:38.614  3664  3664 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:38.614  3664  3664 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:38.614  3664  3664 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:38.614  3664  3664 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:38.624  3650  3650 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:38.624  3650  3650 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:38.634   309   309 I art     : Explicit concurrent mark sweep GC freed 8737(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 28.463ms
,03-17 07:10:38.634  3394  3478 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,03-17 07:10:38.644  3394  3478 I DBG_POLICYDM: [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-17 07:10:38.654   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 17.855ms
,03-17 07:10:38.674   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 17.791ms
,03-17 07:10:38.674  3650  3650 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-17 07:10:38.684  3650  3650 D elm:15183: ELMEngine.ELMEngine( context ).
,03-17 07:10:38.684  3650  3650 D elm:15183: MDMBridge.setEnterpriseBridge()
,03-17 07:10:38.684  1020  1362 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
03-17 07:10:38.684  1020  1362 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,03-17 07:10:38.684  3664  3664 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:38.684  3664  3664 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:38.684  1020  1362 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:38.684  1020  1362 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:38.684  1020  1362 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-17 07:10:38.694  3650  3650 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-17 07:10:38.694  1020  2883 D SettingsProvider: name = PREVIOUS_SYS_TIME
,03-17 07:10:38.694  1020  2883 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-17 07:10:38.694  1020  2883 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-17 07:10:38.694  1020  2883 D SettingsProvider: selectionArgs: false
03-17 07:10:38.694  1020  2883 D SettingsProvider: selectionArgs: 10062
,03-17 07:10:38.694  1020  2883 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,03-17 07:10:38.694  1020  2883 D SettingsProvider: ret = -1
,03-17 07:10:38.704  1020  2883 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
03-17 07:10:38.704  3650  3650 D elm:15183: ElmAgentService : onCreate()
,03-17 07:10:38.704  1020  1491 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
,03-17 07:10:38.704  1020  1491 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-17 07:10:38.704  1020  1491 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-17 07:10:38.704  1020  1491 D SettingsProvider: selectionArgs: false
03-17 07:10:38.704  1020  1491 D SettingsProvider: selectionArgs: 10062
03-17 07:10:38.704  1020  1491 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:38.704  1020  1491 D SettingsProvider: ret = -1
,03-17 07:10:38.714  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 07:10:38.714  3196  3577 W jxcore-log: Initializing JXcore engine
03-17 07:10:38.714  3196  3577 W jxcore-log: JXcore engine is ready
,03-17 07:10:38.714  1020  1491 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,03-17 07:10:38.714  3650  3681 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,03-17 07:10:38.734  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:38.734  3570  3570 I dex2oat : dex2oat took 636.796ms (threads: 4)
,03-17 07:10:38.734   287   287 E SMD     : DCD OFF
,03-17 07:10:38.734  1430  1430 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,03-17 07:10:38.754  3664  3664 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 07:10:38.764  1430  1430 V EmergencyMode: [EmergencyBase] setBootTime
03-17 07:10:38.764  1430  1430 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
,03-17 07:10:38.764  3650  3650 D elm:15183: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,03-17 07:10:38.764  3650  3650 D elm:15183: BootCompletedState : startBootCompleted() call
,03-17 07:10:38.764  1020  1307 D ActivityManager: startProcessLocked calleePkgName: com.sec.factory.camera, hostingType: broadcast
,03-17 07:10:38.764  1020  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.764  1020  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.774  1020  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.774  1020  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.774  3650  3650 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 07:10:38.774  3650  3650 I elm:15183: Get License : 0
,03-17 07:10:38.774  3650  3650 D elm:15183: ElmAgentService : onDestroy().
,03-17 07:10:38.784  1946  1946 E audit   : type=1400 msg=audit(1458195038.784:205): avc:  denied  { ioctl } for  pid=3577 comm="Thread-418" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-17 07:10:38.784  1946  1946 E audit   :  SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:38.784  1946  1946 E audit   : type=1300 msg=audit(1458195038.784:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=4 a3=9bbf48f8 items=0 ppid=309 ppcomm=main pid=3577 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-418" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-17 07:10:38.784  1946  1946 E audit   : type=1320 msg=audit(1458195038.784:205): 
,03-17 07:10:38.794  3687  3687 E Zygote  : MountEmulatedStorage()
03-17 07:10:38.794  3687  3687 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:38.794  3687  3687 E Zygote  : v2,
03-17 07:10:38.794  3687  3687 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:38.794  3687  3687 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:38.794  3687  3687 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 07:10:38.794  3687  3687 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:38.794  1020  1307 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3687 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:38.794  1020  1307 I ActivityManager: Killing 2957:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,03-17 07:10:38.804  3604  3604 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
03-17 07:10:38.804  3196  3577 W jxcore-log: Starting JXcore engine
,03-17 07:10:38.814  3664  3664 I ServiceMode: received = ACTION_BOOT_COMPLETED
03-17 07:10:38.814  3664  3664 I ServiceMode: setReferenceIsDumpState : 0
,03-17 07:10:38.824  3604  3604 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-17 07:10:38.824  3604  3604 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-17 07:10:38.834  3604  3604 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-17 07:10:38.834  1020  2934 D ActivityManager: startProcessLocked calleePkgName: com.wssnps, hostingType: broadcast
03-17 07:10:38.834  3604  3604 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-17 07:10:38.834  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.834  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.834  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.834  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.834  3604  3604 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
03-17 07:10:38.834  3604  3604 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,03-17 07:10:38.834  3687  3687 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:38.834  3687  3687 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:38.844  3706  3706 E Zygote  : MountEmulatedStorage()
03-17 07:10:38.844  3706  3706 E Zygote  : v2
03-17 07:10:38.844  3706  3706 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:38.844  3706  3706 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:38.844  3706  3706 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:38.854  3706  3706 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:38.854  3706  3706 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:38.864  1020  2934 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3706 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 07:10:38.864  1020  2934 I ActivityManager: Killing 2365:com.sec.modem.settings/1000 (adj 15): empty #31
03-17 07:10:38.864  1020  1130 I ActivityManager: Killing 2977:com.sec.knox.bridge/1000 (adj 15): empty #31
,03-17 07:10:38.874  1020  1307 I ActivityManager: Killing 2994:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,03-17 07:10:38.904  3706  3706 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:38.904  3706  3706 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:38.924  3463  3463 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...,
,03-17 07:10:38.924  3463  3463 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-17 07:10:38.924  3463  3463 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-17 07:10:38.964  3463  3463 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-17 07:10:38.964  3196  3577 W jxcore-log: Platform android
03-17 07:10:38.964  3196  3577 W jxcore-log: 
03-17 07:10:38.964  3196  3577 W jxcore-log: Process ARCH arm
03-17 07:10:38.964  3196  3577 W jxcore-log: 
,03-17 07:10:38.964  1020  2883 D ActivityManager: startProcessLocked calleePkgName: com.google.android.onetimeinitializer, hostingType: broadcast
,03-17 07:10:38.964  1020  2883 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.964  1020  2883 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.964  1020  2883 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:38.964  1020  2883 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:38.984  3721  3721 E Zygote  : MountEmulatedStorage()
03-17 07:10:38.984  3721  3721 E Zygote  : v2
03-17 07:10:38.984  3721  3721 I libpersona: KNOX_SDCARD checking this for 10014
03-17 07:10:38.984  3721  3721 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:38.984  3721  3721 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:38.984  3721  3721 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:38.994  1020  2883 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3721 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,03-17 07:10:38.994  3721  3721 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:38.994  3245  3353 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,03-17 07:10:38.994  3706  3706 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
,03-17 07:10:39.004  3706  3706 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,03-17 07:10:39.014  3370  3647 I System.out: Thread-444(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 07:10:39.014  1020  2883 D ActivityManager: startService callerProcessName:com.wssnps, calleePkgName: com.wssnps
03-17 07:10:39.014  1020  2883 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-17 07:10:39.014  1020  2883 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:39.014  1020  2883 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:39.014  1020  2883 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
03-17 07:10:39.014  3370  3647 I System.out: Thread-444(ApacheHTTPLog):isSBSettingEnabled false
03-17 07:10:39.014  3370  3647 I System.out: Thread-444(ApacheHTTPLog):isShipBuild true
03-17 07:10:39.014  3370  3647 I System.out: Thread-444(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,03-17 07:10:39.024  3370  3647 I System.out: Thread-444(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 07:10:39.024   277  1015 D EnterpriseController: uids 10092
03-17 07:10:39.024   277  1015 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 07:10:39.024   277  1015 D Netd    : getNetworkForDns: using netid 502 for uid 10092
03-17 07:10:39.024  3687  3687 I CameraApp: CameraApp.onCreate()... mFeature : null
,03-17 07:10:39.024  3687  3687 I testFeature: Feature.Feature(context)
03-17 07:10:39.024  3687  3687 I testFeature: Feature.readInternalDefaultXml()
,03-17 07:10:39.024  3687  3687 I testFeature: ResetFeatureValue
,03-17 07:10:39.024  3721  3721 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:39.024  3721  3721 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:39.024  3687  3687 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
03-17 07:10:39.024  3687  3687 I CameraApp: CameraApp.getAppFeature()...
,03-17 07:10:39.034  3706  3706 D NPS_WSSNPS: [] Service onCreate!!,
03-17 07:10:39.034  1020  1033 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,03-17 07:10:39.034  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.034  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.034  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.034  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.054  3740  3740 E Zygote  : MountEmulatedStorage()
,03-17 07:10:39.054  3740  3740 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:39.054  3740  3740 E Zygote  : v2
03-17 07:10:39.054  3740  3740 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:39.054  3740  3740 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 07:10:39.054  3740  3740 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:39.054  3740  3740 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:39.064  1020  1033 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=3740 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:39.074  2687  2756 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-17 07:10:39.084  1020  1033 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,03-17 07:10:39.084  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.084  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.084  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.084  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.094  3740  3740 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:39.094  3740  3740 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:39.094  3756  3756 E Zygote  : MountEmulatedStorage()
03-17 07:10:39.094  3756  3756 E Zygote  : v2
03-17 07:10:39.094  3756  3756 I libpersona: KNOX_SDCARD checking this for 10100
03-17 07:10:39.094  3756  3756 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:39.104  3706  3749 D NPS_WSSNPS: [50.150621] NpsServiceTask Start,
03-17 07:10:39.104  3756  3756 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 07:10:39.104  3756  3756 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 07:10:39.114  3756  3756 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:39.124  1020  1033 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3756 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
03-17 07:10:39.124  1020  1033 I ActivityManager: Killing 2333:com.android.mms/u0a46 (adj 15): empty #31
,03-17 07:10:39.124  1020  2934 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:39.124  1020  2934 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:39.124  1020  2934 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:39.124  1020  2934 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 07:10:39.134  3706  3706 D NPS_WSSNPS: [50.150621] smlDBHelper
,03-17 07:10:39.154  3740  3740 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:39.164  3756  3756 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:39.164  3756  3756 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:39.194  3721  3721 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
,03-17 07:10:39.204  1020  1032 D CountryDetector: No listener is left
,03-17 07:10:39.204  1020  1033 D ActivityManager: startService callerProcessName:com.google.android.onetimeinitializer, calleePkgName: com.google.android.onetimeinitializer
,03-17 07:10:39.204  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,03-17 07:10:39.204  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:39.214  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:39.214  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,03-17 07:10:39.214  3706  3706 I NPS_WSSNPS: [50.150621] AsyncBulkFlagCheck
,03-17 07:10:39.224  3394  3480 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 07:10:39.224  3706  3772 I NPS_WSSNPS: [50.150621] IsRemain_AsyncBulkCheck
,03-17 07:10:39.234  3706  3772 I NPS_WSSNPS: [50.150621] IsRemain_Asyncing nothing
,03-17 07:10:39.234  3706  3772 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,03-17 07:10:39.234  1020  2934 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-17 07:10:39.234  1020  2934 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:39.234  1020  2934 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:39.234  1020  2934 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 07:10:39.234  3721  3773 V OneTimeService: OneTimeService.onHandleIntent
,03-17 07:10:39.254  3394  3480 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,03-17 07:10:39.264  3196  3577 I jxcore-log: JXcore Cordova bridge is ready!
03-17 07:10:39.264  3196  3577 I jxcore-log: 
,03-17 07:10:39.264  3196  3577 W jxcore-log: JXcore engine is started
,03-17 07:10:39.264  1020  1344 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-17 07:10:39.264  1020  1344 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,03-17 07:10:39.274  1020  1344 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:39.274  1020  1344 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:39.274  1020  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
03-17 07:10:39.274  3706  3706 D NPS_WSSNPS: [50.150621] Service onDestroy
03-17 07:10:39.274  3196  3429 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 07:10:39.284  3706  3706 I NPS_WSSNPS: [50.150621] smlBRConfigurationDelete
,03-17 07:10:39.284  3706  3706 I NPS_WSSNPS: [50.150621] smlBRMessageDelete
03-17 07:10:39.284  3706  3706 I NPS_WSSNPS: [50.150621] smlBREmailDelete
,03-17 07:10:39.284  3706  3706 I NPS_WSSNPS: [50.150621] smlBRNetworkDelete
,03-17 07:10:39.284  3706  3706 I NPS_WSSNPS: [50.150621] smlBRCallLogDelete
03-17 07:10:39.284  1020  1516 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-17 07:10:39.284  1020  1516 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,03-17 07:10:39.284  3706  3706 I NPS_WSSNPS: [50.150621] smlBRMiniDiaryDelete
,03-17 07:10:39.284  3706  3706 I NPS_WSSNPS: [50.150621] smlBRPenMemoMDelete
,03-17 07:10:39.284  3706  3706 I NPS_WSSNPS: [50.150621] smlBRSMemoDelete
03-17 07:10:39.284  3706  3706 I NPS_WSSNPS: [50.150621] verifier installed? false
,03-17 07:10:39.284  3706  3706 I NPS_WSSNPS: [50.150621] cpuBooster release : false
03-17 07:10:39.284  1020  1516 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:39.284  1020  1516 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:39.284  1020  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 07:10:39.294  1020  1307 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-17 07:10:39.294  1020  1307 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,03-17 07:10:39.294  1020  1307 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:39.294  1020  1307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:39.294  1020  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 07:10:39.294  3756  3756 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
,03-17 07:10:39.294  1020  1362 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-17 07:10:39.294  1020  1362 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,03-17 07:10:39.304  1020  1362 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:39.304  1020  1362 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:39.304  1020  1362 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 07:10:39.304  3706  3706 D NPS_WSSNPS: [50.150621] dsServerSocket close
,03-17 07:10:39.304  3756  3756 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,03-17 07:10:39.314  1020  2933 D ActivityManager: startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
,03-17 07:10:39.314  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.314  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.314  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.314  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.324  3779  3779 E Zygote  : MountEmulatedStorage()
,03-17 07:10:39.324  3779  3779 I libpersona: KNOX_SDCARD checking this for 10101
03-17 07:10:39.324  3779  3779 E Zygote  : v2
03-17 07:10:39.324  3779  3779 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:39.324  3779  3779 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:39.334  3779  3779 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:39.334  1020  2933 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3779 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 07:10:39.334  3779  3779 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:39.334  1020  2933 I ActivityManager: Killing 3052:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
,03-17 07:10:39.344  1020  1032 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-17 07:10:39.344  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,03-17 07:10:39.354  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:39.354  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:39.354  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 07:10:39.354  3779  3779 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:39.354  3779  3779 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:39.364  1020  1516 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,03-17 07:10:39.364  1020  1516 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 07:10:39.374  1020  1516 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:39.374  1020  1516 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:39.374  1020  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 07:10:39.374  2576  2576 I Hs20UtilService: Starting #2
,03-17 07:10:39.384  2576  2599 I Hs20UtilService: Message received 5003
,03-17 07:10:39.384  1020  2933 D ActivityManager: startProcessLocked calleePkgName: com.samsung.klmsagent, hostingType: broadcast
,03-17 07:10:39.384  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.384  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.394  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.394  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.414  1020  2933 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3798 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a,
,03-17 07:10:39.414  1020  1130 W ActivityManager: userId = 0, bbcId = -10000,
,03-17 07:10:39.414  1020  1130 D ActivityManager: bindService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube, action: null
,03-17 07:10:39.414  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:39.414  1020  1130 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
03-17 07:10:39.414  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
03-17 07:10:39.414  3798  3798 E Zygote  : MountEmulatedStorage()
03-17 07:10:39.414  3798  3798 I libpersona: KNOX_SDCARD checking this for 10019
03-17 07:10:39.414  3798  3798 E Zygote  : v2
03-17 07:10:39.414  3798  3798 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:39.414  3798  3798 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:39.424  3798  3798 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:39.424  3798  3798 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:39.464  3798  3798 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:39.464  3798  3798 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:39.484  2663  2663 D FactoryTestApp: [DummyFtClient$onDestroy](2663) Destroy DummyFtClient service
,03-17 07:10:39.484  2663  2663 D FactoryTestApp: [Support$Values.getString](2663) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 07:10:39.484  2663  2663 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2663) mConnectionMode = gsm
03-17 07:10:39.484  2663  2663 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2663) RUNNING_FTCLIENT : false
03-17 07:10:39.484  2663  2663 D FactoryTestApp: [DummyFtClient$onDestroy](2663) kill process
03-17 07:10:39.484  2663  2663 I Process : Sending signal. PID: 2663 SIG: 9
,03-17 07:10:39.514  1637  1711 I art     : Explicit concurrent mark sweep GC freed 2938(119KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 861us total 29.650ms
,03-17 07:10:39.524  1020  1344 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:39.524  1020  1344 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:39.524  1020  1344 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:39.524  1020  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 07:10:39.534  1020  1044 W libprocessgroup: failed to open /acct/uid_10098/pid_2202/cgroup.procs: No such file or directory
03-17 07:10:39.534  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2942/cgroup.procs: No such file or directory
,03-17 07:10:39.534  1020  1044 W libprocessgroup: failed to open /acct/uid_10004/pid_1956/cgroup.procs: No such file or directory
,03-17 07:10:39.534  1020  1044 W libprocessgroup: failed to open /acct/uid_10152/pid_2957/cgroup.procs: No such file or directory
03-17 07:10:39.534  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2365/cgroup.procs: No such file or directory
03-17 07:10:39.534  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2977/cgroup.procs: No such file or directory
03-17 07:10:39.534  1020  1044 W libprocessgroup: failed to open /acct/uid_1101/pid_2994/cgroup.procs: No such file or directory
,03-17 07:10:39.554  1020  1044 W libprocessgroup: failed to open /acct/uid_10046/pid_2333/cgroup.procs: No such file or directory
,03-17 07:10:39.564  1020  1516 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-17 07:10:39.564  1020  1516 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
,03-17 07:10:39.564  1020  1044 W libprocessgroup: failed to open /acct/uid_10048/pid_3052/cgroup.procs: No such file or directory
,03-17 07:10:39.564  1020  1516 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:39.564  1020  1516 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:39.564  1020  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 07:10:39.574   256   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 07:10:39.574   256   516 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:39.574  3357  3357 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 07:10:39.584  3798  3798 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 07:10:39 GMT+01:00 2016
,03-17 07:10:39.594  1020  1130 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:39.604  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:39.604  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:39.604  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 07:10:39.634  1311  3234 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 07:10:39.664  1879  2109 I art     : Explicit concurrent mark sweep GC freed 18135(1383KB) AllocSpace objects, 27(431KB) LOS objects, 40% free, 12MB/20MB, paused 1.127ms total 83.582ms
,03-17 07:10:39.674  1020  1032 I ActivityManager: Process com.sec.factory (pid 2663)(adj 0) has died(84,1124)
,03-17 07:10:39.714  3436  3436 I RlzPingService: Setting next ping for 1458799839718
,03-17 07:10:39.724  1020  1032 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,03-17 07:10:39.724  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-17 07:10:39.724  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:39.724  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:39.724  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 07:10:39.744  3798  3798 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-17 07:10:39.744  1020  1307 D ActivityManager: startProcessLocked calleePkgName: com.android.managedprovisioning, hostingType: broadcast
,03-17 07:10:39.744  1020  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.744  1020  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.744  1020  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.744  1020  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.764  3824  3824 E Zygote  : MountEmulatedStorage()
03-17 07:10:39.764  3824  3824 E Zygote  : v2
03-17 07:10:39.764  3824  3824 I libpersona: KNOX_SDCARD checking this for 10022
03-17 07:10:39.764  3824  3824 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:39.764  3824  3824 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:39.764  3824  3824 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 07:10:39.764  3824  3824 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:39.764  1020  1307 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3824 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
,03-17 07:10:39.794  3824  3824 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:39.794  3824  3824 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:39.924  3798  3798 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-17 07:10:39.934  3798  3798 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 07:10:39.944  3798  3798 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 07:10:39.954  3798  3823 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-17 07:10:39.964  1020  2883 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,03-17 07:10:39.964  1020  2883 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.964  1020  2883 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.964  1020  2883 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:39.964  1020  2883 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:39.964  3798  3823 I KLMS-2.5.183: : KLMSIntentService(): BOOT_COMPLETED
,03-17 07:10:39.984  3847  3847 E Zygote  : MountEmulatedStorage()
03-17 07:10:39.984  3847  3847 E Zygote  : v2
03-17 07:10:39.984  3847  3847 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:39.984  3847  3847 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:39.984  3847  3847 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:39.994  1020  2883 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3847 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 07:10:39.994  3847  3847 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 07:10:39.994  3847  3847 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:39.994  3245  3353 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,03-17 07:10:40.004  1020  2883 I ActivityManager: Killing 3066:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,03-17 07:10:40.024  3847  3847 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:40.024  3847  3847 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:40.034  1311  3234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,03-17 07:10:40.034  1020  2934 I ActivityManager: Killing 3090:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,03-17 07:10:40.034  1311  3234 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,03-17 07:10:40.044  1311  3234 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
,03-17 07:10:40.064  3798  3798 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-17 07:10:40.094  1020  1491 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.accesscontrol, hostingType: broadcast
,03-17 07:10:40.094  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.094  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 07:10:40.104  3847  3847 E MTPRx   : In MtpReceiverandroid.intent.action.BOOT_COMPLETED
03-17 07:10:40.094  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.094  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.124  3865  3865 E Zygote  : MountEmulatedStorage()
,03-17 07:10:40.124  3865  3865 E Zygote  : v2
03-17 07:10:40.124  3865  3865 I libpersona: KNOX_SDCARD checking this for 1000
,03-17 07:10:40.124  3865  3865 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:40.134  3865  3865 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 07:10:40.134  3865  3865 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 07:10:40.144  1020  1491 I ActivityManager: Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3865 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:40.144  1020  1491 I ActivityManager: Killing 3143:com.sec.usbsettings/1000 (adj 15): empty #31
,03-17 07:10:40.144  3865  3865 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:40.164  1020  1044 W libprocessgroup: failed to open /acct/uid_10157/pid_3066/cgroup.procs: No such file or directory
,03-17 07:10:40.164  1020  2883 D SecContentProvider2: uri = 14 selection = getSealedState
,03-17 07:10:40.164  3865  3865 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:40.174  3865  3865 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:40.174  1020  2883 D SecContentProvider2: mCursor = null
,03-17 07:10:40.174  1020  1362 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-17 07:10:40.174  1020  1362 D SecContentProvider2: mCursor = null
,03-17 07:10:40.174  3847  3847 V MTPRx   : sealedState: false
03-17 07:10:40.174  3847  3847 V MTPRx   : sealedUsbMassStorageState: false
,03-17 07:10:40.184  1020  2880 D SettingsProvider: name = mtp_usb_connection_status
,03-17 07:10:40.194  1020  1033 D SettingsProvider: name = media_player_mode
,03-17 07:10:40.194  1020  1516 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 07:10:40.204  1020  2933 D SettingsProvider: name = mtp_running_status
,03-17 07:10:40.214  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:40.224  1020  1344 D SettingsProvider: name = media_mount_count
,03-17 07:10:40.234  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:40.234  1020  2931 D SettingsProvider: name = mtp_sync_alive
,03-17 07:10:40.234  1020  2933 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:40.234  1020  2933 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 07:10:40.244  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:40.254  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:40.264  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:40.264  1020  2883 D SettingsProvider: name = sdcard_launch
,03-17 07:10:40.274  1020  1307 D SettingsProvider: name = boot_time_connected
,03-17 07:10:40.274  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:40.274  1020  1491 D SettingsProvider: name = mtp_open_session
,03-17 07:10:40.274  1020  1344 D PowerManagerService: [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1187 (0x0)
,03-17 07:10:40.284  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:40.294  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:40.334  3578  3578 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-17 07:10:40.334  3578  3578 I PCWCLIENTTRACE_PushUtil: sales region : global
,03-17 07:10:40.334  3578  3578 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,03-17 07:10:40.334  3578  3578 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.BOOT_COMPLETED
,03-17 07:10:40.334  3578  3578 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Version: 4.82
03-17 07:10:40.334  3578  3578 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Push type: [SPP, GCM]
,03-17 07:10:40.354  3578  3578 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,03-17 07:10:40.364  3370  3647 I System.out: pool-10-thread-1 calls detatch()
,03-17 07:10:40.394  1020  1130 I art     : Explicit concurrent mark sweep GC freed 27201(1451KB) AllocSpace objects, 2(38KB) LOS objects, 33% free, 26MB/40MB, paused 2.781ms total 180.630ms
,03-17 07:10:40.404  1020  1032 D SettingsProvider: name = access_control_enabled
,03-17 07:10:40.404  3578  3578 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-17 07:10:40.414  1020  2931 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,03-17 07:10:40.414  3578  3578 I ReactiveServiceManager: Supported : 1
,03-17 07:10:40.414  1020  1130 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 07:10:40.414  1020  1516 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,03-17 07:10:40.414  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.414  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.414  1020  1516 D QSEECOMAPI: : App is not loaded in QSEE
03-17 07:10:40.414  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.414  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.434  3888  3888 E Zygote  : MountEmulatedStorage(),
,03-17 07:10:40.434  3888  3888 E Zygote  : v2,
,03-17 07:10:40.434  3888  3888 I libpersona: KNOX_SDCARD checking this for 10069
03-17 07:10:40.434  3888  3888 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:40.434  3888  3888 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:40.434  3888  3888 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:40.444  3888  3888 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:40.444  3779  3886 I Gmail   : getAccountsCursor
,03-17 07:10:40.444  1020  2931 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3888 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:40.454  1020  1516 D QSEECOMAPI: : Loaded image: APP id = 9
,03-17 07:10:40.454  1020  2931 I ActivityManager: Killing 1577:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,03-17 07:10:40.454  1020  1033 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-17 07:10:40.454  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 07:10:40.464  1020  1516 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-17 07:10:40.464  1020  1516 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 9
03-17 07:10:40.464  1020  1516 E terrier : handleString: Failed to handle string(-4)
03-17 07:10:40.464  1020  1516 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,03-17 07:10:40.474  3578  3578 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-17 07:10:40.474  3578  3578 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
03-17 07:10:40.474   309   309 I art     : Explicit concurrent mark sweep GC freed 8764(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 639us total 26.934ms
,03-17 07:10:40.474  3578  3578 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 07:10:40.474  3578  3578 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 07:10:40.474  3578  3578 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 07:10:40.474  3578  3578 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,03-17 07:10:40.474  1020  2883 D ActivityManager: startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
,03-17 07:10:40.484  1020  2883 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.484  1020  2883 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.484  1020  2883 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.484  1020  2883 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.484  1879  1879 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:40.494  3888  3888 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:40.494  1020  1307 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 07:10:40.494  3888  3888 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:40.494   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 25.451ms
,03-17 07:10:40.514   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 19.111ms
,03-17 07:10:40.524  1020  2880 I AudioService: getStreamVolume 3 index 0
,03-17 07:10:40.534  3904  3904 E Zygote  : MountEmulatedStorage()
03-17 07:10:40.534  3904  3904 I libpersona: KNOX_SDCARD checking this for 10031
03-17 07:10:40.534  3904  3904 E Zygote  : v2
03-17 07:10:40.534  3904  3904 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:40.534  3904  3904 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 07:10:40.534  1020  2883 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3904 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
03-17 07:10:40.534  3904  3904 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:40.534  1020  2883 I ActivityManager: Killing 3016:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
03-17 07:10:40.534  3904  3904 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:40.574  3904  3904 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:40.574  3904  3904 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:40.594  3779  3779 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-17 07:10:40.604  3904  3904 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 07:10:40.644  3888  3888 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,03-17 07:10:40.674  1020  1344 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,03-17 07:10:40.674  1020  1344 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,03-17 07:10:40.674  1020  1344 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:40.674  1020  1344 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:40.674  1824  3596 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 07:10:40.674  1020  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm,
,03-17 07:10:40.694  1020  1362 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,03-17 07:10:40.694  1020  1362 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,03-17 07:10:40.694  1020  1362 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:40.694  1020  1362 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:40.694  1020  1362 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 07:10:40.724  1020  1307 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:40.724  1020  1307 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 07:10:40.744   256   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 07:10:40.744   256   516 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:40.744  3357  3357 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 07:10:40.744   256   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 07:10:40.744   256   516 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:40.744  3357  3357 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-17 07:10:40.744  1020  2931 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,03-17 07:10:40.744   256   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 07:10:40.744   256   516 W Vold    : Returning OperationFailed - no handler for errno 0
03-17 07:10:40.744  1020  2931 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
03-17 07:10:40.744  3357  3357 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-17 07:10:40.754  3779  3925 E Gmail   : Error finding the version of the Email provider.....
03-17 07:10:40.754  3779  3925 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-17 07:10:40.754  3779  3925 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
03-17 07:10:40.754  3779  3925 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
03-17 07:10:40.754  3779  3925 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
03-17 07:10:40.754  3779  3925 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 07:10:40.754  3779  3925 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 07:10:40.754  3779  3925 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:40.754  3779  3925 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 07:10:40.754  3779  3925 W EmailMigration: We do not support migrating this version of the Email provider.
,03-17 07:10:40.754  1020  2931 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:40.754  1020  2931 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:40.754  1020  2931 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 07:10:40.764  1020  1033 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
03-17 07:10:40.764  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,03-17 07:10:40.764  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:40.764  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:40.764  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 07:10:40.774  3779  3931 I Gmail   : getAccountsCursor
,03-17 07:10:40.794  1020  2880 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,03-17 07:10:40.794  1020  2880 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 07:10:40.794  1020  1044 W libprocessgroup: failed to open /acct/uid_10159/pid_3090/cgroup.procs: No such file or directory
03-17 07:10:40.794  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3143/cgroup.procs: No such file or directory
,03-17 07:10:40.794  1020  1130 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,03-17 07:10:40.794  1020  1130 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-17 07:10:40.794  1020  1044 W libprocessgroup: failed to open /acct/uid_10072/pid_1577/cgroup.procs: No such file or directory
03-17 07:10:40.794  1020  1044 W libprocessgroup: failed to open /acct/uid_10085/pid_3016/cgroup.procs: No such file or directory
,03-17 07:10:40.804  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:40.804  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:40.804  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 07:10:40.804  1879  1879 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:40.804  1020  1344 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-17 07:10:40.804  1020  1344 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 07:10:40.814  1020  1516 I ActivityManager: Killing 3116:com.sec.dsm.system/1000 (adj 15): empty #31
,03-17 07:10:40.824  1020  1020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,03-17 07:10:40.824  1020  1020 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,03-17 07:10:40.824  1020  1020 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:40.824  1020  1020 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,03-17 07:10:40.824  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.834  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.834  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.834  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.844  3945  3945 E Zygote  : MountEmulatedStorage(),
03-17 07:10:40.844  3945  3945 E Zygote  : v2
03-17 07:10:40.844  3945  3945 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 07:10:40.844  3945  3945 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:40.844  3945  3945 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-17 07:10:40.844  1020  1020 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3945 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:40.854  1020  2934 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.syncadapters.contacts,
03-17 07:10:40.854  1020  2934 W ActivityManager: userId = 0, bbcId = -10000,
03-17 07:10:40.854  1020  2934 D ActivityManager: retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
03-17 07:10:40.854  1020  2934 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:40.854  1020  2934 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps,
,03-17 07:10:40.854  1020  1130 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:40.854  3945  3945 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 07:10:40.854  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:40.854  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:40.854  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 07:10:40.864  3945  3945 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:40.864  1020  1491 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,03-17 07:10:40.864  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.864  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.864  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:40.864  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:40.874  1637  3952 I GoogleHttpClient: GMS http client unavailable, use old client,
,03-17 07:10:40.884  1020  1491 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3972 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-17 07:10:40.884  3972  3972 E Zygote  : MountEmulatedStorage()
03-17 07:10:40.884  3972  3972 E Zygote  : v2
,03-17 07:10:40.884  3972  3972 I libpersona: KNOX_SDCARD checking this for 10104
03-17 07:10:40.884  3972  3972 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:40.894  3972  3972 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:40.894  3945  3945 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:40.894  3945  3945 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:40.894  3972  3972 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 07:10:40.894  3972  3972 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:40.934  3972  3972 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:40.934  3972  3972 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:40.954  1020  1033 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,03-17 07:10:40.954  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-17 07:10:40.954  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:40.964  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:40.964  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 07:10:40.964  3972  3972 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 07:10:40.974  1020  1362 I ActivityManager: Killing 3207:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,03-17 07:10:40.984  1020  1033 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 07:10:40.994  3904  3904 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
,03-17 07:10:41.004  3245  3353 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,03-17 07:10:41.014  3357  3372 W art     : Suspending all threads took: 8.632ms
,03-17 07:10:41.024  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3116/cgroup.procs: No such file or directory
,03-17 07:10:41.044  3945  3945 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,03-17 07:10:41.044  1020  2880 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
03-17 07:10:41.044  1020  2880 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
03-17 07:10:41.044  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3207/cgroup.procs: No such file or directory
03-17 07:10:41.044  1020  2880 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:41.044  1020  2880 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:41.044  1020  2880 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-17 07:10:41.044  3904  3904 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
,03-17 07:10:41.054  1020  1033 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,03-17 07:10:41.054  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:41.054  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.054  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.054  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:41.074  3997  3997 E Zygote  : MountEmulatedStorage()
03-17 07:10:41.074  3997  3997 E Zygote  : v2
03-17 07:10:41.074  3997  3997 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:41.074  3997  3997 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:41.074  3997  3997 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:41.074  3997  3997 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:41.084  3997  3997 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:41.084  1020  1033 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3997 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 07:10:41.084  1020  1307 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
03-17 07:10:41.094  1020  1307 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-17 07:10:41.094  1020  2883 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
03-17 07:10:41.094  1020  2883 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-17 07:10:41.104  3997  3997 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:41.104  3997  3997 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:41.114  1020  2931 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 07:10:41.114  1020  2931 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 07:10:41.124  3779  3779 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@34caa444 that was originally bound here
03-17 07:10:41.124  3779  3779 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@34caa444 that was originally bound here
03-17 07:10:41.124  3779  3779 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
03-17 07:10:41.124  3779  3779 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
03-17 07:10:41.124  3779  3779 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
03-17 07:10:41.124  3779  3779 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
03-17 07:10:41.124  3779  3779 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
03-17 07:10:41.124  3779  3779 E ActivityThread: 	at com.android.emailcommon.service.ah.a(SourceFile:181)
03-17 07:10:41.124  3779  3779 E ActivityThread: 	at com.android.emailcommon.service.ah.e(SourceFile:224)
03-17 07:10:41.124  3779  3779 E ActivityThread: 	at com.android.email.service.n.c(SourceFile:161)
03-17 07:10:41.124  3779  3779 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:173)
03-17 07:10:41.124  3779  3779 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:117)
03-17 07:10:41.124  3779  3779 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:318)
03-17 07:10:41.124  3779  3779 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1308)
03-17 07:10:41.124  3779  3779 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 07:10:41.124  3779  3779 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 07:10:41.124  3779  3779 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:41.124  3779  3779 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 07:10:41.124  1020  1033 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@2d4263e5
,03-17 07:10:41.144  3997  3997 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,03-17 07:10:41.144  1020  2933 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,03-17 07:10:41.144  1020  2933 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
03-17 07:10:41.144  1020  2933 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:41.154  1020  2933 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:41.154  1020  2933 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 07:10:41.154  1020  2931 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
03-17 07:10:41.154  1020  2931 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-17 07:10:41.154  1020  2931 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:41.154  1020  2931 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:41.154  1020  2931 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 07:10:41.164  1020  2883 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,03-17 07:10:41.164  1020  2883 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,03-17 07:10:41.164  1020  2883 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:41.164  1020  2883 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:41.164  1020  2883 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 07:10:41.184  1020  2880 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 07:10:41.184  1020  2880 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 07:10:41.194  3779  3932 E SQLiteLog: (283) recovered 24 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-17 07:10:41.204  1020  1516 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
03-17 07:10:41.204  1020  1516 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,03-17 07:10:41.204  1020  1516 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:41.204  1020  1516 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:41.204  1020  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 07:10:41.214  3779  4007 I Gmail   : Observing account changes for notifications
,03-17 07:10:41.214  1980  1980 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,03-17 07:10:41.214  1020  2933 D ActivityManager: startService callerProcessName:com.qualcomm.qti.services.secureui, calleePkgName: com.qualcomm.qti.services.secureui
03-17 07:10:41.214  1020  2933 D ActivityManager: retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
,03-17 07:10:41.214  1020  2933 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:41.214  1020  2933 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:41.224  1020  2933 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,03-17 07:10:41.224  1020  1033 D ActivityManager: startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,03-17 07:10:41.234  1980  1980 D SecUISvc: Service started flags 0 startId 1
,03-17 07:10:41.234  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.234  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.234  1980  4023 D SecUISvc: Thread created.
03-17 07:10:41.234  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.234  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:41.244  4025  4025 E Zygote  : MountEmulatedStorage(),
03-17 07:10:41.244  4025  4025 E Zygote  : v2
03-17 07:10:41.244  4025  4025 I libpersona: KNOX_SDCARD checking this for 10028
,03-17 07:10:41.244  4025  4025 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:41.244  1020  1033 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4025 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 07:10:41.244  4025  4025 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:41.254  4025  4025 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:41.254  4025  4025 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:41.274  1020  1516 I ActivityManager: Killing 3260:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,03-17 07:10:41.274  1020  1516 I ActivityManager: Killing 3226:com.samsung.android.app.colorblind/1000 (adj 15): empty #32
,03-17 07:10:41.274  4025  4025 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:41.284  4025  4025 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:41.294  3904  3904 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,03-17 07:10:41.294  3904  3904 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,03-17 07:10:41.314  3904  3904 D DialogFlow: initQueue()
,03-17 07:10:41.334  1020  1344 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,03-17 07:10:41.334  1020  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:41.344  1020  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.344  1020  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:41.344  1020  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:41.374  4041  4041 E Zygote  : MountEmulatedStorage()
03-17 07:10:41.374  4041  4041 I libpersona: KNOX_SDCARD checking this for 10032
03-17 07:10:41.374  4041  4041 E Zygote  : v2
03-17 07:10:41.374  4041  4041 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:41.374  4041  4041 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:41.374  4041  4041 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:41.384  4041  4041 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:41.384  1020  1344 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4041 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,03-17 07:10:41.384  1020  1344 I ActivityManager: Killing 3274:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,03-17 07:10:41.404  4041  4041 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:41.404  4041  4041 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:41.484  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3226/cgroup.procs: No such file or directory
,03-17 07:10:41.494  1020  1044 W libprocessgroup: failed to open /acct/uid_10150/pid_3260/cgroup.procs: No such file or directory
,03-17 07:10:41.494  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3274/cgroup.procs: No such file or directory
,03-17 07:10:41.584  1020  2880 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
,03-17 07:10:41.584  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.584  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.584  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:41.584  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:41.594  4062  4062 E Zygote  : MountEmulatedStorage()
03-17 07:10:41.594  4062  4062 E Zygote  : v2
03-17 07:10:41.594  4062  4062 I libpersona: KNOX_SDCARD checking this for 10033
03-17 07:10:41.594  4062  4062 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:41.594  4062  4062 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:41.604  4062  4062 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:41.604  4062  4062 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
03-17 07:10:41.604  1020  2880 I ActivityManager: Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4062 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 07:10:41.624  4062  4062 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:41.624  4062  4062 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:41.734   287   287 E SMD     : DCD OFF
,03-17 07:10:41.784  4025  4025 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-17 07:10:41.804  3394  3478 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-17 07:10:41.804  3394  3478 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-17 07:10:41.814  3394  3478 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-17 07:10:41.824  3394  3478 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-17 07:10:41.844  3357  4017 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A500FU Build/LRX22G)
,03-17 07:10:41.854  3357  4017 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,03-17 07:10:41.854  3357  4017 I System.out: Thread-493(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 07:10:41.854  3357  4017 I System.out: Thread-493(ApacheHTTPLog):isSBSettingEnabled false
03-17 07:10:41.854  3357  4017 I System.out: Thread-493(ApacheHTTPLog):isShipBuild true
03-17 07:10:41.854  3357  4017 I System.out: Thread-493(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 07:10:41.854  3357  4017 I System.out: Thread-493(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 07:10:41.854   277  1015 D EnterpriseController: uids 10166
03-17 07:10:41.854   277  1015 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 07:10:41.854   277  1015 D Netd    : getNetworkForDns: using netid 502 for uid 10166
,03-17 07:10:41.864  3779  3932 E File    : fail readDirectory() errno=2
,03-17 07:10:41.864  3394  3478 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-17 07:10:41.884  3779  3998 I Gmail   : notifyAccountChanged
,03-17 07:10:41.894  3394  3478 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-17 07:10:41.894  3394  3478 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-17 07:10:41.914  3779  3998 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 07:10:41.954  4062  4062 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,03-17 07:10:41.954  4062  4062 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:41.954  4062  4062 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 07:10:41.964  1020  1491 D TimaService: TIMA: in getTimaVersion
03-17 07:10:41.964  1020  1033 I ActivityManager: Killing 3294:com.google.android.configupdater/u0a86 (adj 15): empty #31
,03-17 07:10:41.964  1020  1344 D TimaService: TIMA3: KeyStore3_init
03-17 07:10:41.964  1020  1344 E TLC_TZ_KEYSTORE: : Inside TZ_KEYSTORE_initialize()
03-17 07:10:41.964  1020  1344 D TimaService: TIMA: in getTimaVersion
03-17 07:10:41.964  1020  1344 I TLC_TZ_KEYSTORE: : creating new keystore context...
03-17 07:10:41.964  1020  1344 I TLC_TZ_KEYSTORE: : initializing ccm context...
03-17 07:10:41.964  1020  1344 I TLC_TZ_KEYSTORE: : root = /firmware/image, root_strlen = 15
03-17 07:10:41.964  1020  1344 I TLC_TZ_KEYSTORE: : process = tima_key, process_strlen = 8
03-17 07:10:41.964  1020  1344 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
03-17 07:10:41.964  1020  1344 I TZ: qc_tlc_communication: process = tima_key, process_strlen = 8
03-17 07:10:41.964  1020  1344 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 1088 = 0x440
03-17 07:10:41.964  1020  1344 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 1088 = 0x440
03-17 07:10:41.964  1020  1344 I TZ: qc_tlc_communication: max_message_size = 2176 = 0x880
03-17 07:10:41.964  1020  1344 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x880
03-17 07:10:41.964  1020  1344 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 07:10:41.974  1020  2793 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,03-17 07:10:41.984  1020  1344 D QSEECOMAPI: : Loaded image: APP id = 10
,03-17 07:10:41.984  1020  1344 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
,03-17 07:10:41.984  1020  1344 I TLC_TZ_KEYSTORE: : ctx = 0xb88f7b70, comm = 0xb883c788, sendmsg = 0x9f0a9000, recvmsg = 0x9f0a9440
03-17 07:10:41.984  1020  1344 I TZ_init: : TZ_init: sending initialization request...
,03-17 07:10:41.984  4062  4062 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 07:10:41.984  4062  4062 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:41.984  4062  4062 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:41.994  1020  1344 E TZ_init: : TZ_init Process: Secure memory is not initialized!
,03-17 07:10:41.994  1020  1344 E TZ_init: : trustlet initialization failed
,03-17 07:10:41.994  1020  1344 I TZ_init: : TZ_init_START...
,03-17 07:10:41.994  1020  1344 I TZ_init: : TZ_init_with_data: sending initialization request...
,03-17 07:10:41.994  1020  1344 I TZ_init: : TZ_init: successful initialization
,03-17 07:10:41.994  1020  1344 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-17 07:10:41.994  1020  1344 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 10
,03-17 07:10:42.004  1020  1344 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
,03-17 07:10:42.004  4062  4062 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 07:10:42.004  3245  3353 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,03-17 07:10:42.004  4062  4062 W ResourcesManager: Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
03-17 07:10:42.004  4062  4062 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 07:10:42.014  1020  2931 D ActivityManager: bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
03-17 07:10:42.014  1020  2931 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-17 07:10:42.014  1020  2931 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:42.014  1020  2931 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:42.014  1020  2931 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 07:10:42.014  1879  1879 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:42.024  1879  1879 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:42.104  3972  4093 I Babel   : MmsConfig: mnc/mcc: 0/0
03-17 07:10:42.104  3972  4093 I Babel   : MmsConfig.loadMmsSettings
,03-17 07:10:42.104  3972  4093 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
03-17 07:10:42.104  3972  4093 I Babel   : MmsConfig.loadFromDatabase
,03-17 07:10:42.104  1020  1044 W libprocessgroup: failed to open /acct/uid_10086/pid_3294/cgroup.procs: No such file or directory
,03-17 07:10:42.104  3779  3998 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 07:10:42.124  3997  3997 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
,03-17 07:10:42.124  1020  2883 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:42.124  1020  2883 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:42.124  1020  2883 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:42.124  1020  2883 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:42.134  1020  2931 D ActivityManager: startService callerProcessName:com.samsung.android.bbc.bbcagent, calleePkgName: com.samsung.android.bbc.bbcagent
,03-17 07:10:42.134  1020  2931 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,03-17 07:10:42.144  1020  2931 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:42.144  1020  2931 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:42.144  1020  2931 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,03-17 07:10:42.144  1020  2933 D ActivityManager: startProcessLocked calleePkgName: com.sec.bcservice, hostingType: broadcast
,03-17 07:10:42.144  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:42.144  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:42.144  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:42.144  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:42.164  4096  4096 E Zygote  : MountEmulatedStorage()
03-17 07:10:42.164  4096  4096 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:42.164  4096  4096 E Zygote  : v2
03-17 07:10:42.164  4096  4096 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:42.164  4096  4096 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:42.164  4096  4096 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:42.174  4096  4096 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:42.174  1020  2933 I ActivityManager: Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=4096 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:42.184  3972  4093 E Babel   : canonicalizeMccMnc: invalid mccmnc 
03-17 07:10:42.184  3972  4093 I Babel   : MmsConfig.loadFromResources
,03-17 07:10:42.184  3972  4093 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,03-17 07:10:42.184  3972  4093 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,03-17 07:10:42.184  1020  2793 D SSRM:n  : SIOP:: AP = 390
,03-17 07:10:42.194  4096  4096 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:42.204  4096  4096 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:42.224  4096  4096 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 07:10:42.264  1020  2934 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,03-17 07:10:42.264  1020  2934 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,03-17 07:10:42.264  1020  2934 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:42.264  1020  2934 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:42.264  1020  2934 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 07:10:42.274  1020  2883 W SEAMService:  hashset_to_int_array returning null
,03-17 07:10:42.284  4096  4096 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,03-17 07:10:42.284  1020  1344 D ActivityManager: startService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.bcservice
,03-17 07:10:42.284  1020  1344 D ActivityManager: retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,03-17 07:10:42.284  1020  1344 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:42.284  1020  1344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:42.284  1020  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,03-17 07:10:42.284  1020  1491 W SEAMService:  hashset_to_int_array returning null
,03-17 07:10:42.304  3997  3997 E SQLiteLog: (284) automatic index on seams_container_info(seams_container_id)
,03-17 07:10:42.304  3972  3972 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-17 07:10:42.314  3997  3997 E SQLiteLog: (284) automatic index on seams_container_info(sp_id)
,03-17 07:10:42.324  1020  1032 W SEAMService:  hashset_to_int_array returning null
,03-17 07:10:42.324  1020  1130 I ActivityManager: Killing 3370:com.dropbox.android/u0a92 (adj 15): empty #31
,03-17 07:10:42.334  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
03-17 07:10:42.334  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:42.334  3945  4014 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:42.334  3945  4014 I AMMetaDataParserService: getResourcePackageName:assistantlist
03-17 07:10:42.334  3945  4014 I AMMetaDataParserService: Resource data:2131165186
,03-17 07:10:42.334  4096  4096 I F_PHONE : [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,03-17 07:10:42.334  4096  4096 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,03-17 07:10:42.334  1020  1344 D ActivityManager: bindService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.phone, action: null
,03-17 07:10:42.334  1020  1344 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,03-17 07:10:42.334  1020  1344 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:42.334  1020  1344 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:42.334  1020  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,03-17 07:10:42.354  3945  4014 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 07:10:42.354  3945  4014 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:42.354  3945  4014 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 07:10:42.354  3945  4014 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 07:10:42.354  3945  4014 I AMMetaDataParserService: getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
03-17 07:10:42.354  3945  4014 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:42.364  4096  4096 D F_PHONE : [[com.sec.bcservice]] onServiceConnected()
,03-17 07:10:42.364  4096  4096 I F_PHONE : default registerAction()
,03-17 07:10:42.364  4096  4096 I F_PHONE : [[com.sec.bcservice]] sendPendingMessage()
,03-17 07:10:42.364  3779  3998 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 07:10:42.374  3779  3998 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 07:10:42.374  3945  4014 I AMMetaDataParserService: Icon data: ResourceEnter URL2131755289android.intent.action.doInputURL2130837509
,03-17 07:10:42.384  4025  4025 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,03-17 07:10:42.414  3972  3972 I Babel_StickerModule: App launched.
,03-17 07:10:42.424  3357  4017 I System.out: Thread-493 calls detatch()
,03-17 07:10:42.444  4025  4025 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 07:10:42.444  3945  4014 I AMMetaDataParserService: Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,03-17 07:10:42.464  1020  2875 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 07:10:42.464  3945  4014 I AMMetaDataParserService: Icon data: ResourceNew Tab2131755460android.intent.action.doNewWindow2130837510
03-17 07:10:42.464  1020  1044 W libprocessgroup: failed to open /acct/uid_10092/pid_3370/cgroup.procs: No such file or directory
,03-17 07:10:42.474  4025  4025 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-17 07:10:42.474  3972  3972 V Babel   : babel boot account: SMS
,03-17 07:10:42.474  3972  3972 W Babel   : EsDatabaseHelper.static should not be called on main thread [called on main thread]
,03-17 07:10:42.474  3972  3972 W Babel   : java.lang.Exception
03-17 07:10:42.474  3972  3972 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
03-17 07:10:42.474  3972  3972 W Babel   : 	at aes.<clinit>(SourceFile:95)
03-17 07:10:42.474  3972  3972 W Babel   : 	at ckh.<init>(SourceFile:103)
03-17 07:10:42.474  3972  3972 W Babel   : 	at ckh.a(SourceFile:67)
03-17 07:10:42.474  3972  3972 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
03-17 07:10:42.474  3972  3972 W Babel   : 	at bhn.a(SourceFile:301)
03-17 07:10:42.474  3972  3972 W Babel   : 	at bhn.a(SourceFile:137)
03-17 07:10:42.474  3972  3972 W Babel   : 	at bhn.a(SourceFile:126)
03-17 07:10:42.474  3972  3972 W Babel   : 	at bhn.a(SourceFile:159)
03-17 07:10:42.474  3972  3972 W Babel   : 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
03-17 07:10:42.474  3972  3972 W Babel   : 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
03-17 07:10:42.474  3972  3972 W Babel   : 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-17 07:10:42.474  3972  3972 W Babel   : 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-17 07:10:42.474  3972  3972 W Babel   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 07:10:42.474  3972  3972 W Babel   : 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:42.474  3972  3972 W Babel   : 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 07:10:42.474  3972  3972 W Babel   : 	at java.lang.reflect.Method.invoke(Native Method)
03-17 07:10:42.474  3972  3972 W Babel   : 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 07:10:42.474  3972  3972 W Babel   : 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 07:10:42.474  3972  3972 W Babel   : 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-17 07:10:42.494  3972  3972 W Babel   : EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,03-17 07:10:42.494  3972  3972 W Babel   : java.lang.Exception
03-17 07:10:42.494  3972  3972 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
03-17 07:10:42.494  3972  3972 W Babel   : 	at aes.a(SourceFile:145)
03-17 07:10:42.494  3972  3972 W Babel   : 	at ckh.<init>(SourceFile:103)
03-17 07:10:42.494  3972  3972 W Babel   : 	at ckh.a(SourceFile:67)
03-17 07:10:42.494  3972  3972 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
03-17 07:10:42.494  3972  3972 W Babel   : 	at bhn.a(SourceFile:301)
03-17 07:10:42.494  3972  3972 W Babel   : 	at bhn.a(SourceFile:137)
03-17 07:10:42.494  3972  3972 W Babel   : 	at bhn.a(SourceFile:126)
03-17 07:10:42.494  3972  3972 W Babel   : 	at bhn.a(SourceFile:159)
03-17 07:10:42.494  3972  3972 W Babel   : 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
03-17 07:10:42.494  3972  3972 W Babel   : 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
03-17 07:10:42.494  3972  3972 W Babel   : 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-17 07:10:42.494  3972  3972 W Babel   : 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-17 07:10:42.494  3972  3972 W Babel   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 07:10:42.494  3972  3972 W Babel   : 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:42.494  3972  3972 W Babel   : 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 07:10:42.494  3972  3972 W Babel   : 	at java.lang.reflect.Method.invoke(Native Method)
03-17 07:10:42.494  3972  3972 W Babel   : 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 07:10:42.494  3972  3972 W Babel   : 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 07:10:42.494  3972  3972 W Babel   : 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
03-17 07:10:42.504  3945  4014 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.,SelectBookmarkFolderActivity
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
03-17 07:10:42.504  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,03-17 07:10:42.534  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
,03-17 07:10:42.544  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:42.544  3945  4014 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:42.544  3945  4014 I AMMetaDataParserService: Resource data:2131034113
,03-17 07:10:42.554  4025  4113 D Volley  : [593] DiskBasedCache.clear: Cache cleared.
,03-17 07:10:42.564  3945  4014 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 07:10:42.564  3945  4014 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:42.564  3945  4014 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 07:10:42.564  3945  4014 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-17 07:10:42.564  3945  4014 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:42.564  1020  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:42.564  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:42.564  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:42.564  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:42.574  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:42.574  4025  4083 D Volley  : [586] DiskBasedCache.clear: Cache cleared.
,03-17 07:10:42.574  3945  4014 I GFX construct_block_size_descriptor_2d second part: took 3.033906ms for 0*0 texture 0
,03-17 07:10:42.584  4025  4025 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-17 07:10:42.584  4025  4025 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,03-17 07:10:42.584  1020  1130 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
03-17 07:10:42.584  1020  1130 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-17 07:10:42.584  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:42.584  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:42.584  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 07:10:42.584  1020  1491 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,03-17 07:10:42.594  1020  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
03-17 07:10:42.594  4025  4137 D Ads     : Skipping gmscore version check
,03-17 07:10:42.594  3945  4014 I GFX generate_partition_tables: took 7.173958ms for 0*0 texture 0
,03-17 07:10:42.594  3945  4014 I GFX raster: took 11.691509ms for 96*96 texture 0
03-17 07:10:42.594  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83ddb18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb83ddae0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:42.614  3945  4014 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-17 07:10:42.624  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:42.624  1020  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:42.624  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-17 07:10:42.634  1020  2931 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,03-17 07:10:42.634  1020  2931 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-17 07:10:42.644  1020  2931 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:42.644  1020  2931 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:42.644  1020  2931 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 07:10:42.644  1020  1344 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,03-17 07:10:42.644  1020  1344 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-17 07:10:42.654  2076  4138 D FileApkUtils: Optimizing (staging complete)
,03-17 07:10:42.654  2076  4138 D FileApkUtils: Optimizing: DynamiteModules-prod.apk [0224a548494bce36274e23f9f1b42d4fbe3d4d8de53a7872e503f8974e43c3c3]
,03-17 07:10:42.654  2076  4138 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
,03-17 07:10:42.664  1020  1344 W ActivityManager: userId = 0, bbcId = -10000,
03-17 07:10:42.664  1020  1344 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:42.664  1020  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
03-17 07:10:42.664  3972  3972 V Babel   : babel boot account: thalitester@gmail.com
,03-17 07:10:42.664  2076  4138 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk appears to be unoptimized.
03-17 07:10:42.664  2076  4138 D DexOptUtils: Lollipop platform, using <isa> directory.
,03-17 07:10:42.664  2076  4138 D DexOptUtils: Instantiating DexClassLoader to force creation of odex.
03-17 07:10:42.664  2076  4138 D DexOptUtils: Primary ABI of odexing process is armeabi-v7a
,03-17 07:10:42.674  3972  3972 W Babel   : EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,03-17 07:10:42.674  3972  3972 W Babel   : java.lang.Exception
03-17 07:10:42.674  3972  3972 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
03-17 07:10:42.674  3972  3972 W Babel   : 	at aes.a(SourceFile:145)
03-17 07:10:42.674  3972  3972 W Babel   : 	at ckh.<init>(SourceFile:103)
03-17 07:10:42.674  3972  3972 W Babel   : 	at ckh.a(SourceFile:67)
03-17 07:10:42.674  3972  3972 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
03-17 07:10:42.674  3972  3972 W Babel   : 	at bhn.a(SourceFile:301)
03-17 07:10:42.674  3972  3972 W Babel   : 	at bhn.a(SourceFile:137)
03-17 07:10:42.674  3972  3972 W Babel   : 	at bhn.a(SourceFile:126)
03-17 07:10:42.674  3972  3972 W Babel   : 	at bhn.a(SourceFile:159)
03-17 07:10:42.674  3972  3972 W Babel   : 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
03-17 07:10:42.674  3972  3972 W Babel   : 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
03-17 07:10:42.674  3972  3972 W Babel   : 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-17 07:10:42.674  3972  3972 W Babel   : 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-17 07:10:42.674  3972  3972 W Babel   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 07:10:42.674  3972  3972 W Babel   : 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:42.674  3972  3972 W Babel   : 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 07:10:42.674  3972  3972 W Babel   : 	at java.lang.reflect.Method.invoke(Native Method)
03-17 07:10:42.674  3972  3972 W Babel   : 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 07:10:42.674  3972  3972 W Babel   : 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 07:10:42.674  3972  3972 W Babel   : 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-17 07:10:42.684  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:42.684  3945  4014 I GFX raster: took 1.020417ms for 96*96 texture 0
03-17 07:10:42.684  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83ddb18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb83ddae0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:42.694  3945  4014 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 07:10:42.734  1020  1307 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
03-17 07:10:42.734  1020  1307 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-17 07:10:42.734  1020  1307 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:42.734  1020  1307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:42.734  1020  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 07:10:42.734  1020  1362 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,03-17 07:10:42.734  1020  1362 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-17 07:10:42.744  1020  1362 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:42.744  1020  1362 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:42.744  1020  1362 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 07:10:42.754  1020  1130 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,03-17 07:10:42.754  1020  1130 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-17 07:10:42.754  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:42.754  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:42.754  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 07:10:42.754  1020  2883 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,03-17 07:10:42.754  1020  2883 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:42.754  1020  2883 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:42.754  1020  2883 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:42.754  1020  2883 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:42.774  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,03-17 07:10:42.774  3945  4014 I GFX construct_block_size_descriptor_2d second part: took 2.403386ms for 0*0 texture 0,
,03-17 07:10:42.784  4143  4143 E Zygote  : MountEmulatedStorage(),
,03-17 07:10:42.784  4143  4143 E Zygote  : v2,
03-17 07:10:42.784  1020  2883 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4143 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 07:10:42.784  4143  4143 I libpersona: KNOX_SDCARD checking this for 1000
,03-17 07:10:42.784  4143  4143 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:42.794  4143  4143 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 07:10:42.794  4143  4143 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 07:10:42.794  4143  4143 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:42.804  3945  4014 I GFX generate_partition_tables: took 7.610520ms for 0*0 texture 0
,03-17 07:10:42.804  3945  4014 I GFX raster: took 10.966562ms for 96*96 texture 0
03-17 07:10:42.804  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83ddae0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83e25d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:42.814  4062  4062 I Process : Sending signal. PID: 4062 SIG: 9
,03-17 07:10:42.824  4143  4143 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:42.824  1020  1130 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:42.824  4143  4143 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:42.834  3945  4014 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 07:10:42.854  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:42.854  3945  4014 I GFX raster: took 0.624427ms for 96*96 texture 0
,03-17 07:10:42.854  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83e7178 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83e72d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:42.864  1020  1130 W ActivityManager: userId = 0, bbcId = -10000,
03-17 07:10:42.864  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:42.864  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-17 07:10:42.864   282  2141 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,03-17 07:10:42.874   282  2141 W QCamera2Factory: getCameraInfo: X
,03-17 07:10:42.884   282   282 W QCamera2Factory: getCameraInfo: E, camera_id = 1
03-17 07:10:42.884   282   282 W QCamera2Factory: getCameraInfo: X
,03-17 07:10:42.894  3945  4014 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 07:10:42.904  1020  2883 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 07:10:42.904  1020  2883 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,03-17 07:10:42.914  1020  2883 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:42.914  1020  2883 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:42.914  1020  2883 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:42.924  1020  2931 I art     : Explicit concurrent mark sweep GC freed 29543(1929KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 26MB/40MB, paused 2.831ms total 204.811ms
,03-17 07:10:42.934  1020  1046 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
,03-17 07:10:42.934  1020  1046 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
,03-17 07:10:42.944  1020  1046 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
,03-17 07:10:42.954  1020  1032 I ActivityManager: Process com.sec.android.app.sns3 (pid 4062)(adj 0) has died(40,1131)
,03-17 07:10:42.954  4025  4025 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-17 07:10:42.954  4141  4141 I dex2oat : ----------------------------------------------------
03-17 07:10:42.954  4141  4141 I dex2oat : <SS>: S T A R T I N G . . .
03-17 07:10:42.954  4141  4141 I dex2oat : <SS>: Zip is absent. Canceled.
03-17 07:10:42.954  4141  4141 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk --oat-fd=45 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-17 07:10:42.954  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:42.954  1020  1045 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,03-17 07:10:42.954  3945  4014 I GFX raster: took 0.916146ms for 96*96 texture 0
03-17 07:10:42.954  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83e3b80 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83e3cd8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:42.964  3945  4014 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 07:10:42.974  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:42.974  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:42.974  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:42.974  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:42.984  3972  3972 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 07:10:42.984  4161  4161 E Zygote  : MountEmulatedStorage()
,03-17 07:10:42.984  4161  4161 E Zygote  : v2,
,03-17 07:10:42.994  4161  4161 I libpersona: KNOX_SDCARD checking this for 10034,
03-17 07:10:42.994  4161  4161 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:42.994  4161  4161 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 07:10:42.994  4161  4161 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 07:10:42.994  1020  1045 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4161 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
03-17 07:10:42.994  4161  4161 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:42.994  1020  2883 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
03-17 07:10:42.994  1020  2883 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:42.994  1020  2883 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
03-17 07:10:42.994  1020  2883 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:42.994  1020  2883 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-17 07:10:43.014  3245  3353 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,03-17 07:10:43.014  3972  3972 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 07:10:43.024  3972  3972 W AudioCapabilities: Unsupported mime audio/qcelp
,03-17 07:10:43.024  4161  4161 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:43.034  4161  4161 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:43.054  3972  3972 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,03-17 07:10:43.054  3972  3972 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,03-17 07:10:43.054  3578  3589 D PCWCLIENTTRACE_AccountAppFacade2_0: unregister AuthInfo UpdateReceiver v2.0
,03-17 07:10:43.064  3972  3972 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,03-17 07:10:43.064  3972  3972 W AudioCapabilities: Unsupported mime audio/x-ima
,03-17 07:10:43.064  3972  3972 W AudioCapabilities: Unsupported mime audio/qcelp
,03-17 07:10:43.064  3972  3972 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 07:10:43.084  3972  3972 W VideoCapabilities: Unsupported mime video/wvc1
,03-17 07:10:43.094  3972  3972 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 07:10:43.094  4025  4025 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-17 07:10:43.114  3972  3972 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,03-17 07:10:43.114  2076  2076 W InstanceID/Rpc: Found 10012
,03-17 07:10:43.124  3972  3972 W VideoCapabilities: Unsupported mime video/wvc1
,03-17 07:10:43.124  3972  3972 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 07:10:43.124  3972  3972 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,03-17 07:10:43.124  3972  3972 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,03-17 07:10:43.134  3972  3972 W VideoCapabilities: Unsupported mime video/mp43
,03-17 07:10:43.144  3972  3972 W VideoCapabilities: Unsupported mime video/sorenson
,03-17 07:10:43.144  3972  3972 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,03-17 07:10:43.154  1020  1307 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 07:10:43.154  1020  1307 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,03-17 07:10:43.164  1020  1307 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:43.164  1020  1307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:43.164  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:43.164  1020  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:43.164  3945  4014 I GFX raster: took 0.793438ms for 96*96 texture 0
03-17 07:10:43.164  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83ddf68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83e2660 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:43.174  3945  4014 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 07:10:43.184  1020  2883 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 07:10:43.184  1020  2883 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,03-17 07:10:43.184  3972  3972 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-17 07:10:43.184  1020  2883 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:43.184  1020  2883 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:43.194  1020  2883 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:43.204  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:43.204  1020  1032 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-17 07:10:43.204  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 07:10:43.204  3945  4014 I GFX raster: took 0.861355ms for 96*96 texture 0
03-17 07:10:43.204  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83e2660 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83e4848 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:43.214  1020  2934 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,03-17 07:10:43.214  1879  1879 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:43.214  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.214  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.214  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.214  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.214  3945  4014 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 07:10:43.234  1020  2934 I ActivityManager: Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=4181 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 07:10:43.244  4181  4181 E Zygote  : MountEmulatedStorage(),
03-17 07:10:43.244  4181  4181 E Zygote  : v2
,03-17 07:10:43.244  4181  4181 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 07:10:43.244  4181  4181 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:43.244  4181  4181 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 07:10:43.254  4181  4181 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 07:10:43.254  3779  4187 I Gmail   : getAccountsCursor
,03-17 07:10:43.264  4181  4181 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 07:10:43.274   309   309 I art     : Explicit concurrent mark sweep GC freed 8774(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 668us total 37.028ms
,03-17 07:10:43.274  1020  1516 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-17 07:10:43.274  1020  1516 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 07:10:43.284   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 17.039ms
,03-17 07:10:43.294  4181  4181 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:43.294  4181  4181 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:43.314   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 20.499ms
,03-17 07:10:43.314  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 07:10:43.314  3945  4014 I GFX raster: took 0.530469ms for 96*96 texture 0
03-17 07:10:43.314  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83e2230 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83e2b40 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:43.314  3945  4014 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 07:10:43.334  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
03-17 07:10:43.334  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:43.334  3945  4014 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:43.334  3945  4014 I AMMetaDataParserService: Resource data:2131034113
03-17 07:10:43.334  3945  4014 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-17 07:10:43.334  3945  4014 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:43.334  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 07:10:43.334  3945  4014 I GFX raster: took 0.821980ms for 96*96 texture 0
03-17 07:10:43.334  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83ddb18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb83e29d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:43.344  3945  4014 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-17 07:10:43.344  1020  1516 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 07:10:43.344  1020  1516 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,03-17 07:10:43.344  1020  1516 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:43.354  3779  3886 I Gmail   : getAccountsCursor
,03-17 07:10:43.354  1020  1516 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:43.354  1020  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:43.354  1020  2880 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,03-17 07:10:43.354  1020  2880 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 07:10:43.364  1879  1879 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:43.374  1020  2934 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 07:10:43.374  1020  2934 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,03-17 07:10:43.374  1020  2934 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:43.374  1020  2934 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:43.374  1020  2934 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:43.384  1020  1491 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,03-17 07:10:43.384  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.384  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.384  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.384  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.394  2076  2076 D BootCompletedReceiver: Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,03-17 07:10:43.394  2076  2076 D BootCompletedReceiver: Got an BootCompleted event.
,03-17 07:10:43.404  4200  4200 E Zygote  : MountEmulatedStorage()
,03-17 07:10:43.404  4200  4200 I libpersona: KNOX_SDCARD checking this for 10035
03-17 07:10:43.404  4200  4200 E Zygote  : v2
03-17 07:10:43.404  4200  4200 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:43.404  4200  4200 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 07:10:43.404  4200  4200 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:43.404  4200  4200 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-17 07:10:43.414  1020  1491 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4200 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 07:10:43.414  1020  1491 I ActivityManager: Killing 3403:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,03-17 07:10:43.414  1020  1032 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
03-17 07:10:43.414  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,03-17 07:10:43.424  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:43.424  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:43.424  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 07:10:43.434  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:43.434  3945  4014 I GFX raster: took 1.037917ms for 96*96 texture 0
03-17 07:10:43.434  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83ddb18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb83e3cd8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:43.444  3945  4014 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 07:10:43.444  4181  4181 D KnoxSetupWizardDbHelper: dbMigrationFlag : false
,03-17 07:10:43.454  4200  4200 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:43.454  4200  4200 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:43.474  1020  1033 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 07:10:43.474  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,03-17 07:10:43.474  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:43.474  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:43.474  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:43.494  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:43.494  3945  4014 I GFX raster: took 0.604219ms for 96*96 texture 0
03-17 07:10:43.494  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83ddae0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83de160 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:43.504  2076  2076 D BootCompletedReceiver: Will NOT schedule AdAttestation signal task because it's disabled.
,03-17 07:10:43.514  4041  4056 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 07:10:43.524  4181  4181 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED,
,03-17 07:10:43.534  4181  4181 D KnoxShortcutUtil: getIsShortcutMigrationFor_2_3_0_Done true
,03-17 07:10:43.534  4181  4181 D ShortcutReceiver:  KnoxContainerVersion 2.4.0
03-17 07:10:43.534  4181  4181 D ShortcutReceiver:  shortcut migration not required 
,03-17 07:10:43.544  3945  4014 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 07:10:43.544  1020  1362 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,03-17 07:10:43.544  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.544  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.544  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.544  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.564  1020  1362 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4223 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 07:10:43.564  1020  1362 I ActivityManager: Killing 3488:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,03-17 07:10:43.564  4223  4223 E Zygote  : MountEmulatedStorage(),
03-17 07:10:43.574  4223  4223 E Zygote  : v2,
03-17 07:10:43.574  4223  4223 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 07:10:43.574  4223  4223 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:43.574  4223  4223 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 07:10:43.574  4223  4223 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 07:10:43.574  4223  4223 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:43.594  4223  4223 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:43.594  4223  4223 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:43.594  1020  2880 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 07:10:43.594  1020  2880 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,03-17 07:10:43.604  1020  2880 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:43.604  1020  2880 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:43.604  1020  2880 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:43.604  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:43.604  3945  4014 I GFX raster: took 0.603750ms for 96*96 texture 0
03-17 07:10:43.604  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83e7178 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83d85c0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:43.624  3945  4014 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 07:10:43.624  2076  4180 D GCM     : COMPAT: Multi user not supported
,03-17 07:10:43.634  1020  1307 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 07:10:43.634  1020  1307 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-17 07:10:43.634  1020  1307 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:43.634  1020  1307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:43.634  1020  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:43.644  1879  1879 D GCM     : COMPAT: Multi user not supported
,03-17 07:10:43.654  1020  1130 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 07:10:43.654  1020  1130 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,03-17 07:10:43.654  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:43.654  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:43.654  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:43.674  3904  3918 W art     : Suspending all threads took: 183.940ms
,03-17 07:10:43.684  1020  1044 W libprocessgroup: failed to open /acct/uid_10057/pid_3403/cgroup.procs: No such file or directory
,03-17 07:10:43.684  1020  1130 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 07:10:43.684  1020  1130 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,03-17 07:10:43.694  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:43.694  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:43.694  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:43.694  4200  4200 E SPPClientService: [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,03-17 07:10:43.704  4200  4239 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
03-17 07:10:43.704  4200  4239 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,03-17 07:10:43.704  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:43.704  3945  4014 I GFX raster: took 0.844219ms for 96*96 texture 0
03-17 07:10:43.704  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83e3b80 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83e4a68 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:43.714  1020  1362 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 07:10:43.714  1020  1362 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 07:10:43.714  1020  1362 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:43.714  1020  1362 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:43.714  1020  1362 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:43.734  1020  1033 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 07:10:43.734  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,03-17 07:10:43.734  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:43.734  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:43.734  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:43.744  1020  1032 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 07:10:43.744  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-17 07:10:43.744  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:43.744  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:43.744  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:43.754  2076  4180 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,03-17 07:10:43.754  1020  1344 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
,03-17 07:10:43.754  1020  1344 W ActivityManager: userId = 0, bbcId = -10000,
03-17 07:10:43.754  1020  1344 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0,
03-17 07:10:43.754  1020  1344 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:43.754  1020  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:43.764  4223  4223 E KnoxSetupWizardClient: isShipMode : 1,
03-17 07:10:43.764  4223  4223 I KnoxSetupWizardClient: onReceive : android.intent.action.BOOT_COMPLETED
,03-17 07:10:43.794  1020  2931 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 07:10:43.794  1020  2931 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4312, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
03-17 07:10:43.794  1020  2931 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,03-17 07:10:43.794  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 07:10:43.794  1020  1020 I MotionRecognitionService: Plugged
,03-17 07:10:43.804  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 07:10:43.804  1187  1187 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 07:10:43.804  1187  1187 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 07:10:43.814  1430  1430 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-17 07:10:43.814  1430  1430 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 07:10:43.814  3945  4014 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 07:10:43.824  2687  2687 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 07:10:43.824  2687  2763 D HeadsetStateMachine: Disconnected process message: 10
,03-17 07:10:43.834  1187  1187 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 07:10:43.834  1187  1187 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 07:10:43.834  1187  1187 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 07:10:43.844  2076  4242 I CheckinService: Disabling old GoogleServicesFramework version
,03-17 07:10:43.874  1020  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 07:10:43.874  1020  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,03-17 07:10:43.874  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:43.874  1020  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:43.874  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:43.874  2076  2076 D SystemUpdateService: onCreate
,03-17 07:10:43.884  1020  1307 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,03-17 07:10:43.894  4200  4239 D SPPClientService: PushLog.txt file is not deleted.
03-17 07:10:43.894  4200  4239 D SPPClientService: PushLog.txt file is not deleted.
03-17 07:10:43.894  4200  4239 D SPPClientService: ============PushLog. stop!
,03-17 07:10:43.894  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:43.894  3945  4014 I GFX raster: took 0.707812ms for 96*96 texture 0
03-17 07:10:43.894  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83ddf68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83e3cd8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:43.894  1020  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.894  1020  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.894  1020  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.904  1020  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.914  4250  4250 E Zygote  : MountEmulatedStorage()
,03-17 07:10:43.914  4250  4250 E Zygote  : v2
03-17 07:10:43.914  4250  4250 I libpersona: KNOX_SDCARD checking this for 10107
03-17 07:10:43.914  4250  4250 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:43.914  4250  4250 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:43.924  1020  1307 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4250 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-17 07:10:43.924  1020  1307 I ActivityManager: Killing 3501:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,03-17 07:10:43.924  4250  4250 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:43.924  4250  4250 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:43.934  3972  4221 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-17 07:10:43.964  1020  2933 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,03-17 07:10:43.964  3945  4014 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 07:10:43.964  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.974  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.974  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:43.974  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:43.974  4250  4250 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:43.984  4250  4250 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:43.994  4264  4264 E Zygote  : MountEmulatedStorage()
03-17 07:10:43.994  4264  4264 E Zygote  : v2
03-17 07:10:43.994  4264  4264 I libpersona: KNOX_SDCARD checking this for 10041
03-17 07:10:43.994  4264  4264 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:43.994  4264  4264 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:43.994  4264  4264 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:43.994  4264  4264 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 07:10:44.004  1020  2933 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4264 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:44.004  1020  2933 I ActivityManager: Killing 3534:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,03-17 07:10:44.034  3245  3353 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,03-17 07:10:44.044  4264  4264 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:44.044  4264  4264 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:44.044  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:44.044  3945  4014 I GFX raster: took 0.710625ms for 96*96 texture 0
03-17 07:10:44.044  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83e2660 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83e08f8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:44.044  3972  4221 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-17 07:10:44.054  3945  4014 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 07:10:44.064  2076  2076 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-17 07:10:44.074  4223  4243 W System.err: java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,03-17 07:10:44.074  4223  4243 W System.err: 	at android.os.Parcel.readException(Parcel.java:1544)
03-17 07:10:44.074  4223  4243 W System.err: 	at android.os.Parcel.readException(Parcel.java:1493)
03-17 07:10:44.074  4223  4243 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
03-17 07:10:44.074  4223  4243 W System.err: 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
03-17 07:10:44.074  4223  4243 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
03-17 07:10:44.074  4223  4243 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,03-17 07:10:44.084  2076  4281 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
,03-17 07:10:44.114  3972  4221 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-17 07:10:44.124  1020  1307 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 07:10:44.124  2076  4281 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED
,03-17 07:10:44.124  1020  1307 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 07:10:44.144  4041  4056 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 07:10:44.144  4041  4056 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 07:10:44.144  4041  4056 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:44.164  1020  1307 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:44.164  1020  1307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:44.164  1020  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:44.164  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:44.164  3945  4014 I GFX raster: took 0.551771ms for 96*96 texture 0
,03-17 07:10:44.164  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83e37e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8397f08 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:44.174  1020  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
03-17 07:10:44.174  1020  1044 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,03-17 07:10:44.204  1020  1098 V AlarmManager: waitForAlarm result :4
,03-17 07:10:44.214  3972  4221 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-17 07:10:44.214  3945  4014 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527,
,03-17 07:10:44.234  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:44.234  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:44.234  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:44.234  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:44.234  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:44.234  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactShortcut
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activityalias.DialShortcut
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activityalias.MessageShortcut
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:44.274  3945 , 4014 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:44.274  3945  4014 I AMMetaDataParserService: Resource data:2131034112
,03-17 07:10:44.284  3945  4014 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_detail
03-17 07:10:44.284  3945  4014 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:44.284  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:44.284  3945  4014 I GFX raster: took 0.624167ms for 96*96 texture 0
03-17 07:10:44.284  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83a91c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8361b10 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:44.294  3945  4014 I AMMetaDataParserService: Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,03-17 07:10:44.304  4264  4264 I SA      : [SSP] onCreated
,03-17 07:10:44.334  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:44.334  3945  4014 I GFX raster: took 0.598906ms for 96*96 texture 0
03-17 07:10:44.334  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83a91c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83e2230 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:44.344  1020  2934 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:44.344  1020  2934 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:44.344  1020  2934 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:44.344  1020  2934 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:44.354  1020  1045 I ActivityManager: Waited long enough for: ServiceRecord{10f6f17c u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,03-17 07:10:44.354  1020  1098 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,03-17 07:10:44.354  1020  1130 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:44.364  3972  4221 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-17 07:10:44.364  3945  4014 I AMMetaDataParserService: Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,03-17 07:10:44.374  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:44.374  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:44.374  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:44.384  2076  4280 I SystemUpdateService: cancelUpdate (empty URL)
03-17 07:10:44.384  2076  4280 I SystemUpdateService: active receiver: disabled
,03-17 07:10:44.394  1020  1033 I ActivityManager: Killing 3553:com.fmm.dm/1000 (adj 15): empty #31
,03-17 07:10:44.424  1020  1042 D SensorService: [SO] 0.134 0.402 10.113
,03-17 07:10:44.434  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,03-17 07:10:44.434  3945  4014 I GFX raster: took 0.692761ms for 96*96 texture 0
03-17 07:10:44.434  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8361b10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb83c5a88 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:44.444  2076  4281 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 07:10:44.444  4264  4264 I SA      : [TPM] There is no property file
,03-17 07:10:44.454  2076  4245 I CheckinService: Checking schedule, now: 1458195044465 next: 1458246240395
03-17 07:10:44.454  2076  4245 I CheckinService: active receiver: disabled
,03-17 07:10:44.454  3945  4014 I AMMetaDataParserService: Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,03-17 07:10:44.454  4264  4264 I SA      : [SCU] isHaveSA() - false
,03-17 07:10:44.464  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:44.464  3945  4014 I GFX raster: took 0.633386ms for 96*96 texture 0
03-17 07:10:44.464  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8397f08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83e2230 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:44.464  3945  4014 I AMMetaDataParserService: Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,03-17 07:10:44.474  1020  1044 W libprocessgroup: failed to open /acct/uid_10092/pid_3488/cgroup.procs: No such file or directory
,03-17 07:10:44.474  4264  4264 I SA      : [TPM] getModelProperty : null
,03-17 07:10:44.484  4264  4264 I SA      : [TPM] getCSCProperty : null
,03-17 07:10:44.484  4264  4264 I SA      : [DM] FLOATING AMOLED FEATURE: true
03-17 07:10:44.484  4264  4264 I SA      : [DM] PRODUCT AMOLED FEATURE: false
03-17 07:10:44.484  4264  4264 I SA      : [DM] TFT FEATURE: false
,03-17 07:10:44.494  4264  4264 I SA      : [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
03-17 07:10:44.494  4264  4264 I SA      : [DM] init START
,03-17 07:10:44.494  1020  1044 W libprocessgroup: failed to open /acct/uid_10003/pid_3501/cgroup.procs: No such file or directory
03-17 07:10:44.494  1020  1044 W libprocessgroup: failed to open /acct/uid_10060/pid_3534/cgroup.procs: No such file or directory
,03-17 07:10:44.514  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3553/cgroup.procs: No such file or directory
,03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.em,ergency.InteractionEmergencyMessageActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:44.524  3945  4014 I AMMetaDataParserService: Resource data:2131034113
,03-17 07:10:44.524  1020  2934 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 07:10:44.534  1020  2934 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:44.534  1020  2934 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:44.534  1020  2934 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:44.554  4264  4264 I SA      : [DM] This device is not a Vodafone
,03-17 07:10:44.564  4264  4264 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,03-17 07:10:44.564  4264  4264 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,03-17 07:10:44.564  4264  4264 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,03-17 07:10:44.564  4264  4264 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,03-17 07:10:44.574  4264  4264 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,03-17 07:10:44.574  4264  4264 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,03-17 07:10:44.574  4264  4264 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,03-17 07:10:44.574  4264  4264 W ResourceType: No package identifier when getting value for resource number 0x00000000
,03-17 07:10:44.574  4264  4264 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,03-17 07:10:44.574  4264  4264 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,03-17 07:10:44.574  4264  4264 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,03-17 07:10:44.584  4264  4264 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,03-17 07:10:44.584  4264  4264 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,03-17 07:10:44.584  4264  4264 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,03-17 07:10:44.584  4264  4264 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,03-17 07:10:44.584  4264  4264 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,03-17 07:10:44.584  4264  4264 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,03-17 07:10:44.584  4264  4264 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,03-17 07:10:44.594  3945  4014 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-17 07:10:44.594  3945  4014 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:44.594  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:44.594  3945  4014 I GFX raster: took 0.828437ms for 96*96 texture 0
03-17 07:10:44.594  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83e2230 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb83c5a88 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:44.594  4264  4264 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,03-17 07:10:44.594  4264  4264 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
03-17 07:10:44.594  4264  4264 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,03-17 07:10:44.604  4264  4264 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,03-17 07:10:44.604  4264  4264 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
03-17 07:10:44.604  4264  4264 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,03-17 07:10:44.604  4264  4264 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,03-17 07:10:44.614  3945  4014 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-17 07:10:44.634  2076  4281 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,03-17 07:10:44.644  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:44.644  3945  4014 I GFX raster: took 0.901720ms for 96*96 texture 0
,03-17 07:10:44.644  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83e2230 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb83c5a88 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:44.654  4264  4264 I SA      : [SCU] isHaveSA() - false
,03-17 07:10:44.654  4264  4264 I SA      : support phone number id : false
03-17 07:10:44.654  4264  4264 I SA      : [DM] Supports Ref Jpn : true
,03-17 07:10:44.654  4264  4264 I SA      : [DM] init END
,03-17 07:10:44.664  4264  4264 I SA      : [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,03-17 07:10:44.664  4264  4264 I SA      : [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,03-17 07:10:44.674  1020  1516 D ActivityManager: startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
03-17 07:10:44.674  1020  1516 D ActivityManager: retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,03-17 07:10:44.674  1020  1516 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:44.674  1020  1516 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-17 07:10:44.674  1020  1516 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,03-17 07:10:44.674  4264  4264 I SA      : [OR] onReceive END
,03-17 07:10:44.674  1020  2933 D ActivityManager: startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,03-17 07:10:44.674  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:44.674  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:44.674  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:44.674  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:44.674  2076  2076 D SystemUpdateService: onDestroy
,03-17 07:10:44.694  3945  4014 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 07:10:44.694  1020  2933 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4302 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:44.704  4302  4302 E Zygote  : MountEmulatedStorage()
03-17 07:10:44.704  4302  4302 I libpersona: KNOX_SDCARD checking this for 10042
03-17 07:10:44.704  4302  4302 E Zygote  : v2
03-17 07:10:44.704  4302  4302 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:44.704  4302  4302 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:44.704  4302  4302 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:44.704  4302  4302 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 07:10:44.704  4264  4264 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-17 07:10:44.714  4264  4264 I SA      : [ODM] queryOpenData(key= GEO_IP )
,03-17 07:10:44.724  4264  4264 I SA      : getMccForGalaxyJpn step2 GEO_IP MCC : 260
,03-17 07:10:44.724  4264  4264 I SA      : [LBE] REF_JPN : true
,03-17 07:10:44.724  4264  4264 I SA      : [BDC] create
,03-17 07:10:44.724  4302  4302 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:44.724  4302  4302 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:44.734   287   287 E SMD     : DCD OFF
03-17 07:10:44.734  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:44.744  3945  4014 I GFX raster: took 0.701511ms for 96*96 texture 0
03-17 07:10:44.744  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83c5a88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83d1fd0 counterpartCT=4 counterpartW=96 counterparth=96,
,03-17 07:10:44.744  3945  4014 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 07:10:44.784  1637  2198 I art     : Explicit concurrent mark sweep GC freed 4290(181KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 814us total 55.101ms
,03-17 07:10:44.794  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:44.794  4264  4264 I SA      : [DBMV2] getEmailID
,03-17 07:10:44.794  3945  4014 I GFX raster: took 0.652552ms for 96*96 texture 0
03-17 07:10:44.794  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83a91c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8380870 counterpartCT=4 counterpartW=96 counterparth=96
03-17 07:10:44.794  1637  1663 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-17 07:10:44.794  4264  4264 I SA      : [DBMV2] getDataV02ForItems
,03-17 07:10:44.794  4264  4264 I SA      : [SSP] query invoked
,03-17 07:10:44.804  3945  4014 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 07:10:44.804  4264  4264 I SA      : [SCU] get signed id from samsung account2.0 DB.
,03-17 07:10:44.824  4264  4264 I SA      : [SCU] get signed id from samsung account1.0 DB.
,03-17 07:10:44.834  4264  4264 I SA      : [BDC] destroy
,03-17 07:10:44.834  1020  2934 I ActivityManager: Killing 2851:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,03-17 07:10:44.834  4302  4302 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-17 07:10:44.834  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:44.834  3945  4014 I GFX raster: took 0.825625ms for 96*96 texture 0
,03-17 07:10:44.834  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8590900 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83e3778 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:44.864  3945  4014 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 07:10:44.904  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:44.904  3945  4014 I GFX raster: took 0.641406ms for 96*96 texture 0
03-17 07:10:44.904  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8397f08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83c4ad0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:44.914  3945  4014 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 07:10:44.934  1020  1044 W libprocessgroup: failed to open /acct/uid_10120/pid_2851/cgroup.procs: No such file or directory
,03-17 07:10:44.954  2076  4281 I AuthZen : Fetching signing key...
,03-17 07:10:44.954  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:44.954  3945  4014 I GFX raster: took 0.694635ms for 96*96 texture 0
03-17 07:10:44.954  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83e2660 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83c4ad0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:44.964  3945  4014 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 07:10:44.984  2076  4291 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 371 ms
,03-17 07:10:45.004  2076  4281 I AuthZen : Signing key fetched successfully!
,03-17 07:10:45.024  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:45.024  3945  4014 I GFX raster: took 0.529167ms for 96*96 texture 0
03-17 07:10:45.024  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83e37e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83c4ad0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:45.024  3945  4014 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 07:10:45.034  2076  4281 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 07:10:45.064  4302  4302 I CalendarProvider2: CalendarProvider2.onCreate() called
,03-17 07:10:45.084  2076  4281 D a       : Opening database auth.proximity.permit_store...
,03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
,03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
03-17 07:10:45.094  3945  4014 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
03-17 07:10:45.084  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,03-17 07:10:45.114  2076  4281 D AuthZenTransactionCache: Initialized cache in: /data/data/com.google.android.gms/files
,03-17 07:10:45.114  2076  4281 D AuthZenTransactionCache: Clearing transaction cache
,03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Welcome
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.DataConnection
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.Ac,countSecurity
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Debug
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageListXL
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:45.124  3945  4014 I AMMetaDataParserService: Resource data:2131165203
,03-17 07:10:45.124  1020  1060 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-17 07:10:45.134  3245  3353 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,03-17 07:10:45.134  3945  4014 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 07:10:45.134  3945  4014 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:45.134  3945  4014 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 07:10:45.134  3945  4014 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:45.134  3945  4014 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:45.144  3945  4014 I AMMetaDataParserService: getResourceName:com.android.email:xml/email_assistant_menu
03-17 07:10:45.144  3945  4014 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:45.144  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:45.144  3945  4014 I GFX construct_block_size_descriptor_2d second part: took 2.731250ms for 0*0 texture 0
,03-17 07:10:45.164  3945  4014 I GFX generate_partition_tables: took 10.059010ms for 0*0 texture 0
,03-17 07:10:45.194  3945  4014 I GFX raster: took 13.800470ms for 96*96 texture 0
03-17 07:10:45.194  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb858fc50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8590220 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:45.204  3945  4014 I AMMetaDataParserService: Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,03-17 07:10:45.214  1879  1879 I GCoreUlr: DispatchingService.onCreate()
,03-17 07:10:45.234  1879  4327 D GCM     : GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,03-17 07:10:45.234  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:45.234  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:45.234  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:45.234  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:45.234  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:45.234  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:45.234  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:45.234  3945  4014 I GFX raster: took 0.771354ms for 96*96 texture 0
03-17 07:10:45.234  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb873bc28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb873bcd0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:45.244  3945  4014 I AMMetaDataParserService: Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,03-17 07:10:45.254   277  1015 D EnterpriseController: uids 10012
03-17 07:10:45.254   277  1015 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 07:10:45.254   277  1015 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,03-17 07:10:45.324  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:45.324  3945  4014 I GFX raster: took 0.937969ms for 96*96 texture 0
03-17 07:10:45.324  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb873bc28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb873e310 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:45.324  1020  2880 I ActivityManager: Killing 3604:com.fmm.ds/1000 (adj 15): empty #31
,03-17 07:10:45.334  1020  1307 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 07:10:45.334  1020  1307 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,03-17 07:10:45.344  1020  1307 W ActivityManager: userId = 0, bbcId = -10000,
03-17 07:10:45.344  1020  1307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:45.344  1020  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.364  1879  4331 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,03-17 07:10:45.374  3945  4014 I AMMetaDataParserService: Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,03-17 07:10:45.384  1879  1879 W Auth    : [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,03-17 07:10:45.414  1020  1362 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 07:10:45.414  1020  1362 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,03-17 07:10:45.424  1020  1362 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.424  1020  1362 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:45.424  1020  1362 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.454  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3604/cgroup.procs: No such file or directory
,03-17 07:10:45.474  1879  1887 I art     : Explicit concurrent mark sweep GC freed 14782(937KB) AllocSpace objects, 10(160KB) LOS objects, 40% free, 12MB/21MB, paused 1.238ms total 92.055ms
,03-17 07:10:45.484  1879  1879 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 07:10:45.484  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:45.494  1879  2091 W GCoreFlp: No location to return for getLastLocation()
,03-17 07:10:45.494  1879  1887 W FusedLocationProvider: location=null
,03-17 07:10:45.504  1879  4326 I GCM     : GCM config loaded
,03-17 07:10:45.514  1879  2091 W GCoreFlp: No location to return for getLastLocation()
,03-17 07:10:45.514  1879  4318 W FusedLocationProvider: location=null
,03-17 07:10:45.524  3945  4014 I GFX raster: took 1.095364ms for 96*96 texture 0
03-17 07:10:45.524  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb873bc28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb873f850 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:45.524  3945  4014 I AMMetaDataParserService: Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,03-17 07:10:45.564  1879  1879 D PersistentNotificationBroadcastReceiver: Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,03-17 07:10:45.574  1020  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 07:10:45.574  1020  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.focus.ContactsSyncIntentService; callingUser = 0; userId(target) = 0
,03-17 07:10:45.574  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.574  1020  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:45.574  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.584  1020  1362 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 07:10:45.584  1020  1362 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncReceiverService; callingUser = 0; userId(target) = 0
,03-17 07:10:45.584  1020  1362 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.584  1020  1362 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:45.584  1020  1362 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.604  1020  1130 D ActivityManager: bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,03-17 07:10:45.604  1020  1130 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,03-17 07:10:45.604  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:45.604  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:45.604  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 07:10:45.614  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:45.614  3945  4014 I GFX raster: took 0.605000ms for 96*96 texture 0
03-17 07:10:45.614  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8740d78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8740e20 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:45.634  3945  4014 I AMMetaDataParserService: Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,03-17 07:10:45.644  3779  3919 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-17 07:10:45.684  1020  2883 D PowerManagerService: [s] UserActivityState : 1 -> 2
,03-17 07:10:45.684  1020  1054 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
,03-17 07:10:45.684  1020  1054 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 07:10:45.684  1020  1054 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-17 07:10:45.694  1020  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,03-17 07:10:45.694  1020  1044 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncService; callingUser = 0; userId(target) = 0
,03-17 07:10:45.694  1020  1173 D lights  : lcd : 36 +
,03-17 07:10:45.714  1020  1054 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
,03-17 07:10:45.714  1020  1054 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 07:10:45.714  1020  1173 D lights  : lcd : 36 -
03-17 07:10:45.714  1020  1173 D lights  : lcd : 19 +
,03-17 07:10:45.734  1020  1173 D lights  : lcd : 19 -
,03-17 07:10:45.734  1020  1054 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
03-17 07:10:45.734  1020  1054 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 07:10:45.754  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:45.754  3945  4014 I GFX raster: took 0.641251ms for 96*96 texture 0
,03-17 07:10:45.754  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8740d78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb87421c0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:45.764  3945  4014 I AMMetaDataParserService: Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,03-17 07:10:45.804  1879  4331 I GCoreUlr: WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,03-17 07:10:45.844  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
03-17 07:10:45.844  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
03-17 07:10:45.844  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
03-17 07:10:45.844  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
03-17 07:10:45.844  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
03-17 07:10:45.844  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageCompose
03-17 07:10:45.844  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:45.844  3945  4014 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-17 07:10:45.844  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
03-17 07:10:45.844  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
03-17 07:10:45.844  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
03-17 07:10:45.844  3945  4014 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 07:10:45.844  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
03-17 07:10:45.844  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
03-17 07:10:45.844  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.DebugActivity
03-17 07:10:45.844  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
03-17 07:10:45.844  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
03-17 07:10:45.844  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
03-17 07:10:45.844  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SearchActivity
03-17 07:10:45.844  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:45.844  3945  4014 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:45.844  3945  4014 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 07:10:45.844  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
03-17 07:10:45.844  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
03-17 07:10:45.844  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,03-17 07:10:45.984  1020  1344 I art     : Explicit concurrent mark sweep GC freed 32893(1833KB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 26MB/40MB, paused 2.541ms total 172.994ms
,03-17 07:10:46.094  1020  1307 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,03-17 07:10:46.094  1020  1307 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,03-17 07:10:46.124  1020  1307 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.124  1020  1307 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:46.124  1020  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-17 07:10:46.134  3245  3353 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,03-17 07:10:46.154  1020  1344 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
,03-17 07:10:46.154  1020  1344 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-17 07:10:46.154  1020  1344 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.154  1020  1344 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:46.154  1020  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
03-17 07:10:46.154  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
03-17 07:10:46.154  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
03-17 07:10:46.154  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
03-17 07:10:46.154  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
03-17 07:10:46.154  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
03-17 07:10:46.154  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:46.154  3945  4014 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-17 07:10:46.154  3945  4014 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 07:10:46.154  3945  4014 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:46.154  3945  4014 I AMMetaDataParserService: Resource data:2131099648
,03-17 07:10:46.164  3945  4014 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
03-17 07:10:46.164  3945  4014 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:46.164  3945  4014 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 07:10:46.164  3945  4014 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:46.164  3945  4014 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 07:10:46.164  3945  4014 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 07:10:46.164  3945  4014 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 07:10:46.164  3945  4014 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:46.164  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:46.174  3945  4014 I GFX raster: took 0.860782ms for 96*96 texture 0
,03-17 07:10:46.174  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83dd818 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83c56a0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:46.184  3945  4014 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 07:10:46.194  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:46.204  1879  4331 I GCoreUlr: Unbound from all location providers
03-17 07:10:46.204  1879  4331 I GCoreUlr: Place inference reporting - stopped
,03-17 07:10:46.204  3945  4014 I GFX construct_block_size_descriptor_2d second part: took 3.145104ms for 0*0 texture 0
,03-17 07:10:46.214  4250  4250 D StrictMode: StrictMode policy violation; ~duration=1747 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-17 07:10:46.214  4250  4250 D StrictMode: StrictMode policy violation; ~duration=1712 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-17 07:10:46.214  4250  4250 D StrictMode: StrictMode policy violation; ~duration=1244 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.io.File.doAccess(File.java:283)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.io.File.exists(File.java:363)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-17 07:10:46.214  4250  4250 D StrictMode: StrictMode policy violation; ~duration=1243 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-17 07:10:46.214  4250  4250 D StrictMode: StrictMode policy violation; ~duration=1243 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 07:10:46.214  4250  4250 D StrictMode: StrictMode policy violation; ~duration=1229 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.r.k.c(PG:1187)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.r.k.a(PG:2107)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.r.v.a(PG:1206)
03-17 07,:10:46.214  4250  4250 D StrictMode: 	at com.google.r.y.a(PG:2233)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.r.e.b(PG:170)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.r.e.b(PG:13188)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 07:10:46.214  4250  4250 D StrictMode: StrictMode policy violation; ~duration=1226 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.r.k.c(PG:1187)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.r.k.b(PG:14147)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.r.k.c(PG:583)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.r.v.a(PG:1206)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.r.y.a(PG:2233)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.r.e.b(PG:170)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.r.e.b(PG:13188)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 07:10:46.214  4250  4250 D StrictMode:, 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 07:10:46.214  4250  4250 D StrictMode: StrictMode policy violation; ~duration=1102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.io.File.doAccess(File.java:283)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.io.File.exists(File.java:363)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 07:10:46.214  4250  4250 D StrictMode: StrictMode policy violation; ~duration=1101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.io.File.doAccess(File.java:283)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.io.File.exists(File.java:363)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 07:10:46.214  4250  4250 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 07:10:46.224  1020  2934 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
03-17 07:10:46.224  3945  4014 I GFX generate_partition_tables: took 9.276771ms for 0*0 texture 0
03-17 07:10:46.224  3945  4014 I GFX raster: took 13.591511ms for 96*96 texture 0
03-17 07:10:46.224  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83c56a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb83ce568 counterpartCT=4 counterpartW=96 counterparth=96
03-17 07:10:46.234  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:46.234  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:46.234  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:46.234  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:46.244  3945  4014 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
03-17 07:10:46.254  4351  4351 E Zygote  : MountEmulatedStorage()
03-17 07:10:46.254  4351  4351 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:46.254  4351  4351 E Zygote  : v2
03-17 07:10:46.254  4351  4351 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:46.254  4351  4351 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:46.254  4351  4351 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:46.254  1020  2934 I ActivityManager: Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4351 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 07:10:46.254  4351  4351 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:46.254  1020  2934 I ActivityManager: Killing 3621:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
03-17 07:10:46.274  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 07:10:46.274  3945  4014 I GFX raster: took 0.833385ms for 96*96 texture 0
03-17 07:10:46.274  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83d1ed0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb83d0bc8 counterpartCT=4 counterpartW=96 counterparth=96
03-17 07:10:46.284  4351  4351 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:46.284  4351  4351 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:46.284  3945  4014 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
03-17 07:10:46.294  1879  1879 I GCoreUlr: DispatchingService.onDestroy()
03-17 07:10:46.294  1879  1879 I GCoreUlr: Stopping handler for UlrDispSvcFast
,03-17 07:10:46.304  1879  1879 I GCoreUlr: Unbound from all location providers
,03-17 07:10:46.304  1879  1879 I GCoreUlr: Place inference reporting - stopped
,03-17 07:10:46.324  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:46.324  3945  4014 I GFX raster: took 0.785052ms for 96*96 texture 0
03-17 07:10:46.324  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83cb3a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb83cb3d8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:46.324  4351  4351 D StatusChecker: onReceive : android.intent.action.BOOT_COMPLETED
,03-17 07:10:46.334  4351  4351 I StatusChecker: onReceive : net.mt.init : DONE
,03-17 07:10:46.334  1020  1130 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,03-17 07:10:46.334  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:46.334  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:46.334  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:46.334  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:46.344  3945  4014 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 07:10:46.354  4368  4368 E Zygote  : MountEmulatedStorage()
03-17 07:10:46.354  4368  4368 E Zygote  : v2
03-17 07:10:46.354  4368  4368 I libpersona: KNOX_SDCARD checking this for 10116
03-17 07:10:46.354  4368  4368 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:46.354  4368  4368 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:46.354  1020  1130 I ActivityManager: Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4368 uid=10116 gids={50116, 9997} abi=armeabi-v7a
,03-17 07:10:46.354  1020  1130 I ActivityManager: Killing 3650:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,03-17 07:10:46.354  4368  4368 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:46.364  4368  4368 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:46.384  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:46.384  3945  4014 I GFX raster: took 0.633229ms for 96*96 texture 0
03-17 07:10:46.384  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83c68c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83c68f8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:46.384  4368  4368 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:46.384  4368  4368 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:46.384  3945  4014 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 07:10:46.424  4368  4368 I PageBuddyNotiSvc: Intent received : action=android.intent.action.BOOT_COMPLETED
,03-17 07:10:46.424  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:46.424  3945  4014 I GFX raster: took 0.731457ms for 96*96 texture 0
,03-17 07:10:46.424  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83c86e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83c8718 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:46.434  3945  4014 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 07:10:46.434  4368  4368 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,03-17 07:10:46.434  1020  2883 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:46.444  1020  2883 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.444  1020  2883 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:46.444  1020  2883 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,03-17 07:10:46.444  1020  1516 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,03-17 07:10:46.444  4368  4368 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,03-17 07:10:46.444  1020  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:46.444  1020  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:46.444  1020  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:46.444  1020  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:46.454  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
,03-17 07:10:46.454  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
03-17 07:10:46.454  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:46.454  3945  4014 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:46.454  3945  4014 I AMMetaDataParserService: Resource data:2131099648
,03-17 07:10:46.454  3945  4014 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
,03-17 07:10:46.454  3945  4014 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:46.464  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,03-17 07:10:46.464  3945  4014 I GFX raster: took 0.683281ms for 96*96 texture 0
03-17 07:10:46.464  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83dd818 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83e1fb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:46.464  1020  1516 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4386 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
,03-17 07:10:46.474  3945  4014 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 07:10:46.474  4386  4386 E Zygote  : MountEmulatedStorage()
03-17 07:10:46.474  4386  4386 I libpersona: KNOX_SDCARD checking this for 10125
03-17 07:10:46.474  4386  4386 E Zygote  : v2
03-17 07:10:46.474  4386  4386 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:46.474  4386  4386 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:46.474  4386  4386 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:46.474  4386  4386 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:46.484  4386  4386 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:46.494  4386  4386 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:46.504  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:46.504  3945  4014 I GFX raster: took 0.644323ms for 96*96 texture 0
03-17 07:10:46.504  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83c56a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb83e1fb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:46.504  3945  4014 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 07:10:46.514  1020  1044 W libprocessgroup: failed to open /acct/uid_10062/pid_3621/cgroup.procs: No such file or directory
03-17 07:10:46.514  1020  1044 W libprocessgroup: failed to open /acct/uid_10094/pid_3650/cgroup.procs: No such file or directory
,03-17 07:10:46.514  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:46.514  3945  4014 I GFX raster: took 0.633385ms for 96*96 texture 0
,03-17 07:10:46.524  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83d1ed0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb83cb2d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:46.524  4386  4386 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:46.524  4386  4386 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 07:10:46.524  4386  4386 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 07:10:46.524  3945  4014 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 07:10:46.564  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:46.564  3945  4014 I GFX raster: took 0.638437ms for 96*96 texture 0
03-17 07:10:46.564  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83cb3a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb83e1fb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:46.574  3945  4014 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 07:10:46.594  4386  4386 D QuickConnect: PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,03-17 07:10:46.604  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:46.604  3945  4014 I GFX raster: took 0.712135ms for 96*96 texture 0
,03-17 07:10:46.604  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83c68c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83cb2d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:46.604  4386  4386 D QuickConnect: Util.setSCRunningSetting - [value]0
,03-17 07:10:46.614  3945  4014 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 07:10:46.614  1020  1516 D SettingsProvider: name = scon_is_running
,03-17 07:10:46.614  1020  1516 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-17 07:10:46.614  1020  1516 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:46.614  1020  1516 D SettingsProvider: selectionArgs: false
,03-17 07:10:46.614  1020  1516 D SettingsProvider: selectionArgs: 10125
,03-17 07:10:46.614  1020  1516 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,03-17 07:10:46.614  1020  1516 D SettingsProvider: ret = -1
,03-17 07:10:46.614  1020  1516 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,03-17 07:10:46.634  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:46.634  3945  4014 I GFX raster: took 0.726354ms for 96*96 texture 0
03-17 07:10:46.634  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83c86e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83e1fb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:46.634  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:46.634  4386  4386 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,03-17 07:10:46.634  4386  4386 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-17 07:10:46.644  1020  2933 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,03-17 07:10:46.644  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:46.644  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:46.644  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:46.644  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:46.654   256   507 I SecDataIO: Write to block,
,03-17 07:10:46.654  1020  2933 I ActivityManager: Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4401 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
03-17 07:10:46.664  3945  4014 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
03-17 07:10:46.664  1020  2933 I ActivityManager: Killing 3664:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,03-17 07:10:46.664  2641  3310 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,03-17 07:10:46.664  4401  4401 E Zygote  : MountEmulatedStorage()
03-17 07:10:46.664  4401  4401 I libpersona: KNOX_SDCARD checking this for 10131
03-17 07:10:46.664  4401  4401 E Zygote  : v2
03-17 07:10:46.664  4401  4401 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:46.674  4401  4401 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:46.674  3245  3245 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,03-17 07:10:46.674  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
03-17 07:10:46.674  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
03-17 07:10:46.674  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
03-17 07:10:46.674  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
03-17 07:10:46.674  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:46.674  3945  4014 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:46.674  3945  4014 I AMMetaDataParserService: Resource data:2131099648
03-17 07:10:46.674  3245  3245 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,03-17 07:10:46.674  3245  3245 E DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
03-17 07:10:46.674  4401  4401 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:46.674  4401  4401 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:46.684  3945  4014 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 07:10:46.684  3945  4014 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:46.684  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:46.684  3945  4014 I GFX raster: took 0.690312ms for 96*96 texture 0
03-17 07:10:46.684  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83dd818 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83e1fb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:46.704  3245  3245 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,03-17 07:10:46.704  2641  2641 I Process : Sending signal. PID: 2641 SIG: 9
03-17 07:10:46.704  4401  4401 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:46.704  4401  4401 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:46.714  3945  4014 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 07:10:46.724  4401  4401 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 07:10:46.724  4401  4401 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:46.724  4401  4401 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-17 07:10:46.724  4401  4401 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:46.754  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:46.754  3945  4014 I GFX raster: took 0.633542ms for 96*96 texture 0
03-17 07:10:46.754  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83c56a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb83e1fb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:46.764  3945  4014 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 07:10:46.774  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:46.774  3945  4014 I GFX raster: took 0.632864ms for 96*96 texture 0
03-17 07:10:46.774  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83d1ed0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb83cb2d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:46.794  3945  4014 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 07:10:46.794  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3664/cgroup.procs: No such file or directory
,03-17 07:10:46.804  1020  1033 I ActivityManager: Process com.sec.android.app.sysscope (pid 2641)(adj 0) has died(57,1088)
,03-17 07:10:46.814  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:46.814  3945  4014 I GFX raster: took 0.638698ms for 96*96 texture 0
03-17 07:10:46.814  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83cb3a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8740e18 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:46.814  4401  4401 D SBrowserFeatureFlag: initialized in static block : loadCscFeatureValue() succeed! 
,03-17 07:10:46.824  3945  4014 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 07:10:46.844  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:46.844  3945  4014 I GFX raster: took 0.634063ms for 96*96 texture 0
03-17 07:10:46.844  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83c68c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83e1fb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:46.844  3945  4014 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 07:10:46.854  4401  4401 D ManifestProvider: onCreate()
,03-17 07:10:46.874  4401  4401 E NetworkSettingsReceiver: onReceive: android.intent.action.BOOT_COMPLETED
,03-17 07:10:46.874  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:46.874  3945  4014 I GFX raster: took 0.728906ms for 96*96 texture 0
03-17 07:10:46.874  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83c86e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83cb2d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:46.884  4250  4293 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,03-17 07:10:46.894  3945  4014 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 07:10:46.904  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
03-17 07:10:46.904  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:46.904  3945  4014 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:46.904  3945  4014 I AMMetaDataParserService: Resource data:2131099648
,03-17 07:10:46.904  3945  4014 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 07:10:46.904  3945  4014 I AMMetaDataParserService: getResourceTypeNamexml
03-17 07:10:46.904  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:46.904  3945  4014 I GFX raster: took 0.681771ms for 96*96 texture 0
03-17 07:10:46.904  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83dd818 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83e1fb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:46.914  3945  4014 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 07:10:46.914  4401  4401 E SBrowserFeatureFlag: initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@2e785b77
,03-17 07:10:46.914  4401  4401 D SBrowserFeatureFlag: initialize : initSupportedPkg() succeed! 
03-17 07:10:46.914  4401  4401 I VerificationLog: SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,03-17 07:10:46.924  1020  2934 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,03-17 07:10:46.924  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:46.924  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:46.924  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:46.924  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:46.934  4420  4420 E Zygote  : MountEmulatedStorage()
,03-17 07:10:46.934  4420  4420 E Zygote  : v2
03-17 07:10:46.934  4420  4420 I libpersona: KNOX_SDCARD checking this for 10135
03-17 07:10:46.934  4420  4420 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:46.944  4420  4420 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:46.944  4420  4420 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 07:10:46.944  1020  2934 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4420 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
03-17 07:10:46.944  1020  2934 I ActivityManager: Killing 3687:com.sec.factory.camera/1000 (adj 15): empty #31
,03-17 07:10:46.944  4420  4420 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:46.964  4420  4420 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:46.964  4420  4420 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:46.964  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:46.964  3945  4014 I GFX raster: took 0.644688ms for 96*96 texture 0
,03-17 07:10:46.964  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83c56a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8740e18 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:46.974  3945  4014 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 07:10:46.984  4420  4420 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 07:10:46.984  4420  4420 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 07:10:46.984  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 07:10:46.984  4420  4420 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:46.994  1020  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:46.994  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:46.994  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:46.994  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
03-17 07:10:47.004  3945  4014 I GFX raster: took 0.644010ms for 96*96 texture 0
03-17 07:10:47.004  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83d1ed0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb83c8280 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:47.014  3945  4014 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 07:10:47.044  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:47.044  3945  4014 I GFX raster: took 0.646250ms for 96*96 texture 0
03-17 07:10:47.044  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83cb3a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb83c8280 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:47.064  3945  4014 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 07:10:47.064  1329  2648 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 07:10:47.074  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3687/cgroup.procs: No such file or directory
,03-17 07:10:47.074  1020  1491 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
03-17 07:10:47.074  1020  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,03-17 07:10:47.084  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:47.084  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:47.084  1020  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:47.084  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
03-17 07:10:47.084  3945  4014 I GFX raster: took 0.633959ms for 96*96 texture 0
03-17 07:10:47.084  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83c68c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83c8280 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:47.094  3945  4014 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 07:10:47.114  1020  2931 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
03-17 07:10:47.114  1020  2931 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,03-17 07:10:47.114  1020  2931 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:47.114  1020  2931 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:47.114  1020  2931 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-17 07:10:47.114  1020  1033 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,03-17 07:10:47.124  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.124  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.124  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.124  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.124  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:47.124  3945  4014 I GFX raster: took 0.746821ms for 96*96 texture 0
,03-17 07:10:47.124  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83c86e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83c8280 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:47.134  3945  4014 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524,
,03-17 07:10:47.134  4440  4440 E Zygote  : MountEmulatedStorage(),
03-17 07:10:47.144  4440  4440 E Zygote  : v2
,03-17 07:10:47.144  4440  4440 I libpersona: KNOX_SDCARD checking this for 10139
03-17 07:10:47.144  4440  4440 I libpersona: KNOX_SDCARD not a persona,
,03-17 07:10:47.144  3245  3353 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,03-17 07:10:47.144  4440  4440 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-17 07:10:47.144  3245  3353 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-17 07:10:47.144  4302  4302 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar },
,03-17 07:10:47.144  1020  1033 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4440 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a,
03-17 07:10:47.144  3245  3353 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,03-17 07:10:47.154  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0,
03-17 07:10:47.154  3245  3353 I DBG_DM  : [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,03-17 07:10:47.154  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:47.154  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
03-17 07:10:47.154  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-17 07:10:47.154  4440  4440 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 07:10:47.154  4440  4440 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:47.164  1020  1491 I ActivityManager: Killing 3463:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
03-17 07:10:47.164  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
03-17 07:10:47.164  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.164  3945  4014 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:47.164  3945  4014 I AMMetaDataParserService: Resource data:2131099648
,03-17 07:10:47.164  3945  4014 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging,
03-17 07:10:47.164  3945  4014 I AMMetaDataParserService: getResourceTypeNamexml
03-17 07:10:47.164  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:47.164  3945  4014 I GFX raster: took 0.681459ms for 96*96 texture 0
03-17 07:10:47.164  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83dd818 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83c8280 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:47.174  3945  4014 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 07:10:47.184  4440  4440 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:47.184   309   309 I art     : Explicit concurrent mark sweep GC freed 8720(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 653us total 37.224ms
03-17 07:10:47.184  4440  4440 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:47.204  4440  4440 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 07:10:47.204  4440  4440 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 07:10:47.204  4440  4440 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 07:10:47.204  4440  4440 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 07:10:47.204  4440  4440 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:47.204   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 18.290ms,
,03-17 07:10:47.224  4141  4217 W dex2oat : Verification of void maps.k.b$j.a(byte[], byte[]) took 141.344ms,
,03-17 07:10:47.224  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
03-17 07:10:47.224  3945  4014 I GFX raster: took 0.635469ms for 96*96 texture 0,
03-17 07:10:47.224  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83c56a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb83c8280 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:47.224  3245  3353 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220,
,03-17 07:10:47.234   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 649us total 21.861ms,
,03-17 07:10:47.234  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-17 07:10:47.234  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,03-17 07:10:47.234  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:47.244  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:47.244  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:47.244  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:47.244  3245  3353 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 8
,03-17 07:10:47.254  3945  4014 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 07:10:47.254  4141  4219 W dex2oat : Verification of void maps.k.b$m.a(byte[], byte[]) took 147.023ms
,03-17 07:10:47.264  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:47.264  3945  4014 I GFX raster: took 0.816303ms for 96*96 texture 0
03-17 07:10:47.264  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83d1ed0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb83c8280 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:47.294  1020  1338 E Watchdog: !@Sync 1
,03-17 07:10:47.294  3945  4014 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 07:10:47.294  3245  3353 I DBG_DM  : [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,03-17 07:10:47.304  1020  1044 W libprocessgroup: failed to open /acct/uid_10009/pid_3463/cgroup.procs: No such file or directory
,03-17 07:10:47.304  1020  1032 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,03-17 07:10:47.304  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.304  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.304  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.304  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.314  3245  3353 I DBG_DM  : [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220],
,03-17 07:10:47.324  4459  4459 E Zygote  : MountEmulatedStorage(),
03-17 07:10:47.324  4459  4459 E Zygote  : v2
03-17 07:10:47.324  4459  4459 I libpersona: KNOX_SDCARD checking this for 10145,
03-17 07:10:47.324  4459  4459 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:47.334  1020  1142 D SettingsProvider: name = audio_safe_volume_state,
03-17 07:10:47.334  1020  1032 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4459 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,03-17 07:10:47.334  4459  4459 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 07:10:47.334  4459  4459 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 07:10:47.334  4459  4459 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:47.334  3245  3353 I DBG_DM  : [IlIlllIlllllIlIllllI(177/lllIlIlIIIllIIlIllIl)] nDownloadPostpone is [8]
,03-17 07:10:47.344  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:47.344  3945  4014 I GFX raster: took 0.639479ms for 96*96 texture 0
03-17 07:10:47.344  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83cb3a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb83c8280 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:47.364  3945  4014 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 07:10:47.384  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:47.384  3945  4014 I GFX raster: took 0.637135ms for 96*96 texture 0
03-17 07:10:47.384  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83c68c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83c8280 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:47.384  4459  4459 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:47.384  4459  4459 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:47.404  4459  4459 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 07:10:47.404  4459  4459 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 07:10:47.404  3945  4014 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 07:10:47.404  4459  4459 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 07:10:47.404  4459  4459 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:47.404  4459  4459 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:47.414  3245  3353 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 0
,03-17 07:10:47.414  3245  3353 I DBG_DM  : [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,03-17 07:10:47.414  3245  3353 I DBG_DM  : [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,03-17 07:10:47.424  3245  3354 I DBG_DM  : [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,03-17 07:10:47.424  3245  3354 I DBG_DM  : [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,03-17 07:10:47.424  3245  3353 I DBG_DM  : [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,03-17 07:10:47.434  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:47.434  3245  3354 I DBG_DM  : [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:308289685
,03-17 07:10:47.434  3245  3353 I DBG_DM  : [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,03-17 07:10:47.434  3945  4014 I GFX raster: took 0.768281ms for 96*96 texture 0
03-17 07:10:47.434  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83c86e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83cc020 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:47.434  3245  3354 I DBG_DM  : [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,03-17 07:10:47.444  1020  1491 I ActivityManager: Killing 3706:com.wssnps/1000 (adj 15): empty #31
,03-17 07:10:47.444  3945  4014 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 07:10:47.454  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationList
,03-17 07:10:47.454  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:47.454  3945  4014 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:47.454  3945  4014 I AMMetaDataParserService: Resource data:2131099648
,03-17 07:10:47.454  1020  2934 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:47.454  1020  2934 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:47.454  1020  2934 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:47.454  1020  2934 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,03-17 07:10:47.464  3945  4014 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 07:10:47.464  3945  4014 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:47.464  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:47.464  1020  2875 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 07:10:47.464  3945  4014 I GFX raster: took 0.869115ms for 96*96 texture 0
03-17 07:10:47.464  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83dd818 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83c8280 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:47.484  3945  4014 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 07:10:47.494  3245  3354 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,03-17 07:10:47.524  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:47.524  3945  4014 I GFX raster: took 0.644323ms for 96*96 texture 0
03-17 07:10:47.524  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83c56a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb83cc020 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:47.524  3945  4014 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 07:10:47.524  1020  2933 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:47.544  1020  2931 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:47.574  3245  3354 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,03-17 07:10:47.574  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:47.574  3945  4014 I GFX raster: took 0.626719ms for 96*96 texture 0
03-17 07:10:47.574  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83d1ed0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb83c8280 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:47.584  3945  4014 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 07:10:47.594  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3706/cgroup.procs: No such file or directory
,03-17 07:10:47.594  1020  1491 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:47.604  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:47.604  3945  4014 I GFX raster: took 0.663438ms for 96*96 texture 0
03-17 07:10:47.604  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83cb3a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb83cc020 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:47.604  3245  3354 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,03-17 07:10:47.614  3245  3354 I DBG_DM  : [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 678432842
,03-17 07:10:47.614  3245  3245 I DBG_DM  : [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,03-17 07:10:47.614  3245  3245 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,03-17 07:10:47.614  3245  3245 I DBG_DM  : [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,03-17 07:10:47.634  3945  4014 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 07:10:47.654  1020  2883 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:47.674  3245  3245 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,03-17 07:10:47.674  3245  3354 I DBG_DM  : [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
03-17 07:10:47.674  3245  3245 I DBG_DM  : [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,03-17 07:10:47.674  3245  3354 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,03-17 07:10:47.674  3245  3245 E DBG_DM  : [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,03-17 07:10:47.684  1020  1130 I ActivityManager: Killing 3756:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,03-17 07:10:47.684  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:47.684  3945  4014 I GFX raster: took 0.634062ms for 96*96 texture 0
03-17 07:10:47.684  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83c68c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83c8280 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:47.684  3245  3245 E DBG_DM  : [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@14700c36
,03-17 07:10:47.684  3245  3354 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,03-17 07:10:47.684  3945  4014 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 07:10:47.704  3245  3354 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,03-17 07:10:47.714  1020  1130 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,03-17 07:10:47.714  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.714  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.714  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.714  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.724  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
03-17 07:10:47.724  3945  4014 I GFX raster: took 0.722812ms for 96*96 texture 0
03-17 07:10:47.724  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb83c86e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb83cc020 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:47.724  3945  4014 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 07:10:47.734  4482  4482 E Zygote  : MountEmulatedStorage()
,03-17 07:10:47.734  4482  4482 E Zygote  : v2
03-17 07:10:47.734  4482  4482 I libpersona: KNOX_SDCARD checking this for 10072
03-17 07:10:47.734  4482  4482 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:47.734  4482  4482 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
,03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
,03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
,03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
,03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
,03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
,03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
03-17 07:10:47.744  3945  4014 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
,03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
,03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
,03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
,03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm,
,03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
03-17 07:10:47.744  1020  1130 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4482 uid=10072 gids={50072, 9997} abi=armeabi-v7a
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
03-17 07:10:47.744  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
03-17 07:10:47.754   287   287 E SMD     : DCD OFF
,03-17 07:10:47.754  4482  4482 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:47.754  4482  4482 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 07:10:47.764  1020  1044 W libprocessgroup: failed to open /acct/uid_10100/pid_3756/cgroup.procs: No such file or directory
,03-17 07:10:47.764  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
,03-17 07:10:47.764  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:47.774  3945  4014 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:47.774  3945  4014 I AMMetaDataParserService: Resource data:2131165197
,03-17 07:10:47.774  4482  4482 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:47.774  4482  4482 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:47.774  1020  1307 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:47.774  3245  3354 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-17 07:10:47.774  3945  4014 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 07:10:47.774  3945  4014 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:47.774  3945  4014 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 07:10:47.774  3945  4014 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:47.774  3945  4014 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,03-17 07:10:47.774  3945  4014 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 07:10:47.774  3945  4014 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 07:10:47.774  3945  4014 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:47.794  1020  2880 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:47.794  1020  2933 D ActivityManager: startService callerProcessName:com.android.email, calleePkgName: com.android.email
,03-17 07:10:47.794  1020  2933 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-17 07:10:47.794  1020  2933 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:47.794  1020  2933 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:47.794  1020  2933 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,03-17 07:10:47.804  4482  4482 D BadgeProvider: onCreate
,03-17 07:10:47.804  4482  4482 D BadgeProvider: DatabaseHelper
,03-17 07:10:47.814  4482  4490 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-17 07:10:47.824  1020  1362 D ActivityManager: startProcessLocked calleePkgName: com.android.exchange, hostingType: broadcast
,03-17 07:10:47.834  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.834  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.834  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:47.834  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:47.844  4503  4503 E Zygote  : MountEmulatedStorage(),
03-17 07:10:47.844  4503  4503 I libpersona: KNOX_SDCARD checking this for 10146
03-17 07:10:47.844  4503  4503 E Zygote  : v2
03-17 07:10:47.844  4503  4503 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:47.844  4503  4503 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-17 07:10:47.844  4503  4503 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:47.844  1020  1362 I ActivityManager: Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4503 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
03-17 07:10:47.844  1020  1362 I ActivityManager: Killing 3436:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,03-17 07:10:47.844  4503  4503 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:47.844  1020  1362 I ActivityManager: Killing 3721:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #32
,03-17 07:10:47.874  4503  4503 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:47.874  4503  4503 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:47.884  4503  4503 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 07:10:47.964  4459  4479 W art     : Verification of void com.android.email.activity.MessageListItemOuterContainer.showColorChip(int, long, boolean) took 171.931ms
,03-17 07:10:47.964  1020  1044 W libprocessgroup: failed to open /acct/uid_10014/pid_3721/cgroup.procs: No such file or directory
03-17 07:10:47.964  1020  1044 W libprocessgroup: failed to open /acct/uid_10015/pid_3436/cgroup.procs: No such file or directory
,03-17 07:10:47.964  1020  1344 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
03-17 07:10:47.964  1020  1344 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-17 07:10:47.964  1020  1020 D WindowManager: showStatusBarByNotification() mOpenByNotification=false
,03-17 07:10:47.964  1020  1020 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-17 07:10:47.974  1187  1770 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:47.974  1020  2931 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,03-17 07:10:47.974  1020  2931 D SecContentProvider2: mCursor = null
,03-17 07:10:47.974  3245  3354 I DBG_DM  : [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
,03-17 07:10:47.974  1020  1491 D SecContentProvider2: uri = 15 selection = getToastGravity
,03-17 07:10:47.974  1020  1491 D SecContentProvider2: mCursor = null
,03-17 07:10:47.974  1020  1516 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
03-17 07:10:47.974  1020  1516 D SecContentProvider2: mCursor = null
,03-17 07:10:47.974  1020  1307 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
03-17 07:10:47.984  1020  1307 D SecContentProvider2: mCursor = null
,03-17 07:10:47.994  3245  3354 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-17 07:10:47.994  1020  1344 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,03-17 07:10:47.994  1020  1344 D SecContentProvider2: mCursor = null
,03-17 07:10:48.004  1020  2933 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,03-17 07:10:48.004  1020  2933 D SecContentProvider2: mCursor = null
,03-17 07:10:48.014  3245  4519 D OpenGLRenderer: Render dirty regions requested: true
,03-17 07:10:48.034   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=4, Uoast
,03-17 07:10:48.044  1492  1492 D Launcher.Model: reloadBadges entered.
03-17 07:10:48.044  4482  4490 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-17 07:10:48.044  4482  4490 D BadgeProvider: sendNotify, [notify] : null
03-17 07:10:48.044  4482  4490 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-17 07:10:48.044  4482  4490 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 07:10:48.044  4482  4490 D BadgeProvider: update, [UpdateCount] : 1
,03-17 07:10:48.064  1020  1362 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1020
,03-17 07:10:48.064  1020  1054 D DisplayPowerController: getFinalBrightness : Summary is 60 -> 60
03-17 07:10:48.064  1020  1054 D DisplayPowerController: animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 07:10:48.064  1020  1054 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-17 07:10:48.074  3245  3245 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 07:10:48.074  3245  4519 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 07:10:48.074  3245  4519 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 07:10:48.074  3245  4519 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 07:10:48.074  3245  4519 I Adreno-EGL: Local Branch: 
03-17 07:10:48.074  3245  4519 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 07:10:48.074  3245  4519 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 07:10:48.074  3245  4519 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 07:10:48.084  1020  1173 D lights  : lcd : 47 +
,03-17 07:10:48.084  1187  1187 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,03-17 07:10:48.094  1187  1187 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
,03-17 07:10:48.094  1020  1054 D DisplayPowerController: getFinalBrightness : Summary is 60 -> 60
03-17 07:10:48.094  1020  1054 D DisplayPowerController: animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 07:10:48.104  1020  1173 D lights  : lcd : 47 -
,03-17 07:10:48.104  1020  1173 D lights  : lcd : 60 +
,03-17 07:10:48.104  3945  4014 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
,03-17 07:10:48.104  3945  4014 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:48.114  1187  1187 D PersonaManager: PersonaID is invalid or persona doesn't exists. : 0
,03-17 07:10:48.114  1187  1187 D PersonaManager: isKioskContainerExistOnDevice
,03-17 07:10:48.114  1187  1187 D PersonaManager: isKioskContainerExistOnDevice
,03-17 07:10:48.114  1187  1187 I PhoneStatusBar: Icon Only
,03-17 07:10:48.114  1187  1187 I StatusBar: Icon Only
,03-17 07:10:48.114  1187  1187 D PanelView: There is/are notification(s) 
03-17 07:10:48.114  1187  1187 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 07:10:48.114  1020  1173 D lights  : lcd : 60 -
,03-17 07:10:48.114  1187  1187 D PersonaManager: isKioskContainerExistOnDevice
03-17 07:10:48.114  1187  1187 I PhoneStatusBar: Icon Only
03-17 07:10:48.114  1187  1187 I StatusBar: Icon Only
03-17 07:10:48.114  1187  1187 D PanelView: There is/are notification(s) 
03-17 07:10:48.114  1187  1187 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 07:10:48.114  1020  1054 D DisplayPowerController: getFinalBrightness : Summary is 60 -> 60
03-17 07:10:48.114  1020  1054 D DisplayPowerController: animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 07:10:48.144  3945  4014 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-17 07:10:48.154  3245  3354 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 8
,03-17 07:10:48.154  3245  3354 I DBG_DM  : [com.wssyncmldm.ui.XUIFotaPostponeActivity(386/llIIIIlllllIIllIIllI)] No idle Postpone
,03-17 07:10:48.154  3245  3354 I DBG_DM  : [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,03-17 07:10:48.164  3245  4519 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 07:10:48.164  4141  4141 I dex2oat : dex2oat took 5.207s (threads: 4)
,03-17 07:10:48.174  3945  4014 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 07:10:48.174  3245  4519 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-17 07:10:48.174  3245  4519 D OpenGLRenderer: Enabling debug mode 0
,03-17 07:10:48.184  2076  4138 D DexOptUtils: Odex created at:/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex
,03-17 07:10:48.184  2076  4138 D DexOptUtils: Set odex to world readable.
,03-17 07:10:48.184  2076  4138 D DexOptUtils: Renamed odex to /data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.odex
,03-17 07:10:48.184  1020  1491 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:48.184  1187  1187 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,03-17 07:10:48.184  1020  1130 I ActivityManager: Killing 3824:com.android.managedprovisioning/u0a22 (adj 15): empty #31
,03-17 07:10:48.194  1020  1307 D ActivityManager: startService callerProcessName:com.android.exchange, calleePkgName: com.android.exchange
,03-17 07:10:48.194  1020  1307 D ActivityManager: retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-17 07:10:48.194  1020  1307 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:48.194  1020  1307 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:48.194  1020  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,03-17 07:10:48.204  1020  2880 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
,03-17 07:10:48.204  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:48.204  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:48.204  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:48.204  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:48.224  1020  2880 I ActivityManager: Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4523 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 07:10:48.224  4523  4523 E Zygote  : MountEmulatedStorage()
03-17 07:10:48.224  4523  4523 E Zygote  : v2
03-17 07:10:48.224  4523  4523 I libpersona: KNOX_SDCARD checking this for 1000
,03-17 07:10:48.224  4523  4523 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:48.224  4523  4523 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:48.234  1020  2931 I ActivityManager: Killing 3847:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,03-17 07:10:48.234  4523  4523 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:48.234  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:48.234  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:48.234  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:48.244  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:48.244  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:48.244  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:48.244  4523  4523 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 07:10:48.244  3945  4014 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-17 07:10:48.274  4523  4523 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:48.274  4523  4523 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:48.294  3945  4014 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-17 07:10:48.304  1020  1491 W ActivityManager: getTasks: caller 10146 does not hold GET_TASKS; limiting output
,03-17 07:10:48.304  4503  4528 I Process : Sending signal. PID: 4503 SIG: 9
,03-17 07:10:48.304  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
03-17 07:10:48.304  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.304  3945  4014 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:48.304  3945  4014 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:48.304  3945  4014 I AMMetaDataParserService: Resource data:2131165197
,03-17 07:10:48.314  3945  4014 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-17 07:10:48.314  3945  4014 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:48.324  3945  4014 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-17 07:10:48.334  3945  4014 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 07:10:48.364  1020  1130 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,03-17 07:10:48.364  1020  1130 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-17 07:10:48.364  3945  4014 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
03-17 07:10:48.364  1020  1032 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,03-17 07:10:48.364  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:48.364  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:48.364  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:48.364  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:48.374  1020  1044 W libprocessgroup: failed to open /acct/uid_10022/pid_3824/cgroup.procs: No such file or directory
,03-17 07:10:48.374  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3847/cgroup.procs: No such file or directory
,03-17 07:10:48.384  4540  4540 E Zygote  : MountEmulatedStorage(),
03-17 07:10:48.384  4540  4540 E Zygote  : v2
03-17 07:10:48.384  4540  4540 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:48.384  4540  4540 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:48.384  4540  4540 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:48.384  4540  4540 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:48.384  4540  4540 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 07:10:48.384  1020  1032 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4540 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:48.394  1020  1032 I ActivityManager: Killing 3865:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
03-17 07:10:48.394  1020  2933 I ActivityManager: Process com.android.exchange (pid 4503)(adj 9) has died(48,1098)
,03-17 07:10:48.394  1020  1362 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-17 07:10:48.404  3904  4020 I System.out: INFO:Resource not found:/Common.properties Using default values
,03-17 07:10:48.414  4540  4540 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:48.414  4540  4540 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:48.424  1020  2883 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
03-17 07:10:48.424  1020  2883 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-17 07:10:48.424  1020  1516 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-17 07:10:48.424  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-17 07:10:48.434  3945  4014 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-17 07:10:48.434  1020  2933 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-17 07:10:48.444  1020  1307 W ActivityManager: getTasks: caller 10145 does not hold GET_TASKS; limiting output
,03-17 07:10:48.444  4459  4501 I Process : Sending signal. PID: 4459 SIG: 9
,03-17 07:10:48.454  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.cooliris.media.Gallery
03-17 07:10:48.454  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
03-17 07:10:48.454  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.454  3945  4014 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:48.454  3945  4014 I AMMetaDataParserService: Resource data:2131165197
,03-17 07:10:48.454  4540  4540 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,03-17 07:10:48.454  3945  4014 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-17 07:10:48.454  3945  4014 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:48.464  3945  4014 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-17 07:10:48.474  4540  4540 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-17 07:10:48.474  4540  4540 D SecurityLogAgent: StateMachine : Current State = 1
,03-17 07:10:48.474  4540  4540 D SecurityLogAgent: BootReceiver : completed task. Failed to return wakelock . 
,03-17 07:10:48.474  1020  2931 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-17 07:10:48.474   254   254 E lowmemorykiller: Error writing /proc/4459/oom_score_adj; errno=22
,03-17 07:10:48.484  3945  4014 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 07:10:48.484  1020  2933 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
03-17 07:10:48.484  1020  2933 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 07:10:48.484  1020  2933 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:48.484  1020  2933 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:48.484  1020  2933 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 07:10:48.484  2576  2576 I Hs20UtilService: Starting #3
,03-17 07:10:48.484   254   254 E lowmemorykiller: Error writing /proc/4459/oom_score_adj; errno=22
,03-17 07:10:48.494  2576  2599 I Hs20UtilService: Message received 5011
,03-17 07:10:48.494  4540  4540 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-17 07:10:48.494  4540  4540 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,03-17 07:10:48.494  4540  4540 D SecurityLogAgent: StateMachine : Current State = 1
,03-17 07:10:48.494  1020  1135 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
03-17 07:10:48.494  1020  1135 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-17 07:10:48.494  1020  1135 E WifiNative-wlan0: invaild command id : 215
,03-17 07:10:48.494  4540  4540 D SecurityLogAgent: StateMachine : Changed Current State = 1
,03-17 07:10:48.504  1020  2880 D ActivityManager: startProcessLocked calleePkgName: com.example.hello, hostingType: broadcast
,03-17 07:10:48.504  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:48.504  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:48.504  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:48.504  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:48.514  3945  4014 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-17 07:10:48.514  4557  4557 E Zygote  : MountEmulatedStorage()
03-17 07:10:48.514  4557  4557 E Zygote  : v2
03-17 07:10:48.514  4557  4557 I libpersona: KNOX_SDCARD checking this for 10174
03-17 07:10:48.514  4557  4557 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:48.524  4557  4557 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:48.524  4557  4557 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:48.524  4557  4557 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 07:10:48.524  1020  2880 I ActivityManager: Start proc com.example.hello for broadcast com.example.hello/io.jxcore.node.ConnectivityChangeListener: pid=4557 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
03-17 07:10:48.524   254   254 E lowmemorykiller: Error writing /proc/4459/oom_score_adj; errno=22
,03-17 07:10:48.554  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3865/cgroup.procs: No such file or directory
,03-17 07:10:48.554  1020  1516 I ActivityManager: Process com.android.email (pid 4459)(adj 11) has died(55,1098)
,03-17 07:10:48.564  4557  4557 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:48.564  4557  4557 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:48.574  3945  4014 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
03-17 07:10:48.584  3945  4014 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running acti,vitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
03-17 07:10:48.584  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,03-17 07:10:48.594  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camera
03-17 07:10:48.594  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.594  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
03-17 07:10:48.594  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-17 07:10:48.594  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.keyguard.layout
03-17 07:10:48.594  3945  4014 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:48.594  3945  4014 I AMMetaDataParserService: Resource data:2131099648
,03-17 07:10:48.604  3945  4014 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 07:10:48.604  3945  4014 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 07:10:48.604  3945  4014 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 07:10:48.604  3945  4014 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 07:10:48.604  3945  4014 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:48.604  3945  4014 I AMMetaDataParserService: getResourceName:com.sec.android.app.camera:xml/assistant
03-17 07:10:48.604  3945  4014 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:48.604  4557  4557 D jxcore_app_log: JniHelper::setJavaVM(0xb8009450), pthread_self() = -1225421112
,03-17 07:10:48.604  4557  4557 E JX-Cordova: JXcore wasn't initialized yet
,03-17 07:10:48.614  1311  1311 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,03-17 07:10:48.624  1311  1311 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-17 07:10:48.624  1311  1311 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-17 07:10:48.624  3945  4014 I AMMetaDataParserService: Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,03-17 07:10:48.624  1311  1311 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,03-17 07:10:48.624  1311  1311 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
03-17 07:10:48.624  1311  1311 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 07:10:48.624  1020  2931 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,03-17 07:10:48.624  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:48.624  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:48.624  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:48.624  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:48.634  3945  4014 I AMMetaDataParserService: Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511,
,03-17 07:10:48.644  4572  4572 I libpersona: KNOX_SDCARD checking this for 10068
03-17 07:10:48.644  4572  4572 E Zygote  : MountEmulatedStorage()
03-17 07:10:48.644  4572  4572 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:48.644  4572  4572 E Zygote  : v2
,03-17 07:10:48.644  4572  4572 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 07:10:48.644  4572  4572 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:48.644  4572  4572 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:48.654  1020  2931 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=4572 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-17 07:10:48.674  4572  4572 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:48.674  4572  4572 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:48.684  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
03-17 07:10:48.684  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
03-17 07:10:48.684  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
03-17 07:10:48.684  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
03-17 07:10:48.684  3945  4014 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,03-17 07:10:48.694  4572  4572 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-17 07:10:48.714  4572  4572 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,03-17 07:10:48.714  4572  4572 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,03-17 07:10:48.754  4572  4572 D FileShare-Client: Outbound.stopDelayTimer - 
,03-17 07:10:48.754  3888  3888 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,03-17 07:10:48.764  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:48.764  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:48.764  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:48.764  1020  1130 I ActivityManager: Killing 3578:com.sec.pcw.device/1000 (adj 15): empty #31
,03-17 07:10:48.774  1020  2883 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,03-17 07:10:48.774  1020  2883 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
03-17 07:10:48.774  1020  2883 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
03-17 07:10:48.774  1020  2883 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-17 07:10:48.774  1020  2883 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:48.774  1020  2883 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:48.774  1020  2883 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:48.784  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:48.784  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:48.784  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:48.794  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:48.794  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:48.794  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:48.804  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:48.804  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:48.804  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:48.804  1020  1362 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:48.804  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GridSettings
03-17 07:10:48.804  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.804  3945  4014 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 07:10:48.804  3945  4014 I AMMetaDataParserService: Resource data:2131165220
,03-17 07:10:48.814  1020  1362 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:48.814  1020  1362 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:48.814  1020  1362 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:48.814  3945  4014 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 07:10:48.814  3945  4014 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 07:10:48.814  3945  4014 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 07:10:48.814  3945  4014 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:48.814  3945  4014 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:48.814  3945  4014 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 07:10:48.814  3945  4014 I AMMetaDataParserService: getResourceName:com.android.settings:xml/assistant
03-17 07:10:48.814  3945  4014 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 07:10:48.814  1020  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 07:10:48.814  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:48.814  3945  4014 I GFX raster: took 0.699062ms for 96*96 texture 0
03-17 07:10:48.814  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8af58c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8af55f0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:48.824  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:48.824  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:48.824  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:48.824  3945  4014 I AMMetaDataParserService: Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,03-17 07:10:48.824  1879  1879 D WearableService: callingUid 10012, callindPid: 1879
,03-17 07:10:48.834  1020  2933 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:48.834  1020  2933 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:48.834  1020  2933 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:48.834  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:48.844  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:48.844  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:48.844  1020  1344 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 07:10:48.844  1020  1344 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-17 07:10:48.844  3945  4014 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 07:10:48.844  3945  4014 I GFX raster: took 0.601510ms for 96*96 texture 0
03-17 07:10:48.844  3945  4014 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8af5710 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b08130 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 07:10:48.844  1020  1344 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:48.844  1020  1344 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:48.854  1020  1344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:48.854  1879  4587 E MDM     : [244] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-17 07:10:48.854  1020  1307 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:48.854  1020  1307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:48.854  1020  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:48.854  1879  1879 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 07:10:48.854  2076  4588 D LocationInitializer: Restart initialization of location
,03-17 07:10:48.864  1020  2933 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 07:10:48.864  1020  2933 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,03-17 07:10:48.864  1020  2933 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:48.864  1020  2933 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:48.864  1020  2933 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:48.864  3945  4014 I AMMetaDataParserService: Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,03-17 07:10:48.864  1020  2934 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:48.864  1020  2934 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:48.864  1020  2934 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SubSettings
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LabelName
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Password
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.,settings.wifi.WifiSecSetupActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest,
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
03-17 07:10:48.884  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3578/cgroup.procs: No such file or directory
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
03-17 07:10:48.884  1020  2931 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.884  1020  2931 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TetherSettings
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.904  1020  1362 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity,
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LanguageSettings
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.HomeSettings
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DisplaySettings
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activity,com.android.settings.Settings$DockSettingsActivity
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.874  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DockSettings
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity,
,03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ManageApplications
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RunningServices
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LaunchApplication
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.StorageUse
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
,03-17 07:10:48.884  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecuritySettings
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CredentialStorage
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetProfileOwner
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.IccLockSettings
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
03-17 07:10:48.894  1020  2931 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:48.894  1020  2931 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:48.894  1020  2931 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ApnEditor
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormat
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormatSd
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.934  1020  2880 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.934  1020  2880 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppPicker
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsbSettings
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActivityPicker
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BatteryInfo
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Display
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RadioInfo
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ProxySelector
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BandMode
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TestingSettings
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
03-17 07:10:48.894  3945  4014, I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity,
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SoundSettings
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AM,MetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
,03-17 07:10:48.964  3945  4014 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GSensorSettings
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreview
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreview
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NewModePreview
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor2014
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewStyleClock
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.WarrantyLegal
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
03-17 07:10:48.974  1020  2934 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.974  1020  2934 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenHelpActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PhoneVibration
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandHelp
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
03-17 07:10:48.894  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.904  1020  1362 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:48.904  1020  1362 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:48.904  1020  1362 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 07:10:48.914  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.914  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.914  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
03-17 07:10:48.914  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.914  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.914  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.914  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
03-17 07:10:48.914  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
03-17 07:10:48.914  1879  1879 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-17 07:10:48.914  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:48.914  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:48.914  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 07:10:48.924  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
03-17 07:10:48.924  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
03-17 07:10:48.924  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
03-17 07:10:48.924  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
03-17 07:10:48.924  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
03-17 07:10:48.924  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
03-17 07:10:48.924  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
03-17 07:10:48.924  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
03-17 07:10:48.924  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
03-17 07:10:48.924  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
03-17 07:10:48.924  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.924  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.924  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.924  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
03-17 07:10:48.924  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.924  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.924  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.924  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
03-17 07:10:48.924  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.924  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.924  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.924  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
03-17 07:10:48.924  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.934  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:48.934  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:48.934  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.934  1020  2880 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:48.934  1020  2880 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:48.934  1020  2880 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MagazineCard
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.934  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:49.004  1020  2933 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:49.004  1020  2933 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SearchActivity
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:49.004  1020  2883 I ActivityManager: Killing 3740:com.samsung.android.sm/1000 (adj 15): empty #31
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.944  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.954  1879  2091 W GCoreFlp: No location to return for getLastLocation()
03-17 07:10:48.954  1879  4589 W FusedLocationProvider: location=null
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.AppList
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.954  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.964  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
03-17 07:10:48.964  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.964  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.964  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.964  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
03-17 07:10:48.964  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
03-17 07:10:48.964  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
03-17 07:10:48.964  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
03-17 07:10:48.964  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.964  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.964  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.964  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
03-17 07:10:48.964  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.964  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.964  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.964  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
03-17 07:10:48.964  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
03-17 07:10:48.964  3945  4014 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 07:10:48.964  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 07:10:48.964  3945  4014 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 07:10:48.964  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
03-17 07:10:48.964  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
03-17 07:10:48.964  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
03-17 07:10:48.964  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
03-17 07:10:48.964  3945  4014 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
03-17 07:10:48.974  1020  2934 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:48.974  1020  2934 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:48.974  1020  2934 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
03-17 07:10:48.984  1311  1311 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
03-17 07:10:48.984  1311  1311 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
03-17 07:10:48.984  1311  1311 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
03-17 07:10:48.984  1311  1311 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
03-17 07:10:48.984  1311  1311 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
03-17 07:10:48.984  1311  1311 I NearbySettings: MountReceiver.onReceive - Keep current state
03-17 07:10:48.984  2576  2576 I Hs20UtilService: Starting #4
03-17 07:10:48.984  2576  2599 I Hs20UtilService: Message received 5007
03-17 07:10:49.004  1020  2933 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:49.004  1020  2933 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:49.004  1020  2933 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
03-17 07:10:49.014  1311  1311 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
03-17 07:10:49.014  1311  1311 I NearbySettings: MountReceiver.onReceive - Keep current state
03-17 07:10:49.034  2576  2576 I Hs20UtilService: Starting #5
03-17 07:10:49.034  2576  2599 I Hs20UtilService: Message received 5007
03-17 07:10:49.034  1020  1130 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
03-17 07:10:49.034  1020  1130 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
03-17 07:10:49.034  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:49.034  1020  1130 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:49.034  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
03-17 07:10:49.034  2576  2576 I Hs20UtilService: Starting #6
03-17 07:10:49.034  1311  1311 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
03-17 07:10:49.034  1311  1311 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
03-17 07:10:49.044  2576  2599 I Hs20UtilService: Message received 5007
03-17 07:10:49.044  1311  1311 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
03-17 07:10:49.044  1311  1311 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
03-17 07:10:49.044  1311  1311 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
03-17 07:10:49.044  1311  1311 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 07:10:49.064  1020  2933 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
03-17 07:10:49.064  1020  2933 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 07:10:49.064  1020  2933 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:49.064  1020  2933 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:49.064  1020  2933 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 07:10:49.064  2576  2576 I Hs20UtilService: Starting #7
,03-17 07:10:49.064  2576  2599 I Hs20UtilService: Message received 5007
,03-17 07:10:49.064  1311  1311 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 07:10:49.064  1311  1311 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 07:10:49.074  1020  2931 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,03-17 07:10:49.084  1020  1362 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,03-17 07:10:49.084  1020  1362 D SecContentProvider2: mCursor = null
,03-17 07:10:49.084  1020  2880 D SecContentProvider2: uri = 15 selection = getToastGravity
,03-17 07:10:49.084  1020  2880 D SecContentProvider2: mCursor = null
,03-17 07:10:49.084  1020  1516 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,03-17 07:10:49.084  1020  1516 D SecContentProvider2: mCursor = null
,03-17 07:10:49.094  1020  1307 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,03-17 07:10:49.094  1020  1307 D SecContentProvider2: mCursor = null
,03-17 07:10:49.094  1020  2933 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,03-17 07:10:49.094  1020  2933 D SecContentProvider2: mCursor = null
,03-17 07:10:49.104  1020  1491 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,03-17 07:10:49.104  1020  1491 D SecContentProvider2: mCursor = null
,03-17 07:10:49.104  1020  2934 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,03-17 07:10:49.114  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:49.114  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.114  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.114  1020  2934 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:49.134  4593  4593 E Zygote  : MountEmulatedStorage(),
03-17 07:10:49.134  1020  2934 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=4593 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:49.134  4593  4593 E Zygote  : v2
,03-17 07:10:49.134  4593  4593 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:49.134  4593  4593 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-17 07:10:49.134  4593  4593 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:49.144  4593  4593 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:49.144  4593  4593 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:49.154  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3740/cgroup.procs: No such file or directory
,03-17 07:10:49.154  4593  4593 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:49.154  4593  4593 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:49.184  4593  4593 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,03-17 07:10:49.184  4593  4593 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
03-17 07:10:49.184  4593  4593 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-17 07:10:49.194  4593  4593 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-17 07:10:49.194  4593  4593 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 07:10:49.194  4593  4593 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 07:10:49.194  4593  4593 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,03-17 07:10:49.194  1020  2933 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=10, mSplitNum[1]=17, mSplitNum[2]=26, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=34
,03-17 07:10:49.194  1020  2933 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,03-17 07:10:49.194  1020  2933 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,03-17 07:10:49.204  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:49.204  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.204  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:49.204  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:49.214  4609  4609 E Zygote  : MountEmulatedStorage(),
03-17 07:10:49.214  4609  4609 E Zygote  : v2
03-17 07:10:49.214  4609  4609 I libpersona: KNOX_SDCARD checking this for 10111,
03-17 07:10:49.214  4609  4609 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 07:10:49.214  4609  4609 I libpersona: KNOX_SDCARD not a persona,
03-17 07:10:49.214  1020  2933 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4609 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:49.224  4609  4609 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:49.224  1020  1045 I ActivityManager: Killing 3779:com.google.android.gm/u0a101 (adj 15): empty #31
,03-17 07:10:49.224  4609  4609 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:49.224  1738  1738 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-17 07:10:49.234  3798  3798 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 07:10:49 GMT+01:00 2016
03-17 07:10:49.234  4540  4540 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-17 07:10:49.234  1020  1362 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
03-17 07:10:49.234  4540  4540 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-17 07:10:49.234  1020  1362 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
03-17 07:10:49.234  4540  4540 D SecurityLogAgent: StateMachine : Current State = 1
,03-17 07:10:49.234  1020  1362 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:49.234  1020  1362 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:49.234  4540  4540 D SecurityLogAgent: StateMachine : Changed Current State = 1
03-17 07:10:49.234  1020  1362 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 07:10:49.234  1020  1130 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,03-17 07:10:49.234  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.234  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.234  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.234  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:49.244  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-17 07:10:49.244  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:49.244  3798  3798 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-17 07:10:49.244  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:49.244  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:49.244  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:49.244  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:49.254  3798  3798 I KLMS-2.5.183: : KLMSIntentService(): onCreate(),
,03-17 07:10:49.254  4624  4624 E Zygote  : MountEmulatedStorage(),
03-17 07:10:49.254  4624  4624 I libpersona: KNOX_SDCARD checking this for 10159
03-17 07:10:49.254  4624  4624 E Zygote  : v2
03-17 07:10:49.254  4624  4624 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:49.254  3798  3798 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-17 07:10:49.254  4624  4624 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 07:10:49.254  3798  3798 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-17 07:10:49.254  4624  4624 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:49.254  4624  4624 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
03-17 07:10:49.254  3798  4621 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) },
,03-17 07:10:49.264  1020  1130 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=4624 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:49.264  4609  4609 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:49.264  4609  4609 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:49.274  3798  4621 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,03-17 07:10:49.284  1329  1343 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
,03-17 07:10:49.284  3798  4621 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,03-17 07:10:49.284  3798  4621 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().START
,03-17 07:10:49.284  4624  4624 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:49.294  4624  4624 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:49.294  3798  4621 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().START 
,03-17 07:10:49.294  1738  1738 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,03-17 07:10:49.294  1738  1738 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,03-17 07:10:49.294  1738  1738 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,03-17 07:10:49.294  1738  1738 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,03-17 07:10:49.304  1738  1738 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-17 07:10:49.304  1738  1738 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-17 07:10:49.314  3798  4621 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().END 
,03-17 07:10:49.314  1020  1362 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,03-17 07:10:49.314  3798  4621 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,03-17 07:10:49.314  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:49.314  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.314  3394  4640 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
03-17 07:10:49.314  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.314  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.314  3394  4640 I DBG_POLICYDM: [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 0, current network is 2
,03-17 07:10:49.324  4200  4200 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,03-17 07:10:49.324  3394  4640 E DBG_POLICYDM: [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... 
,03-17 07:10:49.344  4641  4641 E Zygote  : MountEmulatedStorage()
03-17 07:10:49.344  4641  4641 I libpersona: KNOX_SDCARD checking this for 10081
03-17 07:10:49.344  4641  4641 E Zygote  : v2
03-17 07:10:49.344  4641  4641 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:49.344  4641  4641 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:49.344  1020  1362 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=4641 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:49.344  4641  4641 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:49.354  4641  4641 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,03-17 07:10:49.354  4264  4264 I SA      : [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,03-17 07:10:49.354  4264  4264 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
03-17 07:10:49.354  4264  4264 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,03-17 07:10:49.364  1020  1045 I ActivityManager: Waited long enough for: ServiceRecord{14fe77ac u0 com.android.settings/.wifi.WifiCredService}
03-17 07:10:49.364  1020  1045 I ActivityManager: Waited long enough for: ServiceRecord{33d78c75 u0 com.samsung.android.providers.context/.ContextService}
,03-17 07:10:49.364  3798  3798 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-17 07:10:49.374   309   309 I art     : Explicit concurrent mark sweep GC freed 8715(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 26.800ms
,03-17 07:10:49.374  4264  4264 I SA      : [SLFUCHKMGR] constructor called
,03-17 07:10:49.384  3394  4640 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-17 07:10:49.394   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 19.951ms
,03-17 07:10:49.394  3394  4640 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-17 07:10:49.394  3394  4640 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-17 07:10:49.394  3394  4640 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-17 07:10:49.394  3394  4640 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-17 07:10:49.404  3394  4640 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-17 07:10:49.404  4641  4641 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:49.404  4641  4641 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:49.404  3394  4640 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-17 07:10:49.404  3394  4640 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,03-17 07:10:49.414   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 648us total 19.130ms
,03-17 07:10:49.424  4264  4264 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
03-17 07:10:49.424  4264  4264 I SA      : [OR] == isSIMCardReady false ==
03-17 07:10:49.424  3394  4640 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,03-17 07:10:49.444  1020  1044 W libprocessgroup: failed to open /acct/uid_10101/pid_3779/cgroup.procs: No such file or directory
,03-17 07:10:49.444  4264  4264 I SA      : [SCU] == networkStateCheck == true
,03-17 07:10:49.444  4264  4264 I SA      : [DM] getCountryCodeFromCSC : PL
03-17 07:10:49.444  4264  4264 I SA      : isChinaCountryCode : false
03-17 07:10:49.444  4264  4264 I SA      : [SCU] is ChinestModel Data Restricted   : false
03-17 07:10:49.444  4264  4264 I SA      : [OR] == networkStateCheck true ==
,03-17 07:10:49.464  2076  4659 I iu.SyncManager: SYNC; picasa accounts
,03-17 07:10:49.554  3394  4640 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 07:10:49.634  4264  4264 I SA      : [OR] GetMyCountryZoneTask
03-17 07:10:49.634  4264  4264 I SA      : [OR] onReceive END
,03-17 07:10:49.634  2076  2076 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-17 07:10:49.634  2076  2076 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-17 07:10:49.644  1238  1238 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,03-17 07:10:49.644  2076  4659 I iu.UploadsManager: num queued entries: 0
,03-17 07:10:49.644  2076  4659 I iu.UploadsManager: num updated entries: 0
,03-17 07:10:49.644  2076  4659 I iu.SyncManager: NEXT; no task
,03-17 07:10:49.654  1020  1130 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,03-17 07:10:49.654  1020  1130 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,03-17 07:10:49.654  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:49.654  1020  1130 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:49.654  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 07:10:49.664  4264  4661 I SA      : [SRS] prepareGetMyCountryZone
,03-17 07:10:49.664  1020  2933 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 07:10:49.674  1020  2933 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
03-17 07:10:49.674  1020  1032 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
03-17 07:10:49.674  1020  1032 D SecContentProvider2: mCursor = null
,03-17 07:10:49.674  1020  2933 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:49.674  1020  2933 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:49.674  1020  2933 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:49.674  1020  1362 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,03-17 07:10:49.674  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.674  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.674  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.674  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:49.674  4264  4661 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-17 07:10:49.674  4264  4661 I SA      : [SSP] query invoked
,03-17 07:10:49.704  4667  4667 E Zygote  : MountEmulatedStorage()
03-17 07:10:49.704  1020  1362 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4667 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-17 07:10:49.704  4667  4667 E Zygote  : v2
03-17 07:10:49.704  4667  4667 I libpersona: KNOX_SDCARD checking this for 10010
03-17 07:10:49.704  4667  4667 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:49.714  4667  4667 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:49.714  4667  4667 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 07:10:49.714  4667  4667 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-17 07:10:49.754  4667  4667 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:49.754  4667  4667 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:49.834  3196  3577 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-17 07:10:49.844  1020  1032 I art     : Explicit concurrent mark sweep GC freed 32123(1979KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 26MB/40MB, paused 2.591ms total 156.547ms
,03-17 07:10:49.844  3196  3577 I jxcore-log: WARN testUtils BLE multiple advertisement issue: null
03-17 07:10:49.844  3196  3577 I jxcore-log: 
,03-17 07:10:49.844  4264  4661 I SA      : [TPMU] GetMccFromDB : null
03-17 07:10:49.844  4264  4661 I SA      : [SCU] getMccFromPreferece mcc = 260
03-17 07:10:49.844  4264  4661 I SA      : [TPM] isNoProxy(default) : true
,03-17 07:10:49.844  1020  1516 I ActivityManager: Killing 3945:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,03-17 07:10:49.854  1020  2880 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,03-17 07:10:49.864  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.864  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.864  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:49.864  1020  2880 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:49.874  4264  4661 E File    : fail readDirectory() errno=2
,03-17 07:10:49.884  4684  4684 E Zygote  : MountEmulatedStorage()
03-17 07:10:49.884  4684  4684 E Zygote  : v2
03-17 07:10:49.884  4684  4684 I libpersona: KNOX_SDCARD checking this for 10113
03-17 07:10:49.884  4684  4684 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:49.884  4684  4684 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:49.884  4684  4684 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 07:10:49.884  1020  2880 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4684 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 07:10:49.884  1020  2880 I ActivityManager: Killing 3357:com.google.android.youtube/u0a166 (adj 15): empty #31
,03-17 07:10:49.884  4684  4684 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:49.904  4684  4684 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:49.904  4684  4684 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:49.914  4609  4609 I MusicStore: Database version: 108
,03-17 07:10:49.974  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3945/cgroup.procs: No such file or directory
03-17 07:10:49.974  1020  1044 W libprocessgroup: failed to open /acct/uid_10166/pid_3357/cgroup.procs: No such file or directory
,03-17 07:10:49.984  3196  3577 I jxcore-log: INFO testUtils Toggling radios to: true
03-17 07:10:49.984  3196  3577 I jxcore-log: 
,03-17 07:10:49.984  3196  3577 D BluetoothAdapter: enable()
,03-17 07:10:49.984  3196  3577 D BluetoothAdapter: enable(): BT is already enabled..!
,03-17 07:10:49.994  3196  3577 I jxcore-log: Unit Test app is loaded
03-17 07:10:49.994  3196  3577 I jxcore-log: 
,03-17 07:10:49.994  1020  1307 D SecContentProvider: uri = 18 selection = isWifiEnabled
,03-17 07:10:49.994  1020  1307 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
03-17 07:10:49.994  1020  1307 D SecContentProvider2: mCursor = null
,03-17 07:10:49.994  1020  1307 W WifiService: Failed getting userId using ActivityManagerNative
03-17 07:10:49.994  1020  1307 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=3196, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
03-17 07:10:49.994  1020  1307 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24778)
03-17 07:10:49.994  1020  1307 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
03-17 07:10:49.994  1020  1307 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
03-17 07:10:49.994  1020  1307 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
03-17 07:10:49.994  1020  1307 W WifiService: 	at android.os.Binder.execTransact(Binder.java:461)
03-17 07:10:49.994  1020  1307 D WifiService: setWifiEnabled: true pid=3196, uid=10155
03-17 07:10:49.994  1020  1307 D SettingsProvider: name = wifi_on
03-17 07:10:49.994  1020  1307 W ActivityManager: Permission Denial: getCurrentUser() from pid=3196, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,03-17 07:10:50.004  1020  1033 I WifiService: disconnect: pid=3196, uid=10155
,03-17 07:10:50.004  1945  1945 I wpa_supplicant: [wpa_supplicant_ctrl_iface_process] : DISCONNECT
03-17 07:10:50.004  3196  3196 I chromium: [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,03-17 07:10:50.044  1020  2880 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
03-17 07:10:50.044  1020  2880 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-17 07:10:50.044  1020  2880 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:50.044  1020  2880 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:50.044  1020  2880 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 07:10:50.044  1945  1945 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,03-17 07:10:50.044  1945  1945 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
03-17 07:10:50.044  1945  1945 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,03-17 07:10:50.044  1945  1945 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
03-17 07:10:50.044  1945  1945 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,03-17 07:10:50.044  1945  1945 E wpa_supplicant: Cmd 35605 not handled
03-17 07:10:50.054  1020  1135 E WifiStateMachine: WifiStateMachine: Leaving Connected state
03-17 07:10:50.054  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
03-17 07:10:50.054  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
03-17 07:10:50.054  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
03-17 07:10:50.054  1020  1138 D Tethering: InitialState.processMessage what=4
03-17 07:10:50.054  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
03-17 07:10:50.054  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
03-17 07:10:50.054  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,03-17 07:10:50.054  1945  1945 I wpa_supplicant: reset timer : RESET_TIMER 0
03-17 07:10:50.054  1945  1945 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
03-17 07:10:50.054  1945  1945 I wpa_supplicant: P2P: Current p2p state = IDLE
03-17 07:10:50.054  1945  1945 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
03-17 07:10:50.054  1945  1945 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
03-17 07:10:50.054  1945  1945 I wpa_supplicant: First Scan Start
,03-17 07:10:50.054  1945  1945 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,03-17 07:10:50.054  1020  1138 E Tethering: No numeric data
03-17 07:10:50.054  1020  1138 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
03-17 07:10:50.054  1020  1138 D Tethering: clearTetheredNotification()
,03-17 07:10:50.064  1020  1135 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-17 07:10:50.064  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
03-17 07:10:50.064  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
03-17 07:10:50.064  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,03-17 07:10:50.064  1020  1132 V NetworkStats: performPollLocked(flags=0x1)
03-17 07:10:50.064  1020  1132 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 07:10:50.064  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,03-17 07:10:50.064  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
03-17 07:10:50.064  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
03-17 07:10:50.064  1187  1187 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
03-17 07:10:50.064  1187  1187 D HotspotTile: updateTetherState():false, false
,03-17 07:10:50.064  1020  1132 D NetworkStatsFactory: UpdateStatsForKnox updated
03-17 07:10:50.064  1020  1132 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-17 07:10:50.074  1020  1132 V NetworkStats: performPollLocked() took 6ms
03-17 07:10:50.074  1020  1132 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 07:10:50.074  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 07:10:50.074  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 07:10:50.174  4667  4667 D WaitQueueForNetworkActivate: notifyNetworkActivated
,03-17 07:10:50.224  4609  4609 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-17 07:10:50.234  4609  4609 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 07:10:50.244  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:50.244  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:50.244  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:50.244  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:50.244  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:50.244  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:50.264  4609  4609 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 07:10:50.274  4667  4667 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,03-17 07:10:50.274  1020  1033 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:50.274  1020  1033 W ActivityManager: Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,03-17 07:10:50.294  1020  1134 D WifiP2pService: InactiveState{ what=143375 }
,03-17 07:10:50.294  1020  1134 D WifiP2pService: P2pEnabledState{ what=143375 }
,03-17 07:10:50.294   277  1019 D CommandListener: Clearing all IP addresses on wlan0,
,03-17 07:10:50.304  1879  4340 V NativeCrypto: Read error: ssl=0xb8566b58: I/O error during system call, Connection timed out
03-17 07:10:50.304  1879  4340 V NativeCrypto: SSL shutdown failed: ssl=0xb8566b58: I/O error during system call, Broken pipe,
03-17 07:10:50.304  1020  1135 E WifiStateMachine: Start Disconnecting Watchdog 1
03-17 07:10:50.304  1020  1137 E ConnectivityService: updateNetworkInfo()
03-17 07:10:50.304  1020  1137 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
03-17 07:10:50.304  1020  1137 E ConnectivityService: updateNetworkInfo(),
03-17 07:10:50.304  1020  1137 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,03-17 07:10:50.304  1879  4340 E GCM     : Wifi connection closed with errorCode 20
,03-17 07:10:50.304  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:50.304  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:50.304  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:50.304  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:50.304  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:50.304  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:50.304  1945  1945 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,03-17 07:10:50.314  1020  1135 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14952 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,03-17 07:10:50.314  1020  1130 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,03-17 07:10:50.314  1020  2122 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
03-17 07:10:50.314  1020  2122 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
03-17 07:10:50.314  1020  2122 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
03-17 07:10:50.314  1020  2122 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
03-17 07:10:50.314  1020  2122 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,03-17 07:10:50.314  1020  2122 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-17 07:10:50.314  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
,03-17 07:10:50.314  1020  2122 I qtaguid : Tagging socket 339 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1020, getuid(): 1000
,03-17 07:10:50.314  1020  2122 I qtaguid : Untagging socket 339
,03-17 07:10:50.314  1020  2122 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
,03-17 07:10:50.324  4609  4609 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 07:10:50.324  4609  4609 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@13713f3f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 07:10:50.324  4609  4609 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-17 07:10:50.324  4609  4609 D AndroidMusic: GMSCore installation verified
,03-17 07:10:50.344  1187  1187 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
03-17 07:10:50.344  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
03-17 07:10:50.344  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:50.344  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:50.344  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:50.344  1020  1134 D WifiP2pService: InactiveState{ what=143375 }
03-17 07:10:50.344  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:50.344  1020  1134 D WifiP2pService: P2pEnabledState{ what=143375 }
,03-17 07:10:50.354  1187  1187 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-17 07:10:50.354  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
03-17 07:10:50.354   277  1015 D EnterpriseController: uids 1000
03-17 07:10:50.354   277  1015 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 07:10:50.354   277  1015 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,03-17 07:10:50.354   277  1019 D CommandListener: Clearing all IP addresses on wlan0
,03-17 07:10:50.354  1020  2122 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
03-17 07:10:50.354  1020  2122 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,03-17 07:10:50.354  1020  1137 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,03-17 07:10:50.354  1020  1137 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,03-17 07:10:50.354  1020  1137 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-17 07:10:50.354  1470  1470 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
03-17 07:10:50.354  1020  1137 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
03-17 07:10:50.354  1470  1470 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-17 07:10:50.354  1020  1137 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
03-17 07:10:50.354  2076  2816 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
03-17 07:10:50.354  1020  1137 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,03-17 07:10:50.354  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:50.354  1020  1134 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
03-17 07:10:50.354  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:50.354  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:50.354  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:50.354  1187  1713 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
03-17 07:10:50.364  1020  2122 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,03-17 07:10:50.364  1020  1020 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,03-17 07:10:50.364  1020  1138 D Tethering: MasterInitialState.processMessage what=3
,03-17 07:10:50.364  1020  1132 V NetworkStats: updateIfacesLocked()
,03-17 07:10:50.364  1020  1132 V NetworkStats: performPollLocked(flags=0x1)
,03-17 07:10:50.364  1020  1132 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 07:10:50.364  1187  1187 D StatusBar.NetworkController: EthernetConnected: false
03-17 07:10:50.364  1187  1187 D StatusBar.NetworkController: getUpdateDataNetType(): 0
03-17 07:10:50.364  1187  1187 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
03-17 07:10:50.364  1187  1187 D StatusBar.NetworkController: updateDataNetType()
03-17 07:10:50.364  1187  1187 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
03-17 07:10:50.364  1187  1187 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,03-17 07:10:50.364  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
,03-17 07:10:50.374  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 07:10:50.374  1020  1132 D NetworkStatsFactory: UpdateStatsForKnox updated
,03-17 07:10:50.374  1020  1132 D NetworkStatsFactory: UpdateStatsForKnox main else ---
03-17 07:10:50.374  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 07:10:50.374  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 07:10:50.374  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 07:10:50.374  1020  1133 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
03-17 07:10:50.374  1187  1187 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
03-17 07:10:50.374  1187  1187 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x0 gsm|lte
,03-17 07:10:50.374  1187  1187 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
03-17 07:10:50.374  1187  1187 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:50.374  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
03-17 07:10:50.374  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:50.374  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:50.374  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:50.374  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:50.374  1020  1049 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
03-17 07:10:50.374  1020  1137 D ConnectivityService: nai.networkMonitor.doQuit()
03-17 07:10:50.374  1020  1137 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,03-17 07:10:50.374  1020  1049 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,03-17 07:10:50.374  1020  1132 V NetworkStats: performPollLocked() took 13ms
,03-17 07:10:50.374  1020  1132 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 07:10:50.374  1187  1187 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:50.374  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
03-17 07:10:50.374  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:50.374  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:50.374  1020  1033 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
03-17 07:10:50.374  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:50.374  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
03-17 07:10:50.374  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:50.374  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:50.374  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:50.374  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 07:10:50.384  1020  1135 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,03-17 07:10:50.394  1020  1135 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,03-17 07:10:50.394  1020  1135 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
03-17 07:10:50.394  1020  1135 D SecContentProvider2: mCursor = null
,03-17 07:10:50.394  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 07:10:50.394  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 07:10:50.394  1020  1135 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
03-17 07:10:50.394  1020  1135 D SecContentProvider2: mCursor = null
,03-17 07:10:50.414  4609  4609 I ConfigStore: Config Database version: 1
,03-17 07:10:50.434   256   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-17 07:10:50.434   256   516 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:50.434  4684  4715 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-17 07:10:50.444   256   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-17 07:10:50.444   256   516 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:50.444  4684  4715 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-17 07:10:50.464  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,03-17 07:10:50.464  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,03-17 07:10:50.464  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,03-17 07:10:50.464  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
03-17 07:10:50.464  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,03-17 07:10:50.464  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,03-17 07:10:50.464  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,03-17 07:10:50.474  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,03-17 07:10:50.474  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,03-17 07:10:50.474  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,03-17 07:10:50.474  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,03-17 07:10:50.484  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
03-17 07:10:50.484  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
03-17 07:10:50.484  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
03-17 07:10:50.484  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,03-17 07:10:50.484  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,03-17 07:10:50.484  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,03-17 07:10:50.484  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,03-17 07:10:50.484  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,03-17 07:10:50.494  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,03-17 07:10:50.494   256   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-17 07:10:50.494   256   516 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:50.494  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,03-17 07:10:50.494  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,03-17 07:10:50.494  4684  4719 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-17 07:10:50.494  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,03-17 07:10:50.494  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,03-17 07:10:50.504  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,03-17 07:10:50.504   256   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-17 07:10:50.504   256   516 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:50.504  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
03-17 07:10:50.504  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,03-17 07:10:50.504  4684  4719 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-17 07:10:50.504  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
03-17 07:10:50.504  1470  1470 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,03-17 07:10:50.504  1470  1470 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,03-17 07:10:50.544  1020  2880 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
03-17 07:10:50.544  1020  2880 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,03-17 07:10:50.544  1020  2880 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:50.544  1020  2880 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,03-17 07:10:50.544  1020  2880 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,03-17 07:10:50.554  4667  4667 D hcjo    : AutoUpdateManager:IDLE:execute
,03-17 07:10:50.554   256   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-17 07:10:50.554   256   516 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:50.554  4609  4609 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-17 07:10:50.554  4557  4557 E JX-Cordova: JXcore wasn't initialized yet
,03-17 07:10:50.564  4609  4609 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-17 07:10:50.564   256   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-17 07:10:50.564   256   516 W Vold    : Returning OperationFailed - no handler for errno 0
03-17 07:10:50.564  4667  4667 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,03-17 07:10:50.564  4667  4667 D InitializeManagerStateMachine: exit::IDLE
03-17 07:10:50.564  4667  4667 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,03-17 07:10:50.564   256   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-17 07:10:50.564   256   516 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 07:10:50.564  4667  4667 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_NOT_OK
03-17 07:10:50.564  4667  4667 D InitializeManagerStateMachine: exit::NETWORK_CHECK
03-17 07:10:50.564  4667  4667 D InitializeManagerStateMachine: entry::FAILED
03-17 07:10:50.564  4667  4667 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeFailed
03-17 07:10:50.564  4609  4609 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
03-17 07:10:50.574  4667  4667 D InitializeManagerStateMachine: exit::FAILED
03-17 07:10:50.574  4667  4667 D InitializeManagerStateMachine: entry::IDLE
,03-17 07:10:50.584  1020  1033 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,03-17 07:10:50.584  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,03-17 07:10:50.584  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:50.584  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:50.584  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 07:10:50.594  1020  2931 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
03-17 07:10:50.594  1020  2931 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,03-17 07:10:50.594  1020  2931 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:50.594  1020  2931 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:50.594  1020  2931 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 07:10:50.614  1020  1516 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 07:10:50.624  1020  2934 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 07:10:50.634  1020  2933 I AudioService: getStreamVolume 3 index 0
,03-17 07:10:50.634  4609  4609 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,03-17 07:10:50.644  4609  4609 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-17 07:10:50.684  1020  1033 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
03-17 07:10:50.684  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-17 07:10:50.684  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:50.684  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:50.684  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 07:10:50.684  1020  1032 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,03-17 07:10:50.684  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,03-17 07:10:50.694  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:50.694  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:50.694  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 07:10:50.694  1020  2934 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,03-17 07:10:50.694  1020  2934 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,03-17 07:10:50.694  1020  2934 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:50.694  1020  2934 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:50.694  1020  2934 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 07:10:50.704  1020  2880 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 07:10:50.714  1020  1020 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,03-17 07:10:50.714  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.714  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.714  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.714  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.714  4684  4684 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-17 07:10:50.724  4753  4753 E Zygote  : MountEmulatedStorage()
,03-17 07:10:50.724  4753  4753 E Zygote  : v2
03-17 07:10:50.724  4753  4753 I libpersona: KNOX_SDCARD checking this for 10002
03-17 07:10:50.724  4753  4753 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:50.724  4753  4753 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:50.734  4753  4753 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:50.734  1020  1020 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4753 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 07:10:50.734  4753  4753 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 07:10:50.734  1020  1307 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 07:10:50.734  1020  1307 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:50.734  1020  1307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:50.734  1020  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,03-17 07:10:50.754   287   287 E SMD     : DCD OFF
03-17 07:10:50.754  4684  4684 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2728-2731)
,03-17 07:10:50.754  4684  4684 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 07:10:50.764  4753  4753 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:50.764  1020  2931 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
03-17 07:10:50.764  1020  2931 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,03-17 07:10:50.764  4753  4753 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:50.764  1020  2931 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:50.764  1020  2931 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 07:10:50.764  1020  2931 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,03-17 07:10:50.764  4684  4684 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {35594a4}
,03-17 07:10:50.764  4684  4684 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 07:10:50.764  4684  4684 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,03-17 07:10:50.774  4609  4609 W GoogleHttpClient: Failed to load SSLCertificateSocketFactory from package
03-17 07:10:50.774  4609  4609 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,03-17 07:10:50.774  4609  4609 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,03-17 07:10:50.774  1020  2934 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,03-17 07:10:50.774  1020  2934 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-17 07:10:50.784  1020  2934 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:50.784  1020  2934 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:50.784  1020  2934 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 07:10:50.794  4684  4684 I BrowserStartupController: Initializing chromium process, singleProcess=true,
03-17 07:10:50.794  4684  4684 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 07:10:50.794  4684  4684 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 07:10:50.814  4684  4684 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,03-17 07:10:50.814  4684  4684 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,03-17 07:10:50.814  4684  4684 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,03-17 07:10:50.824  4684  4684 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 07:10:50.824  4684  4684 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 07:10:50.824  4684  4684 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 07:10:50.824  4684  4684 I Adreno-EGL: Local Branch: 
03-17 07:10:50.824  4684  4684 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 07:10:50.824  4684  4684 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 07:10:50.824  4684  4684 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 07:10:50.854  1020  1137 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,03-17 07:10:50.864  1020  1020 I ApplicationPolicy: updateDataUsageMap
,03-17 07:10:50.864  1020  1044 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,03-17 07:10:50.874  3245  3245 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,03-17 07:10:50.884  3245  3245 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,03-17 07:10:50.894  3196  3196 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-17 07:10:50.894  3196  3196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 07:10:50.894  3196  3196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 07:10:50.894  3196  3196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 07:10:50.894  3196  3196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 07:10:50.894  3196  3196 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-17 07:10:50.894  3196  3196 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-17 07:10:50.894  3196  3196 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,03-17 07:10:50.894  3196  3196 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-17 07:10:50.904  1020  1491 I ActivityManager: Killing 3904:com.vlingo.midas/u0a31 (adj 15): empty #31
,03-17 07:10:50.914  4684  4783 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-17 07:10:50.924  4684  4684 I NSApplication: Starting up...
,03-17 07:10:50.924  1020  2931 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,03-17 07:10:50.924  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.924  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.924  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.924  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.944  4789  4789 E Zygote  : MountEmulatedStorage()
,03-17 07:10:50.944  4789  4789 E Zygote  : v2
03-17 07:10:50.944  4789  4789 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:50.944  4789  4789 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:50.944  4789  4789 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:50.944  1020  2931 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4789 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 07:10:50.944  4789  4789 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 07:10:50.944  4789  4789 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:50.954  1020  2933 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,03-17 07:10:50.964  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.964  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.964  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:50.964  1020  2933 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:50.974  4789  4789 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:50.974  4789  4789 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:50.974  4804  4804 E Zygote  : MountEmulatedStorage(),
03-17 07:10:50.974  4804  4804 I libpersona: KNOX_SDCARD checking this for 10120
03-17 07:10:50.974  4804  4804 E Zygote  : v2,
03-17 07:10:50.974  4804  4804 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:50.974  4804  4804 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:50.974  1020  2933 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4804 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
03-17 07:10:50.974  4804  4804 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:50.984  4804  4804 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 07:10:50.984  1020  2933 I ActivityManager: Killing 4025:com.android.vending/u0a28 (adj 15): empty #31,
03-17 07:10:50.984  1020  2933 I ActivityManager: Killing 4143:com.samsung.helphub/1000 (adj 15): empty #32
03-17 07:10:50.984  1020  2933 I ActivityManager: Killing 3997:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #33
,03-17 07:10:51.014  4804  4804 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:51.014  4804  4804 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:51.044  4804  4804 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 07:10:51.044  1020  1098 V AlarmManager: waitForAlarm result :4
,03-17 07:10:51.054  4789  4789 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-17 07:10:51.124  1020  1044 W libprocessgroup: failed to open /acct/uid_10031/pid_3904/cgroup.procs: No such file or directory
,03-17 07:10:51.124  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_4143/cgroup.procs: No such file or directory
,03-17 07:10:51.124  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3997/cgroup.procs: No such file or directory
,03-17 07:10:51.124  1020  1044 W libprocessgroup: failed to open /acct/uid_10028/pid_4025/cgroup.procs: No such file or directory
,03-17 07:10:51.194  4789  4789 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-17 07:10:51.204  4789  4789 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-17 07:10:51.204  4789  4789 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,03-17 07:10:51.214  4789  4789 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-17 07:10:51.214  4789  4789 I DIAGMON_AGENT: ./extraInfo: "NG700"
,03-17 07:10:51.214  4789  4789 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-17 07:10:51.264  4264  4661 I SA      : [RC New] Execute method=[GET] start
,03-17 07:10:51.274  1945  1945 I wpa_supplicant: nl80211: Received scan results (17 BSSes)
03-17 07:10:51.274  1945  1945 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
03-17 07:10:51.274  1945  1945 I wpa_supplicant: Trying to associate with SSID '4E47373030'
03-17 07:10:51.274  1945  1945 I wpa_supplicant: Trying to associate with  'G700'
03-17 07:10:51.274  1945  1945 I wpa_supplicant: Re-associate with F4.99.3E
03-17 07:10:51.274  1945  1945 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
03-17 07:10:51.274  1945  1945 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
03-17 07:10:51.274  1020  2053 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,03-17 07:10:51.284  1020  1135 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
03-17 07:10:51.284  1020  1135 D SecContentProvider2: mCursor = null
,03-17 07:10:51.304  4264  4661 I SA      : [RC New] Security=[true]
,03-17 07:10:51.304  4264  4661 I System.out: Thread-635(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 07:10:51.304  4264  4661 I System.out: Thread-635(ApacheHTTPLog):isSBSettingEnabled false
03-17 07:10:51.304  4264  4661 I System.out: Thread-635(ApacheHTTPLog):isShipBuild true
03-17 07:10:51.304  4264  4661 I System.out: Thread-635(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 07:10:51.304  4264  4661 I System.out: Thread-635(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 07:10:51.304   277  1015 D EnterpriseController: uids 10041
03-17 07:10:51.304   277  1015 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 07:10:51.304   277  1015 D Netd    : getNetworkForDns: using netid 0 for uid 10041
,03-17 07:10:51.314  4264  4661 I System.out: AsyncTask #1 calls detatch()
,03-17 07:10:51.314  4264  4661 I SA      : [SRS] prepareGetMyCountryZone
,03-17 07:10:51.314  1020  1344 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,03-17 07:10:51.324  4264  4661 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
03-17 07:10:51.324  4264  4661 I SA      : [SSP] query invoked
,03-17 07:10:51.324  1020  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.324  1020  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.324  1020  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.324  1020  1344 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:51.324  4264  4661 I SA      : [TPMU] GetMccFromDB : null
03-17 07:10:51.324  4264  4661 I SA      : [SCU] getMccFromPreferece mcc = 260
03-17 07:10:51.324  4264  4661 I SA      : [TPM] isNoProxy(default) : true
03-17 07:10:51.324  4264  4661 I SA      : [RC New] Execute method=[GET] start
,03-17 07:10:51.334  4826  4826 E Zygote  : MountEmulatedStorage()
03-17 07:10:51.334  4826  4826 E Zygote  : v2
,03-17 07:10:51.334  4826  4826 I libpersona: KNOX_SDCARD checking this for 10009
03-17 07:10:51.334  4826  4826 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:51.334  4826  4826 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:51.334  4826  4826 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:51.334  1020  1344 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4826 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 07:10:51.344  4826  4826 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 07:10:51.354  4264  4661 I SA      : [RC New] Security=[true]
,03-17 07:10:51.354  4264  4661 I System.out: Thread-635(ApacheHTTPLog):isSBSettingEnabled false
03-17 07:10:51.354  4264  4661 I System.out: Thread-635(ApacheHTTPLog):isShipBuild true
03-17 07:10:51.354  4264  4661 I System.out: Thread-635(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 07:10:51.354  4264  4661 I System.out: Thread-635(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 07:10:51.354  4264  4661 I System.out: AsyncTask #1 calls detatch()
03-17 07:10:51.354  4264  4661 W System.err: java.net.UnknownHostException: Unable to resolve host "api.samsungosp.com": No address associated with hostname
,03-17 07:10:51.354  4264  4661 W System.err: 	at java.net.InetAddress.lookupHostByName(InetAddress.java:427)
03-17 07:10:51.354  4264  4661 W System.err: 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
03-17 07:10:51.354  4264  4661 W System.err: 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
03-17 07:10:51.354  4264  4661 W System.err: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:180)
03-17 07:10:51.354  4264  4661 W System.err: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-17 07:10:51.354  4264  4661 W System.err: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-17 07:10:51.354  4264  4661 W System.err: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-17 07:10:51.354  4826  4826 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:51.354  4264  4661 W System.err: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-17 07:10:51.354  4264  4661 W System.err: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-17 07:10:51.354  4264  4661 W System.err: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-17 07:10:51.354  4264  4661 W System.err: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-17 07:10:51.354  4264  4661 W System.err: 	at com.msc.b.d.a(HttpRestClient.java:378)
03-17 07:10:51.354  4264  4661 W System.err: 	at com.msc.b.d.a(HttpRestClient.java:679)
03-17 07:10:51.354  4264  4661 W System.err: 	at com.msc.b.i.a(TransactionManager.java:159)
03-17 07:10:51.354  4264  4661 W System.err: 	at com.msc.c.g.a(HttpRequestSet.java:4909)
03-17 07:10:51.354  4264  4661 W System.err: 	at com.osp.app.signin.gp.h(OspReceiver.java:827)
03-17 07:10:51.354  4264  4661 W System.err: 	at com.osp.app.signin.gp.b(OspReceiver.java:805)
03-17 07:10:51.354  4264  4661 W System.err: 	at com.msc.b.d.a(HttpRestClient.java:393)
03-17 07:10:51.354  4264  4661 W System.err: 	at com.msc.b.d.a(HttpRestClient.java:679)
03-17 07:10:51.354  4264  4661 W System.err: 	at com.msc.b.i.a(TransactionManager.java:159)
03-17 07:10:51.354  4264  4661 W System.err: 	at com.msc.c.g.a(HttpRequestSet.java:4909)
03-17 07:10:51.354  4264  4661 W System.err: 	at com.osp.app.signin.gp.h(OspReceiver.java:827)
03-17 07:10:51.354  4264  4661 W System.err: 	at com.osp.app.signin.gp.a(OspReceiver.java:701)
03-17 07:10:51.354  4264  4661 W System.err: 	at com.osp.app.signin.gp.doInBackground(OspReceiver.java:663)
03-17 07:10:51.354  4264  4661 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
03-17 07:10:51.354  4264  4661 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 07:10:51.354  4264  4661 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 07:10:51.354  4264  4661 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 07:10:51.354  4264  4661 W System.err: 	at java.lang.Thread.run(Thread.java:818)
03-17 07:10:51.354  4264  4661 I SA      : [RC New] executeRequest [v2liruge] end. 33
03-17 07:10:51.354  4264  4661 I SA      : [RC New] Execute end
03-17 07:10:51.354  4264  4661 W System.err: java.net.UnknownHostException: Unable to resolve host "api.samsungosp.com": No address associated with hostname
03-17 07:10:51.354  4826  4826 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:51.354  4264  4661 W System.err: 	at java.net.InetAddress.lookupHostByName(InetAddress.java:457)
03-17 07:10:51.354  4264  4661 W System.err: 	at java.net.InetAddress.getAllByNameImpl(InetAddress.java:252)
03-17 07:10:51.354  4264  4661 W System.err: 	at java.net.InetAddress.getAllByName(InetAddress.java:215)
03-17 07:10:51.354  4264  4661 W System.err: 	at org.apache.http.impl.con,n.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:180)
03-17 07:10:51.354  4264  4661 W System.err: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:167)
03-17 07:10:51.354  4264  4661 W System.err: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:125)
03-17 07:10:51.354  4264  4661 W System.err: 	at org.apache.http.impl.client.DefaultRequestDirector.executeOriginal(DefaultRequestDirector.java:1312)
03-17 07:10:51.354  4264  4661 W System.err: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:702)
03-17 07:10:51.354  4264  4661 W System.err: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:694)
03-17 07:10:51.354  4264  4661 W System.err: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:516)
03-17 07:10:51.354  4264  4661 W System.err: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:494)
03-17 07:10:51.354  4264  4661 W System.err: 	at com.msc.b.d.a(HttpRestClient.java:378)
,03-17 07:10:51.354  4264  4661 W System.err: 	at com.msc.b.d.a(HttpRestClient.java:679)
03-17 07:10:51.354  4264  4661 W System.err: 	at com.msc.b.i.a(TransactionManager.java:159)
,03-17 07:10:51.354  4264  4661 W System.err: 	at com.msc.c.g.a(HttpRequestSet.java:4909),
03-17 07:10:51.354  4264  4661 W System.err: 	at com.osp.app.signin.gp.h(OspReceiver.java:827)
03-17 07:10:51.354  4264  4661 W System.err: 	at com.osp.app.signin.gp.a(OspReceiver.java:701)
,03-17 07:10:51.354  4264  4661 W System.err: 	at com.osp.app.signin.gp.doInBackground(OspReceiver.java:663)
03-17 07:10:51.354  4264  4661 W System.err: 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
03-17 07:10:51.354  4264  4661 W System.err: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 07:10:51.354  4264  4661 W System.err: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,03-17 07:10:51.354  4264  4661 W System.err: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 07:10:51.354  4264  4661 W System.err: 	at java.lang.Thread.run(Thread.java:818)
03-17 07:10:51.354  4264  4661 W System.err: Caused by: android.system.GaiException: android_getaddrinfo failed: EAI_NODATA (No address associated with hostname)
03-17 07:10:51.354  4264  4661 W System.err: 	at libcore.io.Posix.android_getaddrinfo(Native Method)
03-17 07:10:51.354  4264  4661 W System.err: 	at libcore.io.ForwardingOs.android_getaddrinfo(ForwardingOs.java:55)
,03-17 07:10:51.354  4264  4661 W System.err: 	at java.net.InetAddress.lookupHostByName(InetAddress.java:438)
03-17 07:10:51.354  4264  4661 W System.err: 	... 22 more
03-17 07:10:51.354  4264  4661 I SA      : [RC New] executeRequest [v2liruge] end. 93
03-17 07:10:51.354  4264  4661 I SA      : [RC New] Execute end
,03-17 07:10:51.364  4264  4264 I SA      : [OR] GetMyCountryZoneTask mcc = null
03-17 07:10:51.364  4264  4264 I SA      : [OR] GetMyCountryZoneTask Fail
,03-17 07:10:51.384  1945  1945 E wpa_supplicant: Cmd 35605 not handled
,03-17 07:10:51.384  1945  1945 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
03-17 07:10:51.384  1945  1945 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
03-17 07:10:51.384  1945  1945 I wpa_supplicant: Associated with F4.99.3E
,03-17 07:10:51.384  1945  1945 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
03-17 07:10:51.384  1945  1945 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
03-17 07:10:51.384  1945  1945 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,03-17 07:10:51.384  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,03-17 07:10:51.384  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
,03-17 07:10:51.384  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,03-17 07:10:51.394  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,03-17 07:10:51.394  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
03-17 07:10:51.394  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,03-17 07:10:51.394  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,03-17 07:10:51.394  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
03-17 07:10:51.394  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,03-17 07:10:51.394  1020  1135 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
03-17 07:10:51.394  1020  1135 D SecContentProvider2: mCursor = null
03-17 07:10:51.394  1945  1945 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,03-17 07:10:51.394  1945  1945 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,03-17 07:10:51.394  1945  1945 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
03-17 07:10:51.394  1945  1945 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,03-17 07:10:51.394  1020  1135 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
03-17 07:10:51.394  1020  1135 D SecContentProvider2: mCursor = null
,03-17 07:10:51.404  1945  1945 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
03-17 07:10:51.404  1945  1945 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
03-17 07:10:51.404  1945  1945 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,03-17 07:10:51.404  1945  1945 I wpa_supplicant: Blacklist: Clear (temp) 
03-17 07:10:51.404  1945  1945 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,03-17 07:10:51.404  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
03-17 07:10:51.404  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, true
03-17 07:10:51.404  1020  1047 D Tethering: interfaceStatusChanged wlan0, true
,03-17 07:10:51.404  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
03-17 07:10:51.404  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, true
03-17 07:10:51.404  1020  1047 D Tethering: interfaceStatusChanged wlan0, true
03-17 07:10:51.404  1020  1138 E Tethering: No numeric data
,03-17 07:10:51.404  1020  1135 D WifiNative-wlan0: callSECApiVoid - ID [50]
,03-17 07:10:51.404  4386  4386 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,03-17 07:10:51.404  1020  1135 E WifiConfigStore: setLastSelectedConfiguration -1
,03-17 07:10:51.414  4386  4386 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
03-17 07:10:51.414  4386  4386 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-17 07:10:51.414  1020  1135 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,03-17 07:10:51.414  1020  1137 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
03-17 07:10:51.414  1020  1137 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
03-17 07:10:51.414  1020  1137 E ConnectivityService: updateNetworkInfo()
,03-17 07:10:51.414  1020  1138 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
03-17 07:10:51.414  1020  1138 D Tethering: clearTetheredNotification()
,03-17 07:10:51.424  1187  1187 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:51.424  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
03-17 07:10:51.424  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:51.424  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:51.424  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:51.424  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:51.424  1020  1132 V NetworkStats: performPollLocked(flags=0x1)
03-17 07:10:51.424  1020  1132 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 07:10:51.424  1020  1132 D NetworkStatsFactory: UpdateStatsForKnox updated
03-17 07:10:51.424  1020  1132 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-17 07:10:51.424  1187  1187 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,03-17 07:10:51.424  1187  1187 D HotspotTile: updateTetherState():false, false
,03-17 07:10:51.424  1020  1135 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-17 07:10:51.424  1020  1130 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,03-17 07:10:51.424  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:51.424  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.424  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.434  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:51.434  1020  1135 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-17 07:10:51.434  1020  1132 V NetworkStats: performPollLocked() took 9ms
03-17 07:10:51.434  1020  1132 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 07:10:51.444   277  1019 D CommandListener: Setting iface cfg
,03-17 07:10:51.444  1020  1135 E WifiStateMachine: Start Dhcp Watchdog 2
,03-17 07:10:51.444  4844  4844 E Zygote  : MountEmulatedStorage()
03-17 07:10:51.444  4844  4844 E Zygote  : v2
03-17 07:10:51.444  1020  1135 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
03-17 07:10:51.444  1020  1135 D SecContentProvider2: mCursor = null
03-17 07:10:51.444  1020  1130 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=4844 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,03-17 07:10:51.444  4844  4844 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 07:10:51.444  4844  4844 I libpersona: KNOX_SDCARD checking this for 10145
03-17 07:10:51.444  4844  4844 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:51.454  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 07:10:51.454  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 07:10:51.454  4844  4844 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:51.454  4844  4844 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:51.464  1020  1135 E WifiNative-wlan0: do suspend false
,03-17 07:10:51.474  1020  1135 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
03-17 07:10:51.474  1020  1135 D SecContentProvider2: mCursor = null
03-17 07:10:51.474  1020  2931 I ActivityManager: Killing 4181:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,03-17 07:10:51.474  1020  1134 D WifiP2pService: InactiveState{ what=143375 }
03-17 07:10:51.474  1020  1134 D WifiP2pService: P2pEnabledState{ what=143375 }
,03-17 07:10:51.474  4826  4826 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 07:10:51.484  4844  4844 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:51.484  4844  4844 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:51.494  4826  4826 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-17 07:10:51.494  4826  4826 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-17 07:10:51.494  4826  4826 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-17 07:10:51.494  1020  1362 I ActivityManager: Killing 4223:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,03-17 07:10:51.504  4844  4844 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 07:10:51.504  4844  4844 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:51.504  4844  4844 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 07:10:51.504  4844  4844 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:51.504  4844  4844 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 07:10:51.524   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=4, Uoast
,03-17 07:10:51.534  1187  1187 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 07:10:51.574  1020  1130 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:51.574  1020  2931 I ActivityManager: Killing 4250:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,03-17 07:10:51.584  1020  1491 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:51.614  1020  2883 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:51.634  1020  1130 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:51.634  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_4181/cgroup.procs: No such file or directory
,03-17 07:10:51.644  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_4223/cgroup.procs: No such file or directory
,03-17 07:10:51.644  1020  1044 W libprocessgroup: failed to open /acct/uid_10107/pid_4250/cgroup.procs: No such file or directory
,03-17 07:10:51.684  4867  4867 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,03-17 07:10:51.684  4867  4867 I dhcpcd  : version 5.5.6 starting
,03-17 07:10:51.684  1020  1054 D PowerManagerService: [s] UserActivityState : 2 -> 4
,03-17 07:10:51.684  1020  1054 I PowerManagerService: [PWL] On : 0 (53665 ms ago)
03-17 07:10:51.684  1020  1054 I PowerManagerService: [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
03-17 07:10:51.684  1020  1054 I PowerManagerService: [PWL]  SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1020, ws=WorkSource{10054}) (elapsedTime=3620)
,03-17 07:10:51.684  4867  4867 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,03-17 07:10:51.704  1020  1491 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:51.704  4482  4490 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-17 07:10:51.714  1020  1032 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:51.724  4482  4509 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-17 07:10:51.724  4482  4509 D BadgeProvider: sendNotify, [notify] : null
03-17 07:10:51.724  4482  4509 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-17 07:10:51.724  4482  4509 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 07:10:51.724  4482  4509 D BadgeProvider: update, [UpdateCount] : 1
,03-17 07:10:51.724  1492  1492 D Launcher.Model: reloadBadges entered.
,03-17 07:10:51.744  1020  1032 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:51.754  4867  4867 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
03-17 07:10:51.754  4867  4867 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
03-17 07:10:51.754  4867  4867 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
03-17 07:10:51.754  4867  4867 I dhcpcd  : bssid match
,03-17 07:10:51.754  4867  4867 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,03-17 07:10:51.754  1020  1130 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 07:10:51.754  1020  1362 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-17 07:10:51.754  1020  1362 I ActivityManager: Killing 4351:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-17 07:10:51.764  1020  1020 I splitIntent: Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=18, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=24
,03-17 07:10:51.764  1020  1020 I splitIntent: finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,03-17 07:10:51.774  4826  4826 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 07:10:51.774  1020  1045 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,03-17 07:10:51.774  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:51.774  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.774  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.774  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:51.784   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 07:10:51.794  4877  4877 E Zygote  : MountEmulatedStorage()
03-17 07:10:51.794  4877  4877 E Zygote  : v2
03-17 07:10:51.794  4877  4877 I libpersona: KNOX_SDCARD checking this for 10062
,03-17 07:10:51.794  4877  4877 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:51.794  1020  1045 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4877 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-17 07:10:51.794  4877  4877 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:51.804  4877  4877 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:51.804  4877  4877 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:51.804  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 07:10:51.804  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 07:10:51.804  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 07:10:51.814  1020  1491 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
03-17 07:10:51.814  1020  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,03-17 07:10:51.814  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:51.814  1020  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:51.814  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-17 07:10:51.814  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 07:10:51.824  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-17 07:10:51.824  4826  4826 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,03-17 07:10:51.834  1329  1329 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,03-17 07:10:51.834  1329  1329 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 07:10:51.834  1329  1329 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,03-17 07:10:51.834  1329  1329 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-17 07:10:51.834  1329  1329 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,03-17 07:10:51.834  1329  1329 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,03-17 07:10:51.834  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 07:10:51.834  4877  4877 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:51.834  4867  4867 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,03-17 07:10:51.834  4877  4877 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:51.844  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-17 07:10:51.844  3798  3798 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Thu Mar 17 07:10:51 GMT+01:00 2016
,03-17 07:10:51.844  1020  2934 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
03-17 07:10:51.844  1020  2934 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
03-17 07:10:51.844  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 07:10:51.844  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 07:10:51.844  1329  1329 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-17 07:10:51.844  1020  2934 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:51.844  1020  2934 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:51.844  1020  2934 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
03-17 07:10:51.844  1329  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 07:10:51.854  1020  1130 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,03-17 07:10:51.854  1020  1130 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-17 07:10:51.854  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:51.854  1020  1130 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:51.854  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
03-17 07:10:51.854  1329  1329 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-17 07:10:51.854  3798  3798 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-17 07:10:51.864  4540  4540 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,03-17 07:10:51.864  4540  4540 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-17 07:10:51.864  4540  4540 D SecurityLogAgent: StateMachine : Current State = 1
,03-17 07:10:51.864  1329  1329 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,03-17 07:10:51.874  1329  1329 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-17 07:10:51.874  3798  3798 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-17 07:10:51.874  4264  4264 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,03-17 07:10:51.874  1020  1491 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,03-17 07:10:51.884  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_4351/cgroup.procs: No such file or directory
,03-17 07:10:51.884  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.884  3798  3798 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
03-17 07:10:51.884  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.884  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.884  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:51.884  3798  3798 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 07:10:51.894  4896  4896 E Zygote  : MountEmulatedStorage()
03-17 07:10:51.894  4896  4896 E Zygote  : v2
03-17 07:10:51.894  4896  4896 I libpersona: KNOX_SDCARD checking this for 10157
03-17 07:10:51.894  4896  4896 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:51.894  4896  4896 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:51.894  3798  4895 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,03-17 07:10:51.904  4867  4867 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds
,03-17 07:10:51.904  1020  1491 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4896 uid=10157 gids={50157, 9997} abi=armeabi-v7a
03-17 07:10:51.904  4896  4896 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:51.904  4896  4896 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:51.914  4877  4877 I ExternalOEMControlProvider: onCreate
,03-17 07:10:51.914  3798  4895 I KLMS-2.5.183: : KLMSIntentService(): TIME_CHANGED
,03-17 07:10:51.924  3798  4895 I KLMS-2.5.183: : StateImplV2(): dateTimeChanged().START : Thu Mar 17 07:10:51 GMT+01:00 2016
,03-17 07:10:51.924  1020  2931 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 07:10:51.924  1020  2931 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,03-17 07:10:51.924  1020  2931 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:51.924  1020  2931 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:51.924  1020  2931 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 07:10:51.924  3798  4895 I KLMS-2.5.183: : StateImplV2(): dateTimeChanged().END
,03-17 07:10:51.934  1020  1516 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,03-17 07:10:51.934  1020  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.934  1020  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.934  1020  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.934  1020  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:51.954  4918  4918 E Zygote  : MountEmulatedStorage()
03-17 07:10:51.954  4918  4918 E Zygote  : v2
03-17 07:10:51.954  4918  4918 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:51.954  4918  4918 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:51.954  4918  4918 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:51.954  4918  4918 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:51.954  1020  1516 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.contextagent.ContextAgentReceiver: pid=4918 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 07:10:51.954  4918  4918 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:51.964  1020  1516 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast,
,03-17 07:10:51.964  1020  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.964  1020  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.964  1020  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:51.964  1020  1516 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:51.964  4896  4896 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-17 07:10:51.964  4896  4896 D ActivityThread: Added TimaKeyStore provider,
,03-17 07:10:51.984  4932  4932 E Zygote  : MountEmulatedStorage()
03-17 07:10:51.984  4932  4932 I libpersona: KNOX_SDCARD checking this for 10046
03-17 07:10:51.984  4932  4932 E Zygote  : v2
03-17 07:10:51.984  4932  4932 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:51.984  4932  4932 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:51.984  1020  1516 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=4932 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a,
,03-17 07:10:51.984  4932  4932 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:51.984  4932  4932 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 07:10:52.004  4918  4918 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:52.004  1020  1344 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
03-17 07:10:52.004  1020  1344 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-17 07:10:52.004  4918  4918 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:52.004   309   309 I art     : Explicit concurrent mark sweep GC freed 8723(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 644us total 23.937ms
,03-17 07:10:52.024  3798  3798 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-17 07:10:52.024  1020  1307 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-17 07:10:52.024   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 18.595ms
,03-17 07:10:52.034  4877  4912 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,03-17 07:10:52.034  1020  1130 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-17 07:10:52.044   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 17.278ms
,03-17 07:10:52.054  4932  4932 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:52.054  4932  4932 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:52.064  4918  4918 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:52.064  1020  2933 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 07:10:52.064  1020  2933 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,03-17 07:10:52.064  4896  4896 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:52.074  1020  2933 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:52.074  1020  2933 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:52.074  1020  2933 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:52.074   257   451 I SurfaceFlinger: id=12 Removed Uoast (8/9)
,03-17 07:10:52.074   257   802 I SurfaceFlinger: id=12 Removed Uoast (-2/9)
,03-17 07:10:52.094  1020  1033 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,03-17 07:10:52.094  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:52.094  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:52.094  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:52.094  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:52.114  4932  4932 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.,
03-17 07:10:52.114  4932  4932 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 07:10:52.114  4932  4932 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 07:10:52.114  4932  4932 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:52.114  4932  4932 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 07:10:52.114  4932  4932 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 07:10:52.114  4964  4964 E Zygote  : MountEmulatedStorage()
,03-17 07:10:52.114  4964  4964 E Zygote  : v2
03-17 07:10:52.114  4964  4964 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:52.114  4964  4964 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:52.114  4964  4964 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:52.124  4964  4964 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 07:10:52.124  1020  1033 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4964 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
03-17 07:10:52.124  4964  4964 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 07:10:52.134  1020  1130 I ActivityManager: Killing 4401:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,03-17 07:10:52.144  4932  4932 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,03-17 07:10:52.154  4964  4964 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:52.154  4964  4964 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:52.154  1738  1738 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,03-17 07:10:52.154  1738  1738 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-17 07:10:52.164  1020  1362 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,03-17 07:10:52.164  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:52.164  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:52.164  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:52.164  1020  1362 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:52.174  4980  4980 E Zygote  : MountEmulatedStorage(),
03-17 07:10:52.174  4980  4980 E Zygote  : v2
03-17 07:10:52.174  4980  4980 I libpersona: KNOX_SDCARD checking this for 10085
03-17 07:10:52.174  4980  4980 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:52.174  4980  4980 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:52.184  4980  4980 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:52.184  1020  1362 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=4980 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 07:10:52.184  4980  4980 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:52.204  4980  4980 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:52.204  4980  4980 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:52.214  1020  2793 D SSRM:n  : SIOP:: AP = 400
,03-17 07:10:52.224  1020  2931 I ActivityManager: Killing 4440:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,03-17 07:10:52.224  4964  4964 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458195052239
,03-17 07:10:52.224  4964  4964 D         : TimeServiceNative: User Time to be set is 1458195052240
,03-17 07:10:52.224  4964  4964 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
,03-17 07:10:52.224  4964  4964 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-17 07:10:52.224  4964  4964 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458195052240
,03-17 07:10:52.234   329   561 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-17 07:10:52.234  4964  4964 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,03-17 07:10:52.234   329  4995 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458195052240
03-17 07:10:52.234   329  4995 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458195052240, operation = 0
,03-17 07:10:52.234   329  4995 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS8/16/70 4:16:6
03-17 07:10:52.234   329  4995 D QC-time-services: Daemon:Value read from RTC seconds = 22306566000
03-17 07:10:52.234   329  4995 D QC-time-services: Daemon:new time 1458195052240 
03-17 07:10:52.234   329  4995 D QC-time-services: Daemon: delta 1435888486240 genoff 1435888486240 
03-17 07:10:52.234   329  4995 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1435888486240 to memory
03-17 07:10:52.234   329  4995 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-17 07:10:52.234   329  4995 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-17 07:10:52.234  4980  4980 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 07:10:52.234  4980  4980 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 07:10:52.234  4980  4980 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 07:10:52.234  4980  4980 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 07:10:52.234  4980  4980 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 07:10:52.234  4980  4980 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,03-17 07:10:52.264   329  4995 D QC-time-services: Updating the TOD offset
03-17 07:10:52.264   329  4995 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1435888486240 to memory
03-17 07:10:52.264   329  4995 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-17 07:10:52.264   329  4995 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-17 07:10:52.274   329  4995 E QC-time-services: Daemon:Update to modem bit set
03-17 07:10:52.274   329  4995 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-17 07:10:52.274   329  4995 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1119923686240
,03-17 07:10:52.274  4964  4964 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,03-17 07:10:52.274   329   559 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-17 07:10:52.274   329   561 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-17 07:10:52.284  1020  2931 I ActivityManager: Killing 4523:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,03-17 07:10:52.294  1020  1516 I art     : Explicit concurrent mark sweep GC freed 52166(2MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 26MB/40MB, paused 2.923ms total 165.420ms
,03-17 07:10:52.304  1020  1134 D WifiP2pService: InactiveState{ what=143375 }
,03-17 07:10:52.304  1020  1134 D WifiP2pService: P2pEnabledState{ what=143375 }
,03-17 07:10:52.304  1020  1135 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
03-17 07:10:52.304  1020  1135 E WifiStateMachine: VerifyingLinkState enter
,03-17 07:10:52.304  1187  1187 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:52.304  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
03-17 07:10:52.304  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:52.304  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:52.304  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:52.304  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:52.314  1020  1135 D WifiNative-wlan0: callSECApiInt - ID [210]
,03-17 07:10:52.314  1020  1137 E ConnectivityService: updateNetworkInfo()
03-17 07:10:52.314  1020  1307 D SettingsProvider: name = next_alarm_formatted
03-17 07:10:52.314  1020  1307 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 07:10:52.314  1020  1307 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 07:10:52.314  1020  1307 D SettingsProvider: selectionArgs: false
03-17 07:10:52.314  1020  1307 D SettingsProvider: selectionArgs: 10085
03-17 07:10:52.314  1020  1307 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 07:10:52.314  1020  1307 D SettingsProvider: ret = -1
,03-17 07:10:52.314  1020  1137 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,03-17 07:10:52.314  1020  1137 D ConnectivityService: Adding iface wlan0 to network 503
,03-17 07:10:52.324  1020  2934 I ActivityManager: Killing 4572:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #31
,03-17 07:10:52.334  1020  1158 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter,
,03-17 07:10:52.334  1020  1137 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,03-17 07:10:52.334  1020  1158 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
03-17 07:10:52.334  1020  1158 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
03-17 07:10:52.334  1020  1158 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
03-17 07:10:52.334  1020  1158 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,03-17 07:10:52.334  1020  1137 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,03-17 07:10:52.344  1020  1137 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,03-17 07:10:52.344  1020  1137 E ConnectivityService: Unexpected mtu value: 0, wlan0
,03-17 07:10:52.344  1020  1137 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
03-17 07:10:52.344  1020  1137 D ConnectivityService: LTETest block dns file not exists
,03-17 07:10:52.344  1187  1187 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:52.344  1020  1137 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,03-17 07:10:52.344  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
03-17 07:10:52.344  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:52.344  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:52.344  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:52.344  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:52.354  1020  1045 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,03-17 07:10:52.354  1020  1045 W ActivityManager: Failed to clear dns cache for: com.samsung.android.app.FileShareClient
03-17 07:10:52.354  1020  1045 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
03-17 07:10:52.354  1020  1045 W ActivityManager: Failed to clear dns cache for: com.sec.android.app.SecSetupWizard
,03-17 07:10:52.354  1020  2931 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,03-17 07:10:52.354  1020  2931 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,03-17 07:10:52.354  1020  2931 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:52.354  1020  1044 W libprocessgroup: failed to open /acct/uid_10131/pid_4401/cgroup.procs: No such file or directory
,03-17 07:10:52.354  1020  2931 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-17 07:10:52.354  1020  2931 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,03-17 07:10:52.354  4932  4932 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 149.268ms
,03-17 07:10:52.364  1020  1135 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,03-17 07:10:52.364  1020  1044 W libprocessgroup: failed to open /acct/uid_10139/pid_4440/cgroup.procs: No such file or directory
,03-17 07:10:52.374  1020  1137 E ConnectivityService: updateNetworkInfo()
,03-17 07:10:52.374  1020  1137 E ConnectivityService: updateNetworkInfo()
,03-17 07:10:52.374  1020  1137 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,03-17 07:10:52.374  1020  1137 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
03-17 07:10:52.374  1020  1137 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
03-17 07:10:52.374  1020  4843 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,03-17 07:10:52.374  1020  4843 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
03-17 07:10:52.374  1020  4843 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,03-17 07:10:52.374  1020  4843 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,03-17 07:10:52.374  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
,03-17 07:10:52.374  1020  1137 D ConnectivityService:    accepting network in place of null
,03-17 07:10:52.374  1020  1134 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,03-17 07:10:52.384  1470  1470 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
03-17 07:10:52.384  1470  1470 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,03-17 07:10:52.384  1020  1137 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,03-17 07:10:52.384  1020  1137 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
,03-17 07:10:52.384  1020  1137 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,03-17 07:10:52.384  1020  4843 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-17 07:10:52.384   277  1015 D EnterpriseController: uids 1000
03-17 07:10:52.384   277  1015 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 07:10:52.384   277  1015 D Netd    : getNetworkForDns: using netid 503 for uid 1000
,03-17 07:10:52.394  1187  1187 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-17 07:10:52.394  1020  1135 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,03-17 07:10:52.394  1020  1137 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,03-17 07:10:52.394  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,03-17 07:10:52.394  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:52.394  1020  1137 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
03-17 07:10:52.394  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:52.394  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:52.394  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,03-17 07:10:52.394  2076  2816 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-17 07:10:52.394  1187  1713 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-17 07:10:52.394  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
,03-17 07:10:52.394  1020  1020 I WifiTrafficPoller: mBoosterFLAG : 0
03-17 07:10:52.394  1020  1020 I WifiTrafficPoller: current booster mode : FullMode
03-17 07:10:52.394  1020  1020 D WifiNative-wlan0: callSECApiVoid - ID [212]
,03-17 07:10:52.404  1187  1187 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-17 07:10:52.404  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
03-17 07:10:52.404  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:52.404  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:52.404  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:52.404  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:52.404  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_4523/cgroup.procs: No such file or directory
,03-17 07:10:52.414  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:52.414  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:52.414  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:52.414  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:52.414  1020  1020 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,03-17 07:10:52.414  1020  1138 D Tethering: MasterInitialState.processMessage what=3
,03-17 07:10:52.414  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:52.414  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:52.414  1020  1132 V NetworkStats: updateIfacesLocked()
,03-17 07:10:52.414  1020  1132 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 07:10:52.414  1020  1132 V NetworkStats: performPollLocked(flags=0x1)
,03-17 07:10:52.414  1020  1132 D NetworkStatsFactory: UpdateStatsForKnox updated
,03-17 07:10:52.414  1020  1132 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-17 07:10:52.414  1020  1044 W libprocessgroup: failed to open /acct/uid_10068/pid_4572/cgroup.procs: No such file or directory
,03-17 07:10:52.424  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 07:10:52.424  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 07:10:52.424  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 07:10:52.424  1020  1133 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
03-17 07:10:52.424  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 07:10:52.424  1020  1132 V NetworkStats: performPollLocked() took 6ms
03-17 07:10:52.424  1020  1132 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 07:10:52.424  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 07:10:52.424  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 07:10:52.434  4932  5002 D Mms/ArtClassLoader: init before art
,03-17 07:10:52.434  4932  4932 D Mms/TelephonyPermission: start operation mode monitor
,03-17 07:10:52.444  1187  1187 D StatusBar.NetworkController: EthernetConnected: false
,03-17 07:10:52.444  1187  1187 D StatusBar.NetworkController: getUpdateDataNetType(): 0
03-17 07:10:52.444  1187  1187 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
03-17 07:10:52.444  1187  1187 D StatusBar.NetworkController: updateDataNetType()
03-17 07:10:52.444  1187  1187 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
03-17 07:10:52.444  1187  1187 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,03-17 07:10:52.444  1187  1187 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,03-17 07:10:52.444  1187  1187 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x0 gsm|lte
,03-17 07:10:52.444  1187  1187 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,03-17 07:10:52.444  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-17 07:10:52.444  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:52.444  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:52.444  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:52.444  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:52.444  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:52.444  4932  4932 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 07:10:52.454  4932  4932 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
,03-17 07:10:52.454  4932  4932 D Mms/TelephonyPermission: isDefault true
,03-17 07:10:52.454  4932  4932 D Mms/MmsApp: onCreate() com.android.mms
,03-17 07:10:52.454  4980  4980 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 136.503ms
,03-17 07:10:52.464  1020  2875 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 07:10:52.494  1020  4843 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-17 07:10:52.494  4932  4932 D Mms/MmsApp: [start]    initCountryIso consume time = 346.588541
,03-17 07:10:52.494  1020  2880 D CountryDetector: The first listener is added
,03-17 07:10:52.494  4932  4932 D Mms/MmsApp: [end]    initCountryIso consume time = 6.303438
03-17 07:10:52.494  4932  4932 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.120781
,03-17 07:10:52.504  4932  4932 D Mms/MmsConfig: before partial update
,03-17 07:10:52.524  4932  4932 D Mms/MmsConfig: Load Resize quality : 80
,03-17 07:10:52.524  4932  4932 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,03-17 07:10:52.524  4932  4932 D EasySignUpManager_1.0.1: isAuth is false
,03-17 07:10:52.524  4932  4932 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,03-17 07:10:52.534  1470  1490 D TP/MmsSmsProvider: query,matched:2117, calling pid = 4932
,03-17 07:10:52.534  1470  1490 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.468 ms
,03-17 07:10:52.544  4932  4932 D EasySignUpManager_1.0.1: isAuth is false
,03-17 07:10:52.544  4932  4932 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,03-17 07:10:52.544  4932  4932 E CscParser: mps_code.dat does not exist
,03-17 07:10:52.544  4932  4932 E CscParser: customer_path =/system/csc/customer.xml
,03-17 07:10:52.544  4932  4932 E CscParser: fileName + /system/csc/customer.xml
,03-17 07:10:52.554  4932  4932 E CscParser: mps_code.dat does not exist
,03-17 07:10:52.554  4932  4932 E CscParser: customer_path =/system/csc/customer.xml
03-17 07:10:52.554  4932  4932 E CscParser: fileName + /system/csc/customer.xml
,03-17 07:10:52.554  1020  2931 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,03-17 07:10:52.564  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:52.564  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:52.564  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:52.564  1020  2931 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:52.564  4932  4932 D CscParser: getInstance fileName =/system/csc/customer.xml
,03-17 07:10:52.564  4932  4932 D Mms/MmsConfig:  enable multiwindow = true,
,03-17 07:10:52.574  5006  5006 E Zygote  : MountEmulatedStorage()
,03-17 07:10:52.574  5006  5006 E Zygote  : v2
03-17 07:10:52.574  5006  5006 I libpersona: KNOX_SDCARD checking this for 10094,
03-17 07:10:52.574  5006  5006 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:52.574  5006  5006 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:52.584  1020  2931 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5006 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,03-17 07:10:52.584  1020  2931 I ActivityManager: Killing 3888:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,03-17 07:10:52.584  5006  5006 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:52.584  4932  4932 E Mms/MessageUtils: setCountryDetector : update country detector info 
03-17 07:10:52.584  4932  4932 E Mms/MessageUtils: updateCountryIso : update country iso info 
,03-17 07:10:52.584  5006  5006 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:52.594  4932  4932 D Mms/MmsConfig: [end]    init() consume time = 93.324792
03-17 07:10:52.594  4932  4932 D Mms/Contact: [start]    init() consume time = 0.726979
,03-17 07:10:52.604  1470  1490 D TP/MmsSmsProvider: query,matched:13, calling pid = 4932
,03-17 07:10:52.604  1470  1490 D TP/MmsSmsProvider: match 13:Elapsed time : 1.196 ms
,03-17 07:10:52.604  1020  4843 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 17 Mar 2016 06:10:52 GMT], X-Android-Received-Millis=[1458195052623], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1458195052557]}
03-17 07:10:52.604  1020  1137 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 503]
03-17 07:10:52.604  1020  4843 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
03-17 07:10:52.604  1020  1137 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
03-17 07:10:52.604  1020  4843 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
03-17 07:10:52.604  1020  1137 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
03-17 07:10:52.614  1020  1137 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,03-17 07:10:52.614  1187  1713 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-17 07:10:52.614  1020  1137 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,03-17 07:10:52.614  5006  5006 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 07:10:52.614  2076  2816 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-17 07:10:52.614  5006  5006 D ActivityThread: Added TimaKeyStore provider
03-17 07:10:52.614  4932  4932 D Mms/Contact: [end]    init consume time = 17.795677
,03-17 07:10:52.614  1187  1187 D StatusBar.NetworkController: EthernetConnected: false
03-17 07:10:52.614  1187  1187 D StatusBar.NetworkController: getUpdateDataNetType(): 0
03-17 07:10:52.614  1187  1187 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
03-17 07:10:52.614  1187  1187 D StatusBar.NetworkController: updateDataNetType()
03-17 07:10:52.614  1187  1187 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
03-17 07:10:52.614  1187  1187 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,03-17 07:10:52.624  1187  1187 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,03-17 07:10:52.624  1187  1187 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 0x0 gsm|lte
03-17 07:10:52.624  1187  1187 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,03-17 07:10:52.624  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 07:10:52.624  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 07:10:52.624  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:52.624  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:52.624  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 07:10:52.624  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 07:10:52.624  4932  5024 D Mms/DraftCache: [start]    rebuildCache consume time = 17.480156
,03-17 07:10:52.634  4932  4932 D Mms/MethodReflector: getSubId is called
03-17 07:10:52.634  4932  4932 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-17 07:10:52.634  1470  2140 D TP/MmsSmsProvider: query,matched:12, calling pid = 4932
,03-17 07:10:52.634  1470  2140 D TP/MmsSmsProvider: match 12:Elapsed time : 1.226 ms
,03-17 07:10:52.634  4932  4932 D Mms/MethodReflector: getTelephonyProperty is called
03-17 07:10:52.634  4932  4932 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-17 07:10:52.634  4932  4932 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-17 07:10:52.634  4932  4932 D Mms/DownloadManager: auto download without roaming -> true
03-17 07:10:52.634  4932  4932 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
03-17 07:10:52.634  4932  4932 D Mms/MethodReflector: getSubId is called
,03-17 07:10:52.634  4932  4932 D Mms/MethodReflector: getDefaultSmsSubId is called
03-17 07:10:52.634  4932  4932 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
03-17 07:10:52.634  4932  4932 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
03-17 07:10:52.644  4932  5024 D Mms/DraftCache: [end]    rebuildCache consume time = 10.859896
,03-17 07:10:52.644  4932  4932 D Mms/MethodReflector: getTelephonyProperty is called
03-17 07:10:52.644  4932  4932 D Mms/DownloadManager: roaming -> false (slotId = 1)
03-17 07:10:52.644  4932  4932 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
03-17 07:10:52.644  4932  4932 D Mms/DownloadManager: auto download without roaming -> true
03-17 07:10:52.644  4932  4932 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
03-17 07:10:52.644  4932  4932 D Mms/DownloadManager: auto download during roaming secondary -> false
03-17 07:10:52.644  4932  4932 D Mms/DownloadManager: mAutoDownload ------> true
,03-17 07:10:52.644  1020  1137 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
03-17 07:10:52.644  1020  1137 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,03-17 07:10:52.644  1020  1137 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,03-17 07:10:52.644  5006  5006 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
03-17 07:10:52.644  1020  1044 W libprocessgroup: failed to open /acct/uid_10069/pid_3888/cgroup.procs: No such file or directory
,03-17 07:10:52.644  2076  2816 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,03-17 07:10:52.644  5006  5006 D elm:15183: ELMEngine.ELMEngine( context ).
,03-17 07:10:52.654  5006  5006 D elm:15183: MDMBridge.setEnterpriseBridge()
,03-17 07:10:52.654  1187  1713 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,03-17 07:10:52.654  2076  2816 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,03-17 07:10:52.654  1020  2880 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,03-17 07:10:52.654  1020  2880 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,03-17 07:10:52.654  1020  2880 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:52.654  1020  2880 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:52.654  1020  2880 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-17 07:10:52.654  1187  1713 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,03-17 07:10:52.654  5006  5006 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,03-17 07:10:52.654  1020  1307 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,03-17 07:10:52.664  1020  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:52.664  1020  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:52.664  1020  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:52.664  1020  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:52.664  5006  5006 D elm:15183: ElmAgentService : onCreate()
,03-17 07:10:52.664  5006  5025 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,03-17 07:10:52.674  5006  5025 D elm:15183: ELMAgentService.listeningToTimeDateChanges( context, intent ).
,03-17 07:10:52.674  5027  5027 I libpersona: KNOX_SDCARD checking this for 10134
03-17 07:10:52.674  5006  5006 D elm:15183: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
03-17 07:10:52.674  5027  5027 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:52.674  5027  5027 E Zygote  : MountEmulatedStorage()
03-17 07:10:52.674  5027  5027 E Zygote  : v2
,03-17 07:10:52.674  5027  5027 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:52.674  5027  5027 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 07:10:52.674  5027  5027 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,03-17 07:10:52.684  5006  5006 D elm:15183: ModuleBase.ModifySetAlarm()
03-17 07:10:52.684  1020  1307 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=5027 uid=10134 gids={50134, 9997} abi=armeabi-v7a
03-17 07:10:52.684  5006  5006 D elm:15183: MDMBridge.getInstance()
03-17 07:10:52.684  5006  5006 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
03-17 07:10:52.684  5006  5006 D elm:15183: ElmAgentService : onDestroy().
,03-17 07:10:52.694  1020  1516 I ActivityManager: Killing 4593:com.sec.pcw.device/1000 (adj 15): empty #31,
,03-17 07:10:52.694  4932  4932 D ComposerPerformance: 1458195052706 ms / [DONE] Composer constructor
,03-17 07:10:52.694  4932  5040 D Mms/Conversation: [start]    init() consume time = 56.645677
,03-17 07:10:52.694  4932  4932 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,03-17 07:10:52.694  4932  4932 I Mms/ReservationManager: ReservationManager()
03-17 07:10:52.694  4932  4932 I Mms/ReservationManager: resetAfterConnected()
,03-17 07:10:52.704  1470  1774 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807,
03-17 07:10:52.704  1470  1800 D TP/MmsSmsProvider: query,matched:7, calling pid = 4932
03-17 07:10:52.704  1470  1774 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-17 07:10:52.704  1470  1774 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,03-17 07:10:52.704  5027  5027 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:52.704  5027  5027 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:52.714  1470  1800 D TP/MmsSmsProvider: match 7:Elapsed time : 5.184 ms,
,03-17 07:10:52.714  1470  1774 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,03-17 07:10:52.714  1470  1774 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 07:10:52.714  1470  1774 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 07:10:52.714  1470  1774 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 07:10:52.714  1470  1774 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 07:10:52.714  1470  1774 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 07:10:52.714  1470  1774 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 07:10:52.714  4932  4932 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,03-17 07:10:52.724  4932  4932 D Mms/MmsApp: [end]    onCreate() consume time = 26.683073
,03-17 07:10:52.724  1470  1774 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
03-17 07:10:52.724  1470  1774 D TP/MmsSmsProvider: need read changed broadcast:false
03-17 07:10:52.724  4932  5040 D Mms/Conversation: [end]    init consume time = 3.647864
03-17 07:10:52.724  5027  5027 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 07:10:52.724  5027  5027 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,03-17 07:10:52.724  4932  4932 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
03-17 07:10:52.724  4932  4932 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
03-17 07:10:52.724  1020  2883 I ActivityManager: Killing 4041:com.samsung.android.app.galaxyfinder:tagService/u0a32 (adj 15): empty #31
,03-17 07:10:52.734  4932  4932 D Mms/MethodReflector: getSubId is called
03-17 07:10:52.734  4932  5040 D Mms/MessagingNotification: [start]    init() consume time = 4.01948
03-17 07:10:52.734  4932  4932 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-17 07:10:52.734  4932  4932 D Mms/MethodReflector: getTelephonyProperty is called
03-17 07:10:52.734  4932  4932 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-17 07:10:52.734  4932  4932 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-17 07:10:52.734  4932  4932 D Mms/DownloadManager: auto download without roaming -> true
03-17 07:10:52.734  4932  4932 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
03-17 07:10:52.734  4932  4932 D Mms/DownloadManager: mAutoDownload ------> true
,03-17 07:10:52.734  4932  5040 D Mms/MessagingNotification: [end]    init consume time = 3.953958
,03-17 07:10:52.734  4932  5044 D Mms/Synchronizer: [start]    doSync consume time = 4.754271
,03-17 07:10:52.734  1470  2140 D TP/MmsSmsProvider: query,matched:0, calling pid = 4932
03-17 07:10:52.744  1470  2140 V TP/MmsSmsProvider: getSimpleConversations entered.
03-17 07:10:52.744  1470  2140 D TP/MmsSmsProvider: match 0:Elapsed time : 1.466 ms
03-17 07:10:52.744  1470  1800 D TP/MmsSmsProvider: update, matched:300, calling pid = 4932
03-17 07:10:52.744  1470  1800 V TP/MmsSmsProvider: syncDBData start
,03-17 07:10:52.744  1470  1800 V TP/MmsSmsProvider: syncDBData sms end
,03-17 07:10:52.744  1470  1800 V TP/MmsSmsProvider: syncDBData mms end
,03-17 07:10:52.744  1470  1800 V TP/MmsSmsProvider: syncDBData end
,03-17 07:10:52.744  4932  5043 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 0.275365
,03-17 07:10:52.744  4932  5044 D Mms/Synchronizer: [end]    doSync consume time = 6.438385
,03-17 07:10:52.754  1020  1130 I splitIntent: Queue : backgroundsplit_0 intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-17 07:10:52.754  1020  1130 I ActivityManager: Killing 4161:com.sec.android.soagent/u0a34 (adj 15): empty #31
,03-17 07:10:52.764  1470  1774 D TP/MmsSmsProvider: query,matched:400, calling pid = 4932
,03-17 07:10:52.764  1020  1045 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:52.764  1020  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:52.764  1020  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-17 07:10:52.774  4932  5040 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,03-17 07:10:52.774  1020  2931 D ActivityManager: startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
03-17 07:10:52.774  1020  2931 D ActivityManager: retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,03-17 07:10:52.774  1020  2931 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:52.774  1020  2931 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:52.774  1020  2931 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-17 07:10:52.774  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:52.774  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:52.774  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:52.784  4932  5043 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 36.241771
,03-17 07:10:52.784  1470  1702 D TP/SmsProvider: query,matched:26, calling pid = 4932
,03-17 07:10:52.784  1470  1702 D TP/SmsProvider: match 26:Elapsed time : 1.495 ms
,03-17 07:10:52.784   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 07:10:52.794  1470  1800 D TP/MmsSmsProvider: query,matched:6, calling pid = 4932
,03-17 07:10:52.804  1470  1800 D TP/MmsSmsProvider: match 6:Elapsed time : 3.327 ms
,03-17 07:10:52.804  1020  1307 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,03-17 07:10:52.804  1020  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:52.804  1020  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:52.804  1020  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:52.804  1020  1307 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:52.814  5046  5046 E Zygote  : MountEmulatedStorage()
03-17 07:10:52.814  5046  5046 I libpersona: KNOX_SDCARD checking this for 1000
03-17 07:10:52.814  5046  5046 E Zygote  : v2
03-17 07:10:52.814  5046  5046 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:52.814  5046  5046 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:52.824  5046  5046 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 07:10:52.824  4932  5002 D Mms/ArtClassLoader: init [DONE] art
,03-17 07:10:52.824  5046  5046 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:52.824  1020  1307 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5046 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 07:10:52.844  1020  1032 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,03-17 07:10:52.844  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:52.844  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:52.844  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:52.844  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:52.854  5046  5046 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:52.854  5046  5046 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:52.854  1637  1711 I art     : Explicit concurrent mark sweep GC freed 3717(151KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 789us total 27.330ms
,03-17 07:10:52.864  5061  5061 E Zygote  : MountEmulatedStorage()
03-17 07:10:52.864  5061  5061 I libpersona: KNOX_SDCARD checking this for 10025
,03-17 07:10:52.864  5061  5061 E Zygote  : v2
03-17 07:10:52.864  5061  5061 I libpersona: KNOX_SDCARD not a persona
03-17 07:10:52.864  5061  5061 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:52.864  1020  1032 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5061 uid=10025 gids={50025, 9997} abi=armeabi-v7a
03-17 07:10:52.864  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_4593/cgroup.procs: No such file or directory
,03-17 07:10:52.864  5061  5061 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:52.864  1020  1044 W libprocessgroup: failed to open /acct/uid_10034/pid_4161/cgroup.procs: No such file or directory
03-17 07:10:52.864  5061  5061 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:52.874  1020  1044 W libprocessgroup: failed to open /acct/uid_10032/pid_4041/cgroup.procs: No such file or directory
,03-17 07:10:52.884  5061  5061 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:52.884  5061  5061 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:52.894  1020  1137 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,03-17 07:10:52.904  5061  5061 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 07:10:52.904  5046  5046 E MTPRx   : In MtpReceiverandroid.hardware.usb.action.USB_STATE
,03-17 07:10:52.924  3245  3245 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-17 07:10:52.924  1020  1044 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,03-17 07:10:52.924  1020  1516 D SecContentProvider2: uri = 14 selection = getSealedState
03-17 07:10:52.924  1020  1516 D SecContentProvider2: mCursor = null
,03-17 07:10:52.934  4609  4609 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-17 07:10:52.934  1020  2883 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-17 07:10:52.934  1020  2883 D SecContentProvider2: mCursor = null
,03-17 07:10:52.934  3196  3196 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-17 07:10:52.934  3196  3196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 07:10:52.934  3196  3196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 07:10:52.934  3196  3196 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 07:10:52.934  3196  3196 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 07:10:52.934  3196  3196 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 07:10:52.934  3196  3196 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 07:10:52.934  3196  3196 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-17 07:10:52.934  3196  3196 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-17 07:10:52.944  5046  5046 V MTPRx   : sealedState: false
03-17 07:10:52.944  5046  5046 V MTPRx   : sealedUsbMassStorageState: false
03-17 07:10:52.944  5046  5046 E MTPRx   : check value of boot_completed is1
03-17 07:10:52.944  5046  5046 E MTPRx   : check booting is completed_sys.boot_completed
,03-17 07:10:52.944  1020  2933 I ActivityManager: Killing 4624:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,03-17 07:10:52.944  5061  5061 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,03-17 07:10:52.944  5046  5046 E MTPRx   : Sd-Card path/storage/extSdCard
,03-17 07:10:52.954  5046  5046 E MTPRx   : Status for mount/Unmount :removed
03-17 07:10:52.954  5046  5046 E MTPRx   : SDcard is not available
,03-17 07:10:52.954  5046  5046 W MTPRx   : value of connected istrue
03-17 07:10:52.954  5046  5046 W MTPRx   : value of configured istrue
03-17 07:10:52.954  5046  5046 W MTPRx   : value of mtpEnabled istrue
03-17 07:10:52.954  5046  5046 W MTPRx   : value of ptpEnabled isfalse
,03-17 07:10:52.954  5046  5046 E MTPRx   : Received USB_STATE with sdCardLaunch = 0
,03-17 07:10:52.954  5046  5046 E MTPRx   : mFirstTime: false
,03-17 07:10:52.964  4932  5040 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,03-17 07:10:52.974  1020  1491 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,03-17 07:10:52.974  1020  1491 D SecContentProvider2: mCursor = null
,03-17 07:10:52.974  1020  1020 I ValidateNoPeople: mEvictionCount: 0
,03-17 07:10:52.974  4932  4932 D Mms/Contact: sContactsObserver.onChange(),selfUpdate=false
,03-17 07:10:52.984  4932  4932 D Mms/Contact: performUpdate:widgetCount=0
,03-17 07:10:52.984  5046  5046 D         : MTP: reading debug level property
,03-17 07:10:52.984  4932  5077 D Mms/ContactsCache: [start]    invalidate() consume time = 201.752083
03-17 07:10:52.984  4932  5077 D Mms/ContactsCache: [end]    invalidate() consume time = 0.123594
,03-17 07:10:52.984  5046  5046 E MTPJNIInterface: Getting CryptionKey from JAVA
03-17 07:10:52.984  5046  5046 E MTPRx   : currentUserId is 0
,03-17 07:10:52.994  5046  5046 E MTPRx   : Start observing USB_STATE_MATCH 
,03-17 07:10:52.994  5061  5061 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,03-17 07:10:52.994  5046  5046 E MTPRx   : cannot open file : /sys/class/android_usb/android0/bcdUSB
03-17 07:10:52.994  5046  5046 E MTPRx   : is_Privatemode is NOT 1
03-17 07:10:52.994  5061  5061 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,03-17 07:10:52.994  5061  5061 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,03-17 07:10:52.994  1020  1362 D SettingsProvider: name = boot_time_connected
,03-17 07:10:52.994  5061  5061 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,03-17 07:10:52.994  5061  5061 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,03-17 07:10:53.004  5061  5061 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,03-17 07:10:53.004  5061  5061 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,03-17 07:10:53.004  5046  5046 E MTPRx   : Sending NORMAL_BOOT to stack
03-17 07:10:53.004  5046  5046 E MTPJNIInterface: noti = 17
,03-17 07:10:53.004  5061  5061 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,03-17 07:10:53.004  5061  5061 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,03-17 07:10:53.004  5061  5061 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,03-17 07:10:53.004  1020  2934 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 07:10:53.004  5061  5061 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,03-17 07:10:53.004  5061  5061 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,03-17 07:10:53.014  5061  5061 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,03-17 07:10:53.014  1020  1307 D SecContentProvider: uri = 18 selection = isUsbMediaPlayerAvailable
,03-17 07:10:53.014  5046  5046 E MTPRx   : sending MTP_ICON_ENABLED to stack
,03-17 07:10:53.014  1020  2880 D ActivityManager: startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
03-17 07:10:53.014  1020  2880 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,03-17 07:10:53.014  1020  2880 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:53.014  1020  2880 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 07:10:53.014  1020  2880 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-17 07:10:53.014  1020  1130 D SettingsProvider: name = mtp_running_status
,03-17 07:10:53.024  1020  2933 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 07:10:53.024  5046  5046 E MTPRx   : else part ... so first time!!!
03-17 07:10:53.024  5046  5046 E MTPPlaObsrvr: inside setContext(),
03-17 07:10:53.024  5046  5046 E MTPPlaObsrvr:  inside createplafiles,
,03-17 07:10:53.024  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 07:10:53.024  5046  5046 E MTPPlaObsrvr: playlist count is0
,03-17 07:10:53.024  5046  5046 E MTPPlaObsrvr:  inside try branch createplafiles
,03-17 07:10:53.034  5046  5046 E MTPPlaObsrvr:  inside deleteing plas createplafiles
,03-17 07:10:53.034  5046  5046 E MTPPlaObsrvr: Inside registerContentObserver
,03-17 07:10:53.034  5046  5046 E MtpAdbObserver: inside setContext()
03-17 07:10:53.034  5046  5046 E MtpAdbObserver: Inside registerContentObserver
03-17 07:10:53.034  5046  5046 W Settings: Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,03-17 07:10:53.034  1020  2880 D ActivityManager: startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
03-17 07:10:53.034  1020  2880 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,03-17 07:10:53.034  1020  2880 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:53.034  1020  2880 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:53.034  1020  2880 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-17 07:10:53.034  1020  1130 D SettingsProvider: name = mtp_running_status
,03-17 07:10:53.034  1020  1033 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 07:10:53.044  5046  5046 E MtpService: onCreate.
,03-17 07:10:53.044  1020  2933 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,03-17 07:10:53.044  1020  2933 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,03-17 07:10:53.044  1020  2933 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:53.044  1020  2933 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:53.044  1020  2933 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 07:10:53.054  1238  1238 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
03-17 07:10:53.054  1020  1307 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:53.054  1020  1307 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 07:10:53.054  1020  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,03-17 07:10:53.054  5046  5080 V MtpMediaDBManager: inside deleteAllDB
,03-17 07:10:53.054  1020  1307 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:53.054  1020  1307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-17 07:10:53.054  1020  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,03-17 07:10:53.054  1020  1044 W libprocessgroup: failed to open /acct/uid_10159/pid_4624/cgroup.procs: No such file or directory
,03-17 07:10:53.064  5046  5046 E MtpService: < MTP > Registering BroadCast receiver :::::
,03-17 07:10:53.064  1020  1307 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:53.064  1020  1307 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-17 07:10:53.064  1020  1307 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,03-17 07:10:53.064  5046  5046 E MtpService: < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,03-17 07:10:53.064  1879  1879 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,03-17 07:10:53.074  5046  5046 E MtpService: < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,03-17 07:10:53.074  5046  5046 E MtpService: onStartCommand.
,03-17 07:10:53.074  5046  5046 W MTPRx   : calling native method
,03-17 07:10:53.074  5046  5046 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::
03-17 07:10:53.074  5046  5081 E MtpService: handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
03-17 07:10:53.074  1020  2883 W ActivityManager: userId = 0, bbcId = -10000
03-17 07:10:53.074  1020  2883 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-17 07:10:53.074  1020  2883 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,03-17 07:10:53.074  1020  2880 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 07:10:53.084  1020  2880 W ActivityManager: userId = 0, bbcId = -10000
,03-17 07:10:53.084  1020  2880 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 07:10:53.084  5046  5080 V MtpMediaDBManager: inside Thread updateDB
03-17 07:10:53.084  1020  2880 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 07:10:53.084  5046  5046 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::::
,03-17 07:10:53.084  5046  5046 E MTPJNIInterface: noti = 10
,03-17 07:10:53.084  5046  5046 E MtpService: onStartCommand.
,03-17 07:10:53.084  5046  5046 W MTPRx   : calling native method
,03-17 07:10:53.084  5046  5046 E MTPRx   : Checking the driver time out
,03-17 07:10:53.084  5046  5080 E MtpMediaDBManager: count : 27
,03-17 07:10:53.084  5046  5081 E MtpService: handleMessage. msg= { when=-2ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,03-17 07:10:53.094  5046  5046 E MTPJNIInterface: noti = 2
03-17 07:10:53.094  5046  5046 D         : deleting sockets before message queue initialization
,03-17 07:10:53.094  5046  5046 D         : event handler thread is created, so set the flag
,03-17 07:10:53.094  5046  5046 E MTPRx   : called native method
03-17 07:10:53.094  5046  5046 E MTPJNIInterface: setting Media scanner status0
03-17 07:10:53.094  5046  5046 E MTPJNIInterface: After setting Media scanner status0
,03-17 07:10:53.094  5046  5046 W MTPRx   : notification from stack 1
,03-17 07:10:53.094  5046  5083 E         : Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
03-17 07:10:53.094  5046  5083 E MTPJNIInterface: Getting media scanner status0
,03-17 07:10:53.094  5046  5083 E MTPJNIInterface: DeviceName is A5-1
,03-17 07:10:53.104  5046  5080 W MtpMediaDBManager: sending db update complete noti to stack
,03-17 07:10:53.104  5046  5080 E MTPJNIInterface: noti = 29
,03-17 07:10:53.114  1311  1311 D BluetoothNotiBroadcastReceiver: onReceive
,03-17 07:10:53.114  5046  5083 E SQLiteLog: (5) database is locked
,03-17 07:10:53.114  1187  1187 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
03-17 07:10:53.114  1187  1187 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,03-17 07:10:53.114  1020  2883 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,03-17 07:10:53.114  1020  2883 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:53.114  1020  2883 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:53.114  1020  2883 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 07:10:53.114  1020  2883 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 07:10:53.134  5085  5085 E Zygote  : MountEmulatedStorage()
,03-17 07:10:53.134  5085  5085 E Zygote  : v2
03-17 07:10:53.134  5085  5085 I libpersona: KNOX_SDCARD checking this for 10003
03-17 07:10:53.134  5085  5085 I libpersona: KNOX_SDCARD not a persona
,03-17 07:10:53.134  5085  5085 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 07:10:53.134  5085  5085 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 07:10:53.134  1020  2883 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5085 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
03-17 07:10:53.134  5085  5085 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 07:10:53.144  5046  5083 E MTPJNIInterface: Status for mount/Unmount :removed
03-17 07:10:53.144  5046  5083 E MTPJNIInterface: SDcard is not available
,03-17 07:10:53.154  5085  5085 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 07:10:53.164  5085  5085 D ActivityThread: Added TimaKeyStore provider
,03-17 07:10:53.164  5046  5083 E         : lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,03-17 07:10:53.164  5046  5083 E         : [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,03-17 07:10:53.174  5046  5083 E MTPJNIInterface: Status for mount/Unmount :removed
03-17 07:10:53.174  5046  5083 E MTPJNIInterface: SDcard is not available
03-17 07:10:53.174  5046  5083 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 07:10:53.174  5046  5083 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
03-17 07:10:53.174  5046  5083 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 07:10:53.174  5046  5083 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-17 07:10:53.174  5046  5083 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 07:10:53.174  5046  5083 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-17 07:10:53.174  5046  5083 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 07:10:53.174  5046  5083 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
,03-17 07:10:53.174  5046  5046 W MTPRx   : notification from stack 2
,03-17 07:10:53.174  5046  5100 D         : [mtp_init_device] Library open with 32 bits.
03-17 07:10:53.184  5046  5100 D         : [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,03-17 07:10:53.184  5046  5100 E         : [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
03-17 07:10:53.184  5046  5100 D         : [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
03-17 07:10:53.184  5046  5100 E         :  [sua_support_present:1287] returning false 
03-17 07:10:53.184  5046  5100 D         : [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,03-17 07:10:53.184  5085  5085 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()

```
