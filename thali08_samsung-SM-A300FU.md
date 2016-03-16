#### Test 63012666d6bb2e8_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
03-16 14:31:04.945  2955  2955 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
03-16 14:31:04.945  1020  1525 D SettingsProvider: name = personal_mode_enabled
03-16 14:31:04.955  2955  2955 D [0]UMC:CoreReceiver: Intent : android.intent.action.BOOT_COMPLETED
03-16 14:31:04.955  2955  2955 D [0]UMC:CoreReceiver:  check PreETag 
03-16 14:31:04.955  3018  3018 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:04.955  3018  3018 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:04.955  1480  1480 D Launcher.Model: reloadBadges entered.
03-16 14:31:04.965  1590  1605 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-16 14:31:04.965  1590  1605 D BadgeProvider: sendNotify, [notify] : null
03-16 14:31:04.965  1590  1605 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-16 14:31:04.965  1590  1605 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-16 14:31:04.965  1590  1605 D BadgeProvider: update, [UpdateCount] : 1
03-16 14:31:04.965  2389  2972 D Mms/MessagingNotification: setBadgeCount(), count=0
03-16 14:31:04.975  2389  2972 D Mms/MessagingNotification: remove alarm
03-16 14:31:04.975   314  1077 D AT_Distributor: SetAtdStatus(), 1_1_0
03-16 14:31:04.975   314  1077 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
--------- beginning of system
03-16 14:31:04.975  1020  1527 I ActivityManager: Killing 2213:com.vlingo.midas/u0a28 (adj 15): empty #31
03-16 14:31:04.985  1458  1758 D TP/SmsProvider: query,matched:0, calling pid = 2389
03-16 14:31:04.985  1458  1758 D TP/SmsProvider: match 0:Elapsed time : 1.770 ms
03-16 14:31:04.985  2389  3041 D Mms/MessagingNotification: updateAllHistoryAsRead()
03-16 14:31:04.985  3018  3018 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 14:31:04.995  2389  2972 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 261.17599
03-16 14:31:04.995  1020  1520 I ActivityManager: Killing 2240:com.sec.android.app.videoplayer/u0a45 (adj 15): empty #31
03-16 14:31:05.025  2955  2955 D [0]UMC:ByodSetupStarter: Container ID : 0
03-16 14:31:05.025  2955  2955 V [0]UMC:Utils: checkAppScreen() : com.sec.android.app.launcher
03-16 14:31:05.025  2955  2955 I [0]UMC:Core: shutdown
03-16 14:31:05.025  3007  3007 E SQLiteLog: (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
03-16 14:31:05.025  2955  2955 I art     : System.exit called, status: 0
03-16 14:31:05.025  2955  2955 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
03-16 14:31:05.035  1020  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.035  1020  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.035  1020  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.035  1020  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.035  2620  2717 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
03-16 14:31:05.045  3007  3007 D DSM     : [Lines:107] Normal booted
03-16 14:31:05.045  3007  3007 D DSM     : [Lines:114] Boot completed
03-16 14:31:05.045  1458  1458 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-16 14:31:05.045  1458  1458 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-16 14:31:05.045  1458  1458 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 14:31:05.045  1458  1458 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 14:31:05.045  1458  1458 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 14:31:05.045  1458  1458 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-16 14:31:05.065  3048  3048 E Zygote  : MountEmulatedStorage()
03-16 14:31:05.065  3048  3048 E Zygote  : v2
03-16 14:31:05.065  3048  3048 I libpersona: KNOX_SDCARD checking this for 10082
03-16 14:31:05.065  3048  3048 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:05.065  1020  1520 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3048 uid=10082 gids={50082, 9997, 3003} abi=armeabi-v7a
03-16 14:31:05.065  3048  3048 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:31:05.065  1020  1520 I ActivityManager: Killing 1499:com.android.printspooler/u0a132 (adj 15): empty #31
03-16 14:31:05.075  3048  3048 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:05.075  3048  3048 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-16 14:31:05.075  1020  1032 I ActivityManager: Process com.sec.enterprise.knox.cloudmdm.smdms (pid 2955)(adj 0) has died(63,648)
03-16 14:31:05.095  1323  1323 I SmartcardBootCompleteReceiver: SmartcardBootCompleteReceiver - onReceive() 
03-16 14:31:05.095  1323  1323 I SmartcardBootCompleteReceiver: Received intent with action - android.intent.action.BOOT_COMPLETED
03-16 14:31:05.095  1020  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.095  1020  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.095  1020  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.095  1020  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.105  3048  3048 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:05.105  3048  3048 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:05.105  3063  3063 E Zygote  : MountEmulatedStorage()
03-16 14:31:05.105  3063  3063 E Zygote  : v2
03-16 14:31:05.105  3063  3063 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:05.105  3063  3063 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:05.105  3063  3063 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:31:05.115  1020  1520 I ActivityManager: Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3063 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 14:31:05.115  3063  3063 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:05.115  1020  1520 I ActivityManager: Killing 2300:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
03-16 14:31:05.115  3063  3063 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:05.125  2620  2717 D BluetoothMediaBrowser: no now playing list
03-16 14:31:05.125  2620  2717 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
03-16 14:31:05.135  1323  1323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
03-16 14:31:05.135  1323  1323 I SmartcardBootCompleteReceiver: Broadcast sent with current lockscreen type
03-16 14:31:05.145  1818  1818 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-16 14:31:05.145  1818  1818 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-16 14:31:05.145  1818  1818 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-16 14:31:05.145  1818  1818 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-16 14:31:05.145  1818  1818 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
03-16 14:31:05.155  1818  1818 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
03-16 14:31:05.155  1818  1818 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-16 14:31:05.155  1818  1818 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-16 14:31:05.155  1818  1818 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-16 14:31:05.155  1818  1818 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-16 14:31:05.155  1818  1818 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-16 14:31:05.155  1818  1818 D daemonapp: [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
03-16 14:31:05.155  3063  3063 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:05.155  3063  3063 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:05.165  1020  1521 D SettingsProvider: name = aw_daemon_service_key_version_check
03-16 14:31:05.165  1020  1521 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 14:31:05.165  1020  1521 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 14:31:05.165  1020  1521 D SettingsProvider: selectionArgs: false
03-16 14:31:05.165  1020  1521 D SettingsProvider: selectionArgs: 10157
03-16 14:31:05.165  1020  1521 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 14:31:05.165  1020  1521 D SettingsProvider: ret = -1
03-16 14:31:05.165  1020  1044 W libprocessgroup: failed to open /acct/uid_10028/pid_2213/cgroup.procs: No such file or directory
03-16 14:31:05.165  1020  1044 W libprocessgroup: failed to open /acct/uid_10045/pid_2240/cgroup.procs: No such file or directory
03-16 14:31:05.175  3063  3063 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-16 14:31:05.185  1020  1521 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10157
03-16 14:31:05.185  1818  1818 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
03-16 14:31:05.185  1818  1818 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
03-16 14:31:05.195  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-16 14:31:05.195  1818  1818 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-16 14:31:05.195  1818  1818 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-16 14:31:05.195  1818  1818 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
03-16 14:31:05.195  1818  1818 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
03-16 14:31:05.195  1818  1818 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
03-16 14:31:05.195  1818  1818 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-16 14:31:05.205  1818  1818 D daemonapp: [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1458135065211
03-16 14:31:05.205  1818  1818 D daemonapp: [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1458156600000
03-16 14:31:05.205  1818  1818 D daemonapp: [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
03-16 14:31:05.205  1818  1818 D daemonapp: [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
03-16 14:31:05.205  1818  1818 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458156600000
03-16 14:31:05.245  1818  1818 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 36
03-16 14:31:05.245  1818  1818 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458156600000
03-16 14:31:05.255  3048  3048 E UpdateRequestReceiver: ignoring update request
03-16 14:31:05.265  3048  3048 E UpdateRequestReceiver: ignoring update request
03-16 14:31:05.265  3063  3063 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-16 14:31:05.275  3048  3048 E UpdateRequestReceiver: ignoring update request
03-16 14:31:05.275  1323  1323 D [SBeam] : SBeamEnabler.initPreferenceForSbeam : 0
03-16 14:31:05.285  1020  1044 W libprocessgroup: failed to open /acct/uid_10132/pid_1499/cgroup.procs: No such file or directory
03-16 14:31:05.285  1020  1044 W libprocessgroup: failed to open /acct/uid_10110/pid_2300/cgroup.procs: No such file or directory
03-16 14:31:05.285  3048  3048 E UpdateRequestReceiver: ignoring update request
03-16 14:31:05.295  1323  1323 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
03-16 14:31:05.295  1323  1323 I SettingSearch/SearchIntentReceiver: search setting db init!!
03-16 14:31:05.295  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a300fu.dat
03-16 14:31:05.295  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a3ulte.dat
03-16 14:31:05.295  3063  3063 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a300fu.dat
03-16 14:31:05.295  3048  3048 E UpdateRequestReceiver: ignoring update request
03-16 14:31:05.305   301   301 E USB_UICC: Timeout! No signal received. Retry num = 29
03-16 14:31:05.305  1818  1818 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
03-16 14:31:05.305   327   327 I ServiceManager: Waiting for service AtCmdFwd...
03-16 14:31:05.305  1818  1818 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
03-16 14:31:05.305  3048  3048 E UpdateRequestReceiver: ignoring update request
03-16 14:31:05.305  1323  1323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
03-16 14:31:05.315  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.315  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.315  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.315  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.315  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
03-16 14:31:05.325  3095  3095 E Zygote  : MountEmulatedStorage()
03-16 14:31:05.335  3095  3095 E Zygote  : v2
03-16 14:31:05.335  3095  3095 I libpersona: KNOX_SDCARD checking this for 10088
03-16 14:31:05.335  3095  3095 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:05.335  3095  3095 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:31:05.335  1020  1527 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3095 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 14:31:05.335  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-16 14:31:05.335  1020  1527 I ActivityManager: Killing 1652:com.google.android.partnersetup/u0a14 (adj 15): empty #31
03-16 14:31:05.335  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-16 14:31:05.335  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.335  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-16 14:31:05.335  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.335  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-16 14:31:05.335  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.335  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-16 14:31:05.335  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.335  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-16 14:31:05.335  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-16 14:31:05.335  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-16 14:31:05.335  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
03-16 14:31:05.335  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
03-16 14:31:05.335  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-16 14:31:05.335  3095  3095 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:05.335  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
03-16 14:31:05.335  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_RUN_REF
03-16 14:31:05.335  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
03-16 14:31:05.335  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
03-16 14:31:05.335  3095  3095 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-16 14:31:05.335  1323  3101 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
03-16 14:31:05.335  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
03-16 14:31:05.335  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-16 14:31:05.335  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
03-16 14:31:05.335  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
03-16 14:31:05.335  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
03-16 14:31:05.345  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
03-16 14:31:05.345  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
03-16 14:31:05.345  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
03-16 14:31:05.345  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
03-16 14:31:05.345  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
03-16 14:31:05.345  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
03-16 14:31:05.345  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
03-16 14:31:05.345  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
03-16 14:31:05.345  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
03-16 14:31:05.345  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
03-16 14:31:05.345  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
03-16 14:31:05.345  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
03-16 14:31:05.345  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
03-16 14:31:05.345  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
03-16 14:31:05.345  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
03-16 14:31:05.345  3063  3063 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
03-16 14:31:05.355  3095  3095 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:05.355  3063  3063 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
03-16 14:31:05.355  3095  3095 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:05.355  3111  3111 E Zygote  : MountEmulatedStorage()
03-16 14:31:05.355  3111  3111 E Zygote  : v2
03-16 14:31:05.355  3111  3111 I libpersona: KNOX_SDCARD checking this for 10161
03-16 14:31:05.355  3111  3111 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:05.355  1020  1527 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3111 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 14:31:05.355  3111  3111 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:31:05.365  3111  3111 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:05.365  3111  3111 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-16 14:31:05.375  1020  1044 W libprocessgroup: failed to open /acct/uid_10014/pid_1652/cgroup.procs: No such file or directory
03-16 14:31:05.375  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.375  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.375  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.375  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.385   310   310 I art     : Explicit concurrent mark sweep GC freed 8730(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 693us total 21.919ms
03-16 14:31:05.395  3111  3111 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:05.395  3111  3111 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:05.395   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 573us total 17.095ms
03-16 14:31:05.415   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 17.363ms
03-16 14:31:05.425  3128  3128 E Zygote  : MountEmulatedStorage()
03-16 14:31:05.435  3128  3128 E Zygote  : v2
03-16 14:31:05.435  3128  3128 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:05.435  3128  3128 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:05.435  3128  3128 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:31:05.435  1020  1527 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3128 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 14:31:05.435  1020  1527 I ActivityManager: Killing 2372:com.sec.modem.settings/1000 (adj 15): empty #31
03-16 14:31:05.435  3128  3128 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:05.435  3128  3128 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:05.435  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.435  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.435  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.435  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.455  3128  3128 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:05.455  3128  3128 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:05.465  3143  3143 E Zygote  : MountEmulatedStorage()
03-16 14:31:05.465  3143  3143 E Zygote  : v2
03-16 14:31:05.465  3143  3143 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:05.465  3143  3143 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:05.465  3143  3143 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:31:05.465  3143  3143 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:05.465  3143  3143 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:05.475  1020  1527 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3143 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 14:31:05.485  1020  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.485  1020  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.485  1020  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.485  1020  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.495  3143  3143 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:05.495  3143  3143 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:05.505  3158  3158 E Zygote  : MountEmulatedStorage()
03-16 14:31:05.505  3158  3158 E Zygote  : v2
03-16 14:31:05.505  3158  3158 I libpersona: KNOX_SDCARD checking this for 10146
03-16 14:31:05.505  3158  3158 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:05.505  3158  3158 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:31:05.505  1020  1521 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3158 uid=10146 gids={50146, 9997} abi=armeabi-v7a
03-16 14:31:05.515  3158  3158 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:05.515  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2372/cgroup.procs: No such file or directory
03-16 14:31:05.515  3158  3158 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-16 14:31:05.525  3143  3143 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 14:31:05.535  3158  3158 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:05.535  3158  3158 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:05.635  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-16 14:31:05.635  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-16 14:31:05.635  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 14:31:05.635  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 14:31:05.635  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 14:31:05.635  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 14:31:05.715  3143  3143 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
03-16 14:31:05.775  3111  3173 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-16 14:31:05.775  3111  3173 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
03-16 14:31:05.805  1020  1396 I art     : Explicit concurrent mark sweep GC freed 135534(7MB) AllocSpace objects, 4(1813KB) LOS objects, 33% free, 22MB/33MB, paused 2.449ms total 267.618ms
03-16 14:31:05.815  3111  3173 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
03-16 14:31:05.825  3067  3067 D AndroidRuntime: 
03-16 14:31:05.825  3067  3067 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-16 14:31:05.835  3067  3067 D AndroidRuntime: CheckJNI is OFF
03-16 14:31:05.835  3067  3067 D AndroidRuntime: readGMSProperty: start
03-16 14:31:05.835  3067  3067 D AndroidRuntime: readGMSProperty: already setted!!
03-16 14:31:05.835  3067  3067 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-16 14:31:05.835  3067  3067 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-16 14:31:05.835  3067  3067 D AndroidRuntime: readGMSProperty: end
03-16 14:31:05.835  3067  3067 D AndroidRuntime: addProductProperty: start
03-16 14:31:05.875  3128  3128 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
03-16 14:31:05.885  1020  1033 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-16 14:31:05.885  1020  1033 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4313, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 14:31:05.885  1020  1033 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-16 14:31:05.885  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-16 14:31:05.885  1020  1020 I MotionRecognitionService: Plugged
03-16 14:31:05.885  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
03-16 14:31:05.895  3111  3173 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-16 14:31:05.895  3111  3173 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@68515a0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-16 14:31:05.895  3111  3173 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-16 14:31:05.895  1181  1181 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 14:31:05.895  1181  1181 D KeyguardUpdateMonitor: handleBatteryUpdate
03-16 14:31:05.895  1181  1181 D PowerUI : Cable  true --> true mBootCompleted : true
03-16 14:31:05.895  1181  1181 D PowerUI : Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
03-16 14:31:05.895  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 14:31:05.895  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-16 14:31:05.905  2620  2620 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-16 14:31:05.905  2620  2715 D HeadsetStateMachine: Disconnected process message: 10
03-16 14:31:05.905  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 14:31:05.905  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 14:31:05.905  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-16 14:31:05.905  1181  1181 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 14:31:05.905  1181  1181 D SViewCoverView: level :100 plugged : 2
03-16 14:31:05.925  3143  3143 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
03-16 14:31:05.925  3143  3143 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
03-16 14:31:05.925  3143  3143 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
03-16 14:31:05.975  1020  1352 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:05.975  1020  1352 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
03-16 14:31:05.975  1020  1352 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
03-16 14:31:05.975  1020  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.975  1020  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.975  1020  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.975  1020  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.995  3178  3178 E Zygote  : MountEmulatedStorage()
03-16 14:31:05.995  3178  3178 E Zygote  : v2
03-16 14:31:05.995  3178  3178 I libpersona: KNOX_SDCARD checking this for 10088
03-16 14:31:05.995  3178  3178 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:05.995  3178  3178 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:31:05.995  3178  3178 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:05.995  3178  3178 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-16 14:31:05.995  1020  1352 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3178 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 14:31:06.025  3143  3143 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
03-16 14:31:06.025  3178  3178 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:06.025  3178  3178 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:06.035  3143  3143 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
03-16 14:31:06.035  3143  3143 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
03-16 14:31:06.035  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:06.035  1020  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:06.035  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
03-16 14:31:06.045  3143  3143 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
03-16 14:31:06.045  3143  3143 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
03-16 14:31:06.045  3143  3143 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
03-16 14:31:06.055  1181  1181 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
03-16 14:31:06.055  3143  3143 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
03-16 14:31:06.055  3143  3143 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
03-16 14:31:06.065  3143  3143 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
03-16 14:31:06.065  3143  3143 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
03-16 14:31:06.065  3143  3143 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
03-16 14:31:06.065  3143  3143 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
03-16 14:31:06.065  3143  3143 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
03-16 14:31:06.065  3143  3143 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
03-16 14:31:06.065  3143  3143 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
03-16 14:31:06.065  3143  3176 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
03-16 14:31:06.075  3143  3143 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
03-16 14:31:06.075  3128  3128 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
03-16 14:31:06.085  3143  3143 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
03-16 14:31:06.085  3143  3143 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
03-16 14:31:06.085  3143  3143 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
03-16 14:31:06.085  3143  3143 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
03-16 14:31:06.085  3143  3176 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
03-16 14:31:06.085  3128  3128 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
03-16 14:31:06.085  3143  3176 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
03-16 14:31:06.085  3143  3143 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
03-16 14:31:06.095  1181  1181 D OverheatReceiver: into the SAFE_MODE_ACTION
03-16 14:31:06.095  1181  1181 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
03-16 14:31:06.095  1020  1141 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:06.095  1020  1141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:06.095  1020  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
03-16 14:31:06.095  1181  1181 D OverheatReceiver: isSafeMode = false
03-16 14:31:06.105  3128  3128 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
03-16 14:31:06.105  3128  3128 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-16 14:31:06.105  3128  3128 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
03-16 14:31:06.105  3128  3128 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
03-16 14:31:06.105  1458  1458 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
03-16 14:31:06.105  1020  1491 D SettingsProvider: name = internet_call_settings_visibility
03-16 14:31:06.105  1020  1491 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 14:31:06.105  1020  1491 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 14:31:06.105  1020  1491 D SettingsProvider: selectionArgs: false
03-16 14:31:06.105  1020  1491 D SettingsProvider: selectionArgs: 1001
03-16 14:31:06.105  1020  1491 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 14:31:06.105  1020  1491 D SettingsProvider: ret = -1
03-16 14:31:06.105  1458  1458 D PhoneUtilsCommon: isSupportVoLTE is false.
03-16 14:31:06.115  3095  3095 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
03-16 14:31:06.135  3143  3143 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
03-16 14:31:06.155  3143  3143 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
03-16 14:31:06.155  1435  1435 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
03-16 14:31:06.155  1020  1396 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:06.155  1020  1396 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:06.155  1020  1396 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
03-16 14:31:06.155  3095  3095 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
03-16 14:31:06.165  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:06.165  1020  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:06.165  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
03-16 14:31:06.165  1020  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.165  1020  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.165  1020  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.165  1020  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.175  3143  3176 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
03-16 14:31:06.175  3207  3207 E Zygote  : MountEmulatedStorage()
03-16 14:31:06.175  3207  3207 E Zygote  : v2
03-16 14:31:06.175  3207  3207 I libpersona: KNOX_SDCARD checking this for 10052
03-16 14:31:06.175  3207  3207 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:06.185  3207  3207 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:31:06.185  1020  1352 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3207 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
03-16 14:31:06.185  3207  3207 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:06.185  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.185  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.185  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.185  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.185  3207  3207 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-16 14:31:06.195  3095  3095 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
03-16 14:31:06.215  3216  3216 E Zygote  : MountEmulatedStorage()
03-16 14:31:06.215  3216  3216 E Zygote  : v2
03-16 14:31:06.215  3216  3216 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:06.215  3216  3216 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:06.225  3216  3216 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:31:06.225  3095  3095 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
03-16 14:31:06.225  1020  1032 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3216 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 14:31:06.225  3216  3216 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:06.225  3216  3216 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:06.225  3095  3095 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
03-16 14:31:06.235  1435  1435 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
03-16 14:31:06.245  3207  3207 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:06.255  3207  3207 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:06.265  3216  3216 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:06.265  3216  3216 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:06.265  3095  3095 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
03-16 14:31:06.275  1020  1045 I ActivityManager: Waited long enough for: ServiceRecord{3709a245 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
03-16 14:31:06.285  3143  3176 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
03-16 14:31:06.305   301   301 E USB_UICC: Timeout! No signal received. Retry num = 30
03-16 14:31:06.305   327   327 I ServiceManager: Waiting for service AtCmdFwd...
03-16 14:31:06.375  3095  3095 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
03-16 14:31:06.385  3067  3067 E AffinityControl: AffinityControl: registerfunction enter
03-16 14:31:06.395  3143  3176 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
03-16 14:31:06.395  3143  3176 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
03-16 14:31:06.395  3143  3176 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
03-16 14:31:06.405  3095  3095 I com.dropbox.sync.android.a: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
03-16 14:31:06.405   301   301 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-16 14:31:06.405   301   301 E USB_UICC: usb_uicc_init_qmi failed ! 
03-16 14:31:06.405   301   301 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
03-16 14:31:06.405   301   301 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
03-16 14:31:06.415   285   668 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
03-16 14:31:06.415   285   668 D audio_hw_extn: audio_extn_get_parameters: returns 
03-16 14:31:06.415   285   668 V msm8974_platform: platform_get_parameters: exit: returns - 
03-16 14:31:06.415   285   668 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-16 14:31:06.415   285   668 I str_params: key: 'call_forwarding' value: ''
03-16 14:31:06.415  1928  1928 V InCall  : ProximitySensor -  - screenonImmediately: false
03-16 14:31:06.415  1928  1928 V InCall  : ProximitySensor -  - mFromRcsShare: false
03-16 14:31:06.425  1928  1928 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
03-16 14:31:06.425  1928  1928 D ScoverManager: serviceVersion : 16908288
03-16 14:31:06.425  1020  1396 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-16 14:31:06.425  3067  3067 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-16 14:31:06.425  1928  1928 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
03-16 14:31:06.425  1020  1352 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-16 14:31:06.425  1928  1928 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
03-16 14:31:06.425  1435  1435 I Telecom : ProximitySensorManager: Proximity wake lock already released
03-16 14:31:06.425  1928  1928 I InCall  : InCallPresenter -  - InCallState = NO_CALLS
03-16 14:31:06.425  1928  1928 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
03-16 14:31:06.425  1928  1928 D InCall  : InCallPresenter -  - dismissCoverDialog()...
03-16 14:31:06.435  1928  1928 I InCall  : CallSContextMotion - stopPutDownListening
03-16 14:31:06.435  1928  1928 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
03-16 14:31:06.435  1181  1181 D PhoneStatusBarView: setCallBackground:0
03-16 14:31:06.445  1020  1759 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-16 14:31:06.445  1928  1928 D InCall  : InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
03-16 14:31:06.475  1928  1928 D VideoCallManager: Instantiating VideoCallManager
03-16 14:31:06.485  1928  1928 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
03-16 14:31:06.485  1928  1928 I GFX construct_block_size_descriptor_2d second part: took 2.127656ms for 0*0 texture 0
03-16 14:31:06.495  1928  1928 I GFX generate_partition_tables: took 5.752604ms for 0*0 texture 0
03-16 14:31:06.495  1928  1928 I GFX raster: took 12.324271ms for 176*144 texture 0
03-16 14:31:06.495  1928  1928 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b1b1a0 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb8b1aa70 counterpartCT=4 counterpartW=176 counterparth=144
03-16 14:31:06.545  1020  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.545  1020  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.545  1020  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.545  1020  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.545  1020  1527 E PersonaManagerService: inState():  stateMachine is null !!
03-16 14:31:06.545  1020  1527 I PersonaManagerService: PersonaId don't exist
03-16 14:31:06.545  1020  1527 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-16 14:31:06.545  3216  3216 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
03-16 14:31:06.555  3216  3216 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
03-16 14:31:06.555  3095  3095 I com.dropbox.sync.android.ad: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A300FU armeabi-v7a; en_US))
03-16 14:31:06.555  3260  3260 E Zygote  : MountEmulatedStorage()
03-16 14:31:06.555  3260  3260 E Zygote  : v2
03-16 14:31:06.555  3260  3260 I libpersona: KNOX_SDCARD checking this for 10008
03-16 14:31:06.555  3260  3260 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:06.555  1928  1928 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
03-16 14:31:06.555  3260  3260 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:31:06.555  1928  1928 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-16 14:31:06.555  1928  1928 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-16 14:31:06.555  1928  1928 I Adreno-EGL: Build Date: 04/06/15 Mon
03-16 14:31:06.555  1928  1928 I Adreno-EGL: Local Branch: 
03-16 14:31:06.555  1928  1928 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-16 14:31:06.555  1928  1928 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-16 14:31:06.555  1928  1928 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
03-16 14:31:06.555  3260  3260 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:06.565  1020  1519 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3260 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 14:31:06.565  3260  3260 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-16 14:31:06.565  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.565  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.565  3216  3256 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
03-16 14:31:06.565  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.565  3216  3216 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
03-16 14:31:06.565  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.575  3216  3216 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
03-16 14:31:06.575  3216  3216 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
03-16 14:31:06.575  3216  3216 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
03-16 14:31:06.585  3216  3216 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
03-16 14:31:06.585  3268  3268 E Zygote  : MountEmulatedStorage()
03-16 14:31:06.585  3268  3268 I libpersona: KNOX_SDCARD checking this for 10014
03-16 14:31:06.585  3268  3268 E Zygote  : v2
03-16 14:31:06.585  3268  3268 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:06.585  3216  3216 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
03-16 14:31:06.585  1020  1142 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3268 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
03-16 14:31:06.585  3268  3268 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:31:06.585  3216  3216 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
03-16 14:31:06.585  3268  3268 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:06.585  1020  1527 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 14:31:06.585  3216  3216 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
03-16 14:31:06.585  3268  3268 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-16 14:31:06.585  3216  3216 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
03-16 14:31:06.585  3216  3216 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
03-16 14:31:06.595  3216  3256 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
03-16 14:31:06.595  3216  3216 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
03-16 14:31:06.595  1020  1527 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-16 14:31:06.605  1020  1527 W ActivityManager: mDVFSHelper.acquire()
03-16 14:31:06.605  1020  1032 D LocationManagerService: getProviders()=[passive]
03-16 14:31:06.605  1020  1527 D FocusedStackFrame: Set to : 0
03-16 14:31:06.605  1928  1928 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-16 14:31:06.625  1928  1928 I glCompressedTexImage2D: took 0.423855ms for 320*61440 texture 37809
03-16 14:31:06.625  1020  1050 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-16 14:31:06.625  1020  1050 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-16 14:31:06.625  1020  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-16 14:31:06.625  1020  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-16 14:31:06.625   259   259 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, uhalitest
03-16 14:31:06.625  1480  1480 D Launcher.HomeView: onPause
03-16 14:31:06.625  3260  3260 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:06.635  3260  3260 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:06.635  1928  1928 I draw setup: took 10.741354ms for 320*240 texture 37809
03-16 14:31:06.635  1928  1928 E GFX GPU raster: drawn
03-16 14:31:06.635  1480  1480 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-16 14:31:06.635  1928  1928 I GFX GPU raster ASTC: took 45.664789ms for 320*240 texture 12
03-16 14:31:06.635  1928  1928 I GFX raster: took 45.741091ms for 320*240 texture 0
03-16 14:31:06.635  1928  1928 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b1b120 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb8b1ac88 counterpartCT=4 counterpartW=320 counterparth=240
03-16 14:31:06.635  3268  3268 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:06.635  3268  3268 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:06.645  3216  3256 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
03-16 14:31:06.645  1928  1928 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
03-16 14:31:06.645  1928  1928 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-16 14:31:06.655  1928  1928 I glCompressedTexImage2D: took 0.332865ms for 480*122880 texture 37813
03-16 14:31:06.655  1928  1928 I draw setup: took 0.811302ms for 480*640 texture 37813
03-16 14:31:06.655  1928  1928 E GFX GPU raster: drawn
03-16 14:31:06.665  1928  1928 I GFX GPU raster ASTC: took 8.508542ms for 480*640 texture 12
03-16 14:31:06.665  1928  1928 I GFX raster: took 8.585313ms for 480*640 texture 0
03-16 14:31:06.665  1928  1928 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b1ac88 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb8d5c6e0 counterpartCT=4 counterpartW=480 counterparth=640
03-16 14:31:06.665  1020  1527 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-16 14:31:06.665  1020  1527 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 14:31:06.665  1020  1527 D InputDispatcher: Focused application set to: xxxx
03-16 14:31:06.665  1020  1527 D InputDispatcher: Focus left window: 1480
03-16 14:31:06.665  3067  3067 D AndroidRuntime: Shutting down VM
03-16 14:31:06.675  1020  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 14:31:06.675  1020  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
03-16 14:31:06.695  1020  1396 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.695  1020  1396 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.695  1020  1396 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.695  1020  1396 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.715  3299  3299 E Zygote  : MountEmulatedStorage()
03-16 14:31:06.715  3299  3299 E Zygote  : v2
03-16 14:31:06.715  3299  3299 I libpersona: KNOX_SDCARD checking this for 10167
03-16 14:31:06.715  3299  3299 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:06.715  3207  3297 I ContactAccountLoggerTas: canRun() : Opted Out
03-16 14:31:06.715  3299  3299 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:31:06.715  1020  1396 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3299 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-16 14:31:06.715  3299  3299 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:06.715  1928  1928 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
03-16 14:31:06.715  3299  3299 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-16 14:31:06.725  1928  1928 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-16 14:31:06.725  1928  1928 I glCompressedTexImage2D: took 0.402500ms for 440*116864 texture 37809
03-16 14:31:06.725  1928  1928 I draw setup: took 1.024688ms for 440*330 texture 37809
03-16 14:31:06.725  1928  1928 E GFX GPU raster: drawn
03-16 14:31:06.725  1928  1928 I GFX GPU raster ASTC: took 6.549792ms for 440*330 texture 12
03-16 14:31:06.725  1928  1928 I GFX raster: took 6.633801ms for 440*330 texture 0
03-16 14:31:06.725  1928  1928 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8d5c6c0 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb8d5ca90 counterpartCT=4 counterpartW=440 counterparth=330
03-16 14:31:06.735  1020  1141 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:06.735  1020  1141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:06.735  1020  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
03-16 14:31:06.755  3299  3299 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:06.755  3299  3299 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:06.765  1020  1032 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-16 14:31:06.765  1020  1032 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-16 14:31:06.765  1020  1032 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-16 14:31:06.765  1928  1928 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
03-16 14:31:06.765  1928  1928 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-16 14:31:06.765  1928  1928 I glCompressedTexImage2D: took 0.498125ms for 480*163840 texture 37811
03-16 14:31:06.765  1928  1928 I draw setup: took 1.036405ms for 480*640 texture 37811
03-16 14:31:06.765  1928  1928 E GFX GPU raster: drawn
03-16 14:31:06.775  1480  1480 V ActivityThread: updateVisibility : ActivityRecord{1ab6c8a0 token=android.os.BinderProxy@8c29613 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-16 14:31:06.775  1928  1928 I GFX GPU raster ASTC: took 6.343540ms for 480*640 texture 12
03-16 14:31:06.775  1928  1928 I GFX raster: took 6.421508ms for 480*640 texture 0
03-16 14:31:06.775  1928  1928 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8d5c500 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb8d6f528 counterpartCT=4 counterpartW=480 counterparth=640
03-16 14:31:06.775  1480  1480 D Launcher.HomeView: onStop
03-16 14:31:06.775   258   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-16 14:31:06.775   258   516 W Vold    : Returning OperationFailed - no handler for errno 0
03-16 14:31:06.775  3111  3111 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
03-16 14:31:06.785  1020  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-16 14:31:06.785  1480  1480 V ActivityThread: updateVisibility : ActivityRecord{1ab6c8a0 token=android.os.BinderProxy@8c29613 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-16 14:31:06.785  1480  1480 D Launcher: onTrimMemory. Level: 20
03-16 14:31:06.785  3216  3256 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
03-16 14:31:06.795  1020  1032 D PersonaManager: isKioskContainerExistOnDevice
03-16 14:31:06.795  3216  3256 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
03-16 14:31:06.805  1020  1142 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:06.805  1020  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:06.805  1020  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
03-16 14:31:06.815  3216  3256 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
03-16 14:31:06.825  3207  3297 I Velvet.VelvetFactory: refreshing search history.
03-16 14:31:06.825  3216  3256 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
03-16 14:31:06.825  1020  1020 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-16 14:31:06.825  1020  1020 D SensorService: [SO] activate (ident=0xb9054240, enabled=0)
03-16 14:31:06.825  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-16 14:31:06.835  1020  1020 D SensorManager: unregisterListener ::   
03-16 14:31:06.835  1020  1020 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
03-16 14:31:06.835  3216  3256 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
03-16 14:31:06.835  1020  1020 D SensorService: [SO] changed settle time [1]
03-16 14:31:06.835  1020  1020 D SensorService: [SO] setDelay [66000000]
03-16 14:31:06.835  1020  1020 D SensorService: [SO] activate (ident=0xb9027bc8, enabled=1)
03-16 14:31:06.835  1020  1020 D SensorService: [SO] AR_init
03-16 14:31:06.835  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
03-16 14:31:06.845  1020  1020 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
03-16 14:31:06.855  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.865  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.865  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.865  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.875  3067  3067 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters,.
03-16 14:31:06.875  1020  1142 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3323 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
03-16 14:31:06.885  3323  3323 E Zygote  : MountEmulatedStorage()
03-16 14:31:06.885  3323  3323 E Zygote  : v2
03-16 14:31:06.885  3323  3323 I libpersona: KNOX_SDCARD checking this for 10090
03-16 14:31:06.885  3323  3323 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:31:06.885  3323  3323 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:06.885  3216  3256 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
03-16 14:31:06.885  1020  1142 I ActivityManager: Killing 2405:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
03-16 14:31:06.885  3323  3323 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:06.885  3323  3323 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:06.885  1928  1928 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
03-16 14:31:06.895  1928  1928 I GFX construct_block_size_descriptor_2d second part: took 2.436511ms for 0*0 texture 0
,03-16 14:31:06.905  1928  1928 I GFX generate_partition_tables: took 7.745625ms for 0*0 texture 0
,03-16 14:31:06.905  1928  1928 I GFX raster: took 12.129897ms for 176*144 texture 0
03-16 14:31:06.905  1928  1928 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8d5c480 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb8d6f528 counterpartCT=4 counterpartW=176 counterparth=144
,03-16 14:31:06.915  1020  1042 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-16 14:31:06.915  3216  3256 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-16 14:31:06.925  3323  3323 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:06.925  3323  3323 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:06.925  1928  1928 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-16 14:31:06.925  1928  1928 I GFX construct_block_size_descriptor_2d second part: took 2.440574ms for 0*0 texture 0
,03-16 14:31:06.935  3216  3256 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-16 14:31:06.935  3216  3256 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,03-16 14:31:06.935  3216  3256 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,03-16 14:31:06.945  3216  3257 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true,
,03-16 14:31:06.945  3216  3257 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-16 14:31:06.945  3216  3256 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/20/16:34:31
,03-16 14:31:06.955  3216  3256 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/16/14:31:06
,03-16 14:31:06.955  3216  3256 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
03-16 14:31:06.955  1928  1928 I GFX generate_partition_tables: took 6.300104ms for 0*0 texture 0
,03-16 14:31:06.955  3216  3256 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,03-16 14:31:06.955  1928  1928 I GFX raster: took 10.851043ms for 176*144 texture 0
03-16 14:31:06.955  1928  1928 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8d6f528 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb8d5cc48 counterpartCT=4 counterpartW=176 counterparth=144
,03-16 14:31:06.955  1928  1928 D ScoverManager: registerListener
,03-16 14:31:06.955  1020  1525 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-16 14:31:06.955  3216  3257 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-16 14:31:06.955  3216  3257 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-16 14:31:06.965  1020  1396 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-16 14:31:06.965  1020  1396 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@6fd5f84, pid : 1928, uid : 1001, type : 1
,03-16 14:31:06.965  3216  3257 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-16 14:31:06.965  3216  3257 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-16 14:31:06.965  3216  3257 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
03-16 14:31:06.965  3216  3257 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
03-16 14:31:06.965  3216  3257 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,03-16 14:31:06.965  3216  3257 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-16 14:31:06.975  1020  1032 I ActivityManager: Killing 2416:com.sec.tcpdumpservice/1000 (adj 15): empty #31
,03-16 14:31:06.985  1020  1042 D SensorService: [SO] currT = 36891061000, prevT = 36541290000, diff = 349771000, [-0.460 0.192 9.902]
,03-16 14:31:06.985  1020  1042 D SensorService: [SO] -0.460 0.192 9.902
03-16 14:31:06.985  1020  1042 D SensorService: [SO] [100 -> 255]
,03-16 14:31:07.005  3299  3299 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,03-16 14:31:07.015  3323  3323 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-16 14:31:07.015  3323  3323 D elm:15121: ELMEngine.ELMEngine( context ).
,03-16 14:31:07.015  3323  3323 D elm:15121: MDMBridge.setEnterpriseBridge()
,03-16 14:31:07.015  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:07.015  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:07.015  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-16 14:31:07.015  3323  3323 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-16 14:31:07.015  3299  3299 I LibraryLoader: Loading: webviewchromium
,03-16 14:31:07.025  3299  3299 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 6927-6931)
03-16 14:31:07.025  3299  3299 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 14:31:07.035  1928  1928 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-16 14:31:07.035  3216  3256 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,03-16 14:31:07.035  3323  3323 D elm:15121: ElmAgentService : onCreate()
03-16 14:31:07.035  3323  3349 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,03-16 14:31:07.045  3323  3323 D elm:15121: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). ,
03-16 14:31:07.045  3323  3323 D elm:15121: BootCompletedState : startBootCompleted() call
,03-16 14:31:07.055  1420  1420 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,03-16 14:31:07.055  3299  3299 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2d47af5b}
,03-16 14:31:07.055  3299  3299 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 14:31:07.055  3299  3299 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,03-16 14:31:07.055  3323  3323 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-16 14:31:07.065  3323  3323 I elm:15121: Get License : 0
,03-16 14:31:07.065  3323  3323 D elm:15121: ElmAgentService : onDestroy().
,03-16 14:31:07.075  3095  3320 I System.out: Thread-395(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-16 14:31:07.075  1020  1044 W libprocessgroup: failed to open /acct/uid_10127/pid_2405/cgroup.procs: No such file or directory
03-16 14:31:07.075  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2416/cgroup.procs: No such file or directory
03-16 14:31:07.075  1020  1521 I ActivityManager: Killing 2437:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,03-16 14:31:07.075  3095  3320 I System.out: Thread-395(ApacheHTTPLog):isSBSettingEnabled false
03-16 14:31:07.075  3095  3320 I System.out: Thread-395(ApacheHTTPLog):isShipBuild true
03-16 14:31:07.075  3095  3320 I System.out: Thread-395(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-16 14:31:07.075  3095  3320 I System.out: Thread-395(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-16 14:31:07.095   280  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-16 14:31:07.095   280  1012 D Netd    : getNetworkForDns: using netid 502 for uid 10088
03-16 14:31:07.095  3299  3299 I BrowserStartupController: Initializing chromium process, renderers=0
03-16 14:31:07.095  3299  3299 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 14:31:07.095  3216  3231 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-16 14:31:07.105  3216  3231 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-16 14:31:07.105  3216  3231 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-16 14:31:07.105  3216  3233 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-16 14:31:07.115  3216  3233 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-16 14:31:07.115  3216  3233 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-16 14:31:07.115  3299  3299 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
03-16 14:31:07.115  3299  3299 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=36 off=46768 len=2953
03-16 14:31:07.115  3299  3299 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:37 off:229524 len:643667
,03-16 14:31:07.125  3207  3296 W GAV2    : Thread[Background Non-Blocking-0,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-16 14:31:07.125  3207  3296 W GAV2    : Thread[Background Non-Blocking-0,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,03-16 14:31:07.145  3299  3299 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-16 14:31:07.145  3299  3299 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-16 14:31:07.145  3299  3299 I Adreno-EGL: Build Date: 04/06/15 Mon
03-16 14:31:07.145  3299  3299 I Adreno-EGL: Local Branch: 
03-16 14:31:07.145  3299  3299 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-16 14:31:07.145  3299  3299 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-16 14:31:07.145  3299  3299 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-16 14:31:07.145  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2437/cgroup.procs: No such file or directory
,03-16 14:31:07.145  1020  1142 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-16 14:31:07.145  3216  3257 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-16 14:31:07.155  1020  1352 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-16 14:31:07.155  1020  1032 I AudioService: getStreamVolume 3 index 0
,03-16 14:31:07.165  3207  3207 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,03-16 14:31:07.165  3207  3319 I ContactAccountLoggerTas: canRun() : Opted Out
,03-16 14:31:07.165  3207  3319 I ContactAccountLoggerTas: canRun() : Opted Out
,03-16 14:31:07.165  3207  3207 I FavoriteContactNamesSup: get() : Execute runnable (UI thread)
03-16 14:31:07.165  3207  3207 I ContactLabelSupplier: get() : Execute runnable (UI thread)
,03-16 14:31:07.195  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.195  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.195  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.195  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.205  1020  1521 E Tethering: No numeric data
,03-16 14:31:07.205  1020  1519 E Tethering: No numeric data
,03-16 14:31:07.215  3381  3381 E Zygote  : MountEmulatedStorage()
03-16 14:31:07.215  3381  3381 E Zygote  : v2
03-16 14:31:07.215  3381  3381 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:07.215  3381  3381 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:07.215  3381  3381 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:07.215  3381  3381 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 14:31:07.215  3381  3381 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:07.225  1020  1033 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3381 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 14:31:07.215  3216  3257 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
03-16 14:31:07.225  1020  1033 I ActivityManager: Killing 2545:com.sec.android.app.camera/u0a135 (adj 15): empty #31
03-16 14:31:07.225  1020  1033 I ActivityManager: Killing 2524:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #32
03-16 14:31:07.225  1020  1033 I ActivityManager: Killing 2480:com.wsomacp/u0a23 (adj 15): empty #33
,03-16 14:31:07.225  1020  1527 E Tethering: No numeric data
,03-16 14:31:07.235  1020  1519 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:07.235  1020  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:07.235  1020  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-16 14:31:07.235  3216  3256 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
03-16 14:31:07.235   259   453 I SurfaceFlinger: id=9 Removed Mauncher (5/8)
,03-16 14:31:07.235   259   458 I SurfaceFlinger: id=9 Removed Mauncher (-2/8)
,03-16 14:31:07.235  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.235  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.245  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.245  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.255   310   310 I art     : Explicit concurrent mark sweep GC freed 8725(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 620us total 37.508ms
,03-16 14:31:07.255  1420  1420 V EmergencyMode: [EmergencyBase] setBootTime
,03-16 14:31:07.255  1420  1420 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
,03-16 14:31:07.275  1020  1521 E Tethering: No numeric data
,03-16 14:31:07.275   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 19.488ms
,03-16 14:31:07.275  3216  3256 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-16 14:31:07.285  3381  3381 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:07.285  1020  1141 E Tethering: No numeric data
,03-16 14:31:07.285  3381  3381 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:07.285  1020  1520 E Tethering: No numeric data
,03-16 14:31:07.295   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 16.574ms
,03-16 14:31:07.305  3396  3396 E Zygote  : MountEmulatedStorage()
03-16 14:31:07.305  3396  3396 E Zygote  : v2
03-16 14:31:07.305  3396  3396 I libpersona: KNOX_SDCARD checking this for 10055,
03-16 14:31:07.305   290   290 E SMD     : DCD OFF
03-16 14:31:07.305  1020  1142 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3396 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
03-16 14:31:07.305   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,03-16 14:31:07.305  3396  3396 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:07.305  3396  3396 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:07.315  3396  3396 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:07.315  3207  3297 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,03-16 14:31:07.315  1020  1520 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
03-16 14:31:07.315  3396  3396 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:07.335  3207  3296 I ContactLabelSupplier: get() : OptedIn = false
,03-16 14:31:07.335  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.335  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.335  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.335  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.335  3396  3396 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:07.345  3396  3396 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:07.345  3411  3411 E Zygote  : MountEmulatedStorage()
03-16 14:31:07.345  3411  3411 E Zygote  : v2
03-16 14:31:07.345  3411  3411 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:07.345  3411  3411 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:07.355  3411  3411 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:07.355  3411  3411 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 14:31:07.355  3411  3411 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:07.355  1020  1142 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3411 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 14:31:07.355  3299  3370 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,03-16 14:31:07.365  3216  3257 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false,
03-16 14:31:07.365  3299  3299 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,03-16 14:31:07.375  1020  1044 W libprocessgroup: failed to open /acct/uid_10135/pid_2545/cgroup.procs: No such file or directory
03-16 14:31:07.375  1020  1044 W libprocessgroup: failed to open /acct/uid_10023/pid_2480/cgroup.procs: No such file or directory
03-16 14:31:07.375  1020  1044 W libprocessgroup: failed to open /acct/uid_10139/pid_2524/cgroup.procs: No such file or directory
,03-16 14:31:07.385  3411  3411 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:07.385  3411  3411 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:07.385  3207  3297 I LibraryLoader: Loading: webviewchromium
,03-16 14:31:07.405  3207  3297 I LibraryLoader: Time to load native libraries: 17 ms (timestamps 7294-7311)
,03-16 14:31:07.405  3207  3297 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 14:31:07.415  3299  3299 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 14:31:07.415  3216  3257 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-16 14:31:07.415  3299  3299 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-16 14:31:07.425  3216  3257 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,03-16 14:31:07.425  3143  3176 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
03-16 14:31:07.425  3299  3299 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-16 14:31:07.425  3299  3299 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-16 14:31:07.435  3299  3299 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-16 14:31:07.445  3299  3299 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 14:31:07.445  3299  3299 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 14:31:07.445  3396  3396 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-16 14:31:07.485  3381  3381 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,03-16 14:31:07.485  3396  3396 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-16 14:31:07.485  3396  3396 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-16 14:31:07.485  3396  3396 D UserAnalysis: Create SecureDbHelper
,03-16 14:31:07.495  3411  3411 I CameraApp: CameraApp.onCreate()... mFeature : null
,03-16 14:31:07.495  3411  3411 I testFeature: Feature.Feature(context)
,03-16 14:31:07.495  3411  3411 I testFeature: Feature.readInternalDefaultXml()
,03-16 14:31:07.495  3411  3411 I testFeature: ResetFeatureValue
,03-16 14:31:07.505  3411  3411 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
,03-16 14:31:07.505  3411  3411 I CameraApp: CameraApp.getAppFeature()...
,03-16 14:31:07.505  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.505  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.505  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.505  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.525  3429  3429 E Zygote  : MountEmulatedStorage(),
,03-16 14:31:07.525  3429  3429 E Zygote  : v2
03-16 14:31:07.525  3429  3429 I libpersona: KNOX_SDCARD checking this for 10095,
03-16 14:31:07.525  3429  3429 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:07.525  1020  1491 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for broadcast com.samsung.android.provider.filterprovider/.FilterProviderReceiver: pid=3429 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
,03-16 14:31:07.525  3429  3429 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:07.525  1020  1491 I ActivityManager: Killing 2358:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-16 14:31:07.525  3429  3429 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:07.525  3429  3429 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:07.535  3396  3396 D IntelligenceServiceApplication: onCreate()
,03-16 14:31:07.535  3396  3396 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
03-16 14:31:07.535  3381  3381 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
03-16 14:31:07.535  3381  3381 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
03-16 14:31:07.535  3381  3381 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-16 14:31:07.535  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.535  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.535  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.535  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.545  3396  3396 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-16 14:31:07.555  3444  3444 E Zygote  : MountEmulatedStorage()
,03-16 14:31:07.555  3444  3444 E Zygote  : v2
03-16 14:31:07.555  3444  3444 I libpersona: KNOX_SDCARD checking this for 10056
03-16 14:31:07.555  3444  3444 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:07.555  3444  3444 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-16 14:31:07.555  1020  1142 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3444 uid=10056 gids={50056, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
03-16 14:31:07.555  3429  3429 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:07.555  3429  3429 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:07.555  1020  1142 I ActivityManager: Killing 1774:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,03-16 14:31:07.555  3444  3444 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:07.565  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.565  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.565  3396  3396 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
03-16 14:31:07.565  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.565  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.565  3444  3444 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:07.575  1323  3101 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
,03-16 14:31:07.575  1323  3101 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
,03-16 14:31:07.575  3455  3455 E Zygote  : MountEmulatedStorage()
,03-16 14:31:07.575  3455  3455 E Zygote  : v2
03-16 14:31:07.575  3455  3455 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:07.575  3455  3455 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:07.575  3455  3455 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-16 14:31:07.585  3396  3396 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
03-16 14:31:07.585  1020  1033 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3455 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 14:31:07.585  3396  3396 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
,03-16 14:31:07.585  3455  3455 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:07.595  3455  3455 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:07.605  3444  3444 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:07.605  3444  3444 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:07.615  3455  3455 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:07.615  3455  3455 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:07.625  1020  1519 E Tethering: No numeric data
,03-16 14:31:07.625  1020  1759 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:07.625  1020  1759 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:07.625  1020  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
03-16 14:31:07.625  1020  1520 E Tethering: No numeric data
,03-16 14:31:07.625  1020  1141 E Tethering: No numeric data
,03-16 14:31:07.635  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2358/cgroup.procs: No such file or directory
03-16 14:31:07.635  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_1774/cgroup.procs: No such file or directory
,03-16 14:31:07.635  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-16 14:31:07.635  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-16 14:31:07.635  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:07.645  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:07.645  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 14:31:07.645  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:07.655  3429  3429 D PreloadFilterInstaller: uses FILTER_DB_VER_1
,03-16 14:31:07.665  3455  3455 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-16 14:31:07.665  3455  3455 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-16 14:31:07.665  3455  3455 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
03-16 14:31:07.665  3299  3485 D OpenGLRenderer: Render dirty regions requested: true
03-16 14:31:07.675  1020  1141 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-16 14:31:07.675  1020  1141 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-16 14:31:07.675  1020  1141 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-16 14:31:07.675  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-16 14:31:07.675  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
03-16 14:31:07.675  3207  3297 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 14:31:07.675  3299  3299 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-16 14:31:07.675  3299  3299 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-16 14:31:07.675  3455  3473 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-16 14:31:07.725  3381  3381 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-16 14:31:07.735  3381  3381 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,03-16 14:31:07.735  3381  3381 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-16 14:31:07.735  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.735  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.735  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.735  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.745  1020  1032 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3493 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 14:31:07.755  3493  3493 E Zygote  : MountEmulatedStorage(),
03-16 14:31:07.755  3493  3493 E Zygote  : v2
03-16 14:31:07.755  3493  3493 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:07.755  3493  3493 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:07.755  3493  3493 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:07.755  1020  1032 I ActivityManager: Killing 2636:com.android.keychain/1000 (adj 15): empty #31
03-16 14:31:07.755  1020  1032 I ActivityManager: Killing 2597:com.android.calendar/u0a131 (adj 15): empty #32
,03-16 14:31:07.755  1020  2741 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-16 14:31:07.755  3493  3493 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:07.755  3493  3493 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:07.775  3493  3493 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:07.775  3493  3493 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:07.795  3429  3429 E SQLiteLog: (284) automatic index on titles(filter_id)
03-16 14:31:07.795  1020  1396 E Tethering: No numeric data
,03-16 14:31:07.805   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
,03-16 14:31:07.805  1020  1033 D InputDispatcher: Focus entered window: 3299
,03-16 14:31:07.815  3299  3299 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-16 14:31:07.815  3299  3485 I OpenGLRenderer: Initialized EGL, version 1.4
,03-16 14:31:07.815  1020  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 14:31:07.815  1020  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-16 14:31:07.815  1020  1044 W libprocessgroup: failed to open /acct/uid_10131/pid_2597/cgroup.procs: No such file or directory
,03-16 14:31:07.815  3299  3485 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-16 14:31:07.815  3299  3485 D OpenGLRenderer: Enabling debug mode 0
,03-16 14:31:07.825  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2636/cgroup.procs: No such file or directory
,03-16 14:31:07.865  2582  3005 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3005)  
,03-16 14:31:07.875  1020  1033 I ActivityManager: Killing 2499:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,03-16 14:31:07.875  1020  1520 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-16 14:31:07.875  1181  1181 I StatusBar: Icon Only
,03-16 14:31:07.875  1181  1181 D PanelView: There is/are notification(s) 
,03-16 14:31:07.875  1020  1050 I ActivityManager: Displayed Component not be shown by security: +1s191ms
,03-16 14:31:07.885  1020  3510 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 14:31:07.885  1020  1050 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@7,
,03-16 14:31:07.885  1020  1045 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-16 14:31:07.885  1020  3511 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 14:31:07.885  1020  1050 D CustomFrequencyManagerService: FrequencyrequestList.getNextMaxCPUCoreRequest, index: 1
,03-16 14:31:07.885  1020  1050 W ActivityManager: mDVFSHelper.release()
03-16 14:31:07.885  1020  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{4b38aaf u0 com.test.thalitest/.MainActivity t11} time:37798
,03-16 14:31:07.895  3299  3299 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2a3b99e6 time:37805
,03-16 14:31:07.895  3444  3444 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.7.KK_APP
,03-16 14:31:07.895  3493  3493 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-16 14:31:07.905  3493  3493 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-16 14:31:07.905  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.905  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.905  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.905  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.925  1020  1491 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3512 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-16 14:31:07.925  3512  3512 E Zygote  : MountEmulatedStorage()
03-16 14:31:07.925  3512  3512 I libpersona: KNOX_SDCARD checking this for 10058
03-16 14:31:07.925  3512  3512 E Zygote  : v2
03-16 14:31:07.925  3512  3512 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:07.925  3512  3512 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:07.925  1020  1491 I ActivityManager: Killing 2659:com.android.chrome/u0a77 (adj 15): empty #31
,03-16 14:31:07.925  3512  3512 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:07.935  3512  3512 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:07.955  3512  3512 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:07.955  3512  3512 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:07.985  3429  3429 I FilterProviderReceiver: onReceive in FilterProviderReceiver
03-16 14:31:07.985  3429  3429 I FilterProviderReceiver: onReceive in FilterProviderReceiver when ACTION_BOOT_COMPLETED
,03-16 14:31:07.985  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.985  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.985  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.985  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.985  1020  1142 V VibratorService: hasVibrator - useVibetonz: true
,03-16 14:31:08.005  3530  3530 E Zygote  : MountEmulatedStorage()
03-16 14:31:08.005  3530  3530 E Zygote  : v2
03-16 14:31:08.005  3530  3530 I libpersona: KNOX_SDCARD checking this for 10098
03-16 14:31:08.005  3530  3530 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:08.005  3530  3530 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:08.005  3530  3530 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:08.005  3530  3530 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:08.005  1020  1527 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3530 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
03-16 14:31:08.005  1020  1527 I ActivityManager: Killing 2724:com.android.email/u0a141 (adj 15): empty #31
,03-16 14:31:08.015  3455  3473 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-16 14:31:08.015  1323  3101 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,03-16 14:31:08.025  1020  1759 V VibratorService: hasVibrator - useVibetonz: true
,03-16 14:31:08.025  3493  3493 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-16 14:31:08.025  1020  1491 V VibratorService: hasVibrator - useVibetonz: true
,03-16 14:31:08.035  3493  3493 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-16 14:31:08.035  3530  3530 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:08.035  3530  3530 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:08.045  1323  3101 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 14:31:08.055  3111  3111 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-16 14:31:08.065  1020  2778 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 14:31:08.075   259  1079 I SurfaceFlinger: id=11 Removed uhalitest (7/8)
,03-16 14:31:08.075   259   453 I SurfaceFlinger: id=11 Removed uhalitest (-2/8)
,03-16 14:31:08.105  3530  3530 D PackageIntentReceiver: ACTION_BOOT_COMPLETED,
,03-16 14:31:08.115  3530  3530 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,03-16 14:31:08.115  1020  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:08.115  1020  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.115  1020  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:08.115  1020  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:08.125  3556  3556 E Zygote  : MountEmulatedStorage(),
,03-16 14:31:08.135  3556  3556 E Zygote  : v2
,03-16 14:31:08.135  1020  1519 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3556 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 14:31:08.135  3556  3556 I libpersona: KNOX_SDCARD checking this for 10099
03-16 14:31:08.135  3556  3556 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:08.135  3556  3556 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:08.135  1858  1858 I SamsungIME: getCurrentCandidateView
,03-16 14:31:08.135  3556  3556 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:08.145  3512  3512 I ExternalOEMControlProvider: onCreate
,03-16 14:31:08.145  3556  3556 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 14:31:08.165  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.165  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.165  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.165  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:08.165  1020  1044 W libprocessgroup: failed to open /acct/uid_10039/pid_2499/cgroup.procs: No such file or directory
03-16 14:31:08.165  1020  1044 W libprocessgroup: failed to open /acct/uid_10077/pid_2659/cgroup.procs: No such file or directory
03-16 14:31:08.165  1020  1044 W libprocessgroup: failed to open /acct/uid_10141/pid_2724/cgroup.procs: No such file or directory
,03-16 14:31:08.175  3556  3556 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:08.175  3556  3556 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:08.175  3574  3574 E Zygote  : MountEmulatedStorage(),
,03-16 14:31:08.175  3574  3574 E Zygote  : v2
03-16 14:31:08.175  3574  3574 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:08.185  3574  3574 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:08.185  3574  3574 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:08.185  1020  1527 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3574 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 14:31:08.185  3574  3574 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:08.185  3574  3574 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:08.185  1020  1020 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@11
03-16 14:31:08.185  1020  1527 I ActivityManager: Killing 2792:com.mobeam.barcodeService/1000 (adj 15): empty #31
,03-16 14:31:08.205  3574  3574 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:08.215  3574  3574 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:08.215  3299  3299 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-16 14:31:08.225  1020  1525 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-16 14:31:08.225  1323  3101 D ScoverManager: serviceVersion : 16908288
,03-16 14:31:08.245  1020  1527 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-16 14:31:08.255  3574  3574 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-16 14:31:08.265  1020  1520 I AudioService: getStreamVolume 3 index 0
,03-16 14:31:08.275  3493  3493 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,03-16 14:31:08.295  3493  3493 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-16 14:31:08.295  3493  3493 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-16 14:31:08.295  3493  3493 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-16 14:31:08.295  3493  3493 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-16 14:31:08.305  3493  3493 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,03-16 14:31:08.305  3493  3493 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,03-16 14:31:08.305   327   327 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-16 14:31:08.325  1020  1525 I ActivityManager: Killing 2812:flipboard.boxer.app/u0a97 (adj 15): empty #31
,03-16 14:31:08.335  3299  3592 D jxcore_app_log: JniHelper::setJavaVM(0xb8770448), pthread_self() = -1193456520
,03-16 14:31:08.335  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2792/cgroup.procs: No such file or directory
,03-16 14:31:08.335  3299  3592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-16 14:31:08.335  3299  3592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-16 14:31:08.335  3299  3592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-16 14:31:08.335  3299  3592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-16 14:31:08.335  3299  3592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-16 14:31:08.335  3299  3592 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e67a1ed added. We now have 1 listener(s)
,03-16 14:31:08.345  3299  3592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,03-16 14:31:08.345  3299  3592 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
,03-16 14:31:08.355  3299  3592 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:76:27"}
03-16 14:31:08.355  3299  3592 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-16 14:31:08.355  3299  3592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-16 14:31:08.355  3260  3260 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-16 14:31:08.355  3299  3592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-16 14:31:08.355  3299  3592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-16 14:31:08.355  3299  3592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-16 14:31:08.355  3299  3592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
03-16 14:31:08.355  3299  3592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-16 14:31:08.355  3299  3592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-16 14:31:08.355  3299  3592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-16 14:31:08.355  3299  3592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-16 14:31:08.355  3299  3592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-16 14:31:08.355  3299  3592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-16 14:31:08.355  3299  3592 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31ecb070 added. We now have 1 listener(s)
,03-16 14:31:08.355  3299  3592 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-16 14:31:08.355  3574  3574 I ServiceMode: received = ACTION_BOOT_COMPLETED
03-16 14:31:08.355  3260  3260 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-16 14:31:08.365  3574  3574 I ServiceMode: setReferenceIsDumpState : 0
,03-16 14:31:08.365  3260  3260 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-16 14:31:08.365  1020  1142 I art     : Explicit concurrent mark sweep GC freed 24664(1361KB) AllocSpace objects, 2(38KB) LOS objects, 33% free, 22MB/33MB, paused 2.781ms total 178.383ms
,03-16 14:31:08.365  1020  1519 D SettingsProvider: name = PREVIOUS_SYS_TIME
03-16 14:31:08.365  1020  1519 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 14:31:08.365  1020  1519 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 14:31:08.365  1020  1519 D SettingsProvider: selectionArgs: false
03-16 14:31:08.365  1020  1519 D SettingsProvider: selectionArgs: 10058
03-16 14:31:08.365  1020  1519 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 14:31:08.365  1020  1519 D SettingsProvider: ret = -1
,03-16 14:31:08.375  3299  3592 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-16 14:31:08.375  1020  1519 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,03-16 14:31:08.375  3299  3592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-16 14:31:08.375  3299  3592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-16 14:31:08.375  3299  3592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-16 14:31:08.375  3299  3592 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-16 14:31:08.375  1020  1142 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
03-16 14:31:08.375  1020  1142 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 14:31:08.375  1020  1142 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 14:31:08.375  1020  1142 D SettingsProvider: selectionArgs: false
03-16 14:31:08.375  1020  1142 D SettingsProvider: selectionArgs: 10058
03-16 14:31:08.375  1020  1142 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 14:31:08.375  1020  1142 D SettingsProvider: ret = -1
,03-16 14:31:08.385  1020  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:08.385  1020  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.385  1020  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:08.385  1020  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:08.385  1858  1858 D SamsungIME: Dismiss ExpandCandiate
,03-16 14:31:08.395  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 14:31:08.395  3602  3602 E Zygote  : MountEmulatedStorage()
03-16 14:31:08.395  3602  3602 E Zygote  : v2
03-16 14:31:08.395  3602  3602 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:08.395  3602  3602 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:08.395  3602  3602 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:08.405  3602  3602 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:08.405  3602  3602 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:08.405  1020  1759 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3602 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 14:31:08.415  1020  1759 I ActivityManager: Killing 2844:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,03-16 14:31:08.415   280  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-16 14:31:08.415   280  1012 D Netd    : getNetworkForDns: using netid 502 for uid 10052
,03-16 14:31:08.415  1020  1142 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,03-16 14:31:08.425  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 14:31:08.425  3299  3592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-16 14:31:08.425  3260  3260 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-16 14:31:08.425   310   310 I art     : Explicit concurrent mark sweep GC freed 8734(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 910us total 26.474ms
,03-16 14:31:08.425  3299  3592 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,03-16 14:31:08.435  3143  3176 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
03-16 14:31:08.435  1020  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.435  1020  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.435  3602  3602 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:08.435  1020  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.435  1020  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.435  3602  3602 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:08.445   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 17.648ms
,03-16 14:31:08.465   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 16.151ms
,03-16 14:31:08.475  3618  3618 E Zygote  : MountEmulatedStorage()
03-16 14:31:08.475  3618  3618 E Zygote  : v2
03-16 14:31:08.475  3618  3618 I libpersona: KNOX_SDCARD checking this for 10013
03-16 14:31:08.475  3618  3618 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:08.475  3618  3618 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:08.475  3618  3618 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:08.475  1020  1521 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3618 uid=10013 gids={50013, 9997} abi=armeabi-v7a
,03-16 14:31:08.475  3618  3618 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 14:31:08.475  1020  1521 I ActivityManager: Killing 1618:com.android.defcontainer/u0a3 (adj 15): empty #31
,03-16 14:31:08.495  3299  3592 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-16 14:31:08.495  3299  3592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-16 14:31:08.495  3299  3592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-16 14:31:08.495  3299  3592 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-16 14:31:08.495  3299  3592 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-16 14:31:08.495  3299  3592 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-16 14:31:08.495  3299  3592 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-16 14:31:08.495  3299  3592 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-16 14:31:08.495  3299  3592 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-16 14:31:08.495  3299  3592 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-16 14:31:08.495  3299  3299 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 14:31:08.505  3299  3299 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 14:31:08.515  3618  3618 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:08.515  3618  3618 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:08.515   258   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-16 14:31:08.515   258   516 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 14:31:08.525  3111  3111 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-16 14:31:08.525   258   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-16 14:31:08.525   258   516 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 14:31:08.525  1020  1521 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:08.525  3111  3111 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
03-16 14:31:08.525  1020  1521 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:08.525  1020  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-16 14:31:08.535   258   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-16 14:31:08.535   258   516 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 14:31:08.535  3111  3111 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-16 14:31:08.535  1020  1521 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:08.535  1020  1521 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:08.535  1020  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-16 14:31:08.545  1020  1044 W libprocessgroup: failed to open /acct/uid_10097/pid_2812/cgroup.procs: No such file or directory
,03-16 14:31:08.545  3207  3297 I qtaguid : Tagging socket 39 with tag 100000000{1,0} for uid -1, pid: 3207, getuid(): 10052
,03-16 14:31:08.545  1020  1044 W libprocessgroup: failed to open /acct/uid_1101/pid_2844/cgroup.procs: No such file or directory
,03-16 14:31:08.545  1020  1044 W libprocessgroup: failed to open /acct/uid_10003/pid_1618/cgroup.procs: No such file or directory
,03-16 14:31:08.565  1323  3101 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-16 14:31:08.595  3602  3602 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
,03-16 14:31:08.605  3602  3602 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,03-16 14:31:08.605  3618  3618 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
,03-16 14:31:08.605  1020  1527 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:08.605  1020  1527 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:08.605  1020  1527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,03-16 14:31:08.605  1020  1521 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:08.605  1020  1521 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:08.605  1020  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-16 14:31:08.615  3602  3602 D NPS_WSSNPS: [] Service onCreate!!
,03-16 14:31:08.615  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:08.615  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:08.615  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-16 14:31:08.615  1020  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-16 14:31:08.615  1020  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.615  1020  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.615  1020  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:08.625  3618  3648 V OneTimeService: OneTimeService.onHandleIntent,
,03-16 14:31:08.625  1323  3101 D Settings_Utils: isSupportVNFestival SM-A300FU XEO
,03-16 14:31:08.635  3650  3650 E Zygote  : MountEmulatedStorage()
03-16 14:31:08.635  3650  3650 E Zygote  : v2
03-16 14:31:08.635  3650  3650 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:08.635  3650  3650 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:08.635  3650  3650 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:08.635  1020  1525 I ActivityManager: Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3650 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 14:31:08.635  3650  3650 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:08.635  3650  3650 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:08.645  1020  1141 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:08.645  1020  1141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:08.645  1020  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-16 14:31:08.655  1020  1142 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:08.655  1020  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:08.655  1020  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-16 14:31:08.665  3650  3650 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:08.665  3650  3650 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:08.665  1020  1527 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:08.665  1020  1527 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:08.665  1020  1527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-16 14:31:08.675  1020  1396 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-16 14:31:08.675  3602  3602 D NPS_WSSNPS: [50.150321] smlDBHelper
03-16 14:31:08.675  3602  3658 D NPS_WSSNPS: [50.150321] NpsServiceTask Start
,03-16 14:31:08.685  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:08.685  1020  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:08.685  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
03-16 14:31:08.705  1020  1759 I ActivityManager: Killing 2256:flipboard.app/u0a96 (adj 15): empty #31
03-16 14:31:08.705  3602  3602 I NPS_WSSNPS: [50.150321] AsyncBulkFlagCheck
03-16 14:31:08.715  3299  3527 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
03-16 14:31:08.715  3299  3527 I chromium: 
,03-16 14:31:08.725  3602  3678 I NPS_WSSNPS: [50.150321] IsRemain_AsyncBulkCheck
,03-16 14:31:08.725  3602  3678 I NPS_WSSNPS: [50.150321] IsRemain_Asyncing nothing
,03-16 14:31:08.725  3602  3678 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,03-16 14:31:08.725  1020  1519 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:08.725  1020  1519 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:08.725  1020  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-16 14:31:08.725  3602  3602 D NPS_WSSNPS: [50.150321] Service onDestroy
,03-16 14:31:08.745  1020  1520 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:08.745  1020  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:08.745  1020  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-16 14:31:08.745  1020  1396 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:08.745  1020  1396 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:08.745  1020  1396 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-16 14:31:08.755  1714  1714 I Hs20UtilService: Starting #7
,03-16 14:31:08.755  1714  1769 I Hs20UtilService: Message received 5003
,03-16 14:31:08.755  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:08.755  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.755  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.755  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:08.755  3299  3299 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-16 14:31:08.765  1858  1858 I SamsungIME: getDebugLevel  : 0x4f4c
,03-16 14:31:08.765  3688  3688 E Zygote  : MountEmulatedStorage()
03-16 14:31:08.765  3688  3688 E Zygote  : v2
03-16 14:31:08.765  3688  3688 I libpersona: KNOX_SDCARD checking this for 10018
03-16 14:31:08.765  3688  3688 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:08.775  3688  3688 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:08.775  1323  3101 W ResourceType: Failure getting entry for 0x7f0202b4 (t=1 e=692) (error -75)
,03-16 14:31:08.775  3688  3688 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:08.775  1020  1141 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3688 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
03-16 14:31:08.775  3688  3688 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:08.775  3602  3602 I NPS_WSSNPS: [50.150321] smlBRConfigurationDelete
03-16 14:31:08.775  3602  3602 I NPS_WSSNPS: [50.150321] smlBRMessageDelete
,03-16 14:31:08.785  3602  3602 I NPS_WSSNPS: [50.150321] smlBREmailDelete
,03-16 14:31:08.785  1323  3101 W ResourceType: Failure getting entry for 0x7f020510 (t=1 e=1296) (error -75)
,03-16 14:31:08.785  3602  3602 I NPS_WSSNPS: [50.150321] smlBRNetworkDelete
03-16 14:31:08.785  3602  3602 I NPS_WSSNPS: [50.150321] smlBRCallLogDelete
,03-16 14:31:08.785  3602  3602 I NPS_WSSNPS: [50.150321] smlBRMiniDiaryDelete
03-16 14:31:08.785  3602  3602 I NPS_WSSNPS: [50.150321] smlBRPenMemoMDelete
03-16 14:31:08.785  3602  3602 I NPS_WSSNPS: [50.150321] smlBRSMemoDelete
,03-16 14:31:08.785  3602  3602 I NPS_WSSNPS: [50.150321] cpuBooster release : false
,03-16 14:31:08.795  3602  3602 D NPS_WSSNPS: [50.150321] dsServerSocket close
03-16 14:31:08.795  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:08.795  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:08.795  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-16 14:31:08.795  1020  1033 I ActivityManager: Killing 2904:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
,03-16 14:31:08.815  1020  1759 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:08.815  1020  1759 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:08.815  1020  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-16 14:31:08.825  3688  3688 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:08.825  3688  3688 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:08.825  1020  1527 D SettingsProvider: name = access_control_enabled
,03-16 14:31:08.835  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:08.835  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.835  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.835  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:08.865  3707  3707 E Zygote  : MountEmulatedStorage()
03-16 14:31:08.865  3707  3707 E Zygote  : v2
03-16 14:31:08.865  3707  3707 I libpersona: KNOX_SDCARD checking this for 10065
03-16 14:31:08.865  3707  3707 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:08.865  3707  3707 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-16 14:31:08.865  1020  1141 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3707 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 14:31:08.875  1020  1141 I ActivityManager: Killing 2923:com.sec.usbsettings/1000 (adj 15): empty #31
,03-16 14:31:08.875  3707  3707 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:08.875  3688  3688 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Mar 16 14:31:08 GMT+01:00 2016
,03-16 14:31:08.875  3707  3707 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:08.885  1020  1759 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:08.885  1020  1759 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:08.885  1020  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-16 14:31:08.895  3688  3688 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-16 14:31:08.895  1020  1396 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.895  1020  1396 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.895  1020  1396 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.895  1020  1396 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:08.915  3707  3707 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:08.915  3707  3707 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:08.915  3724  3724 E Zygote  : MountEmulatedStorage(),
03-16 14:31:08.915  3724  3724 E Zygote  : v2
03-16 14:31:08.915  3724  3724 I libpersona: KNOX_SDCARD checking this for 10020,
03-16 14:31:08.915  3724  3724 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:08.915  1020  1396 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3724 uid=10020 gids={50020, 9997, 1028, 3003} abi=armeabi-v7a
03-16 14:31:08.915  3724  3724 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:31:08.915  1858  1858 I SamsungIME: getDebugLevel  : 0x4f4c
,03-16 14:31:08.915  3724  3724 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:08.925  3688  3688 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
03-16 14:31:08.925  1020  1352 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-16 14:31:08.925  3724  3724 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:08.925  1020  1521 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:08.925  1020  1521 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:08.925  1020  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-16 14:31:08.945  3724  3724 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:08.945  3724  3724 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:08.955  1858  1858 I SamsungIME: KeybaordView init() : load resources
,03-16 14:31:08.955  3688  3688 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-16 14:31:08.955  3688  3688 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-16 14:31:08.965  3111  3680 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
,03-16 14:31:08.965  3111  3680 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,03-16 14:31:08.975  3111  3680 I System.out: Thread-443(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-16 14:31:08.975  3111  3680 I System.out: Thread-443(ApacheHTTPLog):isSBSettingEnabled false
,03-16 14:31:08.975  3111  3680 I System.out: Thread-443(ApacheHTTPLog):isShipBuild true
03-16 14:31:08.975  3111  3680 I System.out: Thread-443(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-16 14:31:08.975  3111  3680 I System.out: Thread-443(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-16 14:31:08.975  3688  3722 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-16 14:31:08.975   280  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-16 14:31:08.975   280  1012 D Netd    : getNetworkForDns: using netid 502 for uid 10161
,03-16 14:31:08.985  1020  1396 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:08.985  1020  1396 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:08.985  1020  1396 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-16 14:31:08.985  3688  3722 I KLMS-2.5.123: : KLMSIntentService(): BOOT_COMPLETED
,03-16 14:31:08.995  1020  1352 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:08.995  1020  1352 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:08.995  1020  1352 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-16 14:31:09.015  3111  3689 W MessageQueue: Handler (android.os.Handler) {fa791d} sending message to a Handler on a dead thread
03-16 14:31:09.015  3111  3689 W MessageQueue: java.lang.IllegalStateException: Handler (android.os.Handler) {fa791d} sending message to a Handler on a dead thread
03-16 14:31:09.015  3111  3689 W MessageQueue: 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:325)
03-16 14:31:09.015  3111  3689 W MessageQueue: 	at android.os.Handler.enqueueMessage(Handler.java:631)
03-16 14:31:09.015  3111  3689 W MessageQueue: 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
03-16 14:31:09.015  3111  3689 W MessageQueue: 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
03-16 14:31:09.015  3111  3689 W MessageQueue: 	at android.os.Handler.post(Handler.java:326)
03-16 14:31:09.015  3111  3689 W MessageQueue: 	at ffw.a(SourceFile:327)
03-16 14:31:09.015  3111  3689 W MessageQueue: 	at guw.a(SourceFile:120)
03-16 14:31:09.015  3111  3689 W MessageQueue: 	at guf.c(SourceFile:26)
03-16 14:31:09.015  3111  3689 W MessageQueue: 	at gui.run(SourceFile:297)
03-16 14:31:09.015  3111  3689 W MessageQueue: 	at android.os.Handler.handleCallback(Handler.java:739)
03-16 14:31:09.015  3111  3689 W MessageQueue: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-16 14:31:09.015  3111  3689 W MessageQueue: 	at android.os.Looper.loop(Looper.java:145)
03-16 14:31:09.015  3111  3689 W MessageQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-16 14:31:09.015  3095  3320 I System.out: pool-10-thread-1 calls detatch()
,03-16 14:31:09.015  3268  3268 I RlzPingService: Setting next ping for 1458739869030
,03-16 14:31:09.035  3207  3297 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3207, getuid(): 10052
,03-16 14:31:09.035  3207  3297 I qtaguid : Untagging socket 43
,03-16 14:31:09.035  3207  3297 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3207, getuid(): 10052
,03-16 14:31:09.035  3207  3297 I qtaguid : Untagging socket 43
,03-16 14:31:09.035  3207  3297 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3207, getuid(): 10052
03-16 14:31:09.035  3207  3297 I qtaguid : Untagging socket 43
,03-16 14:31:09.035  3207  3297 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3207, getuid(): 10052
,03-16 14:31:09.035  3207  3297 I qtaguid : Untagging socket 43
,03-16 14:31:09.035  3207  3297 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3207, getuid(): 10052
03-16 14:31:09.035  3207  3297 I qtaguid : Untagging socket 43
,03-16 14:31:09.045  3207  3297 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3207, getuid(): 10052
,03-16 14:31:09.045  3207  3297 I qtaguid : Untagging socket 43
,03-16 14:31:09.045  3207  3297 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3207, getuid(): 10052
,03-16 14:31:09.045  3207  3297 I qtaguid : Untagging socket 43
,03-16 14:31:09.045  3207  3297 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3207, getuid(): 10052
,03-16 14:31:09.045  3207  3297 I qtaguid : Untagging socket 43
,03-16 14:31:09.045  3207  3297 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3207, getuid(): 10052
,03-16 14:31:09.045  3207  3297 I qtaguid : Untagging socket 43
,03-16 14:31:09.045  3207  3297 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3207, getuid(): 10052
,03-16 14:31:09.045  3207  3297 I qtaguid : Untagging socket 43
03-16 14:31:09.045  3207  3297 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3207, getuid(): 10052
,03-16 14:31:09.045  3207  3297 I qtaguid : Untagging socket 43
,03-16 14:31:09.045  3207  3297 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3207, getuid(): 10052
03-16 14:31:09.045  3207  3297 I qtaguid : Untagging socket 43
,03-16 14:31:09.045  3207  3297 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3207, getuid(): 10052
,03-16 14:31:09.045  3207  3297 I qtaguid : Untagging socket 43
,03-16 14:31:09.065  3707  3707 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,03-16 14:31:09.065  1858  1858 I SamsungIME: getCurrentKeyboard
03-16 14:31:09.065  1858  1858 I SamsungIME: getTextKeyboard
,03-16 14:31:09.095  1911  1911 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,03-16 14:31:09.095  1020  1352 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:09.095  1020  1352 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:09.095  1020  1352 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,03-16 14:31:09.115  1911  1911 D SecUISvc: Service started flags 0 startId 1
03-16 14:31:09.115  1911  3747 D SecUISvc: Thread created.
,03-16 14:31:09.125  1858  1858 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-16 14:31:09.125  1020  1044 W libprocessgroup: failed to open /acct/uid_10096/pid_2256/cgroup.procs: No such file or directory
03-16 14:31:09.125  1020  1044 W libprocessgroup: failed to open /acct/uid_10153/pid_2904/cgroup.procs: No such file or directory
03-16 14:31:09.125  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2923/cgroup.procs: No such file or directory
,03-16 14:31:09.145  3688  3688 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-16 14:31:09.155  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:09.155  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:09.155  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:09.155  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:09.165  3751  3751 E Zygote  : MountEmulatedStorage(),
03-16 14:31:09.165  3751  3751 E Zygote  : v2
03-16 14:31:09.165  3751  3751 I libpersona: KNOX_SDCARD checking this for 1000,
03-16 14:31:09.165  3751  3751 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:09.175  1020  1141 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3751 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 14:31:09.175  3751  3751 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-16 14:31:09.175  1020  1032 V VibratorService: hasVibrator - useVibetonz: true,
03-16 14:31:09.175  3751  3751 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:09.175  3751  3751 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:09.195  1020  1142 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:09.205  1020  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:09.205  1020  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:09.235  1020  1525 I ActivityManager: Killing 2389:com.android.mms/u0a41 (adj 15): empty #31
,03-16 14:31:09.245  3751  3751 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:09.255  3751  3751 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:09.295  3207  3297 I qtaguid : Tagging socket 43 with tag 100000000{1,0} for uid -1, pid: 3207, getuid(): 10052
,03-16 14:31:09.315  3207  3319 I ContactAccountLoggerTas: canRun() : Opted Out
,03-16 14:31:09.315  2134  3760 D FileApkUtils: Optimizing (staging complete)
,03-16 14:31:09.325  2134  3760 D FileApkUtils: Optimizing: DynamiteModules-prod.apk [1dad65bca29c108ad7dad5d3707435ff0555d8adf974340225c102890df71a23]
,03-16 14:31:09.345  2134  3760 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
,03-16 14:31:09.355  1020  1032 I ActivityManager: Killing 2830:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
,03-16 14:31:09.365  1020  1020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,03-16 14:31:09.375  1020  1020 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,03-16 14:31:09.375  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:09.375  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:09.375  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:09.375  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:09.385  3751  3751 E MTPRx   : In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,03-16 14:31:09.385  3774  3774 E Zygote  : MountEmulatedStorage()
,03-16 14:31:09.385  3774  3774 E Zygote  : v2
,03-16 14:31:09.395  3774  3774 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:09.395  3774  3774 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:09.395  3774  3774 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:09.395  3774  3774 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:09.395  1020  1020 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3774 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 14:31:09.395  3774  3774 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:09.415  2134  3760 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk is already optimized. Bailing.
,03-16 14:31:09.425  1020  1352 I ActivityManager: Killing 2941:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
,03-16 14:31:09.425  3556  3781 I Gmail   : getAccountsCursor
,03-16 14:31:09.435  3774  3774 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:09.435  3143  3176 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
03-16 14:31:09.435  3774  3774 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:09.435  1020  1525 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-16 14:31:09.435  1020  1033 D SecContentProvider2: uri = 14 selection = getSealedState
03-16 14:31:09.435  1020  1033 D SecContentProvider2: mCursor = null
,03-16 14:31:09.445  1020  1491 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-16 14:31:09.445  1020  1491 D SecContentProvider2: mCursor = null
,03-16 14:31:09.445  3751  3751 V MTPRx   : sealedState: false
03-16 14:31:09.445  3751  3751 V MTPRx   : sealedUsbMassStorageState: false
,03-16 14:31:09.445  1020  1491 D SettingsProvider: name = mtp_usb_connection_status
,03-16 14:31:09.455  1020  1525 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:09.455  1020  1525 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:09.455  1020  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-16 14:31:09.465  1020  1519 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-16 14:31:09.475  1020  1521 D CountryDetector: No listener is left
,03-16 14:31:09.475  1020  1396 D SettingsProvider: name = media_player_mode
,03-16 14:31:09.475  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 14:31:09.485  1020  1044 E libprocessgroup: failed to kill 1 processes for processgroup 2389
,03-16 14:31:09.495  1020  1044 W libprocessgroup: failed to open /acct/uid_10081/pid_2830/cgroup.procs: No such file or directory
,03-16 14:31:09.505  1020  1044 W libprocessgroup: failed to open /acct/uid_10043/pid_2941/cgroup.procs: No such file or directory
,03-16 14:31:09.505  3556  3556 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-16 14:31:09.525  1020  1032 D SettingsProvider: name = mtp_usb_conditions_met
,03-16 14:31:09.525  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 14:31:09.535  3556  3792 I Gmail   : Observing account changes for notifications
,03-16 14:31:09.545  1020  1527 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:09.545  1020  1527 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:09.545  1020  1527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:09.555  1020  1519 D SettingsProvider: name = mtp_running_status
,03-16 14:31:09.555  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 14:31:09.565  1843  1843 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 14:31:09.575  1020  1759 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:09.575  1020  1759 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:09.575  1323  3101 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
03-16 14:31:09.575  1020  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-16 14:31:09.575  3774  3774 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,03-16 14:31:09.575  1020  1521 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:09.575  1020  1521 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:09.575  1020  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-16 14:31:09.585  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:09.585  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:09.585  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:09.585  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:09.595  1020  1033 D SettingsProvider: name = media_mount_count
,03-16 14:31:09.595  3797  3797 E Zygote  : MountEmulatedStorage()
03-16 14:31:09.595  3797  3797 E Zygote  : v2
03-16 14:31:09.595  3797  3797 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:09.595  3797  3797 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:09.595  3797  3797 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:09.595  3797  3797 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:09.595  3797  3797 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:09.605  2620  2700 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-16 14:31:09.605  1020  1141 I ActivityManager: Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3797 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 14:31:09.605  1020  1759 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:09.605  1020  1759 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:09.605  1020  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
03-16 14:31:09.605  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 14:31:09.615  1020  1032 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-16 14:31:09.625  1843  1843 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 14:31:09.625  1020  1525 D SettingsProvider: name = mtp_sync_alive
,03-16 14:31:09.635  1843  1843 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 14:31:09.635  1020  1759 D SettingsProvider: name = sdcard_launch
,03-16 14:31:09.635  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 14:31:09.635  3797  3797 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:09.645  3797  3797 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:09.655  1020  1396 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:09.655  1020  1396 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:09.655  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 14:31:09.655  1020  1396 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:09.655  1020  1520 D SettingsProvider: name = boot_time_connected
,03-16 14:31:09.665  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 14:31:09.665  1020  1396 D SettingsProvider: name = mtp_open_session
,03-16 14:31:09.675  3556  3814 E Gmail   : Error finding the version of the Email provider.....
03-16 14:31:09.675  3556  3814 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-16 14:31:09.675  3556  3814 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
03-16 14:31:09.675  3556  3814 E Gmail   : 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
03-16 14:31:09.675  3556  3814 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
03-16 14:31:09.675  3556  3814 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-16 14:31:09.675  3556  3814 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 14:31:09.675  3556  3814 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
03-16 14:31:09.675  3556  3814 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 14:31:09.675  3556  3814 W EmailMigration: We do not support migrating this version of the Email provider.
,03-16 14:31:09.675  3797  3797 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-16 14:31:09.675  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:09.675  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:09.675  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:09.685  3111  3680 I System.out: Thread-443 calls detatch()
,03-16 14:31:09.685  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 14:31:09.685  1020  1352 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:09.685  1020  1352 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:09.685  1020  1352 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-16 14:31:09.695  3556  3785 I Gmail   : getAccountsCursor
,03-16 14:31:09.695  3797  3797 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,03-16 14:31:09.715  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:09.715  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:09.715  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,03-16 14:31:09.715  3455  3455 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-16 14:31:09.725  3455  3455 I PCWCLIENTTRACE_PushUtil: sales region : global
03-16 14:31:09.725  3455  3455 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-16 14:31:09.725  3455  3455 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.BOOT_COMPLETED
03-16 14:31:09.725  3455  3455 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Version: 4.82
03-16 14:31:09.725  3455  3455 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Push type: [SPP, GCM]
,03-16 14:31:09.725  1020  1141 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:09.725  1020  1141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:09.725  1020  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-16 14:31:09.725  1020  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:09.725  1020  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:09.725  1020  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:09.725  1020  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:09.735  3797  3797 I F_PHONE : [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,03-16 14:31:09.735  3797  3797 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,03-16 14:31:09.745  3822  3822 E Zygote  : MountEmulatedStorage()
,03-16 14:31:09.745  3822  3822 E Zygote  : v2
03-16 14:31:09.745  3822  3822 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:09.745  3822  3822 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:09.745  3822  3822 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-16 14:31:09.745  3822  3822 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:09.745  3822  3822 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:09.755  1020  1521 I ActivityManager: Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3822 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 14:31:09.755  1020  1759 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:09.755  1020  1759 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:09.755  1020  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,03-16 14:31:09.775  3455  3455 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,03-16 14:31:09.795  3822  3822 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:09.795  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:09.795  3822  3822 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:09.795  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:09.795  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,03-16 14:31:09.815  3797  3797 D F_PHONE : [[com.sec.bcservice]] onServiceConnected()
03-16 14:31:09.815  3797  3797 I F_PHONE : default registerAction()
03-16 14:31:09.815  3797  3797 I F_PHONE : [[com.sec.bcservice]] sendPendingMessage()
,03-16 14:31:09.815  1020  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:09.815  1020  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:09.815  1020  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:09.815  1020  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:09.825  3455  3455 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-16 14:31:09.825  3299  3630 W jxcore-log: Initializing JXcore engine,
03-16 14:31:09.825  3299  3630 W jxcore-log: JXcore engine is ready
03-16 14:31:09.825  3822  3822 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.,
,03-16 14:31:09.835  1667  3840 I GoogleHttpClient: GMS http client unavailable, use old client
,03-16 14:31:09.835  3842  3842 E Zygote  : MountEmulatedStorage()
03-16 14:31:09.835  1020  1352 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3842 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,03-16 14:31:09.835  3842  3842 E Zygote  : v2
,03-16 14:31:09.835  3842  3842 I libpersona: KNOX_SDCARD checking this for 10102
,03-16 14:31:09.835  3842  3842 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:09.835  3842  3842 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:09.845  3842  3842 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:09.845  3842  3842 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-16 14:31:09.845  1020  1520 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:09.845  1020  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:09.845  1020  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:09.855  3455  3455 I ReactiveServiceManager: Supported : 1
,03-16 14:31:09.855  1020  1759 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-16 14:31:09.855  2582  2582 D FactoryTestApp: [DummyFtClient$onDestroy](2582) Destroy DummyFtClient service
,03-16 14:31:09.865  1020  1032 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,03-16 14:31:09.865  1020  1032 D QSEECOMAPI: : App is not loaded in QSEE
,03-16 14:31:09.875  2582  2582 D FactoryTestApp: [Support$Values.getString](2582) id=MODEL_COMMUNICATION_MODE, value=gsm
,03-16 14:31:09.875  3842  3842 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:09.875  2582  2582 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2582) mConnectionMode = gsm
,03-16 14:31:09.875  2582  2582 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2582) RUNNING_FTCLIENT : false
,03-16 14:31:09.875  3842  3842 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:09.875  2582  2582 D FactoryTestApp: [DummyFtClient$onDestroy](2582) kill process
,03-16 14:31:09.875  2582  2582 I Process : Sending signal. PID: 2582 SIG: 9
,03-16 14:31:09.895  1020  1032 D QSEECOMAPI: : Loaded image: APP id = 9
,03-16 14:31:09.895  1020  1142 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-16 14:31:09.895  3842  3842 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 14:31:09.905  1020  1032 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-16 14:31:09.905  1020  1032 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 9
,03-16 14:31:09.905  1020  1032 E terrier : handleString: Failed to handle string(-4)
03-16 14:31:09.905  1020  1032 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,03-16 14:31:09.905  1902  1902 E audit   : type=1400 msg=audit(1458135069.905:205): avc:  denied  { ioctl } for  pid=3630 comm="Thread-458" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-16 14:31:09.915  1902  1902 E audit   :  SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:09.915  1902  1902 E audit   : type=1300 msg=audit(1458135069.905:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=4 a3=9eaf98f8 items=0 ppid=310 ppcomm=main pid=3630 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-458" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
,03-16 14:31:09.915  1902  1902 E audit   : type=1320 msg=audit(1458135069.905:205): 
03-16 14:31:09.915  1843  1843 D ChimeraCfgMgr: Reading stored module config
,03-16 14:31:09.915  3455  3455 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
,03-16 14:31:09.915  3455  3455 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
03-16 14:31:09.915  1020  1759 I ActivityManager: Process com.sec.factory (pid 2582)(adj 0) has died(22,673)
,03-16 14:31:09.915  3455  3455 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-16 14:31:09.925  3455  3455 I PCWCLIENTTRACE_PushUtil: sales region : global
,03-16 14:31:09.925  3455  3455 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,03-16 14:31:09.925  3455  3455 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,03-16 14:31:09.925  3299  3630 W jxcore-log: Starting JXcore engine
,03-16 14:31:09.925  3822  3822 D BluetoothBDAdrressReceiver: onReceive(), action: android.intent.action.BOOT_COMPLETED
,03-16 14:31:09.925  3822  3822 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,03-16 14:31:09.935  1020  1519 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:09.935  1020  1519 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 14:31:09.935  1020  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,03-16 14:31:09.945  3556  3556 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@6296fe9 that was originally bound here
03-16 14:31:09.945  3556  3556 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@6296fe9 that was originally bound here
03-16 14:31:09.945  3556  3556 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
03-16 14:31:09.945  3556  3556 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
03-16 14:31:09.945  3556  3556 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
03-16 14:31:09.945  3556  3556 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
03-16 14:31:09.945  3556  3556 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
03-16 14:31:09.945  3556  3556 E ActivityThread: 	at com.android.emailcommon.service.H.a(SourceFile:181)
03-16 14:31:09.945  3556  3556 E ActivityThread: 	at com.android.emailcommon.service.H.mb(SourceFile:224)
03-16 14:31:09.945  3556  3556 E ActivityThread: 	at com.android.email.service.n.j(SourceFile:160)
03-16 14:31:09.945  3556  3556 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:171)
03-16 14:31:09.945  3556  3556 E ActivityThread: 	at com.android.email.provider.b.F(SourceFile:115)
03-16 14:31:09.945  3556  3556 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
03-16 14:31:09.945  3556  3556 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
03-16 14:31:09.945  3556  3556 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-16 14:31:09.945  3556  3556 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 14:31:09.945  3556  3556 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-16 14:31:09.945  3556  3556 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 14:31:09.945  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:09.945  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:09.945  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:09.955  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:09.955  1458  1458 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-16 14:31:09.965  1458  1458 D BluetoothBDTestService: onCreate()
,03-16 14:31:09.965  1458  1458 E BluetoothBDTestService: onStart(), extra_type: BOOT_COMPLETED
03-16 14:31:09.965  1458  1458 E BluetoothBDTestService: bd_address_path: /efs/bluetooth/bt_addr
,03-16 14:31:09.965  1458  1458 E BluetoothBDTestService: already exist!( /efs/bluetooth/bt_addr ), file length: 17
,03-16 14:31:09.975  1020  1141 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3859 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,03-16 14:31:09.985  3859  3859 E Zygote  : MountEmulatedStorage()
03-16 14:31:09.985  3859  3859 I libpersona: KNOX_SDCARD checking this for 10028
03-16 14:31:09.985  3859  3859 E Zygote  : v2
03-16 14:31:09.985  3859  3859 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:09.985  3859  3859 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:09.985  3859  3859 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:09.985  3859  3859 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 14:31:10.025  3859  3859 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:10.025  3859  3859 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:10.035   310   310 I art     : Explicit concurrent mark sweep GC freed 8737(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 607us total 56.777ms
,03-16 14:31:10.055   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 580us total 26.717ms
,03-16 14:31:10.075  1843  1843 D WearableService: callingUid 10011, callindPid: 1843
,03-16 14:31:10.075   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 19.278ms
,03-16 14:31:10.205  2134  2134 W InstanceID/Rpc: Found 10011
,03-16 14:31:10.215  1020  1142 I art     : Explicit concurrent mark sweep GC freed 23472(1202KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/33MB, paused 2.740ms total 275.185ms
,03-16 14:31:10.215  1020  1396 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@1240e71d
,03-16 14:31:10.225  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:10.225  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:10.225  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:10.225  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:10.235  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
,03-16 14:31:10.235  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 14:31:10.235  3774  3813 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 14:31:10.235  3774  3813 I AMMetaDataParserService: getResourcePackageName:assistantlist
03-16 14:31:10.235  3774  3813 I AMMetaDataParserService: Resource data:2131165186
,03-16 14:31:10.245  3874  3874 E Zygote  : MountEmulatedStorage()
,03-16 14:31:10.245  3874  3874 E Zygote  : v2
03-16 14:31:10.245  3874  3874 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:10.245  3874  3874 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:10.245  3874  3874 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:10.245  1020  1141 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3874 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 14:31:10.245  3874  3874 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:10.245  3874  3874 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:10.255  1843  1843 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 14:31:10.285  3874  3874 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:10.285  3874  3874 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:10.305   290   290 E SMD     : DCD OFF
,03-16 14:31:10.315  3874  3874 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 14:31:10.355  3774  3813 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-16 14:31:10.355  3774  3813 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 14:31:10.355  3774  3813 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-16 14:31:10.355  3774  3813 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 14:31:10.365  3774  3813 I AMMetaDataParserService: getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
,03-16 14:31:10.365  3774  3813 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 14:31:10.395  1020  1142 D PersonaManagerService: getPersonasForUser(): returning null!
,03-16 14:31:10.425  1843  1843 E GmsWearableNodeHelper: GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-16 14:31:10.435  3143  3176 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,03-16 14:31:10.465  3874  3874 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,03-16 14:31:10.465  3874  3874 I KnoxUsageLogPro: premStatus:2
,03-16 14:31:10.465  3874  3874 I KnoxUsageLogPro: isEulaShown : false
03-16 14:31:10.465  3874  3874 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,03-16 14:31:10.465  3874  3896 I KnoxUsageLogPro: savePreference: key = previous_sys_time value = 1458135070477
,03-16 14:31:10.555  3216  3256 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-16 14:31:10.565  3774  3813 I AMMetaDataParserService: Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,03-16 14:31:10.565  3556  3818 E SQLiteLog: (283) recovered 61 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-16 14:31:10.575  1020  1759 I ActivityManager: Killing 3018:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,03-16 14:31:10.585  1020  1519 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:10.585  1020  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:10.585  1020  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:10.605  3216  3256 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-16 14:31:10.615  3216  3256 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-16 14:31:10.615  3216  3256 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-16 14:31:10.615  3216  3256 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-16 14:31:10.615  3216  3256 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-16 14:31:10.625  3216  3256 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-16 14:31:10.625  3216  3256 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-16 14:31:10.655  1020  1519 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:10.655  1020  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:10.655  1020  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:10.685  3859  3859 I System.out: Inside onCreate() of WakeupTriggerProvide
,03-16 14:31:10.685  3859  3859 I System.out: Inside WakeupProvider
,03-16 14:31:10.715  3774  3813 I AMMetaDataParserService: Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,03-16 14:31:10.735  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3018/cgroup.procs: No such file or directory
,03-16 14:31:10.745  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:10.745  1020  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:10.745  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:10.755  3774  3813 I AMMetaDataParserService: Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
,03-16 14:31:10.765  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
,03-16 14:31:10.765  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
,03-16 14:31:10.765  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
03-16 14:31:10.765  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
,03-16 14:31:10.765  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
03-16 14:31:10.765  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
,03-16 14:31:10.765  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
03-16 14:31:10.765  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
,03-16 14:31:10.765  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
,03-16 14:31:10.765  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
,03-16 14:31:10.775  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
,03-16 14:31:10.775  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
,03-16 14:31:10.775  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
,03-16 14:31:10.775  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
,03-16 14:31:10.775  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
03-16 14:31:10.775  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
03-16 14:31:10.775  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
,03-16 14:31:10.775  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
03-16 14:31:10.775  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
,03-16 14:31:10.775  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
03-16 14:31:10.775  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
,03-16 14:31:10.775  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
03-16 14:31:10.775  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
,03-16 14:31:10.775  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
03-16 14:31:10.775  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
,03-16 14:31:10.775  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
03-16 14:31:10.775  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
,03-16 14:31:10.775  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
03-16 14:31:10.775  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
,03-16 14:31:10.775  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
03-16 14:31:10.775  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
,03-16 14:31:10.775  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
03-16 14:31:10.775  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
03-16 14:31:10.775  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
,03-16 14:31:10.775  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,03-16 14:31:10.785  1020  1141 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:10.785  1020  1141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:10.785  1020  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:10.785  3859  3859 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
,03-16 14:31:10.795  3842  3909 I Babel   : MmsConfig: mnc/mcc: 0/0
03-16 14:31:10.795  3842  3909 I Babel   : MmsConfig.loadMmsSettings
03-16 14:31:10.795  3842  3909 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
03-16 14:31:10.795  3842  3909 I Babel   : MmsConfig.loadFromDatabase
,03-16 14:31:10.805  1020  1527 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:10.805  1020  1527 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:10.805  1020  1527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-16 14:31:10.805  1843  1843 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 14:31:10.805  1843  1843 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 14:31:10.835  1020  1519 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:10.835  1020  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:10.835  1020  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-16 14:31:10.845  3874  3896 I KnoxUsageLogPro: savePreference: key = previous_elapsed_time value = 40375
,03-16 14:31:10.845  3774  3813 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,03-16 14:31:10.875  3859  3859 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
,03-16 14:31:10.885  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
,03-16 14:31:10.885  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:10.885  3774  3813 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 14:31:10.885  3774  3813 I AMMetaDataParserService: Resource data:2131034113
03-16 14:31:10.885  3774  3813 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-16 14:31:10.885  3774  3813 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 14:31:10.885  3774  3813 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-16 14:31:10.895  3774  3813 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
,03-16 14:31:10.895  3774  3813 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 14:31:10.895  3842  3907 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-16 14:31:10.905  1020  1520 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:10.905  1020  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:10.905  1020  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:10.915  3842  3909 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,03-16 14:31:10.915  3842  3909 I Babel   : MmsConfig.loadFromResources
,03-16 14:31:10.915  3842  3909 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,03-16 14:31:10.915  3842  3909 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,03-16 14:31:10.915  3842  3907 W AudioCapabilities: Unsupported mime audio/evrc
,03-16 14:31:10.925  3842  3907 W AudioCapabilities: Unsupported mime audio/qcelp
,03-16 14:31:10.935  3842  3907 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,03-16 14:31:10.935  3842  3842 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-16 14:31:10.935  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:10.935  1020  1521 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:10.935  1020  1521 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:10.935  1020  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:10.935  3842  3907 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,03-16 14:31:10.945  3774  3813 I GFX construct_block_size_descriptor_2d second part: took 4.344376ms for 0*0 texture 0
,03-16 14:31:10.965  2134  3902 D GCM     : COMPAT: Multi user not supported,
,03-16 14:31:10.965  3842  3907 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,03-16 14:31:10.965  3842  3907 W AudioCapabilities: Unsupported mime audio/x-ima
,03-16 14:31:10.975  3842  3907 W AudioCapabilities: Unsupported mime audio/qcelp
,03-16 14:31:10.975  3842  3907 W AudioCapabilities: Unsupported mime audio/evrc
,03-16 14:31:10.975  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:10.975  1020  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:10.975  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:10.985  1843  1843 D GCM     : COMPAT: Multi user not supported
,03-16 14:31:10.985  3774  3813 I GFX generate_partition_tables: took 15.332864ms for 0*0 texture 0
,03-16 14:31:10.985  3774  3813 I GFX raster: took 20.950469ms for 96*96 texture 0
03-16 14:31:10.985  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b3e3f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b3e538 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:10.995  1323  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,03-16 14:31:10.995  1323  3101 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,03-16 14:31:10.995  1323  3101 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
,03-16 14:31:11.005  3556  3818 E File    : fail readDirectory() errno=2
,03-16 14:31:11.005  1020  1520 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:11.005  1020  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:11.005  1020  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:11.015  1020  1352 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:11.015  1020  1352 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:11.015  1020  1352 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:11.015  3842  3907 W VideoCapabilities: Unsupported mime video/wvc1
,03-16 14:31:11.025  3842  3907 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-16 14:31:11.035  1020  1521 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:11.035  1020  1521 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:11.035  1020  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:11.055  1667  1683 I art     : Explicit concurrent mark sweep GC freed 3775(162KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 799us total 39.402ms
,03-16 14:31:11.065  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:11.065  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:11.065  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:11.065  3774  3813 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-16 14:31:11.065  1667  1691 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-16 14:31:11.065  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:11.065  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:11.065  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:11.075  2134  3902 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,03-16 14:31:11.075  1020  1352 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:11.075  1020  1352 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:11.075  1020  1352 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:11.075  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:11.075  3774  3813 I GFX raster: took 0.956562ms for 96*96 texture 0
,03-16 14:31:11.075  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b3e3f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b4c780 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:11.085  3842  3907 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,03-16 14:31:11.095  3842  3907 W VideoCapabilities: Unsupported mime video/wvc1
,03-16 14:31:11.095  3842  3907 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-16 14:31:11.105  3842  3907 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,03-16 14:31:11.115  3842  3907 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,03-16 14:31:11.115  3842  3907 W VideoCapabilities: Unsupported mime video/mp43
,03-16 14:31:11.115  3842  3907 W VideoCapabilities: Unsupported mime video/sorenson
,03-16 14:31:11.125  3556  3781 I Gmail   : getAccountsCursor
,03-16 14:31:11.125  3774  3813 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-16 14:31:11.135  3842  3907 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,03-16 14:31:11.135  3842  3842 V Babel   : babel boot account: SMS
,03-16 14:31:11.135  3842  3842 V Babel   : babel boot account: thalitester@gmail.com
,03-16 14:31:11.165  3556  3890 I Gmail   : notifyAccountChanged
,03-16 14:31:11.165  3859  3859 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,03-16 14:31:11.175  3859  3859 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,03-16 14:31:11.175  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:11.175  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:11.175  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:11.175  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:11.175  3556  3890 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-16 14:31:11.185  3923  3923 E Zygote  : MountEmulatedStorage()
,03-16 14:31:11.185  3923  3923 E Zygote  : v2,
03-16 14:31:11.185  1020  1527 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3923 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 14:31:11.195  3859  3859 D DialogFlow: initQueue()
03-16 14:31:11.185  1020  1527 I ActivityManager: Killing 1590:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
03-16 14:31:11.195  3923  3923 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:31:11.195  3923  3923 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:11.195  3923  3923 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:11.195  3923  3923 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:11.195  3923  3923 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:11.205  1020  1100 V AlarmManager: waitForAlarm result :4
,03-16 14:31:11.225  3842  3907 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-16 14:31:11.225  3556  3890 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-16 14:31:11.235  3923  3923 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:11.235  3923  3923 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:11.235  1020  1142 I ActivityManager: Killing 3007:com.sec.dsm.system/1000 (adj 15): empty #31
,03-16 14:31:11.245  1020  1100 V AlarmManager: waitForAlarm result :4
,03-16 14:31:11.265  3556  3890 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-16 14:31:11.265  3556  3890 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-16 14:31:11.285  2134  3939 I CheckinService: Disabling old GoogleServicesFramework version
,03-16 14:31:11.315  1020  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:11.315  1020  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:11.315  1020  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:11.315  1020  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:11.335  3940  3940 E Zygote  : MountEmulatedStorage()
,03-16 14:31:11.335  3940  3940 E Zygote  : v2
03-16 14:31:11.335  3940  3940 I libpersona: KNOX_SDCARD checking this for 10029
03-16 14:31:11.335  3940  3940 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:11.335  3940  3940 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:11.335  3940  3940 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 14:31:11.335  3940  3940 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:11.335  1020  1520 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3940 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,03-16 14:31:11.335  1020  1520 I ActivityManager: Killing 3063:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,03-16 14:31:11.375  3940  3940 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:11.375  3940  3940 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:11.435  1020  1519 D PowerManagerService: [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1181 (0x0)
,03-16 14:31:11.435  3143  3176 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,03-16 14:31:11.455  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:11.455  3774  3813 I GFX construct_block_size_descriptor_2d second part: took 2.152917ms for 0*0 texture 0
,03-16 14:31:11.465  3774  3813 I GFX generate_partition_tables: took 7.411979ms for 0*0 texture 0
,03-16 14:31:11.465  3774  3813 I GFX raster: took 10.489791ms for 96*96 texture 0
03-16 14:31:11.465  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb87788b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88d0bb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:11.485  3774  3813 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-16 14:31:11.495  1020  1044 W libprocessgroup: failed to open /acct/uid_10068/pid_1590/cgroup.procs: No such file or directory
,03-16 14:31:11.495  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3007/cgroup.procs: No such file or directory
,03-16 14:31:11.525  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3063/cgroup.procs: No such file or directory
,03-16 14:31:11.525  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:11.535  1020  1521 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:11.535  1020  1521 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:11.535  1020  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:11.545  3774  3813 I GFX raster: took 0.741093ms for 96*96 texture 0
,03-16 14:31:11.545  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b2c768 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb886ea38 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:11.565  3774  3813 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-16 14:31:11.595  2134  3955 I CheckinService: Checking schedule, now: 1458135071609 next: 1458299986961
,03-16 14:31:11.595  2134  3955 I CheckinService: active receiver: disabled
,03-16 14:31:11.605  1020  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:11.605  1020  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:11.605  1020  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:11.605  1020  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:11.615  3959  3959 E Zygote  : MountEmulatedStorage()
,03-16 14:31:11.615  3959  3959 E Zygote  : v2
03-16 14:31:11.615  3959  3959 I libpersona: KNOX_SDCARD checking this for 10030
,03-16 14:31:11.615  3959  3959 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:11.625  3959  3959 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:11.625  1020  1759 I ActivityManager: Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=3959 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-16 14:31:11.625  1020  1759 I ActivityManager: Killing 3048:com.google.android.configupdater/u0a82 (adj 15): empty #31,
,03-16 14:31:11.625  3959  3959 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 14:31:11.635  3959  3959 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-16 14:31:11.655  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-16 14:31:11.655  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-16 14:31:11.655  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:11.655  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 14:31:11.655  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:11.655  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:11.665  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:11.665  3774  3813 I GFX raster: took 0.840937ms for 96*96 texture 0
,03-16 14:31:11.665  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b2bbc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8777f38 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:11.665  1020  1142 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:11.665  1020  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:11.665  1020  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-16 14:31:11.675  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:11.675  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:11.675  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:11.675  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:11.675  3959  3959 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:11.685  3959  3959 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:11.715  3976  3976 E Zygote  : MountEmulatedStorage(),
03-16 14:31:11.715  1020  1491 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3976 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 14:31:11.715  3976  3976 E Zygote  : v2,
03-16 14:31:11.715  3976  3976 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:11.715  3976  3976 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:31:11.715  3976  3976 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:11.715  1020  1491 I ActivityManager: Killing 3095:com.dropbox.android/u0a88 (adj 15): empty #31
,03-16 14:31:11.725  3976  3976 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 14:31:11.725  3976  3976 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:11.755  3976  3976 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:11.755  3976  3976 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:11.815  3774  3813 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-16 14:31:11.815  1843  3992 D GCM     : GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,03-16 14:31:11.845   280  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-16 14:31:11.845   280  1012 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,03-16 14:31:11.865  1020  1519 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:11.865  1020  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:11.865  1020  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:11.915  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:11.915  3774  3813 I GFX raster: took 0.622396ms for 96*96 texture 0
03-16 14:31:11.915  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b2acb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88d0bb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:11.915  3774  3813 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-16 14:31:11.925  3976  3976 E KnoxSetupWizardClient: isShipMode : 1
,03-16 14:31:11.925  3976  3976 I KnoxSetupWizardClient: onReceive : android.intent.action.BOOT_COMPLETED
,03-16 14:31:11.955  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:11.955  3774  3813 I GFX raster: took 0.699948ms for 96*96 texture 0
03-16 14:31:11.955  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb886ea38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8777f38 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:11.965  3774  3813 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-16 14:31:11.965  1020  1527 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:11.975  1020  1527 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:11.975  1020  1527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:11.975  3959  3959 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-16 14:31:11.975  3959  3959 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 14:31:11.975  3959  3959 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-16 14:31:11.975  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:11.975  3774  3813 I GFX raster: took 0.542032ms for 96*96 texture 0
03-16 14:31:11.975  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88d0bb0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8777f38 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:11.985  3774  3813 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-16 14:31:11.985  1843  1843 I GCoreUlr: DispatchingService.onCreate()
,03-16 14:31:11.995  3976  3976 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,03-16 14:31:11.995  2134  2134 D SystemUpdateService: onCreate
,03-16 14:31:12.005  1667  1811 I art     : Explicit concurrent mark sweep GC freed 3191(125KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 805us total 186.922ms
,03-16 14:31:12.015  3976  3976 D KnoxShortcutUtil: getIsShortcutMigrationFor_2_3_0_Done true
03-16 14:31:12.015  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
03-16 14:31:12.015  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:12.015  3774  3813 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 14:31:12.015  3774  3813 I AMMetaDataParserService: Resource data:2131034113
,03-16 14:31:12.015  3774  3813 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-16 14:31:12.015  3774  3813 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 14:31:12.025  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:12.025  3774  3813 I GFX raster: took 0.865155ms for 96*96 texture 0
03-16 14:31:12.025  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b3e3f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8777f38 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:12.025  3976  3976 D ShortcutReceiver:  KnoxContainerVersion 2.3.0
,03-16 14:31:12.025  3976  3976 D ShortcutReceiver:  shortcut migration not required 
,03-16 14:31:12.035  1020  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:12.035  1020  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:12.035  1020  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:12.035  1020  1519 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:12.035  3959  3959 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 14:31:12.035  3774  3813 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-16 14:31:12.035  3959  3959 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 14:31:12.035  3959  3959 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 14:31:12.055  1020  1519 I ActivityManager: Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4004 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
03-16 14:31:12.055  1020  1519 I ActivityManager: Killing 3128:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,03-16 14:31:12.055  4004  4004 E Zygote  : MountEmulatedStorage(),
03-16 14:31:12.055  4004  4004 E Zygote  : v2
,03-16 14:31:12.055  4004  4004 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:12.055  4004  4004 I libpersona: KNOX_SDCARD not a persona,
03-16 14:31:12.055  3959  3959 W ResourcesManager: Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.,
03-16 14:31:12.055  1020  1142 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:12.055  3959  3959 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
03-16 14:31:12.055  1020  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:12.055  1020  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms,
,03-16 14:31:12.065  4004  4004 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-16 14:31:12.065  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,03-16 14:31:12.065  3774  3813 I GFX raster: took 0.835053ms for 96*96 texture 0,
03-16 14:31:12.065  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b3e3f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b5edc0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:12.065  4004  4004 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 14:31:12.065  4004  4004 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:12.075  3774  3813 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-16 14:31:12.085  3207  3354 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-16 14:31:12.105  3976  3997 W System.err: java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,03-16 14:31:12.125  1843  1843 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
03-16 14:31:12.125  3976  3997 W System.err: 	at android.os.Parcel.readException(Parcel.java:1544)
03-16 14:31:12.125  3976  3997 W System.err: 	at android.os.Parcel.readException(Parcel.java:1493)
03-16 14:31:12.125  3976  3997 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
03-16 14:31:12.125  3976  3997 W System.err: 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
,03-16 14:31:12.125  3976  3997 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
03-16 14:31:12.125  3976  3997 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,03-16 14:31:12.125  3556  3740 I Gmail   : getAccountsCursor
,03-16 14:31:12.135  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:12.135  3774  3813 I GFX raster: took 0.600833ms for 96*96 texture 0
03-16 14:31:12.135  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb87788b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8777f38 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:12.135  4004  4004 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:12.135  4004  4004 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:12.145  2134  2134 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-16 14:31:12.145  1843  4020 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,03-16 14:31:12.155  2134  2134 D ChimeraCfgMgr: Reading stored module config
,03-16 14:31:12.155  2134  3957 I Icing   : Storage manager: low false usage 2.11MB avail 9.95GB capacity 11.63GB
,03-16 14:31:12.165  3774  3813 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-16 14:31:12.175  1020  1044 W libprocessgroup: failed to open /acct/uid_10082/pid_3048/cgroup.procs: No such file or directory
03-16 14:31:12.175  1020  1044 W libprocessgroup: failed to open /acct/uid_10088/pid_3095/cgroup.procs: No such file or directory
,03-16 14:31:12.185  1020  1352 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:12.185  1020  1352 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:12.185  1020  1352 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:12.185  2134  2134 D BootCompletedReceiver: Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,03-16 14:31:12.185  2134  2134 D BootCompletedReceiver: Got an BootCompleted event.
,03-16 14:31:12.195  1843  1843 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 14:31:12.195  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:12.195  3774  3813 I GFX raster: took 0.595469ms for 96*96 texture 0
03-16 14:31:12.195  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b2c768 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8777f38 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:12.195  1843  1843 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 14:31:12.205  2134  2134 D BootCompletedReceiver: Will NOT schedule AdAttestation signal task because it's disabled.
,03-16 14:31:12.215  2134  4027 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
,03-16 14:31:12.215  3774  3813 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-16 14:31:12.235  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:12.235  3774  3813 I GFX raster: took 0.840834ms for 96*96 texture 0
03-16 14:31:12.235  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b2bbc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8777f38 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:12.235  3774  3813 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-16 14:31:12.255  4004  4004 D StatusChecker: onReceive : android.intent.action.BOOT_COMPLETED
,03-16 14:31:12.265  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:12.265  3774  3813 I GFX raster: took 0.623177ms for 96*96 texture 0
03-16 14:31:12.265  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b2acb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8777f38 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:12.275  3774  3813 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-16 14:31:12.285  4004  4004 I StatusChecker: onReceive : net.mt.init : DONE
,03-16 14:31:12.285  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:12.285  3774  3813 I GFX raster: took 0.712864ms for 96*96 texture 0
03-16 14:31:12.285  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb886ea38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8777f38 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:12.295  3774  3813 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-16 14:31:12.295  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:12.295  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:12.295  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:12.295  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:12.305  2134  4027 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED
,03-16 14:31:12.305  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:12.305  3774  3813 I GFX raster: took 0.528438ms for 96*96 texture 0
03-16 14:31:12.305  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88d0bb0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8777f38 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:12.305  4032  4032 E Zygote  : MountEmulatedStorage(),
03-16 14:31:12.305  4032  4032 E Zygote  : v2
,03-16 14:31:12.305  3774  3813 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
03-16 14:31:12.305  4032  4032 I libpersona: KNOX_SDCARD checking this for 10113
,03-16 14:31:12.305  4032  4032 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:12.315  4032  4032 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:31:12.315  1020  1032 I ActivityManager: Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4032 uid=10113 gids={50113, 9997} abi=armeabi-v7a
03-16 14:31:12.315  4032  4032 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:12.315  4032  4032 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:12.315  1020  1032 I ActivityManager: Killing 3158:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
,03-16 14:31:12.325  2134  4023 I SystemUpdateService: cancelUpdate (empty URL)
,03-16 14:31:12.325  2134  4023 I SystemUpdateService: active receiver: disabled
,03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactShortcut
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activityalias.DialShortcut
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activityalias.MessageShortcut
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 14:31:12.355  3774 , 3813 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 14:31:12.355  3774  3813 I AMMetaDataParserService: Resource data:2131034112
,03-16 14:31:12.365  3774  3813 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_detail
,03-16 14:31:12.365  3774  3813 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 14:31:12.365  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:12.365  3774  3813 I GFX raster: took 0.596094ms for 96*96 texture 0
03-16 14:31:12.365  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b2c768 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8777f38 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:12.385  4032  4032 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:12.385  3774  3813 I AMMetaDataParserService: Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,03-16 14:31:12.385  4032  4032 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:12.405  1843  3991 I GCM     : GCM config loaded
,03-16 14:31:12.445  3143  3176 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,03-16 14:31:12.455  3859  3872 W art     : Suspending all threads took: 22.453ms
,03-16 14:31:12.475  1843  2157 I art     : Explicit concurrent mark sweep GC freed 32384(2039KB) AllocSpace objects, 30(480KB) LOS objects, 40% free, 9MB/15MB, paused 10.457ms total 98.924ms
,03-16 14:31:12.475  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:12.475  3774  3813 I GFX raster: took 0.597135ms for 96*96 texture 0
03-16 14:31:12.475  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b2c768 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8777f38 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:12.485  3774  3813 I AMMetaDataParserService: Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,03-16 14:31:12.495  1020  1396 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:12.505  1020  1396 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:12.505  1020  1396 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:12.515  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:12.515  3774  3813 I GFX raster: took 0.629219ms for 96*96 texture 0
03-16 14:31:12.515  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8777f38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb87c45d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:12.525  4032  4032 I PageBuddyNotiSvc: Intent received : action=android.intent.action.BOOT_COMPLETED
,03-16 14:31:12.535  3774  3813 I AMMetaDataParserService: Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,03-16 14:31:12.545  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:12.545  3774  3813 I GFX raster: took 0.915730ms for 96*96 texture 0
03-16 14:31:12.545  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b2acb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb87c4488 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:12.565  4032  4032 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,03-16 14:31:12.565  1843  4020 I GCoreUlr: WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,03-16 14:31:12.575  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:12.575  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:12.575  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,03-16 14:31:12.575  3774  3813 I AMMetaDataParserService: Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,03-16 14:31:12.585  4032  4032 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,03-16 14:31:12.585  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:12.585  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:12.585  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:12.585  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:12.595  4057  4057 E Zygote  : MountEmulatedStorage()
03-16 14:31:12.595  4057  4057 I libpersona: KNOX_SDCARD checking this for 10121
03-16 14:31:12.595  4057  4057 E Zygote  : v2
03-16 14:31:12.595  4057  4057 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:12.595  4057  4057 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:31:12.605  1020  1141 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4057 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
03-16 14:31:12.605  4057  4057 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:12.605  4057  4057 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:12.615  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3128/cgroup.procs: No such file or directory
03-16 14:31:12.615  1020  1044 W libprocessgroup: failed to open /acct/uid_10146/pid_3158/cgroup.procs: No such file or directory
,03-16 14:31:12.615  1843  4020 I GCoreUlr: Unbound from all location providers
03-16 14:31:12.615  1843  4020 I GCoreUlr: Place inference reporting - stopped
,03-16 14:31:12.625  2134  4027 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 14:31:12.655  4057  4057 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:12.655  4057  4057 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:12.665  1020  1521 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:12.665  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-16 14:31:12.665  1020  1521 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:12.665  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-16 14:31:12.665  1020  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 14:31:12.665  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 14:31:12.665  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 14:31:12.665  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:12.665  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:12.675  1020  1525 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:12.675  1020  1525 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:12.675  1020  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:12.695  1843  1843 I GCoreUlr: DispatchingService.onDestroy()
03-16 14:31:12.695  1843  1843 I GCoreUlr: Stopping handler for UlrDispSvcFast
,03-16 14:31:12.695  1843  1843 I GCoreUlr: Unbound from all location providers
03-16 14:31:12.695  1843  1843 I GCoreUlr: Place inference reporting - stopped
,03-16 14:31:12.715  3455  3477 D PCWCLIENTTRACE_AccountAppFacade2_0: unregister AuthInfo UpdateReceiver v2.0
,03-16 14:31:12.725  4057  4057 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 14:31:12.725  4057  4057 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-16 14:31:12.725  4057  4057 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-16 14:31:12.735  2134  4027 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,03-16 14:31:12.735  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:12.735  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:12.735  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:12.755  2134  2134 D SystemUpdateService: onDestroy
,03-16 14:31:12.765  1020  1519 I ActivityManager: Killing 3178:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
,03-16 14:31:12.775  1020  2741 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.em,ergency.InteractionEmergencyMessageActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity,
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity,
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: Resource data:2131034113
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main,
03-16 14:31:12.795  3774  3813 I AMMetaDataParserService: getResourceTypeNamexml
03-16 14:31:12.795  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:12.795  3774  3813 I GFX raster: took 0.810834ms for 96*96 texture 0
03-16 14:31:12.795  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb886ea38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b2bbc8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:12.815  3774  3813 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-16 14:31:12.825  1843  2155 W GCoreFlp: No location to return for getLastLocation()
,03-16 14:31:12.825  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:12.825  1843  2239 W FusedLocationProvider: location=null
,03-16 14:31:12.825  3774  3813 I GFX raster: took 0.835833ms for 96*96 texture 0
03-16 14:31:12.825  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb886ea38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb88d0bb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:12.835  3774  3813 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-16 14:31:12.845  1843  2155 W GCoreFlp: No location to return for getLastLocation()
,03-16 14:31:12.845  1843  2157 W FusedLocationProvider: location=null
,03-16 14:31:12.855  1843  1843 W Auth    : [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,03-16 14:31:12.855  1020  1759 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:12.855  1020  1759 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:12.855  1020  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:12.875  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:12.875  3774  3813 I GFX raster: took 0.599636ms for 96*96 texture 0
03-16 14:31:12.875  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b2c768 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb87788b8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:12.875  3774  3813 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-16 14:31:12.895  1843  1843 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 14:31:12.895  4057  4057 D QuickConnect: PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,03-16 14:31:12.915  1020  1044 W libprocessgroup: failed to open /acct/uid_10088/pid_3178/cgroup.procs: No such file or directory
,03-16 14:31:12.925  1020  1142 D SettingsProvider: name = scon_is_running
,03-16 14:31:12.925  1020  1142 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 14:31:12.925  1020  1142 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 14:31:12.925  1020  1142 D SettingsProvider: selectionArgs: false
,03-16 14:31:12.925  1020  1142 D SettingsProvider: selectionArgs: 10121
,03-16 14:31:12.925  1020  1142 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 14:31:12.925  1020  1142 D SettingsProvider: ret = -1
,03-16 14:31:12.935  3940  3956 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 14:31:12.945  1020  1142 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,03-16 14:31:12.945  4057  4057 D QuickConnect: Utils.setQCRunningSetting - set : 0
,03-16 14:31:12.945  4057  4057 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,03-16 14:31:12.955  4057  4057 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-16 14:31:12.955  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 14:31:12.955  1020  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:12.955  1020  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:12.955  1020  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:12.955  1020  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:12.965  1020  2741 D SSRM:n  : SIOP:: AP = 420
,03-16 14:31:12.965  4091  4091 E Zygote  : MountEmulatedStorage()
03-16 14:31:12.965  4091  4091 E Zygote  : v2
03-16 14:31:12.965  4091  4091 I libpersona: KNOX_SDCARD checking this for 10127
03-16 14:31:12.965  4091  4091 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:12.975  4091  4091 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:12.975  4091  4091 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-16 14:31:12.975  4091  4091 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:12.975  1020  1525 I ActivityManager: Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4091 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,03-16 14:31:12.985  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:12.995  3774  3813 I GFX raster: took 0.697239ms for 96*96 texture 0
,03-16 14:31:12.995  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b2bbc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88d0bb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:13.005  3774  3813 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-16 14:31:13.025  4091  4091 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:13.025  3940  3956 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-16 14:31:13.025  3940  3956 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 14:31:13.025  3940  3956 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 14:31:13.025  4091  4091 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:13.035  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:13.035  3774  3813 I GFX raster: took 0.998438ms for 96*96 texture 0
03-16 14:31:13.035  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb87788b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88d0bb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:13.045  1020  1521 I art     : Explicit concurrent mark sweep GC freed 32244(1930KB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 22MB/34MB, paused 4.721ms total 219.044ms
,03-16 14:31:13.045  3774  3813 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-16 14:31:13.075  1020  2778 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 14:31:13.075  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:13.075  3774  3813 I GFX raster: took 0.770625ms for 96*96 texture 0
03-16 14:31:13.075  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b2acb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88d0bb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:13.085  3774  3813 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-16 14:31:13.095  4091  4091 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-16 14:31:13.095  4091  4091 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 14:31:13.095  4091  4091 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-16 14:31:13.095  4091  4091 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 14:31:13.095  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:13.095  3774  3813 I GFX raster: took 0.874896ms for 96*96 texture 0
03-16 14:31:13.095  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88d0bb0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b00b70 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:13.105  3959  3959 I Process : Sending signal. PID: 3959 SIG: 9
,03-16 14:31:13.125  2134  4027 I AuthZen : Fetching signing key...
,03-16 14:31:13.125  3774  3813 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-16 14:31:13.125  1843  1843 D PersistentNotificationBroadcastReceiver: Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,03-16 14:31:13.145  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:13.145  3774  3813 I GFX raster: took 0.781355ms for 96*96 texture 0
03-16 14:31:13.145  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b36c78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b102c8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:13.155  3774  3813 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
03-16 14:31:13.165  3774  3813 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-16 14:31:13.165  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
03-16 14:31:13.,165  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,03-16 14:31:13.185  2134  4027 I AuthZen : Signing key fetched successfully!
,03-16 14:31:13.185  1020  1519 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:13.185  1020  1519 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:13.185  1020  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:13.195  2134  4027 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
,03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Welcome
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.DataConnection
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSe,tup
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Debug
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageListXL
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 14:31:13.205  3774  3813 I AMMetaDataParserService: Resource data:2131165203
03-16 14:31:13.205  1020  1519 I ActivityManager: Process com.sec.android.app.sns3 (pid 3959)(adj 0) has died(23,661)
,03-16 14:31:13.215  3774  3813 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-16 14:31:13.215  3774  3813 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 14:31:13.215  3774  3813 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 14:31:13.215  3774  3813 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 14:31:13.215  3774  3813 I AMMetaDataParserService: getResourceName:com.android.email:xml/email_assistant_menu
03-16 14:31:13.215  3774  3813 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 14:31:13.225  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:13.225  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:13.225  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:13.225  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:13.225  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-16 14:31:13.235  2134  4027 D a       : Opening database auth.proximity.permit_store...,
03-16 14:31:13.235  3774  3813 I GFX construct_block_size_descriptor_2d second part: took 3.390261ms for 0*0 texture 0
,03-16 14:31:13.245  2134  4027 D AuthZenTransactionCache: Initialized cache in: /data/data/com.google.android.gms/files,
03-16 14:31:13.245  2134  4027 D AuthZenTransactionCache: Clearing transaction cache
,03-16 14:31:13.245  4111  4111 E Zygote  : MountEmulatedStorage(),
,03-16 14:31:13.245  1020  1045 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4111 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
03-16 14:31:13.245  4111  4111 E Zygote  : v2
03-16 14:31:13.245  4111  4111 I libpersona: KNOX_SDCARD checking this for 10031
03-16 14:31:13.245  4111  4111 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:13.255  4111  4111 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:13.255  4111  4111 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:13.255  4111  4111 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:13.255  3774  3813 I GFX generate_partition_tables: took 17.105726ms for 0*0 texture 0
03-16 14:31:13.255  3774  3813 I GFX raster: took 21.041977ms for 80*80 texture 0
03-16 14:31:13.255  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b14ab8 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b7, Counterpart=0xb8b15778 counterpartCT=4 counterpartW=80 counterparth=80
,03-16 14:31:13.265  3774  3813 I AMMetaDataParserService: Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,03-16 14:31:13.275  4111  4111 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:13.275  4111  4111 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:13.275  3574  3586 W art     : Suspending all threads took: 44.050ms
,03-16 14:31:13.305  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-16 14:31:13.305   290   290 E SMD     : DCD OFF
,03-16 14:31:13.315  3774  3813 I GFX construct_block_size_descriptor_2d second part: took 2.371094ms for 0*0 texture 0
,03-16 14:31:13.315  1020  1352 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:13.315  1020  1352 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:13.315  1020  1352 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:13.325  3774  3813 I GFX generate_partition_tables: took 5.090729ms for 0*0 texture 0
,03-16 14:31:13.325  3774  3813 I GFX raster: took 8.501405ms for 80*80 texture 0
03-16 14:31:13.325  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8e9b118 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8e9b1c0 counterpartCT=4 counterpartW=80 counterparth=80
,03-16 14:31:13.325  3859  3918 I System.out: INFO:Resource not found:/Common.properties Using default values
,03-16 14:31:13.325  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:13.325  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:13.325  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:13.325  1020  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:13.355  1020  1141 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4129 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-16 14:31:13.355  4129  4129 E Zygote  : MountEmulatedStorage(),
03-16 14:31:13.355  4129  4129 E Zygote  : v2
03-16 14:31:13.355  4129  4129 I libpersona: KNOX_SDCARD checking this for 10026,
03-16 14:31:13.355  4129  4129 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:13.355  4129  4129 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-16 14:31:13.365  4129  4129 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 14:31:13.365  4129  4129 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,03-16 14:31:13.375   310   310 I art     : Explicit concurrent mark sweep GC freed 8727(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 30.963ms
,03-16 14:31:13.395  4129  4129 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:13.395  4129  4129 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:13.395   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 590us total 18.774ms
,03-16 14:31:13.405  3774  3813 I AMMetaDataParserService: Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575,
,03-16 14:31:13.425   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.580ms total 21.464ms
,03-16 14:31:13.435  1020  1521 I ActivityManager: Killing 3216:com.policydm/1000 (adj 15): empty #31
,03-16 14:31:13.455  3143  3176 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,03-16 14:31:13.475  1020  1759 I ActivityManager: Killing 3323:com.sec.esdk.elm/u0a90 (adj 15): empty #31
,03-16 14:31:13.475  1020  1759 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,03-16 14:31:13.485  1020  1759 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.policydm/com.policydm.XDMBroadcastReceiver}
03-16 14:31:13.485  1020  1759 W BroadcastQueue: android.os.TransactionTooLargeException
03-16 14:31:13.485  1020  1759 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
03-16 14:31:13.485  1020  1759 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:511)
03-16 14:31:13.485  1020  1759 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
03-16 14:31:13.485  1020  1759 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
03-16 14:31:13.485  1020  1759 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
03-16 14:31:13.485  1020  1759 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20387)
03-16 14:31:13.485  1020  1759 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
03-16 14:31:13.485  1020  1759 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3368)
03-16 14:31:13.485  1020  1759 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:461)
,03-16 14:31:13.485  1020  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:13.485  1020  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:13.485  1020  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:13.485  1020  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:13.495  4145  4145 E Zygote  : MountEmulatedStorage(),
03-16 14:31:13.495  4145  4145 E Zygote  : v2
,03-16 14:31:13.495  4145  4145 I libpersona: KNOX_SDCARD checking this for 1000
,03-16 14:31:13.495  4145  4145 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:13.505  1020  1759 I ActivityManager: Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4145 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 14:31:13.505  4145  4145 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:13.505  4145  4145 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:13.505  4091  4091 D SBrowserFeatureFlag: initialized in static block : loadCscFeatureValue() succeed! 
03-16 14:31:13.515  4145  4145 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:13.535  4145  4145 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:13.545  4145  4145 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:13.565  4091  4091 D ManifestProvider: onCreate()
,03-16 14:31:13.585  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-16 14:31:13.585  3774  3813 I GFX raster: took 0.715208ms for 80*80 texture 0
,03-16 14:31:13.595  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8e9b118 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8b4a1d8 counterpartCT=4 counterpartW=80 counterparth=80
,03-16 14:31:13.605  4091  4091 E NetworkSettingsReceiver: onReceive: android.intent.action.BOOT_COMPLETED
,03-16 14:31:13.605  3774  3813 I AMMetaDataParserService: Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,03-16 14:31:13.635  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-16 14:31:13.645  3774  3813 I GFX raster: took 0.751980ms for 80*80 texture 0
03-16 14:31:13.645  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8e9b118 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8b4a1d8 counterpartCT=4 counterpartW=80 counterparth=80
,03-16 14:31:13.645  3774  3813 I AMMetaDataParserService: Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,03-16 14:31:13.665  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3216/cgroup.procs: No such file or directory
03-16 14:31:13.665  1020  1044 W libprocessgroup: failed to open /acct/uid_10090/pid_3323/cgroup.procs: No such file or directory
,03-16 14:31:13.665  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-16 14:31:13.665  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-16 14:31:13.665  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:13.665  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 14:31:13.665  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 14:31:13.665  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:13.675  4091  4091 W System.err: java.lang.NoSuchMethodException: isEnabled []
,03-16 14:31:13.675  4145  4145 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,03-16 14:31:13.685  4145  4145 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-16 14:31:13.695  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-16 14:31:13.695  3774  3813 I GFX raster: took 0.621146ms for 80*80 texture 0
03-16 14:31:13.695  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b4a1d8 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8b25998 counterpartCT=4 counterpartW=80 counterparth=80
,03-16 14:31:13.695  4091  4091 W System.err: 	at java.lang.Class.getMethod(Class.java:665)
,03-16 14:31:13.695  4091  4091 W System.err: 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
03-16 14:31:13.695  4091  4091 W System.err: 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
03-16 14:31:13.695  4091  4091 W System.err: 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
03-16 14:31:13.695  4091  4091 W System.err: 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
03-16 14:31:13.695  4091  4091 W System.err: 	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
,03-16 14:31:13.695  4091  4091 W System.err: 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
03-16 14:31:13.695  4091  4091 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
03-16 14:31:13.695  4091  4091 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-16 14:31:13.695  4091  4091 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-16 14:31:13.695  4091  4091 W System.err: ,	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 14:31:13.695  4091  4091 W System.err: 	,at android.os.Looper.loop(Looper.java:145)
03-16 14:31:13.695  4091  4091 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-16 14:31:13.695  4091  4091 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 14:31:13.695  4091  4091 W System.err: 	,at java.lang.reflect.Method.invoke(Method.java:372)
03-16 14:31:13.695  4091  4091 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-16 14:31:13.695  4091  4091 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-16 14:31:13.695  3774  3813 I AMMetaDataParserService: Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,03-16 14:31:13.715  4091  4091 E SBrowserFeatureFlag: initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@1e47e637
,03-16 14:31:13.725  4091  4091 D SBrowserFeatureFlag: initialize : initSupportedPkg() succeed! 
,03-16 14:31:13.725  4091  4091 I VerificationLog: SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,03-16 14:31:13.735  4145  4163 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,03-16 14:31:13.735  4145  4163 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,03-16 14:31:13.735  4145  4145 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,03-16 14:31:13.745  4145  4145 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-16 14:31:13.745  4145  4145 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,03-16 14:31:13.755  4145  4163 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,03-16 14:31:13.765  3774  3813 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,03-16 14:31:13.765  3774  3813 I GFX raster: took 0.622865ms for 80*80 texture 0
03-16 14:31:13.765  3774  3813 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b4a1d8 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb8b258f0 counterpartCT=4 counterpartW=80 counterparth=80
,03-16 14:31:13.765  3774  3813 I AMMetaDataParserService: Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,03-16 14:31:13.775  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:13.775  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:13.775  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:13.775  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:13.795  4145  4145 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0],
,03-16 14:31:13.795  4145  4145 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,03-16 14:31:13.795  4145  4145 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache],
,03-16 14:31:13.795  4145  4145 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true],
,03-16 14:31:13.795  1020  1032 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4170 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
,03-16 14:31:13.805  1020  1032 I ActivityManager: Killing 3381:com.fmm.dm/1000 (adj 15): empty #31
03-16 14:31:13.805  4170  4170 E Zygote  : MountEmulatedStorage()
03-16 14:31:13.805  4170  4170 E Zygote  : v2
03-16 14:31:13.805  4170  4170 I libpersona: KNOX_SDCARD checking this for 10131
03-16 14:31:13.805  4170  4170 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:13.805  4145  4145 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
03-16 14:31:13.805  4170  4170 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:31:13.805  4145  4145 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
03-16 14:31:13.805  4145  4145 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
03-16 14:31:13.805  4170  4170 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:13.805  4170  4170 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:13.835  4145  4145 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !,
,03-16 14:31:13.845  4145  4145 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED,
,03-16 14:31:13.845  4170  4170 D TimaKeyStoreProvider: TimaSignature is unavailable,
,03-16 14:31:13.845  4170  4170 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:13.865  4145  4145 I DBG_POLICYDM: [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,03-16 14:31:13.865  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:13.865  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:13.865  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:13.865  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:13.865  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
03-16 14:31:13.865  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
,03-16 14:31:13.875  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
03-16 14:31:13.875  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
03-16 14:31:13.875  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
03-16 14:31:13.875  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageCompose
03-16 14:31:13.875  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:13.875  3774  3813 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-16 14:31:13.875  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
03-16 14:31:13.875  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
03-16 14:31:13.875  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
03-16 14:31:13.875  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
03-16 14:31:13.875  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
03-16 14:31:13.875  3774  3813 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-16 14:31:13.875  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.DebugActivity
03-16 14:31:13.875  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
03-16 14:31:13.875  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
03-16 14:31:13.875  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
03-16 14:31:13.875  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SearchActivity
03-16 14:31:13.875  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:13.875  3774  3813 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 14:31:13.875  3774  3813 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-16 14:31:13.875  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
03-16 14:31:13.875  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
03-16 14:31:13.875  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,03-16 14:31:13.875  4170  4170 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 14:31:13.875  4170  4170 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 14:31:13.875  4170  4170 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 14:31:13.885  4185  4185 E Zygote  : MountEmulatedStorage()
,03-16 14:31:13.885  4185  4185 E Zygote  : v2
03-16 14:31:13.885  4185  4185 I libpersona: KNOX_SDCARD checking this for 10032
03-16 14:31:13.885  4185  4185 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:13.885  4185  4185 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-16 14:31:13.885  1020  1491 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4185 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 14:31:13.895  4185  4185 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:13.895  4185  4185 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-16 14:31:13.915  3859  3872 W art     : Suspending all threads took: 24.280ms
,03-16 14:31:13.935  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3381/cgroup.procs: No such file or directory
,03-16 14:31:13.935  4185  4185 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:13.935  4185  4185 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:13.965  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
03-16 14:31:13.965  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
03-16 14:31:13.965  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
03-16 14:31:13.965  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
03-16 14:31:13.965  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
03-16 14:31:13.965  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:13.965  3774  3813 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-16 14:31:13.965  3774  3813 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-16 14:31:13.965  3774  3813 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 14:31:13.965  3774  3813 I AMMetaDataParserService: Resource data:2131099648
,03-16 14:31:13.965  4145  4163 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-16 14:31:13.965  4145  4163 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-16 14:31:13.975  3774  3813 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,03-16 14:31:13.975  3774  3813 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 14:31:13.975  3774  3813 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 14:31:13.975  3774  3813 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 14:31:13.975  3774  3813 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
03-16 14:31:13.975  4145  4163 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,03-16 14:31:13.975  4145  4163 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
03-16 14:31:13.975  3774  3813 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
,03-16 14:31:13.975  3774  3813 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 14:31:13.975  4145  4163 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,03-16 14:31:13.995  4145  4163 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,03-16 14:31:14.005  1818  2069 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-16 14:31:14.055  3774  3813 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-16 14:31:14.065  4145  4163 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-16 14:31:14.075  4145  4163 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-16 14:31:14.075  4145  4163 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
03-16 14:31:14.075  4145  4164 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-16 14:31:14.085  4145  4164 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-16 14:31:14.085  1020  1519 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:14.085  1020  1519 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:14.085  1020  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-16 14:31:14.095  3774  3813 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-16 14:31:14.095  4145  4164 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-16 14:31:14.095  4145  4163 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,03-16 14:31:14.105  4145  4164 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-16 14:31:14.105  4145  4164 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-16 14:31:14.105  4145  4163 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/20/16:34:31
,03-16 14:31:14.105  4145  4164 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-16 14:31:14.105  4145  4163 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/16/14:31:14
,03-16 14:31:14.105  4145  4164 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-16 14:31:14.115  4145  4163 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..,
,03-16 14:31:14.115  1020  1100 V AlarmManager: waitForAlarm result :8
03-16 14:31:14.115  4145  4164 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
03-16 14:31:14.115  4145  4163 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,03-16 14:31:14.115  4145  4164 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
03-16 14:31:14.115  4145  4164 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-16 14:31:14.135  3774  3813 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-16 14:31:14.145  4145  4163 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,03-16 14:31:14.155  4145  4164 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-16 14:31:14.165  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-16 14:31:14.165  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-16 14:31:14.165  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:14.165  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-16 14:31:14.175  1020  1033 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4211 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 14:31:14.185  1020  1142 W ActivityManager: userId = 0, bbcId = -10000,
03-16 14:31:14.185  1020  1142 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:14.185  1020  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-16 14:31:14.185  4211  4211 E Zygote  : MountEmulatedStorage()
03-16 14:31:14.185  4211  4211 E Zygote  : v2,
03-16 14:31:14.185  4211  4211 I libpersona: KNOX_SDCARD checking this for 10037
03-16 14:31:14.185  4211  4211 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:14.185  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-16 14:31:14.185  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:14.185  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-16 14:31:14.185  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-16 14:31:14.195  4211  4211 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:14.195  4211  4211 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:14.195  4145  4164 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,03-16 14:31:14.205  4211  4211 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-16 14:31:14.215  4220  4220 E Zygote  : MountEmulatedStorage(),
03-16 14:31:14.215  4220  4220 E Zygote  : v2
,03-16 14:31:14.215  4220  4220 I libpersona: KNOX_SDCARD checking this for 10135
03-16 14:31:14.215  4220  4220 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:14.225  4220  4220 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-16 14:31:14.225  1020  1527 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4220 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,03-16 14:31:14.225  4220  4220 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 14:31:14.225  4220  4220 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:14.265  4220  4220 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:14.265  4211  4211 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:14.265  4220  4220 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:14.265  4211  4211 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:14.265  3774  3813 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-16 14:31:14.275  3751  3764 I art     : WaitForGcToComplete blocked for 11.442ms for cause HomogeneousSpaceCompact
,03-16 14:31:14.295  4129  4129 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-16 14:31:14.305  4220  4220 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,03-16 14:31:14.305  4220  4220 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 14:31:14.305  4220  4220 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-16 14:31:14.305  4220  4220 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,03-16 14:31:14.305  4220  4220 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 14:31:14.305  4211  4211 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-16 14:31:14.315  4145  4163 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,03-16 14:31:14.315  3774  3813 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-16 14:31:14.325  4145  4163 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-16 14:31:14.365  1020  1045 I ActivityManager: Waited long enough for: ServiceRecord{51be233 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,03-16 14:31:14.395  3774  3813 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-16 14:31:14.415  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
03-16 14:31:14.415  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
03-16 14:31:14.415  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:14.415  3774  3813 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 14:31:14.415  3774  3813 I AMMetaDataParserService: Resource data:2131099648
,03-16 14:31:14.415  3774  3813 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging,
03-16 14:31:14.415  3774  3813 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 14:31:14.415  4185  4248 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,03-16 14:31:14.415  4185  4248 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,03-16 14:31:14.425  4185  4185 E SPPClientService: [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,03-16 14:31:14.425  1020  1519 I ActivityManager: Killing 3396:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
,03-16 14:31:14.435  3774  3813 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-16 14:31:14.465  3143  3176 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,03-16 14:31:14.465  4185  4248 D SPPClientService: PushLog.txt file is not deleted.
,03-16 14:31:14.465  4211  4211 I CalendarProvider2: CalendarProvider2.onCreate() called
,03-16 14:31:14.465  4185  4248 D SPPClientService: PushLog.txt file is not deleted.
,03-16 14:31:14.465  4185  4248 D SPPClientService: ============PushLog. stop!
,03-16 14:31:14.475  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:14.475  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:14.475  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:14.475  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:14.495  4254  4254 E Zygote  : MountEmulatedStorage()
03-16 14:31:14.495  4254  4254 E Zygote  : v2
03-16 14:31:14.495  4254  4254 I libpersona: KNOX_SDCARD checking this for 10141
03-16 14:31:14.495  4254  4254 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:14.495  4254  4254 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:14.505  4254  4254 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:14.505  4254  4254 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:14.505  1020  1142 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4254 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,03-16 14:31:14.515  4145  4164 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,03-16 14:31:14.525  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:14.525  1020  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:14.525  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-16 14:31:14.545  3556  3793 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-16 14:31:14.545  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:14.545  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:14.545  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:14.545  1020  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:14.545  3774  3813 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519,
,03-16 14:31:14.555  1020  1142 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4271 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-16 14:31:14.565  1020  1142 I ActivityManager: Killing 3411:com.sec.factory.camera/1000 (adj 15): empty #31
03-16 14:31:14.565  1020  1044 W libprocessgroup: failed to open /acct/uid_10055/pid_3396/cgroup.procs: No such file or directory,
,03-16 14:31:14.565  3774  3813 I art     : WaitForGcToComplete blocked for 20.450ms for cause DisableMovingGc
,03-16 14:31:14.575  4271  4271 E Zygote  : MountEmulatedStorage()
03-16 14:31:14.575  4271  4271 E Zygote  : v2
03-16 14:31:14.575  4271  4271 I libpersona: KNOX_SDCARD checking this for 10036
03-16 14:31:14.575  4271  4271 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:14.575  4271  4271 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:14.575  4254  4254 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:14.575  4271  4271 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:14.575  4254  4254 D ActivityThread: Added TimaKeyStore provider,
03-16 14:31:14.575  4271  4271 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-16 14:31:14.595  4271  4271 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:14.595  4271  4271 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:14.595  2134  3957 I Icing   : updateResources: need to parse f{com.google.android.gms}
,03-16 14:31:14.615  4145  4164 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-16 14:31:14.625  4254  4254 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-16 14:31:14.625  4254  4254 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 14:31:14.625  4254  4254 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 14:31:14.625  4254  4254 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 14:31:14.635  4145  4164 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,03-16 14:31:14.635  3774  3813 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-16 14:31:14.665  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-16 14:31:14.665  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,03-16 14:31:14.665  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 14:31:14.665  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 14:31:14.665  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:14.665  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:14.675  3774  3813 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-16 14:31:14.705  3774  3813 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-16 14:31:14.735  3774  3813 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-16 14:31:14.735  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity,
,03-16 14:31:14.735  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
03-16 14:31:14.735  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
03-16 14:31:14.735  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
03-16 14:31:14.735  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-16 14:31:14.735  3774  3813 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 14:31:14.735  3774  3813 I AMMetaDataParserService: Resource data:2131099648
03-16 14:31:14.745  3774  3813 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-16 14:31:14.745  3774  3813 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 14:31:14.745  3774  3813 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-16 14:31:14.765  4129  4129 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,03-16 14:31:14.795  4271  4271 I SA      : [SSP] onCreated
,03-16 14:31:14.795  1020  1491 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:14.805  1020  1352 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:14.815  4129  4129 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 14:31:14.815  4129  4129 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 14:31:14.825  1020  1396 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:14.825  1020  1491 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:14.825  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3411/cgroup.procs: No such file or directory
,03-16 14:31:14.845  4271  4271 I SA      : [TPM] There is no property file
,03-16 14:31:14.855  4271  4271 I SA      : [SCU] isHaveSA() - false
,03-16 14:31:14.855  4271  4271 I SA      : [TPM] getModelProperty : null
,03-16 14:31:14.855  4271  4271 I SA      : [TPM] getCSCProperty : null
,03-16 14:31:14.855  4271  4271 I SA      : [DM] FLOATING AMOLED FEATURE: true
03-16 14:31:14.855  4271  4271 I SA      : [DM] PRODUCT AMOLED FEATURE: false
03-16 14:31:14.855  4271  4271 I SA      : [DM] TFT FEATURE: false
,03-16 14:31:14.865  4271  4271 I SA      : [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
03-16 14:31:14.865  4271  4271 I SA      : [DM] init START
,03-16 14:31:14.875  4271  4271 I SA      : [DM] This device is not a Vodafone
,03-16 14:31:14.895  4271  4271 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,03-16 14:31:14.895  4271  4271 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
03-16 14:31:14.895  4271  4271 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,03-16 14:31:14.895  4271  4271 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,03-16 14:31:14.895  4271  4271 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,03-16 14:31:14.905  4271  4271 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,03-16 14:31:14.905  4271  4271 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,03-16 14:31:14.905  4271  4271 W ResourceType: No package identifier when getting value for resource number 0x00000000
,03-16 14:31:14.905  4271  4271 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,03-16 14:31:14.905  4271  4271 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,03-16 14:31:14.905  4271  4271 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,03-16 14:31:14.905  4271  4271 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,03-16 14:31:14.905  4271  4271 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
03-16 14:31:14.905  4271  4271 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,03-16 14:31:14.905  4271  4271 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,03-16 14:31:14.905  4271  4271 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,03-16 14:31:14.915  4129  4244 D Volley  : [616] DiskBasedCache.clear: Cache cleared.
,03-16 14:31:14.925  1020  1527 I ActivityManager: Killing 3444:com.samsung.android.scloud.backup/u0a56 (adj 15): empty #31
,03-16 14:31:14.925  1020  1527 I ActivityManager: Killing 3429:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #32
,03-16 14:31:14.925  4129  4289 D Volley  : [623] DiskBasedCache.clear: Cache cleared.
,03-16 14:31:14.935  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:14.935  1020  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:14.935  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-16 14:31:14.935  1020  1520 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:14.935  4271  4271 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,03-16 14:31:14.935  4271  4271 W ResourceType: Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
,03-16 14:31:14.935  4271  4271 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,03-16 14:31:14.935  4271  4271 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,03-16 14:31:14.945  1020  1521 D RCPManagerService: exchangeData() failure , invalid userId
03-16 14:31:14.945  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:14.945  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:14.945  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:14.945  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:14.955  4271  4271 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
03-16 14:31:14.955  4271  4271 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
03-16 14:31:14.955  4271  4271 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
03-16 14:31:14.955  4271  4271 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
03-16 14:31:14.955  4271  4271 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
03-16 14:31:14.955  4271  4271 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
03-16 14:31:14.955  4129  4307 D Ads     : Skipping gmscore version check
03-16 14:31:14.965  4310  4310 E Zygote  : MountEmulatedStorage()
03-16 14:31:14.965  4310  4310 E Zygote  : v2
03-16 14:31:14.965  4310  4310 I libpersona: KNOX_SDCARD checking this for 10068
03-16 14:31:14.965  4310  4310 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:14.965  4310  4310 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:31:14.965  1020  1527 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4310 uid=10068 gids={50068, 9997} abi=armeabi-v7a
03-16 14:31:14.965  4310  4310 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:14.965  4310  4310 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-16 14:31:14.965  4271  4271 I SA      : [SCU] isHaveSA() - false
03-16 14:31:14.965  4271  4271 I SA      : support phone number id : false
03-16 14:31:14.965  4271  4271 I SA      : [DM] Supports Ref Jpn : true
03-16 14:31:14.965  4271  4271 I SA      : [DM] init END
,03-16 14:31:14.985  4271  4271 I SA      : [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
03-16 14:31:14.985  4271  4271 I SA      : [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,03-16 14:31:14.985  3859  3872 W art     : Suspending all threads took: 24.143ms
,03-16 14:31:14.985  1020  1142 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:14.985  1020  1142 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
,03-16 14:31:14.995  1020  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,03-16 14:31:14.995  4310  4310 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:14.995  4271  4271 I SA      : [OR] onReceive END
03-16 14:31:14.995  4310  4310 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:15.015  4271  4271 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-16 14:31:15.015  4271  4271 I SA      : [ODM] queryOpenData(key= GEO_IP )
,03-16 14:31:15.015  4254  4300 W art     : Verification of boolean com.android.email.activity.MessageListItemOuterContainer.onTouchEvent(android.view.MotionEvent) took 165.856ms
,03-16 14:31:15.025  4271  4271 I SA      : getMccForGalaxyJpn step2 GEO_IP MCC : 260
03-16 14:31:15.025  4271  4271 I SA      : [LBE] REF_JPN : true
03-16 14:31:15.025  4271  4271 I SA      : [BDC] create
,03-16 14:31:15.045  1020  1759 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:15.045  1020  1759 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:15.045  1020  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-16 14:31:15.055  1020  1044 W libprocessgroup: failed to open /acct/uid_10095/pid_3429/cgroup.procs: No such file or directory
,03-16 14:31:15.055  1020  1044 W libprocessgroup: failed to open /acct/uid_10056/pid_3444/cgroup.procs: No such file or directory
,03-16 14:31:15.055  4310  4310 D BadgeProvider: onCreate
03-16 14:31:15.055  4310  4310 D BadgeProvider: DatabaseHelper
,03-16 14:31:15.065  4271  4271 I SA      : [DBMV2] getEmailID
,03-16 14:31:15.065  4271  4271 I SA      : [DBMV2] getDataV02ForItems
03-16 14:31:15.065  4271  4271 I SA      : [SSP] query invoked
,03-16 14:31:15.065  4129  4129 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-16 14:31:15.065  4129  4129 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,03-16 14:31:15.075  1020  1519 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:15.075  1020  1519 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:15.075  1020  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,03-16 14:31:15.085  3774  3813 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-16 14:31:15.085  4271  4271 I SA      : [SCU] get signed id from samsung account2.0 DB.
,03-16 14:31:15.095  4271  4271 I SA      : [SCU] get signed id from samsung account1.0 DB.
,03-16 14:31:15.095  4310  4324 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-16 14:31:15.095  4271  4271 I SA      : [BDC] destroy
,03-16 14:31:15.115  3774  3813 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-16 14:31:15.125  3774  3813 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-16 14:31:15.135  3774  3813 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-16 14:31:15.145  1020  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:15.145  1020  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:15.145  1020  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:15.145  1020  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:15.155  4333  4333 E Zygote  : MountEmulatedStorage()
03-16 14:31:15.155  4333  4333 E Zygote  : v2
03-16 14:31:15.155  4333  4333 I libpersona: KNOX_SDCARD checking this for 10142
03-16 14:31:15.155  4333  4333 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:15.155  4333  4333 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:15.165  4333  4333 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:15.165  4333  4333 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-16 14:31:15.165  1020  1521 I ActivityManager: Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4333 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,03-16 14:31:15.165  3774  3813 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-16 14:31:15.175  1020  1521 I ActivityManager: Killing 3512:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
,03-16 14:31:15.175  1020  1521 I ActivityManager: Killing 3493:com.fmm.ds/1000 (adj 15): empty #32
,03-16 14:31:15.185  1020  1352 I ActivityManager: Killing 3530:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
,03-16 14:31:15.195  4333  4333 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:15.195  4333  4333 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:15.225  4333  4333 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-16 14:31:15.235  4310  4324 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,03-16 14:31:15.235  4310  4324 D BadgeProvider: sendNotify, [notify] : null
03-16 14:31:15.235  4310  4324 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
,03-16 14:31:15.235  4310  4324 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-16 14:31:15.235  4310  4324 D BadgeProvider: update, [UpdateCount] : 1
,03-16 14:31:15.235  1020  1525 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:15.235  1020  1525 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:15.235  1020  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-16 14:31:15.305  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
03-16 14:31:15.305  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:15.305  3774  3813 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 14:31:15.305  3774  3813 I AMMetaDataParserService: Resource data:2131099648
,03-16 14:31:15.305  3774  3813 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-16 14:31:15.305  3774  3813 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 14:31:15.315  3774  3813 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-16 14:31:15.315  4129  4129 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-16 14:31:15.315  1020  1044 W libprocessgroup: failed to open /acct/uid_10098/pid_3530/cgroup.procs: No such file or directory
03-16 14:31:15.315  1020  1044 W libprocessgroup: failed to open /acct/uid_10058/pid_3512/cgroup.procs: No such file or directory
03-16 14:31:15.325  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3493/cgroup.procs: No such file or directory
,03-16 14:31:15.325  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:15.325  1020  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:15.325  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-16 14:31:15.335  3774  3813 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-16 14:31:15.345  1480  1480 D Launcher.Model: reloadBadges entered.
,03-16 14:31:15.345  3859  3871 W art     : Suspending all threads took: 7.385ms
,03-16 14:31:15.355  3774  3813 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-16 14:31:15.365  1020  1521 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:15.375  4129  4129 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-16 14:31:15.395  1020  1519 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-16 14:31:15.395  3774  3813 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-16 14:31:15.405  1020  1525 W ActivityManager: getTasks: caller 10141 does not hold GET_TASKS; limiting output
,03-16 14:31:15.415  1020  1141 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:15.415  1020  1141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:15.415  1020  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,03-16 14:31:15.425  1020  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:15.425  1020  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:15.425  1020  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:15.425  1020  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:15.445  4354  4354 E Zygote  : MountEmulatedStorage(),
03-16 14:31:15.445  4354  4354 E Zygote  : v2
03-16 14:31:15.445  4354  4354 I libpersona: KNOX_SDCARD checking this for 1000,
03-16 14:31:15.445  4354  4354 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:15.445  4354  4354 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-16 14:31:15.455  4354  4354 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-16 14:31:15.455  1020  1520 I ActivityManager: Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4354 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 14:31:15.455  4254  4328 I Process : Sending signal. PID: 4254 SIG: 9,
,03-16 14:31:15.465  4354  4354 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:15.465  3774  3813 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-16 14:31:15.475  3143  3176 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec,
,03-16 14:31:15.485  4354  4354 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:15.485  4354  4354 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:15.495  1020  1033 I ActivityManager: Process com.android.email (pid 4254)(adj 11) has died(36,621)
,03-16 14:31:15.515  3774  3813 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-16 14:31:15.525  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
,03-16 14:31:15.525  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:15.525  3774  3813 I AMMetaDataParserService: getResourcePackageName:assistant
,03-16 14:31:15.525  3774  3813 I AMMetaDataParserService: Resource data:2131099648
,03-16 14:31:15.525  3774  3813 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
,03-16 14:31:15.525  3774  3813 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 14:31:15.535  3774  3813 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-16 14:31:15.545  3774  3813 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-16 14:31:15.565  3774  3813 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-16 14:31:15.575  1020  1491 I ActivityManager: Killing 3574:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,03-16 14:31:15.575  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:15.585  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:15.585  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:15.585  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:15.595  4372  4372 E Zygote  : MountEmulatedStorage()
03-16 14:31:15.595  4372  4372 E Zygote  : v2
03-16 14:31:15.595  4372  4372 I libpersona: KNOX_SDCARD checking this for 10141
03-16 14:31:15.595  4372  4372 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:15.595  4372  4372 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:15.595  4372  4372 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 14:31:15.595  4372  4372 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:15.605  1020  1032 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4372 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,03-16 14:31:15.605  1020  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:15.605  1020  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:15.605  1020  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:15.605  1020  1520 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:15.605  3774  3813 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-16 14:31:15.625   310   310 I art     : Explicit concurrent mark sweep GC freed 8700(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.689ms total 23.788ms
,03-16 14:31:15.625  4372  4372 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:15.635  4372  4372 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:15.645   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 18.118ms
,03-16 14:31:15.655  3774  3813 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-16 14:31:15.665   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 17.735ms
,03-16 14:31:15.675  4387  4387 E Zygote  : MountEmulatedStorage()
03-16 14:31:15.675  4387  4387 E Zygote  : v2
03-16 14:31:15.675  4387  4387 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:15.675  3774  3813 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
03-16 14:31:15.675  4387  4387 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:15.675  4387  4387 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:15.685  1020  1520 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4387 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 14:31:15.685  1020  1520 I ActivityManager: Killing 3260:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
,03-16 14:31:15.685  4387  4387 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:15.685  4387  4387 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:15.695  1020  1142 I ActivityManager: Killing 3618:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #31
,03-16 14:31:15.695  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationList
03-16 14:31:15.695  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:15.695  3774  3813 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 14:31:15.695  3774  3813 I AMMetaDataParserService: Resource data:2131099648
,03-16 14:31:15.695  3774  3813 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-16 14:31:15.695  3774  3813 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 14:31:15.705  3774  3813 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-16 14:31:15.715  4387  4387 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:15.715  4387  4387 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:15.715  4372  4372 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-16 14:31:15.715  4372  4372 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 14:31:15.715  4372  4372 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 14:31:15.715  4372  4372 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 14:31:15.725  3774  3813 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-16 14:31:15.745  3774  3813 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-16 14:31:15.765  3774  3813 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-16 14:31:15.785  3774  3813 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-16 14:31:15.805  1020  1042 D SensorService: [SO] -0.460 0.192 9.883
,03-16 14:31:15.805  3774  3813 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
03-16 14:31:15.815  3774  3813 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.se,rviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages,
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
,03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
,03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
,03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity,
,03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
,03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable,
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
,03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
,03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
,03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
,03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
,03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
03-16 14:31:15.815  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
,03-16 14:31:15.835  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
03-16 14:31:15.835  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:15.835  3774  3813 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 14:31:15.835  3774  3813 I AMMetaDataParserService: Resource data:2131165197
,03-16 14:31:15.835  4387  4387 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,03-16 14:31:15.835  4387  4387 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-16 14:31:15.835  4387  4387 D SecurityLogAgent: StateMachine : Current State = 1
03-16 14:31:15.835  4387  4387 D SecurityLogAgent: BootReceiver : completed task. Failed to return wakelock . 
,03-16 14:31:15.835  1020  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:15.835  1020  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:15.835  1020  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:15.835  1020  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:15.845  4403  4403 E Zygote  : MountEmulatedStorage()
03-16 14:31:15.845  4403  4403 E Zygote  : v2
03-16 14:31:15.845  4403  4403 I libpersona: KNOX_SDCARD checking this for 10148
,03-16 14:31:15.855  4403  4403 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:15.855  3774  3813 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 14:31:15.855  3774  3813 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
03-16 14:31:15.855  3774  3813 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 14:31:15.855  3774  3813 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-16 14:31:15.855  3774  3813 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-16 14:31:15.855  3774  3813 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-16 14:31:15.855  3774  3813 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-16 14:31:15.855  3774  3813 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-16 14:31:15.855  3774  3813 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 14:31:15.855  4403  4403 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-16 14:31:15.855  1020  1521 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4403 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
03-16 14:31:15.855  1020  1521 I ActivityManager: Killing 3602:com.wssnps/1000 (adj 15): empty #31
,03-16 14:31:15.865  1020  1141 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:15.875  4403  4403 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:15.875  4403  4403 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:15.885  1020  1519 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:15.895  4403  4403 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:15.895  4403  4403 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:15.915  1020  1044 E libprocessgroup: failed to kill 1 processes for processgroup 3260
03-16 14:31:15.915  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3574/cgroup.procs: No such file or directory
03-16 14:31:15.915  1020  1044 W libprocessgroup: failed to open /acct/uid_10013/pid_3618/cgroup.procs: No such file or directory
,03-16 14:31:15.925  3774  3813 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-16 14:31:15.925  1020  1525 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-16 14:31:15.925  1020  1525 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4302, temperature: 256, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-16 14:31:15.925  1020  1525 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-16 14:31:15.925  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-16 14:31:15.925  1020  1020 I MotionRecognitionService: Plugged
03-16 14:31:15.925  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,03-16 14:31:15.925  1181  1181 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-16 14:31:15.935  1181  1181 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-16 14:31:15.935  1420  1420 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-16 14:31:15.935  1420  1420 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-16 14:31:15.945  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 14:31:15.945  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 14:31:15.945  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-16 14:31:15.955  1181  1181 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-16 14:31:15.955  1181  1181 D SViewCoverView: level :100 plugged : 2
,03-16 14:31:15.955  2620  2620 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-16 14:31:15.955  2620  2715 D HeadsetStateMachine: Disconnected process message: 10
,03-16 14:31:15.955  3774  3813 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-16 14:31:15.965  4403  4403 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,03-16 14:31:15.995  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:15.995  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 14:31:15.995  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,03-16 14:31:15.995  1020  1520 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:16.015  3774  3813 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-16 14:31:16.025  3774  3813 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-16 14:31:16.045  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
03-16 14:31:16.045  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.045  3774  3813 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 14:31:16.045  3774  3813 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 14:31:16.045  3774  3813 I AMMetaDataParserService: Resource data:2131165197
,03-16 14:31:16.045  3774  3813 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
,03-16 14:31:16.045  3774  3813 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 14:31:16.045  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3602/cgroup.procs: No such file or directory
,03-16 14:31:16.065  3774  3813 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-16 14:31:16.075  3774  3813 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-16 14:31:16.105  3774  3813 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-16 14:31:16.115  3774  3813 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-16 14:31:16.115  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.cooliris.media.Gallery
,03-16 14:31:16.115  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
03-16 14:31:16.115  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 14:31:16.125  3774  3813 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 14:31:16.125  3774  3813 I AMMetaDataParserService: Resource data:2131165197
,03-16 14:31:16.125  3774  3813 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
,03-16 14:31:16.125  3774  3813 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 14:31:16.145  3774  3813 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-16 14:31:16.155  3774  3813 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-16 14:31:16.155  1020  1520 I art     : Explicit concurrent mark sweep GC freed 27896(1520KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 22MB/33MB, paused 4.063ms total 154.544ms
,03-16 14:31:16.165  1020  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:16.165  1020  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:16.165  1020  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:16.165  1020  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:16.175  4429  4429 E Zygote  : MountEmulatedStorage()
03-16 14:31:16.175  4429  4429 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:16.175  4429  4429 E Zygote  : v2
03-16 14:31:16.175  4429  4429 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:16.185  4429  4429 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:16.185  4429  4429 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 14:31:16.185  4429  4429 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:16.185  1020  1525 I ActivityManager: Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4429 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,03-16 14:31:16.195  1020  1141 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:16.195  4310  4325 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-16 14:31:16.205  3774  3813 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-16 14:31:16.215  4310  4319 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-16 14:31:16.215  4310  4319 D BadgeProvider: sendNotify, [notify] : null
03-16 14:31:16.215  4310  4319 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-16 14:31:16.215  4310  4319 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-16 14:31:16.215  4310  4319 D BadgeProvider: update, [UpdateCount] : 1
,03-16 14:31:16.225  3774  3813 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-16 14:31:16.225  1020  1521 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:16.225  4429  4429 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:16.225  4429  4429 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:16.235  1020  1491 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:16.245  1020  1527 W ActivityManager: getTasks: caller 10142 does not hold GET_TASKS; limiting output
,03-16 14:31:16.255  4211  4211 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-16 14:31:16.255  1480  1480 D Launcher.Model: reloadBadges entered.
,03-16 14:31:16.255  1020  1519 I ActivityManager: Killing 3650:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
03-16 14:31:16.255  3774  3813 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running acti,vitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
03-16 14:31:16.255  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,03-16 14:31:16.265  1020  1141 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:16.265  1020  1141 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:16.265  1020  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-16 14:31:16.275  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camera
03-16 14:31:16.275  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.275  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
03-16 14:31:16.275  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-16 14:31:16.275  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.keyguard.layout
03-16 14:31:16.275  3774  3813 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 14:31:16.275  3774  3813 I AMMetaDataParserService: Resource data:2131099648
,03-16 14:31:16.275  4333  4370 I Process : Sending signal. PID: 4333 SIG: 9
,03-16 14:31:16.275  1020  1525 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-16 14:31:16.275  3774  3813 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,03-16 14:31:16.285  3774  3813 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 14:31:16.285  3774  3813 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-16 14:31:16.285  3774  3813 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-16 14:31:16.285  3774  3813 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 14:31:16.285  3774  3813 I AMMetaDataParserService: getResourceName:com.sec.android.app.camera:xml/assistant
03-16 14:31:16.285  3774  3813 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 14:31:16.285  1020  1045 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:16.285  1020  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:16.285  1020  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:16.295  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:16.295  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:16.295  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:16.295  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:16.295  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:16.295  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:16.305  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:16.305  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 14:31:16.305  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:16.305  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:16.305  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:16.305  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:16.315   290   290 E SMD     : DCD OFF,
,03-16 14:31:16.315  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:16.315  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:16.315  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:16.325  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:16.325  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:16.325  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.daemonapp
,03-16 14:31:16.335  1818  1818 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-16 14:31:16.335  1818  1818 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-16 14:31:16.335  1818  1818 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-16 14:31:16.345  1020  1759 I ActivityManager: Killing 3268:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,03-16 14:31:16.345  1818  1818 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-16 14:31:16.345  3774  3813 I AMMetaDataParserService: Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,03-16 14:31:16.345  1818  1818 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-16 14:31:16.355  1020  1352 I ActivityManager: Killing 3707:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,03-16 14:31:16.355  1818  1818 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,03-16 14:31:16.355  1818  1818 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,03-16 14:31:16.355  1818  1818 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,03-16 14:31:16.355  1818  1818 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-16 14:31:16.355  1818  1818 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,03-16 14:31:16.365  1818  1818 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,03-16 14:31:16.365  3774  3813 I AMMetaDataParserService: Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,03-16 14:31:16.365  1818  1818 D daemonapp: [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:widgetappapheroaccuweather, cp:Accuweather, aRS:false
,03-16 14:31:16.365  1818  1818 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-16 14:31:16.375  1818  1818 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-16 14:31:16.375  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
03-16 14:31:16.375  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
03-16 14:31:16.375  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
03-16 14:31:16.375  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
03-16 14:31:16.375  3774  3813 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,03-16 14:31:16.425  1818  1818 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-16 14:31:16.425  1818  1818 D daemonapp: [MSC_Daemon]>>> WDSM:140 [0:0] Widget flag autoRefreshSet :  false
,03-16 14:31:16.435  1020  1520 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:16.435  1020  1520 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:16.435  1020  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:16.445  3455  3455 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-16 14:31:16.445  3455  3455 I PCWCLIENTTRACE_PushUtil: sales region : global
03-16 14:31:16.445  3455  3455 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-16 14:31:16.445  3455  3455 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,03-16 14:31:16.445  1020  1759 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=15, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
03-16 14:31:16.445  1020  1759 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,03-16 14:31:16.445  1020  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:16.445  1020  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:16.445  1020  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:16.445  1020  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:16.465  4449  4449 E Zygote  : MountEmulatedStorage()
03-16 14:31:16.465  4449  4449 E Zygote  : v2
03-16 14:31:16.465  4449  4449 I libpersona: KNOX_SDCARD checking this for 10108
03-16 14:31:16.465  4449  4449 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:16.475  4449  4449 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-16 14:31:16.475  4449  4449 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:16.475  4449  4449 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 14:31:16.475   256   256 E lowmemorykiller: Error opening /proc/4333/oom_score_adj; errno=2
03-16 14:31:16.475  1020  1759 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4449 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 14:31:16.485  1020  1519 I ActivityManager: Process com.android.exchange (pid 4333)(adj 15) has died(42,625)
,03-16 14:31:16.495  1761  1761 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-16 14:31:16.505  1818  1826 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,03-16 14:31:16.505  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GridSettings
03-16 14:31:16.505  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.505  3774  3813 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 14:31:16.505  3774  3813 I AMMetaDataParserService: Resource data:2131165220
,03-16 14:31:16.515  1761  1761 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,03-16 14:31:16.515  1761  1761 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
03-16 14:31:16.515  1761  1761 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
03-16 14:31:16.515  1761  1761 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,03-16 14:31:16.515  1020  1044 E libprocessgroup: failed to kill 1 processes for processgroup 3650
,03-16 14:31:16.515  3774  3813 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-16 14:31:16.515  3774  3813 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-16 14:31:16.515  3774  3813 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 14:31:16.515  3774  3813 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 14:31:16.515  3774  3813 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 14:31:16.515  3774  3813 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-16 14:31:16.515  3774  3813 I AMMetaDataParserService: getResourceName:com.android.settings:xml/assistant
03-16 14:31:16.515  3774  3813 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 14:31:16.525  1020  1141 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:16.525  1020  1033 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:16.525  3774  3813 I AMMetaDataParserService: Icon data: ResourceSearch2131363517com.android.settings.Search2130837580
,03-16 14:31:16.525  1761  1761 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-16 14:31:16.535  1761  1761 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-16 14:31:16.535  3774  3813 I AMMetaDataParserService: Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,03-16 14:31:16.535  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:16.545  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:16.545  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:16.545  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:16.545  4387  4387 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,03-16 14:31:16.545  4387  4387 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,03-16 14:31:16.555  4387  4387 D SecurityLogAgent: StateMachine : Current State = 1
,03-16 14:31:16.555  4387  4387 D SecurityLogAgent: StateMachine : Changed Current State = 1
,03-16 14:31:16.555  4459  4459 E Zygote  : MountEmulatedStorage()
03-16 14:31:16.555  4459  4459 I libpersona: KNOX_SDCARD checking this for 10077
03-16 14:31:16.555  4459  4459 E Zygote  : v2
03-16 14:31:16.555  4459  4459 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:16.555  4459  4459 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:16.565  1020  1527 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4459 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 14:31:16.565  4459  4459 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:16.565  4459  4459 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,03-16 14:31:16.565  4449  4449 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SubSettings
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LabelName
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Password
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.,settings.wifi.WifiSecSetupActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.575  3774  3813 I AMMetaDataP,arserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TetherSettings
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LanguageSettings
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.HomeSettings
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DisplaySettings
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  4449  4449 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DockSettings
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ManageApplications
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RunningServices
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LaunchApplication
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.StorageUse
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecuritySettings
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CredentialStorage
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-1,6 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetProfileOwner
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.IccLockSettings
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ApnEditor
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormat
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormatSd
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
,03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppPicker
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsbSettings
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActivityPicker
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BatteryInfo
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Display
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RadioInfo
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ProxySelector
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BandMode
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TestingSettings
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.575  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
03-16 14:31:16.585  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.585  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.585  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.585  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
03-16 14:31:16.585  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.585  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.585  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.585  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
03-16 14:31:16.585  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.585  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.585  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.585  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
03-16 14:31:16.585  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.585  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.585  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  4459  4459 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:16.605  4459  4459 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SoundSettings
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GSensorSettings
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreview
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreview
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NewModePreview
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor2014
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewStyleClock
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.WarrantyLegal
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenHelpActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PhoneVibration
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandHelp
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.605  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MagazineCard
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
,03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SearchActivity
,03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
,03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.AppList
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
,03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
,03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
,03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
03-16 14:31:16.615  3774  3813 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
03-16 14:31:16.655  3143  3176 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,03-16 14:31:16.655  3688  3688 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Mar 16 14:31:16 GMT+01:00 2016
,03-16 14:31:16.685  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-16 14:31:16.685  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-16 14:31:16.685  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:16.685  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:16.685  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:16.685  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:16.685  1020  1519 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:16.685  1020  1519 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:16.685  1020  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-16 14:31:16.705  3688  3688 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-16 14:31:16.715  3688  3688 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-16 14:31:16.715  3688  3688 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-16 14:31:16.715  3688  3688 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-16 14:31:16.715  2134  3957 I Icing   : Internal init done: storage state 0
,03-16 14:31:16.725  3688  4481 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-16 14:31:16.725  3688  4481 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,03-16 14:31:16.735  3688  4481 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,03-16 14:31:16.735  3688  4481 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
,03-16 14:31:16.735  3688  4481 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
,03-16 14:31:16.745  1020  1058 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-16 14:31:16.855  4145  4145 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,03-16 14:31:16.865  3688  4481 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 
,03-16 14:31:16.865  3688  4481 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,03-16 14:31:16.875  3688  3688 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-16 14:31:16.895  2134  3957 I Icing   : Post-init done
,03-16 14:31:16.895  4145  4483 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-16 14:31:16.905  4145  4483 I DBG_POLICYDM: [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,03-16 14:31:16.915  1020  1520 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-16 14:31:16.915  4145  4483 E DBG_POLICYDM: [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,03-16 14:31:16.925  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:16.925  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:16.925  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:16.935  4145  4483 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-16 14:31:16.945  4185  4185 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,03-16 14:31:16.955  4271  4271 I SA      : [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,03-16 14:31:16.955  4271  4271 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
03-16 14:31:16.955  4271  4271 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,03-16 14:31:16.955  4271  4271 I SA      : [SLFUCHKMGR] constructor called
,03-16 14:31:16.975  4271  4271 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
03-16 14:31:16.975  4271  4271 I SA      : [OR] == isSIMCardReady false ==
,03-16 14:31:16.985  4271  4271 I SA      : [SCU] == networkStateCheck == true
,03-16 14:31:16.985  4271  4271 I SA      : [DM] getCountryCodeFromCSC : PL
03-16 14:31:16.985  4271  4271 I SA      : isChinaCountryCode : false
,03-16 14:31:16.985  4271  4271 I SA      : [SCU] is ChinestModel Data Restricted   : false
,03-16 14:31:16.985  4271  4271 I SA      : [OR] == networkStateCheck true ==
,03-16 14:31:16.985  4145  4483 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-16 14:31:17.015  4145  4483 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-16 14:31:17.015  4145  4483 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-16 14:31:17.015  4145  4483 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-16 14:31:17.015  4145  4483 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-16 14:31:17.015  4145  4483 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-16 14:31:17.015  4145  4483 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-16 14:31:17.015  4145  4483 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,03-16 14:31:17.025  4145  4483 I DBG_POLICYDM: [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,03-16 14:31:17.035  4145  4483 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,03-16 14:31:17.045  4145  4483 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-16 14:31:17.055  4145  4483 I DBG_POLICYDM: [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,03-16 14:31:17.105  4271  4271 I SA      : [OR] GetMyCountryZoneTask
,03-16 14:31:17.105  4271  4271 I SA      : [OR] onReceive END
,03-16 14:31:17.105  1236  1236 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,03-16 14:31:17.105  1020  1759 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:17.105  1020  1759 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:17.105  1020  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-16 14:31:17.115  1020  1033 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
,03-16 14:31:17.115  1020  1033 D SecContentProvider2: mCursor = null
,03-16 14:31:17.125  1020  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:17.125  1020  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:17.125  1020  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:17.125  1020  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:17.135  1020  1525 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4490 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 14:31:17.145  4490  4490 E Zygote  : MountEmulatedStorage(),
03-16 14:31:17.145  4490  4490 E Zygote  : v2
03-16 14:31:17.145  4490  4490 I libpersona: KNOX_SDCARD checking this for 10110
03-16 14:31:17.145  4490  4490 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:17.145  4490  4490 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-16 14:31:17.145  4490  4490 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:17.145  4490  4490 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,03-16 14:31:17.145  1020  1044 W libprocessgroup: failed to open /acct/uid_10065/pid_3707/cgroup.procs: No such file or directory,
03-16 14:31:17.145  1020  1044 W libprocessgroup: failed to open /acct/uid_10014/pid_3268/cgroup.procs: No such file or directory
,03-16 14:31:17.165  4490  4490 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:17.165  4490  4490 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:17.175  4449  4449 I MusicStore: Database version: 104
,03-16 14:31:17.185  4271  4488 I SA      : [SRS] prepareGetMyCountryZone
,03-16 14:31:17.185  4271  4488 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-16 14:31:17.185  4271  4488 I SA      : [SSP] query invoked
,03-16 14:31:17.205  4271  4488 I SA      : [TPMU] GetMccFromDB : null
,03-16 14:31:17.245  4271  4488 I SA      : [SCU] getMccFromPreferece mcc = 260
03-16 14:31:17.245  4271  4488 I SA      : [TPM] isNoProxy(default) : true
,03-16 14:31:17.325  1020  1759 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:17.325  1020  1759 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:17.325  1020  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-16 14:31:17.325  4271  4488 E File    : fail readDirectory() errno=2
,03-16 14:31:17.335  4145  4163 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-16 14:31:17.365  4145  4163 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-16 14:31:17.365  4145  4163 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-16 14:31:17.365  4145  4163 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-16 14:31:17.365  4145  4163 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-16 14:31:17.365  4145  4163 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-16 14:31:17.365  4145  4163 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-16 14:31:17.375  4145  4163 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-16 14:31:17.395  2134  2134 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-16 14:31:17.395  2134  4514 I iu.SyncManager: SYNC; picasa accounts
,03-16 14:31:17.405  2134  2134 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-16 14:31:17.435  1020  1396 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:17.435  1020  1396 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:17.435  1020  1396 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:17.435  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:17.435  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:17.435  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:17.435  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:17.445  2134  4514 I iu.UploadsManager: num queued entries: 0,
,03-16 14:31:17.445  2134  4514 I iu.UploadsManager: num updated entries: 0
03-16 14:31:17.445  2134  4514 I iu.SyncManager: NEXT; no task
,03-16 14:31:17.455  4517  4517 E Zygote  : MountEmulatedStorage()
03-16 14:31:17.455  4517  4517 E Zygote  : v2
03-16 14:31:17.455  4517  4517 I libpersona: KNOX_SDCARD checking this for 10009
03-16 14:31:17.455  4517  4517 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:17.455  4517  4517 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-16 14:31:17.465  4517  4517 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:17.465  4517  4517 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-16 14:31:17.465  1020  1527 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4517 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-16 14:31:17.465  1020  1759 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:17.475  1020  1759 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:17.475  1020  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:17.485  4449  4449 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-16 14:31:17.485  4449  4449 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 14:31:17.505  4517  4517 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:17.505  4517  4517 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:17.535  4449  4449 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...,
,03-16 14:31:17.565  1020  1759 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:17.565  1020  1759 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:17.565  1020  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:17.655  3143  3176 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 10 sec
,03-16 14:31:17.675  4449  4449 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-16 14:31:17.675  4449  4449 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@e1df1ff: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,03-16 14:31:17.675  4449  4449 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-16 14:31:17.685  4449  4449 D AndroidMusic: GMSCore installation verified
,03-16 14:31:17.685  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-16 14:31:17.685  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-16 14:31:17.685  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:17.685  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 14:31:17.685  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 14:31:17.685  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:17.705  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:17.705  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:17.705  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-16 14:31:17.715   258   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-16 14:31:17.715   258   516 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 14:31:17.715  4490  4534 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-16 14:31:17.715   258   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-16 14:31:17.715   258   516 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 14:31:17.715  4490  4534 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-16 14:31:17.715  4449  4449 I ConfigStore: Config Database version: 1
,03-16 14:31:17.725   258   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-16 14:31:17.725   258   516 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 14:31:17.725  4490  4536 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-16 14:31:17.725   258   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-16 14:31:17.725   258   516 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 14:31:17.735  4490  4536 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-16 14:31:17.745  4517  4517 D WaitQueueForNetworkActivate: notifyNetworkActivated
,03-16 14:31:17.805  4517  4517 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,03-16 14:31:17.815  1020  1520 W ActivityManager: Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,03-16 14:31:17.895   258   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-16 14:31:17.895   258   516 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 14:31:17.895  4449  4449 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-16 14:31:17.945   258   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-16 14:31:17.945   258   516 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 14:31:17.945  4449  4449 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-16 14:31:17.945   258   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-16 14:31:17.945   258   516 W Vold    : Returning OperationFailed - no handler for errno 0
,03-16 14:31:17.945  4449  4449 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-16 14:31:17.955  1020  1142 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:17.955  1020  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:17.955  1020  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-16 14:31:17.975  1020  1521 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:17.975  1020  1521 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:17.975  1020  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,03-16 14:31:18.025  1020  1142 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-16 14:31:18.025  1020  1520 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-16 14:31:18.035  1020  1032 I AudioService: getStreamVolume 3 index 0
,03-16 14:31:18.035  4449  4449 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,03-16 14:31:18.065  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:18.065  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:18.065  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:18.065  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:18.065  4449  4449 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-16 14:31:18.075  1020  2778 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 14:31:18.075  4490  4490 I WebViewFactory: Loading com.google.android.webview version 37 (1726107-arm) (code 119201),
,03-16 14:31:18.085  4558  4558 E Zygote  : MountEmulatedStorage(),
03-16 14:31:18.085  4558  4558 E Zygote  : v2
03-16 14:31:18.085  4558  4558 I libpersona: KNOX_SDCARD checking this for 10001
03-16 14:31:18.085  4558  4558 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-16 14:31:18.085  4558  4558 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:18.085  4558  4558 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:18.085  4558  4558 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-16 14:31:18.085  1020  1020 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4558 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-16 14:31:18.095  1020  1141 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:18.095  1020  1141 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
03-16 14:31:18.095  1020  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,03-16 14:31:18.095  4517  4517 D hcjo    : AutoUpdateManager:IDLE:execute
,03-16 14:31:18.105  4490  4490 I LibraryLoader: Loading: webviewchromium
,03-16 14:31:18.115  1020  1525 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-16 14:31:18.115  4517  4517 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,03-16 14:31:18.115  4517  4517 D InitializeManagerStateMachine: exit::IDLE
03-16 14:31:18.115  4517  4517 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,03-16 14:31:18.115  4517  4517 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
03-16 14:31:18.115  4517  4517 D InitializeManagerStateMachine: exit::NETWORK_CHECK
03-16 14:31:18.115  4517  4517 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
03-16 14:31:18.115  4517  4517 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
03-16 14:31:18.115  4517  4517 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
03-16 14:31:18.115  4517  4517 D InitializeManagerStateMachine: entry::SUCCESS
03-16 14:31:18.115  4517  4517 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,03-16 14:31:18.125  4449  4449 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-16 14:31:18.125  4490  4490 I LibraryLoader: Time to load native libraries: 22 ms (timestamps 8017-8039)
03-16 14:31:18.125  4490  4490 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 14:31:18.135  4517  4517 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:345600000
,03-16 14:31:18.135  4558  4558 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:18.135  1020  1142 I ActivityManager: Killing 3724:com.android.managedprovisioning/u0a20 (adj 15): empty #31
,03-16 14:31:18.135  4558  4558 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:18.145  4517  4517 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
03-16 14:31:18.145  4517  4517 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,03-16 14:31:18.145  4517  4517 D InitializeManagerStateMachine: exit::SUCCESS
03-16 14:31:18.145  4517  4517 D InitializeManagerStateMachine: entry::IDLE
,03-16 14:31:18.155  1020  1141 I ActivityManager: Killing 3751:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,03-16 14:31:18.155  4490  4490 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ea12691}
,03-16 14:31:18.165  4490  4490 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 14:31:18.165  4490  4490 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,03-16 14:31:18.205  4490  4490 I BrowserStartupController: Initializing chromium process, renderers=0
,03-16 14:31:18.205  4490  4490 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 14:31:18.225  4490  4490 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,03-16 14:31:18.225  4490  4490 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,03-16 14:31:18.225  4490  4490 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
,03-16 14:31:18.245  4490  4490 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
03-16 14:31:18.245  4490  4490 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-16 14:31:18.245  4490  4490 I Adreno-EGL: Build Date: 04/06/15 Mon
03-16 14:31:18.245  4490  4490 I Adreno-EGL: Local Branch: 
03-16 14:31:18.245  4490  4490 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-16 14:31:18.245  4490  4490 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-16 14:31:18.245  4490  4490 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-16 14:31:18.255  1020  1044 W libprocessgroup: failed to open /acct/uid_10020/pid_3724/cgroup.procs: No such file or directory
,03-16 14:31:18.255  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3751/cgroup.procs: No such file or directory
,03-16 14:31:18.265  4490  4579 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-16 14:31:18.275  1020  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:18.275  1020  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:18.275  1020  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:18.275  1020  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:18.285  4590  4590 E Zygote  : MountEmulatedStorage()
,03-16 14:31:18.285  4590  4590 E Zygote  : v2
03-16 14:31:18.285  4590  4590 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:18.285  4590  4590 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:18.295  4590  4590 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:18.295  4590  4590 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:18.295  4590  4590 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:18.295  1020  1352 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4590 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-16 14:31:18.295  1020  1352 I ActivityManager: Killing 3774:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,03-16 14:31:18.325  4590  4590 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:18.325  4590  4590 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:18.355  4490  4490 I NSApplication: Starting up...
,03-16 14:31:18.375  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:18.375  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:18.375  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:18.375  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:18.385  4610  4610 E Zygote  : MountEmulatedStorage()
03-16 14:31:18.385  4610  4610 E Zygote  : v2
03-16 14:31:18.385  4610  4610 I libpersona: KNOX_SDCARD checking this for 10117
03-16 14:31:18.385  4610  4610 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:18.385  4610  4610 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:18.395  4610  4610 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-16 14:31:18.395  4610  4610 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 14:31:18.395  1020  1491 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4610 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-16 14:31:18.405  4610  4610 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:18.405  1020  1491 I ActivityManager: Killing 3822:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
03-16 14:31:18.405  4610  4610 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:18.405  1020  1491 I ActivityManager: Killing 3556:com.google.android.gm/u0a99 (adj 15): empty #32
,03-16 14:31:18.455  4610  4610 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 14:31:18.455  4590  4590 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-16 14:31:18.505  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3774/cgroup.procs: No such file or directory
,03-16 14:31:18.505  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3822/cgroup.procs: No such file or directory
,03-16 14:31:18.505  1020  1044 W libprocessgroup: failed to open /acct/uid_10099/pid_3556/cgroup.procs: No such file or directory
,03-16 14:31:18.595  4590  4590 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-16 14:31:18.605  4590  4590 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-16 14:31:18.605  4590  4590 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,03-16 14:31:18.605  4590  4590 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-16 14:31:18.605  4590  4590 I DIAGMON_AGENT: ./extraInfo: "NG700"
,03-16 14:31:18.615  4590  4590 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-16 14:31:18.635  1020  1322 E Watchdog: !@Sync 1
,03-16 14:31:18.655  3143  3176 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 11 sec
,03-16 14:31:18.665  1020  1140 D SettingsProvider: name = audio_safe_volume_state,
,03-16 14:31:18.675  4145  4156 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-16 14:31:18.675  4145  4156 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-16 14:31:18.675  4145  4156 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-16 14:31:18.685  4145  4154 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-16 14:31:18.685  4145  4154 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-16 14:31:18.685  4145  4154 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-16 14:31:18.685  1020  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:18.685  1020  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:18.685  1020  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:18.685  1020  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:18.705  4627  4627 E Zygote  : MountEmulatedStorage()
,03-16 14:31:18.705  4627  4627 E Zygote  : v2
03-16 14:31:18.705  4627  4627 I libpersona: KNOX_SDCARD checking this for 10008
03-16 14:31:18.705  4627  4627 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:18.705  4627  4627 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:18.705  4627  4627 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-16 14:31:18.705  1020  1525 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4627 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 14:31:18.715  4627  4627 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-16 14:31:18.725   310   310 I art     : Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 597us total 19.920ms
,03-16 14:31:18.735  4627  4627 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-16 14:31:18.735  4627  4627 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:18.745   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 16.792ms
,03-16 14:31:18.765   310   310 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 650us total 17.129ms
,03-16 14:31:18.815  1020  1033 I ActivityManager: Killing 3842:com.google.android.talk/u0a102 (adj 15): empty #31
,03-16 14:31:18.815  4627  4627 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-16 14:31:18.825  4627  4627 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-16 14:31:18.825  4627  4627 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-16 14:31:18.825  4627  4627 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-16 14:31:18.825  1020  1527 I ActivityManager: Killing 3874:com.sec.knox.bridge/1000 (adj 15): empty #31
,03-16 14:31:18.875  1020  1521 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:18.875  1020  1521 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:18.875  1020  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-16 14:31:18.935  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3874/cgroup.procs: No such file or directory
,03-16 14:31:18.935  1020  1044 W libprocessgroup: failed to open /acct/uid_10102/pid_3842/cgroup.procs: No such file or directory
,03-16 14:31:19.225  4057  4057 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,03-16 14:31:19.225  4057  4057 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,03-16 14:31:19.235  4057  4057 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-16 14:31:19.235  1020  1759 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-16 14:31:19.235  1020  1045 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:19.235  1020  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:19.235  1020  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:19.245  1020  1020 I splitIntent: Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=12, mSplitNum[2]=17, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
,03-16 14:31:19.245  1020  1020 I splitIntent: finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,03-16 14:31:19.245  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:19.245  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:19.255  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:19.255  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:19.265  4657  4657 E Zygote  : MountEmulatedStorage()
03-16 14:31:19.265  4657  4657 E Zygote  : v2
03-16 14:31:19.265  4657  4657 I libpersona: KNOX_SDCARD checking this for 10058
03-16 14:31:19.265  4657  4657 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:19.265  1020  1045 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4657 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 14:31:19.275  4657  4657 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:19.275  4657  4657 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:19.275  4657  4657 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:19.295  1020  1520 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:19.295  1020  1520 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:19.295  1020  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-16 14:31:19.295  4627  4627 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-16 14:31:19.305  1818  1818 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-16 14:31:19.305  1818  1818 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-16 14:31:19.305  1818  1818 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-16 14:31:19.315   290   290 E SMD     : DCD OFF,
,03-16 14:31:19.325  4657  4657 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:19.325  4657  4657 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:19.325  2875  4247 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,03-16 14:31:19.325  1818  1818 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-16 14:31:19.335  4627  4627 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,03-16 14:31:19.335  3143  3143 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,03-16 14:31:19.335  1020  1759 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:19.335  1020  1759 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:19.335  1020  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-16 14:31:19.345  3143  3143 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,03-16 14:31:19.345  1818  1818 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-16 14:31:19.345  3143  3143 E DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,03-16 14:31:19.345  1818  1818 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,03-16 14:31:19.345  1818  1818 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-16 14:31:19.345  1818  1818 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-16 14:31:19.345  1818  1818 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-16 14:31:19.345  1818  1818 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,03-16 14:31:19.345  1818  1818 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-16 14:31:19.345  1818  1818 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-16 14:31:19.355  3688  3688 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Wed Mar 16 14:31:19 GMT+01:00 2016
,03-16 14:31:19.355  1818  1818 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-16 14:31:19.355  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:19.355  1020  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:19.355  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-16 14:31:19.355  1818  1818 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-16 14:31:19.355  3143  3143 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,03-16 14:31:19.355  1818  1818 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-16 14:31:19.355  1818  1818 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-16 14:31:19.365  3688  3688 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-16 14:31:19.365  1818  1818 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-16 14:31:19.365  4387  4387 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-16 14:31:19.365  4387  4387 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-16 14:31:19.365  4387  4387 D SecurityLogAgent: StateMachine : Current State = 1
,03-16 14:31:19.375  4271  4271 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,03-16 14:31:19.375  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:19.375  1020  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:19.385  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-16 14:31:19.385  3688  3688 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-16 14:31:19.395  1843  1843 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 14:31:19.395  1843  1843 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 14:31:19.405  3688  3688 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-16 14:31:19.425  4657  4657 I ExternalOEMControlProvider: onCreate
,03-16 14:31:19.425  3688  3688 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-16 14:31:19.435  1818  1818 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-16 14:31:19.435  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:19.435  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:19.435  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:19.435  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:19.435  3688  4676 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,03-16 14:31:19.445  3688  4676 I KLMS-2.5.123: : KLMSIntentService(): TIME_CHANGED
,03-16 14:31:19.445  3688  4676 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().START : Wed Mar 16 14:31:19 GMT+01:00 2016
,03-16 14:31:19.445  1020  1527 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4677 uid=10153 gids={50153, 9997} abi=armeabi-v7a
,03-16 14:31:19.455  4677  4677 E Zygote  : MountEmulatedStorage(),
03-16 14:31:19.455  4677  4677 I libpersona: KNOX_SDCARD checking this for 10153
03-16 14:31:19.455  4677  4677 E Zygote  : v2
03-16 14:31:19.455  4677  4677 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:19.455  4677  4677 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:19.455  3688  4676 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().END
,03-16 14:31:19.455  4677  4677 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:19.455  4677  4677 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:19.475  4677  4677 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:19.475  1818  1818 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,03-16 14:31:19.475  1818  1818 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-16 14:31:19.475  4677  4677 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:19.485  3688  3688 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-16 14:31:19.505  4271  4488 I SA      : [RC New] Execute method=[GET] start
,03-16 14:31:19.525  1020  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:19.525  1020  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:19.525  1020  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:19.525  1020  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:19.535  4693  4693 E Zygote  : MountEmulatedStorage()
03-16 14:31:19.535  4693  4693 E Zygote  : v2
03-16 14:31:19.535  4693  4693 I libpersona: KNOX_SDCARD checking this for 10041
03-16 14:31:19.535  4693  4693 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:19.535  4693  4693 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:19.545  1020  1525 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=4693 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a,
,03-16 14:31:19.545  4693  4693 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:19.545  4693  4693 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-16 14:31:19.545  1020  1352 I art     : Explicit concurrent mark sweep GC freed 24196(1477KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 22MB/33MB, paused 2.636ms total 179.015ms
,03-16 14:31:19.555  4677  4677 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 14:31:19.565  1020  1520 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:19.565  1020  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:19.565  1020  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:19.565  4271  4488 I SA      : [RC New] Security=[true]
,03-16 14:31:19.565  1761  1761 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,03-16 14:31:19.565  1761  1761 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-16 14:31:19.575  4657  4692 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,03-16 14:31:19.575  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:19.575  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:19.575  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:19.575  1020  1527 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:19.575  4271  4488 I System.out: Thread-651(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-16 14:31:19.585  4271  4488 I System.out: Thread-651(ApacheHTTPLog):isSBSettingEnabled false
,03-16 14:31:19.585  4271  4488 I System.out: Thread-651(ApacheHTTPLog):isShipBuild true
,03-16 14:31:19.585  4271  4488 I System.out: Thread-651(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,03-16 14:31:19.595  4708  4708 E Zygote  : MountEmulatedStorage()
,03-16 14:31:19.595  4708  4708 I libpersona: KNOX_SDCARD checking this for 10081
03-16 14:31:19.595  4708  4708 E Zygote  : v2
03-16 14:31:19.595  4708  4708 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:19.595  4708  4708 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:31:19.595  1020  1527 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=4708 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 14:31:19.595  4271  4488 I System.out: Thread-651(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-16 14:31:19.595  4708  4708 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:19.595  4708  4708 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:19.595   280  1012 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
03-16 14:31:19.595   280  1012 D Netd    : getNetworkForDns: using netid 502 for uid 10036
,03-16 14:31:19.605  2875  2875 I Process : Sending signal. PID: 2875 SIG: 9
,03-16 14:31:19.605  4693  4693 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:19.605  4693  4693 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:19.635  4708  4708 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:19.635  4708  4708 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:19.635  1020  1396 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:19.635  1020  1396 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:19.635  1020  1396 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:19.635  1020  1396 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:19.645  4724  4724 E Zygote  : MountEmulatedStorage(),
03-16 14:31:19.645  4724  4724 E Zygote  : v2
03-16 14:31:19.645  4724  4724 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:19.645  4724  4724 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:19.645  4724  4724 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:19.645  1020  1396 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4724 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 14:31:19.655  4724  4724 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
03-16 14:31:19.655  4724  4724 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:19.655  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:19.655  1020  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:19.655  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:19.655  3143  3176 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 12 sec
,03-16 14:31:19.665  4693  4693 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,03-16 14:31:19.665  4693  4693 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 14:31:19.665  4693  4693 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 14:31:19.665  4693  4693 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-16 14:31:19.665  4693  4693 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-16 14:31:19.675  3143  3176 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-16 14:31:19.675  3143  3176 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,03-16 14:31:19.675  3143  3176 I DBG_DM  : [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,03-16 14:31:19.685  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-16 14:31:19.685  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-16 14:31:19.685  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:19.695  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 14:31:19.695  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 14:31:19.695  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:19.695  4724  4724 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:19.695  1020  1525 I ActivityManager: Process com.sec.android.app.sysscope (pid 2875)(adj 0) has died(28,618)
,03-16 14:31:19.695  4724  4724 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:19.705  4708  4708 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-16 14:31:19.705  4708  4708 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-16 14:31:19.705  4708  4708 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 14:31:19.705  4708  4708 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 14:31:19.705  4708  4708 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,03-16 14:31:19.725  1020  1519 I ActivityManager: Killing 3923:com.samsung.helphub/1000 (adj 15): empty #31
,03-16 14:31:19.735  1020  1759 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:19.735  1020  1759 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:19.735  1020  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:19.745  3143  3176 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-16 14:31:19.755  1020  1525 I ActivityManager: Killing 3859:com.vlingo.midas/u0a28 (adj 15): empty #31
,03-16 14:31:19.785  3143  3176 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-16 14:31:19.805  3143  3176 I DBG_DM  : [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,03-16 14:31:19.805  3143  3176 I DBG_DM  : [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,03-16 14:31:19.805  3143  3176 I DBG_DM  : [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,03-16 14:31:19.815  3143  3176 I DBG_DM  : [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,03-16 14:31:19.815  1020  1045 I ActivityManager: Waited long enough for: ServiceRecord{13e385fc u0 com.android.settings/.wifi.WifiCredService}
,03-16 14:31:19.855  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3923/cgroup.procs: No such file or directory
,03-16 14:31:19.855  1020  1044 W libprocessgroup: failed to open /acct/uid_10028/pid_3859/cgroup.procs: No such file or directory
,03-16 14:31:19.875  1020  1045 I ActivityManager: Waited long enough for: ServiceRecord{3db49894 u0 com.samsung.android.providers.context/.ContextService}
,03-16 14:31:19.875  4693  4693 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,03-16 14:31:19.895  3143  3176 I DBG_DM  : [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,03-16 14:31:19.895  3143  3177 I DBG_DM  : [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
03-16 14:31:19.895  4724  4724 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458135079906
,03-16 14:31:19.895  4724  4724 D         : TimeServiceNative: User Time to be set is 1458135079906
03-16 14:31:19.895  4724  4724 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
,03-16 14:31:19.895  4724  4724 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-16 14:31:19.895  4724  4724 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458135079906
,03-16 14:31:19.895   329   437 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-16 14:31:19.895  4724  4724 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,03-16 14:31:19.895   329  4741 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458135079906
03-16 14:31:19.895   329  4741 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458135079906, operation = 0
03-16 14:31:19.895   329  4741 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS8/11/70 17:7:58
03-16 14:31:19.895   329  4741 D QC-time-services: Daemon:Value read from RTC seconds = 21920878000
03-16 14:31:19.895   329  4741 D QC-time-services: Daemon:new time 1458135079906 
03-16 14:31:19.895   329  4741 D QC-time-services: Daemon: delta 1436214201906 genoff 1436214201906 
03-16 14:31:19.895   329  4741 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436214201906 to memory
,03-16 14:31:19.895   329  4741 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-16 14:31:19.905   329  4741 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-16 14:31:19.905  3143  3176 I DBG_DM  : [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,03-16 14:31:19.905  3143  3177 I DBG_DM  : [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,03-16 14:31:19.905  3143  3176 I DBG_DM  : [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,03-16 14:31:19.935  3143  3177 I DBG_DM  : [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:362673799
,03-16 14:31:19.935  3143  3177 I DBG_DM  : [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,03-16 14:31:19.935  1020  1396 D SettingsProvider: name = next_alarm_formatted
03-16 14:31:19.935  1020  1396 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 14:31:19.935  1020  1396 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 14:31:19.935  1020  1396 D SettingsProvider: selectionArgs: false
03-16 14:31:19.935  1020  1396 D SettingsProvider: selectionArgs: 10081
03-16 14:31:19.935  1020  1396 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 14:31:19.935  1020  1396 D SettingsProvider: ret = -1
,03-16 14:31:19.945  3143  3177 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,03-16 14:31:19.955  3143  3177 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,03-16 14:31:19.955  1020  1520 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:19.955  1020  1520 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
03-16 14:31:19.955  1020  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,03-16 14:31:19.965   329  4741 D QC-time-services: Updating the TOD offset
03-16 14:31:19.965   329  4741 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436214201906 to memory
03-16 14:31:19.965   329  4741 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-16 14:31:19.965   329  4741 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-16 14:31:19.965   329  4741 E QC-time-services: Daemon:Update to modem bit set
03-16 14:31:19.965  4724  4724 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
03-16 14:31:19.965   329  4741 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-16 14:31:19.965   329  4741 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120249401906
,03-16 14:31:19.975   329   433 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
03-16 14:31:19.975   329   437 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-16 14:31:19.995  1020  1142 I ActivityManager: Killing 3976:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,03-16 14:31:20.015  3143  3177 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,03-16 14:31:20.025  3143  3177 I DBG_DM  : [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 705624899
,03-16 14:31:20.025  3143  3143 I DBG_DM  : [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,03-16 14:31:20.045  3143  3143 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,03-16 14:31:20.055  3143  3143 I DBG_DM  : [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,03-16 14:31:20.065  4693  4693 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 171.320ms
,03-16 14:31:20.075  3143  3143 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,03-16 14:31:20.075  3143  3177 I DBG_DM  : [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
03-16 14:31:20.075  3143  3143 I DBG_DM  : [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,03-16 14:31:20.075  3143  3177 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,03-16 14:31:20.075  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3976/cgroup.procs: No such file or directory
,03-16 14:31:20.075  3143  3143 E DBG_DM  : [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,03-16 14:31:20.085  3143  3177 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,03-16 14:31:20.085  3143  3143 E DBG_DM  : [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@96a852a
,03-16 14:31:20.085  4708  4708 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 144.873ms
,03-16 14:31:20.085  3143  3177 I DBG_DM  : [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(649/IIIIllIlIIlIIIIlllIl)] nWidgetStatus : 2
,03-16 14:31:20.085  3143  3177 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.wssyncmldm.ui.llllIIIllIlIIIIllllI.IIIIllIlIIlIIIIlllIl:652 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:172 llllIIIllIllIlllIIlI.llIIIIlllllIIllIIllI:732 
,03-16 14:31:20.095  1020  1520 D SettingsProvider: name = SOFTWARE_UPDATE_NOTIFICATION_STATUS
,03-16 14:31:20.115  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text,
,03-16 14:31:20.115  3143  3177 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7,
,03-16 14:31:20.125  3143  3177 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-16 14:31:20.155  1020  1032 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,03-16 14:31:20.155  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:20.155  1020  1032 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
03-16 14:31:20.155  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:20.165  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:20.165  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:20.175  4749  4749 E Zygote  : MountEmulatedStorage()
,03-16 14:31:20.175  4749  4749 E Zygote  : v2
03-16 14:31:20.175  4749  4749 I libpersona: KNOX_SDCARD checking this for 10090
03-16 14:31:20.175  4749  4749 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:20.175  1020  1033 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=4749 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a,
,03-16 14:31:20.185  1020  1020 D WindowManager: showStatusBarByNotification() mOpenByNotification=false,
03-16 14:31:20.185  1020  1033 I ActivityManager: Killing 4004:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-16 14:31:20.185  4749  4749 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:31:20.185  4749  4749 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:31:20.185  4749  4749 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:20.195  1020  1020 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-16 14:31:20.195  4693  4693 W art     : Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 129.175ms
,03-16 14:31:20.195  1181  1833 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 14:31:20.205  4693  4758 D Mms/ArtClassLoader: init before art
,03-16 14:31:20.205  1020  1525 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
03-16 14:31:20.205  1020  1525 D SecContentProvider2: mCursor = null
,03-16 14:31:20.205  4693  4693 D Mms/TelephonyPermission: start operation mode monitor
,03-16 14:31:20.205  1020  1527 D SecContentProvider2: uri = 15 selection = getToastGravity
,03-16 14:31:20.205  4749  4749 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:20.205  1020  1527 D SecContentProvider2: mCursor = null
,03-16 14:31:20.205  4749  4749 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:20.205  1020  1141 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
03-16 14:31:20.205  1020  1141 D SecContentProvider2: mCursor = null
,03-16 14:31:20.215  4693  4693 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 14:31:20.215  1020  1759 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,03-16 14:31:20.215  1020  1759 D SecContentProvider2: mCursor = null
,03-16 14:31:20.165  3143  3177 I DBG_DM  : [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
,03-16 14:31:20.245  4693  4693 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
03-16 14:31:20.245  4693  4693 D Mms/TelephonyPermission: isDefault true
,03-16 14:31:20.245  4693  4693 D Mms/MmsApp: onCreate() com.android.mms
,03-16 14:31:20.265  3143  3177 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-16 14:31:20.275  1181  1181 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,03-16 14:31:20.275  1020  1527 D SecContentProvider2: uri = 15 selection = getToastEnabledState
03-16 14:31:20.275  1020  1527 D SecContentProvider2: mCursor = null
,03-16 14:31:20.285  1020  1525 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,03-16 14:31:20.285  1020  1525 D SecContentProvider2: mCursor = null
,03-16 14:31:20.285  1181  1181 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
,03-16 14:31:20.295  1181  1181 D PersonaManager: PersonaID is invalid or persona doesn't exists. : 0
,03-16 14:31:20.295  1181  1181 D PersonaManager: isKioskContainerExistOnDevice
,03-16 14:31:20.295  1181  1181 D PersonaManager: isKioskContainerExistOnDevice
,03-16 14:31:20.295  1020  1100 V AlarmManager: waitForAlarm result :4
,03-16 14:31:20.305  1181  1181 I PhoneStatusBar: Icon Only
,03-16 14:31:20.305  1181  1181 I StatusBar: Icon Only
,03-16 14:31:20.305  1181  1181 D PanelView: There is/are notification(s) 
03-16 14:31:20.305  1181  1181 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-16 14:31:20.305  3143  3177 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 8
,03-16 14:31:20.305  1181  1181 D PersonaManager: isKioskContainerExistOnDevice
03-16 14:31:20.305  1181  1181 I PhoneStatusBar: Icon Only
03-16 14:31:20.305  1181  1181 I StatusBar: Icon Only
,03-16 14:31:20.305  1181  1181 D PanelView: There is/are notification(s) 
03-16 14:31:20.305  1181  1181 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-16 14:31:20.305  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_4004/cgroup.procs: No such file or directory
,03-16 14:31:20.305  4749  4749 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,03-16 14:31:20.305  4749  4749 D elm:15121: ELMEngine.ELMEngine( context ).
,03-16 14:31:20.305  3143  3177 I DBG_DM  : [com.wssyncmldm.ui.XUIFotaPostponeActivity(386/llIIIIlllllIIllIIllI)] No idle Postpone
,03-16 14:31:20.305  3143  3177 I DBG_DM  : [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,03-16 14:31:20.315  4749  4749 D elm:15121: MDMBridge.setEnterpriseBridge()
,03-16 14:31:20.315  1020  1527 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.315  1020  1527 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.315  1020  1527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-16 14:31:20.325  4749  4749 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,03-16 14:31:20.325  1020  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:20.325  1020  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:20.325  3143  4766 D OpenGLRenderer: Render dirty regions requested: true
,03-16 14:31:20.325  1020  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:20.325  1020  1759 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:20.335  4768  4768 E Zygote  : MountEmulatedStorage(),
03-16 14:31:20.335  4768  4768 I libpersona: KNOX_SDCARD checking this for 10130
03-16 14:31:20.335  4768  4768 E Zygote  : v2
03-16 14:31:20.335  4768  4768 I libpersona: KNOX_SDCARD not a persona,
03-16 14:31:20.335  4768  4768 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:31:20.345  1020  1759 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=4768 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,03-16 14:31:20.345  4693  4693 D Mms/MmsApp: [start]    initCountryIso consume time = 464.748333
,03-16 14:31:20.345  4768  4768 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:20.345  4768  4768 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,03-16 14:31:20.345  4749  4749 D elm:15121: ElmAgentService : onCreate()
,03-16 14:31:20.345  4749  4767 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,03-16 14:31:20.355   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=4, Uoast
,03-16 14:31:20.365  4693  4758 W art     : Verification of com.android.mms.ui.ConversationListAdapter com.android.mms.ui.ConversationListFragment.access$1300(com.android.mms.ui.ConversationListFragment) took 101.597ms
,03-16 14:31:20.365  1020  1396 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1020
,03-16 14:31:20.375  4749  4767 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).
,03-16 14:31:20.375  4749  4749 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
03-16 14:31:20.375  4749  4749 D elm:15121: ModuleBase.ModifySetAlarm()
03-16 14:31:20.375  4749  4749 D elm:15121: MDMBridge.getInstance()
03-16 14:31:20.375  4749  4749 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-16 14:31:20.375  4749  4749 D elm:15121: ElmAgentService : onDestroy().
,03-16 14:31:20.375  1181  1181 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,03-16 14:31:20.375  1020  1142 I ActivityManager: Killing 4091:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #31
,03-16 14:31:20.385  3143  3143 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-16 14:31:20.385  3143  4766 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-16 14:31:20.385  3143  4766 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-16 14:31:20.385  3143  4766 I Adreno-EGL: Build Date: 04/06/15 Mon
03-16 14:31:20.385  3143  4766 I Adreno-EGL: Local Branch: 
03-16 14:31:20.385  3143  4766 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-16 14:31:20.385  3143  4766 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-16 14:31:20.385  3143  4766 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-16 14:31:20.385  3143  4766 I OpenGLRenderer: Initialized EGL, version 1.4
,03-16 14:31:20.395  1020  1141 D CountryDetector: The first listener is added
,03-16 14:31:20.395  4768  4768 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:20.395  4768  4768 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:20.405  3143  4766 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-16 14:31:20.405  3143  4766 D OpenGLRenderer: Enabling debug mode 0
,03-16 14:31:20.415  4693  4693 D Mms/MmsApp: [end]    initCountryIso consume time = 70.979583
03-16 14:31:20.415  4693  4693 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.203906
,03-16 14:31:20.435  4768  4768 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 14:31:20.435  4768  4768 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,03-16 14:31:20.445  4693  4693 D Mms/MmsConfig: before partial update
,03-16 14:31:20.475  4693  4693 D Mms/MmsConfig: Load Resize quality : 80
,03-16 14:31:20.475  1020  1759 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:20.475  1020  1759 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:20.475  1020  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,03-16 14:31:20.485  4693  4693 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,03-16 14:31:20.485  4693  4693 D EasySignUpManager_1.0.1: isAuth is false
,03-16 14:31:20.485  4693  4693 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,03-16 14:31:20.495  1020  1396 I ActivityManager: Killing 4220:com.sec.android.app.camera/u0a135 (adj 15): empty #31
,03-16 14:31:20.505  1458  1474 D TP/MmsSmsProvider: query,matched:2117, calling pid = 4693
,03-16 14:31:20.505  1458  1474 D TP/MmsSmsProvider: match 2117:Elapsed time : 2.902 ms
,03-16 14:31:20.505  1020  1044 W libprocessgroup: failed to open /acct/uid_10127/pid_4091/cgroup.procs: No such file or directory
,03-16 14:31:20.515  4271  4488 I SA      : [RC New] [v2liruge] api execute + 956
03-16 14:31:20.515  4271  4488 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,03-16 14:31:20.515  4271  4488 I System.out: AsyncTask #1 calls detatch()
,03-16 14:31:20.525  4693  4693 D EasySignUpManager_1.0.1: isAuth is false
,03-16 14:31:20.525  4693  4693 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,03-16 14:31:20.535  4271  4488 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,03-16 14:31:20.535  4693  4693 E CscParser: mps_code.dat does not exist
,03-16 14:31:20.535  4693  4693 E CscParser: customer_path =/system/csc/customer.xml
03-16 14:31:20.535  4693  4693 E CscParser: fileName + /system/csc/customer.xml
,03-16 14:31:20.545  4271  4488 I SA      : [OCP] update openData : PL
,03-16 14:31:20.555  4271  4488 I SA      : [TPMU] getNetworkMcc : 
,03-16 14:31:20.555  4271  4488 I SA      : [SCU] saveMccToPreferece Start
03-16 14:31:20.555  4271  4488 I SA      : [SCU] RegionMCC : 260
03-16 14:31:20.555  4271  4488 I SA      : [SSP] query invoked
,03-16 14:31:20.555  4271  4488 I SA      : [TPMU] GetMccFromDB : null
,03-16 14:31:20.555  4271  4488 I SA      : [SCU] getMccFromPreferece mcc = 260
,03-16 14:31:20.565  4271  4488 I SA      : [SCU] saveMccToPreferece End
,03-16 14:31:20.565  4271  4488 I SA      : [RC New] executeRequest [v2liruge] end. 1056
03-16 14:31:20.565  4271  4488 I SA      : [RC New] Execute end
,03-16 14:31:20.565  4271  4271 I SA      : [OR] GetMyCountryZoneTask mcc = 260
,03-16 14:31:20.565  4271  4271 I SA      : [OR] GetMyCountryZoneTask Success
,03-16 14:31:20.575  4693  4693 E CscParser: mps_code.dat does not exist,
03-16 14:31:20.575  4693  4693 E CscParser: customer_path =/system/csc/customer.xml
03-16 14:31:20.575  4693  4693 E CscParser: fileName + /system/csc/customer.xml
,03-16 14:31:20.585  4693  4693 D CscParser: getInstance fileName =/system/csc/customer.xml,
,03-16 14:31:20.585  4693  4693 D Mms/MmsConfig:  enable multiwindow = false
,03-16 14:31:20.595  4693  4693 E Mms/MessageUtils: setCountryDetector : update country detector info 
03-16 14:31:20.595  4693  4693 E Mms/MessageUtils: updateCountryIso : update country iso info 
,03-16 14:31:20.595  4693  4693 D Mms/MmsConfig: [end]    init() consume time = 186.527292
,03-16 14:31:20.605  4693  4693 D Mms/Contact: [start]    init() consume time = 2.028281
,03-16 14:31:20.615  4693  4693 D Mms/Contact: [end]    init consume time = 17.135104
,03-16 14:31:20.625  4693  4791 D Mms/DraftCache: [start]    rebuildCache consume time = 6.898177
,03-16 14:31:20.625  1458  1758 D TP/MmsSmsProvider: query,matched:13, calling pid = 4693
,03-16 14:31:20.625  1458  1477 D TP/MmsSmsProvider: query,matched:12, calling pid = 4693
,03-16 14:31:20.635  1458  1758 D TP/MmsSmsProvider: match 13:Elapsed time : 2.462 ms
,03-16 14:31:20.635  1458  1477 D TP/MmsSmsProvider: match 12:Elapsed time : 2.972 ms
,03-16 14:31:20.635  1020  1044 W libprocessgroup: failed to open /acct/uid_10135/pid_4220/cgroup.procs: No such file or directory
,03-16 14:31:20.635  4693  4693 D Mms/MethodReflector: getSubId is called
03-16 14:31:20.635  4693  4693 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-16 14:31:20.635  4693  4693 D Mms/MethodReflector: getTelephonyProperty is called
,03-16 14:31:20.635  4693  4693 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-16 14:31:20.635  4693  4693 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-16 14:31:20.635  4693  4693 D Mms/DownloadManager: auto download without roaming -> true
03-16 14:31:20.635  4693  4693 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
03-16 14:31:20.635  4693  4791 D Mms/DraftCache: [end]    rebuildCache consume time = 13.419219
03-16 14:31:20.635  4693  4693 D Mms/MethodReflector: getSubId is called
,03-16 14:31:20.645  4693  4693 D Mms/MethodReflector: getDefaultSmsSubId is called
03-16 14:31:20.645  4693  4693 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
03-16 14:31:20.645  4693  4693 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
03-16 14:31:20.645  4693  4693 D Mms/MethodReflector: getTelephonyProperty is called
03-16 14:31:20.645  4693  4693 D Mms/DownloadManager: roaming -> false (slotId = 1)
03-16 14:31:20.645  4693  4693 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
03-16 14:31:20.645  4693  4693 D Mms/DownloadManager: auto download without roaming -> true
03-16 14:31:20.645  4693  4693 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
03-16 14:31:20.645  4693  4693 D Mms/DownloadManager: auto download during roaming secondary -> false
03-16 14:31:20.645  4693  4693 D Mms/DownloadManager: mAutoDownload ------> true
,03-16 14:31:20.665  4693  4693 D ComposerPerformance: 1458135080671 ms / [DONE] Composer constructor
,03-16 14:31:20.665  4693  4793 D Mms/Conversation: [start]    init() consume time = 25.897917
,03-16 14:31:20.665  1458  1474 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,03-16 14:31:20.665  4693  4693 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,03-16 14:31:20.675  4693  4693 I Mms/ReservationManager: ReservationManager()
,03-16 14:31:20.675  4693  4693 I Mms/ReservationManager: resetAfterConnected()
,03-16 14:31:20.675  1458  1474 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-16 14:31:20.675  1458  1474 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,03-16 14:31:20.675  1458  1758 D TP/MmsSmsProvider: query,matched:7, calling pid = 4693
,03-16 14:31:20.675  1458  1758 D TP/MmsSmsProvider: match 7:Elapsed time : 4.453 ms
,03-16 14:31:20.685  1458  1474 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,03-16 14:31:20.685  1458  1474 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-16 14:31:20.685  1458  1474 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-16 14:31:20.685  1458  1474 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-16 14:31:20.685  1458  1474 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-16 14:31:20.685  1458  1474 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-16 14:31:20.685  1458  1474 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-16 14:31:20.685  4693  4693 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,03-16 14:31:20.695  1458  1474 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
03-16 14:31:20.695  1458  1474 D TP/MmsSmsProvider: need read changed broadcast:false
,03-16 14:31:20.695  4693  4793 D Mms/Conversation: [end]    init consume time = 29.756406
,03-16 14:31:20.695  4693  4758 D Mms/ArtClassLoader: init [DONE] art
,03-16 14:31:20.695  4693  4693 D Mms/MmsApp: [end]    onCreate() consume time = 3.128594
,03-16 14:31:20.715  4693  4793 D Mms/MessagingNotification: [start]    init() consume time = 15.056354
,03-16 14:31:20.715  4693  4793 D Mms/MessagingNotification: [end]    init consume time = 3.764427
,03-16 14:31:20.725  4693  4795 D Mms/Synchronizer: [start]    doSync consume time = 4.471406
,03-16 14:31:20.725  4693  4693 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
,03-16 14:31:20.725  4693  4693 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,03-16 14:31:20.725  1020  1142 I splitIntent: Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
,03-16 14:31:20.725  1458  1753 D TP/MmsSmsProvider: query,matched:0, calling pid = 4693
03-16 14:31:20.725  1458  1753 V TP/MmsSmsProvider: getSimpleConversations entered.
,03-16 14:31:20.725  1458  1753 D TP/MmsSmsProvider: match 0:Elapsed time : 1.272 ms
,03-16 14:31:20.725  4693  4794 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 5.195417
,03-16 14:31:20.725  1020  1142 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:20.725  1020  1142 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 14:31:20.735  1020  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.735  1020  1142 I ActivityManager: Killing 4310:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,03-16 14:31:20.735  4693  4693 D Mms/MethodReflector: getSubId is called
,03-16 14:31:20.735  4693  4693 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-16 14:31:20.735  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:20.735  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.735  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.745  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.745  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.745  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.745  4693  4693 D Mms/MethodReflector: getTelephonyProperty is called
03-16 14:31:20.745  4693  4693 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-16 14:31:20.745  4693  4693 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-16 14:31:20.745  4693  4693 D Mms/DownloadManager: auto download without roaming -> true
03-16 14:31:20.745  4693  4693 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
,03-16 14:31:20.745  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:20.745  4693  4693 D Mms/DownloadManager: mAutoDownload ------> true
,03-16 14:31:20.745  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.745  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.755  1458  1474 D TP/MmsSmsProvider: update, matched:300, calling pid = 4693
03-16 14:31:20.755  1458  1474 V TP/MmsSmsProvider: syncDBData start
,03-16 14:31:20.755  1458  1474 V TP/MmsSmsProvider: syncDBData sms end
,03-16 14:31:20.755  1458  1474 V TP/MmsSmsProvider: syncDBData mms end
,03-16 14:31:20.755  1458  1474 V TP/MmsSmsProvider: syncDBData end
,03-16 14:31:20.755  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.755  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.755  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.765  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.765  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.765  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.765  1458  1758 D TP/MmsSmsProvider: query,matched:400, calling pid = 4693
,03-16 14:31:20.765  4693  4795 D Mms/Synchronizer: [end]    doSync consume time = 40.322448
,03-16 14:31:20.765  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.765  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.765  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.775  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:20.775  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.775  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.775  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.775  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.775  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.775  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.775  4693  4793 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
03-16 14:31:20.775  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.775  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.775  4693  4793 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,03-16 14:31:20.785  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.785  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.785  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.785  4693  4794 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 18.115885
,03-16 14:31:20.785  1458  1474 D TP/SmsProvider: query,matched:26, calling pid = 4693
,03-16 14:31:20.785  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.785  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.785  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.785  1458  1474 D TP/SmsProvider: match 26:Elapsed time : 2.065 ms
,03-16 14:31:20.795  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.795  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.795  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.795  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.795  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.795  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.795  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.795  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.795  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.805  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.805  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.805  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.805  1458  1758 D TP/MmsSmsProvider: query,matched:6, calling pid = 4693
,03-16 14:31:20.805  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.805  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.805  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.815  1458  1758 D TP/MmsSmsProvider: match 6:Elapsed time : 3.573 ms
,03-16 14:31:20.815  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.815  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.815  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.815  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.815  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.815  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.825  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.825  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.825  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.825  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.825  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.825  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.835  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.835  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.835  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.835  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.835  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.835  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.835  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.835  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.835  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.845  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:20.845  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.845  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.845  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.845  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.845  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.845  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.845  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.845  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.855  1020  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:20.855  1020  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:20.855  1020  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:20.855  1020  1521 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:20.855  1020  1044 W libprocessgroup: failed to open /acct/uid_10068/pid_4310/cgroup.procs: No such file or directory
,03-16 14:31:20.865  1020  1521 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=4796 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,03-16 14:31:20.865  4796  4796 E Zygote  : MountEmulatedStorage(),
03-16 14:31:20.865  4796  4796 E Zygote  : v2
03-16 14:31:20.865  4796  4796 I libpersona: KNOX_SDCARD checking this for 10023
03-16 14:31:20.865  4796  4796 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:20.865  1020  1020 W ActivityManager: userId = 0, bbcId = -10000,
,03-16 14:31:20.865  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
03-16 14:31:20.865  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.875  4796  4796 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
03-16 14:31:20.875  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:20.875  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.875  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-16 14:31:20.875  4796  4796 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:20.875  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.875  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.875  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-16 14:31:20.875  4796  4796 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:20.885  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.885  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.885  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.885  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.885  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.885  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.885  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.885  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.885  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:20.895  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:20.895  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:20.895  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-16 14:31:20.895  4796  4796 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:20.895  4796  4796 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:20.905  1020  1352 I ActivityManager: Killing 4129:com.android.vending/u0a26 (adj 15): empty #31
,03-16 14:31:20.925  1020  1527 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:20.925  1020  1527 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:20.925  1020  1527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:20.925  1020  1759 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,03-16 14:31:20.925  1020  1759 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
,03-16 14:31:20.935  1020  1759 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
03-16 14:31:20.935  1020  1759 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-16 14:31:20.935  1020  1759 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:20.935  1020  1759 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:20.935  1020  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:20.945  1458  4811 D SIP     : [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,03-16 14:31:20.955  1458  4811 E File    : fail readDirectory() errno=2
,03-16 14:31:20.965  1020  1352 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:20.965  1020  1352 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:20.965  1020  1352 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:20.995  1020  1142 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:20.995  1020  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:20.995  1020  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.015  1020  1527 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.015  1020  1527 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:21.015  1020  1527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.025  4796  4796 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,03-16 14:31:21.035  1020  1759 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.035  1020  1759 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:21.035  1020  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.035  1843  1843 D WearableService: callingUid 10011, callindPid: 1843
,03-16 14:31:21.035  4693  4793 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,03-16 14:31:21.045  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.055  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:21.055  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.055  1020  1141 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.055  1020  1141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:21.055  1020  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.065  1843  4813 E MDM     : [228] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-16 14:31:21.065  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.065  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:21.065  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 14:31:21.065  4796  4796 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,03-16 14:31:21.065  4796  4796 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,03-16 14:31:21.075  4796  4796 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,03-16 14:31:21.075  4796  4796 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,03-16 14:31:21.075  4796  4796 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
03-16 14:31:21.075  4796  4796 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
03-16 14:31:21.075  4796  4796 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
03-16 14:31:21.075  4796  4796 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
03-16 14:31:21.075  4796  4796 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
03-16 14:31:21.075  4796  4796 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,03-16 14:31:21.085  2134  4814 D LocationInitializer: Restart initialization of location
,03-16 14:31:21.085  4796  4796 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,03-16 14:31:21.085  4796  4796 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
03-16 14:31:21.085  1020  1759 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:21.085  1020  1759 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:21.085  1020  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 14:31:21.085  4796  4796 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,03-16 14:31:21.085  1020  1520 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.085  1020  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:21.085  1020  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.095  1020  1527 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.095  1020  1527 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:21.095  1020  1527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.115  1020  1396 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.115  1020  1396 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:21.115  1020  1396 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.135  1020  1044 W libprocessgroup: failed to open /acct/uid_10026/pid_4129/cgroup.procs: No such file or directory
,03-16 14:31:21.145  1458  1753 D TP/SmsProvider: query,matched:0, calling pid = 2134
,03-16 14:31:21.145  1458  1753 D TP/SmsProvider: match 0:Elapsed time : 2.258 ms
,03-16 14:31:21.155  1020  1396 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.155  1020  1396 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:21.155  1020  1396 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.175  1458  1477 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2134
,03-16 14:31:21.185  1458  1753 D TP/SmsProvider: query,matched:0, calling pid = 2134
,03-16 14:31:21.195  1458  1753 D TP/SmsProvider: match 0:Elapsed time : 2.382 ms
,03-16 14:31:21.205  1458  1477 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2134
,03-16 14:31:21.315  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.315  1020  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:21.315  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.335  1843  1843 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-16 14:31:21.345  1843  1843 D a       : Opening database auth.proximity.permit_store...
,03-16 14:31:21.345  1020  1520 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.345  1020  1520 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:21.345  1020  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.355  3299  3630 W jxcore-log: Platform android
03-16 14:31:21.355  3299  3630 W jxcore-log: 
,03-16 14:31:21.355  3299  3630 W jxcore-log: Process ARCH arm
03-16 14:31:21.355  3299  3630 W jxcore-log: 
,03-16 14:31:21.365  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.365  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:21.365  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.395  1020  1525 I art     : Explicit concurrent mark sweep GC freed 16919(919KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/33MB, paused 6.005ms total 155.814ms
,03-16 14:31:21.415  2134  4819 W IcingInternalCorpora: getNumBytesRead when not calculated.
,03-16 14:31:21.425  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:21.425  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:21.425  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.435  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:21.435  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:21.435  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.445  1020  1525 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:21.445  1020  1525 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:21.445  1020  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.445  1843  1843 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 14:31:21.455  1020  1527 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.455  1020  1527 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:21.455  1020  1527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.465  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.465  1020  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:21.465  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.465  3455  3455 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
,03-16 14:31:21.475  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:21.475  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:21.475  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:21.475  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.475  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:21.475  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:21.475  3455  4833 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,03-16 14:31:21.485  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.485  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:21.485  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:21.485  1843  2155 W GCoreFlp: No location to return for getLastLocation()
03-16 14:31:21.485  1843  4826 W FusedLocationProvider: location=null
,03-16 14:31:21.485  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.485  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:21.495  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:21.495  3455  4833 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-16 14:31:21.495  3455  4833 I ReactiveServiceManager: Supported : 1
,03-16 14:31:21.495  1020  1525 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
03-16 14:31:21.495  1020  1525 D QSEECOMAPI: : App is not loaded in QSEE
,03-16 14:31:21.495  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:21.495  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:21.495  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:21.505  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:21.505  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:21.505  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:21.515  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:21.515  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:21.515  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-16 14:31:21.515  1020  1525 D QSEECOMAPI: : Loaded image: APP id = 10
,03-16 14:31:21.515  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:21.515  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:21.515  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:21.515  1020  1525 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-16 14:31:21.515  1020  1525 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 10
,03-16 14:31:21.515  1020  1525 E terrier : handleString: Failed to handle string(-4)
03-16 14:31:21.515  1020  1525 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,03-16 14:31:21.525  3455  4833 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-16 14:31:21.525  3455  4833 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
03-16 14:31:21.525  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:21.525  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:21.525  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:21.525  3455  4833 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-16 14:31:21.525  3455  4833 I PCWCLIENTTRACE_PushUtil: sales region : global
03-16 14:31:21.525  3455  4833 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-16 14:31:21.525  3455  4833 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,03-16 14:31:21.525  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:21.525  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:21.525  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:21.535  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:21.535  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:21.535  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:21.535  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.535  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:21.535  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:21.545  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:21.545  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:21.545  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:21.545  1020  1058 D PackageManager: [MSG] SEND_PENDING_BROADCAST
,03-16 14:31:21.545  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:21.545  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:21.545  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:21.545  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:21.545  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:21.545  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-16 14:31:21.555  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.555  1020  1020 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:21.555  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.585  1181  1181 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.PACKAGE_CHANGED
,03-16 14:31:21.585  1020  1103 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-16 14:31:21.595  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 14:31:21.595  1020  1525 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
03-16 14:31:21.595  1020  1525 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
03-16 14:31:21.595  1020  1525 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
03-16 14:31:21.595  1020  1525 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-16 14:31:21.605  1020  1525 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:21.605  1020  1525 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:21.605  1020  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.605  1458  1458 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 14:31:21.615  1020  1020 W IntentResolver: resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,03-16 14:31:21.615  4032  4032 I PageBuddyNotiSvc: mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,03-16 14:31:21.615  3299  3630 I jxcore-log: JXcore Cordova bridge is ready!
03-16 14:31:21.615  3299  3630 I jxcore-log: 
,03-16 14:31:21.625  3299  3630 W jxcore-log: JXcore engine is started
,03-16 14:31:21.625  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:31:21.625  3299  3592 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-16 14:31:21.625  1442  1442 D RegisteredServicesCache: empty dynamic service
03-16 14:31:21.625  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:21.625  1020  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:21.625  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.625  3299  3299 I chromium: [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,03-16 14:31:21.645  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.645  1020  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:21.645  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.655  1843  4835 E MDM     : [243] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-16 14:31:21.665  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.665  1020  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:21.665  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.675  1020  1396 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.675  1020  1396 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:21.675  1020  1396 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.685  1020  1759 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.685  1020  1032 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-16 14:31:21.685  1020  1759 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:21.685  1020  1032 D SecContentProvider2: mCursor = null
,03-16 14:31:21.685  1020  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.705  1020  1527 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.705  1020  1527 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:21.705  1020  1527 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.705  2134  4837 D LocationInitializer: Restart initialization of location
,03-16 14:31:21.705  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:31:21.705  1020  1759 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:21.705  1020  1759 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:21.705  1020  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.715  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.715  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:21.715  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.715  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:31:21.725  1020  1759 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.725  1020  1759 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:21.725  1020  1759 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.735  1843  1843 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-16 14:31:21.745  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.745  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:21.745  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.755  1020  1396 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.755  1020  1396 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:21.755  1020  1396 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.765  1020  1521 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.765  1020  1521 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:21.765  1020  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.765  1843  1843 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 14:31:21.765  1843  2155 W GCoreFlp: No location to return for getLastLocation()
,03-16 14:31:21.765  1843  4838 W FusedLocationProvider: location=null
,03-16 14:31:21.765  1020  1141 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.775  1020  1141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:21.775  1020  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.775  1020  1142 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.785  1020  1142 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-16 14:31:21.785  1020  1142 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.785  1020  1519 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.785  1020  1519 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 14:31:21.785  1020  1519 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-16 14:31:21.805  1020  1521 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:21.805  1020  1521 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:21.805  1020  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-16 14:31:21.815  1020  1045 I ActivityManager: Waited long enough for: ServiceRecord{f405531 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,03-16 14:31:21.815  1020  1396 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:21.815  1020  1396 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-16 14:31:21.815  1020  1396 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:21.855  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:21.855  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:21.855  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:21.855  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:21.865  1020  1044 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75),
,03-16 14:31:21.875  4842  4842 E Zygote  : MountEmulatedStorage(),
03-16 14:31:21.875  4842  4842 E Zygote  : v2
,03-16 14:31:21.875  4842  4842 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:21.875  4842  4842 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:21.875  4842  4842 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:31:21.875  1020  1032 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4842 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 14:31:21.875  4842  4842 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:21.885  4842  4842 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:21.885  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,03-16 14:31:21.885  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:31:21.895  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:31:21.895  1020  1044 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-16 14:31:21.905  1020  1020 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
03-16 14:31:21.905  1020  1020 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-16 14:31:21.905  1020  1020 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-16 14:31:21.905  1020  1044 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
03-16 14:31:21.905  1020  1044 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 14:31:21.915  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:31:21.915  4842  4842 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:21.915  4842  4842 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:21.925  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:31:21.925  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:31:21.925  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 14:31:21.925  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-16 14:31:21.935  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:31:21.935  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 14:31:21.935  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-16 14:31:21.945  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 14:31:21.945  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-16 14:31:21.945  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:31:21.955  1020  1020 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-16 14:31:21.955  1020  1020 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@90c1f96
,03-16 14:31:21.965  4842  4842 E MTPRx   : In MtpReceiverandroid.hardware.usb.action.USB_STATE
,03-16 14:31:21.965  1020  1033 D SecContentProvider2: uri = 14 selection = getSealedState
03-16 14:31:21.965  1020  1033 D SecContentProvider2: mCursor = null
,03-16 14:31:21.965  1020  1396 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
,03-16 14:31:21.975  1020  1396 D SecContentProvider2: mCursor = null
,03-16 14:31:21.975  4842  4842 V MTPRx   : sealedState: false
,03-16 14:31:21.975  4842  4842 V MTPRx   : sealedUsbMassStorageState: false
03-16 14:31:21.975  4842  4842 E MTPRx   : check value of boot_completed is1,
03-16 14:31:21.975  4842  4842 E MTPRx   : check booting is completed_sys.boot_completed
,03-16 14:31:21.975  4842  4842 E MTPRx   : Sd-Card path/storage/extSdCard
,03-16 14:31:21.975  4842  4842 E MTPRx   : Status for mount/Unmount :removed
03-16 14:31:21.975  4842  4842 E MTPRx   : SDcard is not available
,03-16 14:31:21.975  4842  4842 W MTPRx   : value of connected istrue
03-16 14:31:21.975  4842  4842 W MTPRx   : value of configured istrue
03-16 14:31:21.975  4842  4842 W MTPRx   : value of mtpEnabled istrue
03-16 14:31:21.975  4842  4842 W MTPRx   : value of ptpEnabled isfalse
,03-16 14:31:21.985  4842  4842 E MTPRx   : Received USB_STATE with sdCardLaunch = 0
,03-16 14:31:21.985  4842  4842 E MTPRx   : mFirstTime: false
,03-16 14:31:22.005  4842  4842 D         : MTP: reading debug level property
,03-16 14:31:22.005  4842  4842 E MTPJNIInterface: Getting CryptionKey from JAVA
03-16 14:31:22.005  4842  4842 E MTPRx   : currentUserId is 0
,03-16 14:31:22.005  1843  1843 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,03-16 14:31:22.015  4693  4693 D Mms/Contact: performUpdate:widgetCount=0
,03-16 14:31:22.015  1020  1020 I ValidateNoPeople: mEvictionCount: 0
,03-16 14:31:22.015  4693  4693 D Mms/Contact: sContactsObserver.onChange(),selfUpdate=false
,03-16 14:31:22.015  4842  4842 E MTPRx   : Start observing USB_STATE_MATCH 
,03-16 14:31:22.015  4842  4842 E MTPRx   : cannot open file : /sys/class/android_usb/android0/bcdUSB
03-16 14:31:22.015  4842  4842 E MTPRx   : is_Privatemode is NOT 1
,03-16 14:31:22.025  4693  4859 D Mms/ContactsCache: [start]    invalidate() consume time = 1235.225937
,03-16 14:31:22.025  4693  4859 D Mms/ContactsCache: [end]    invalidate() consume time = 1.218438
,03-16 14:31:22.025  1020  1525 D SettingsProvider: name = boot_time_connected
,03-16 14:31:22.025  1020  1044 D LocationProviderProxy: applying state to connected service
,03-16 14:31:22.045  4842  4842 E MTPRx   : Sending NORMAL_BOOT to stack
03-16 14:31:22.045  4842  4842 E MTPJNIInterface: noti = 17
,03-16 14:31:22.045  1020  1142 D SettingsProvider: name = mtp_usb_conditions_met
,03-16 14:31:22.045  1020  1044 D LocationProviderProxy: applying state to connected service
,03-16 14:31:22.045  1020  1525 D SecContentProvider: uri = 18 selection = isUsbMediaPlayerAvailable
,03-16 14:31:22.045  4842  4842 E MTPRx   : sending MTP_ICON_ENABLED to stack
,03-16 14:31:22.055  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:22.055  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 14:31:22.055  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-16 14:31:22.065  1020  1352 D SettingsProvider: name = mtp_running_status
,03-16 14:31:22.075  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 14:31:22.075  1020  1491 D SettingsProvider: name = mtp_usb_conditions_met
,03-16 14:31:22.075  4842  4842 E MTPRx   : else part ... so first time!!!
,03-16 14:31:22.075  4842  4842 E MTPPlaObsrvr: inside setContext()
,03-16 14:31:22.075  4842  4842 E MTPPlaObsrvr:  inside createplafiles
,03-16 14:31:22.085  4842  4842 E MTPPlaObsrvr: playlist count is0
,03-16 14:31:22.085  4842  4842 E MTPPlaObsrvr:  inside try branch createplafiles
,03-16 14:31:22.085  4842  4842 E MTPPlaObsrvr:  inside deleteing plas createplafiles
,03-16 14:31:22.095  4842  4842 E MTPPlaObsrvr: Inside registerContentObserver
,03-16 14:31:22.095  4842  4842 E MtpAdbObserver: inside setContext()
,03-16 14:31:22.095  4842  4842 E MtpAdbObserver: Inside registerContentObserver
03-16 14:31:22.095  4842  4842 W Settings: Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,03-16 14:31:22.095  1020  1520 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:22.095  1020  1520 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 14:31:22.095  1020  1520 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-16 14:31:22.095  1020  1491 D SettingsProvider: name = mtp_running_status
,03-16 14:31:22.095  1020  1759 D SettingsProvider: name = mtp_usb_conditions_met
,03-16 14:31:22.105  4842  4842 E MtpService: onCreate.
,03-16 14:31:22.105  4842  4842 E MtpService: < MTP > Registering BroadCast receiver :::::
,03-16 14:31:22.105  4842  4862 V MtpMediaDBManager: inside deleteAllDB
,03-16 14:31:22.105  4842  4842 E MtpService: < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,03-16 14:31:22.105  1020  1521 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:22.105  1020  1521 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 14:31:22.105  1020  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-16 14:31:22.105  4842  4842 E MtpService: < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,03-16 14:31:22.115  4842  4842 E MtpService: onStartCommand.
,03-16 14:31:22.115  4842  4842 W MTPRx   : calling native method
03-16 14:31:22.115  4842  4842 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::
,03-16 14:31:22.115  4842  4863 E MtpService: handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,03-16 14:31:22.115  4842  4842 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::::
,03-16 14:31:22.115  4842  4842 E MTPJNIInterface: noti = 10
,03-16 14:31:22.115  1236  1236 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,03-16 14:31:22.115  4842  4842 W MTPRx   : calling native method
03-16 14:31:22.125  4842  4842 E MTPRx   : Checking the driver time out
03-16 14:31:22.125  4842  4842 E MTPJNIInterface: noti = 2
03-16 14:31:22.125  4842  4842 D         : deleting sockets before message queue initialization
,03-16 14:31:22.125  4842  4842 D         : event handler thread is created, so set the flag
,03-16 14:31:22.125  4842  4842 E MTPRx   : called native method
03-16 14:31:22.125  4842  4842 E MTPJNIInterface: setting Media scanner status0
03-16 14:31:22.125  4842  4842 E MTPJNIInterface: After setting Media scanner status0
03-16 14:31:22.125  4842  4842 E MtpService: onStartCommand.
,03-16 14:31:22.125  1020  1396 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:22.125  1020  1396 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-16 14:31:22.125  1020  1396 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-16 14:31:22.125  1020  1396 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:22.135  4842  4863 E MtpService: handleMessage. msg= { when=0 what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,03-16 14:31:22.135  4842  4862 V MtpMediaDBManager: inside Thread updateDB
,03-16 14:31:22.135  4842  4842 W MTPRx   : notification from stack 1
,03-16 14:31:22.135  4842  4864 E         : Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
03-16 14:31:22.135  4842  4864 E MTPJNIInterface: Getting media scanner status0
,03-16 14:31:22.135  4842  4864 E MTPJNIInterface: DeviceName is Thali Test (Galaxy A3)
,03-16 14:31:22.135  4865  4865 E Zygote  : MountEmulatedStorage()
03-16 14:31:22.135  4865  4865 E Zygote  : v2
03-16 14:31:22.135  4865  4865 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:22.135  4865  4865 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:22.145  4865  4865 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-16 14:31:22.145  4865  4865 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:31:22.145  1020  1396 I ActivityManager: Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4865 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-16 14:31:22.155  4865  4865 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-16 14:31:22.165  4842  4862 E MtpMediaDBManager: count : 26,
,03-16 14:31:22.185  4865  4865 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:22.185  4865  4865 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:22.215  4842  4862 W MtpMediaDBManager: sending db update complete noti to stack
03-16 14:31:22.215  4842  4862 E MTPJNIInterface: noti = 29
,03-16 14:31:22.225  4842  4864 E MTPJNIInterface: Status for mount/Unmount :removed
,03-16 14:31:22.225  4842  4864 E MTPJNIInterface: SDcard is not available
,03-16 14:31:22.285  4842  4864 E         : [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,03-16 14:31:22.295  4842  4864 E MTPJNIInterface: Status for mount/Unmount :removed
,03-16 14:31:22.295  4842  4864 E MTPJNIInterface: SDcard is not available
03-16 14:31:22.295  4842  4864 E SQLiteLog: (21) API call with NULL database connection pointer
03-16 14:31:22.295  4842  4864 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
03-16 14:31:22.295  4842  4864 E SQLiteLog: (21) API call with NULL database connection pointer
03-16 14:31:22.295  4842  4864 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-16 14:31:22.295  4842  4864 E SQLiteLog: (21) API call with NULL database connection pointer
03-16 14:31:22.295  4842  4864 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-16 14:31:22.295  4842  4864 E SQLiteLog: (21) API call with NULL database connection pointer
03-16 14:31:22.295  4842  4864 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
,03-16 14:31:22.295  4842  4842 W MTPRx   : notification from stack 2
,03-16 14:31:22.295  4842  4880 D         : [mtp_init_device] Library open with 32 bits.
,03-16 14:31:22.295  4842  4880 D         : [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,03-16 14:31:22.295  4842  4880 E         : [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
,03-16 14:31:22.295  4842  4880 D         : [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
03-16 14:31:22.295  4842  4880 E         :  [sua_support_present:1287] returning false 
,03-16 14:31:22.295  4842  4880 D         : [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,03-16 14:31:22.305  4865  4865 D TMNetworkReceiver: TMNetworkReceiver.TMNetworkReceiver() Enter 1 main
,03-16 14:31:22.305  4865  4865 D TMNetworkReceiver: TMNetworkReceiver.onReceive() Enter
,03-16 14:31:22.305  4865  4865 D TMNetworkReceiver: MirrorLink feauture level: using UEvent

```
