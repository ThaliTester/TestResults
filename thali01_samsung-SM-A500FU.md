#### Test 630369953a3bebd_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
03-16 11:17:14.595  3135  3135 E Zygote  : MountEmulatedStorage()
03-16 11:17:14.595  3135  3135 E Zygote  : v2
03-16 11:17:14.595  3135  3135 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
--------- beginning of system
03-16 11:17:14.595  3135  3135 I libpersona: KNOX_SDCARD checking this for 1000
03-16 11:17:14.595  3135  3135 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:14.605  3135  3135 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:14.605  3135  3135 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 11:17:14.605  2978  3038 I KnoxUsageLogPro: savePreference: key = previous_elapsed_time value = 36358
03-16 11:17:14.605  1473  1741 I art     : Explicit concurrent mark sweep GC freed 40168(2MB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 7MB/13MB, paused 1.079ms total 73.754ms
03-16 11:17:14.605  1018  1345 I ActivityManager: Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=3135 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-16 11:17:14.605  1018  1345 I ActivityManager: Killing 1636:com.google.android.partnersetup/u0a15 (adj 15): empty #31
03-16 11:17:14.605  1018  1031 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
03-16 11:17:14.605  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.wifi.WifiCredService; callingUser = 0; userId(target) = -2
03-16 11:17:14.615  1473  1741 D TP/SmsProvider: match 51:Elapsed time : 30.334 ms
03-16 11:17:14.615  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:14.615  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:14.615  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
03-16 11:17:14.625  1314  1314 I WifiCredService: onCreate
03-16 11:17:14.625  3099  3099 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
03-16 11:17:14.635  3135  3135 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 11:17:14.635  3135  3135 D ActivityThread: Added TimaKeyStore provider
03-16 11:17:14.645  3099  3099 D DSM     : [Lines:107] Normal booted
03-16 11:17:14.645  3099  3099 D DSM     : [Lines:114] Boot completed
03-16 11:17:14.645  1018  1574 D SettingsProvider: name = next_alarm_formatted
03-16 11:17:14.645  1018  1574 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 11:17:14.645  1018  1574 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 11:17:14.645  1018  1574 D SettingsProvider: selectionArgs: false
03-16 11:17:14.645  1018  1574 D SettingsProvider: selectionArgs: 10085
03-16 11:17:14.645  1018  1574 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 11:17:14.645  1018  1574 D SettingsProvider: ret = -1
03-16 11:17:14.655  2335  3036 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
03-16 11:17:14.655  1314  1314 D WifiTimerReceiver: action: android.intent.action.BOOT_COMPLETED
03-16 11:17:14.655  1314  1314 D WifiTimerReceiver: extra: Bundle[mParcelledData.dataSize=84]
03-16 11:17:14.655  1314  1314 D MY_TAG  : Action boot completed received
03-16 11:17:14.655  2335  3090 D Mms/SmsReceiver: unregisterForServiceStateChanges, already unregistered
03-16 11:17:14.655  2335  3090 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-16 11:17:14.655   297   297 E USB_UICC: Timeout! No signal received. Retry num = 30
03-16 11:17:14.655  1018  1574 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10085
03-16 11:17:14.665  1018  1574 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.factorykeystring, hostingType: broadcast
03-16 11:17:14.675  2335  3090 D Mms/TelephonyPermission: isDefault true
03-16 11:17:14.675  1314  1314 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
03-16 11:17:14.675  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:14.675  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:14.675  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:14.675  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:14.675  1018  1132 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
03-16 11:17:14.675  1018  1132 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-16 11:17:14.675  1018  1132 E WifiNative-wlan0: invaild command id : 215
03-16 11:17:14.695  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 11:17:14.695   315   315 I ServiceManager: Waiting for service AtCmdFwd...
03-16 11:17:14.695  3155  3155 E Zygote  : MountEmulatedStorage()
03-16 11:17:14.695  3155  3155 I libpersona: KNOX_SDCARD checking this for 1000
03-16 11:17:14.695  3155  3155 E Zygote  : v2
03-16 11:17:14.695  3155  3155 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:14.695  3155  3155 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-16 11:17:14.705  3155  3155 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:14.705  1241  2993 V MediaScanner: processDirectory :  /system/media
03-16 11:17:14.705  1018  1574 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3155 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-16 11:17:14.705  1018  1574 I ActivityManager: Killing 2314:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
03-16 11:17:14.705  3155  3155 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 11:17:14.725   306   306 I art     : Explicit concurrent mark sweep GC freed 8746(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 660us total 24.887ms
03-16 11:17:14.735  3155  3155 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 11:17:14.735  3155  3155 D ActivityThread: Added TimaKeyStore provider
03-16 11:17:14.745  1473  1484 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2335
03-16 11:17:14.745   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 20.068ms
03-16 11:17:14.755   297   297 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-16 11:17:14.755   297   297 E USB_UICC: usb_uicc_init_qmi failed ! 
03-16 11:17:14.755   297   297 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
03-16 11:17:14.755   297   297 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
03-16 11:17:14.755  1018  1574 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
03-16 11:17:14.755  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:14.755  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:14.755  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:14.755  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:14.785   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 588us total 28.992ms
03-16 11:17:14.815  3177  3177 E Zygote  : MountEmulatedStorage()
03-16 11:17:14.815  3177  3177 I libpersona: KNOX_SDCARD checking this for 10160
03-16 11:17:14.815  3177  3177 E Zygote  : v2
03-16 11:17:14.815  3177  3177 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:14.815  3177  3177 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-16 11:17:14.815  3177  3177 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:14.815  3177  3177 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 11:17:14.815  1018  1574 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3177 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
03-16 11:17:14.825  1018  1574 I ActivityManager: Killing 2352:com.sec.android.omc/1000 (adj 15): empty #31
03-16 11:17:14.835  1241  2993 V MediaScanner:  prescan time: 497ms (DB items: 141)
03-16 11:17:14.835  1241  2993 V MediaScanner:     scan time: 138ms (Caching mode: true), (makeEntry time: 125ms ~90%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-16 11:17:14.835  3047  3047 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 170.739ms
03-16 11:17:14.835  1241  2993 V MediaScanner: postscan time: 1ms (bulkDeleter : 0), (delete DeadThumbnail time : 1ms)
03-16 11:17:14.835  1241  2993 V MediaScanner:    total time: 636ms
03-16 11:17:14.835  1241  2993 V MediaScanner: checked files: 133  directories : 6  (I: 0, U: 0)
03-16 11:17:14.835  1018  1044 W libprocessgroup: failed to open /acct/uid_10015/pid_1636/cgroup.procs: No such file or directory
03-16 11:17:14.845  1241  2993 D MediaScanner: checkDefaultSounds
03-16 11:17:14.845  1241  2993 D MediaScanner: system alarm_alert  : Vwiurug_etwofi5wgg
03-16 11:17:14.845  3177  3177 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 11:17:14.845  3177  3177 D ActivityThread: Added TimaKeyStore provider
03-16 11:17:14.865  1314  1314 D NearbySettings: MountReceiver.onReceive - Create HandlerThread
03-16 11:17:14.865  1314  1314 D NearbySettings: MountReceiver.onReceive - Start HandlerThread
03-16 11:17:14.865  1314  1314 D NearbySettings: MountReceiver.onReceive - Create mPrefHandler
03-16 11:17:14.865  1576  1584 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
03-16 11:17:14.875  3155  3155 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-16 11:17:14.875  3177  3177 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-16 11:17:14.885  1314  1314 D NearbySettings: MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
03-16 11:17:14.885  1018  1030 D SettingsProvider: name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
03-16 11:17:14.885  1314  3192 V NearbySettings: MountReceiver.mPrefHandler - 7002
03-16 11:17:14.895  1018  3034 I ActivityManager: Killing 2368:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
03-16 11:17:14.895  1314  1314 I NearbySettings: MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
03-16 11:17:14.895  1314  1314 I NearbySettings: MountReceiver.onReceive - Internal Path
03-16 11:17:14.895  1241  2993 D MediaScanner: OK. alarm_alert is already exist in setting DB.
03-16 11:17:14.905  1241  2993 D MediaScanner: system notification_sound  : K_Oprkltf5wgg
03-16 11:17:14.925  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-16 11:17:14.925  1576  1591 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-16 11:17:14.925  1576  1591 D BadgeProvider: sendNotify, [notify] : null
03-16 11:17:14.925  1576  1591 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-16 11:17:14.925  1576  1591 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-16 11:17:14.925  1576  1591 D BadgeProvider: update, [UpdateCount] : 1
03-16 11:17:14.935  2335  3036 D Mms/MessagingNotification: setBadgeCount(), count=0
03-16 11:17:14.935  1491  1491 D Launcher.Model: reloadBadges entered.
03-16 11:17:14.935  1473  1486 D TP/MmsSmsProvider: query,matched:200, calling pid = 2335
03-16 11:17:14.945  1473  1486 D TP/MmsSmsProvider: match 200:Elapsed time : 2.792 ms
03-16 11:17:14.945  1241  2993 D MediaScanner: OK. notification_sound is already exist in setting DB.
03-16 11:17:14.965  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2314/cgroup.procs: No such file or directory
03-16 11:17:14.965  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2352/cgroup.procs: No such file or directory
03-16 11:17:14.975  2335  3036 D Mms/MessagingNotification: remove alarm
03-16 11:17:14.975  3155  3155 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-16 11:17:14.975  3170  3170 D AndroidRuntime: 
03-16 11:17:14.975  3170  3170 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-16 11:17:14.975  1473  1741 D TP/SmsProvider: query,matched:0, calling pid = 2335
03-16 11:17:14.975  1473  1741 D TP/SmsProvider: match 0:Elapsed time : 1.841 ms
03-16 11:17:14.975  3170  3170 D AndroidRuntime: CheckJNI is OFF
03-16 11:17:14.975  3170  3170 D AndroidRuntime: readGMSProperty: start
03-16 11:17:14.975  3170  3170 D AndroidRuntime: readGMSProperty: already setted!!
03-16 11:17:14.975  3170  3170 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-16 11:17:14.975  3170  3170 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-16 11:17:14.975  3170  3170 D AndroidRuntime: readGMSProperty: end
03-16 11:17:14.975  3170  3170 D AndroidRuntime: addProductProperty: start
03-16 11:17:14.985  1241  2993 D MediaScanner: system ringtone  : Wmfi_lpf_pwirywu5wgg
03-16 11:17:14.985  1018  1573 D SettingsProvider: name = personal_mode_enabled
03-16 11:17:14.985  2335  3036 D Mms/MessagingNotification: [end]    nonBlockingUpdateMessageIndicator() consume time = 546.489323
03-16 11:17:14.985  1473  1486 D TP/SmsProvider: query,matched:0, calling pid = 2335
03-16 11:17:14.985  1241  2993 D MediaScanner: OK. ringtone is already exist in setting DB.
03-16 11:17:14.985  1473  1486 D TP/SmsProvider: match 0:Elapsed time : 1.333 ms
03-16 11:17:14.995  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
03-16 11:17:14.995  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
03-16 11:17:14.995  3155  3155 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
03-16 11:17:15.015  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
03-16 11:17:15.025  1473  1473 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-16 11:17:15.025  1473  1473 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-16 11:17:15.025  1473  1473 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 11:17:15.025  1473  1473 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 11:17:15.025  1473  1473 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 11:17:15.025  1473  1473 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-16 11:17:15.035  1241  2993 D MediaScannerService: !@done scanning volume internal
03-16 11:17:15.035  2666  2666 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2666) action= = android.intent.action.MEDIA_SCANNER_FINISHED
03-16 11:17:15.035  2666  2666 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2666) ACTION_MEDIA_SCANNER_FINISHED = /system/media
03-16 11:17:15.035  2666  2666 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2666) ACTION_MEDIA_SCANNER_FINISHED = Ignored
03-16 11:17:15.035  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-16 11:17:15.035  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-16 11:17:15.035  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-16 11:17:15.035  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-16 11:17:15.035  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-16 11:17:15.035  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-16 11:17:15.035  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-16 11:17:15.035  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-16 11:17:15.035  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
03-16 11:17:15.035  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
03-16 11:17:15.035  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-16 11:17:15.035  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
03-16 11:17:15.035  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
03-16 11:17:15.035  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
03-16 11:17:15.045  1018  1044 W libprocessgroup: failed to open /acct/uid_10131/pid_2368/cgroup.procs: No such file or directory
03-16 11:17:15.035  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
03-16 11:17:15.035  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-16 11:17:15.035  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
03-16 11:17:15.035  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
03-16 11:17:15.035  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
03-16 11:17:15.035  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
03-16 11:17:15.035  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
03-16 11:17:15.045  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
03-16 11:17:15.045  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
03-16 11:17:15.045  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
03-16 11:17:15.045  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
03-16 11:17:15.045  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
03-16 11:17:15.045  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
03-16 11:17:15.045  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
03-16 11:17:15.045  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
03-16 11:17:15.045  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
03-16 11:17:15.045  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
03-16 11:17:15.045  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
03-16 11:17:15.045  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
03-16 11:17:15.045  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
03-16 11:17:15.045  3155  3155 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
03-16 11:17:15.055  1241  2993 D MediaScannerService: !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private]
03-16 11:17:15.055  2335  3194 D Mms/MessagingNotification: updateAllHistoryAsRead()
03-16 11:17:15.055  1473  1692 D TP/SmsProvider: query,matched:51, calling pid = 2335
03-16 11:17:15.065  1473  1692 D TP/SmsProvider: match 51:Elapsed time : 6.994 ms
03-16 11:17:15.065  3155  3155 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
03-16 11:17:15.065  1018  1573 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
03-16 11:17:15.065  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:15.065  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:15.065  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:15.065  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:15.085  1241  2993 D MediaProvider: savePlaylistTableInBulkDeleter started
03-16 11:17:15.085  1241  2993 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
03-16 11:17:15.085  3203  3203 E Zygote  : MountEmulatedStorage()
03-16 11:17:15.095  3203  3203 E Zygote  : v2
03-16 11:17:15.095  3203  3203 I libpersona: KNOX_SDCARD checking this for 1000
03-16 11:17:15.095  3203  3203 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:15.095  3203  3203 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-16 11:17:15.095  3203  3203 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:15.095  1018  1573 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3203 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-16 11:17:15.095  3203  3203 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 11:17:15.095  1018  1573 I ActivityManager: Killing 2398:com.sec.tcpdumpservice/1000 (adj 15): empty #31
03-16 11:17:15.105  1241  2993 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
03-16 11:17:15.105  1018  1366 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-16 11:17:15.105  1018  1366 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
03-16 11:17:15.105  1018  1366 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:15.105  1018  1366 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:15.105  1018  1366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 11:17:15.115  1241  2993 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-16 11:17:15.115  1241  2993 D MediaProvider: savePlaylistTableInBulkDeleter started
03-16 11:17:15.115  1241  2993 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
03-16 11:17:15.115  1241  2993 D MediaProvider: savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
03-16 11:17:15.125  3203  3203 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 11:17:15.125  1241  2993 D MediaProvider: savePlaylistTableInBulkDeleter finished
03-16 11:17:15.125  3170  3170 E AffinityControl: AffinityControl: registerfunction enter
03-16 11:17:15.135  1314  1314 I SmartcardBootCompleteReceiver: SmartcardBootCompleteReceiver - onReceive() 
03-16 11:17:15.135  1314  1314 I SmartcardBootCompleteReceiver: Received intent with action - android.intent.action.BOOT_COMPLETED
03-16 11:17:15.145  3203  3203 D ActivityThread: Added TimaKeyStore provider
03-16 11:17:15.145  3177  3177 D [0]UMC:UMCContentProvider: @onCreate
03-16 11:17:15.155  1314  1314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
03-16 11:17:15.155  3170  3170 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-16 11:17:15.165  1018  1369 E PersonaManagerService: inState():  stateMachine is null !!
03-16 11:17:15.165  1018  1369 I PersonaManagerService: PersonaId don't exist
03-16 11:17:15.165  1018  1369 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-16 11:17:15.165  1018  1369 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 11:17:15.185  1018  1369 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-16 11:17:15.185  1018  1369 W ActivityManager: mDVFSHelper.acquire()
03-16 11:17:15.185  1018  1369 D FocusedStackFrame: Set to : 0
03-16 11:17:15.185  1491  1491 D Launcher.HomeView: onPause
03-16 11:17:15.195  1018  1050 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-16 11:17:15.195  1018  1050 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-16 11:17:15.195  1491  1491 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-16 11:17:15.195  1018  1369 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-16 11:17:15.195  1018  1369 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 11:17:15.195  1018  1369 D InputDispatcher: Focused application set to: xxxx
03-16 11:17:15.195  1018  1369 D InputDispatcher: Focus left window: 1491
03-16 11:17:15.205  3170  3170 D AndroidRuntime: Shutting down VM
03-16 11:17:15.205  1018  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-16 11:17:15.205  1018  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-16 11:17:15.215   258   258 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-16 11:17:15.215  3177  3177 D [0]UMC:Core: onCreate(): 
03-16 11:17:15.215  3177  3177 D [0]UMC:Core: @isManagedProfileUser
03-16 11:17:15.215  3177  3177 D [0]UMC:Core: userId: 0
03-16 11:17:15.215  3177  3177 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
03-16 11:17:15.215  3177  3177 D [0]UMC:Core: userInfo.isManagedProfile() : false
03-16 11:17:15.235  1018  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 11:17:15.235  1018  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
03-16 11:17:15.235  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2398/cgroup.procs: No such file or directory
03-16 11:17:15.235  3177  3177 D [0]UMC:DeviceInfo: USA==US==
03-16 11:17:15.325  1018  3034 I art     : Explicit concurrent mark sweep GC freed 138289(7MB) AllocSpace objects, 4(1813KB) LOS objects, 33% free, 26MB/39MB, paused 2.802ms total 177.797ms
03-16 11:17:15.335  1018  1490 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.colorblind, hostingType: broadcast
03-16 11:17:15.335   335   335 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
03-16 11:17:15.335  1241  2993 D MediaScanner: Prescan. DB items number : 27 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
03-16 11:17:15.335  1314  1314 I SmartcardBootCompleteReceiver: Broadcast sent with current lockscreen type
03-16 11:17:15.335  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:15.335  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:15.335  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:15.335  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:15.345  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-16 11:17:15.345  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-16 11:17:15.345  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 11:17:15.345  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 11:17:15.345  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 11:17:15.345  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 11:17:15.355  3225  3225 E Zygote  : MountEmulatedStorage()
03-16 11:17:15.355  3225  3225 E Zygote  : v2
03-16 11:17:15.355  3225  3225 I libpersona: KNOX_SDCARD checking this for 1000
03-16 11:17:15.355  3225  3225 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:15.365  3225  3225 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-16 11:17:15.365  1018  1490 I ActivityManager: Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3225 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-16 11:17:15.365  3225  3225 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:15.365  3225  3225 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 11:17:15.385  2335  3090 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
03-16 11:17:15.385  3014  3082 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
03-16 11:17:15.385  3014  3082 I SecureStorage: [INFO]: SPID(0x00000002)Skip using SecureStorageExceptionJNI
03-16 11:17:15.385  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:15.385  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:15.385  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:15.385  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:15.385  1018  1098 V AlarmManager: waitForAlarm result :8
03-16 11:17:15.395  1241  2993 V MediaScanner: processDirectory :  /storage/emulated/0
03-16 11:17:15.395  1241  2993 D MediaScanner: Skipping:
03-16 11:17:15.395  1241  2993 D MediaScanner: 7klwibgf7fvntblfd7(75ebcf7
03-16 11:17:15.395  1241  2993 D MediaScanner: Skipping:
03-16 11:17:15.395  1241  2993 D MediaScanner: 7klwibgf7fvntblfd7(7Budiwrd7dblb7
03-16 11:17:15.395  3239  3239 E Zygote  : MountEmulatedStorage()
03-16 11:17:15.395  3239  3239 I libpersona: KNOX_SDCARD checking this for 10155
03-16 11:17:15.395  3239  3239 E Zygote  : v2
03-16 11:17:15.395  3239  3239 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:15.405  3239  3239 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-16 11:17:15.405  3239  3239 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:15.405  3239  3239 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-16 11:17:15.405  1018  1345 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3239 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-16 11:17:15.415  1241  2993 V MediaScanner: processDirectory :  /storage/extSdCard
03-16 11:17:15.415  1241  2993 W MediaScanner: Error opening directory, reason : Permission denied.
03-16 11:17:15.415  1241  2993 W MediaScanner: 7klwibgf7fxlKdCbid7
03-16 11:17:15.415  1018  1098 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-16 11:17:15.415  3170  3170 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-16 11:17:15.425  3225  3225 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:15.425  3225  3225 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:15.435  1491  1491 V ActivityThread: updateVisibility : ActivityRecord{896c12d token=android.os.BinderProxy@3ad601d5 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,03-16 11:17:15.445  3239  3239 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 11:17:15.445  1241  2993 V MediaScanner:  prescan time: 266ms (DB items: 27)
03-16 11:17:15.445  3239  3239 D ActivityThread: Added TimaKeyStore provider
03-16 11:17:15.445  1241  2993 V MediaScanner:     scan time: 26ms (Caching mode: true), (makeEntry time: 14ms ~53%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
03-16 11:17:15.445  1241  2993 V MediaScanner: postscan time: 29ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
03-16 11:17:15.445  1241  2993 V MediaScanner:    total time: 321ms
03-16 11:17:15.445  1241  2993 V MediaScanner: checked files: 10  directories : 17  (I: 0, U: 0)
,03-16 11:17:15.445  1018  1030 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-16 11:17:15.445  1018  1030 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-16 11:17:15.445  1018  1030 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-16 11:17:15.455  3177  3177 D USER_AGENT: UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,03-16 11:17:15.465  1018  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-16 11:17:15.465  1491  1491 D Launcher.HomeView: onStop
03-16 11:17:15.465  1576  1591 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,03-16 11:17:15.465  1018  1030 D PersonaManager: isKioskContainerExistOnDevice
,03-16 11:17:15.465  1491  1491 V ActivityThread: updateVisibility : ActivityRecord{896c12d token=android.os.BinderProxy@3ad601d5 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
,03-16 11:17:15.465  1491  1491 D Launcher: onTrimMemory. Level: 20
,03-16 11:17:15.475  3225  3225 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
,03-16 11:17:15.485  1314  1314 D [SBeam] : SBeamEnabler.initPreferenceForSbeam : 0
,03-16 11:17:15.495  1241  2993 D MediaScannerService: !@done scanning volume external
,03-16 11:17:15.495  3177  3177 D [0]UMC:AdminManager: init - start
,03-16 11:17:15.505  1314  1314 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
,03-16 11:17:15.505  1314  1314 I SettingSearch/SearchIntentReceiver: search setting db init!!
,03-16 11:17:15.505  1314  1314 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,03-16 11:17:15.515  1314  3257 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
,03-16 11:17:15.535  3177  3177 D [0]UMC:AdminManager: loadAdmins
,03-16 11:17:15.535  1018  1018 D SensorService: [SO] activate (ident=0xb83694d8, enabled=0)
03-16 11:17:15.535  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-16 11:17:15.535  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-16 11:17:15.535  2666  2666 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2666) action= = android.intent.action.MEDIA_SCANNER_FINISHED
,03-16 11:17:15.535  2666  2666 D FactoryTestApp: [DummyFtClient$mBroadcastReceiver](2666) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
,03-16 11:17:15.535  2666  2666 D FactoryTestApp: [DummyFtClient$sendBootCompletedAndFinish](2666) ...
,03-16 11:17:15.545  1018  1018 D SensorManager: unregisterListener ::   
,03-16 11:17:15.545  1018  1018 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-16 11:17:15.545  2666  2666 D FactoryTestApp: [Support$Values.getString](2666) id=MODEL_COMMUNICATION_MODE, value=gsm
03-16 11:17:15.545  2666  2666 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2666) mConnectionMode = gsm
03-16 11:17:15.545  1018  1018 D SensorService: [SO] changed settle time [1]
03-16 11:17:15.545  1018  1018 D SensorService: [SO] setDelay [66000000]
03-16 11:17:15.545  1018  1018 D SensorService: [SO] activate (ident=0xb83034f0, enabled=1)
03-16 11:17:15.545  1018  1018 D SensorService: [SO] AR_init
03-16 11:17:15.545  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-16 11:17:15.545  2666  2666 D FactoryTestApp: [IPCWriterToSecPhoneService$ResponseWriter](2666) Create IPCWriterToSecPhoneService
03-16 11:17:15.545  2666  2666 I FactoryTestApp: [IPCWriterToSecPhoneService$connectToSecPhoneService](2666)  
,03-16 11:17:15.545  2666  2666 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,03-16 11:17:15.545  1018  1369 D ActivityManager: bindService callerProcessName:com.sec.factory, calleePkgName: com.sec.phone, action: null
,03-16 11:17:15.545  1018  1369 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,03-16 11:17:15.555  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:15.555  1018  1369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:15.555  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.factory, destAppInfo.processName = com.sec.phone
,03-16 11:17:15.555  1018  1018 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-16 11:17:15.555  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.wssyncmldm, hostingType: broadcast
,03-16 11:17:15.555  3177  3177 D [0]UMC:AdminManager: init - end
,03-16 11:17:15.555  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:15.555  3177  3177 D GSLBManager: migrateStoredUrlFromOldPref
03-16 11:17:15.555  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:15.555  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:15.555  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:15.565  2686  2776 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,03-16 11:17:15.575  3259  3259 E Zygote  : MountEmulatedStorage(),
03-16 11:17:15.575  3259  3259 E Zygote  : v2
03-16 11:17:15.575  3259  3259 I libpersona: KNOX_SDCARD checking this for 1000,
03-16 11:17:15.575  3259  3259 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:15.575  3259  3259 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:15.575  3259  3259 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:15.575  3259  3259 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:15.585  3177  3177 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
,03-16 11:17:15.585  3177  3177 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-16 11:17:15.585  1018  1031 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3259 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-16 11:17:15.585  3177  3177 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-16 11:17:15.585  3177  3177 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
03-16 11:17:15.585  3177  3177 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-16 11:17:15.585  3177  3177 D [0]UMC:UMCAdmin: isContainer : 0
03-16 11:17:15.585  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.google.android.configupdater, hostingType: broadcast
03-16 11:17:15.585  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:15.585  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:15.585  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:15.585  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:15.595  3203  3203 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-16 11:17:15.595  3259  3259 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:15.605  1018  1369 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
03-16 11:17:15.605  3259  3259 D ActivityThread: Added TimaKeyStore provider
03-16 11:17:15.605  3177  3177 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
03-16 11:17:15.605  3177  3177 D [0]UMC:UMCAdmin: isContainer : 0
,03-16 11:17:15.605  3177  3177 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
03-16 11:17:15.605  3275  3275 E Zygote  : MountEmulatedStorage()
03-16 11:17:15.605  3275  3275 E Zygote  : v2
03-16 11:17:15.605  3275  3275 I libpersona: KNOX_SDCARD checking this for 10086
03-16 11:17:15.605  3275  3275 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:15.605  3275  3275 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:15.605  1576  1591 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-16 11:17:15.605  1576  1591 D BadgeProvider: sendNotify, [notify] : null
,03-16 11:17:15.605  1576  1591 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-16 11:17:15.605  1576  1591 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-16 11:17:15.605  1576  1591 D BadgeProvider: update, [UpdateCount] : 1
03-16 11:17:15.605  3275  3275 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:15.605  3275  3275 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-16 11:17:15.605  1018  1031 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3275 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
03-16 11:17:15.615  1491  1491 D Launcher.Model: reloadBadges entered.
03-16 11:17:15.615  1018  1142 D ActivityManager: getContentProviderImpl callerProcessName:com.android.settings, calleePkgName: com.sec.providers.settingsearch
03-16 11:17:15.615  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:15.615  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:15.615  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:15.615  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:15.625  1018  1042 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-16 11:17:15.635  3275  3275 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:15.635  3275  3275 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:15.635  1967  3219 I iu.UploadsManager: #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,03-16 11:17:15.645  3293  3293 E Zygote  : MountEmulatedStorage()
03-16 11:17:15.645  3293  3293 I libpersona: KNOX_SDCARD checking this for 10150
03-16 11:17:15.645  3293  3293 E Zygote  : v2
03-16 11:17:15.645  3293  3293 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:15.645  3293  3293 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:15.645  3293  3293 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:15.645  1018  1142 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3293 uid=10150 gids={50150, 9997} abi=armeabi-v7a
03-16 11:17:15.645  2666  2666 I FactoryTestApp: [IPCWriterToSecPhoneService$onServiceConnected](2666) connected done
03-16 11:17:15.645  2666  2666 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2666) Send Response Message to SecPhone
03-16 11:17:15.645  2666  2666 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2666) Response ��,
03-16 11:17:15.645  3293  3293 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-16 11:17:15.655  1018  1369 D ActivityManager: startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
03-16 11:17:15.655  1018  1369 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,03-16 11:17:15.665  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:15.665  1018  1369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:15.665  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-16 11:17:15.665   310  1075 D AT_Distributor: Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>,
,03-16 11:17:15.675  2335  3090 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-16 11:17:15.685  2666  2666 D FactoryTestApp: [IPCWriterToSecPhoneService$handleMessage](2666) Send BOOTING COMPLETED done
,03-16 11:17:15.685  3177  3177 D [0]UMC:GuardService: @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
,03-16 11:17:15.695  3177  3177 D [0]UMC:CoreReceiver: Intent : android.intent.action.BOOT_COMPLETED
03-16 11:17:15.695  3177  3177 D [0]UMC:CoreReceiver:  check PreETag 
,03-16 11:17:15.695  1018  1042 D SensorService: [SO] currT = 37800083630, prevT = 37450075193, diff = 350008437, [0.134 0.402 10.132]
03-16 11:17:15.695  1018  1042 D SensorService: [SO] 0.134 0.402 10.132
03-16 11:17:15.695  1018  1042 D SensorService: [SO] [100 -> 255]
,03-16 11:17:15.695   288   288 E SMD     : DCD OFF,
,03-16 11:17:15.695   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,03-16 11:17:15.705  3293  3293 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:15.705  2686  2776 D BluetoothMediaBrowser: no now playing list
03-16 11:17:15.705  2686  2776 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,03-16 11:17:15.705  3293  3293 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:15.705  2335  3311 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-16 11:17:15.725  3259  3259 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 11:17:15.725  2335  3090 D Mms/MessagingNotification: remove alarm
,03-16 11:17:15.765  1473  1486 D TP/SmsProvider: query,matched:0, calling pid = 2335
03-16 11:17:15.765  3239  3239 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
03-16 11:17:15.765   310  1075 D AT_Distributor: SetAtdStatus(), 1_1_0
03-16 11:17:15.765   310  1075 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
,03-16 11:17:15.775  1473  1486 D TP/SmsProvider: match 0:Elapsed time : 2.182 ms
,03-16 11:17:15.785  3177  3177 D [0]UMC:CoreReceiver: bulk enrolled package: null
,03-16 11:17:15.785  3177  3177 V [0]UMC:ProfileStorage: Enter loadList
,03-16 11:17:15.785  3177  3177 D [0]UMC:CoreReceiver: handleAutoEnrollmentAndUMCAdminDeactivation
03-16 11:17:15.785  3177  3177 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,03-16 11:17:15.785  3177  3177 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-16 11:17:15.785  3177  3177 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
,03-16 11:17:15.785  3177  3177 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
03-16 11:17:15.785  3177  3177 D [0]UMC:UMCAdmin: isContainer : 0
,03-16 11:17:15.785  1018  1574 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-16 11:17:15.785  3177  3177 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
03-16 11:17:15.785  3177  3177 D [0]UMC:UMCAdmin: isContainer : 0
03-16 11:17:15.785  3239  3239 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7895-7897)
03-16 11:17:15.785  2335  3090 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 803.171926
03-16 11:17:15.785  3239  3239 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 11:17:15.795  3177  3177 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-16 11:17:15.795  1018  1369 I ActivityManager: Killing 2305:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-16 11:17:15.805  1967  3219 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 164 ms,
,03-16 11:17:15.805  3177  3177 D [0]UMC:ByodSetupStarter: Container ID : 0
,03-16 11:17:15.805  3177  3177 V [0]UMC:Utils: checkAppScreen() : com.test.thalitest
03-16 11:17:15.805  3177  3177 I [0]UMC:Core: shutdown
,03-16 11:17:15.805  1018  1345 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,03-16 11:17:15.805  1018  1345 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:15.805  1018  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:15.805  1018  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-16 11:17:15.815  3177  3177 D [0]UMC:GuardService: @GuardService - stopService Result = true
,03-16 11:17:15.815  1018  1366 I ActivityManager: Killing 2427:com.wsomacp/u0a25 (adj 15): empty #31
03-16 11:17:15.815  3177  3177 I art     : System.exit called, status: 0
03-16 11:17:15.815  3177  3177 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,03-16 11:17:15.825  3239  3239 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3a008dfa}
,03-16 11:17:15.825  3239  3239 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 11:17:15.825  3239  3239 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,03-16 11:17:15.855  3239  3239 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-16 11:17:15.865  3239  3239 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 11:17:15.865  3239  3239 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-16 11:17:15.865  3275  3275 E UpdateRequestReceiver: ignoring update request
,03-16 11:17:15.865  3259  3259 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,03-16 11:17:15.895  3275  3275 E UpdateRequestReceiver: ignoring update request
,03-16 11:17:15.895  3239  3239 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,03-16 11:17:15.895  3239  3239 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=50556 len=3379
03-16 11:17:15.895  3239  3239 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:40 off:7638088 len:1165478
,03-16 11:17:15.895  3239  3239 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-16 11:17:15.895  3239  3239 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-16 11:17:15.895  3239  3239 I Adreno-EGL: Build Date: 04/06/15 Mon
03-16 11:17:15.895  3239  3239 I Adreno-EGL: Local Branch: 
03-16 11:17:15.895  3239  3239 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-16 11:17:15.895  3239  3239 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-16 11:17:15.895  3239  3239 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-16 11:17:15.905  1018  1369 I ActivityManager: Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3177)(adj 0) has died(245,1047)
,03-16 11:17:15.905  3275  3275 E UpdateRequestReceiver: ignoring update request
,03-16 11:17:15.915   258   432 I SurfaceFlinger: id=8 Removed Mauncher (5/8)
,03-16 11:17:15.915   258   853 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
03-16 11:17:15.915  1367  1367 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-16 11:17:15.915  1367  1367 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-16 11:17:15.915  1367  1367 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-16 11:17:15.925  1367  1367 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-16 11:17:15.925  1367  1367 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-16 11:17:15.925  1367  1367 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
03-16 11:17:15.935  1367  1367 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-16 11:17:15.935  1367  1367 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,03-16 11:17:15.935  1367  1367 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-16 11:17:15.935  1367  1367 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-16 11:17:15.935  1367  1367 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-16 11:17:15.935  1367  1367 D daemonapp: [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,03-16 11:17:15.945  1018  3034 D SettingsProvider: name = aw_daemon_service_key_version_check
,03-16 11:17:15.945  1018  3034 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 11:17:15.945  1018  3034 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 11:17:15.945  1018  3034 D SettingsProvider: selectionArgs: false
03-16 11:17:15.945  1018  3034 D SettingsProvider: selectionArgs: 10162
03-16 11:17:15.945  1018  3034 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 11:17:15.945  1018  3034 D SettingsProvider: ret = -1
03-16 11:17:15.945  3275  3275 E UpdateRequestReceiver: ignoring update request
,03-16 11:17:15.955  1018  3034 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10162
,03-16 11:17:15.955  1367  1367 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-16 11:17:15.955  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2305/cgroup.procs: No such file or directory
03-16 11:17:15.955  1018  1044 W libprocessgroup: failed to open /acct/uid_10025/pid_2427/cgroup.procs: No such file or directory
,03-16 11:17:15.965  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 11:17:15.965  3275  3275 E UpdateRequestReceiver: ignoring update request
,03-16 11:17:15.975  3275  3275 E UpdateRequestReceiver: ignoring update request
,03-16 11:17:15.975  1018  1142 D ActivityManager: startProcessLocked calleePkgName: com.dropbox.android, hostingType: broadcast
03-16 11:17:15.975  3203  3203 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-16 11:17:15.975  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:15.975  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:15.975  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:15.985  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:15.985  1367  1367 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
03-16 11:17:15.985  3203  3203 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-16 11:17:15.995  3203  3203 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED,
,03-16 11:17:15.995  1367  1367 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR,
,03-16 11:17:15.995  1367  1367 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng,
03-16 11:17:15.995  3203  3203 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-16 11:17:15.995  1367  1367 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
03-16 11:17:15.995  3203  3203 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
03-16 11:17:15.995  3203  3203 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-16 11:17:15.995  3259  3259 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,03-16 11:17:15.995  1367  1367 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename,
,03-16 11:17:16.005  3346  3346 E Zygote  : MountEmulatedStorage(),
03-16 11:17:16.005  3346  3346 I libpersona: KNOX_SDCARD checking this for 10092
,03-16 11:17:16.005  3346  3346 E Zygote  : v2
03-16 11:17:16.005  3346  3346 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:16.005  1367  1367 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-16 11:17:16.005  1367  1367 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-16 11:17:16.005  3259  3259 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,03-16 11:17:16.005  3346  3346 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-16 11:17:16.005  1367  1367 D daemonapp: [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1458123436018
03-16 11:17:16.005  1367  1367 D daemonapp: [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1458145020000
03-16 11:17:16.005  1367  1367 D daemonapp: [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
03-16 11:17:16.005  1367  1367 D daemonapp: [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
03-16 11:17:16.005  3259  3259 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
03-16 11:17:16.005  3346  3346 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:16.015  3346  3346 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-16 11:17:16.025  1018  1142 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3346 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 11:17:16.025  1018  1142 I ActivityManager: Killing 2474:com.sec.android.widgetapp.digitalclock/u0a88 (adj 15): empty #31
,03-16 11:17:16.055  3346  3346 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:16.055  3346  3346 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:16.075  1367  1367 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458145020000,
,03-16 11:17:16.075  1367  1367 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
03-16 11:17:16.075  1367  1367 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458145020000
,03-16 11:17:16.085  1018  1573 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.policydm
,03-16 11:17:16.095  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:16.095  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:16.095  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:16.095  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:16.105  3367  3367 E Zygote  : MountEmulatedStorage(),
03-16 11:17:16.105  3367  3367 I libpersona: KNOX_SDCARD checking this for 1000
03-16 11:17:16.105  3367  3367 E Zygote  : v2
,03-16 11:17:16.105  3367  3367 I libpersona: KNOX_SDCARD not a persona,
,03-16 11:17:16.105  3367  3367 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:16.115  1018  1573 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3367 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-16 11:17:16.115  3367  3367 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:16.115  3367  3367 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:16.145  3367  3367 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 11:17:16.145  3367  3367 D ActivityThread: Added TimaKeyStore provider
03-16 11:17:16.145  3239  3342 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,03-16 11:17:16.155  1018  1044 W libprocessgroup: failed to open /acct/uid_10088/pid_2474/cgroup.procs: No such file or directory
,03-16 11:17:16.185  1018  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 11:17:16.185  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:16.185  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 11:17:16.185  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-16 11:17:16.215  3239  3239 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 11:17:16.255  3239  3239 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-16 11:17:16.255  1018  1142 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,03-16 11:17:16.255  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:16.255  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:16.255  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:16.255  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:16.265  3239  3239 D PhoneWindow: *FMB* installDecor mIsFloating : false
,03-16 11:17:16.265  3239  3239 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-16 11:17:16.275  3367  3367 I DBG_POLICYDM: [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,03-16 11:17:16.275  3390  3390 E Zygote  : MountEmulatedStorage()
03-16 11:17:16.275  3390  3390 E Zygote  : v2
03-16 11:17:16.275  3390  3390 I libpersona: KNOX_SDCARD checking this for 10009
03-16 11:17:16.275  3390  3390 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:16.275  3239  3239 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
03-16 11:17:16.275  1018  1142 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3390 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:17:16.285  3390  3390 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-16 11:17:16.285  3367  3367 I DBG_POLICYDM: [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-16 11:17:16.285  3390  3390 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:16.285  3239  3239 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 11:17:16.285  3239  3239 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 11:17:16.285  3390  3390 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-16 11:17:16.295  1367  1367 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,03-16 11:17:16.295  1367  1367 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-16 11:17:16.295  1018  1366 D ActivityManager: startProcessLocked calleePkgName: com.google.android.youtube, hostingType: broadcast
,03-16 11:17:16.305  1018  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:16.305  1018  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:16.305  1018  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:16.305  1018  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:16.305  3367  3386 I DBG_POLICYDM: [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,03-16 11:17:16.315  3405  3405 E Zygote  : MountEmulatedStorage()
,03-16 11:17:16.315  3367  3367 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,03-16 11:17:16.315  3405  3405 E Zygote  : v2
03-16 11:17:16.315  3405  3405 I libpersona: KNOX_SDCARD checking this for 10166
,03-16 11:17:16.315  3405  3405 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:16.315  3405  3405 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:16.315  3405  3405 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:16.325  1018  1366 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3405 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:17:16.325  3405  3405 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 11:17:16.325  3367  3367 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-16 11:17:16.325  3390  3390 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:16.325  3390  3390 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:16.355   306   306 I art     : Explicit concurrent mark sweep GC freed 8755(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 647us total 31.016ms
,03-16 11:17:16.355  3405  3405 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:16.355  3405  3405 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:16.355  3014  3014 E BluetoothHeadset: BTStateChangeCB is registed
,03-16 11:17:16.355  3014  3014 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,03-16 11:17:16.365  1018  2954 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
03-16 11:17:16.365  1018  2954 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,03-16 11:17:16.365  1018  2954 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:16.365  3367  3386 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
03-16 11:17:16.365  1018  2954 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:16.365  1018  2954 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,03-16 11:17:16.365  3014  3014 E BluetoothHeadset: BluetoothHeadset service is binded
,03-16 11:17:16.365  3014  3014 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,03-16 11:17:16.365  1018  1515 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
03-16 11:17:16.375   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 19.484ms
03-16 11:17:16.375  1018  1515 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
03-16 11:17:16.375  1018  1515 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:16.375  1018  1515 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 11:17:16.375  1018  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,03-16 11:17:16.375  3367  3367 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-16 11:17:16.385  3367  3367 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-16 11:17:16.385  3367  3367 I DBG_POLICYDM: [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,03-16 11:17:16.385  3367  3367 I DBG_POLICYDM: [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,03-16 11:17:16.385  3367  3367 I DBG_POLICYDM: [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,03-16 11:17:16.385   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 618us total 18.212ms
,03-16 11:17:16.395  3259  3259 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,03-16 11:17:16.395  3259  3259 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,03-16 11:17:16.395  3259  3259 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,03-16 11:17:16.395  1018  1574 D ActivityManager: startService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm
,03-16 11:17:16.395  1018  1574 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,03-16 11:17:16.405  1018  1574 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:16.405  1018  1574 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:16.405  1018  1574 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-16 11:17:16.405  1018  1345 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 11:17:16.405  3239  3424 D OpenGLRenderer: Render dirty regions requested: true
,03-16 11:17:16.405  3259  3259 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,03-16 11:17:16.405  3259  3259 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
,03-16 11:17:16.415  3259  3259 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
03-16 11:17:16.415  1018  1345 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:16.415  1018  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:16.415  1018  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:16.415  1018  1574 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-16 11:17:16.415  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
03-16 11:17:16.415  1018  1574 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-16 11:17:16.415  1018  1574 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-16 11:17:16.415  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-16 11:17:16.425  1018  3034 I ActivityManager: Killing 2491:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
03-16 11:17:16.425  3239  3239 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-16 11:17:16.425  3239  3239 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-16 11:17:16.425  3259  3259 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
03-16 11:17:16.425  3259  3259 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
03-16 11:17:16.425  3259  3259 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
03-16 11:17:16.425  3259  3259 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,03-16 11:17:16.435   258   258 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
03-16 11:17:16.435  1187  1187 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
03-16 11:17:16.435  1187  1187 D OverheatReceiver: into the SAFE_MODE_ACTION
03-16 11:17:16.435  1187  1187 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
03-16 11:17:16.435  1187  1187 D OverheatReceiver: isSafeMode = false
03-16 11:17:16.435  3259  3259 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
,03-16 11:17:16.435  3259  3259 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
03-16 11:17:16.435  3259  3259 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
,03-16 11:17:16.435  3259  3259 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
,03-16 11:17:16.435  3259  3259 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
03-16 11:17:16.435  3259  3343 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,03-16 11:17:16.445  1473  1473 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
,03-16 11:17:16.445  1018  1490 D SettingsProvider: name = internet_call_settings_visibility
03-16 11:17:16.445  1018  1490 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 11:17:16.445  1018  1490 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 11:17:16.445  1018  1490 D SettingsProvider: selectionArgs: false
03-16 11:17:16.445  1018  1490 D SettingsProvider: selectionArgs: 1001
03-16 11:17:16.445  1018  1490 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 11:17:16.445  1018  1490 D SettingsProvider: ret = -1
03-16 11:17:16.445  1473  1473 D PhoneUtilsCommon: isSupportVoLTE is false.
03-16 11:17:16.445  1018  1366 D InputDispatcher: Focus entered window: 3239
03-16 11:17:16.445  3259  3259 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,03-16 11:17:16.455  1018  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 11:17:16.455  1018  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-16 11:17:16.455  3239  3239 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-16 11:17:16.455  3239  3424 I OpenGLRenderer: Initialized EGL, version 1.4
03-16 11:17:16.455  1444  1444 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,03-16 11:17:16.455  1018  1369 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: android.telecom.InCallService
03-16 11:17:16.455  1018  1369 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
03-16 11:17:16.455  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:16.455  1018  1369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:16.455  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
03-16 11:17:16.455  3239  3424 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-16 11:17:16.455  3239  3424 D OpenGLRenderer: Enabling debug mode 0
,03-16 11:17:16.455  1018  2954 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: com.samsung.incallui.SEC_IN_CALL_SERVICE
03-16 11:17:16.465  1018  2954 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:16.455  1018  2954 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
03-16 11:17:16.465  1018  2954 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:16.465  1018  2954 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-16 11:17:16.465  3259  3259 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,03-16 11:17:16.465  3259  3259 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,03-16 11:17:16.465  3259  3259 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,03-16 11:17:16.465  1018  3034 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,03-16 11:17:16.465  3259  3259 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
03-16 11:17:16.475  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:16.475  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:16.475  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:16.475  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:16.475  3259  3259 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
,03-16 11:17:16.485  3430  3430 E Zygote  : MountEmulatedStorage(),
,03-16 11:17:16.495  3430  3430 E Zygote  : v2
,03-16 11:17:16.495  3430  3430 I libpersona: KNOX_SDCARD checking this for 10057
03-16 11:17:16.495  3430  3430 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:16.495  3430  3430 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:16.495  3430  3430 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:16.495  1018  3034 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3430 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
03-16 11:17:16.495  3430  3430 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 11:17:16.505  1018  1044 W libprocessgroup: failed to open /acct/uid_10142/pid_2491/cgroup.procs: No such file or directory
,03-16 11:17:16.505  3259  3343 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,03-16 11:17:16.505  3259  3343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,03-16 11:17:16.505  1018  1573 D ActivityManager: bindService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm, action: null
03-16 11:17:16.505  1018  1573 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
,03-16 11:17:16.505  1018  1573 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:16.505  1018  1573 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:16.505  1018  1573 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-16 11:17:16.515  3259  3259 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-16 11:17:16.525  2146  2146 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,03-16 11:17:16.525  2146  2146 I dhcpcd  : wlan0: no IPv6 Routers available
,03-16 11:17:16.525  3367  3386 I DBG_POLICYDM: [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,03-16 11:17:16.535  3014  3014 D BluetoothA2dp: Proxy object connected
,03-16 11:17:16.535  3430  3430 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:16.535  3430  3430 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:16.565  1018  1030 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
03-16 11:17:16.565  1187  1187 I StatusBar: Icon Only
03-16 11:17:16.565  1187  1187 D PanelView: There is/are notification(s) 
,03-16 11:17:16.565  1018  3445 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 11:17:16.575  3239  3239 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@b9d9477 time:38684
,03-16 11:17:16.575  1808  1808 I SamsungIME: getCurrentCandidateView
,03-16 11:17:16.585  1018  1050 I ActivityManager: Displayed Component not be shown by security: +1s204ms
,03-16 11:17:16.585  1018  1050 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,03-16 11:17:16.585  1018  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3ff1f3d6 u0 com.test.thalitest/.MainActivity t12} time:38694
03-16 11:17:16.585  1018  1050 W ActivityManager: mDVFSHelper.release()
,03-16 11:17:16.585  1018  1045 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-16 11:17:16.695   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-16 11:17:16.735  3259  3343 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,03-16 11:17:16.755  1018  1574 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,03-16 11:17:16.755  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:16.755  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:16.755  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:16.765  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:16.775  3457  3457 E Zygote  : MountEmulatedStorage()
03-16 11:17:16.775  3457  3457 E Zygote  : v2
03-16 11:17:16.775  3457  3457 I libpersona: KNOX_SDCARD checking this for 10015
03-16 11:17:16.775  3457  3457 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:16.775  3457  3457 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:16.775  3457  3457 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-16 11:17:16.775  1018  1574 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3457 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
03-16 11:17:16.775  3457  3457 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 11:17:16.785   258   430 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
,03-16 11:17:16.785   258   432 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
,03-16 11:17:16.805  1018  1030 D LocationManagerService: getProviders()=[passive]
,03-16 11:17:16.805  3457  3457 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:16.805  3457  3457 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:16.825  3405  3449 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-16 11:17:16.825  3405  3449 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 11:17:16.855  1018  1345 D ActivityManager: startProcessLocked calleePkgName: com.fmm.dm, hostingType: broadcast
,03-16 11:17:16.855  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:16.855  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:16.855  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:16.855  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:16.865  3259  3259 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] ,
,03-16 11:17:16.885  3479  3479 E Zygote  : MountEmulatedStorage()
,03-16 11:17:16.885  3479  3479 E Zygote  : v2
03-16 11:17:16.885  3479  3479 I libpersona: KNOX_SDCARD checking this for 1000
03-16 11:17:16.885  3479  3479 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:16.885  3479  3479 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-16 11:17:16.885  1018  1345 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3479 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
03-16 11:17:16.885  1018  1018 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,03-16 11:17:16.885  1018  1345 I ActivityManager: Killing 2618:com.example.hello/u0a174 (adj 15): empty #31,
,03-16 11:17:16.895  1018  1345 I ActivityManager: Killing 2506:com.sec.android.app.camera/u0a139 (adj 15): empty #32,
,03-16 11:17:16.895  3479  3479 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:16.895  3479  3479 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-16 11:17:16.905  1444  1444 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,03-16 11:17:16.935  3405  3449 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-16 11:17:16.935  3479  3479 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:16.935  3479  3479 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:17.015  3405  3449 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-16 11:17:17.015  3405  3449 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@19aa2b62: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-16 11:17:17.015  3405  3449 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-16 11:17:17.015  1018  1044 W libprocessgroup: failed to open /acct/uid_10174/pid_2618/cgroup.procs: No such file or directory
03-16 11:17:17.015  1018  1044 W libprocessgroup: failed to open /acct/uid_10139/pid_2506/cgroup.procs: No such file or directory
,03-16 11:17:17.035  1018  1369 I art     : Explicit concurrent mark sweep GC freed 17740(904KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 26MB/39MB, paused 3.094ms total 155.460ms
,03-16 11:17:17.035  1018  1369 E Tethering: No numeric data
,03-16 11:17:17.045  1018  1573 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,03-16 11:17:17.045  1018  1573 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,03-16 11:17:17.045  1018  1573 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:17.045  1018  1573 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:17.045  1018  1573 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-16 11:17:17.045  1018  1366 E Tethering: No numeric data
,03-16 11:17:17.045  1018  2954 I ActivityManager: Killing 2602:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,03-16 11:17:17.055  1018  3034 E Tethering: No numeric data
,03-16 11:17:17.055  1018  1142 I ActivityManager: Killing 2651:com.android.calendar/u0a135 (adj 15): empty #31
,03-16 11:17:17.065  1018  1345 D ActivityManager: startService callerProcessName:com.dropbox.android, calleePkgName: com.dropbox.android
03-16 11:17:17.065  1018  1345 D ActivityManager: retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,03-16 11:17:17.065  1018  1515 E Tethering: No numeric data
,03-16 11:17:17.075  1018  1345 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:17.075  1018  1345 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,03-16 11:17:17.075  1018  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-16 11:17:17.075  1018  1366 E Tethering: No numeric data
,03-16 11:17:17.075  1018  2954 E Tethering: No numeric data
,03-16 11:17:17.075  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:17.075  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:17.075  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:17.075  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:17.085  3430  3492 I SearchServiceFactory: checking for language pack updates,
,03-16 11:17:17.095  3501  3501 E Zygote  : MountEmulatedStorage()
03-16 11:17:17.095  3501  3501 I libpersona: KNOX_SDCARD checking this for 10092
03-16 11:17:17.095  3501  3501 E Zygote  : v2
03-16 11:17:17.095  3501  3501 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:17.095  1018  1345 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3501 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:17:17.095  3501  3501 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:17.105  3501  3501 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:17.105  1018  1366 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
03-16 11:17:17.105  1018  1366 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
,03-16 11:17:17.105  1018  1366 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:17.105  1018  1366 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:17.105  1018  1366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-16 11:17:17.105  3501  3501 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-16 11:17:17.125  3501  3501 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:17.125  3501  3501 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:17.125  3430  3517 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[update_gservices_config]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-16 11:17:17.125  3430  3517 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[refresh_search_domain_and_cookies]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-16 11:17:17.135  3430  3518 I GservicesUpdateTask: Updating Gservices keys
,03-16 11:17:17.135  3430  3517 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[update_language_packs]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-16 11:17:17.155  3430  3519 I UpdateLanguagePacksTask: Checking for language pack updates.
,03-16 11:17:17.165  1018  2783 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.cB:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-16 11:17:17.165  3479  3479 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,03-16 11:17:17.175  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,03-16 11:17:17.185  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:17.185  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:17.185  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:17.185  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:17.185  1018  1044 W libprocessgroup: failed to open /acct/uid_10135/pid_2651/cgroup.procs: No such file or directory
03-16 11:17:17.185  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2602/cgroup.procs: No such file or directory
03-16 11:17:17.185  1808  1808 D SamsungIME: Dismiss ExpandCandiate
,03-16 11:17:17.195  3523  3523 E Zygote  : MountEmulatedStorage(),
03-16 11:17:17.195  3523  3523 E Zygote  : v2
03-16 11:17:17.195  3523  3523 I libpersona: KNOX_SDCARD checking this for 10003,
03-16 11:17:17.195  3479  3479 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
03-16 11:17:17.195  3523  3523 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:17.195  3479  3479 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-16 11:17:17.195  3479  3479 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-16 11:17:17.195  3523  3523 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-16 11:17:17.195  1018  1018 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3523 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,03-16 11:17:17.205  3523  3523 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-16 11:17:17.205  3523  3523 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:17.215  3259  3343 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,03-16 11:17:17.225  3239  3239 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3239
,03-16 11:17:17.235  1314  3257 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
,03-16 11:17:17.255  3523  3523 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:17.255  3523  3523 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:17.255  1314  3257 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
,03-16 11:17:17.265   281   834 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
,03-16 11:17:17.275   281   834 D audio_hw_extn: audio_extn_get_parameters: returns 
03-16 11:17:17.275   281   834 V msm8974_platform: platform_get_parameters: exit: returns - 
03-16 11:17:17.275   281   834 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-16 11:17:17.275   281   834 I str_params: key: 'call_forwarding' value: ''
,03-16 11:17:17.275  2029  2029 V InCall  : ProximitySensor -  - screenonImmediately: false
,03-16 11:17:17.275  2029  2029 V InCall  : ProximitySensor -  - mFromRcsShare: false
,03-16 11:17:17.275  2029  2029 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,03-16 11:17:17.275  2029  2029 D ScoverManager: serviceVersion : 16908288
,03-16 11:17:17.275  1018  1515 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-16 11:17:17.275  2029  2029 D InCall  : InCallUtils - isCoverClosed false
,03-16 11:17:17.285  1018  1573 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-16 11:17:17.285  1018  1490 E Tethering: No numeric data
03-16 11:17:17.285  1444  1444 I Telecom : ProximitySensorManager: Proximity wake lock already released
03-16 11:17:17.285  2029  2029 D InCall  : InCallUtils - isCoverClosed false
03-16 11:17:17.285  2029  2029 I InCall  : InCallPresenter -  - InCallState = NO_CALLS
,03-16 11:17:17.285  2029  2029 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
,03-16 11:17:17.285  2029  2029 D InCall  : InCallPresenter -  - dismissCoverDialog()...
03-16 11:17:17.285  1018  1030 E Tethering: No numeric data
,03-16 11:17:17.285  1018  1515 E Tethering: No numeric data
03-16 11:17:17.295  1018  1574 D ActivityManager: getContentProviderImpl callerProcessName:com.fmm.dm, calleePkgName: com.sec.pcw.device
03-16 11:17:17.295  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:17.295  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:17.295  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:17.295  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:17.305  3259  3343 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-16 11:17:17.315  3544  3544 E Zygote  : MountEmulatedStorage()
03-16 11:17:17.315  3544  3544 E Zygote  : v2
03-16 11:17:17.315  3544  3544 I libpersona: KNOX_SDCARD checking this for 1000
03-16 11:17:17.315  3544  3544 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:17.315  3544  3544 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:17.325  3544  3544 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:17.325  3544  3544 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:17.325  1018  1030 E Tethering: No numeric data
,03-16 11:17:17.335  2029  2029 I InCall  : CallSContextMotion - stopPutDownListening
,03-16 11:17:17.335  2029  2029 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,03-16 11:17:17.335  1018  1574 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3544 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-16 11:17:17.345  3544  3544 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:17.345  1187  1187 D PhoneStatusBarView: setCallBackground:0
03-16 11:17:17.345  3544  3544 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:17.345  3367  3386 I DBG_POLICYDM: [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-16 11:17:17.355  3259  3343 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,03-16 11:17:17.355  3259  3343 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,03-16 11:17:17.355  1018  1031 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-16 11:17:17.355  2029  2029 D InCall  : InCallUtils - isCoverClosed false
,03-16 11:17:17.365  3367  3386 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-16 11:17:17.395  3367  3386 I DBG_POLICYDM: [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,03-16 11:17:17.395  3367  3386 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,03-16 11:17:17.405  3430  3491 E File    : fail readDirectory() errno=2
,03-16 11:17:17.415  1018  1345 V VibratorService: hasVibrator - useVibetonz: true
,03-16 11:17:17.435  3367  3386 I DBG_POLICYDM: [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,03-16 11:17:17.445  3523  3523 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-16 11:17:17.455  3346  3346 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
,03-16 11:17:17.455  1314  3257 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,03-16 11:17:17.465  1018  1490 V VibratorService: hasVibrator - useVibetonz: true
,03-16 11:17:17.495  3430  3520 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-16 11:17:17.495  2029  2029 D VideoCallManager: Instantiating VideoCallManager
03-16 11:17:17.495  1018  2954 V VibratorService: hasVibrator - useVibetonz: true
,03-16 11:17:17.495   257   511 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.googlequicksearchbox/files/download_cache/
03-16 11:17:17.495   257   511 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:17:17.495  2029  2029 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-16 11:17:17.505  3544  3544 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-16 11:17:17.505  3544  3544 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-16 11:17:17.505  2029  2029 I GFX construct_block_size_descriptor_2d second part: took 2.373542ms for 0*0 texture 0
03-16 11:17:17.505  3430  3492 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.googlequicksearchbox/files/download_cache
,03-16 11:17:17.515  3544  3544 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-16 11:17:17.515  2029  2029 I GFX generate_partition_tables: took 5.163228ms for 0*0 texture 0
,03-16 11:17:17.515  2029  2029 I GFX raster: took 11.505885ms for 176*144 texture 0
03-16 11:17:17.515  2029  2029 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7e9cd38 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb7eb4f48 counterpartCT=4 counterpartW=176 counterparth=144
,03-16 11:17:17.525  2029  2029 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,03-16 11:17:17.525  2029  2029 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-16 11:17:17.525  2029  2029 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-16 11:17:17.525  2029  2029 I Adreno-EGL: Build Date: 04/06/15 Mon
03-16 11:17:17.525  2029  2029 I Adreno-EGL: Local Branch: 
03-16 11:17:17.525  2029  2029 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-16 11:17:17.525  2029  2029 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-16 11:17:17.525  2029  2029 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-16 11:17:17.545  1314  3257 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 11:17:17.545  2029  2029 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-16 11:17:17.555  2029  2029 I glCompressedTexImage2D: took 0.439792ms for 320*61440 texture 37809
,03-16 11:17:17.555  3544  3551 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-16 11:17:17.565  2029  2029 I draw setup: took 11.617135ms for 320*240 texture 37809
03-16 11:17:17.565  2029  2029 E GFX GPU raster: drawn
,03-16 11:17:17.565  2029  2029 I GFX GPU raster ASTC: took 41.063021ms for 320*240 texture 12
03-16 11:17:17.565  2029  2029 I GFX raster: took 41.143854ms for 320*240 texture 0
03-16 11:17:17.565  2029  2029 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7eb4f48 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb7eb7288 counterpartCT=4 counterpartW=320 counterparth=240
,03-16 11:17:17.575  3479  3479 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-16 11:17:17.585  3479  3479 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,03-16 11:17:17.585  3479  3479 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-16 11:17:17.585  2029  2029 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-16 11:17:17.585  1018  1574 I ActivityManager: Killing 2460:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
03-16 11:17:17.585  1018  1574 I ActivityManager: Killing 2705:com.android.keychain/1000 (adj 15): empty #32
03-16 11:17:17.585  2029  2029 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-16 11:17:17.585  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.fmm.ds, hostingType: broadcast
,03-16 11:17:17.585  2029  2029 I glCompressedTexImage2D: took 0.349896ms for 480*122880 texture 37813
03-16 11:17:17.585  2029  2029 I draw setup: took 0.716719ms for 480*640 texture 37813
03-16 11:17:17.585  2029  2029 E GFX GPU raster: drawn
,03-16 11:17:17.595  2029  2029 I GFX GPU raster ASTC: took 7.206615ms for 480*640 texture 12
03-16 11:17:17.595  2029  2029 I GFX raster: took 7.292760ms for 480*640 texture 0
03-16 11:17:17.595  2029  2029 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7eb7288 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb80e5700 counterpartCT=4 counterpartW=480 counterparth=640
,03-16 11:17:17.625  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:17.625  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:17.625  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:17.625  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:17.625  3367  3386 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,03-16 11:17:17.645  3571  3571 E Zygote  : MountEmulatedStorage(),
03-16 11:17:17.645  3571  3571 E Zygote  : v2
03-16 11:17:17.645  3571  3571 I libpersona: KNOX_SDCARD checking this for 1000,
03-16 11:17:17.645  3571  3571 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:17.645  3571  3571 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-16 11:17:17.645  1018  2866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-16 11:17:17.645  1018  1031 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3571 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-16 11:17:17.655  3571  3571 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:17.655  3571  3571 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:17.655  2029  2029 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,03-16 11:17:17.655  2029  2029 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS,
03-16 11:17:17.665  3346  3346 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
03-16 11:17:17.665  2029  2029 I glCompressedTexImage2D: took 0.503073ms for 440*116864 texture 37809
03-16 11:17:17.665  2029  2029 I draw setup: took 1.130625ms for 440*330 texture 37809
,03-16 11:17:17.665  2029  2029 E GFX GPU raster: drawn
03-16 11:17:17.675  2029  2029 I GFX GPU raster ASTC: took 5.906823ms for 440*330 texture 12
03-16 11:17:17.675  2029  2029 I GFX raster: took 6.029949ms for 440*330 texture 0
03-16 11:17:17.675  2029  2029 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb80e5700 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb80f9af0 counterpartCT=4 counterpartW=440 counterparth=330
,03-16 11:17:17.685  3523  3523 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-16 11:17:17.685  3523  3523 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-16 11:17:17.685  3523  3523 D UserAnalysis: Create SecureDbHelper
,03-16 11:17:17.705  3571  3571 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:17.705  3571  3571 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:17.715  1808  1808 I SamsungIME: getDebugLevel  : 0x4f4c
,03-16 11:17:17.725  3430  3520 I LibraryLoader: Time to load native libraries: 30 ms (timestamps 9801-9831)
,03-16 11:17:17.725  3430  3520 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 11:17:17.725  2029  2029 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-16 11:17:17.725  2029  2029 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-16 11:17:17.725  2029  2029 I glCompressedTexImage2D: took 0.458646ms for 480*163840 texture 37811
03-16 11:17:17.725  2029  2029 I draw setup: took 0.851510ms for 480*640 texture 37811
03-16 11:17:17.725  2029  2029 E GFX GPU raster: drawn
,03-16 11:17:17.735  2029  2029 I GFX GPU raster ASTC: took 5.842604ms for 480*640 texture 12
03-16 11:17:17.735  3367  3386 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
03-16 11:17:17.735  2029  2029 I GFX raster: took 5.934844ms for 480*640 texture 0
03-16 11:17:17.735  2029  2029 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb80e9900 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb80f9628 counterpartCT=4 counterpartW=480 counterparth=640
,03-16 11:17:17.755  3367  3386 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-16 11:17:17.755  3367  3386 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,03-16 11:17:17.755  3367  3386 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,03-16 11:17:17.775  3367  3387 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-16 11:17:17.785  2029  2029 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-16 11:17:17.785  2029  2029 I GFX construct_block_size_descriptor_2d second part: took 2.046719ms for 0*0 texture 0
,03-16 11:17:17.785  3367  3387 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-16 11:17:17.795  1314  3257 D ScoverManager: serviceVersion : 16908288
,03-16 11:17:17.795  2029  2029 I GFX generate_partition_tables: took 7.618334ms for 0*0 texture 0
,03-16 11:17:17.795  2029  2029 I GFX raster: took 11.705261ms for 176*144 texture 0
03-16 11:17:17.795  2029  2029 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb80e2fc0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb80e30e0 counterpartCT=4 counterpartW=176 counterparth=144
,03-16 11:17:17.805  3523  3523 D IntelligenceServiceApplication: onCreate()
,03-16 11:17:17.805  3346  3346 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,03-16 11:17:17.805  3523  3523 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,03-16 11:17:17.805  2029  2029 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
03-16 11:17:17.805  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,03-16 11:17:17.815  2029  2029 I GFX construct_block_size_descriptor_2d second part: took 2.547030ms for 0*0 texture 0
,03-16 11:17:17.815  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:17.815  3346  3346 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
03-16 11:17:17.815  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:17.815  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:17.815  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:17.815  3346  3346 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,03-16 11:17:17.835  3590  3590 E Zygote  : MountEmulatedStorage(),
03-16 11:17:17.835  3590  3590 E Zygote  : v2
03-16 11:17:17.835  2029  2029 I GFX generate_partition_tables: took 6.488906ms for 0*0 texture 0,
03-16 11:17:17.835  3590  3590 I libpersona: KNOX_SDCARD checking this for 10060
03-16 11:17:17.835  3590  3590 I libpersona: KNOX_SDCARD not a persona,
,03-16 11:17:17.845  2029  2029 I GFX raster: took 11.456040ms for 176*144 texture 0,
03-16 11:17:17.845  1018  1031 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3590 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-16 11:17:17.845  2029  2029 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb80e3300 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb80e32a0 counterpartCT=4 counterpartW=176 counterparth=144
,03-16 11:17:17.845  1018  1031 I ActivityManager: Killing 2799:com.android.email/u0a145 (adj 15): empty #31
,03-16 11:17:17.845  3590  3590 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:17.845  3590  3590 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-16 11:17:17.845  3590  3590 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:17.845  2029  2029 D ScoverManager: registerListener,
,03-16 11:17:17.855  1018  1490 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-16 11:17:17.855  1018  1345 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-16 11:17:17.855  1018  1345 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@1358b9ad, pid : 2029, uid : 1001, type : 1
,03-16 11:17:17.865  3430  3520 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 11:17:17.875  2029  2029 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-16 11:17:17.885  3367  3386 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/03/18/16:12:11
,03-16 11:17:17.885  3590  3590 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:17.885  3367  3386 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/03/16/11:17:17
,03-16 11:17:17.885  3590  3590 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:17.885  3346  3346 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,03-16 11:17:17.885  3367  3386 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,03-16 11:17:17.885  3367  3386 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,03-16 11:17:17.895  3367  3387 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-16 11:17:17.905  3346  3346 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,03-16 11:17:17.905  3523  3523 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-16 11:17:17.915  3367  3387 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-16 11:17:17.915  3367  3387 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-16 11:17:17.925  3430  3520 W TRThreadPoolExecutor: Task "b[Get cookie call]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-16 11:17:17.935  3367  3387 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-16 11:17:17.935  3367  3387 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-16 11:17:17.935  3571  3571 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-16 11:17:17.945  3367  3387 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,03-16 11:17:17.945  3367  3387 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,03-16 11:17:17.945  3367  3387 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
03-16 11:17:17.945  3571  3571 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-16 11:17:17.965  3367  3386 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,03-16 11:17:17.985  3346  3346 I com.dropbox.sync.android.a: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,03-16 11:17:17.985  3544  3551 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
03-16 11:17:17.995  1018  3034 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,03-16 11:17:18.005  3523  3523 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-16 11:17:18.015  3571  3571 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-16 11:17:18.025  3367  3387 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-16 11:17:18.035  3239  3239 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-16 11:17:18.055  3571  3571 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-16 11:17:18.065  3523  3523 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-16 11:17:18.065  3523  3523 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
,03-16 11:17:18.075  1808  1808 I SamsungIME: getDebugLevel  : 0x4f4c
,03-16 11:17:18.085  1808  1808 I SamsungIME: KeybaordView init() : load resources
,03-16 11:17:18.085  3367  3387 I DBG_POLICYDM: [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,03-16 11:17:18.165  3346  3346 I com.dropbox.sync.android.ad: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
,03-16 11:17:18.185  3590  3590 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.8.KK_APP
,03-16 11:17:18.185  3405  3421 W art     : Suspending all threads took: 6.438ms
,03-16 11:17:18.195  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2705/cgroup.procs: No such file or directory
03-16 11:17:18.195  1018  1044 W libprocessgroup: failed to open /acct/uid_10044/pid_2460/cgroup.procs: No such file or directory
,03-16 11:17:18.195  1018  1044 W libprocessgroup: failed to open /acct/uid_10145/pid_2799/cgroup.procs: No such file or directory
,03-16 11:17:18.205  1018  1142 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,03-16 11:17:18.215  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:18.215  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:18.215  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:18.215  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:18.215  1808  1808 I SamsungIME: getCurrentKeyboard
03-16 11:17:18.215  1808  1808 I SamsungIME: getTextKeyboard
,03-16 11:17:18.225  3617  3617 E Zygote  : MountEmulatedStorage()
03-16 11:17:18.225  3617  3617 E Zygote  : v2
03-16 11:17:18.225  3617  3617 I libpersona: KNOX_SDCARD checking this for 10062
03-16 11:17:18.225  3617  3617 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:18.225  3617  3617 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:18.225  3617  3617 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:18.235  3617  3617 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:18.235  1018  1142 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3617 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-16 11:17:18.235  3239  3487 D jxcore_app_log: JniHelper::setJavaVM(0xb7ad3450), pthread_self() = -1207711392
,03-16 11:17:18.245  3239  3487 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-16 11:17:18.245  3239  3487 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-16 11:17:18.245  3239  3487 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-16 11:17:18.245  3239  3487 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-16 11:17:18.245  3239  3487 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-16 11:17:18.245  3239  3487 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fb5f1b2 added. We now have 1 listener(s)
,03-16 11:17:18.255  1018  1515 I ActivityManager: Killing 2809:com.samsung.android.sm/1000 (adj 15): empty #31
03-16 11:17:18.255  1808  1808 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-16 11:17:18.255  3239  3487 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,03-16 11:17:18.255  3239  3487 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
,03-16 11:17:18.265  3239  3487 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
03-16 11:17:18.265  3239  3487 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-16 11:17:18.265  3239  3487 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-16 11:17:18.265  3239  3487 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-16 11:17:18.265  3239  3487 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-16 11:17:18.265  3239  3487 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-16 11:17:18.265  3239  3487 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
03-16 11:17:18.265  3239  3487 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-16 11:17:18.265  3239  3487 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-16 11:17:18.265  3239  3487 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-16 11:17:18.265  3239  3487 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-16 11:17:18.265  3239  3487 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-16 11:17:18.265  3239  3487 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-16 11:17:18.265  3239  3487 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2410c2b9 added. We now have 1 listener(s)
,03-16 11:17:18.265  3239  3487 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-16 11:17:18.285  3617  3617 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 11:17:18.285  3239  3487 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-16 11:17:18.285  3617  3617 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:18.285  3239  3487 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-16 11:17:18.285  3239  3487 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-16 11:17:18.285  3239  3487 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-16 11:17:18.285  3239  3487 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-16 11:17:18.295  3239  3487 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-16 11:17:18.295  3405  3522 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-16 11:17:18.295  3405  3522 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 11:17:18.295  3239  3487 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,03-16 11:17:18.305  3239  3487 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-16 11:17:18.305  3239  3487 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-16 11:17:18.305  3239  3487 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-16 11:17:18.305  3239  3487 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-16 11:17:18.305  3239  3487 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-16 11:17:18.305  3239  3487 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-16 11:17:18.305  3239  3487 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-16 11:17:18.305  3239  3487 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-16 11:17:18.305  3239  3487 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-16 11:17:18.305  3239  3487 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-16 11:17:18.315  3239  3239 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 11:17:18.315  3239  3239 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 11:17:18.325  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2809/cgroup.procs: No such file or directory
,03-16 11:17:18.335  1314  3257 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-16 11:17:18.345  3367  3386 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,03-16 11:17:18.355  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-16 11:17:18.355  1314  3257 D Settings_Utils: isSupportVNFestival SM-A500FU XEO
,03-16 11:17:18.355  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,03-16 11:17:18.355  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 11:17:18.355  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 11:17:18.355  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 11:17:18.355  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 11:17:18.355  3239  3239 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-16 11:17:18.355  3367  3386 I DBG_POLICYDM: [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-16 11:17:18.435  3617  3617 I ExternalOEMControlProvider: onCreate
,03-16 11:17:18.455  1018  2954 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.servicemodeapp, hostingType: broadcast
,03-16 11:17:18.455  1018  2954 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:18.455  1018  2954 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:18.455  1018  2954 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:18.455  1018  2954 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:18.465  3571  3571 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
03-16 11:17:18.465  3259  3343 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-16 11:17:18.475  3640  3640 E Zygote  : MountEmulatedStorage()
03-16 11:17:18.475  3640  3640 E Zygote  : v2
03-16 11:17:18.475  3640  3640 I libpersona: KNOX_SDCARD checking this for 1000
03-16 11:17:18.475  3640  3640 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:18.475  3640  3640 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:18.475  1018  2954 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3640 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-16 11:17:18.475  1018  2954 I ActivityManager: Killing 2902:flipboard.boxer.app/u0a99 (adj 15): empty #31
,03-16 11:17:18.475  3640  3640 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:18.475  3640  3640 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:18.475  1018  1030 D SettingsProvider: name = PREVIOUS_SYS_TIME
03-16 11:17:18.475  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 11:17:18.475  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 11:17:18.475  1018  1030 D SettingsProvider: selectionArgs: false
03-16 11:17:18.475  1018  1030 D SettingsProvider: selectionArgs: 10062
03-16 11:17:18.475  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 11:17:18.475  1018  1030 D SettingsProvider: ret = -1
,03-16 11:17:18.485  1018  1030 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,03-16 11:17:18.485  1018  1366 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
03-16 11:17:18.485  1018  1366 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 11:17:18.485  1018  1366 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 11:17:18.485  1018  1366 D SettingsProvider: selectionArgs: false
03-16 11:17:18.485  1018  1366 D SettingsProvider: selectionArgs: 10062
03-16 11:17:18.485  1018  1366 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 11:17:18.485  1018  1366 D SettingsProvider: ret = -1
,03-16 11:17:18.495  1018  1366 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,03-16 11:17:18.495  3571  3571 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-16 11:17:18.495  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 11:17:18.495  3571  3571 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-16 11:17:18.505  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 11:17:18.515  3571  3571 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-16 11:17:18.515  3571  3571 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-16 11:17:18.515  3571  3571 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,03-16 11:17:18.515  3571  3571 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,03-16 11:17:18.525  3640  3640 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:18.525  3640  3640 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:18.525  1018  1369 I ActivityManager: Killing 2208:flipboard.app/u0a98 (adj 15): empty #31
,03-16 11:17:18.545  3390  3390 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-16 11:17:18.545  1018  1369 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,03-16 11:17:18.545  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:18.545  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:18.545  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:18.545  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:18.565  3430  3520 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,03-16 11:17:18.565  1018  1369 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3663 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a,
,03-16 11:17:18.575  3663  3663 E Zygote  : MountEmulatedStorage(),
03-16 11:17:18.575  3663  3663 E Zygote  : v2
03-16 11:17:18.575  3663  3663 I libpersona: KNOX_SDCARD checking this for 10094,
03-16 11:17:18.575  3663  3663 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:18.575  3663  3663 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-16 11:17:18.575  3663  3663 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-16 11:17:18.585  3663  3663 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-16 11:17:18.595   306   306 I art     : Explicit concurrent mark sweep GC freed 8753(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 34.003ms,
,03-16 11:17:18.605  1018  1369 I ActivityManager: Killing 2946:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31,
,03-16 11:17:18.625   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 681us total 19.970ms,
,03-16 11:17:18.625  3663  3663 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 11:17:18.625  3663  3663 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:18.645  3640  3640 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.,
,03-16 11:17:18.645   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 757us total 19.896ms,
,03-16 11:17:18.645  2666  3301 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3301)  
,03-16 11:17:18.655  3390  3390 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-16 11:17:18.665  3390  3390 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
03-16 11:17:18.665  1018  1142 I ActivityManager: Killing 1976:com.android.defcontainer/u0a4 (adj 15): empty #31
,03-16 11:17:18.695  3390  3390 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-16 11:17:18.695   288   288 E SMD     : DCD OFF
,03-16 11:17:18.705  3640  3640 I ServiceMode: received = ACTION_BOOT_COMPLETED
03-16 11:17:18.705  3640  3640 I ServiceMode: setReferenceIsDumpState : 0
,03-16 11:17:18.705  1018  1573 D ActivityManager: startProcessLocked calleePkgName: com.google.android.onetimeinitializer, hostingType: broadcast
,03-16 11:17:18.705  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:18.705  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:18.705  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:18.705  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:18.725  3681  3681 E Zygote  : MountEmulatedStorage(),
,03-16 11:17:18.725  3681  3681 E Zygote  : v2,
03-16 11:17:18.725  3681  3681 I libpersona: KNOX_SDCARD checking this for 10014,
03-16 11:17:18.735  3681  3681 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:18.735  1018  1573 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3681 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,03-16 11:17:18.735  1018  1573 I ActivityManager: Killing 2963:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,03-16 11:17:18.735  3681  3681 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:18.735  3681  3681 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:18.735  3681  3681 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 11:17:18.735  3663  3663 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-16 11:17:18.755  3663  3663 D elm:15183: ELMEngine.ELMEngine( context ).
,03-16 11:17:18.755  3663  3663 D elm:15183: MDMBridge.setEnterpriseBridge()
,03-16 11:17:18.755  1018  3034 D ActivityManager: startProcessLocked calleePkgName: com.wssnps, hostingType: broadcast
,03-16 11:17:18.755  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:18.755  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:18.755  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:18.755  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:18.765  3367  3387 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0],
,03-16 11:17:18.775  3681  3681 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-16 11:17:18.775  3681  3681 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:18.775  1018  3034 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3696 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-16 11:17:18.775  1018  3034 I ActivityManager: Killing 2383:com.sec.modem.settings/1000 (adj 15): empty #31
,03-16 11:17:18.785  3696  3696 E Zygote  : MountEmulatedStorage(),
,03-16 11:17:18.785  3696  3696 E Zygote  : v2,
03-16 11:17:18.785  3696  3696 I libpersona: KNOX_SDCARD checking this for 1000
03-16 11:17:18.785  3696  3696 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:18.785  3696  3696 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-16 11:17:18.785  3367  3387 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false,
,03-16 11:17:18.785  3346  3661 I System.out: Thread-439(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-16 11:17:18.785  1018  1142 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
03-16 11:17:18.785  1018  1142 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
03-16 11:17:18.795  1018  1142 W ActivityManager: userId = 0, bbcId = -10000,
03-16 11:17:18.795  1018  1142 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:18.795  1018  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
03-16 11:17:18.795  3346  3661 I System.out: Thread-439(ApacheHTTPLog):isSBSettingEnabled false
03-16 11:17:18.795  3346  3661 I System.out: Thread-439(ApacheHTTPLog):isShipBuild true
03-16 11:17:18.795  3346  3661 I System.out: Thread-439(ApacheHTTPLog):SMARTBONDING_ENABLED is false,
03-16 11:17:18.795  3346  3661 I System.out: Thread-439(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-16 11:17:18.795  3696  3696 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-16 11:17:18.795   275   872 D EnterpriseController: uids 10092
03-16 11:17:18.795   275   872 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-16 11:17:18.795   275   872 D Netd    : getNetworkForDns: using netid 502 for uid 10092
03-16 11:17:18.795  3696  3696 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:18.795  3663  3663 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.,
,03-16 11:17:18.815  1428  1428 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,03-16 11:17:18.835  3696  3696 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:18.835  3663  3663 D elm:15183: ElmAgentService : onCreate()
,03-16 11:17:18.835  3696  3696 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:18.855  3663  3705 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,03-16 11:17:18.855  3663  3663 D elm:15183: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,03-16 11:17:18.855  3663  3663 D elm:15183: BootCompletedState : startBootCompleted() call
,03-16 11:17:18.875  3663  3663 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,03-16 11:17:18.885  3663  3663 I elm:15183: Get License : 0
03-16 11:17:18.885  3663  3663 D elm:15183: ElmAgentService : onDestroy().
,03-16 11:17:18.885  1018  1366 I ActivityManager: Killing 2978:com.sec.knox.bridge/1000 (adj 15): empty #31
,03-16 11:17:18.905  3681  3681 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
,03-16 11:17:18.905  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.onetimeinitializer, calleePkgName: com.google.android.onetimeinitializer
,03-16 11:17:18.905  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,03-16 11:17:18.905  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:18.905  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 11:17:18.905  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,03-16 11:17:18.925  1428  1428 V EmergencyMode: [EmergencyBase] setBootTime
,03-16 11:17:18.925  3681  3723 V OneTimeService: OneTimeService.onHandleIntent
,03-16 11:17:18.935  1428  1428 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
,03-16 11:17:18.935  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.factory.camera, hostingType: broadcast
,03-16 11:17:18.935  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:18.935  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:18.935  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:18.935  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:18.945   275   872 D EnterpriseController: uids 10057,
,03-16 11:17:18.945   275   872 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-16 11:17:18.945   275   872 D Netd    : getNetworkForDns: using netid 502 for uid 10057
,03-16 11:17:18.965  3696  3696 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
,03-16 11:17:18.965  3696  3696 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
03-16 11:17:18.965  3729  3729 E Zygote  : MountEmulatedStorage()
,03-16 11:17:18.965  3729  3729 E Zygote  : v2
03-16 11:17:18.965  3729  3729 I libpersona: KNOX_SDCARD checking this for 1000
03-16 11:17:18.965  3729  3729 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:18.965  3729  3729 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-16 11:17:18.965  1018  1030 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3729 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-16 11:17:18.975  3729  3729 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:18.975  3729  3729 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:18.985  1018  1573 D ActivityManager: startService callerProcessName:com.wssnps, calleePkgName: com.wssnps
03-16 11:17:18.985  1018  1573 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-16 11:17:18.985  1018  1573 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:18.985  1018  1573 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:18.985  1018  1573 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-16 11:17:18.985  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-16 11:17:18.985  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,03-16 11:17:18.985  3696  3696 D NPS_WSSNPS: [] Service onCreate!!
,03-16 11:17:18.995  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:18.995  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:18.995  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-16 11:17:18.995  1018  1490 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,03-16 11:17:18.995  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:18.995  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:18.995  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:18.995  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:19.015  3729  3729 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 11:17:19.015  3729  3729 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:19.015  3738  3738 E Zygote  : MountEmulatedStorage(),
03-16 11:17:19.015  3738  3738 E Zygote  : v2,
03-16 11:17:19.015  3738  3738 I libpersona: KNOX_SDCARD checking this for 1000
03-16 11:17:19.015  3738  3738 I libpersona: KNOX_SDCARD not a persona,
,03-16 11:17:19.015  3738  3738 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-16 11:17:19.025  3738  3738 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-16 11:17:19.025  3738  3738 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-16 11:17:19.025  1018  1490 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=3738 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
03-16 11:17:19.025  1018  1573 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:19.025  1018  1573 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-16 11:17:19.025  1018  1573 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:19.025  1018  1573 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0,
03-16 11:17:19.025  1018  1573 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-16 11:17:19.055  1018  1142 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-16 11:17:19.055  1018  1142 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,03-16 11:17:19.055  3696  3752 D NPS_WSSNPS: [] NpsServiceTask Start
,03-16 11:17:19.055  3738  3738 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:19.055  3738  3738 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:19.055  1018  1142 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:19.055  1018  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:19.055  1018  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-16 11:17:19.065  1018  1044 W libprocessgroup: failed to open /acct/uid_10099/pid_2902/cgroup.procs: No such file or directory
03-16 11:17:19.065  1018  1044 W libprocessgroup: failed to open /acct/uid_10098/pid_2208/cgroup.procs: No such file or directory
,03-16 11:17:19.065  3696  3696 D NPS_WSSNPS: [50.150621] smlDBHelper
,03-16 11:17:19.085  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2946/cgroup.procs: No such file or directory
,03-16 11:17:19.085  1018  1044 W libprocessgroup: failed to open /acct/uid_10004/pid_1976/cgroup.procs: No such file or directory
,03-16 11:17:19.095  1018  1044 W libprocessgroup: failed to open /acct/uid_10152/pid_2963/cgroup.procs: No such file or directory
03-16 11:17:19.095  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2383/cgroup.procs: No such file or directory
03-16 11:17:19.095  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2978/cgroup.procs: No such file or directory
,03-16 11:17:19.095  1018  2954 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-16 11:17:19.095  1018  2954 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,03-16 11:17:19.105  3696  3696 I NPS_WSSNPS: [50.150621] AsyncBulkFlagCheck
,03-16 11:17:19.105  1018  2954 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:19.105  1018  2954 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:19.105  1018  2954 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-16 11:17:19.115  3696  3762 I NPS_WSSNPS: [50.150621] IsRemain_AsyncBulkCheck
,03-16 11:17:19.125  3405  3405 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-16 11:17:19.135  3696  3762 I NPS_WSSNPS: [50.150621] IsRemain_Asyncing nothing
,03-16 11:17:19.135  3696  3762 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,03-16 11:17:19.135  1018  1366 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-16 11:17:19.135  1018  1366 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:19.135  1018  1366 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 11:17:19.135  1018  1366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-16 11:17:19.145  3738  3738 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 11:17:19.145  3696  3696 D NPS_WSSNPS: [50.150621] Service onDestroy
,03-16 11:17:19.145  3696  3696 I NPS_WSSNPS: [50.150621] smlBRConfigurationDelete
,03-16 11:17:19.145  3696  3696 I NPS_WSSNPS: [50.150621] smlBRMessageDelete
,03-16 11:17:19.145  3696  3696 I NPS_WSSNPS: [50.150621] smlBREmailDelete
,03-16 11:17:19.155  3696  3696 I NPS_WSSNPS: [50.150621] smlBRNetworkDelete
03-16 11:17:19.155  3696  3696 I NPS_WSSNPS: [50.150621] smlBRCallLogDelete
,03-16 11:17:19.155  3696  3696 I NPS_WSSNPS: [50.150621] smlBRMiniDiaryDelete
,03-16 11:17:19.155  3696  3696 I NPS_WSSNPS: [50.150621] smlBRPenMemoMDelete
,03-16 11:17:19.155  3696  3696 I NPS_WSSNPS: [50.150621] smlBRSMemoDelete
03-16 11:17:19.155  3696  3696 I NPS_WSSNPS: [50.150621] verifier installed? false
,03-16 11:17:19.155  3696  3696 I NPS_WSSNPS: [50.150621] cpuBooster release : false
,03-16 11:17:19.155  3696  3696 D NPS_WSSNPS: [50.150621] dsServerSocket close
,03-16 11:17:19.155  1018  1030 I ActivityManager: Killing 2999:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,03-16 11:17:19.175  3729  3729 I CameraApp: CameraApp.onCreate()... mFeature : null
,03-16 11:17:19.175  3729  3729 I testFeature: Feature.Feature(context)
03-16 11:17:19.175  3729  3729 I testFeature: Feature.readInternalDefaultXml()
03-16 11:17:19.175  3729  3729 I testFeature: ResetFeatureValue
,03-16 11:17:19.175  3729  3729 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
03-16 11:17:19.175  3729  3729 I CameraApp: CameraApp.getAppFeature()...
,03-16 11:17:19.175  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,03-16 11:17:19.185  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:19.185  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:19.185  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:19.185  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:19.195  3405  3405 I System.out: YouTube MDX: MDX video stage moved to NEW
,03-16 11:17:19.195  3405  3405 I System.out: YouTube MDX: MDX video player state moved to UNSTARTED
,03-16 11:17:19.195  3405  3405 I System.out: YouTube MDX: MDX ad player state moved to UNSTARTED
,03-16 11:17:19.195  3771  3771 E Zygote  : MountEmulatedStorage(),
03-16 11:17:19.195  3771  3771 E Zygote  : v2
03-16 11:17:19.195  3239  3638 W jxcore-log: Initializing JXcore engine
,03-16 11:17:19.195  3239  3638 W jxcore-log: JXcore engine is ready
03-16 11:17:19.195  3771  3771 I libpersona: KNOX_SDCARD checking this for 10100
,03-16 11:17:19.195  3771  3771 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:19.205  3771  3771 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-16 11:17:19.205  1018  1031 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3771 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
03-16 11:17:19.205  3771  3771 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:19.205  3771  3771 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 11:17:19.205  3653  3653 I dex2oat : ----------------------------------------------------
03-16 11:17:19.205  3653  3653 I dex2oat : <SS>: S T A R T I N G . . .
03-16 11:17:19.205  3653  3653 I dex2oat : <SS>: Zip is absent. Canceled.
03-16 11:17:19.205  3653  3653 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1241403075.jar --oat-fd=31 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads-1241403075.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-16 11:17:19.215  1018  1031 I ActivityManager: Killing 2335:com.android.mms/u0a46 (adj 15): empty #31
,03-16 11:17:19.235  3771  3771 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:19.235  3771  3771 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:19.245  2686  2763 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-16 11:17:19.265  1018  1345 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-16 11:17:19.265  1018  1345 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,03-16 11:17:19.275  1018  1345 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:19.275  1018  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:19.275  1018  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-16 11:17:19.295  1961  1961 E audit   : type=1400 msg=audit(1458123439.295:205): avc:  denied  { ioctl } for  pid=3638 comm="Thread-434" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-16 11:17:19.295  1961  1961 E audit   :  SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:19.295  1961  1961 E audit   : type=1300 msg=audit(1458123439.295:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9c5fa8b8 items=0 ppid=306 ppcomm=main pid=3638 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-434" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-16 11:17:19.295  1961  1961 E audit   : type=1320 msg=audit(1458123439.295:205): 
,03-16 11:17:19.325  3239  3638 W jxcore-log: Starting JXcore engine
,03-16 11:17:19.355  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-16 11:17:19.355  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-16 11:17:19.355  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 11:17:19.355  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 11:17:19.355  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 11:17:19.355  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 11:17:19.365  1018  1366 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
03-16 11:17:19.365  1018  1366 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-16 11:17:19.385  1018  1366 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:19.385  1018  1366 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:19.385  1018  1366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-16 11:17:19.395  1018  1573 D ActivityManager: startProcessLocked calleePkgName: com.samsung.klmsagent, hostingType: broadcast
,03-16 11:17:19.395  2583  2583 I Hs20UtilService: Starting #2
,03-16 11:17:19.395  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:19.395  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:19.395  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:19.395  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:19.405  2583  2598 I Hs20UtilService: Message received 5003
,03-16 11:17:19.405  3798  3798 E Zygote  : MountEmulatedStorage()
,03-16 11:17:19.415  3798  3798 E Zygote  : v2
,03-16 11:17:19.415  3798  3798 I libpersona: KNOX_SDCARD checking this for 10019
03-16 11:17:19.415  3798  3798 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:19.415  1018  1573 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3798 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a,
,03-16 11:17:19.415  3798  3798 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:19.415  3798  3798 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-16 11:17:19.415  3798  3798 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:19.425  1645  1732 I art     : Explicit concurrent mark sweep GC freed 2949(120KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 803us total 26.964ms
,03-16 11:17:19.425  3771  3771 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
,03-16 11:17:19.435  3771  3771 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,03-16 11:17:19.435  1018  2954 D ActivityManager: startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
,03-16 11:17:19.445  1018  2954 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:19.445  1018  2954 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:19.445  1018  2954 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:19.445  1018  2954 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:19.445  3798  3798 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:19.445  3798  3798 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:19.455  3239  3638 W jxcore-log: Platform android
03-16 11:17:19.455  3239  3638 W jxcore-log: 
03-16 11:17:19.455  3239  3638 W jxcore-log: Process ARCH arm
03-16 11:17:19.455  3239  3638 W jxcore-log: 
03-16 11:17:19.455  3814  3814 E Zygote  : MountEmulatedStorage()
03-16 11:17:19.455  3814  3814 E Zygote  : v2
03-16 11:17:19.455  3814  3814 I libpersona: KNOX_SDCARD checking this for 10101
03-16 11:17:19.455  3814  3814 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:19.465  1018  2954 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3814 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 11:17:19.465  3814  3814 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-16 11:17:19.465  1018  2954 I ActivityManager: Killing 3061:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,03-16 11:17:19.465  3814  3814 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:19.465  3814  3814 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 11:17:19.475  3259  3343 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,03-16 11:17:19.495  3814  3814 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:19.495  3814  3814 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:19.535  1018  1044 E libprocessgroup: failed to kill 1 processes for processgroup 2335
03-16 11:17:19.535  1018  1044 W libprocessgroup: failed to open /acct/uid_1101/pid_2999/cgroup.procs: No such file or directory
,03-16 11:17:19.545  1018  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 11:17:19.545  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:19.545  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 11:17:19.545  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-16 11:17:19.555  1018  1345 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-16 11:17:19.555  1018  1345 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
03-16 11:17:19.555  1018  1345 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:19.555  1018  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:19.555  1018  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-16 11:17:19.605  1018  1044 W libprocessgroup: failed to open /acct/uid_10157/pid_3061/cgroup.procs: No such file or directory
,03-16 11:17:19.615  3798  3798 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Mar 16 11:17:19 GMT+01:00 2016
,03-16 11:17:19.625  1018  1574 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,03-16 11:17:19.625  1018  1574 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-16 11:17:19.625  1018  1574 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:19.625  1018  1574 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:19.625  1018  1574 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-16 11:17:19.625  3798  3798 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-16 11:17:19.635  1018  1345 D ActivityManager: startProcessLocked calleePkgName: com.android.managedprovisioning, hostingType: broadcast
,03-16 11:17:19.635  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:19.635  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:19.635  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:19.635  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:19.655  3838  3838 E Zygote  : MountEmulatedStorage(),
03-16 11:17:19.655  3838  3838 E Zygote  : v2
03-16 11:17:19.655  3838  3838 I libpersona: KNOX_SDCARD checking this for 10022
03-16 11:17:19.655  3798  3798 I KLMS-2.5.183: : KLMSIntentService(): onCreate(),
03-16 11:17:19.655  3838  3838 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:19.655  3838  3838 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:19.655  3838  3838 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:19.665  1018  1345 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3838 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
,03-16 11:17:19.665  3798  3798 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-16 11:17:19.665  3838  3838 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:19.675  3457  3457 I RlzPingService: Setting next ping for 1458728239687
,03-16 11:17:19.675  3798  3798 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-16 11:17:19.695  3798  3837 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-16 11:17:19.705  3838  3838 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:19.705  3838  3838 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:19.705  3239  3638 I jxcore-log: JXcore Cordova bridge is ready!
03-16 11:17:19.705  3239  3638 I jxcore-log: 
,03-16 11:17:19.705  3239  3638 W jxcore-log: JXcore engine is started
,03-16 11:17:19.725  3239  3487 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-16 11:17:19.735  3798  3837 I KLMS-2.5.183: : KLMSIntentService(): BOOT_COMPLETED
,03-16 11:17:19.745  3239  3638 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-16 11:17:19.745  3239  3638 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-16 11:17:19.755  3239  3239 I chromium: [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,03-16 11:17:19.755  1018  1345 D FocusedStackFrame: Set to : 0
,03-16 11:17:19.765  1018  1345 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 11:17:19.765  1018  1345 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,03-16 11:17:19.765  1018  1345 D InputDispatcher: Focused application set to: xxxx
,03-16 11:17:19.765  1018  1345 D InputDispatcher: Focus left window: 3239
,03-16 11:17:19.765  1018  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-16 11:17:19.765  1018  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-16 11:17:19.775   258  1173 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (335 us)
,03-16 11:17:19.795  1314  3257 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-16 11:17:19.815  3239  3487 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 53ms. Plugin should use CordovaInterface.getThreadPool().
03-16 11:17:19.815  1018  1031 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-16 11:17:19.815  1018  1031 W ActivityManager: mDVFSHelper.acquire()
,03-16 11:17:19.825  1018  1031 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-16 11:17:19.825  1018  1031 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-16 11:17:19.825  1018  1031 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-16 11:17:19.835  1018  1574 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.accesscontrol, hostingType: broadcast
,03-16 11:17:19.835  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:19.845  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:19.845  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:19.845  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:19.855  3653  3653 I dex2oat : dex2oat took 645.221ms (threads: 4)
,03-16 11:17:19.855  3858  3858 E Zygote  : MountEmulatedStorage()
,03-16 11:17:19.855  3858  3858 E Zygote  : v2
03-16 11:17:19.855  3858  3858 I libpersona: KNOX_SDCARD checking this for 1000
03-16 11:17:19.855  3858  3858 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:19.855  3858  3858 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-16 11:17:19.855  1018  1574 I ActivityManager: Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3858 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-16 11:17:19.865  3858  3858 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:19.865  1018  1574 I ActivityManager: Killing 3083:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
,03-16 11:17:19.865  3858  3858 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:19.865  1491  1491 D Launcher: onRestart, Launcher: 918130630
,03-16 11:17:19.865  1491  1491 D Launcher: onStart, Launcher: 918130630
03-16 11:17:19.865  1491  1491 D Launcher.HomeView: onStart
,03-16 11:17:19.875  1491  1491 D Launcher: onResume, Launcher: 918130630
,03-16 11:17:19.875  1018  1515 D SettingsProvider: name = kids_home_mode
03-16 11:17:19.875  1018  1515 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 11:17:19.875  1018  1515 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 11:17:19.875  1018  1515 D SettingsProvider: selectionArgs: false
03-16 11:17:19.875  1018  1515 D SettingsProvider: selectionArgs: 10007
03-16 11:17:19.875  1018  1515 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 11:17:19.875  1018  1515 D SettingsProvider: ret = -1
,03-16 11:17:19.875  1018  1574 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,03-16 11:17:19.875  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-16 11:17:19.875  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:19.875  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:19.875  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:19.875  1491  1491 D Launcher.HomeView: onResume,
,03-16 11:17:19.895  1018  1574 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3875 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-16 11:17:19.895  1018  1574 I ActivityManager: Killing 3112:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,03-16 11:17:19.905  3875  3875 E Zygote  : MountEmulatedStorage(),
03-16 11:17:19.905  3875  3875 E Zygote  : v2
03-16 11:17:19.905  1018  1031 D ActivityManager: bindService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube, action: null
03-16 11:17:19.905  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0,
03-16 11:17:19.905  3875  3875 I libpersona: KNOX_SDCARD checking this for 1000
03-16 11:17:19.905  3875  3875 I libpersona: KNOX_SDCARD not a persona,
03-16 11:17:19.905  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:19.905  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:19.905  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube,
03-16 11:17:19.905  1491  1491 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-16 11:17:19.905  3875  3875 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-16 11:17:19.905  3858  3858 D TimaKeyStoreProvider: TimaSignature is unavailable,
,03-16 11:17:19.905  3858  3858 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:19.915  1808  3625 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619,
,03-16 11:17:19.915  3875  3875 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:19.915  3875  3875 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:19.925  1491  1491 D MenuAppsGridFragment: onResume
,03-16 11:17:19.925  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-16 11:17:19.925  1018  1018 D SensorService: [SO] activate (ident=0xb83034f0, enabled=0)
,03-16 11:17:19.925  1018  1031 D ActivityManager: handle home activity for 0
,03-16 11:17:19.925  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-16 11:17:19.935  1018  1031 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-16 11:17:19.935  1018  1031 D KnoxTimeoutHandler: post home show event for user 0
03-16 11:17:19.935  1018  1031 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-16 11:17:19.935  1018  1031 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-16 11:17:19.935  1018  1031 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-16 11:17:19.935  3875  3875 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:19.935  3875  3875 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:19.945   258   258 I SurfaceFlinger: id=12 createSurf (720x1280),1 flag=4, Mauncher
,03-16 11:17:19.945  3798  3798 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-16 11:17:19.955   257   511 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-16 11:17:19.955   257   511 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:17:19.955  1018  1018 D SensorManager: unregisterListener ::   
,03-16 11:17:19.955  1018  1018 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-16 11:17:19.955  1018  1018 D SensorService: [SO] changed settle time [0]
,03-16 11:17:19.955  1018  1018 D SensorService: [SO] setDelay [200000000]
03-16 11:17:19.955  1018  1018 D SensorService: [SO] activate (ident=0xb83034f0, enabled=1)
03-16 11:17:19.955  1018  1018 D SensorService: [SO] AR_init
,03-16 11:17:19.955  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-16 11:17:19.955  3405  3405 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache,
,03-16 11:17:19.955  1018  1018 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
03-16 11:17:19.965  1018  1018 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-16 11:17:19.965  1018  1018 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-16 11:17:19.965  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
03-16 11:17:19.965  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-16 11:17:19.965  1018  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-16 11:17:20.005  1018  1044 W libprocessgroup: failed to open /acct/uid_10048/pid_3083/cgroup.procs: No such file or directory
,03-16 11:17:20.005  1018  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-16 11:17:20.015  1018  1490 D InputDispatcher: Focus entered window: 1491
,03-16 11:17:20.025  1491  1491 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-16 11:17:20.035  1491  1491 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-16 11:17:20.035  1018  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 11:17:20.035  1018  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-16 11:17:20.035  1018  2954 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-16 11:17:20.045  1018  1044 W libprocessgroup: failed to open /acct/uid_10159/pid_3112/cgroup.procs: No such file or directory
,03-16 11:17:20.055  1187  1187 I StatusBar: Icon Only
,03-16 11:17:20.055  1187  1187 D PanelView: There is/are notification(s) 
,03-16 11:17:20.055  1018  3898 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 11:17:20.055  3239  3239 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-16 11:17:20.055  1808  1808 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-16 11:17:20.085  1018  1515 D SettingsProvider: name = access_control_enabled
,03-16 11:17:20.095  1018  1573 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,03-16 11:17:20.095  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:20.095  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:20.095  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:20.095  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:20.115  3875  3875 E MTPRx   : In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,03-16 11:17:20.115  1491  1491 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3ad601d5 time:42221
,03-16 11:17:20.125  1018  1573 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3902 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:17:20.125  1018  1573 I ActivityManager: Killing 3135:com.sec.usbsettings/1000 (adj 15): empty #31
03-16 11:17:20.125  1018  1050 D PersonaManager: isKioskContainerExistOnDevice
,03-16 11:17:20.135  3902  3902 E Zygote  : MountEmulatedStorage()
03-16 11:17:20.135  3902  3902 E Zygote  : v2
03-16 11:17:20.135  3902  3902 I libpersona: KNOX_SDCARD checking this for 10069
,03-16 11:17:20.135  3902  3902 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:20.135  3902  3902 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:20.145  3902  3902 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-16 11:17:20.145  3902  3902 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-16 11:17:20.155  1018  1042 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-16 11:17:20.165   306   306 I art     : Explicit concurrent mark sweep GC freed 8741(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 7.481ms total 41.205ms
,03-16 11:17:20.165  1018  1345 D SecContentProvider2: uri = 14 selection = getSealedState
03-16 11:17:20.165  1018  1345 D SecContentProvider2: mCursor = null
,03-16 11:17:20.175  1018  1369 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
,03-16 11:17:20.175  1018  1369 D SecContentProvider2: mCursor = null
,03-16 11:17:20.185  3875  3875 V MTPRx   : sealedState: false
03-16 11:17:20.185  3875  3875 V MTPRx   : sealedUsbMassStorageState: false
,03-16 11:17:20.185  3902  3902 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:20.185  3902  3902 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:20.185   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 17.989ms
,03-16 11:17:20.205   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 645us total 20.393ms
,03-16 11:17:20.205  1018  1490 D SettingsProvider: name = mtp_usb_connection_status
,03-16 11:17:20.215  1018  1050 I ActivityManager: Displayed Component not be shown by security: +398ms
,03-16 11:17:20.225  1018  1573 D SettingsProvider: name = media_player_mode
,03-16 11:17:20.225  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 11:17:20.235  1018  2954 D SettingsProvider: name = mtp_usb_conditions_met
,03-16 11:17:20.235  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 11:17:20.245  1018  1490 D SettingsProvider: name = mtp_running_status
,03-16 11:17:20.255  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 11:17:20.255  1018  1574 D SettingsProvider: name = media_mount_count
,03-16 11:17:20.275  1018  1031 D SettingsProvider: name = mtp_sync_alive
,03-16 11:17:20.285  1018  1366 D SettingsProvider: name = sdcard_launch
,03-16 11:17:20.285  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 11:17:20.285  1018  1490 D SettingsProvider: name = boot_time_connected
,03-16 11:17:20.295  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 11:17:20.295  1018  1030 I art     : Explicit concurrent mark sweep GC freed 27257(1467KB) AllocSpace objects, 2(38KB) LOS objects, 33% free, 29MB/44MB, paused 2.832ms total 197.847ms
,03-16 11:17:20.305  1018  1366 D SettingsProvider: name = mtp_open_session
,03-16 11:17:20.305  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 11:17:20.315  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3135/cgroup.procs: No such file or directory
,03-16 11:17:20.315  3346  3661 I System.out: pool-10-thread-1 calls detatch()
03-16 11:17:20.315  1018  1045 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,03-16 11:17:20.325  1018  1045 W ActivityManager: mDVFSHelper.release()
,03-16 11:17:20.325  1018  1045 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-16 11:17:20.325  3902  3902 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,03-16 11:17:20.325  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 11:17:20.335  1018  1515 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 11:17:20.335  1314  3257 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,03-16 11:17:20.335  1018  1515 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:20.335  1018  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:20.335  1018  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-16 11:17:20.335  1314  3257 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,03-16 11:17:20.335  1314  3257 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
,03-16 11:17:20.335  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 11:17:20.345  3544  3544 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-16 11:17:20.345  3544  3544 I PCWCLIENTTRACE_PushUtil: sales region : global
03-16 11:17:20.345  3544  3544 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-16 11:17:20.345  3544  3544 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.BOOT_COMPLETED
03-16 11:17:20.345  3544  3544 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Version: 4.82
03-16 11:17:20.345  3544  3544 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Push type: [SPP, GCM]
,03-16 11:17:20.355  1018  1042 D SensorService: [SO] currT = 42460123160, prevT = 42000068785, diff = 460054375, [0.134 0.402 10.132]
,03-16 11:17:20.355  1018  1042 D SensorService: [SO] 0.134 0.402 10.132
03-16 11:17:20.355  1018  1042 D SensorService: [SO] [100 -> 255]
,03-16 11:17:20.355  1018  1031 D CountryDetector: No listener is left
,03-16 11:17:20.375  1018  1345 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 11:17:20.375  1018  1345 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:20.375  1018  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 11:17:20.375  1018  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-16 11:17:20.375  3544  3544 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,03-16 11:17:20.385  1018  1366 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 11:17:20.385  1018  1366 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-16 11:17:20.405  3544  3544 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-16 11:17:20.405  3544  3544 I ReactiveServiceManager: Supported : 1
,03-16 11:17:20.405  1018  1366 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,03-16 11:17:20.405  1018  1366 D QSEECOMAPI: : App is not loaded in QSEE
,03-16 11:17:20.465  1018  1366 D QSEECOMAPI: : Loaded image: APP id = 9
,03-16 11:17:20.475  1018  1366 D QSEECOMAPI: : QSEECom_dealloc_memory 
,03-16 11:17:20.475  1018  1366 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 9
,03-16 11:17:20.475  1018  1366 E terrier : handleString: Failed to handle string(-4)
,03-16 11:17:20.475  1018  1366 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,03-16 11:17:20.475  3544  3544 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-16 11:17:20.475  3544  3544 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
03-16 11:17:20.475  3544  3544 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-16 11:17:20.475  3544  3544 I PCWCLIENTTRACE_PushUtil: sales region : global
03-16 11:17:20.475  3544  3544 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-16 11:17:20.475  3544  3544 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,03-16 11:17:20.485  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
,03-16 11:17:20.485  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:20.485  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:20.485  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:20.485  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:20.495  3927  3927 E Zygote  : MountEmulatedStorage()
03-16 11:17:20.495  3927  3927 I libpersona: KNOX_SDCARD checking this for 10031
03-16 11:17:20.495  3927  3927 E Zygote  : v2
03-16 11:17:20.495  3927  3927 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:20.495  3927  3927 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-16 11:17:20.495  3927  3927 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:20.495  3927  3927 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-16 11:17:20.495  1018  1031 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3927 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
03-16 11:17:20.495  1018  1031 I ActivityManager: Killing 3099:com.sec.dsm.system/1000 (adj 15): empty #31
,03-16 11:17:20.535  3927  3927 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:20.535  3927  3927 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:20.555  3814  3943 I Gmail   : getAccountsCursor
,03-16 11:17:20.555  3927  3927 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-16 11:17:20.555  1018  1490 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,03-16 11:17:20.555  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0,
,03-16 11:17:20.565  2666  2666 D FactoryTestApp: [DummyFtClient$onDestroy](2666) Destroy DummyFtClient service
,03-16 11:17:20.565  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3099/cgroup.procs: No such file or directory
,03-16 11:17:20.565  2666  2666 D FactoryTestApp: [Support$Values.getString](2666) id=MODEL_COMMUNICATION_MODE, value=gsm
03-16 11:17:20.565  2666  2666 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2666) mConnectionMode = gsm
03-16 11:17:20.565  2666  2666 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2666) RUNNING_FTCLIENT : false
03-16 11:17:20.565  2666  2666 D FactoryTestApp: [DummyFtClient$onDestroy](2666) kill process
03-16 11:17:20.565  2666  2666 I Process : Sending signal. PID: 2666 SIG: 9
03-16 11:17:20.565  1856  1856 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:17:20.575  1018  3034 I ActivityManager: Process com.sec.factory (pid 2666)(adj 0) has died(44,1135)
,03-16 11:17:20.585  3814  3814 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-16 11:17:20.635  1018  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{49e8151 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t11} time:42740
,03-16 11:17:20.635  1018  1045 I ActivityManager: Killing 3155:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,03-16 11:17:20.635   258   853 I SurfaceFlinger: id=11 Removed NainActivit (7/8)
,03-16 11:17:20.635   258   430 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-16 11:17:20.655  1018  1018 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,03-16 11:17:20.665  1018  1018 I ActivityManager: Killing 1576:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,03-16 11:17:20.665  1018  1490 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-16 11:17:20.675  1018  1574 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-16 11:17:20.685  1018  2954 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,03-16 11:17:20.685  1018  3034 I AudioService: getStreamVolume 3 index 0
,03-16 11:17:20.685  1018  2954 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,03-16 11:17:20.685  1018  2954 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:20.695  1018  2954 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 11:17:20.695  1018  2954 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-16 11:17:20.715  1018  1515 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,03-16 11:17:20.715  1018  1515 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,03-16 11:17:20.715  1018  1515 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:20.715  1018  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:20.715  1018  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-16 11:17:20.725  1018  1366 D PowerManagerService: [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1187 (0x0)
,03-16 11:17:20.735  3259  3343 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,03-16 11:17:20.755  1018  1574 I ActivityManager: Killing 3047:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,03-16 11:17:20.765  3239  3239 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3239
,03-16 11:17:20.765  1018  1515 W ActivityManager: Duplicate finish request for ActivityRecord{3ff1f3d6 u0 com.test.thalitest/.MainActivity t12 f}
,03-16 11:17:20.765  1018  1345 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 11:17:20.765  1018  1345 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-16 11:17:20.765  3239  3239 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@a8d76fe that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 11:17:20.765  3239  3239 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@a8d76fe that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 11:17:20.765  3239  3239 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@1ef13e5f that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 11:17:20.765  3239  3239 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@1ef13e5f that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-16 11:17:20.765  3239  3239 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 11:17:20.775  1018  1018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,03-16 11:17:20.775  1018  1018 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
03-16 11:17:20.775  1018  1018 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 11:17:20.775  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,03-16 11:17:20.775  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:20.775  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:20.775  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:20.775  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:20.795  3956  3956 E Zygote  : MountEmulatedStorage(),
03-16 11:17:20.795  3956  3956 E Zygote  : v2
03-16 11:17:20.795  3956  3956 I libpersona: KNOX_SDCARD checking this for 1000
03-16 11:17:20.795  3956  3956 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:20.795  3956  3956 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-16 11:17:20.795  3956  3956 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-16 11:17:20.795  3956  3956 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:20.795  3814  3954 E Gmail   : Error finding the version of the Email provider.....,
03-16 11:17:20.795  3814  3954 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-16 11:17:20.795  3814  3954 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
03-16 11:17:20.795  3814  3954 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
03-16 11:17:20.795  3814  3954 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
03-16 11:17:20.795  3814  3954 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-16 11:17:20.795  3814  3954 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 11:17:20.795  3814  3954 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
03-16 11:17:20.795  3814  3954 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-16 11:17:20.795  3814  3954 W EmailMigration: We do not support migrating this version of the Email provider.,
,03-16 11:17:20.805  1018  1018 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3956 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-16 11:17:20.805  1018  1573 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
03-16 11:17:20.805  1018  1573 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,03-16 11:17:20.805  1018  1573 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:20.805  1018  1573 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:20.805  1018  1573 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-16 11:17:20.815  3814  3965 I Gmail   : getAccountsCursor
,03-16 11:17:20.815  1018  1031 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,03-16 11:17:20.815  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-16 11:17:20.815  3956  3956 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:20.815  3956  3956 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:20.825  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3155/cgroup.procs: No such file or directory
,03-16 11:17:20.825  1018  1044 W libprocessgroup: failed to open /acct/uid_10072/pid_1576/cgroup.procs: No such file or directory
,03-16 11:17:20.825  1856  1856 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:17:20.825  3927  3927 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
,03-16 11:17:20.845  1018  1044 W libprocessgroup: failed to open /acct/uid_10085/pid_3047/cgroup.procs: No such file or directory
,03-16 11:17:20.865  3927  3927 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
,03-16 11:17:20.875  1018  1573 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
03-16 11:17:20.875  1018  1573 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-16 11:17:20.875  1018  1573 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:20.875  1018  1573 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:20.875  1018  1573 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-16 11:17:20.875  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
,03-16 11:17:20.875  1018  1030 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-16 11:17:20.875  1018  1345 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-16 11:17:20.875  1018  1345 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-16 11:17:20.885  1856  1856 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:17:20.895  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.syncadapters.contacts
03-16 11:17:20.895  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,03-16 11:17:20.895  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:20.895  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:20.895  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,03-16 11:17:20.905  1018  1573 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,03-16 11:17:20.905  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:20.905  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:20.905  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:20.905  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:20.905   257   511 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-16 11:17:20.905   257   511 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:17:20.905  3405  3405 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-16 11:17:20.905   257   511 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-16 11:17:20.905  3956  3956 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
03-16 11:17:20.905   257   511 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:17:20.915  3405  3405 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-16 11:17:20.925  3987  3987 E Zygote  : MountEmulatedStorage()
03-16 11:17:20.925  1018  1573 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3987 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
03-16 11:17:20.925  3987  3987 E Zygote  : v2
03-16 11:17:20.925  3987  3987 I libpersona: KNOX_SDCARD checking this for 10104
03-16 11:17:20.925  3987  3987 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:20.925  3987  3987 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-16 11:17:20.925  1018  1369 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,03-16 11:17:20.925  1018  1369 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
03-16 11:17:20.925   257   511 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-16 11:17:20.925   257   511 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:17:20.925  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:20.925  3405  3405 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-16 11:17:20.925  1018  1369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:20.925  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
03-16 11:17:20.925  3987  3987 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:20.925  3987  3987 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 11:17:20.935  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-16 11:17:20.935  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:20.935  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:20.935  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-16 11:17:20.935  1018  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-16 11:17:20.935  1018  1490 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-16 11:17:20.935  1645  3985 I GoogleHttpClient: GMS http client unavailable, use old client
,03-16 11:17:20.935  3814  3978 I Gmail   : Observing account changes for notifications
,03-16 11:17:20.945  1018  1573 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,03-16 11:17:20.945  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:20.945  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:20.945  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:20.945  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:20.955  3987  3987 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:20.955  3987  3987 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:20.955  4004  4004 E Zygote  : MountEmulatedStorage(),
03-16 11:17:20.955  1018  1573 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=4004 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-16 11:17:20.955  4004  4004 E Zygote  : v2,
,03-16 11:17:20.965  4004  4004 I libpersona: KNOX_SDCARD checking this for 1000,
03-16 11:17:20.965  4004  4004 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:20.965  4004  4004 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:20.965  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,03-16 11:17:20.965  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,03-16 11:17:20.965  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:20.965  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:20.965  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-16 11:17:20.965  4004  4004 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:20.975  4004  4004 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:20.985  1018  1345 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-16 11:17:20.985  1018  1345 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-16 11:17:21.005  1018  1142 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 11:17:21.005  3987  3987 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 11:17:21.005  4004  4004 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:21.005  1018  1142 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-16 11:17:21.005  4004  4004 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:21.015  3814  3814 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@e7c6926 that was originally bound here
03-16 11:17:21.015  3814  3814 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@e7c6926 that was originally bound here
03-16 11:17:21.015  3814  3814 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
03-16 11:17:21.015  3814  3814 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
03-16 11:17:21.015  3814  3814 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
03-16 11:17:21.015  3814  3814 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
03-16 11:17:21.015  3814  3814 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
03-16 11:17:21.015  3814  3814 E ActivityThread: 	at com.android.emailcommon.service.ah.a(SourceFile:181)
03-16 11:17:21.015  3814  3814 E ActivityThread: 	at com.android.emailcommon.service.ah.e(SourceFile:224)
03-16 11:17:21.015  3814  3814 E ActivityThread: 	at com.android.email.service.n.c(SourceFile:161)
03-16 11:17:21.015  3814  3814 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:173)
03-16 11:17:21.015  3814  3814 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:117)
03-16 11:17:21.015  3814  3814 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:318)
03-16 11:17:21.015  3814  3814 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1308)
03-16 11:17:21.015  3814  3814 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-16 11:17:21.015  3814  3814 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 11:17:21.015  3814  3814 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-16 11:17:21.015  3814  3814 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 11:17:21.015  1018  1369 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@316bbd2d
,03-16 11:17:21.025  3814  3966 E SQLiteLog: (283) recovered 14 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-16 11:17:21.025  4004  4004 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,03-16 11:17:21.075  3927  3927 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,03-16 11:17:21.075  3927  3927 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,03-16 11:17:21.085  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,03-16 11:17:21.085  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-16 11:17:21.085  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:21.085  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 11:17:21.085  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-16 11:17:21.095  3927  3927 D DialogFlow: initQueue()
,03-16 11:17:21.105  1018  1030 I ActivityManager: Killing 3203:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,03-16 11:17:21.105  1018  1515 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-16 11:17:21.145  1018  1345 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,03-16 11:17:21.145  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:21.145  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:21.145  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:21.145  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:21.155  4045  4045 E Zygote  : MountEmulatedStorage()
03-16 11:17:21.155  4045  4045 E Zygote  : v2
03-16 11:17:21.155  4045  4045 I libpersona: KNOX_SDCARD checking this for 10032
03-16 11:17:21.155  4045  4045 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:21.155  4045  4045 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-16 11:17:21.165  4045  4045 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:21.165  4045  4045 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:21.165  1018  1345 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4045 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,03-16 11:17:21.165  1018  1345 I ActivityManager: Killing 3225:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,03-16 11:17:21.185  4045  4045 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:21.185  4045  4045 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:21.215  1018  1515 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,03-16 11:17:21.215  1018  1515 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,03-16 11:17:21.215  1018  1515 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:21.215  1018  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:21.215  1018  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-16 11:17:21.225  1018  1366 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,03-16 11:17:21.225  1018  1366 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-16 11:17:21.225  1018  1366 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:21.225  1018  1366 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:21.225  1018  1366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-16 11:17:21.235  1018  1142 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,03-16 11:17:21.235  1018  1142 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,03-16 11:17:21.235  1018  1142 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:21.235  1018  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:21.235  1018  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-16 11:17:21.255  2004  2004 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,03-16 11:17:21.255  1018  1142 D ActivityManager: startService callerProcessName:com.qualcomm.qti.services.secureui, calleePkgName: com.qualcomm.qti.services.secureui
03-16 11:17:21.255  1018  1142 D ActivityManager: retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
,03-16 11:17:21.255  1018  1142 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:21.255  1018  1142 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:21.255  1018  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,03-16 11:17:21.255  1018  1574 D ActivityManager: startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
,03-16 11:17:21.265  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:21.265  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:21.265  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:21.265  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:21.265  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3203/cgroup.procs: No such file or directory
,03-16 11:17:21.265  2004  2004 D SecUISvc: Service started flags 0 startId 1
,03-16 11:17:21.265  2004  4063 D SecUISvc: Thread created.
,03-16 11:17:21.275  4065  4065 E Zygote  : MountEmulatedStorage()
03-16 11:17:21.275  4065  4065 E Zygote  : v2
03-16 11:17:21.275  4065  4065 I libpersona: KNOX_SDCARD checking this for 10028
03-16 11:17:21.275  4065  4065 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:21.275  4065  4065 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:21.285  4065  4065 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-16 11:17:21.285  4065  4065 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 11:17:21.295  1018  1574 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4065 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:17:21.295  1018  1490 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,03-16 11:17:21.295  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,03-16 11:17:21.305  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:21.305  1018  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
03-16 11:17:21.305  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
03-16 11:17:21.305  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3225/cgroup.procs: No such file or directory
,03-16 11:17:21.315  4065  4065 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:21.315  4065  4065 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:21.385  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
,03-16 11:17:21.385  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 11:17:21.385  3956  3998 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
,03-16 11:17:21.395  3956  3998 I AMMetaDataParserService: getResourcePackageName:assistantlist
03-16 11:17:21.395  3956  3998 I AMMetaDataParserService: Resource data:2131165186
,03-16 11:17:21.405  3956  3998 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-16 11:17:21.405  3956  3998 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 11:17:21.405  1018  1574 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
,03-16 11:17:21.405  3956  3998 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-16 11:17:21.405  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:21.405  3956  3998 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-16 11:17:21.405  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:21.405  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:21.405  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:21.405  3956  3998 I AMMetaDataParserService: getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
03-16 11:17:21.405  3956  3998 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 11:17:21.415  4083  4083 E Zygote  : MountEmulatedStorage()
03-16 11:17:21.415  4083  4083 E Zygote  : v2
03-16 11:17:21.415  4083  4083 I libpersona: KNOX_SDCARD checking this for 10033
03-16 11:17:21.415  4083  4083 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:21.415  4083  4083 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:21.425  4083  4083 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:21.425  1018  1574 I ActivityManager: Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4083 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-16 11:17:21.425  4083  4083 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-16 11:17:21.425  1018  1574 I ActivityManager: Killing 3293:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,03-16 11:17:21.435  3367  3386 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-16 11:17:21.435  3367  3386 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-16 11:17:21.435  3367  3386 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-16 11:17:21.445  4083  4083 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:21.445  3367  3386 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-16 11:17:21.445  4083  4083 D ActivityThread: Added TimaKeyStore provider
03-16 11:17:21.445  3367  3386 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-16 11:17:21.455  3367  3386 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-16 11:17:21.455  3367  3386 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-16 11:17:21.485  3956  3998 I AMMetaDataParserService: Icon data: ResourceEnter URL2131755289android.intent.action.doInputURL2130837509
,03-16 11:17:21.505  1018  1044 W libprocessgroup: failed to open /acct/uid_10150/pid_3293/cgroup.procs: No such file or directory
,03-16 11:17:21.585  3956  3998 I AMMetaDataParserService: Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,03-16 11:17:21.615  3956  3998 I AMMetaDataParserService: Icon data: ResourceNew Tab2131755460android.intent.action.doNewWindow2130837510
,03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
,03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
,03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
,03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
,03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
03-16 11:17:21.625  3956  3998 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccoun,tActivity
03-16 11:17:21.625  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,03-16 11:17:21.645  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
03-16 11:17:21.645  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:21.645  3956  3998 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 11:17:21.645  3956  3998 I AMMetaDataParserService: Resource data:2131034113
,03-16 11:17:21.655  3956  3998 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,03-16 11:17:21.655  3956  3998 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 11:17:21.655  3956  3998 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-16 11:17:21.655  3956  3998 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-16 11:17:21.655  3956  3998 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 11:17:21.695  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:21.695   288   288 E SMD     : DCD OFF
,03-16 11:17:21.705  3956  3998 I GFX construct_block_size_descriptor_2d second part: took 2.420885ms for 0*0 texture 0
,03-16 11:17:21.715  3956  3998 I GFX generate_partition_tables: took 6.102450ms for 0*0 texture 0
,03-16 11:17:21.715  3956  3998 I GFX raster: took 9.772710ms for 96*96 texture 0
03-16 11:17:21.715  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ea8c28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7ea8fe0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:21.725  3956  3998 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-16 11:17:21.745  3259  3343 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,03-16 11:17:21.795  4065  4065 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-16 11:17:21.825  3987  4114 I Babel   : MmsConfig: mnc/mcc: 0/0
03-16 11:17:21.825  3987  4114 I Babel   : MmsConfig.loadMmsSettings
03-16 11:17:21.825  3987  4114 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
03-16 11:17:21.825  3987  4114 I Babel   : MmsConfig.loadFromDatabase
,03-16 11:17:21.855  3987  4114 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,03-16 11:17:21.855  3987  4114 I Babel   : MmsConfig.loadFromResources
,03-16 11:17:21.855  1018  1345 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,03-16 11:17:21.855  1018  1345 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,03-16 11:17:21.855  1018  1345 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:21.855  1018  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:21.855  1018  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-16 11:17:21.855  3987  4114 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull,
,03-16 11:17:21.865  3987  4114 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,03-16 11:17:21.865  3987  3987 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-16 11:17:21.925  3987  4003 W art     : Suspending all threads took: 6.138ms
,03-16 11:17:21.935  3814  3966 E File    : fail readDirectory() errno=2
,03-16 11:17:21.935  3987  3987 I Babel_StickerModule: App launched.
,03-16 11:17:21.945  3814  4026 I Gmail   : notifyAccountChanged
,03-16 11:17:21.965  3814  4026 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-16 11:17:21.965  1018  1031 I ActivityManager: Killing 3275:com.google.android.configupdater/u0a86 (adj 15): empty #31
,03-16 11:17:21.975  1018  1515 I ActivityManager: Killing 3346:com.dropbox.android/u0a92 (adj 15): empty #31
,03-16 11:17:21.985  1018  1574 D TimaService: TIMA: in getTimaVersion
,03-16 11:17:21.995  3405  4043 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A500FU Build/LRX22G)
03-16 11:17:21.995  3405  4043 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,03-16 11:17:21.995  3405  4043 I System.out: Thread-507(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
03-16 11:17:21.995  1018  1030 D ActivityManager: bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
,03-16 11:17:21.995  3405  4043 I System.out: Thread-507(ApacheHTTPLog):isSBSettingEnabled false
03-16 11:17:21.995  3405  4043 I System.out: Thread-507(ApacheHTTPLog):isShipBuild true
03-16 11:17:21.995  3405  4043 I System.out: Thread-507(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-16 11:17:21.995  3405  4043 I System.out: Thread-507(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-16 11:17:21.995  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-16 11:17:21.995  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:21.995  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:21.995  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-16 11:17:21.995   275   872 D EnterpriseController: uids 10166
03-16 11:17:21.995   275   872 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-16 11:17:21.995   275   872 D Netd    : getNetworkForDns: using netid 502 for uid 10166
,03-16 11:17:22.005  1018  2954 D TimaService: TIMA3: KeyStore3_init
03-16 11:17:22.005  1018  2954 E TLC_TZ_KEYSTORE: : Inside TZ_KEYSTORE_initialize()
03-16 11:17:22.005  1018  2954 D TimaService: TIMA: in getTimaVersion
03-16 11:17:22.005  1018  2954 I TLC_TZ_KEYSTORE: : creating new keystore context...
03-16 11:17:22.005  1018  2954 I TLC_TZ_KEYSTORE: : initializing ccm context...
03-16 11:17:22.005  1018  2954 I TLC_TZ_KEYSTORE: : root = /firmware/image, root_strlen = 15
03-16 11:17:22.005  1018  2954 I TLC_TZ_KEYSTORE: : process = tima_key, process_strlen = 8
03-16 11:17:22.005  1018  2954 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
03-16 11:17:22.005  1018  2954 I TZ: qc_tlc_communication: process = tima_key, process_strlen = 8
03-16 11:17:22.005  1018  2954 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 1088 = 0x440
03-16 11:17:22.005  1018  2954 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 1088 = 0x440
03-16 11:17:22.005  1018  2954 I TZ: qc_tlc_communication: max_message_size = 2176 = 0x880
03-16 11:17:22.005  1018  2954 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x880
03-16 11:17:22.005  1018  2954 D QSEECOMAPI: : App is not loaded in QSEE
,03-16 11:17:22.005  3814  4026 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-16 11:17:22.005  1856  1856 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:17:22.005  1856  1856 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:17:22.015  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:22.025  3956  3998 I GFX raster: took 0.849896ms for 96*96 texture 0,
03-16 11:17:22.025  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ea8c28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7eb1078 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:22.035  4083  4083 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-16 11:17:22.035  4083  4083 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 11:17:22.035  4083  4083 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-16 11:17:22.035  3956  3998 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-16 11:17:22.045  1018  2954 D QSEECOMAPI: : Loaded image: APP id = 10
,03-16 11:17:22.045  1018  2954 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
03-16 11:17:22.045  1018  2954 I TLC_TZ_KEYSTORE: : ctx = 0xb82c3df0, comm = 0xb82ebd88, sendmsg = 0xa0761000, recvmsg = 0xa0761440
03-16 11:17:22.045  1018  2954 I TZ_init: : TZ_init: sending initialization request...
,03-16 11:17:22.045  1018  2954 E TZ_init: : TZ_init Process: Secure memory is not initialized!
03-16 11:17:22.045  1018  2954 E TZ_init: : trustlet initialization failed
03-16 11:17:22.045  1018  2954 I TZ_init: : TZ_init_START...
,03-16 11:17:22.055  1018  2954 I TZ_init: : TZ_init_with_data: sending initialization request...
,03-16 11:17:22.055  1018  2954 I TZ_init: : TZ_init: successful initialization
,03-16 11:17:22.055  1018  2954 D QSEECOMAPI: : QSEECom_dealloc_memory 
,03-16 11:17:22.055  1018  2954 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 10
,03-16 11:17:22.055  1018  2954 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
,03-16 11:17:22.055  4083  4083 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-16 11:17:22.055  4083  4083 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 11:17:22.055  4083  4083 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 11:17:22.075  1018  1044 W libprocessgroup: failed to open /acct/uid_10086/pid_3275/cgroup.procs: No such file or directory
,03-16 11:17:22.095  4083  4083 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-16 11:17:22.095  4083  4083 W ResourcesManager: Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
03-16 11:17:22.095  4083  4083 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-16 11:17:22.105  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:22.105  3987  3987 V Babel   : babel boot account: SMS
,03-16 11:17:22.105  3987  3987 W Babel   : EsDatabaseHelper.static should not be called on main thread [called on main thread]
,03-16 11:17:22.135  3987  3987 W Babel   : java.lang.Exception
03-16 11:17:22.135  3987  3987 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
03-16 11:17:22.135  3987  3987 W Babel   : 	at aes.<clinit>(SourceFile:95)
03-16 11:17:22.135  3987  3987 W Babel   : 	at ckh.<init>(SourceFile:103)
03-16 11:17:22.135  3987  3987 W Babel   : 	at ckh.a(SourceFile:67)
03-16 11:17:22.135  3987  3987 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
03-16 11:17:22.135  3987  3987 W Babel   : 	at bhn.a(SourceFile:301)
03-16 11:17:22.135  3987  3987 W Babel   : 	at bhn.a(SourceFile:137)
03-16 11:17:22.135  3987  3987 W Babel   : 	at bhn.a(SourceFile:126)
03-16 11:17:22.135  3987  3987 W Babel   : 	at bhn.a(SourceFile:159)
03-16 11:17:22.135  3987  3987 W Babel   : 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
03-16 11:17:22.135  3987  3987 W Babel   : 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
03-16 11:17:22.135  3987  3987 W Babel   : 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-16 11:17:22.135  3987  3987 W Babel   : 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-16 11:17:22.135  3987  3987 W Babel   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 11:17:22.135  3987  3987 W Babel   : 	at android.os.Looper.loop(Looper.java:145)
03-16 11:17:22.135  3987  3987 W Babel   : 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-16 11:17:22.135  3987  3987 W Babel   : 	at java.lang.reflect.Method.invoke(Native Method)
03-16 11:17:22.135  3987  3987 W Babel   : 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 11:17:22.135  3987  3987 W Babel   : 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-16 11:17:22.135  3987  3987 W Babel   : 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-16 11:17:22.135  3956  3998 I GFX construct_block_size_descriptor_2d second part: took 2.434687ms for 0*0 texture 0
03-16 11:17:22.135  3987  3987 W Babel   : EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,03-16 11:17:22.135  3987  3987 W Babel   : java.lang.Exception
03-16 11:17:22.135  3987  3987 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
03-16 11:17:22.135  3987  3987 W Babel   : 	at aes.a(SourceFile:145)
03-16 11:17:22.135  3987  3987 W Babel   : 	at ckh.<init>(SourceFile:103)
03-16 11:17:22.135  3987  3987 W Babel   : 	at ckh.a(SourceFile:67)
03-16 11:17:22.135  3987  3987 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
03-16 11:17:22.135  3987  3987 W Babel   : 	at bhn.a(SourceFile:301)
03-16 11:17:22.135  3987  3987 W Babel   : 	at bhn.a(SourceFile:137)
03-16 11:17:22.135  3987  3987 W Babel   : 	at bhn.a(SourceFile:126)
03-16 11:17:22.135  3987  3987 W Babel   : 	at bhn.a(SourceFile:159)
03-16 11:17:22.135  3987  3987 W Babel   : 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
03-16 11:17:22.135  3987  3987 W Babel   : 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
03-16 11:17:22.135  3987  3987 W Babel   : 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-16 11:17:22.135  3987  3987 W Babel   : 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-16 11:17:22.135  3987  3987 W Babel   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 11:17:22.135  3987  3987 W Babel   : 	at android.os.Looper.loop(Looper.java:145)
03-16 11:17:22.135  3987  3987 W Babel   : 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-16 11:17:22.135  3987  3987 W Babel   : 	at java.lang.reflect.Method.invoke(Native Method)
03-16 11:17:22.135  3987  3987 W Babel   : 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 11:17:22.135  3987  3987 W Babel   : 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-16 11:17:22.135  3987  3987 W Babel   : 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-16 11:17:22.145  1018  2783 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,03-16 11:17:22.155  3814  4026 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-16 11:17:22.155  3814  4026 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-16 11:17:22.165  3956  3998 I GFX generate_partition_tables: took 7.470208ms for 0*0 texture 0
,03-16 11:17:22.165  3956  3998 I GFX raster: took 10.872448ms for 96*96 texture 0
03-16 11:17:22.165  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7eadd08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7eade60 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:22.175  3956  3998 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-16 11:17:22.195  3987  4003 W art     : Suspending all threads took: 21.043ms
,03-16 11:17:22.195  4065  4065 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,03-16 11:17:22.205  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:22.205  3956  3998 I GFX raster: took 0.621406ms for 96*96 texture 0
03-16 11:17:22.205  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7eb1c78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7eb1dd0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:22.215  4004  4004 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
03-16 11:17:22.215  1018  1044 W libprocessgroup: failed to open /acct/uid_10092/pid_3346/cgroup.procs: No such file or directory
,03-16 11:17:22.215  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.android.bbc.bbcagent, calleePkgName: com.samsung.android.bbc.bbcagent
,03-16 11:17:22.215  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,03-16 11:17:22.215  3956  3998 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-16 11:17:22.215  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:22.215  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:22.215  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,03-16 11:17:22.215  1018  3034 D ActivityManager: startProcessLocked calleePkgName: com.sec.bcservice, hostingType: broadcast
,03-16 11:17:22.225  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:22.225  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:22.225  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:22.225  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:22.235  4133  4133 E Zygote  : MountEmulatedStorage()
03-16 11:17:22.235  4133  4133 E Zygote  : v2
03-16 11:17:22.235  4133  4133 I libpersona: KNOX_SDCARD checking this for 1000
03-16 11:17:22.235  4133  4133 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:22.235  4133  4133 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:22.245  4133  4133 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-16 11:17:22.245  1018  3034 I ActivityManager: Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=4133 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-16 11:17:22.245  1018  2954 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk,
03-16 11:17:22.245  1018  2954 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
03-16 11:17:22.245  1018  2954 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:22.245  1018  2954 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:22.245  1018  2954 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk,
,03-16 11:17:22.245  4133  4133 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:22.245  1018  1574 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
03-16 11:17:22.255  1018  1574 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-16 11:17:22.255  1018  1574 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:22.255  1018  1574 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:22.255  1018  1574 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-16 11:17:22.255  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:22.255  3956  3998 I GFX raster: took 0.870156ms for 96*96 texture 0
03-16 11:17:22.255  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7eaf8a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7eafa00 counterpartCT=4 counterpartW=96 counterparth=96
03-16 11:17:22.255  1018  1515 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
03-16 11:17:22.255  1018  1515 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-16 11:17:22.255  1018  1515 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:22.255  1018  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:22.255  1018  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-16 11:17:22.255  3987  3987 V Babel   : babel boot account: thalitester@gmail.com
,03-16 11:17:22.265  4065  4065 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 11:17:22.265  3956  3998 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-16 11:17:22.275  4065  4065 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 11:17:22.285  4133  4133 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-16 11:17:22.285  4133  4133 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:22.305  4133  4133 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-16 11:17:22.315  1018  1574 W SEAMService:  hashset_to_int_array returning null
,03-16 11:17:22.315  3987  3987 W Babel   : EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,03-16 11:17:22.315  3987  3987 W Babel   : java.lang.Exception
03-16 11:17:22.315  3987  3987 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
03-16 11:17:22.315  3987  3987 W Babel   : 	at aes.a(SourceFile:145)
03-16 11:17:22.315  3987  3987 W Babel   : 	at ckh.<init>(SourceFile:103)
03-16 11:17:22.315  3987  3987 W Babel   : 	at ckh.a(SourceFile:67)
03-16 11:17:22.315  3987  3987 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
03-16 11:17:22.315  3987  3987 W Babel   : 	at bhn.a(SourceFile:301)
03-16 11:17:22.315  3987  3987 W Babel   : 	at bhn.a(SourceFile:137)
03-16 11:17:22.315  3987  3987 W Babel   : 	at bhn.a(SourceFile:126)
03-16 11:17:22.315  3987  3987 W Babel   : 	at bhn.a(SourceFile:159)
03-16 11:17:22.315  3987  3987 W Babel   : 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
03-16 11:17:22.315  3987  3987 W Babel   : 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
03-16 11:17:22.315  3987  3987 W Babel   : 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-16 11:17:22.315  3987  3987 W Babel   : 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-16 11:17:22.315  3987  3987 W Babel   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 11:17:22.315  3987  3987 W Babel   : 	at android.os.Looper.loop(Looper.java:145)
03-16 11:17:22.315  3987  3987 W Babel   : 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-16 11:17:22.315  3987  3987 W Babel   : 	at java.lang.reflect.Method.invoke(Native Method)
03-16 11:17:22.315  3987  3987 W Babel   : 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 11:17:22.315  3987  3987 W Babel   : 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-16 11:17:22.315  3987  3987 W Babel   : 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-16 11:17:22.325  1018  3034 W SEAMService:  hashset_to_int_array returning null
,03-16 11:17:22.325  4004  4004 E SQLiteLog: (284) automatic index on seams_container_info(seams_container_id)
,03-16 11:17:22.325  4004  4004 E SQLiteLog: (284) automatic index on seams_container_info(sp_id)
,03-16 11:17:22.325  1018  1490 W SEAMService:  hashset_to_int_array returning null
,03-16 11:17:22.335  1018  1031 I ActivityManager: Killing 3367:com.policydm/1000 (adj 15): empty #31
,03-16 11:17:22.345  4133  4133 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,03-16 11:17:22.345  1018  1142 D ActivityManager: startService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.bcservice
,03-16 11:17:22.345  1018  1142 D ActivityManager: retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,03-16 11:17:22.345  1018  1142 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:22.345  1018  1142 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:22.345  1018  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,03-16 11:17:22.355  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:22.355  3956  3998 I GFX raster: took 0.631980ms for 96*96 texture 0
03-16 11:17:22.355  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7eb1968 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7eadef0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:22.355  3956  3998 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-16 11:17:22.365  4133  4133 I F_PHONE : [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,03-16 11:17:22.365  4133  4133 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,03-16 11:17:22.365  1018  1030 D ActivityManager: bindService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.phone, action: null
03-16 11:17:22.365  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,03-16 11:17:22.375  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:22.375  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:22.375  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,03-16 11:17:22.375  1018  2783 D SSRM:n  : SIOP:: AP = 380
,03-16 11:17:22.385  4133  4133 D F_PHONE : [[com.sec.bcservice]] onServiceConnected()
,03-16 11:17:22.385  4133  4133 I F_PHONE : default registerAction()
03-16 11:17:22.385  4133  4133 I F_PHONE : [[com.sec.bcservice]] sendPendingMessage()
,03-16 11:17:22.395  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:22.395  3956  3998 I GFX raster: took 0.683906ms for 96*96 texture 0
03-16 11:17:22.395  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ea9070 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7eadef0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:22.405  3956  3998 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-16 11:17:22.415  1018  1345 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
03-16 11:17:22.415  1018  1345 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-16 11:17:22.415  1018  1345 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:22.415  1018  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:22.415  1018  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-16 11:17:22.415  1018  1369 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,03-16 11:17:22.415  1018  1369 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-16 11:17:22.425  1018  1369 W ActivityManager: userId = 0, bbcId = -10000,
03-16 11:17:22.425  1018  1369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:22.425  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-16 11:17:22.435  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:22.435  3956  3998 I GFX raster: took 0.574688ms for 96*96 texture 0
03-16 11:17:22.435  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7eadef0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7eb1b88 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:22.445  1018  1515 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
03-16 11:17:22.445  1018  1515 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-16 11:17:22.445  1018  1515 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:22.445  1018  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:22.445  1018  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-16 11:17:22.445  1018  1345 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
03-16 11:17:22.445  3956  3998 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-16 11:17:22.445  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:22.445  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:22.445  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:22.445  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:22.455  4161  4161 E Zygote  : MountEmulatedStorage(),
03-16 11:17:22.455  4161  4161 E Zygote  : v2
03-16 11:17:22.455  4161  4161 I libpersona: KNOX_SDCARD checking this for 1000
,03-16 11:17:22.465  4161  4161 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:22.465  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3367/cgroup.procs: No such file or directory
,03-16 11:17:22.465  4065  4124 D Volley  : [598] DiskBasedCache.clear: Cache cleared.
03-16 11:17:22.465  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
03-16 11:17:22.465  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-16 11:17:22.465  3956  3998 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 11:17:22.465  3956  3998 I AMMetaDataParserService: Resource data:2131034113
,03-16 11:17:22.465  4161  4161 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-16 11:17:22.465  3956  3998 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main,
03-16 11:17:22.465  3956  3998 I AMMetaDataParserService: getResourceTypeNamexml
03-16 11:17:22.465  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:22.465  3956  3998 I GFX raster: took 0.867917ms for 96*96 texture 0,
03-16 11:17:22.465  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ea8c28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7eb23f8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:22.475  4161  4161 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-16 11:17:22.475  1018  1345 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4161 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-16 11:17:22.475  1856  1879 I art     : Explicit concurrent mark sweep GC freed 19069(1432KB) AllocSpace objects, 27(431KB) LOS objects, 40% free, 12MB/20MB, paused 4.815ms total 329.791ms
,03-16 11:17:22.475  4065  4111 D Volley  : [591] DiskBasedCache.clear: Cache cleared.
,03-16 11:17:22.485  4065  4065 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-16 11:17:22.485  4065  4065 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,03-16 11:17:22.485  4161  4161 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-16 11:17:22.495  3956  3998 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-16 11:17:22.515  4065  4166 D Ads     : Skipping gmscore version check
,03-16 11:17:22.515  4161  4161 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:22.515  4161  4161 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:22.515   281   834 W QCamera2Factory: getCameraInfo: E, camera_id = 0
03-16 11:17:22.515   281   834 W QCamera2Factory: getCameraInfo: X
,03-16 11:17:22.525   281   281 W QCamera2Factory: getCameraInfo: E, camera_id = 1
03-16 11:17:22.525   281   281 W QCamera2Factory: getCameraInfo: X
,03-16 11:17:22.545  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:22.545  3956  3998 I GFX raster: took 1.001927ms for 96*96 texture 0
03-16 11:17:22.545  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ea8c28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7eabf68 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:22.555  3987  3987 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 11:17:22.555  3987  3987 W AudioCapabilities: Unsupported mime audio/evrc
,03-16 11:17:22.565  3987  3987 W AudioCapabilities: Unsupported mime audio/qcelp
03-16 11:17:22.565  3956  3998 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-16 11:17:22.565  3987  3987 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,03-16 11:17:22.565  3987  3987 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,03-16 11:17:22.575  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:22.575  3956  3998 I GFX raster: took 0.616876ms for 96*96 texture 0
03-16 11:17:22.575  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7eadd08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7eacbe8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:22.575  3987  3987 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,03-16 11:17:22.575  3987  3987 W AudioCapabilities: Unsupported mime audio/x-ima
,03-16 11:17:22.585  3987  3987 W AudioCapabilities: Unsupported mime audio/qcelp
,03-16 11:17:22.585  3987  3987 W AudioCapabilities: Unsupported mime audio/evrc
,03-16 11:17:22.595  3956  3998 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-16 11:17:22.605  3987  3987 W VideoCapabilities: Unsupported mime video/wvc1
,03-16 11:17:22.605  3987  3987 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-16 11:17:22.615  4045  4072 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 11:17:22.615  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:22.615  3956  3998 I GFX raster: took 0.615729ms for 96*96 texture 0
03-16 11:17:22.615  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7eb1c78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ead9f8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:22.625  3956  3998 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-16 11:17:22.625  3987  3987 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,03-16 11:17:22.635  3987  3987 W VideoCapabilities: Unsupported mime video/wvc1
,03-16 11:17:22.635  3987  3987 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-16 11:17:22.635  3987  3987 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,03-16 11:17:22.635  4045  4072 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-16 11:17:22.635  4045  4072 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 11:17:22.635  4045  4072 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 11:17:22.645  3987  3987 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,03-16 11:17:22.645  3987  3987 W VideoCapabilities: Unsupported mime video/mp43
,03-16 11:17:22.645  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:22.645  1018  1515 I art     : Explicit concurrent mark sweep GC freed 31820(2032KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 30MB/45MB, paused 2.770ms total 171.426ms
03-16 11:17:22.645  1018  1515 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-16 11:17:22.645  3956  3998 I GFX raster: took 0.834322ms for 96*96 texture 0
03-16 11:17:22.645  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7eaf8a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7eace98 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:22.655  1018  1046 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
,03-16 11:17:22.655  1018  1046 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
03-16 11:17:22.655  1018  1515 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:22.655  1018  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:22.655  1018  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:22.655  3987  3987 W VideoCapabilities: Unsupported mime video/sorenson
,03-16 11:17:22.655  3956  3998 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-16 11:17:22.655  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 11:17:22.665  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:22.665  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:22.665  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:22.665  1018  2866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 11:17:22.665  3987  3987 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,03-16 11:17:22.665  1018  1030 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
03-16 11:17:22.665  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,03-16 11:17:22.665  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:22.665  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 11:17:22.665  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-16 11:17:22.665  1018  1046 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
,03-16 11:17:22.675  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:22.675  3956  3998 I GFX raster: took 0.627500ms for 96*96 texture 0
03-16 11:17:22.675  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7eb1968 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7eb23e8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:22.675  1018  1369 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 11:17:22.675  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:22.675  1018  1369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 11:17:22.685  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-16 11:17:22.685  3956  3998 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-16 11:17:22.685  4083  4083 I Process : Sending signal. PID: 4083 SIG: 9
,03-16 11:17:22.695  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:22.695  3956  3998 I GFX raster: took 0.700469ms for 96*96 texture 0
03-16 11:17:22.695  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ea9070 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ea8c68 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:22.695  1967  4180 D FileApkUtils: Optimizing (staging complete)
,03-16 11:17:22.695  1967  4180 D FileApkUtils: Optimizing: DynamiteModules-prod.apk [0224a548494bce36274e23f9f1b42d4fbe3d4d8de53a7872e503f8974e43c3c3]
,03-16 11:17:22.695  1967  4180 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
,03-16 11:17:22.705  3956  3998 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-16 11:17:22.715  1967  4180 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk appears to be unoptimized.
03-16 11:17:22.715  1967  4180 D DexOptUtils: Lollipop platform, using <isa> directory.
,03-16 11:17:22.715  1967  4180 D DexOptUtils: Instantiating DexClassLoader to force creation of odex.
03-16 11:17:22.715  1967  4180 D DexOptUtils: Primary ABI of odexing process is armeabi-v7a
,03-16 11:17:22.725  3987  3987 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-16 11:17:22.725  4065  4065 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-16 11:17:22.735  3405  4043 I System.out: Thread-507 calls detatch()
,03-16 11:17:22.735  1018  1142 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
03-16 11:17:22.735  1018  1142 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,03-16 11:17:22.735  1018  1142 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:22.735  1018  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:22.735  1018  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-16 11:17:22.745  3259  3343 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,03-16 11:17:22.765  3927  3986 I System.out: INFO:Resource not found:/Common.properties Using default values
,03-16 11:17:22.765  1018  1366 I ActivityManager: Process com.sec.android.app.sns3 (pid 4083)(adj 0) has died(41,1157)
,03-16 11:17:22.765  1018  1045 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,03-16 11:17:22.765  1018  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:22.765  1018  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:22.765  1018  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:22.765  1018  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:22.785  4187  4187 E Zygote  : MountEmulatedStorage(),
03-16 11:17:22.785  4187  4187 E Zygote  : v2
03-16 11:17:22.785  4187  4187 I libpersona: KNOX_SDCARD checking this for 10034
,03-16 11:17:22.785  4187  4187 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:22.795  1018  1045 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4187 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a,
,03-16 11:17:22.795  4187  4187 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-16 11:17:22.795  4187  4187 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:22.795  4187  4187 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:22.825  4065  4065 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-16 11:17:22.825  4187  4187 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:22.825  4187  4187 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:22.855  1018  3034 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND,
03-16 11:17:22.855  1018  3034 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,03-16 11:17:22.855  1018  3034 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:22.855  1018  3034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:22.855  1018  3034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-16 11:17:22.875  1018  2954 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-16 11:17:22.875  1018  2954 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,03-16 11:17:22.875  1018  2954 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:22.875  1018  2954 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 11:17:22.875  1018  2954 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:22.885  4185  4185 I dex2oat : ----------------------------------------------------
03-16 11:17:22.885  4185  4185 I dex2oat : <SS>: S T A R T I N G . . .
03-16 11:17:22.885  4185  4185 I dex2oat : <SS>: Zip is absent. Canceled.
,03-16 11:17:22.885  4185  4185 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk --oat-fd=45 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-16 11:17:22.895  1018  1369 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,03-16 11:17:22.895  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:22.895  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:22.895  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:22.895  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:22.905  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:22.905  3956  3998 I GFX raster: took 0.528802ms for 96*96 texture 0
03-16 11:17:22.905  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7eb2a40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7cec5b8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:22.905  4205  4205 E Zygote  : MountEmulatedStorage(),
03-16 11:17:22.905  4205  4205 E Zygote  : v2,
03-16 11:17:22.915  4205  4205 I libpersona: KNOX_SDCARD checking this for 1000
,03-16 11:17:22.915  4205  4205 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:22.915  4205  4205 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-16 11:17:22.915  1018  1369 I ActivityManager: Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=4205 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-16 11:17:22.915  4205  4205 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-16 11:17:22.925  4205  4205 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 11:17:22.925  3956  3998 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-16 11:17:22.935  1018  1369 I ActivityManager: Killing 3479:com.fmm.dm/1000 (adj 15): empty #31
,03-16 11:17:22.945   306   306 I art     : Explicit concurrent mark sweep GC freed 8751(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 11.849ms total 36.453ms
,03-16 11:17:22.965  4205  4205 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:22.965  4205  4205 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:22.965   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 602us total 19.809ms
,03-16 11:17:23.005   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 743us total 31.068ms
,03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactShortcut
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activityalias.DialShortcut
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activityalias.MessageShortcut
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 11:17:23.015  3956 , 3998 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: Resource data:2131034112
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_detail
03-16 11:17:23.015  3956  3998 I AMMetaDataParserService: getResourceTypeNamexml
03-16 11:17:23.015  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:23.015  3956  3998 I GFX raster: took 0.757448ms for 96*96 texture 0
03-16 11:17:23.015  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7c00750 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7cec718 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:23.035  1018  2954 D ActivityManager: startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
,03-16 11:17:23.035  1018  2954 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:23.035  1018  2954 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:23.035  1018  2954 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:23.035  1018  2954 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:23.055  3956  3998 I AMMetaDataParserService: Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,03-16 11:17:23.055  4205  4205 D KnoxSetupWizardDbHelper: dbMigrationFlag : false
,03-16 11:17:23.065  4225  4225 E Zygote  : MountEmulatedStorage(),
03-16 11:17:23.065  4225  4225 I libpersona: KNOX_SDCARD checking this for 1000
03-16 11:17:23.065  4225  4225 E Zygote  : v2
03-16 11:17:23.065  4225  4225 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:23.065  4225  4225 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:23.065  4225  4225 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-16 11:17:23.065  1018  2954 I ActivityManager: Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4225 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-16 11:17:23.065  4225  4225 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 11:17:23.065  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3479/cgroup.procs: No such file or directory
,03-16 11:17:23.095  4225  4225 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:23.095  4225  4225 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:23.115  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:23.115  3956  3998 I GFX raster: took 0.650730ms for 96*96 texture 0
03-16 11:17:23.115  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7c00750 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e76d88 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:23.115  3956  3998 I AMMetaDataParserService: Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,03-16 11:17:23.125  4205  4205 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,03-16 11:17:23.125  1967  1967 W InstanceID/Rpc: Found 10012
,03-16 11:17:23.125  4205  4205 D KnoxShortcutUtil: getIsShortcutMigrationFor_2_3_0_Done true
,03-16 11:17:23.125  4205  4205 D ShortcutReceiver:  KnoxContainerVersion 2.4.0
,03-16 11:17:23.125  4205  4205 D ShortcutReceiver:  shortcut migration not required 
03-16 11:17:23.125  3987  4222 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-16 11:17:23.135  1018  1031 I ActivityManager: Killing 3430:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,03-16 11:17:23.135  1018  1369 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,03-16 11:17:23.135  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:23.135  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:23.135  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:23.135  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:23.155  4242  4242 E Zygote  : MountEmulatedStorage()
03-16 11:17:23.155  4242  4242 E Zygote  : v2
03-16 11:17:23.155  4242  4242 I libpersona: KNOX_SDCARD checking this for 1000
03-16 11:17:23.155  4242  4242 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:23.155  4242  4242 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:23.155  4242  4242 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:23.155  4242  4242 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:23.165  1018  1369 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4242 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-16 11:17:23.165  1018  1369 I ActivityManager: Killing 3501:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31,
,03-16 11:17:23.175  3987  4222 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-16 11:17:23.185  4242  4242 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:23.185  4242  4242 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:23.185  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:23.185  3956  3998 I GFX raster: took 0.659271ms for 96*96 texture 0
03-16 11:17:23.185  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7e90c00 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7e73510 counterpartCT=4 counterpartW=96 counterparth=96
03-16 11:17:23.185  3987  4222 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-16 11:17:23.195  1018  2954 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-16 11:17:23.195  1018  2954 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,03-16 11:17:23.195  1018  2954 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:23.195  1018  2954 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:23.195  1018  2954 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:23.195  3956  3998 I AMMetaDataParserService: Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,03-16 11:17:23.215  1018  1490 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-16 11:17:23.225  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,03-16 11:17:23.225  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:23.225  1018  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:23.225  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 11:17:23.225  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:23.225  3956  3998 I GFX raster: took 0.628906ms for 96*96 texture 0
03-16 11:17:23.225  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ce4568 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7cec5b8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:23.235  3987  4222 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-16 11:17:23.235  1018  1574 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-16 11:17:23.235  1018  1574 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,03-16 11:17:23.235  1018  1574 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:23.235  1018  1574 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:23.235  1018  1574 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:23.245  3956  3998 I AMMetaDataParserService: Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,03-16 11:17:23.255  3987  4222 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-16 11:17:23.265  4242  4242 E KnoxSetupWizardClient: isShipMode : 1
,03-16 11:17:23.265  4242  4242 I KnoxSetupWizardClient: onReceive : android.intent.action.BOOT_COMPLETED
,03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.em,ergency.InteractionEmergencyMessageActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
,03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
,03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 11:17:23.275  3956  3998 I AMMetaDataParserService: Resource data:2131034113
,03-16 11:17:23.285  3956  3998 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main,
03-16 11:17:23.285  3956  3998 I AMMetaDataParserService: getResourceTypeNamexml
03-16 11:17:23.285  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-16 11:17:23.285  3956  3998 I GFX raster: took 0.835365ms for 96*96 texture 0
,03-16 11:17:23.285  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7e76d88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7cec718 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:23.305  1018  1515 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-16 11:17:23.305  1018  1515 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,03-16 11:17:23.305  3956  3998 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-16 11:17:23.315  1018  1515 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:23.315  1018  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:23.315  1018  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:23.315  1018  3034 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,03-16 11:17:23.315  4225  4225 I DBG_POLICYDM: [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,03-16 11:17:23.325  4225  4225 I DBG_POLICYDM: [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-16 11:17:23.325  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:23.325  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:23.325  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:23.325  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:23.335  1018  3034 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4267 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-16 11:17:23.345  1018  3034 I ActivityManager: Killing 3523:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,03-16 11:17:23.345  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:23.345  3956  3998 I GFX raster: took 0.824375ms for 96*96 texture 0
03-16 11:17:23.345  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7e76d88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7e73510 counterpartCT=4 counterpartW=96 counterparth=96
03-16 11:17:23.345  4225  4225 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] ,
03-16 11:17:23.355  4267  4267 E Zygote  : MountEmulatedStorage()
03-16 11:17:23.355  4267  4267 E Zygote  : v2
03-16 11:17:23.355  4267  4267 I libpersona: KNOX_SDCARD checking this for 10107
03-16 11:17:23.355  4267  4267 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:23.355  4267  4267 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:23.355  4267  4267 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-16 11:17:23.355  4267  4267 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 11:17:23.365  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-16 11:17:23.365  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,03-16 11:17:23.365  3956  3998 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-16 11:17:23.365  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:23.365  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:23.365  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:23.375  4225  4261 I DBG_POLICYDM: [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
03-16 11:17:23.375  1018  1044 W libprocessgroup: failed to open /acct/uid_10092/pid_3501/cgroup.procs: No such file or directory
,03-16 11:17:23.375  4267  4267 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:23.375  4225  4225 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-16 11:17:23.375  4267  4267 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:23.385  4225  4261 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,03-16 11:17:23.395  4242  4259 W System.err: java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,03-16 11:17:23.395  4242  4259 W System.err: 	at android.os.Parcel.readException(Parcel.java:1544)
03-16 11:17:23.395  4242  4259 W System.err: 	at android.os.Parcel.readException(Parcel.java:1493)
03-16 11:17:23.395  4242  4259 W System.err: ,	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
03-16 11:17:23.395  4242  4259 W System.err: 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
,03-16 11:17:23.395  4242  4259 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
03-16 11:17:23.395  4242  4259 W System.err: ,	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,03-16 11:17:23.405  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:23.405  3956  3998 I GFX raster: took 0.642865ms for 96*96 texture 0
03-16 11:17:23.405  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7cec5b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ea37f0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:23.415  3956  3998 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-16 11:17:23.415  4225  4225 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-16 11:17:23.415  4225  4225 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-16 11:17:23.425  4225  4225 I DBG_POLICYDM: [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,03-16 11:17:23.425  4225  4225 I DBG_POLICYDM: [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,03-16 11:17:23.425  4225  4225 I DBG_POLICYDM: [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,03-16 11:17:23.425  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:23.425  3956  3998 I GFX raster: took 0.644479ms for 96*96 texture 0
03-16 11:17:23.425  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7c00750 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7cec718 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:23.435  1018  1574 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-16 11:17:23.435  1018  1574 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,03-16 11:17:23.435  1018  1574 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:23.435  1018  1574 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 11:17:23.435  1018  1574 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:23.445  3956  3998 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-16 11:17:23.445  1018  1490 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,03-16 11:17:23.445  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-16 11:17:23.455  1967  4257 D GCM     : COMPAT: Multi user not supported
,03-16 11:17:23.455  1856  1856 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:17:23.455  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-16 11:17:23.455  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-16 11:17:23.455  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:23.455  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:23.455  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:23.455  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 11:17:23.455  3956  3998 I GFX raster: took 0.825468ms for 96*96 texture 0
03-16 11:17:23.455  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7e73510 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ea37f0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:23.455  3814  4282 I Gmail   : getAccountsCursor
,03-16 11:17:23.455  1018  1369 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,03-16 11:17:23.465  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:23.465  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:23.465  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:23.465  1856  1856 D GCM     : COMPAT: Multi user not supported
03-16 11:17:23.465  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:23.485  3956  3998 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-16 11:17:23.495  1018  1044 W libprocessgroup: failed to open /acct/uid_10057/pid_3430/cgroup.procs: No such file or directory
,03-16 11:17:23.495  4286  4286 E Zygote  : MountEmulatedStorage()
,03-16 11:17:23.495  4286  4286 E Zygote  : v2
03-16 11:17:23.495  4286  4286 I libpersona: KNOX_SDCARD checking this for 10035
03-16 11:17:23.495  4286  4286 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:23.495  4286  4286 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:23.505  4286  4286 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:23.505  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:23.505  3956  3998 I GFX raster: took 0.646302ms for 96*96 texture 0
03-16 11:17:23.505  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ce4568 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7cec718 counterpartCT=4 counterpartW=96 counterparth=96
03-16 11:17:23.505  4286  4286 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,03-16 11:17:23.505  1018  1369 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4286 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-16 11:17:23.505  1018  1369 I ActivityManager: Killing 3571:com.fmm.ds/1000 (adj 15): empty #31
03-16 11:17:23.505  1018  1030 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-16 11:17:23.505  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-16 11:17:23.505  4225  4261 I DBG_POLICYDM: [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,03-16 11:17:23.515  3956  3998 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-16 11:17:23.515  1018  2954 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-16 11:17:23.515  1018  2954 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,03-16 11:17:23.515  1018  2954 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:23.515  1018  2954 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:23.515  1018  2954 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:23.535  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:23.535  3956  3998 I GFX raster: took 0.689843ms for 96*96 texture 0
03-16 11:17:23.535  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ea9070 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7ea37f0 counterpartCT=4 counterpartW=96 counterparth=96
03-16 11:17:23.535  1018  1574 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-16 11:17:23.535  1018  1574 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,03-16 11:17:23.535  1018  1574 W ActivityManager: userId = 0, bbcId = -10000,
03-16 11:17:23.535  1018  1574 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:23.535  1018  1574 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:23.555  3956  3998 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-16 11:17:23.555  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-16 11:17:23.555  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-16 11:17:23.555  4286  4286 D TimaKeyStoreProvider: TimaSignature is unavailable,
,03-16 11:17:23.555  4286  4286 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:23.555  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:23.555  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:23.555  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:23.565  1018  1044 W libprocessgroup: failed to open /acct/uid_10003/pid_3523/cgroup.procs: No such file or directory
,03-16 11:17:23.565  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:23.565  3956  3998 I GFX raster: took 0.536771ms for 96*96 texture 0
03-16 11:17:23.565  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7eb2a40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7cec718 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:23.575  3956  3998 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-16 11:17:23.575  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3571/cgroup.procs: No such file or directory
,03-16 11:17:23.595  1018  1574 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-16 11:17:23.595  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
03-16 11:17:23.595  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
03-16 11:17:23.595  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:23.595  3956  3998 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 11:17:23.595  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
03-16 11:17:23.595  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
03-16 11:17:23.595  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
03-16 11:17:23.595  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
03-16 11:17:23.595  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
03-16 11:17:23.595  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
03-16 11:17:23.595  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
03-16 11:17:23.595  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
03-16 11:17:23.595  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
03-16 11:17:23.595  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
,03-16 11:17:23.605  1018  1574 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,03-16 11:17:23.605  1018  1574 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:23.605  1018  1574 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 11:17:23.605  1018  1574 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:23.605  1018  1142 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-16 11:17:23.605  1018  1142 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-16 11:17:23.615  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
03-16 11:17:23.615  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
03-16 11:17:23.615  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
03-16 11:17:23.615  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
03-16 11:17:23.615  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
03-16 11:17:23.615  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
03-16 11:17:23.615  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:23.615  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-16 11:17:23.615  3956  3998 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-16 11:17:23.615  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
03-16 11:17:23.615  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:23.615  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-16 11:17:23.615  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
03-16 11:17:23.615  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,03-16 11:17:23.615  1018  1142 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:23.615  1018  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:23.615  1018  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:23.625  1967  4257 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,03-16 11:17:23.625  1018  1345 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-16 11:17:23.625  3814  3943 I Gmail   : getAccountsCursor
,03-16 11:17:23.625  1018  1345 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,03-16 11:17:23.625  1018  1345 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:23.625  1018  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:23.625  1018  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:23.625  1018  1142 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-16 11:17:23.625  1018  1142 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Welcome
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.DataConnection
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL,
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
,03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity,
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Debug
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageListXL
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: getResourcePackageName:assistant
,03-16 11:17:23.635  3956  3998 I AMMetaDataParserService: Resource data:2131165203
03-16 11:17:23.645  3956  3998 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-16 11:17:23.645  3956  3998 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 11:17:23.645  3956  3998 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-16 11:17:23.645  3956  3998 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 11:17:23.645  3956  3998 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 11:17:23.645  3956  3998 I AMMetaDataParserService: getResourceName:com.android.email:xml/email_assistant_menu
,03-16 11:17:23.645  3956  3998 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 11:17:23.655  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:23.655  3956  3998 I GFX construct_block_size_descriptor_2d second part: took 2.985938ms for 0*0 texture 0
,03-16 11:17:23.665  1018  1515 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 11:17:23.665  1018  1515 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,03-16 11:17:23.665  1018  1515 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,03-16 11:17:23.665  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 11:17:23.665  3956  3998 I GFX generate_partition_tables: took 10.171614ms for 0*0 texture 0
,03-16 11:17:23.675  3956  3998 I GFX raster: took 14.039531ms for 96*96 texture 0
03-16 11:17:23.675  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb805c308 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb805bc50 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:23.675  1018  1018 I MotionRecognitionService: Plugged
,03-16 11:17:23.675  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 11:17:23.685  3956  3998 I AMMetaDataParserService: Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,03-16 11:17:23.685  1187  1187 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-16 11:17:23.685  1187  1187 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 11:17:23.695  1428  1428 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 11:17:23.695  1428  1428 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 11:17:23.695  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:23.695  3956  3998 I GFX raster: took 0.788073ms for 96*96 texture 0
03-16 11:17:23.695  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7e86150 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7e86188 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:23.705  3956  3998 I AMMetaDataParserService: Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,03-16 11:17:23.715  2686  2686 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-16 11:17:23.715  2686  2772 D HeadsetStateMachine: Disconnected process message: 10
,03-16 11:17:23.715  1187  1187 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:17:23.715  1187  1187 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 11:17:23.715  1187  1187 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 11:17:23.735  1967  4309 I CheckinService: Disabling old GoogleServicesFramework version,
,03-16 11:17:23.745  3259  3343 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,03-16 11:17:23.755  1967  1967 D BootCompletedReceiver: Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,03-16 11:17:23.755  1967  1967 D BootCompletedReceiver: Got an BootCompleted event.
,03-16 11:17:23.785  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:23.785  3956  3998 I GFX raster: took 0.785469ms for 96*96 texture 0
03-16 11:17:23.785  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7e86150 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb82126f8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:23.795  1967  1967 D BootCompletedReceiver: Will NOT schedule AdAttestation signal task because it's disabled.
,03-16 11:17:23.795  1967  1967 D SystemUpdateService: onCreate
,03-16 11:17:23.795  3956  3998 I AMMetaDataParserService: Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,03-16 11:17:23.825  4286  4315 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,03-16 11:17:23.835  4286  4315 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,03-16 11:17:23.835  4225  4261 I DBG_POLICYDM: [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-16 11:17:23.845  4225  4261 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-16 11:17:23.845  4225  4261 I DBG_POLICYDM: [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,03-16 11:17:23.845  4225  4261 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,03-16 11:17:23.845  4286  4286 E SPPClientService: [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,03-16 11:17:23.855  4225  4261 I DBG_POLICYDM: [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,03-16 11:17:23.855  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:23.855  1967  1967 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-16 11:17:23.855  3956  3998 I GFX raster: took 0.867552ms for 96*96 texture 0
,03-16 11:17:23.865  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7e86150 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb805cee8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:23.875  1967  4321 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
,03-16 11:17:23.885  4225  4261 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,03-16 11:17:23.895  3956  3998 I AMMetaDataParserService: Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,03-16 11:17:23.905  1018  1366 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-16 11:17:23.905  1018  1366 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-16 11:17:23.905  1018  1366 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:23.905  1018  1366 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:23.905  1018  1366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:23.915  1967  4310 I CheckinService: Checking schedule, now: 1458123443927 next: 1458246240395
,03-16 11:17:23.915  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:23.915  3956  3998 I GFX raster: took 0.627656ms for 96*96 texture 0
03-16 11:17:23.915  4286  4315 D SPPClientService: PushLog.txt file is not deleted.
,03-16 11:17:23.915  4286  4315 D SPPClientService: PushLog.txt file is not deleted.
03-16 11:17:23.915  4286  4315 D SPPClientService: ============PushLog. stop!
,03-16 11:17:23.915  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8204b58 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8204c00 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:23.925  1967  4310 I CheckinService: active receiver: disabled
,03-16 11:17:23.945  1967  4321 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED
,03-16 11:17:23.945  1018  1366 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-16 11:17:23.945  1018  1366 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,03-16 11:17:23.945  1018  1366 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:23.945  1018  1366 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 11:17:23.945  1018  1366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:23.955  4225  4261 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-16 11:17:23.975  4225  4261 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-16 11:17:23.975  3956  3998 I AMMetaDataParserService: Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,03-16 11:17:23.975  4225  4261 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,03-16 11:17:23.975  4225  4261 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,03-16 11:17:23.985  1018  1574 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,03-16 11:17:23.985  4225  4262 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-16 11:17:23.985  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:23.985  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:23.985  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:23.985  4225  4261 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/03/18/16:12:11
03-16 11:17:23.985  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:23.985  4225  4261 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/03/16/11:17:23
,03-16 11:17:23.985  4225  4261 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,03-16 11:17:23.985  4225  4261 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,03-16 11:17:23.995  4225  4262 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-16 11:17:23.995  4326  4326 E Zygote  : MountEmulatedStorage(),
03-16 11:17:23.995  4326  4326 E Zygote  : v2
03-16 11:17:23.995  4326  4326 I libpersona: KNOX_SDCARD checking this for 10041
03-16 11:17:23.995  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:23.995  4326  4326 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:23.995  3956  3998 I GFX raster: took 0.858125ms for 96*96 texture 0
03-16 11:17:23.995  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8204b58 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8207078 counterpartCT=4 counterpartW=96 counterparth=96
03-16 11:17:23.995  4326  4326 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:24.005  1018  1574 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4326 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-16 11:17:24.005  1018  1574 I ActivityManager: Killing 3590:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,03-16 11:17:24.005  4326  4326 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:24.015  4326  4326 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-16 11:17:24.025  4225  4261 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,03-16 11:17:24.045  4326  4326 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:24.045  4326  4326 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:24.045  4225  4262 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-16 11:17:24.055  1967  4320 I SystemUpdateService: cancelUpdate (empty URL)
,03-16 11:17:24.055  1967  4320 I SystemUpdateService: active receiver: disabled
,03-16 11:17:24.065  3956  3998 I AMMetaDataParserService: Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,03-16 11:17:24.065  4225  4262 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-16 11:17:24.065  4225  4262 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-16 11:17:24.065  4225  4262 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-16 11:17:24.065  4225  4262 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-16 11:17:24.075  4225  4262 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,03-16 11:17:24.075  4225  4262 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
03-16 11:17:24.075  1018  1044 W libprocessgroup: failed to open /acct/uid_10060/pid_3590/cgroup.procs: No such file or directory
,03-16 11:17:24.075  4225  4262 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-16 11:17:24.085  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
03-16 11:17:24.085  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
03-16 11:17:24.085  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
03-16 11:17:24.085  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
03-16 11:17:24.085  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
03-16 11:17:24.085  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageCompose
03-16 11:17:24.085  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:24.085  3956  3998 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-16 11:17:24.085  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
03-16 11:17:24.085  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
03-16 11:17:24.085  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
03-16 11:17:24.085  3956  3998 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-16 11:17:24.085  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
03-16 11:17:24.085  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
03-16 11:17:24.085  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.DebugActivity
03-16 11:17:24.085  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
03-16 11:17:24.085  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
03-16 11:17:24.085  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
03-16 11:17:24.085  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SearchActivity
03-16 11:17:24.085  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:24.085  3956  3998 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 11:17:24.085  3956  3998 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-16 11:17:24.085  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
03-16 11:17:24.085  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
03-16 11:17:24.085  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,03-16 11:17:24.085  1018  3034 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 11:17:24.095  1018  3034 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:24.095  1018  3034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:24.095  1018  3034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:24.105  1018  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 11:17:24.105  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:24.105  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:24.105  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:24.115  1967  4321 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 11:17:24.145  4225  4262 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-16 11:17:24.155  4225  4261 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,03-16 11:17:24.155  4225  4261 I DBG_POLICYDM: [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-16 11:17:24.175  1018  1573 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-16 11:17:24.175  1018  1573 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:24.175  1018  1573 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 11:17:24.175  1018  1573 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:24.215  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
03-16 11:17:24.215  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
03-16 11:17:24.215  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
03-16 11:17:24.215  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
03-16 11:17:24.215  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
03-16 11:17:24.215  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:24.215  3956  3998 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-16 11:17:24.215  3956  3998 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-16 11:17:24.215  3956  3998 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 11:17:24.215  3956  3998 I AMMetaDataParserService: Resource data:2131099648
,03-16 11:17:24.225  4225  4262 I DBG_POLICYDM: [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,03-16 11:17:24.245  1018  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
03-16 11:17:24.245  1018  1044 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,03-16 11:17:24.245  3956  3998 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,03-16 11:17:24.255  3956  3998 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 11:17:24.255  3956  3998 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-16 11:17:24.255  3956  3998 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 11:17:24.255  3956  3998 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 11:17:24.255  3956  3998 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-16 11:17:24.255  3956  3998 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
,03-16 11:17:24.255  3956  3998 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 11:17:24.265  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:24.265  3956  3998 I GFX raster: took 0.702552ms for 96*96 texture 0
03-16 11:17:24.265  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ea3940 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7eb2968 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:24.265  3956  3998 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-16 11:17:24.295  1967  1967 D SystemUpdateService: onDestroy
,03-16 11:17:24.305  1967  4321 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,03-16 11:17:24.315  4326  4326 I SA      : [SSP] onCreated
,03-16 11:17:24.325  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:24.335  3956  3998 I GFX construct_block_size_descriptor_2d second part: took 2.800157ms for 0*0 texture 0
,03-16 11:17:24.395  1645  2759 I art     : Explicit concurrent mark sweep GC freed 5020(205KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 826us total 43.105ms
,03-16 11:17:24.405  1645  1673 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-16 11:17:24.415  4267  4267 D StrictMode: StrictMode policy violation; ~duration=861 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-16 11:17:24.415  4267  4267 D StrictMode: StrictMode policy violation; ~duration=848 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-16 11:17:24.415  4267  4267 D StrictMode: StrictMode policy violation; ~duration=740 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.io.File.doAccess(File.java:283)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.io.File.exists(File.java:363)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityTh,read.main(ActivityThread.java:6145)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-16 11:17:24.415  4267  4267 D StrictMode: StrictMode policy violation; ~duration=738 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-16 11:17:24.415  4267  4267 D StrictMode: StrictMode policy violation; ~duration=734 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-16 11:17:24.415  4267  4267 D StrictMode: StrictMode policy violation; ~duration=732 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.r.k.c(PG:1187)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.r.k.a(PG:2107)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.r.v.a(PG:1206)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.r.y.a(PG:2233)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.r.e.b(PG:170)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.r.e.b(PG:13188)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-16 11:17:24.415  4267  4267 D StrictMode: StrictMode policy violation; ~duration=729 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.r.k.c(PG:1187)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.r.k.b(PG:14147)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.r.k.c(PG:583)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.r.v.a(PG:1206)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.r.y.a(PG:2233)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.r.e.b(PG:170)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.r.e.b(PG:13188)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-16 11:17:24.415  4267  4267 D StrictMode: StrictMode policy violation; ~duration=631 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.io.File.doAccess(File.java:283)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.io.File.exists(File.java:363)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-16 11:17:24.415  1018  1573 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
03-16 11:17:24.415  4267  4267 D StrictMode: StrictMode policy violation; ~duration=631 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.io.File.doAccess(File.java:283)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.io.File.exists(File.java:363)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-16 11:17:24.415  4267  4267 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-16 11:17:24.415  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:24.415  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:24.425  3956  3998 I GFX generate_partition_tables: took 8.900729ms for 0*0 texture 0
03-16 11:17:24.415  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:24.425  3956  3998 I GFX raster: took 12.937135ms for 96*96 texture 0
03-16 11:17:24.415  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:24.425  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ce4568 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7eb18f0 counterpartCT=4 counterpartW=96 counterparth=96
03-16 11:17:24.425  3956  3998 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
03-16 11:17:24.445  4357  4357 E Zygote  : MountEmulatedStorage()
03-16 11:17:24.445  4357  4357 E Zygote  : v2
03-16 11:17:24.445  4357  4357 I libpersona: KNOX_SDCARD checking this for 1000
03-16 11:17:24.445  4357  4357 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:24.445  4357  4357 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-16 11:17:24.445  4357  4357 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:24.445  1018  1573 I ActivityManager: Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4357 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-16 11:17:24.445  4357  4357 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 11:17:24.445  1018  1573 I ActivityManager: Killing 2777:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,03-16 11:17:24.475  1856  1856 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-16 11:17:24.475  4357  4357 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 11:17:24.475  4357  4357 D ActivityThread: Added TimaKeyStore provider
03-16 11:17:24.485  1856  4374 D GCM     : GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
03-16 11:17:24.495  1856  1856 I GCoreUlr: DispatchingService.onCreate()
,03-16 11:17:24.495   275   872 D EnterpriseController: uids 10012
03-16 11:17:24.495   275   872 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-16 11:17:24.495   275   872 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,03-16 11:17:24.515  1018  1044 W libprocessgroup: failed to open /acct/uid_10120/pid_2777/cgroup.procs: No such file or directory
,03-16 11:17:24.535  1018  1142 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
03-16 11:17:24.535  1018  1142 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-16 11:17:24.535  1018  1142 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:24.535  1018  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:24.535  1018  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,03-16 11:17:24.545  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:24.545  3956  3998 I GFX raster: took 0.805781ms for 96*96 texture 0
03-16 11:17:24.545  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7c00750 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7eb2968 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:24.555  1967  4321 I AuthZen : Fetching signing key...
,03-16 11:17:24.565  4326  4326 I SA      : [TPM] There is no property file
,03-16 11:17:24.565  4225  4262 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-16 11:17:24.575  4326  4326 I SA      : [SCU] isHaveSA() - false
,03-16 11:17:24.585  4326  4326 I SA      : [TPM] getModelProperty : null
,03-16 11:17:24.585  4326  4326 I SA      : [TPM] getCSCProperty : null
,03-16 11:17:24.585  4326  4326 I SA      : [DM] FLOATING AMOLED FEATURE: true
,03-16 11:17:24.585  4326  4326 I SA      : [DM] PRODUCT AMOLED FEATURE: false
03-16 11:17:24.585  4326  4326 I SA      : [DM] TFT FEATURE: false
,03-16 11:17:24.595  3956  3998 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-16 11:17:24.595  1967  4321 I AuthZen : Signing key fetched successfully!
,03-16 11:17:24.595  4326  4326 I SA      : [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
,03-16 11:17:24.605  4326  4326 I SA      : [DM] init START
,03-16 11:17:24.615  4357  4357 D StatusChecker: onReceive : android.intent.action.BOOT_COMPLETED
,03-16 11:17:24.625  4357  4357 I StatusChecker: onReceive : net.mt.init : DONE
,03-16 11:17:24.625  1967  4321 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 11:17:24.625  1018  3034 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,03-16 11:17:24.635  4225  4262 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,03-16 11:17:24.635  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:24.635  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:24.635  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:24.635  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:24.645  4326  4326 I SA      : [DM] This device is not a Vodafone
,03-16 11:17:24.665  4384  4384 E Zygote  : MountEmulatedStorage()
03-16 11:17:24.665  4384  4384 E Zygote  : v2
03-16 11:17:24.665  4384  4384 I libpersona: KNOX_SDCARD checking this for 10116
03-16 11:17:24.665  4384  4384 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:24.665  4384  4384 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-16 11:17:24.665  4384  4384 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:24.665  1018  3034 I ActivityManager: Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4384 uid=10116 gids={50116, 9997} abi=armeabi-v7a
03-16 11:17:24.665  4384  4384 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:24.665  1018  3034 I ActivityManager: Killing 3617:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,03-16 11:17:24.685  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:24.695  3956  3998 I GFX raster: took 0.662969ms for 96*96 texture 0
,03-16 11:17:24.695  1018  3034 I ActivityManager: Killing 3640:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
03-16 11:17:24.695   288   288 E SMD     : DCD OFF
,03-16 11:17:24.705  4384  4384 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:24.705  4326  4326 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
03-16 11:17:24.705  4326  4326 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,03-16 11:17:24.705  4384  4384 D ActivityThread: Added TimaKeyStore provider
03-16 11:17:24.705  4326  4326 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
03-16 11:17:24.705  4326  4326 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,03-16 11:17:24.705  4326  4326 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
03-16 11:17:24.705  4326  4326 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
03-16 11:17:24.705  4326  4326 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,03-16 11:17:24.705  1856  4372 I GCM     : GCM config loaded
,03-16 11:17:24.705  4326  4326 W ResourceType: No package identifier when getting value for resource number 0x00000000
,03-16 11:17:24.705  4326  4326 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,03-16 11:17:24.715  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7eb18f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7eb2968 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:24.725  1967  4321 D a       : Opening database auth.proximity.permit_store...
,03-16 11:17:24.735  1967  4321 D AuthZenTransactionCache: Initialized cache in: /data/data/com.google.android.gms/files
,03-16 11:17:24.735  1967  4321 D AuthZenTransactionCache: Clearing transaction cache
,03-16 11:17:24.745  3956  3998 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-16 11:17:24.745  4326  4326 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,03-16 11:17:24.745  4326  4326 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
03-16 11:17:24.745  4326  4326 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,03-16 11:17:24.745  4326  4326 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
03-16 11:17:24.745  4326  4326 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,03-16 11:17:24.745  4326  4326 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
03-16 11:17:24.745  4326  4326 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,03-16 11:17:24.745  4326  4326 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,03-16 11:17:24.755  3259  3343 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,03-16 11:17:24.755  4326  4326 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,03-16 11:17:24.755  4326  4326 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,03-16 11:17:24.755  4326  4326 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,03-16 11:17:24.755  4326  4326 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
03-16 11:17:24.755  4326  4326 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,03-16 11:17:24.755  4326  4326 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,03-16 11:17:24.765  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:24.765  3956  3998 I GFX raster: took 0.641511ms for 96*96 texture 0
03-16 11:17:24.765  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7acf8d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7eb2968 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:24.775  3956  3998 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-16 11:17:24.785  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
03-16 11:17:24.795  4326  4326 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
03-16 11:17:24.795  4326  4326 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
03-16 11:17:24.795  3956  3998 I GFX raster: took 0.838645ms for 96*96 texture 0
03-16 11:17:24.795  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7eb2968 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e71ce8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:24.805  4326  4326 I SA      : [SCU] isHaveSA() - false,
03-16 11:17:24.805  4326  4326 I SA      : support phone number id : false
03-16 11:17:24.805  4326  4326 I SA      : [DM] Supports Ref Jpn : true
,03-16 11:17:24.805  4384  4384 I PageBuddyNotiSvc: Intent received : action=android.intent.action.BOOT_COMPLETED
,03-16 11:17:24.805  4326  4326 I SA      : [DM] init END
,03-16 11:17:24.805  3956  3998 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-16 11:17:24.805  1018  1142 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-16 11:17:24.805  1018  1142 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,03-16 11:17:24.805  1018  1142 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:24.805  1018  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 11:17:24.815  1856  4380 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
03-16 11:17:24.815  1018  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:24.815  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
03-16 11:17:24.815  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
03-16 11:17:24.815  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:24.815  3956  3998 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 11:17:24.815  3956  3998 I AMMetaDataParserService: Resource data:2131099648
,03-16 11:17:24.815  3956  3998 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-16 11:17:24.815  3956  3998 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 11:17:24.815  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:24.815  3956  3998 I GFX raster: took 0.702500ms for 96*96 texture 0
03-16 11:17:24.815  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ea3940 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e71ce8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:24.825  4326  4326 I SA      : [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
03-16 11:17:24.825  4326  4326 I SA      : [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,03-16 11:17:24.825  4384  4384 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,03-16 11:17:24.825  1018  1345 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 11:17:24.825  3956  3998 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-16 11:17:24.835   275   872 D EnterpriseController: uids 1000
03-16 11:17:24.835   275   872 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-16 11:17:24.835   275   872 D Netd    : getNetworkForDns: using netid 502 for uid 1000
,03-16 11:17:24.835  1018  1044 W libprocessgroup: failed to open /acct/uid_10062/pid_3617/cgroup.procs: No such file or directory
03-16 11:17:24.835  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3640/cgroup.procs: No such file or directory
,03-16 11:17:24.835  1018  1345 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:24.835  1018  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 11:17:24.835  1018  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,03-16 11:17:24.845  1018  2954 D ActivityManager: startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
,03-16 11:17:24.845  1018  2954 D ActivityManager: retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,03-16 11:17:24.845  1018  2954 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:24.845  4384  4384 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,03-16 11:17:24.845  1018  2954 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-16 11:17:24.845  1018  2954 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,03-16 11:17:24.855  4326  4326 I SA      : [OR] onReceive END
,03-16 11:17:24.855  1856  2060 W GCoreFlp: No location to return for getLastLocation()
,03-16 11:17:24.855  1856  1879 W FusedLocationProvider: location=null
,03-16 11:17:24.855  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:24.855  3956  3998 I GFX raster: took 0.664949ms for 96*96 texture 0
,03-16 11:17:24.865  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ce4568 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8208588 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:24.865  1018  3034 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,03-16 11:17:24.875  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:24.875  3956  3998 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
03-16 11:17:24.875  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:24.875  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:24.875  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:24.885  4408  4408 E Zygote  : MountEmulatedStorage()
,03-16 11:17:24.885  4408  4408 E Zygote  : v2
03-16 11:17:24.885  4408  4408 I libpersona: KNOX_SDCARD checking this for 10125
,03-16 11:17:24.885  4408  4408 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:24.885  4408  4408 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-16 11:17:24.885  1018  3034 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4408 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
03-16 11:17:24.895  4408  4408 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:24.895  1018  1045 I ActivityManager: Waited long enough for: ServiceRecord{352c7f36 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
03-16 11:17:24.895  4408  4408 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 11:17:24.895  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:24.895  3956  3998 I GFX raster: took 0.626302ms for 96*96 texture 0
03-16 11:17:24.895  1018  1045 D ActivityManager: startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
03-16 11:17:24.895  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7c00750 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7eb11b0 counterpartCT=4 counterpartW=96 counterparth=96
03-16 11:17:24.895  1018  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:24.905  1018  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:24.905  1018  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:24.905  1018  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:24.915  3956  3998 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521,
,03-16 11:17:24.915  4326  4326 I SA      : [TPMU]  strSIMState ,	:SIM_STATE_ABSENT
,03-16 11:17:24.915  4326  4326 I SA      : [ODM] queryOpenData(key= GEO_IP ),
03-16 11:17:24.925  4417  4417 E Zygote  : MountEmulatedStorage(),
03-16 11:17:24.925  4417  4417 I libpersona: KNOX_SDCARD checking this for 10042
03-16 11:17:24.925  4417  4417 E Zygote  : v2
03-16 11:17:24.925  4417  4417 I libpersona: KNOX_SDCARD not a persona,
03-16 11:17:24.925  4417  4417 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:24.925  4417  4417 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-16 11:17:24.925  4417  4417 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-16 11:17:24.935  1018  1045 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4417 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-16 11:17:24.945  1856  2060 W GCoreFlp: No location to return for getLastLocation()
,03-16 11:17:24.945  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:24.945  1856  2200 W FusedLocationProvider: location=null
,03-16 11:17:24.945  3956  3998 I GFX raster: took 0.888959ms for 96*96 texture 0
03-16 11:17:24.945  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7eb18f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7e71ce8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:24.955  3956  3998 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-16 11:17:24.955  4408  4408 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:24.955  4408  4408 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:24.965  1856  1856 W Auth    : [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,03-16 11:17:24.975  4417  4417 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:24.975  4417  4417 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:24.985  4326  4326 I SA      : getMccForGalaxyJpn step2 GEO_IP MCC : 260
03-16 11:17:24.985  4326  4326 I SA      : [LBE] REF_JPN : true
,03-16 11:17:24.985  4326  4326 I SA      : [BDC] create
,03-16 11:17:24.995  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:24.995  3956  3998 I GFX raster: took 0.844114ms for 96*96 texture 0
03-16 11:17:24.995  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7acf8d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8208588 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:24.995  4408  4408 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 11:17:24.995  4408  4408 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-16 11:17:24.995  4408  4408 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-16 11:17:24.995  3956  3998 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
03-16 11:17:24.995  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-16 11:17:24.995  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,03-16 11:17:25.005  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:25.005  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 11:17:25.005  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:25.025  1856  1856 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:17:25.025  4417  4417 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-16 11:17:25.055  1856  1856 D PersistentNotificationBroadcastReceiver: Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,03-16 11:17:25.065  1018  1130 D NtpTrustedTime: requestTime Success from server:north-america.pool.ntp.org mCachedNtpTime : 1458123444787 mCachedNtpElapsedRealtime : 47172 mCachedNtpCertainty : 75
,03-16 11:17:25.065  4326  4326 I SA      : [DBMV2] getEmailID
,03-16 11:17:25.065  1018  1098 V AlarmManager: waitForAlarm result :4
,03-16 11:17:25.075  1018  1098 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,03-16 11:17:25.075  4326  4326 I SA      : [DBMV2] getDataV02ForItems
03-16 11:17:25.075  4326  4326 I SA      : [SSP] query invoked
,03-16 11:17:25.075  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,03-16 11:17:25.075  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,03-16 11:17:25.085  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
03-16 11:17:25.085  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
03-16 11:17:25.085  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,03-16 11:17:25.085  1018  1130 D NtpTrustedTime: currentTimeMillis() cache hit
03-16 11:17:25.085  1018  1130 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,03-16 11:17:25.085  4326  4326 I SA      : [SCU] get signed id from samsung account2.0 DB.
,03-16 11:17:25.095  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-16 11:17:25.095  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.focus.ContactsSyncIntentService; callingUser = 0; userId(target) = 0
,03-16 11:17:25.095  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:25.095  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 11:17:25.095  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:25.135  4417  4417 I CalendarProvider2: CalendarProvider2.onCreate() called
,03-16 11:17:25.135  1018  1366 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-16 11:17:25.135  1018  1366 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncReceiverService; callingUser = 0; userId(target) = 0
,03-16 11:17:25.145  1018  1366 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:25.145  1018  1366 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 11:17:25.145  4408  4408 D QuickConnect: PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
03-16 11:17:25.145  1018  1366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:25.145  4408  4408 D QuickConnect: Util.setSCRunningSetting - [value]0
,03-16 11:17:25.145  4326  4326 I SA      : [SCU] get signed id from samsung account1.0 DB.
,03-16 11:17:25.155  1018  1142 D SettingsProvider: name = scon_is_running
03-16 11:17:25.155  1018  1142 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 11:17:25.155  1018  1142 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 11:17:25.155  1018  1142 D SettingsProvider: selectionArgs: false
03-16 11:17:25.155  1018  1142 D SettingsProvider: selectionArgs: 10125
03-16 11:17:25.155  1018  1142 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 11:17:25.155  1018  1142 D SettingsProvider: ret = -1
,03-16 11:17:25.155  4326  4326 I SA      : [BDC] destroy
,03-16 11:17:25.155  1018  1142 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,03-16 11:17:25.155  4408  4408 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,03-16 11:17:25.165  4408  4408 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-16 11:17:25.175  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:25.175  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-16 11:17:25.175  3956  3998 I GFX raster: took 0.758646ms for 96*96 texture 0
03-16 11:17:25.175  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7eb2968 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7eb11b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:25.175  4267  4303 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,03-16 11:17:25.175  1018  1031 I ActivityManager: Killing 3390:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,03-16 11:17:25.185  1018  1142 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,03-16 11:17:25.185  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:25.185  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:25.185  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:25.185  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:25.185  3927  3942 W art     : Suspending all threads took: 8.313ms
,03-16 11:17:25.205  4446  4446 E Zygote  : MountEmulatedStorage()
03-16 11:17:25.205  4446  4446 E Zygote  : v2
03-16 11:17:25.205  4446  4446 I libpersona: KNOX_SDCARD checking this for 10131
03-16 11:17:25.205  4446  4446 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:25.205  4446  4446 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:25.205  1856  4380 I GCoreUlr: WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,03-16 11:17:25.205  4446  4446 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:25.205  4446  4446 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:25.215  1018  1142 I ActivityManager: Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4446 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,03-16 11:17:25.215  3956  3998 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-16 11:17:25.225  1018  1142 I ActivityManager: Killing 3663:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,03-16 11:17:25.225   257   505 I SecDataIO: Write to block
,03-16 11:17:25.235  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
03-16 11:17:25.235  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
03-16 11:17:25.235  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
03-16 11:17:25.235  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
03-16 11:17:25.235  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:25.235  3956  3998 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 11:17:25.235  3956  3998 I AMMetaDataParserService: Resource data:2131099648
,03-16 11:17:25.245  2636  3313 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,03-16 11:17:25.245  3956  3998 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
,03-16 11:17:25.245  3956  3998 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 11:17:25.245  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:25.245  3956  3998 I GFX raster: took 0.725105ms for 96*96 texture 0
,03-16 11:17:25.245  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ea3940 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8208588 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:25.245  4446  4446 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:25.255  4446  4446 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:25.255  3259  3259 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,03-16 11:17:25.255  3259  3259 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,03-16 11:17:25.265  3259  3259 E DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,03-16 11:17:25.265  1018  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
03-16 11:17:25.265  1018  1044 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncService; callingUser = 0; userId(target) = 0
,03-16 11:17:25.275  3956  3998 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-16 11:17:25.275  3259  3259 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,03-16 11:17:25.275  1018  1369 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 11:17:25.275  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:25.275  1018  1369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 11:17:25.275  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,03-16 11:17:25.285  2636  2636 I Process : Sending signal. PID: 2636 SIG: 9
,03-16 11:17:25.295  1967  4443 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 183 ms
,03-16 11:17:25.305  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:25.305  3956  3998 I GFX raster: took 0.638958ms for 96*96 texture 0
03-16 11:17:25.305  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ce4568 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7e71ce8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:25.315  3956  3998 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-16 11:17:25.315  4446  4446 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-16 11:17:25.315  4446  4446 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 11:17:25.315  4446  4446 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-16 11:17:25.315  4446  4446 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 11:17:25.325  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:25.325  3956  3998 I GFX raster: took 0.638802ms for 96*96 texture 0
,03-16 11:17:25.325  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7c00750 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb82086e0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:25.345  3956  3998 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-16 11:17:25.355  1018  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 11:17:25.355  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:25.355  1018  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:25.355  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,03-16 11:17:25.355  1018  1515 I ActivityManager: Process com.sec.android.app.sysscope (pid 2636)(adj 0) has died(57,1122)
,03-16 11:17:25.375  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:25.375  3956  3998 I GFX raster: took 0.673229ms for 96*96 texture 0
,03-16 11:17:25.375  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7eb18f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7eb11b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:25.385  3956  3998 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-16 11:17:25.395  4446  4446 D SBrowserFeatureFlag: initialized in static block : loadCscFeatureValue() succeed! 
,03-16 11:17:25.395  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:25.405  1018  1407 D NtpTrustedTime: requestTime Success from server:north-america.pool.ntp.org mCachedNtpTime : 1458123445134 mCachedNtpElapsedRealtime : 47511 mCachedNtpCertainty : 79
03-16 11:17:25.405  1018  1407 D NtpTrustedTime: currentTimeMillis() cache hit
,03-16 11:17:25.405  1018  1407 D AlarmManagerService: Setting time of day to sec=1458123445
03-16 11:17:25.405  1018  1407 D AlarmManagerService: Trying to open a file
,03-16 11:17:25.405  1018  1407 D AlarmManagerService: File Open Success
,03-16 11:17:25.405  1018  1407 D AlarmManagerService: File Close Success
,03-16 11:17:25.405  1018  1407 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
03-16 11:17:25.134  1018  1407 W AlarmManagerService: Unable to set rtc to 1458123445: Invalid argument
03-16 11:17:25.134  1018  1098 V AlarmManager: waitForAlarm result :65536
,03-16 11:17:25.134  3956  3998 I GFX raster: took 0.645937ms for 96*96 texture 0
03-16 11:17:25.134  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7acf8d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8208588 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:25.134  4446  4446 D ManifestProvider: onCreate()
,03-16 11:17:25.134  1018  1345 I art     : Explicit concurrent mark sweep GC freed 39274(2MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 30MB/45MB, paused 3.337ms total 187.937ms
,03-16 11:17:25.134  1018  1028 I art     : WaitForGcToComplete blocked for 118.966ms for cause HeapTrim
,03-16 11:17:25.134  1018  1044 W libprocessgroup: failed to open /acct/uid_10009/pid_3390/cgroup.procs: No such file or directory
,03-16 11:17:25.134  3956  3998 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-16 11:17:25.143  1018  1044 W libprocessgroup: failed to open /acct/uid_10094/pid_3663/cgroup.procs: No such file or directory
,03-16 11:17:25.143  1018  1060 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-16 11:17:25.153  4446  4446 E NetworkSettingsReceiver: onReceive: android.intent.action.BOOT_COMPLETED
,03-16 11:17:25.163  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:25.163  3956  3998 I GFX raster: took 1.027553ms for 96*96 texture 0
03-16 11:17:25.163  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7eb2968 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e71ce8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:25.173  3956  3998 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-16 11:17:25.173  1018  1098 V AlarmManager: No more alarm at this time.nowELAPSED=47564 batch.start=63289
,03-16 11:17:25.183  1018  1018 D OTPFW   : OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1458123445190
,03-16 11:17:25.183  1018  1018 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,03-16 11:17:25.183  1187  1187 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
,03-16 11:17:25.183  1187  1187 D KeyguardUpdateMonitor: handleTimeUpdate
,03-16 11:17:25.183  1018  1018 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
,03-16 11:17:25.183  1187  1187 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-16 11:17:25.193  1743  1743 D accuweather: [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_SET
03-16 11:17:25.193  1743  1743 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,03-16 11:17:25.193  1187  1187 D SecKeyguardClockView: HomeTimezone(): 1
,03-16 11:17:25.203  1187  1187 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:17:25.203  1018  1018 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-16 11:17:25.213  1187  1187 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
,03-16 11:17:25.213  1743  1743 D accuweather: [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,03-16 11:17:25.213  1743  1743 D accuweather: [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,03-16 11:17:25.213  1743  1743 D accuweather: [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,03-16 11:17:25.213  1743  1743 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
03-16 11:17:25.213  1187  1187 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:17:25.213  1743  1743 D accuweather: [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,03-16 11:17:25.213  1187  1187 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-16 11:17:25.213  1187  1187 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-16 11:17:25.213  1743  1743 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,03-16 11:17:25.213  1743  1743 D accuweather: [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,03-16 11:17:25.223  1743  1743 E accuweather: [KK AccuPhone]>>> UIM:1488 [0:0] bTM 11 17
,03-16 11:17:25.223  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 11:17:25.223  1018  1369 D SettingsProvider: name = lockscreen_zoom_panning_effect
,03-16 11:17:25.223  4446  4446 E SBrowserFeatureFlag: initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@36b98fc6
,03-16 11:17:25.223  1018  1369 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,03-16 11:17:25.223  1018  1369 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 11:17:25.223  1018  1369 D SettingsProvider: selectionArgs: false
,03-16 11:17:25.233  1018  1369 D SettingsProvider: selectionArgs: 10054
,03-16 11:17:25.233  1018  1369 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,03-16 11:17:25.233  1018  1369 D SettingsProvider: ret = -1
,03-16 11:17:25.233  4446  4446 D SBrowserFeatureFlag: initialize : initSupportedPkg() succeed! 
,03-16 11:17:25.233  4446  4446 I VerificationLog: SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,03-16 11:17:25.233  1187  1187 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
,03-16 11:17:25.243  1187  1187 D KeyguardEffectViewController: isPreloadedWallpaper=true
03-16 11:17:25.243  1187  1187 I GeometricMosaic_Keyguard: update
,03-16 11:17:25.243  1187  1187 D KeyguardEffectViewUtil: getCurrentWallpaper() mWallpaperPath :null
,03-16 11:17:25.253  1018  1142 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,03-16 11:17:25.253   280   280 W SEC_DRM_PLUGIN_Playready: PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1458123445 after conversion: 1458123445
,03-16 11:17:25.253   280   280 W SEC_DRM_PLUGIN_Playready: PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1458123445 after conversion: 1458123445
,03-16 11:17:25.253  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:25.253  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:25.253  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:25.253  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:25.273  1018  1142 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4470 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,03-16 11:17:25.283  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
03-16 11:17:25.283  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:25.283  3956  3998 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 11:17:25.283  3956  3998 I AMMetaDataParserService: Resource data:2131099648
,03-16 11:17:25.283  4470  4470 E Zygote  : MountEmulatedStorage()
03-16 11:17:25.283  4470  4470 I libpersona: KNOX_SDCARD checking this for 10135
03-16 11:17:25.283  4470  4470 E Zygote  : v2
03-16 11:17:25.283  4470  4470 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:25.283  4470  4470 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:25.293  4470  4470 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:25.293  4470  4470 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:25.323  1018  1515 D ActivityManager: bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START,
03-16 11:17:25.323  1018  1515 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
03-16 11:17:25.323  3956  3998 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-16 11:17:25.323  1018  1515 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:25.323  1018  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:25.323  1018  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-16 11:17:25.333  4470  4470 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:25.333  4470  4470 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:25.343   306   306 I art     : Explicit concurrent mark sweep GC freed 8727(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 20.742ms total 69.210ms
,03-16 11:17:25.343  3956  3998 I AMMetaDataParserService: getResourceTypeNamexml
03-16 11:17:25.343  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:25.343  3956  3998 I GFX raster: took 0.690781ms for 96*96 texture 0
03-16 11:17:25.343  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ea3940 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7eb11b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:25.353  1187  1187 I KeyguardEffectViewUtil: set current wallpaper info
,03-16 11:17:25.363  1018  1030 D SettingsProvider: name = keyguard_current_wallpaper_type,
03-16 11:17:25.363  1018  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 11:17:25.363  1018  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 11:17:25.363  1018  1030 D SettingsProvider: selectionArgs: false
03-16 11:17:25.363  1018  1030 D SettingsProvider: selectionArgs: 10054,
03-16 11:17:25.363  1018  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 11:17:25.363  1018  1030 D SettingsProvider: ret = -1
03-16 11:17:25.363  1018  1345 D SettingsProvider: name = keyguard_current_wallpaper_file_path
03-16 11:17:25.363  1018  1345 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
03-16 11:17:25.363  1018  1345 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 11:17:25.363  1018  1345 D SettingsProvider: selectionArgs: false
03-16 11:17:25.363  1018  1345 D SettingsProvider: selectionArgs: 10054
,03-16 11:17:25.363  1018  1345 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 11:17:25.363  1018  1345 D SettingsProvider: ret = -1
03-16 11:17:25.363  1018  1574 D SettingsProvider: name = keyguard_current_wallpaper_res_id
03-16 11:17:25.363  1018  1574 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 11:17:25.363  1018  1574 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
03-16 11:17:25.363  1018  1574 D SettingsProvider: selectionArgs: false
03-16 11:17:25.363  1018  1574 D SettingsProvider: selectionArgs: 10054
03-16 11:17:25.363  1018  1574 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 11:17:25.363  1018  1574 D SettingsProvider: ret = -1
03-16 11:17:25.363   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 20.790ms,
,03-16 11:17:25.373  3927  3941 W art     : Suspending all threads took: 104.661ms,
,03-16 11:17:25.393   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 19.804ms
,03-16 11:17:25.393  4470  4470 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-16 11:17:25.393  4470  4470 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 11:17:25.393  4470  4470 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 11:17:25.413  3814  3946 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-16 11:17:25.423  3956  3998 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-16 11:17:25.443  1187  1701 D TEST    : run!!!
,03-16 11:17:25.453  4185  4185 W dex2oat : Verification of boolean maps.ai.y.a(java.lang.String) took 104.019ms
,03-16 11:17:25.453  1187  1701 I GeometricMosaic_Renderer: setBackgroundBitmap
,03-16 11:17:25.463  1367  2135 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-16 11:17:25.473  1018  1574 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,03-16 11:17:25.473  1018  1574 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,03-16 11:17:25.473  1018  1574 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:25.473  3259  3343 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,03-16 11:17:25.473  1018  1574 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 11:17:25.473  1018  1574 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-16 11:17:25.473  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-16 11:17:25.473  3956  3998 I GFX raster: took 0.646823ms for 96*96 texture 0
03-16 11:17:25.473  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ce4568 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7ea8be8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:25.483  3956  3998 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-16 11:17:25.493  3259  3343 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-16 11:17:25.503  3259  3343 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,03-16 11:17:25.503  3259  3343 I DBG_DM  : [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,03-16 11:17:25.513  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:25.513  3956  3998 I GFX raster: took 0.631354ms for 96*96 texture 0
03-16 11:17:25.513  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7c00750 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7eacc38 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:25.513  3956  3998 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-16 11:17:25.523  1018  1142 I ActivityManager: Killing 3681:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,03-16 11:17:25.523  3259  3343 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-16 11:17:25.533  3259  3343 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 3
,03-16 11:17:25.543  3259  3343 I DBG_DM  : [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,03-16 11:17:25.543  3259  3343 I DBG_DM  : [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,03-16 11:17:25.573  1018  1369 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,03-16 11:17:25.573  1018  1369 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,03-16 11:17:25.573  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:25.573  1018  1369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:25.573  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-16 11:17:25.573  1018  1366 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,03-16 11:17:25.573  1018  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:25.573  1018  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:25.573  1018  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:25.573  1018  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:25.583  3259  3343 I DBG_DM  : [IlIlllIlllllIlIllllI(177/lllIlIlIIIllIIlIllIl)] nDownloadPostpone is [3]
,03-16 11:17:25.603  4497  4497 E Zygote  : MountEmulatedStorage()
03-16 11:17:25.603  4497  4497 I libpersona: KNOX_SDCARD checking this for 10139
03-16 11:17:25.603  4497  4497 E Zygote  : v2
03-16 11:17:25.603  4497  4497 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:25.603  4497  4497 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-16 11:17:25.603  3259  3259 I DBG_DM  : [com.wssyncmldm.llIIllllIIlllIIIIlll(1140/handleMessage)] 
,03-16 11:17:25.603  3259  3259 I DBG_DM  : [com.wssyncmldm.XDMService(685/llIIlIlIIIllIIIIIllI)] 
03-16 11:17:25.603  1018  1366 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4497 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
03-16 11:17:25.603  4497  4497 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:25.603  4497  4497 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:25.613  3259  3343 I DBG_DM  : [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,03-16 11:17:25.613  1856  4380 I art     : Explicit concurrent mark sweep GC freed 17517(1191KB) AllocSpace objects, 17(272KB) LOS objects, 40% free, 12MB/21MB, paused 10.750ms total 352.104ms
,03-16 11:17:25.613  3259  3343 I DBG_DM  : [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
03-16 11:17:25.613  3259  3343 I DBG_DM  : [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,03-16 11:17:25.623  1018  1044 W libprocessgroup: failed to open /acct/uid_10014/pid_3681/cgroup.procs: No such file or directory
,03-16 11:17:25.623  3259  3343 I DBG_DM  : [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,03-16 11:17:25.633  3259  3259 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-16 11:17:25.633  1018  1142 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,03-16 11:17:25.633  1018  1142 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,03-16 11:17:25.643  3259  3259 I DBG_DM  : [com.wssyncmldm.ui.XUIFotaPostponeActivity(501/llIIIIlllllIIllIIllI)] 
,03-16 11:17:25.643  4497  4497 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:25.643  1018  1142 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:25.643  1018  1142 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:25.643  1018  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-16 11:17:25.643  4497  4497 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:25.653  1856  4380 I GCoreUlr: Unbound from all location providers
03-16 11:17:25.653  1856  4380 I GCoreUlr: Place inference reporting - stopped
,03-16 11:17:25.673  3259  3259 I DBG_DM  : [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,03-16 11:17:25.683  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:25.683  3956  3998 I GFX raster: took 0.631407ms for 96*96 texture 0
03-16 11:17:25.683  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ce4568 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb82084a8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:25.683  4497  4497 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-16 11:17:25.683  4497  4497 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-16 11:17:25.683  4497  4497 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-16 11:17:25.683  4497  4497 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-16 11:17:25.683  4497  4497 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 11:17:25.703  3956  3998 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-16 11:17:25.723  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:25.723  3956  3998 I GFX raster: took 0.660989ms for 96*96 texture 0
03-16 11:17:25.723  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb805c0d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e4fcd8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:25.723  3259  3259 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
,03-16 11:17:25.733  1856  1856 I GCoreUlr: DispatchingService.onDestroy()
03-16 11:17:25.733  1856  1856 I GCoreUlr: Stopping handler for UlrDispSvcFast
,03-16 11:17:25.743  1856  1856 I GCoreUlr: Unbound from all location providers
,03-16 11:17:25.743  1856  1856 I GCoreUlr: Place inference reporting - stopped
,03-16 11:17:25.753  3956  3998 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-16 11:17:25.773  1018  1574 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
03-16 11:17:25.773  1018  1574 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-16 11:17:25.773  1018  1018 D WindowManager: showStatusBarByNotification() mOpenByNotification=false
,03-16 11:17:25.773  1018  1018 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-16 11:17:25.773  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:25.773  1187  3918 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 11:17:25.783  3956  3998 I GFX raster: took 0.782501ms for 96*96 texture 0
03-16 11:17:25.783  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ea8790 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7eacc38 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:25.783  1018  1345 I ActivityManager: Killing 3696:com.wssnps/1000 (adj 15): empty #31
,03-16 11:17:25.803  1018  1366 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,03-16 11:17:25.803  3956  3998 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-16 11:17:25.803  1018  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:25.803  1018  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:25.803  1018  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:25.803  1018  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:25.813  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
03-16 11:17:25.813  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:25.813  3956  3998 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 11:17:25.813  3956  3998 I AMMetaDataParserService: Resource data:2131099648
,03-16 11:17:25.813  3956  3998 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-16 11:17:25.813  3956  3998 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 11:17:25.813  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:25.813  3956  3998 I GFX raster: took 0.876250ms for 96*96 texture 0
03-16 11:17:25.813  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7eacc38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb82084a8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:25.813  1018  1366 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4517 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,03-16 11:17:25.823  4517  4517 E Zygote  : MountEmulatedStorage()
03-16 11:17:25.823  4517  4517 E Zygote  : v2
03-16 11:17:25.823  4517  4517 I libpersona: KNOX_SDCARD checking this for 10145
03-16 11:17:25.823  4517  4517 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:25.823  4517  4517 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:25.823  4517  4517 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:25.823  4517  4517 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:25.833  3956  3998 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-16 11:17:25.853  1187  1187 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,03-16 11:17:25.863  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:25.863  3956  3998 I GFX raster: took 0.772344ms for 96*96 texture 0
03-16 11:17:25.863  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7e4fcd8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb82084a8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:25.863  4517  4517 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:25.863  4517  4517 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:25.873  3956  3998 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-16 11:17:25.883  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:25.883  1187  1187 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
03-16 11:17:25.883  1018  1053 D PowerManagerService: [s] UserActivityState : 1 -> 2
,03-16 11:17:25.883  1018  1053 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
03-16 11:17:25.883  1018  1053 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-16 11:17:25.883  3956  3998 I GFX raster: took 0.653802ms for 96*96 texture 0
,03-16 11:17:25.883  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7c00750 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb82084a8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:25.893  1018  1053 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-16 11:17:25.893  1187  1187 D PersonaManager: PersonaID is invalid or persona doesn't exists. : 0
,03-16 11:17:25.893  1187  1187 D PersonaManager: isKioskContainerExistOnDevice
03-16 11:17:25.893  1187  1187 D PersonaManager: isKioskContainerExistOnDevice
,03-16 11:17:25.893  1187  1187 I PhoneStatusBar: Icon Only
,03-16 11:17:25.893  1187  1187 I StatusBar: Icon Only
,03-16 11:17:25.893  1187  1187 D PanelView: There is/are notification(s) 
03-16 11:17:25.893  1187  1187 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-16 11:17:25.893  1187  1187 D PersonaManager: isKioskContainerExistOnDevice
03-16 11:17:25.893  1187  1187 I PhoneStatusBar: Icon Only
03-16 11:17:25.893  1187  1187 I StatusBar: Icon Only
,03-16 11:17:25.893  1187  1187 D PanelView: There is/are notification(s) 
03-16 11:17:25.893  1187  1187 D PanelView: kidsfalse mQsExpansionEnabled:true
03-16 11:17:25.893  1018  1171 D lights  : lcd : 42 +
,03-16 11:17:25.903  3956  3998 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-16 11:17:25.903  4517  4517 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-16 11:17:25.903  4517  4517 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 11:17:25.903  4517  4517 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-16 11:17:25.903  4517  4517 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 11:17:25.903  4517  4517 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 11:17:25.913  1018  1053 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
03-16 11:17:25.913  1018  1053 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-16 11:17:25.913  1018  1171 D lights  : lcd : 42 -
03-16 11:17:25.913  1018  1171 D lights  : lcd : 19 +
,03-16 11:17:25.913  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:25.913  3956  3998 I GFX raster: took 0.657396ms for 96*96 texture 0
03-16 11:17:25.913  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ce4568 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb82084a8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:25.923  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3696/cgroup.procs: No such file or directory
,03-16 11:17:25.933  1018  1171 D lights  : lcd : 19 -
,03-16 11:17:25.933  1018  1053 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
03-16 11:17:25.933  1018  1053 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-16 11:17:25.933  3956  3998 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-16 11:17:25.943  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:25.943  3956  3998 I GFX raster: took 0.662500ms for 96*96 texture 0
,03-16 11:17:25.943  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb805c0d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb82084a8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:25.953  3956  3998 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-16 11:17:25.963  1018  3034 I ActivityManager: Killing 3729:com.sec.factory.camera/1000 (adj 15): empty #31
,03-16 11:17:25.963  1187  1187 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,03-16 11:17:25.963  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:25.963  3956  3998 I GFX raster: took 0.786771ms for 96*96 texture 0
03-16 11:17:25.963  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ea8790 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb82084a8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:25.973  3956  3998 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-16 11:17:25.983  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationList
03-16 11:17:25.983  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:25.983  3956  3998 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 11:17:25.983  3956  3998 I AMMetaDataParserService: Resource data:2131099648
,03-16 11:17:25.983  3956  3998 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-16 11:17:25.983  3956  3998 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 11:17:25.983  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:25.983  3956  3998 I GFX raster: took 0.690000ms for 96*96 texture 0
03-16 11:17:25.983  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7eacc38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb82084a8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:25.983  1018  1030 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 11:17:25.993  3956  3998 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-16 11:17:26.003  1018  1142 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 11:17:26.003  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:26.003  3956  3998 I GFX raster: took 0.663021ms for 96*96 texture 0
,03-16 11:17:26.003  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7e4fcd8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb82084a8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:26.013  3956  3998 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-16 11:17:26.013  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:26.013  3956  3998 I GFX raster: took 0.640729ms for 96*96 texture 0
03-16 11:17:26.023  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7c00750 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb82084a8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:26.023  3956  3998 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-16 11:17:26.023  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3729/cgroup.procs: No such file or directory
,03-16 11:17:26.033  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:26.033  3956  3998 I GFX raster: took 0.633698ms for 96*96 texture 0
03-16 11:17:26.033  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ce4568 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb82084a8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:26.043  3956  3998 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-16 11:17:26.053  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:26.053  3956  3998 I GFX raster: took 0.716041ms for 96*96 texture 0
03-16 11:17:26.053  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb805c0d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb82084a8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:26.053  3956  3998 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-16 11:17:26.053  1018  2954 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 11:17:26.063  1018  1490 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 11:17:26.083  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-16 11:17:26.083  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-16 11:17:26.083  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 11:17:26.083  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 11:17:26.083  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 11:17:26.083  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 11:17:26.083  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:26.083  3956  3998 I GFX raster: took 0.783177ms for 96*96 texture 0
03-16 11:17:26.083  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb7ea8790 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb82084a8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:26.093  3956  3998 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android,.mms.ui.PushMessageDialog
03-16 11:17:26.103  3956  3998 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
,03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
,03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
,03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
,03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity,
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
,03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
,03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
,03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
,03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
,03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
03-16 11:17:26.103  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
,03-16 11:17:26.123  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
03-16 11:17:26.123  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.123  3956  3998 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 11:17:26.123  3956  3998 I AMMetaDataParserService: Resource data:2131165197
,03-16 11:17:26.123  3956  3998 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 11:17:26.123  3956  3998 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 11:17:26.123  3956  3998 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-16 11:17:26.123  3956  3998 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 11:17:26.123  3956  3998 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-16 11:17:26.123  3956  3998 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-16 11:17:26.123  3956  3998 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-16 11:17:26.123  3956  3998 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 11:17:26.123  3956  3998 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-16 11:17:26.123  3956  3998 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 11:17:26.133  3956  3998 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-16 11:17:26.153  3956  3998 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-16 11:17:26.163  1018  1142 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,03-16 11:17:26.163  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:26.163  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:26.163  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:26.163  1018  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:26.173  3956  3998 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-16 11:17:26.183  4539  4539 E Zygote  : MountEmulatedStorage(),
03-16 11:17:26.183  4539  4539 E Zygote  : v2
03-16 11:17:26.183  4539  4539 I libpersona: KNOX_SDCARD checking this for 10072,
03-16 11:17:26.183  4539  4539 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:26.183  4539  4539 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-16 11:17:26.183  1018  1142 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4539 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,03-16 11:17:26.193  4539  4539 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:26.193  4539  4539 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-16 11:17:26.203  1018  1366 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 11:17:26.203  3956  3998 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-16 11:17:26.213  4539  4539 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:26.213  4539  4539 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:26.223  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
03-16 11:17:26.223  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.223  3956  3998 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 11:17:26.223  3956  3998 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 11:17:26.223  3956  3998 I AMMetaDataParserService: Resource data:2131165197
,03-16 11:17:26.223  3956  3998 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-16 11:17:26.223  3956  3998 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 11:17:26.233  3956  3998 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-16 11:17:26.233  4539  4539 D BadgeProvider: onCreate
,03-16 11:17:26.233  4539  4539 D BadgeProvider: DatabaseHelper
,03-16 11:17:26.243  1018  1030 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 11:17:26.243  1018  1574 D ActivityManager: startService callerProcessName:com.android.email, calleePkgName: com.android.email
03-16 11:17:26.243  1018  1574 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-16 11:17:26.243  1018  1574 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:26.243  1018  1574 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:26.243  1018  1574 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,03-16 11:17:26.243  3956  3998 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-16 11:17:26.253  4539  4553 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-16 11:17:26.263  1491  1491 D Launcher.Model: reloadBadges entered.
,03-16 11:17:26.263  4539  4555 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-16 11:17:26.263  4539  4555 D BadgeProvider: sendNotify, [notify] : null
,03-16 11:17:26.263  4539  4555 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-16 11:17:26.263  4539  4555 D BadgeProvider: update, [BadgeCount] : badgecount=0
,03-16 11:17:26.263  4539  4555 D BadgeProvider: update, [UpdateCount] : 1
,03-16 11:17:26.273  3956  3998 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-16 11:17:26.273  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.android.exchange, hostingType: broadcast
,03-16 11:17:26.273  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:26.273  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:26.273  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:26.273  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:26.283  4561  4561 E Zygote  : MountEmulatedStorage()
03-16 11:17:26.283  4561  4561 I libpersona: KNOX_SDCARD checking this for 10146
03-16 11:17:26.283  4561  4561 E Zygote  : v2
03-16 11:17:26.283  4561  4561 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:26.293  4561  4561 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:26.293  4561  4561 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:26.293  4561  4561 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:26.293  1018  1030 I ActivityManager: Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4561 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-16 11:17:26.293  1018  1030 I ActivityManager: Killing 3771:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,03-16 11:17:26.303  1018  1345 I ActivityManager: Killing 3457:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,03-16 11:17:26.303  3956  3998 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-16 11:17:26.323  4561  4561 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:26.323  4561  4561 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:26.333  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.cooliris.media.Gallery
03-16 11:17:26.333  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
03-16 11:17:26.333  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.333  3956  3998 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 11:17:26.333  3956  3998 I AMMetaDataParserService: Resource data:2131165197
,03-16 11:17:26.333  4517  4534 W art     : Verification of boolean com.android.email.activity.MessageListItemOuterContainer.onTouchEvent(android.view.MotionEvent) took 109.417ms
,03-16 11:17:26.333  3956  3998 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-16 11:17:26.333  3956  3998 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 11:17:26.333  4561  4561 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-16 11:17:26.343  3956  3998 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-16 11:17:26.363  3956  3998 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-16 11:17:26.383  1018  1044 W libprocessgroup: failed to open /acct/uid_10100/pid_3771/cgroup.procs: No such file or directory
03-16 11:17:26.383  1018  1044 W libprocessgroup: failed to open /acct/uid_10015/pid_3457/cgroup.procs: No such file or directory
,03-16 11:17:26.393  3956  3998 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-16 11:17:26.413  1018  1490 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 11:17:26.413  3956  3998 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-16 11:17:26.423  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
,03-16 11:17:26.423  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 11:17:26.423  3956  3998 I AMMetaDataParserService: getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
03-16 11:17:26.423  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
,03-16 11:17:26.423  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.423  3956  3998 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
,03-16 11:17:26.423  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
03-16 11:17:26.423  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 11:17:26.423  3956  3998 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-16 11:17:26.423  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
03-16 11:17:26.423  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 11:17:26.423  3956  3998 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-16 11:17:26.423  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
03-16 11:17:26.423  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
,03-16 11:17:26.423  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
03-16 11:17:26.423  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
,03-16 11:17:26.423  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
03-16 11:17:26.423  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
,03-16 11:17:26.423  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.423  3956  3998 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 11:17:26.423  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
,03-16 11:17:26.423  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
03-16 11:17:26.423  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
,03-16 11:17:26.423  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
,03-16 11:17:26.433  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
,03-16 11:17:26.433  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
03-16 11:17:26.433  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
,03-16 11:17:26.433  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
03-16 11:17:26.433  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
,03-16 11:17:26.433  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
03-16 11:17:26.433  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
03-16 11:17:26.433  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
,03-16 11:17:26.433  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
03-16 11:17:26.433  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
03-16 11:17:26.433  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
,03-16 11:17:26.433  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,03-16 11:17:26.433  3956  3998 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,03-16 11:17:26.443  1018  2954 D ActivityManager: startService callerProcessName:com.android.exchange, calleePkgName: com.android.exchange
,03-16 11:17:26.443  1018  2954 D ActivityManager: retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-16 11:17:26.443  1018  2954 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:26.443  1018  2954 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:26.443  1018  2954 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,03-16 11:17:26.443  1018  1345 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
,03-16 11:17:26.453  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:26.453  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:26.453  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:26.453  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:26.453  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camera
,03-16 11:17:26.453  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 11:17:26.453  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
,03-16 11:17:26.463  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE,
03-16 11:17:26.463  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.keyguard.layout
,03-16 11:17:26.463  3956  3998 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 11:17:26.463  3956  3998 I AMMetaDataParserService: Resource data:2131099648
,03-16 11:17:26.463  3956  3998 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.,
03-16 11:17:26.463  3956  3998 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-16 11:17:26.463  3956  3998 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-16 11:17:26.463  3956  3998 I AMMetaDataParserService: getResourceName:com.sec.android.app.camera:xml/assistant
03-16 11:17:26.463  3956  3998 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,03-16 11:17:26.463  3956  3998 I AMMetaDataParserService: getResourceTypeNamexml
03-16 11:17:26.463  3956  3998 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 11:17:26.463  1018  1345 I ActivityManager: Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4577 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-16 11:17:26.473  4577  4577 E Zygote  : MountEmulatedStorage()
03-16 11:17:26.473  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
03-16 11:17:26.473  4577  4577 E Zygote  : v2
03-16 11:17:26.473  1018  1031 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
03-16 11:17:26.473  4577  4577 I libpersona: KNOX_SDCARD checking this for 1000
03-16 11:17:26.473  4577  4577 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:26.473  4577  4577 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-16 11:17:26.473  4577  4577 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:26.473  4577  4577 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:26.483  1018  1366 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-16 11:17:26.483  1018  1515 I ActivityManager: Killing 3838:com.android.managedprovisioning/u0a22 (adj 15): empty #31
,03-16 11:17:26.483  3956  3998 I AMMetaDataParserService: Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,03-16 11:17:26.503  4577  4577 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:26.503  4577  4577 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:26.513  3956  3998 I AMMetaDataParserService: Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,03-16 11:17:26.533  1018  3034 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-16 11:17:26.533  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
03-16 11:17:26.533  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
03-16 11:17:26.533  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
03-16 11:17:26.533  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
03-16 11:17:26.533  3956  3998 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,03-16 11:17:26.553  1018  1369 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,03-16 11:17:26.553  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:26.553  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:26.553  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:26.553  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:26.573  4594  4594 E Zygote  : MountEmulatedStorage()
,03-16 11:17:26.573  4594  4594 I libpersona: KNOX_SDCARD checking this for 1000,
,03-16 11:17:26.573  4594  4594 E Zygote  : v2
03-16 11:17:26.573  1018  1369 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4594 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-16 11:17:26.573  1018  1369 I ActivityManager: Killing 3858:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
03-16 11:17:26.573  1018  1345 W ActivityManager: getTasks: caller 10145 does not hold GET_TASKS; limiting output
,03-16 11:17:26.573  4594  4594 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-16 11:17:26.573  4594  4594 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:26.583  1018  1490 W ActivityManager: getTasks: caller 10146 does not hold GET_TASKS; limiting output
,03-16 11:17:26.583  4561  4583 I Process : Sending signal. PID: 4561 SIG: 9
,03-16 11:17:26.583  4594  4594 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:26.583  4517  4559 I Process : Sending signal. PID: 4517 SIG: 9
,03-16 11:17:26.593  1018  1044 W libprocessgroup: failed to open /acct/uid_10022/pid_3838/cgroup.procs: No such file or directory
03-16 11:17:26.593  4594  4594 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:26.603  4594  4594 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:26.603  4594  4594 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:26.633  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GridSettings
03-16 11:17:26.633  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.633  3956  3998 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 11:17:26.633  3956  3998 I AMMetaDataParserService: Resource data:2131165220
,03-16 11:17:26.643  4594  4594 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,03-16 11:17:26.643  4594  4594 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,03-16 11:17:26.643  4594  4594 D SecurityLogAgent: StateMachine : Current State = 1
03-16 11:17:26.643  4594  4594 D SecurityLogAgent: BootReceiver : completed task. Failed to return wakelock . 
,03-16 11:17:26.643  1018  1031 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-16 11:17:26.643   255   255 E lowmemorykiller: Error writing /proc/4561/oom_score_adj; errno=22
,03-16 11:17:26.643   255   255 E lowmemorykiller: Error writing /proc/4517/oom_score_adj; errno=22
,03-16 11:17:26.643  1018  1031 I ActivityManager: Killing 3875:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,03-16 11:17:26.653  4417  4417 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-16 11:17:26.653  3956  3998 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-16 11:17:26.653  1018  1369 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
03-16 11:17:26.653  1018  1369 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
03-16 11:17:26.653  3956  3998 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-16 11:17:26.653  3956  3998 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 11:17:26.653  3956  3998 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 11:17:26.653  3956  3998 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 11:17:26.653  3956  3998 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-16 11:17:26.653  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:26.653  1018  1369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:26.653  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-16 11:17:26.653  3956  3998 I AMMetaDataParserService: getResourceName:com.android.settings:xml/assistant
03-16 11:17:26.653  3956  3998 I AMMetaDataParserService: getResourceTypeNamexml
03-16 11:17:26.653  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
03-16 11:17:26.653  2583  2583 I Hs20UtilService: Starting #3
,03-16 11:17:26.653  2583  2598 I Hs20UtilService: Message received 5011
03-16 11:17:26.653  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:26.653  1018  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:26.653  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-16 11:17:26.653  1018  1132 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
03-16 11:17:26.653  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:26.663  1018  1132 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-16 11:17:26.663  1018  1132 E WifiNative-wlan0: invaild command id : 215
03-16 11:17:26.663  3956  3998 I GFX raster: took 0.824271ms for 96*96 texture 0
03-16 11:17:26.663  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb85ac508 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb85ac238 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:26.663   255   255 E lowmemorykiller: Error writing /proc/4561/oom_score_adj; errno=22
03-16 11:17:26.663   255   255 E lowmemorykiller: Error writing /proc/4517/oom_score_adj; errno=22
,03-16 11:17:26.663  4594  4594 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-16 11:17:26.663  4594  4594 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-16 11:17:26.663  4594  4594 D SecurityLogAgent: StateMachine : Current State = 1
,03-16 11:17:26.663  3956  3998 I AMMetaDataParserService: Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,03-16 11:17:26.663  4594  4594 D SecurityLogAgent: StateMachine : Changed Current State = 1
,03-16 11:17:26.673  1018  1366 D ActivityManager: startProcessLocked calleePkgName: com.example.hello, hostingType: broadcast
,03-16 11:17:26.673  1018  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:26.673  1018  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:26.673  1018  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:26.673  1018  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:26.683  4610  4610 E Zygote  : MountEmulatedStorage()
03-16 11:17:26.683  4610  4610 E Zygote  : v2
03-16 11:17:26.683  4610  4610 I libpersona: KNOX_SDCARD checking this for 10174
03-16 11:17:26.683  4610  4610 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:26.683  4610  4610 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:26.693  4610  4610 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:26.693   255   255 E lowmemorykiller: Error opening /proc/4561/oom_score_adj; errno=2
03-16 11:17:26.693  1018  1366 I ActivityManager: Start proc com.example.hello for broadcast com.example.hello/io.jxcore.node.ConnectivityChangeListener: pid=4610 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
03-16 11:17:26.693   255   255 E lowmemorykiller: Error writing /proc/4517/oom_score_adj; errno=22
03-16 11:17:26.693  1018  1366 I ActivityManager: Killing 3902:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
03-16 11:17:26.693  4610  4610 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-16 11:17:26.693  1018  1031 I ActivityManager: Process com.android.exchange (pid 4561)(adj 11) has died(63,1129)
03-16 11:17:26.693   255   255 E lowmemorykiller: Error writing /proc/4517/oom_score_adj; errno=22
,03-16 11:17:26.713  3956  3998 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 11:17:26.713  1018  2954 I ActivityManager: Process com.android.email (pid 4517)(adj 11) has died(64,1129)
03-16 11:17:26.713  3956  3998 I GFX raster: took 0.599844ms for 96*96 texture 0
03-16 11:17:26.713  3956  3998 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb85ae450 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb85ae588 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 11:17:26.723  4610  4610 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:26.723  4610  4610 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:26.723  3956  3998 I AMMetaDataParserService: Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,03-16 11:17:26.753  4610  4610 D jxcore_app_log: JniHelper::setJavaVM(0xb7ad3450), pthread_self() = -1224991032
,03-16 11:17:26.753  4610  4610 E JX-Cordova: JXcore wasn't initialized yet
,03-16 11:17:26.763  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SubSettings
,03-16 11:17:26.763  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LabelName
03-16 11:17:26.763  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Password
,03-16 11:17:26.763  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
03-16 11:17:26.763  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.763  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-16 11:17:26.763  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.763  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 11:17:26.773  1314  1314 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
03-16 11:17:26.773  3956  3998 I AMMetaDataPa,rserService: Resource data:Inside bundle  check
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.773  1314  1314 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
,03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
,03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
,03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
,03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
,03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TetherSettings
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
,03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS,
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
,03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-16 11:17:26.773  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
,03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LanguageSettings
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
,03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.793  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.HomeSettings
03-16 11:17:26.793  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-16 11:17:26.793  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DisplaySettings
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
,03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DockSettings
,03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:2,6.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ManageApplications
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RunningServices
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LaunchApplication
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.StorageUse
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.an,droid.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecuritySettings
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CredentialStorage
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetProfileOwner
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.IccLockSettings
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.813  4625  4625 I libpersona: KNOX_SDCARD checking this for 10068
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.813  4625  4625 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
03-16 11:17:26.783  1314  1314 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
03-16 11:17:26.823  1018  1031 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=4625 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ApnEditor
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormat
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormatSd
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppPicker
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsbSettings
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActivityPicker
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BatteryInfo
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Display
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RadioInfo
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ProxySelector
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BandMode
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TestingSettings
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:In,side bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SoundSettings
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GSensorSettings
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreview
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreview
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NewModePreview
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor2014
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewStyleClock
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.WarrantyLegal
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.853  4625  4625 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenHelpActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PhoneVibration
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandHelp
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.783  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android,.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MagazineCard
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SearchActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.AppList
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
03-16 11:17:26.793  3956  3998 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
03-16 11:17:26.793  1314  1314 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
03-16 11:17:26.793  1314  1314 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
03-16 11:17:26.793  1314  1314 I NearbySettings: MountReceiver.onReceive - Keep current state
03-16 11:17:26.813  4625  4625 E Zygote  : MountEmulatedStorage()
03-16 11:17:26.813  4625  4625 E Zygote  : v2
03-16 11:17:26.813  4625  4625 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-16 11:17:26.813  4625  4625 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:26.813  4625  4625 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 11:17:26.843  4625  4625 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 11:17:26.843  4625  4625 D ActivityThread: Added TimaKeyStore provider
03-16 11:17:26.903  4225  4261 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
03-16 11:17:26.903  4225  4261 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
03-16 11:17:26.903  4225  4261 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
03-16 11:17:26.913  4225  4261 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
03-16 11:17:26.913  4225  4261 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
03-16 11:17:26.913  4225  4261 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
03-16 11:17:26.913  4225  4261 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-16 11:17:27.003  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3858/cgroup.procs: No such file or directory
03-16 11:17:27.003  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3875/cgroup.procs: No such file or directory
,03-16 11:17:27.003  1018  1044 W libprocessgroup: failed to open /acct/uid_10069/pid_3902/cgroup.procs: No such file or directory
,03-16 11:17:27.023  4625  4625 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,03-16 11:17:27.023  4625  4625 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,03-16 11:17:27.033  4185  4185 I dex2oat : dex2oat took 4.426s (threads: 4)
,03-16 11:17:27.043  1967  4180 D DexOptUtils: Odex created at:/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex
,03-16 11:17:27.043  1967  4180 D DexOptUtils: Set odex to world readable.
,03-16 11:17:27.053  1967  4180 D DexOptUtils: Renamed odex to /data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.odex
,03-16 11:17:27.053  1018  1369 I ActivityManager: Killing 3544:com.sec.pcw.device/1000 (adj 15): empty #31
,03-16 11:17:27.073  4625  4625 D FileShare-Client: Outbound.stopDelayTimer - 
,03-16 11:17:27.073  1018  1490 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,03-16 11:17:27.083  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:27.083  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:27.083  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:27.083  1018  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:27.093  4640  4640 E Zygote  : MountEmulatedStorage()
03-16 11:17:27.093  4640  4640 I libpersona: KNOX_SDCARD checking this for 10069
03-16 11:17:27.093  4640  4640 E Zygote  : v2
03-16 11:17:27.093  4640  4640 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:27.093  4640  4640 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:27.103  4640  4640 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:27.103  4640  4640 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:27.103  1018  1490 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=4640 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 11:17:27.103  1018  1490 I ActivityManager: Killing 3738:com.samsung.android.sm/1000 (adj 15): empty #31
,03-16 11:17:27.123  4640  4640 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:27.123  4640  4640 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:27.143  4640  4640 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,03-16 11:17:27.153  1018  1574 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:27.153  1018  1574 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:27.153  1018  1574 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:27.153  1018  1574 I ActivityManager: Killing 3239:com.test.thalitest/u0a155 (adj 15): empty #31
,03-16 11:17:27.153  1018  1574 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
03-16 11:17:27.153  1018  1574 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
03-16 11:17:27.153  1018  1574 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
03-16 11:17:27.153  1018  1574 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-16 11:17:27.153  1018  1574 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:27.153  1018  1574 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:27.153  1018  1574 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:27.183  1018  1345 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:27.183  1018  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:27.183  1018  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:27.183  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:27.193  1018  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:27.193  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:27.193  1018  1142 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 11:17:27.193  1018  1142 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:27.193  1018  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:27.193  1018  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:27.203  1018  1313 E Watchdog: !@Sync 1
,03-16 11:17:27.203  1856  1856 D WearableService: callingUid 10012, callindPid: 1856
,03-16 11:17:27.203  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:27.203  1018  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 11:17:27.203  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:27.203  1856  4655 E MDM     : [244] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-16 11:17:27.213  1018  1345 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,03-16 11:17:27.213  1018  1345 W ActivityManager: userId = 0, bbcId = -10000,
03-16 11:17:27.213  1018  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:27.213  1018  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:27.213  1018  1366 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:27.213  1018  1366 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:27.213  1018  1366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:27.223  1018  1515 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:27.223  1018  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:27.223  1018  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:27.223  1018  3034 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:27.223  1018  3034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:27.223  1018  3034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:27.223  1856  1856 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-16 11:17:27.223  1018  2954 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-16 11:17:27.233  1018  2954 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-16 11:17:27.233  1018  2954 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:27.233  1018  2954 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:27.233  1018  2954 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:27.233  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3544/cgroup.procs: No such file or directory
,03-16 11:17:27.233  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:27.233  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:27.233  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 11:17:27.233  1967  4656 D LocationInitializer: Restart initialization of location
,03-16 11:17:27.233  1018  1490 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-16 11:17:27.233  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,03-16 11:17:27.233  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:27.233  1018  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:27.233  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:27.233  1018  1141 D SettingsProvider: name = audio_safe_volume_state
,03-16 11:17:27.243  1018  1345 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-16 11:17:27.243  1018  1345 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,03-16 11:17:27.243  1018  1345 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:27.243  1018  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:27.243  1018  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:27.253  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:27.253  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:27.253  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:27.253  1856  1856 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 11:17:27.253  1018  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,03-16 11:17:27.253  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:27.253  1018  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:27.253  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:27.263  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3738/cgroup.procs: No such file or directory
,03-16 11:17:27.263  1018  1044 W libprocessgroup: failed to open /acct/uid_10155/pid_3239/cgroup.procs: No such file or directory
03-16 11:17:27.263  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:27.263  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:27.263  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:27.263  1018  1515 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-16 11:17:27.263  1018  1515 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,03-16 11:17:27.263  1018  1515 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:27.263  1018  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:27.263  1018  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:27.273  1856  2060 W GCoreFlp: No location to return for getLastLocation()
,03-16 11:17:27.273  1856  4658 W FusedLocationProvider: location=null
,03-16 11:17:27.283  1018  1369 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,03-16 11:17:27.283  1018  1369 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-16 11:17:27.283  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:27.283  1018  1369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:27.283  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-16 11:17:27.293  2583  2583 I Hs20UtilService: Starting #4
,03-16 11:17:27.293  2583  2598 I Hs20UtilService: Message received 5007
,03-16 11:17:27.293  1314  1314 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-16 11:17:27.293  1314  1314 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-16 11:17:27.293  1314  1314 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-16 11:17:27.293  1314  1314 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,03-16 11:17:27.293  1314  1314 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
03-16 11:17:27.293  1314  1314 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-16 11:17:27.303  1018  1366 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,03-16 11:17:27.303  1018  1366 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-16 11:17:27.303  1018  1366 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:27.303  1018  1366 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:27.303  1018  1366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-16 11:17:27.313  2583  2583 I Hs20UtilService: Starting #5
,03-16 11:17:27.313  1314  1314 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-16 11:17:27.313  2583  2598 I Hs20UtilService: Message received 5007
,03-16 11:17:27.313  1314  1314 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-16 11:17:27.323  1018  1142 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
03-16 11:17:27.323  1018  1142 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-16 11:17:27.323  1018  1142 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:27.323  1018  1142 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:27.323  1018  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-16 11:17:27.323  2583  2583 I Hs20UtilService: Starting #6
03-16 11:17:27.323  1314  1314 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-16 11:17:27.323  1314  1314 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-16 11:17:27.323  2583  2598 I Hs20UtilService: Message received 5007
,03-16 11:17:27.323  1314  1314 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-16 11:17:27.323  1314  1314 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,03-16 11:17:27.323  1314  1314 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
03-16 11:17:27.323  1314  1314 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-16 11:17:27.333  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,03-16 11:17:27.333  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-16 11:17:27.333  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:27.333  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:27.333  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-16 11:17:27.333  2583  2583 I Hs20UtilService: Starting #7
,03-16 11:17:27.343  2583  2598 I Hs20UtilService: Message received 5007
,03-16 11:17:27.343  1314  1314 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-16 11:17:27.343  1314  1314 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-16 11:17:27.343  1018  1142 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,03-16 11:17:27.353  1018  1345 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,03-16 11:17:27.353  1018  1345 D SecContentProvider2: mCursor = null
,03-16 11:17:27.353  1018  4657 D SecContentProvider2: uri = 15 selection = getToastGravity
,03-16 11:17:27.353  1018  4657 D SecContentProvider2: mCursor = null
,03-16 11:17:27.353  1018  1369 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,03-16 11:17:27.353  1018  1369 D SecContentProvider2: mCursor = null
,03-16 11:17:27.353  1018  1031 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,03-16 11:17:27.353  1018  1031 D SecContentProvider2: mCursor = null
,03-16 11:17:27.363  1018  1515 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,03-16 11:17:27.363  1018  1515 D SecContentProvider2: mCursor = null
,03-16 11:17:27.363  1018  1030 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,03-16 11:17:27.363  1018  1030 D SecContentProvider2: mCursor = null
,03-16 11:17:27.363  1018  3034 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,03-16 11:17:27.363  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:27.363  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:27.363  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:27.363  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:27.383  4661  4661 E Zygote  : MountEmulatedStorage()
03-16 11:17:27.383  4661  4661 I libpersona: KNOX_SDCARD checking this for 1000
03-16 11:17:27.383  4661  4661 E Zygote  : v2
03-16 11:17:27.383  4661  4661 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:27.383  4661  4661 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-16 11:17:27.383  1018  3034 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=4661 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-16 11:17:27.383   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=4, Uoast
,03-16 11:17:27.383  4661  4661 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-16 11:17:27.383  4661  4661 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:27.393  1018  4657 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
,03-16 11:17:27.393  1018  1053 D DisplayPowerController: getFinalBrightness : Summary is 60 -> 60
03-16 11:17:27.393  1018  1053 D DisplayPowerController: animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-16 11:17:27.393  1018  1053 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-16 11:17:27.403  1187  1187 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-16 11:17:27.403  1018  2866 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 11:17:27.413  1018  1171 D lights  : lcd : 47 +
,03-16 11:17:27.413  4661  4661 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:27.413  4661  4661 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:27.423   288   288 E SMD     : DCD OFF
,03-16 11:17:27.423  1018  1053 D DisplayPowerController: getFinalBrightness : Summary is 60 -> 60
,03-16 11:17:27.433  1018  1053 D DisplayPowerController: animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-16 11:17:27.433  1018  1171 D lights  : lcd : 47 -
,03-16 11:17:27.433  1018  1171 D lights  : lcd : 60 +
,03-16 11:17:27.443  4661  4661 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,03-16 11:17:27.443  4661  4661 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
03-16 11:17:27.443  4661  4661 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-16 11:17:27.443  1018  1171 D lights  : lcd : 60 -
,03-16 11:17:27.443  1018  1053 D DisplayPowerController: getFinalBrightness : Summary is 60 -> 60
,03-16 11:17:27.443  1018  1053 D DisplayPowerController: animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-16 11:17:27.453  4661  4661 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-16 11:17:27.453  4661  4661 I PCWCLIENTTRACE_PushUtil: sales region : global
03-16 11:17:27.453  4661  4661 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-16 11:17:27.453  4661  4661 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,03-16 11:17:27.453  1018  1573 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=10, mSplitNum[1]=17, mSplitNum[2]=26, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=34
,03-16 11:17:27.453  1018  1573 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,03-16 11:17:27.453  1018  1573 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,03-16 11:17:27.463  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:27.463  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:27.463  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:27.463  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:27.473  4678  4678 E Zygote  : MountEmulatedStorage()
,03-16 11:17:27.473  4678  4678 I libpersona: KNOX_SDCARD checking this for 10111
03-16 11:17:27.473  4678  4678 E Zygote  : v2
03-16 11:17:27.473  4678  4678 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:27.473  4678  4678 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-16 11:17:27.473  1018  1573 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4678 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:17:27.483  4678  4678 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:27.483  1018  1573 I ActivityManager: Killing 3814:com.google.android.gm/u0a101 (adj 15): empty #31
03-16 11:17:27.483  4678  4678 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 11:17:27.493  4594  4594 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-16 11:17:27.493  4594  4594 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-16 11:17:27.493  4594  4594 D SecurityLogAgent: StateMachine : Current State = 1
,03-16 11:17:27.493  4594  4594 D SecurityLogAgent: StateMachine : Changed Current State = 1
,03-16 11:17:27.503  1743  1743 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-16 11:17:27.503  1018  4657 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,03-16 11:17:27.503   306   306 I art     : Explicit concurrent mark sweep GC freed 8740(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 819us total 29.522ms
,03-16 11:17:27.503  3798  3798 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Mar 16 11:17:27 GMT+01:00 2016
03-16 11:17:27.503  1018  4657 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:27.503  1018  4657 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:27.503  1018  4657 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:27.503  1018  4657 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:27.513  4678  4678 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:27.513  4678  4678 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:27.523   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 591us total 17.815ms
,03-16 11:17:27.543   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 602us total 17.412ms,
,03-16 11:17:27.553  4693  4693 E Zygote  : MountEmulatedStorage(),
03-16 11:17:27.553  4693  4693 I libpersona: KNOX_SDCARD checking this for 10159
03-16 11:17:27.553  4693  4693 E Zygote  : v2
03-16 11:17:27.553  4693  4693 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:27.553  4693  4693 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:27.553  1018  4657 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=4693 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-16 11:17:27.553  4693  4693 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:27.553  1018  1490 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
03-16 11:17:27.553  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:27.553  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-16 11:17:27.553  1018  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:27.553  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
03-16 11:17:27.553  4693  4693 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,03-16 11:17:27.573  3798  3798 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-16 11:17:27.583  1367  1388 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 10
,03-16 11:17:27.583  3798  3798 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-16 11:17:27.583  4693  4693 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 11:17:27.583  4693  4693 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:27.593  3798  3798 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-16 11:17:27.593  1743  1743 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,03-16 11:17:27.593  1743  1743 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,03-16 11:17:27.593  1743  1743 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,03-16 11:17:27.593  1743  1743 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
03-16 11:17:27.593  3798  3798 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-16 11:17:27.593  3798  4703 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-16 11:17:27.603  3798  4703 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,03-16 11:17:27.603  1743  1743 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
03-16 11:17:27.603  1743  1743 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-16 11:17:27.603  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,03-16 11:17:27.613  3798  4703 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,03-16 11:17:27.613  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:27.613  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:27.613  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:27.613  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:27.613  3798  4703 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().START
,03-16 11:17:27.613  4225  4709 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
03-16 11:17:27.613  3798  4703 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().START 
03-16 11:17:27.613  4225  4709 I DBG_POLICYDM: [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 0, current network is 2
03-16 11:17:27.613  4225  4709 E DBG_POLICYDM: [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... 
,03-16 11:17:27.613  1018  1044 W libprocessgroup: failed to open /acct/uid_10101/pid_3814/cgroup.procs: No such file or directory
,03-16 11:17:27.623  4710  4710 E Zygote  : MountEmulatedStorage()
03-16 11:17:27.623  4710  4710 E Zygote  : v2
03-16 11:17:27.623  4710  4710 I libpersona: KNOX_SDCARD checking this for 10081
03-16 11:17:27.623  4710  4710 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:27.633  4710  4710 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:27.633  4710  4710 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-16 11:17:27.633  4710  4710 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
03-16 11:17:27.633  1018  1031 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=4710 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:17:27.643  4225  4709 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] ,
,03-16 11:17:27.653  4225  4709 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-16 11:17:27.653  4225  4709 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-16 11:17:27.653  4225  4709 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-16 11:17:27.653  4225  4709 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-16 11:17:27.653  4225  4709 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
03-16 11:17:27.653  4225  4709 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-16 11:17:27.653  4225  4709 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,03-16 11:17:27.663  3798  4703 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().END 
,03-16 11:17:27.663  4710  4710 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 11:17:27.663  3798  4703 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,03-16 11:17:27.663  4225  4709 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,03-16 11:17:27.663  4710  4710 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:27.663  3798  3798 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-16 11:17:27.673  4286  4286 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,03-16 11:17:27.683  4326  4326 I SA      : [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,03-16 11:17:27.683  4326  4326 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
03-16 11:17:27.683  4326  4326 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
03-16 11:17:27.683  4225  4709 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-16 11:17:27.713  1967  4727 I iu.SyncManager: SYNC; picasa accounts
,03-16 11:17:27.723  1967  1967 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-16 11:17:27.723  1967  1967 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-16 11:17:27.743  1967  4727 I iu.UploadsManager: num queued entries: 0
,03-16 11:17:27.743  1967  4727 I iu.UploadsManager: num updated entries: 0
,03-16 11:17:27.743  1967  4727 I iu.SyncManager: NEXT; no task
,03-16 11:17:27.743  4326  4326 I SA      : [SLFUCHKMGR] constructor called
,03-16 11:17:27.743  1018  1366 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-16 11:17:27.743  1018  1366 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-16 11:17:27.753  1018  1366 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:27.753  1018  1366 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:27.753  1018  1366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:27.753  1018  1573 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,03-16 11:17:27.753  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:27.753  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:27.753  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:27.753  1018  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:27.753  4326  4326 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
03-16 11:17:27.753  4326  4326 I SA      : [OR] == isSIMCardReady false ==
,03-16 11:17:27.763  4729  4729 E Zygote  : MountEmulatedStorage(),
03-16 11:17:27.763  1018  1573 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4729 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-16 11:17:27.773  4729  4729 E Zygote  : v2
03-16 11:17:27.773  4729  4729 I libpersona: KNOX_SDCARD checking this for 10010
03-16 11:17:27.773  4729  4729 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:27.773  4729  4729 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:27.773  4729  4729 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-16 11:17:27.773  4729  4729 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,03-16 11:17:27.793  4729  4729 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:27.793  4729  4729 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:27.933  4326  4326 I SA      : [SCU] == networkStateCheck == true
,03-16 11:17:27.933  4326  4326 I SA      : [DM] getCountryCodeFromCSC : PL
03-16 11:17:27.933  4326  4326 I SA      : isChinaCountryCode : false
03-16 11:17:27.933  4326  4326 I SA      : [SCU] is ChinestModel Data Restricted   : false
03-16 11:17:27.933  4326  4326 I SA      : [OR] == networkStateCheck true ==
,03-16 11:17:27.933  4326  4326 I SA      : [OR] GetMyCountryZoneTask
,03-16 11:17:27.943  4326  4326 I SA      : [OR] onReceive END
,03-16 11:17:27.943  1018  3034 I ActivityManager: Killing 3956:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,03-16 11:17:27.943  1241  1241 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,03-16 11:17:27.953  1018  1031 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,03-16 11:17:27.953  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,03-16 11:17:27.953  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:27.953  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:27.953  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-16 11:17:27.963  1018  1573 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
,03-16 11:17:27.963  1018  1573 D SecContentProvider2: mCursor = null
,03-16 11:17:28.063  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3956/cgroup.procs: No such file or directory
,03-16 11:17:28.063  4729  4729 D WaitQueueForNetworkActivate: notifyNetworkActivated
,03-16 11:17:28.073  4678  4678 I MusicStore: Database version: 108
,03-16 11:17:28.113  1018  3034 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,03-16 11:17:28.113  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:28.113  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:28.113  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:28.113  1018  3034 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:28.113  4326  4745 I SA      : [SRS] prepareGetMyCountryZone
,03-16 11:17:28.133  4752  4752 E Zygote  : MountEmulatedStorage(),
03-16 11:17:28.133  4752  4752 E Zygote  : v2
03-16 11:17:28.133  4752  4752 I libpersona: KNOX_SDCARD checking this for 10113
03-16 11:17:28.133  4752  4752 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:28.133  4752  4752 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:28.133  4752  4752 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:28.133  4326  4745 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-16 11:17:28.133  4752  4752 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 11:17:28.133  4326  4745 I SA      : [SSP] query invoked
,03-16 11:17:28.143  1018  3034 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4752 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 11:17:28.143  1018  3034 I ActivityManager: Killing 3927:com.vlingo.midas/u0a31 (adj 15): empty #31
,03-16 11:17:28.163  4752  4752 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:28.163  4752  4752 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:28.183  1018  3034 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,03-16 11:17:28.183  1018  3034 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-16 11:17:28.183  1018  3034 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:28.183  1018  3034 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:28.183  1018  3034 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-16 11:17:28.233  4729  4729 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,03-16 11:17:28.243  1018  1345 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 11:17:28.243  1018  1345 W ActivityManager: Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,03-16 11:17:28.263  1018  1044 W libprocessgroup: failed to open /acct/uid_10031/pid_3927/cgroup.procs: No such file or directory
,03-16 11:17:28.303  1018  1031 I art     : Explicit concurrent mark sweep GC freed 32484(1915KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 30MB/45MB, paused 2.735ms total 164.081ms
,03-16 11:17:28.313  4326  4745 I SA      : [TPMU] GetMccFromDB : null
,03-16 11:17:28.313  4326  4745 I SA      : [SCU] getMccFromPreferece mcc = 260
03-16 11:17:28.313  4326  4745 I SA      : [TPM] isNoProxy(default) : true
,03-16 11:17:28.313  4678  4678 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-16 11:17:28.313  4678  4678 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 11:17:28.323  4326  4745 E File    : fail readDirectory() errno=2
,03-16 11:17:28.343  4678  4678 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-16 11:17:28.403  4678  4678 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-16 11:17:28.403  4678  4678 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16839bae: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-16 11:17:28.403  4678  4678 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-16 11:17:28.403  4678  4678 D AndroidMusic: GMSCore installation verified
,03-16 11:17:28.423  1018  1345 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
03-16 11:17:28.423  1018  1345 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,03-16 11:17:28.423  1018  1345 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:28.423  1018  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:28.423  1018  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-16 11:17:28.433  4678  4678 I ConfigStore: Config Database version: 1
,03-16 11:17:28.443   257   511 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-16 11:17:28.443   257   511 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:17:28.443  4752  4777 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-16 11:17:28.453   257   511 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-16 11:17:28.453   257   511 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:17:28.453  4752  4777 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
03-16 11:17:28.453  1018  2954 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
03-16 11:17:28.453  1018  2954 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,03-16 11:17:28.453  1018  2954 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:28.453  1018  2954 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-16 11:17:28.453  1018  2954 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,03-16 11:17:28.463  4729  4729 D hcjo    : AutoUpdateManager:IDLE:execute
,03-16 11:17:28.473  4729  4729 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,03-16 11:17:28.473  4729  4729 D InitializeManagerStateMachine: exit::IDLE
03-16 11:17:28.473  4729  4729 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,03-16 11:17:28.473  4729  4729 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
03-16 11:17:28.473  4729  4729 D InitializeManagerStateMachine: exit::NETWORK_CHECK
03-16 11:17:28.473  4729  4729 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
03-16 11:17:28.473  4729  4729 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
03-16 11:17:28.473  4729  4729 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
03-16 11:17:28.473  4729  4729 D InitializeManagerStateMachine: entry::SUCCESS
03-16 11:17:28.473  4729  4729 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,03-16 11:17:28.483   257   511 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-16 11:17:28.483   257   511 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:17:28.483  4729  4729 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:345600000
,03-16 11:17:28.483  4752  4780 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-16 11:17:28.483   257   511 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-16 11:17:28.483   257   511 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:17:28.483  4729  4729 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,03-16 11:17:28.483  4752  4780 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
03-16 11:17:28.483  4729  4729 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,03-16 11:17:28.493  4729  4729 D InitializeManagerStateMachine: exit::SUCCESS
03-16 11:17:28.493  4729  4729 D InitializeManagerStateMachine: entry::IDLE
,03-16 11:17:28.553   257   511 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-16 11:17:28.553   257   511 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:17:28.553  4678  4678 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-16 11:17:28.553   257   511 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-16 11:17:28.553   257   511 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:17:28.553  4678  4678 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-16 11:17:28.563   257   511 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-16 11:17:28.563   257   511 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 11:17:28.563  4678  4678 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-16 11:17:28.573  1018  1345 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,03-16 11:17:28.573  1018  1345 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
03-16 11:17:28.573  1018  1345 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:28.573  1018  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:28.573  1018  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-16 11:17:28.583  1018  1030 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,03-16 11:17:28.583  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,03-16 11:17:28.583  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:28.583  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:28.583  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-16 11:17:28.613  1018  1366 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 11:17:28.613  1018  1366 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:28.613  1018  1366 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 11:17:28.613  1018  1366 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,03-16 11:17:28.613  1018  3034 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-16 11:17:28.613  1018  1142 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-16 11:17:28.623  1018  2954 I AudioService: getStreamVolume 3 index 0
,03-16 11:17:28.623  4678  4678 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,03-16 11:17:28.633  4752  4752 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-16 11:17:28.633  4678  4678 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-16 11:17:28.643  4678  4678 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-16 11:17:28.643  4752  4752 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 1038-1039)
03-16 11:17:28.653  4752  4752 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 11:17:28.653  4752  4752 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2930889d}
,03-16 11:17:28.653  4752  4752 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 11:17:28.653  4752  4752 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,03-16 11:17:28.673  1018  1030 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
03-16 11:17:28.673  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-16 11:17:28.673  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:28.673  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 11:17:28.673  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-16 11:17:28.673  1018  1515 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,03-16 11:17:28.673  1018  1515 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,03-16 11:17:28.673  1018  1515 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:28.673  1018  1515 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:28.673  1018  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-16 11:17:28.683  4752  4752 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-16 11:17:28.683  4752  4752 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 11:17:28.683  4752  4752 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-16 11:17:28.683  1018  1490 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,03-16 11:17:28.683  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,03-16 11:17:28.683  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:28.683  1018  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 11:17:28.683  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-16 11:17:28.693  1018  1031 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-16 11:17:28.693  4678  4678 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-16 11:17:28.703  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,03-16 11:17:28.703  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:28.703  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:28.703  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:28.703  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:28.713  4804  4804 E Zygote  : MountEmulatedStorage()
03-16 11:17:28.713  4804  4804 I libpersona: KNOX_SDCARD checking this for 10002
03-16 11:17:28.713  4804  4804 E Zygote  : v2
03-16 11:17:28.713  4804  4804 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:28.723  4804  4804 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:28.723  4804  4804 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-16 11:17:28.723  4752  4752 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
03-16 11:17:28.723  4804  4804 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:28.723  4752  4752 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
03-16 11:17:28.723  4752  4752 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,03-16 11:17:28.723  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4804 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:17:28.733  4752  4752 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-16 11:17:28.733  4752  4752 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-16 11:17:28.733  4752  4752 I Adreno-EGL: Build Date: 04/06/15 Mon
03-16 11:17:28.733  4752  4752 I Adreno-EGL: Local Branch: 
03-16 11:17:28.733  4752  4752 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-16 11:17:28.733  4752  4752 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-16 11:17:28.733  4752  4752 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-16 11:17:28.743  4804  4804 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 11:17:28.743  1018  1490 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
03-16 11:17:28.743  4804  4804 D ActivityThread: Added TimaKeyStore provider
03-16 11:17:28.743  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,03-16 11:17:28.753  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:28.753  1018  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:28.753  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,03-16 11:17:28.753  4678  4678 W GoogleHttpClient: Failed to load SSLCertificateSocketFactory from package
03-16 11:17:28.753  4678  4678 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,03-16 11:17:28.763  4678  4678 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,03-16 11:17:28.763  1018  1490 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,03-16 11:17:28.763  1018  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-16 11:17:28.763  1018  1490 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:28.763  1018  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:28.763  1018  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-16 11:17:28.803  4752  4828 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-16 11:17:28.803  4752  4752 I NSApplication: Starting up...
,03-16 11:17:28.813  1018  1574 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,03-16 11:17:28.813  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:28.813  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:28.813  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:28.813  1018  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:28.833  4833  4833 E Zygote  : MountEmulatedStorage()
03-16 11:17:28.833  4833  4833 E Zygote  : v2
03-16 11:17:28.833  4833  4833 I libpersona: KNOX_SDCARD checking this for 10120
03-16 11:17:28.833  4833  4833 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:28.833  4833  4833 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:28.833  4833  4833 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:28.833  1018  1574 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4833 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-16 11:17:28.833  4833  4833 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-16 11:17:28.833  1018  1574 I ActivityManager: Killing 3405:com.google.android.youtube/u0a166 (adj 15): empty #31
,03-16 11:17:28.853  4833  4833 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:28.853  4833  4833 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:28.873  1018  1515 I ActivityManager: Killing 4161:com.samsung.helphub/1000 (adj 15): empty #31
,03-16 11:17:28.873  1018  1515 I ActivityManager: Killing 4004:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #32
,03-16 11:17:28.883  1018  1345 I ActivityManager: Killing 4065:com.android.vending/u0a28 (adj 15): empty #31
,03-16 11:17:28.893  1018  1369 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,03-16 11:17:28.893  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:28.893  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:28.893  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:28.893  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:28.903  4833  4833 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 11:17:28.903  4850  4850 E Zygote  : MountEmulatedStorage(),
03-16 11:17:28.903  4850  4850 E Zygote  : v2
03-16 11:17:28.913  4850  4850 I libpersona: KNOX_SDCARD checking this for 1000
,03-16 11:17:28.913  4850  4850 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-16 11:17:28.913  4850  4850 I libpersona: KNOX_SDCARD not a persona
03-16 11:17:28.913  1018  1369 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4850 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-16 11:17:28.913  4850  4850 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:28.913  4850  4850 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:28.933  4850  4850 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:28.933  4850  4850 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:28.983  4850  4850 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-16 11:17:29.073  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_4004/cgroup.procs: No such file or directory
,03-16 11:17:29.073  1018  1044 W libprocessgroup: failed to open /acct/uid_10028/pid_4065/cgroup.procs: No such file or directory
,03-16 11:17:29.073  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_4161/cgroup.procs: No such file or directory
,03-16 11:17:29.073  1018  1044 W libprocessgroup: failed to open /acct/uid_10166/pid_3405/cgroup.procs: No such file or directory
,03-16 11:17:29.113  1018  1045 I ActivityManager: Waited long enough for: ServiceRecord{27511905 u0 com.samsung.android.providers.context/.ContextService}
,03-16 11:17:29.123  4850  4850 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-16 11:17:29.133  4850  4850 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-16 11:17:29.133  4850  4850 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,03-16 11:17:29.133  4326  4745 I SA      : [RC New] Execute method=[GET] start,
,03-16 11:17:29.133  4850  4850 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-16 11:17:29.133  4850  4850 I DIAGMON_AGENT: ./extraInfo: "NG700"
,03-16 11:17:29.133  4850  4850 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-16 11:17:29.163  4326  4745 I SA      : [RC New] Security=[true]
,03-16 11:17:29.163  4326  4745 I System.out: Thread-641(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-16 11:17:29.163  4326  4745 I System.out: Thread-641(ApacheHTTPLog):isSBSettingEnabled false
03-16 11:17:29.163  4326  4745 I System.out: Thread-641(ApacheHTTPLog):isShipBuild true
03-16 11:17:29.163  4326  4745 I System.out: Thread-641(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-16 11:17:29.163  4326  4745 I System.out: Thread-641(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-16 11:17:29.163   275   872 D EnterpriseController: uids 10041
03-16 11:17:29.163   275   872 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-16 11:17:29.163   275   872 D Netd    : getNetworkForDns: using netid 502 for uid 10041
,03-16 11:17:29.213  1018  1031 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,03-16 11:17:29.213  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:29.213  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:29.213  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:29.213  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:29.233  4876  4876 E Zygote  : MountEmulatedStorage()
,03-16 11:17:29.233  4876  4876 E Zygote  : v2
03-16 11:17:29.233  4876  4876 I libpersona: KNOX_SDCARD checking this for 10009
03-16 11:17:29.233  4876  4876 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:29.233  4876  4876 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:29.233  4876  4876 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:29.233  4876  4876 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-16 11:17:29.233  1018  1031 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4876 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 11:17:29.253  4876  4876 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:29.253  4876  4876 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:29.263  4408  4408 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,03-16 11:17:29.263  4408  4408 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,03-16 11:17:29.263  4408  4408 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-16 11:17:29.263  1018  1369 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,03-16 11:17:29.263  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:29.263  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:29.263  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:29.263  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:29.283  4891  4891 E Zygote  : MountEmulatedStorage()
03-16 11:17:29.283  4891  4891 E Zygote  : v2
03-16 11:17:29.283  4891  4891 I libpersona: KNOX_SDCARD checking this for 10145
03-16 11:17:29.283  4891  4891 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:29.283  4891  4891 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:29.283  4891  4891 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:29.283  1018  1369 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=4891 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,03-16 11:17:29.283  4891  4891 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:29.303  4891  4891 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:29.303  4891  4891 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:29.323  4891  4891 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-16 11:17:29.333  4891  4891 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 11:17:29.333  4891  4891 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-16 11:17:29.333  4891  4891 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 11:17:29.333  4891  4891 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 11:17:29.333  1018  1045 I ActivityManager: Waited long enough for: ServiceRecord{39d87880 u0 com.android.settings/.wifi.WifiCredService}
,03-16 11:17:29.343  1018  3034 I ActivityManager: Killing 4205:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,03-16 11:17:29.343  4876  4876 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-16 11:17:29.353  4876  4876 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-16 11:17:29.353  4876  4876 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-16 11:17:29.353  4876  4876 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-16 11:17:29.363  1018  4657 I ActivityManager: Killing 4242:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,03-16 11:17:29.383  1018  1515 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 11:17:29.393  1018  1574 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 11:17:29.443  1018  1030 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 11:17:29.453  1018  1345 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 11:17:29.493  4539  4555 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-16 11:17:29.503  1018  1369 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 11:17:29.503  1018  1031 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 11:17:29.513  4539  4549 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-16 11:17:29.513  4539  4549 D BadgeProvider: sendNotify, [notify] : null
03-16 11:17:29.513  4539  4549 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-16 11:17:29.513  4539  4549 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-16 11:17:29.513  4539  4549 D BadgeProvider: update, [UpdateCount] : 1
,03-16 11:17:29.513  1491  1491 D Launcher.Model: reloadBadges entered.
,03-16 11:17:29.523  1018  4657 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 11:17:29.523  1018  1030 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 11:17:29.523  1018  1490 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-16 11:17:29.523  1018  1490 I ActivityManager: Killing 4267:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,03-16 11:17:29.533  1018  1045 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:29.533  1018  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:29.533  1018  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-16 11:17:29.563  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_4205/cgroup.procs: No such file or directory
03-16 11:17:29.563  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_4242/cgroup.procs: No such file or directory
,03-16 11:17:29.563  1018  1142 D ActivityManager: startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
03-16 11:17:29.563  1018  1142 D ActivityManager: retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,03-16 11:17:29.563  1018  1142 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:29.573  1018  1142 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:29.573  1018  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-16 11:17:29.583  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:29.583  1018  1369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:29.583  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:29.603  1018  1515 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:29.603  1018  1515 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:29.603  1018  1515 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,03-16 11:17:29.603  1018  1515 I ActivityManager: Killing 4357:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-16 11:17:29.623  1018  1142 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:29.623  1018  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-16 11:17:29.623  1018  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,03-16 11:17:29.643  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:29.643  1018  1369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,03-16 11:17:29.643  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,03-16 11:17:29.643  1856  1856 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,03-16 11:17:29.653  1018  2954 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:29.653  1018  2954 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-16 11:17:29.653  1018  2954 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,03-16 11:17:29.653  1018  1574 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 11:17:29.653  1018  1574 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:29.653  1018  1574 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 11:17:29.653  1018  1574 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 11:17:29.663  1018  1044 W libprocessgroup: failed to open /acct/uid_10107/pid_4267/cgroup.procs: No such file or directory
,03-16 11:17:29.663  1018  2954 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,03-16 11:17:29.663  1018  2954 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-16 11:17:29.663  1018  2954 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:29.663  1018  2954 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:29.663  1018  2954 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:29.673  4919  4919 E Zygote  : MountEmulatedStorage()
03-16 11:17:29.673  4919  4919 E Zygote  : v2
03-16 11:17:29.673  4919  4919 I libpersona: KNOX_SDCARD checking this for 1000
03-16 11:17:29.673  4919  4919 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:29.683  4919  4919 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-16 11:17:29.683  1018  2954 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4919 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-16 11:17:29.683  4919  4919 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-16 11:17:29.683  4919  4919 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:29.703  4919  4919 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 11:17:29.713  4919  4919 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:29.723  1018  1515 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,03-16 11:17:29.723  1018  1515 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-16 11:17:29.723  1018  1573 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-16 11:17:29.733  1018  2954 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-16 11:17:29.733  4919  4919 E MTPRx   : In MtpReceiverandroid.hardware.usb.action.USB_STATE
,03-16 11:17:29.733  1018  1515 D SecContentProvider2: uri = 14 selection = getSealedState
,03-16 11:17:29.743  1018  1515 D SecContentProvider2: mCursor = null
,03-16 11:17:29.743  1018  1490 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-16 11:17:29.743  1018  1490 D SecContentProvider2: mCursor = null
,03-16 11:17:29.743  4919  4919 V MTPRx   : sealedState: false
03-16 11:17:29.743  4919  4919 V MTPRx   : sealedUsbMassStorageState: false
,03-16 11:17:29.743  4919  4919 E MTPRx   : check value of boot_completed is1
03-16 11:17:29.743  4919  4919 E MTPRx   : check booting is completed_sys.boot_completed
,03-16 11:17:29.743  4919  4919 E MTPRx   : Sd-Card path/storage/extSdCard
,03-16 11:17:29.743  4919  4919 E MTPRx   : Status for mount/Unmount :removed
03-16 11:17:29.743  4919  4919 E MTPRx   : SDcard is not available
,03-16 11:17:29.743  1018  1018 I ValidateNoPeople: mEvictionCount: 0
,03-16 11:17:29.743  4919  4919 W MTPRx   : value of connected istrue
03-16 11:17:29.743  4919  4919 W MTPRx   : value of configured istrue
03-16 11:17:29.743  4919  4919 W MTPRx   : value of mtpEnabled istrue
03-16 11:17:29.743  4919  4919 W MTPRx   : value of ptpEnabled isfalse
,03-16 11:17:29.753  4919  4919 E MTPRx   : Received USB_STATE with sdCardLaunch = 0
,03-16 11:17:29.753  4919  4919 E MTPRx   : mFirstTime: false
,03-16 11:17:29.763  4919  4919 D         : MTP: reading debug level property
,03-16 11:17:29.773  4919  4919 E MTPJNIInterface: Getting CryptionKey from JAVA
,03-16 11:17:29.773  4919  4919 E MTPRx   : currentUserId is 0
,03-16 11:17:29.773  1018  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_4357/cgroup.procs: No such file or directory
,03-16 11:17:29.773  4919  4919 E MTPRx   : Start observing USB_STATE_MATCH 
,03-16 11:17:29.773  4919  4919 E MTPRx   : cannot open file : /sys/class/android_usb/android0/bcdUSB
,03-16 11:17:29.773  4919  4919 E MTPRx   : is_Privatemode is NOT 1
,03-16 11:17:29.773  1018  1030 D SettingsProvider: name = boot_time_connected
,03-16 11:17:29.783  4919  4919 E MTPRx   : Sending NORMAL_BOOT to stack
03-16 11:17:29.783  4919  4919 E MTPJNIInterface: noti = 17
,03-16 11:17:29.783  1018  1490 D SettingsProvider: name = mtp_usb_conditions_met
,03-16 11:17:29.783  1018  1574 D SecContentProvider: uri = 18 selection = isUsbMediaPlayerAvailable
,03-16 11:17:29.783  4919  4919 E MTPRx   : sending MTP_ICON_ENABLED to stack
,03-16 11:17:29.783  1018  1369 D ActivityManager: startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,03-16 11:17:29.783  1018  1369 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,03-16 11:17:29.793  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
,03-16 11:17:29.793  1018  1369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:29.793  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-16 11:17:29.793  1018  3034 D SettingsProvider: name = mtp_running_status
,03-16 11:17:29.793  1018  1031 D SettingsProvider: name = mtp_usb_conditions_met
,03-16 11:17:29.793  4919  4919 E MTPRx   : else part ... so first time!!!
03-16 11:17:29.793  4919  4919 E MTPPlaObsrvr: inside setContext()
,03-16 11:17:29.793  4919  4919 E MTPPlaObsrvr:  inside createplafiles
,03-16 11:17:29.803  4919  4919 E MTPPlaObsrvr: playlist count is0
,03-16 11:17:29.803  4919  4919 E MTPPlaObsrvr:  inside try branch createplafiles
,03-16 11:17:29.803  4919  4919 E MTPPlaObsrvr:  inside deleteing plas createplafiles
,03-16 11:17:29.803  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 11:17:29.803  4919  4919 E MTPPlaObsrvr: Inside registerContentObserver
,03-16 11:17:29.813  4919  4919 E MtpAdbObserver: inside setContext()
03-16 11:17:29.813  4919  4919 E MtpAdbObserver: Inside registerContentObserver
03-16 11:17:29.813  4919  4919 W Settings: Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,03-16 11:17:29.813  1018  1345 D ActivityManager: startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,03-16 11:17:29.813  1018  1345 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
03-16 11:17:29.813  1018  1345 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:29.813  1018  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:29.813  1018  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-16 11:17:29.813  1018  1031 D SettingsProvider: name = mtp_running_status
,03-16 11:17:29.813  1018  1142 D SettingsProvider: name = mtp_usb_conditions_met
,03-16 11:17:29.813  4919  4919 E MtpService: onCreate.
,03-16 11:17:29.813  1018  1030 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
03-16 11:17:29.813  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,03-16 11:17:29.813  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-16 11:17:29.813  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 11:17:29.813  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-16 11:17:29.823  4919  4936 V MtpMediaDBManager: inside deleteAllDB
,03-16 11:17:29.823  4919  4919 E MtpService: < MTP > Registering BroadCast receiver :::::
,03-16 11:17:29.823  4919  4919 E MtpService: < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,03-16 11:17:29.823  1241  1241 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,03-16 11:17:29.833  4919  4919 E MtpService: < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,03-16 11:17:29.833  4919  4919 E MtpService: onStartCommand.
,03-16 11:17:29.833  4919  4919 W MTPRx   : calling native method
03-16 11:17:29.833  4919  4919 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::
,03-16 11:17:29.833  4919  4919 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::::
,03-16 11:17:29.833  4919  4937 E MtpService: handleMessage. msg= { when=-3ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
03-16 11:17:29.833  4919  4919 E MTPJNIInterface: noti = 10
,03-16 11:17:29.833  1314  1314 D BluetoothNotiBroadcastReceiver: onReceive
,03-16 11:17:29.833  4919  4919 E MtpService: onStartCommand.
03-16 11:17:29.833  4919  4919 W MTPRx   : calling native method
,03-16 11:17:29.833  4919  4919 E MTPRx   : Checking the driver time out
03-16 11:17:29.833  4919  4919 E MTPJNIInterface: noti = 2
03-16 11:17:29.833  4919  4919 D         : deleting sockets before message queue initialization
,03-16 11:17:29.843  4919  4919 D         : event handler thread is created, so set the flag
,03-16 11:17:29.843  4919  4919 E MTPRx   : called native method,
03-16 11:17:29.843  4919  4919 E MTPJNIInterface: setting Media scanner status0
03-16 11:17:29.843  4919  4919 E MTPJNIInterface: After setting Media scanner status0
03-16 11:17:29.843  4919  4937 E MtpService: handleMessage. msg= { when=-8ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
03-16 11:17:29.843  1187  1187 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
03-16 11:17:29.843  1187  1187 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,03-16 11:17:29.843  1018  1345 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,03-16 11:17:29.843  4919  4919 W MTPRx   : notification from stack 1
,03-16 11:17:29.853  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:29.853  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:29.853  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 11:17:29.853  4919  4938 E         : Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
,03-16 11:17:29.853  4919  4938 E MTPJNIInterface: Getting media scanner status0
03-16 11:17:29.853  1018  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 11:17:29.853  4919  4938 E MTPJNIInterface: DeviceName is A5-1,
,03-16 11:17:29.863  4919  4936 V MtpMediaDBManager: inside Thread updateDB
,03-16 11:17:29.863  4939  4939 E Zygote  : MountEmulatedStorage(),
03-16 11:17:29.863  4939  4939 E Zygote  : v2
03-16 11:17:29.863  4939  4939 I libpersona: KNOX_SDCARD checking this for 10003
03-16 11:17:29.863  4939  4939 I libpersona: KNOX_SDCARD not a persona
,03-16 11:17:29.863  4939  4939 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-16 11:17:29.873  1018  1345 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=4939 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,03-16 11:17:29.873  4939  4939 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-16 11:17:29.873  4939  4939 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 11:17:29.883  4919  4936 E MtpMediaDBManager: count : 27
,03-16 11:17:29.883   306   306 I art     : Explicit concurrent mark sweep GC freed 8739(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 639us total 20.064ms
03-16 11:17:29.893  4326  4745 I SA      : [RC New] [v2liruge] api execute + 733
03-16 11:17:29.893  4326  4745 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
03-16 11:17:29.893  4326  4745 I System.out: AsyncTask #1 calls detatch()
,03-16 11:17:29.903  4326  4745 I SA      : [ODM] saveOpenData( GEO_IP, PL ),
,03-16 11:17:29.903   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 17.743ms
,03-16 11:17:29.913  4326  4745 I SA      : [OCP] update openData : PL
03-16 11:17:29.913  4939  4939 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 11:17:29.913  4939  4939 D ActivityThread: Added TimaKeyStore provider
,03-16 11:17:29.913  4326  4745 I SA      : [TPMU] getNetworkMcc : 
,03-16 11:17:29.913  4326  4745 I SA      : [SCU] saveMccToPreferece Start
,03-16 11:17:29.913  4326  4745 I SA      : [SCU] RegionMCC : 260
03-16 11:17:29.913  4326  4745 I SA      : [SSP] query invoked
,03-16 11:17:29.923  4919  4936 W MtpMediaDBManager: sending db update complete noti to stack
03-16 11:17:29.923  4919  4936 E MTPJNIInterface: noti = 29
,03-16 11:17:29.923   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 618us total 17.182ms
,03-16 11:17:29.923  4326  4745 I SA      : [TPMU] GetMccFromDB : null
03-16 11:17:29.923  4326  4745 I SA      : [SCU] getMccFromPreferece mcc = 260
03-16 11:17:29.923  4326  4745 I SA      : [SCU] saveMccToPreferece End
,03-16 11:17:29.923  4326  4745 I SA      : [RC New] executeRequest [v2liruge] end. 796
03-16 11:17:29.923  4326  4745 I SA      : [RC New] Execute end
,03-16 11:17:29.923  4326  4326 I SA      : [OR] GetMyCountryZoneTask mcc = 260
03-16 11:17:29.923  4326  4326 I SA      : [OR] GetMyCountryZoneTask Success
,03-16 11:17:29.933  4919  4938 E MTPJNIInterface: Status for mount/Unmount :removed
,03-16 11:17:29.933  4919  4938 E MTPJNIInterface: SDcard is not available
,03-16 11:17:29.943  4939  4939 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-16 11:17:29.943  4919  4938 E         : lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,03-16 11:17:29.953  4919  4938 E         : [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,03-16 11:17:29.953  4919  4938 E MTPJNIInterface: Status for mount/Unmount :removed
,03-16 11:17:29.953  4919  4938 E MTPJNIInterface: SDcard is not available
,03-16 11:17:29.953  4919  4938 E SQLiteLog: (21) API call with NULL database connection pointer
03-16 11:17:29.953  4919  4938 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
,03-16 11:17:29.953  4919  4938 E SQLiteLog: (21) API call with NULL database connection pointer
03-16 11:17:29.953  4919  4938 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
,03-16 11:17:29.953  4919  4938 E SQLiteLog: (21) API call with NULL database connection pointer
03-16 11:17:29.953  4919  4938 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
,03-16 11:17:29.963  4919  4938 E SQLiteLog: (21) API call with NULL database connection pointer
03-16 11:17:29.963  4919  4938 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
,03-16 11:17:29.963  4919  4919 W MTPRx   : notification from stack 2
,03-16 11:17:29.963  4919  4954 D         : [mtp_init_device] Library open with 32 bits.
,03-16 11:17:29.963  4919  4954 D         : [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,03-16 11:17:29.963  4919  4954 E         : [mtp_init_device 702]  After open the MTP fd = 33 and line = 702...
,03-16 11:17:29.963  4919  4954 D         : [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
03-16 11:17:29.963  4919  4954 E         :  [sua_support_present:1287] returning false 
,03-16 11:17:29.963  4919  4954 D         : [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host

```
