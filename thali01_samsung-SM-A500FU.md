#### Test 62754403d2f0346_thali01_samsung-SM-A500FU Logs


```
--------- beginning of system
03-17 13:26:05.812  1018  1388 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10085
--------- beginning of main
03-17 13:26:05.822  1367  1367 I WifiCredService: onCreate
03-17 13:26:05.822  1018  1043 W libprocessgroup: failed to open /acct/uid_10050/pid_2185/cgroup.procs: No such file or directory
03-17 13:26:05.832  1018  1018 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 13:26:05.842  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 13:26:05.842  1018  1043 D LocationProviderProxy: applying state to connected service
03-17 13:26:05.842  1018  1043 W libprocessgroup: failed to open /acct/uid_10113/pid_2248/cgroup.procs: No such file or directory
03-17 13:26:05.852  2643  2643 I FactoryTestApp: [IPCWriterToSecPhoneService$onServiceConnected](2643) connected done
03-17 13:26:05.852  2643  2643 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2643) Send Response Message to SecPhone
03-17 13:26:05.852  2643  2643 D FactoryTestApp: [IPCWriterToSecPhoneService$write](2643) Response ��
03-17 13:26:05.852  1843  1843 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
03-17 13:26:05.862  3150  3150 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:05.862  3150  3150 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:05.862   327  1076 D AT_Distributor: Send Msg [RIL > ATD] 19 bytes <BOOTING COMPLETED(\r)(\n)>
03-17 13:26:05.872  1467  1481 D TP/SmsProvider: query,matched:26, calling pid = 2336
03-17 13:26:05.882  1367  1367 D WifiTimerReceiver: action: android.intent.action.BOOT_COMPLETED
03-17 13:26:05.882  1367  1367 D WifiTimerReceiver: extra: Bundle[mParcelledData.dataSize=84]
03-17 13:26:05.882  1367  1367 D MY_TAG  : Action boot completed received
03-17 13:26:05.882  2643  2643 D FactoryTestApp: [IPCWriterToSecPhoneService$handleMessage](2643) Send BOOTING COMPLETED done
03-17 13:26:05.882  1018  2999 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
03-17 13:26:05.892  1367  1367 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
03-17 13:26:05.892  1018  1135 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
03-17 13:26:05.892  1018  1135 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-17 13:26:05.892  1018  1135 E WifiNative-wlan0: invaild command id : 215
03-17 13:26:05.892  1018  2999 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:05.892  1018  2999 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:05.892  1018  2999 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:05.892  1018  2999 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:05.892  3150  3150 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 13:26:05.902  3179  3179 E Zygote  : MountEmulatedStorage()
03-17 13:26:05.902  3179  3179 I libpersona: KNOX_SDCARD checking this for 10160
03-17 13:26:05.902  3179  3179 E Zygote  : v2
03-17 13:26:05.902  3179  3179 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:05.912  3179  3179 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 13:26:05.912  3179  3179 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:05.912  1018  2999 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3179 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
03-17 13:26:05.912  1467  1481 D TP/SmsProvider: match 26:Elapsed time : 34.993 ms
03-17 13:26:05.912  2661  2748 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
03-17 13:26:05.912  3119  3119 D BadgeProvider: onCreate
03-17 13:26:05.912  3119  3119 D BadgeProvider: DatabaseHelper
03-17 13:26:05.912  3179  3179 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:05.952  1018  1231 I ActivityManager: Killing 1631:com.google.android.partnersetup/u0a15 (adj 15): empty #31
03-17 13:26:05.962  3179  3179 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:05.962  3179  3179 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:05.962   327  1076 D AT_Distributor: SetAtdStatus(), 1_1_0
03-17 13:26:05.962   327  1076 D AT_Distributor: Send Msg [ATD > UART] 19 bytes <BOOTING COMPLETED(\r)(\n)>
03-17 13:26:05.972  2661  2748 D BluetoothMediaBrowser: no now playing list
03-17 13:26:05.972  2661  2748 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
03-17 13:26:05.972  3150  3150 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-17 13:26:05.982  2336  3093 D Mms/SmsReceiver: unregisterForServiceStateChanges, already unregistered
03-17 13:26:05.982  2336  3093 D Mms/MessagingNotification: sDisableVibrateForCamera = false
03-17 13:26:05.982  2336  3093 D Mms/TelephonyPermission: isDefault true
03-17 13:26:05.982  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-a500fu.dat
03-17 13:26:05.982  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=a5ulte.dat
03-17 13:26:05.992  1367  1367 D NearbySettings: MountReceiver.onReceive - Create HandlerThread
03-17 13:26:05.992  1367  1367 D NearbySettings: MountReceiver.onReceive - Start HandlerThread
03-17 13:26:05.992  1367  1367 D NearbySettings: MountReceiver.onReceive - Create mPrefHandler
03-17 13:26:05.992  3119  3140 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
03-17 13:26:05.992  1367  1367 D NearbySettings: MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
03-17 13:26:06.002  1367  3196 V NearbySettings: MountReceiver.mPrefHandler - 7002
03-17 13:26:06.012  3150  3150 I LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-a500fu.dat
03-17 13:26:06.012  1467  1722 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2336
03-17 13:26:06.012  1018  1152 D SettingsProvider: name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
03-17 13:26:06.012   305   305 E USB_UICC: Timeout! No signal received. Retry num = 30
03-17 13:26:06.022  3179  3179 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 13:26:06.022   331   331 I ServiceManager: Waiting for service AtCmdFwd...
03-17 13:26:06.022  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
03-17 13:26:06.052  1018  1043 W libprocessgroup: failed to open /acct/uid_10015/pid_1631/cgroup.procs: No such file or directory
03-17 13:26:06.052  1467  1481 D TP/MmsSmsProvider: query,matched:200, calling pid = 2336
03-17 13:26:06.052  1467  1481 D TP/MmsSmsProvider: match 200:Elapsed time : 2.025 ms
03-17 13:26:06.072  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
03-17 13:26:06.072  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
03-17 13:26:06.072  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
03-17 13:26:06.072  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
03-17 13:26:06.072  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
03-17 13:26:06.072  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
03-17 13:26:06.072  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
03-17 13:26:06.072  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
03-17 13:26:06.072  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
03-17 13:26:06.072  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
03-17 13:26:06.072  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
03-17 13:26:06.082  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=FAILHIST_VERSION
03-17 13:26:06.082  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
03-17 13:26:06.082  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
03-17 13:26:06.082  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
03-17 13:26:06.082  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
03-17 13:26:06.082  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
03-17 13:26:06.082  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
03-17 13:26:06.082  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
03-17 13:26:06.082  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_CHARGE_COUNT
03-17 13:26:06.082  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
03-17 13:26:06.082  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
03-17 13:26:06.082  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
03-17 13:26:06.082  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
03-17 13:26:06.082  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
03-17 13:26:06.082   406   406 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
03-17 13:26:06.082  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
03-17 13:26:06.082  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
03-17 13:26:06.082  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
03-17 13:26:06.082  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
03-17 13:26:06.082  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
03-17 13:26:06.082  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
03-17 13:26:06.082  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
03-17 13:26:06.082  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
03-17 13:26:06.082  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_BACK_RAWDATA
03-17 13:26:06.092  3150  3150 D LcdtestApp: [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=PATH_NOISE_TSK_RECENT_RAWDATA
03-17 13:26:06.092  3150  3150 I LcdtestApp: [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
03-17 13:26:06.092  1018  1483 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
03-17 13:26:06.092  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.092  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.092  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.092  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.102  3199  3199 E Zygote  : MountEmulatedStorage()
03-17 13:26:06.102  3199  3199 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:06.102  3199  3199 E Zygote  : v2
03-17 13:26:06.102  3199  3199 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:06.102  3199  3199 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 13:26:06.102  1018  1483 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3199 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 13:26:06.102  1018  1483 I ActivityManager: Killing 2319:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
03-17 13:26:06.112  3199  3199 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:06.112  3199  3199 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:06.122  3023  3023 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 244.892ms
03-17 13:26:06.122  3199  3199 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:06.132  3199  3199 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:06.142  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 13:26:06.152   305   305 E USB_UICC: Timeout! No signal received. Reach maximum retries!
03-17 13:26:06.152   305   305 E USB_UICC: usb_uicc_init_qmi failed ! 
03-17 13:26:06.152   305   305 I USB_UICC: usb_uicc_cleanup, signal received: 0x3 
03-17 13:26:06.152   305   305 I USB_UICC: usb_uicc_cleanup, Issuing QMI deinit ... 
03-17 13:26:06.152  1367  1367 I NearbySettings: MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
03-17 13:26:06.152  1367  1367 I NearbySettings: MountReceiver.onReceive - Internal Path
03-17 13:26:06.162  3119  3140 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-17 13:26:06.162  3119  3140 D BadgeProvider: sendNotify, [notify] : null
03-17 13:26:06.162  3119  3140 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 13:26:06.162  3119  3140 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 13:26:06.162  3119  3140 D BadgeProvider: update, [UpdateCount] : 1
03-17 13:26:06.162  1490  1490 D Launcher.Model: reloadBadges entered.
03-17 13:26:06.162  1018  2734 D SettingsProvider: name = personal_mode_enabled
03-17 13:26:06.172  2336  3041 D Mms/MessagingNotification: setBadgeCount(), count=0
03-17 13:26:06.172  1018  1099 V AlarmManager: waitForAlarm result :8
03-17 13:26:06.172  1018  1099 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 13:26:06.192  2978  3040 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
03-17 13:26:06.192  2978  3040 I SecureStorage: [INFO]: SPID(0x00000004)Skip using SecureStorageExceptionJNI
03-17 13:26:06.212  1018  3001 I ActivityManager: Killing 2354:com.sec.android.omc/1000 (adj 15): empty #31
03-17 13:26:06.212  2336  3216 D Mms/MessagingNotification: updateAllHistoryAsRead()
03-17 13:26:06.222  3194  3194 D AndroidRuntime: 
03-17 13:26:06.222  3194  3194 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 13:26:06.222  3194  3194 D AndroidRuntime: CheckJNI is OFF
03-17 13:26:06.222  3194  3194 D AndroidRuntime: readGMSProperty: start
03-17 13:26:06.222  3194  3194 D AndroidRuntime: readGMSProperty: already setted!!
03-17 13:26:06.222  3194  3194 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 13:26:06.222  3194  3194 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 13:26:06.222  3194  3194 D AndroidRuntime: readGMSProperty: end
03-17 13:26:06.222  3194  3194 D AndroidRuntime: addProductProperty: start
03-17 13:26:06.232  3179  3179 D [0]UMC:UMCContentProvider: @onCreate
03-17 13:26:06.242  3179  3179 D [0]UMC:Core: onCreate(): 
03-17 13:26:06.242  3179  3179 D [0]UMC:Core: @isManagedProfileUser
03-17 13:26:06.242  3179  3179 D [0]UMC:Core: userId: 0
03-17 13:26:06.242  3179  3179 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
03-17 13:26:06.242  3179  3179 D [0]UMC:Core: userInfo.isManagedProfile() : false
03-17 13:26:06.262  1467  1467 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-17 13:26:06.262  1467  1467 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 13:26:06.262  1467  1467 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 13:26:06.262  1467  1467 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:06.262  1467  1467 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:06.262  1467  1467 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-17 13:26:06.302  3199  3199 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
03-17 13:26:06.302  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 13:26:06.302  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:06.302  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:06.302  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:06.302  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:06.302  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:06.322  3179  3179 D [0]UMC:DeviceInfo: USA==US==
03-17 13:26:06.332  2336  3041 D Mms/MessagingNotification: remove alarm
03-17 13:26:06.362  3194  3194 E AffinityControl: AffinityControl: registerfunction enter
03-17 13:26:06.382  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2319/cgroup.procs: No such file or directory
03-17 13:26:06.382  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2354/cgroup.procs: No such file or directory
03-17 13:26:06.382  3194  3194 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 13:26:06.392  1467  1722 I art     : Explicit concurrent mark sweep GC freed 40657(2MB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 8MB/13MB, paused 959us total 329.288ms
03-17 13:26:06.402  1018  1152 E PersonaManagerService: inState():  stateMachine is null !!
03-17 13:26:06.402  1018  1152 I PersonaManagerService: PersonaId don't exist
03-17 13:26:06.402  1018  1152 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-17 13:26:06.402  1467  1722 D TP/SmsProvider: query,matched:0, calling pid = 2336
03-17 13:26:06.402  1467  1722 D TP/SmsProvider: match 0:Elapsed time : 1.105 ms
03-17 13:26:06.412  1367  1367 I SmartcardBootCompleteReceiver: SmartcardBootCompleteReceiver - onReceive() 
03-17 13:26:06.412  1367  1367 I SmartcardBootCompleteReceiver: Received intent with action - android.intent.action.BOOT_COMPLETED
03-17 13:26:06.412  1018  1152 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 13:26:06.422  1018  1152 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-17 13:26:06.422  1018  1152 W ActivityManager: mDVFSHelper.acquire()
03-17 13:26:06.432  1018  1152 D FocusedStackFrame: Set to : 0
03-17 13:26:06.432  1018  1152 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 13:26:06.432  1018  1152 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 13:26:06.432  1490  1490 D Launcher.HomeView: onPause
03-17 13:26:06.432  1018  1152 D InputDispatcher: Focused application set to: xxxx
03-17 13:26:06.432  1018  1152 D InputDispatcher: Focus left window: 1490
03-17 13:26:06.432  3194  3194 D AndroidRuntime: Shutting down VM
03-17 13:26:06.442  1490  1490 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-17 13:26:06.442  1018  1052 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 13:26:06.442  1018  1052 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-17 13:26:06.452  1018  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 13:26:06.452  1018  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 13:26:06.452  1018  1052 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 13:26:06.452  1018  1052 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 13:26:06.452   258   258 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-17 13:26:06.452  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.452  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.452  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.452  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.472  3232  3232 E Zygote  : MountEmulatedStorage()
03-17 13:26:06.472  3232  3232 E Zygote  : v2
03-17 13:26:06.472  3232  3232 I libpersona: KNOX_SDCARD checking this for 10155
03-17 13:26:06.472  3232  3232 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:06.472  3232  3232 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 13:26:06.472  1367  1367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
03-17 13:26:06.472  3232  3232 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:06.482  3232  3232 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 13:26:06.492  1018  3000 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3232 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 13:26:06.502  1018  1369 I ActivityManager: Killing 2385:com.sec.tcpdumpservice/1000 (adj 15): empty #31
03-17 13:26:06.512  1367  1367 I SmartcardBootCompleteReceiver: Broadcast sent with current lockscreen type
03-17 13:26:06.532  3232  3232 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:06.532  3232  3232 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:06.542  1018  1369 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 13:26:06.542  1018  1369 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 13:26:06.542  1018  1369 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 13:26:06.542  1018  1050 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 13:26:06.562  1018  1369 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:26:06.572  1467  1477 D TP/SmsProvider: query,matched:51, calling pid = 2336
03-17 13:26:06.572  1490  1490 V ActivityThread: updateVisibility : ActivityRecord{7d01bd6 token=android.os.BinderProxy@bd24560 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-17 13:26:06.572  1490  1490 D Launcher.HomeView: onStop
03-17 13:26:06.572  1490  1490 V ActivityThread: updateVisibility : ActivityRecord{7d01bd6 token=android.os.BinderProxy@bd24560 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-17 13:26:06.572  1467  1477 D TP/SmsProvider: match 51:Elapsed time : 29.723 ms
03-17 13:26:06.602  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2385/cgroup.procs: No such file or directory
03-17 13:26:06.612  1018  1483 I art     : Explicit concurrent mark sweep GC freed 134890(7MB) AllocSpace objects, 4(1814KB) LOS objects, 33% free, 26MB/39MB, paused 15.888ms total 273.454ms
03-17 13:26:06.612  1018  1152 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.colorblind, hostingType: broadcast
03-17 13:26:06.612  1018  1152 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.612  1018  1152 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.612  1018  1152 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.612  1018  1152 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.632  1490  1490 D Launcher: onTrimMemory. Level: 20
03-17 13:26:06.642  3251  3251 E Zygote  : MountEmulatedStorage()
03-17 13:26:06.642  3251  3251 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:06.642  3251  3251 E Zygote  : v2
03-17 13:26:06.642  3251  3251 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:06.642  3251  3251 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 13:26:06.642  3194  3194 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-17 13:26:06.642  3251  3251 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:06.642  3251  3251 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:06.652  1018  1152 I ActivityManager: Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3251 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 13:26:06.662  1367  1367 D [SBeam] : SBeamEnabler.initPreferenceForSbeam : 0
,03-17 13:26:06.662  1018  1152 I ActivityManager: Killing 2400:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,03-17 13:26:06.662  3199  3199 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-17 13:26:06.672  3251  3251 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:06.672  3251  3251 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:06.672  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,03-17 13:26:06.672  1018  1018 D SensorService: [SO] activate (ident=0xb8a1ca98, enabled=0)
03-17 13:26:06.672  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-17 13:26:06.682  3199  3199 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-17 13:26:06.682  1018  1018 D SensorManager: unregisterListener ::   
,03-17 13:26:06.682  1018  1018 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-17 13:26:06.682  1018  1018 D SensorService: [SO] changed settle time [1]
03-17 13:26:06.682  1018  1018 D SensorService: [SO] setDelay [66000000]
03-17 13:26:06.682  1018  1018 D SensorService: [SO] activate (ident=0xb8a050e8, enabled=1)
03-17 13:26:06.682  1018  1018 D SensorService: [SO] AR_init
03-17 13:26:06.682  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-17 13:26:06.692  3199  3199 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,03-17 13:26:06.692  1018  1018 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
03-17 13:26:06.692  3199  3199 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
,03-17 13:26:06.692  3199  3199 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
,03-17 13:26:06.692  3199  3199 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-17 13:26:06.702  1467  1722 D TP/SmsProvider: query,matched:0, calling pid = 2336
,03-17 13:26:06.702  1367  1367 I SettingSearch/SearchIntentReceiver: action : android.intent.action.BOOT_COMPLETED
03-17 13:26:06.702  1367  1367 I SettingSearch/SearchIntentReceiver: search setting db init!!
,03-17 13:26:06.702  1467  1722 D TP/SmsProvider: match 0:Elapsed time : 2.115 ms
,03-17 13:26:06.702  1367  1367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,03-17 13:26:06.712  2336  3041 D Mms/MessagingNotification: [end]    nonBlockingUpdateMessageIndicator() consume time = 1189.052292
,03-17 13:26:06.712  1367  3266 I SettingSearch/SearchIntentReceiver: BOOT_COMPLETED call InitSerachDBThread thread start!
,03-17 13:26:06.712  3251  3251 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 13:26:06.722  2336  3093 D Mms/MessagingNotification: isBlockingModeEnabled() = false, Zen mode = 0
,03-17 13:26:06.732  1018  1152 D ActivityManager: startProcessLocked calleePkgName: com.wssyncmldm, hostingType: broadcast
,03-17 13:26:06.742  1018  1152 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:06.742  1018  1152 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.742  1018  1152 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.742  1018  1152 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:06.742  3119  3140 D BadgeProvider: query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,03-17 13:26:06.752  3179  3179 D USER_AGENT: UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
,03-17 13:26:06.762  1018  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
03-17 13:26:06.762  3268  3268 E Zygote  : MountEmulatedStorage()
03-17 13:26:06.762  3268  3268 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:06.762  3268  3268 E Zygote  : v2
03-17 13:26:06.762  3268  3268 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:06.762  3268  3268 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:06.762  1018  1043 W libprocessgroup: failed to open /acct/uid_10131/pid_2400/cgroup.procs: No such file or directory
03-17 13:26:06.762  3232  3232 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-17 13:26:06.762  3268  3268 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:06.762  3268  3268 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-17 13:26:06.762  1018  1152 I ActivityManager: Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3268 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 13:26:06.782  3232  3232 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 7543-7544)
,03-17 13:26:06.782  3232  3232 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 13:26:06.782  2978  2978 E BluetoothHeadset: BTStateChangeCB is registed
,03-17 13:26:06.792  1490  1490 D Launcher.Model: reloadBadges entered.
,03-17 13:26:06.792  2978  2978 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,03-17 13:26:06.792  3119  3140 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/2
03-17 13:26:06.792  3119  3140 D BadgeProvider: sendNotify, [notify] : null
03-17 13:26:06.792  3119  3140 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/2
03-17 13:26:06.792  3119  3140 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 13:26:06.792  3119  3140 D BadgeProvider: update, [UpdateCount] : 1
,03-17 13:26:06.792  3268  3268 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:06.792  3268  3268 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:06.802  1018  3002 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
03-17 13:26:06.802  1018  3002 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,03-17 13:26:06.802  1018  3002 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:06.802  1018  3002 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:06.802  1018  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,03-17 13:26:06.802  3179  3179 D [0]UMC:AdminManager: init - start
,03-17 13:26:06.802  2978  2978 E BluetoothHeadset: BluetoothHeadset service is binded
,03-17 13:26:06.802  2978  2978 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,03-17 13:26:06.812  2336  3093 D Mms/MessagingNotification: setBadgeCount(), count=0
,03-17 13:26:06.812  1018  1483 D ActivityManager: getContentProviderImpl callerProcessName:com.android.settings, calleePkgName: com.sec.providers.settingsearch
,03-17 13:26:06.812  3232  3232 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {28ddd9ee}
,03-17 13:26:06.812  3232  3232 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 13:26:06.812  3232  3232 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,03-17 13:26:06.822  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.822  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.822  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.822  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:06.822  2336  3093 D Mms/MessagingNotification: remove alarm
,03-17 13:26:06.832  1018  1041 D SensorService: [SO] 0.153 0.402 10.132
03-17 13:26:06.832  1018  1041 D SensorService: [SO] [100 -> 255]
,03-17 13:26:06.832  3286  3286 E Zygote  : MountEmulatedStorage()
03-17 13:26:06.832  3286  3286 E Zygote  : v2
03-17 13:26:06.832  3286  3286 I libpersona: KNOX_SDCARD checking this for 10150
03-17 13:26:06.832  3286  3286 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:06.832  3286  3286 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 13:26:06.842  3286  3286 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:06.842  3286  3286 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 13:26:06.842  3179  3179 D [0]UMC:AdminManager: loadAdmins
03-17 13:26:06.842  1018  1483 I ActivityManager: Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3286 uid=10150 gids={50150, 9997} abi=armeabi-v7a
03-17 13:26:06.842  3268  3268 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:06.852  1018  1152 D ActivityManager: startProcessLocked calleePkgName: com.google.android.configupdater, hostingType: broadcast
03-17 13:26:06.852  1018  1152 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.852  1018  1152 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.852  1018  1152 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.852  1018  1152 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:06.862  3179  3179 D [0]UMC:AdminManager: init - end
,03-17 13:26:06.862  3179  3179 D GSLBManager: migrateStoredUrlFromOldPref
,03-17 13:26:06.862  3232  3232 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-17 13:26:06.862  3232  3232 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 13:26:06.872  3232  3232 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 13:26:06.872  3298  3298 E Zygote  : MountEmulatedStorage(),
03-17 13:26:06.872  3298  3298 I libpersona: KNOX_SDCARD checking this for 10086
03-17 13:26:06.872  3298  3298 E Zygote  : v2
03-17 13:26:06.872  3298  3298 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:06.872  3298  3298 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 13:26:06.872  1018  1152 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3298 uid=10086 gids={50086, 9997, 3003} abi=armeabi-v7a
03-17 13:26:06.872  3298  3298 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:06.872  3298  3298 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:06.882  1018  1485 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.policydm
,03-17 13:26:06.882  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.882  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.882  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:06.882  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:06.892  3319  3319 E Zygote  : MountEmulatedStorage()
03-17 13:26:06.892  3319  3319 E Zygote  : v2
03-17 13:26:06.892  3319  3319 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:06.892  3319  3319 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:06.902  3319  3319 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-17 13:26:06.902  1018  1485 I ActivityManager: Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3319 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 13:26:06.902  1018  1369 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
03-17 13:26:06.902  1018  1369 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,03-17 13:26:06.902  3319  3319 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:06.902  3286  3286 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:06.902  3286  3286 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:06.902  3319  3319 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:06.902  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:06.902  1018  1369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:06.902  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,03-17 13:26:06.912  3179  3179 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
,03-17 13:26:06.912  3298  3298 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:06.912  3298  3298 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:06.912  2336  3285 D Mms/MessagingNotification: updateAllHistoryAsRead()
,03-17 13:26:06.922  3232  3232 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
03-17 13:26:06.922  3179  3179 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
03-17 13:26:06.922  3232  3232 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,03-17 13:26:06.922  3232  3232 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,03-17 13:26:06.922  3232  3232 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 13:26:06.922  3232  3232 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 13:26:06.922  3232  3232 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 13:26:06.922  3232  3232 I Adreno-EGL: Local Branch: 
03-17 13:26:06.922  3232  3232 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 13:26:06.922  3232  3232 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 13:26:06.922  3232  3232 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 13:26:06.922  3179  3179 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-17 13:26:06.932  3179  3179 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
,03-17 13:26:06.932  3179  3179 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
,03-17 13:26:06.932  3179  3179 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 13:26:06.942  3319  3319 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:06.942  3319  3319 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:06.952  1018  1388 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-17 13:26:06.952   291   291 E SMD     : DCD OFF
,03-17 13:26:06.952  1467  1813 D TP/SmsProvider: query,matched:0, calling pid = 2336
,03-17 13:26:06.962  3179  3179 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
03-17 13:26:06.962  3179  3179 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 13:26:06.962  3179  3179 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-17 13:26:06.962  1467  1813 D TP/SmsProvider: match 0:Elapsed time : 5.004 ms
,03-17 13:26:06.962  3268  3268 I FOTA    : [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,03-17 13:26:06.972  1018  3001 D ActivityManager: startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
03-17 13:26:06.972  1018  3001 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,03-17 13:26:06.972  1018  3001 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:06.972  1018  3001 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:06.972  1018  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-17 13:26:06.982  3179  3179 D [0]UMC:GuardService: @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
03-17 13:26:06.982  1018  1369 I ActivityManager: Killing 2305:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-17 13:26:06.982  3179  3179 D [0]UMC:CoreReceiver: Intent : android.intent.action.BOOT_COMPLETED
03-17 13:26:06.982  3179  3179 D [0]UMC:CoreReceiver:  check PreETag 
,03-17 13:26:06.992  2336  3093 D Mms/SmsReceiverService: [end]    handleBootCompleted() consume time = 279.243697
,03-17 13:26:06.992  1018  3004 I ActivityManager: Killing 2438:com.wsomacp/u0a25 (adj 15): empty #31
,03-17 13:26:07.022   258   444 I SurfaceFlinger: id=8 Removed Mauncher (5/8)
,03-17 13:26:07.022   258  1841 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
,03-17 13:26:07.022   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:26:07.082  2978  2978 D BluetoothA2dp: Proxy object connected
,03-17 13:26:07.112  3179  3179 D [0]UMC:CoreReceiver: bulk enrolled package: null
,03-17 13:26:07.112  3179  3179 V [0]UMC:ProfileStorage: Enter loadList
03-17 13:26:07.112  3179  3179 D [0]UMC:CoreReceiver: handleAutoEnrollmentAndUMCAdminDeactivation
03-17 13:26:07.112  3179  3179 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
03-17 13:26:07.112  3179  3179 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,03-17 13:26:07.112  3179  3179 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
,03-17 13:26:07.112  3179  3179 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
,03-17 13:26:07.112  3179  3179 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 13:26:07.112  1018  2999 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,03-17 13:26:07.112  3179  3179 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
03-17 13:26:07.112  3179  3179 D [0]UMC:UMCAdmin: isContainer : 0
,03-17 13:26:07.112  3179  3179 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,03-17 13:26:07.132  3179  3179 D [0]UMC:ByodSetupStarter: Container ID : 0
,03-17 13:26:07.132  3179  3179 V [0]UMC:Utils: checkAppScreen() : com.test.thalitest
,03-17 13:26:07.132  3179  3179 I [0]UMC:Core: shutdown
,03-17 13:26:07.132  1018  1388 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,03-17 13:26:07.132  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2305/cgroup.procs: No such file or directory
03-17 13:26:07.132  1018  1043 W libprocessgroup: failed to open /acct/uid_10025/pid_2438/cgroup.procs: No such file or directory
,03-17 13:26:07.132  1018  1388 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:07.132  1018  1388 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:07.132  1018  1388 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,03-17 13:26:07.132  3179  3179 D [0]UMC:GuardService: @GuardService - stopService Result = true
,03-17 13:26:07.132  1018  1030 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,03-17 13:26:07.132  3179  3179 I art     : System.exit called, status: 0
03-17 13:26:07.132  3179  3179 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,03-17 13:26:07.142  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.142  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.142  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.142  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:07.152  3358  3358 E Zygote  : MountEmulatedStorage(),
,03-17 13:26:07.152  3358  3358 E Zygote  : v2
03-17 13:26:07.152  3358  3358 I libpersona: KNOX_SDCARD checking this for 10009
03-17 13:26:07.152  3358  3358 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:07.152  3358  3358 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:07.152  3358  3358 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:07.152  3358  3358 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-17 13:26:07.152  1018  1030 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3358 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:07.162  3319  3319 I DBG_POLICYDM: [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,03-17 13:26:07.172  3268  3268 I DBG_DM  : [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
,03-17 13:26:07.182  3298  3298 E UpdateRequestReceiver: ignoring update request
,03-17 13:26:07.182  3319  3319 I DBG_POLICYDM: [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
03-17 13:26:07.182  3358  3358 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:07.182  3358  3358 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:07.192  3298  3298 E UpdateRequestReceiver: ignoring update request
,03-17 13:26:07.192  3319  3319 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,03-17 13:26:07.202  3319  3360 I DBG_POLICYDM: [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,03-17 13:26:07.202  3319  3319 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-17 13:26:07.222  1018  1152 I ActivityManager: Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3179)(adj 0) has died(221,1048)
,03-17 13:26:07.222  3319  3319 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-17 13:26:07.222  3319  3319 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-17 13:26:07.222  3319  3319 I DBG_POLICYDM: [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,03-17 13:26:07.232  3319  3319 I DBG_POLICYDM: [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,03-17 13:26:07.232  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 13:26:07.232  3319  3319 I DBG_POLICYDM: [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,03-17 13:26:07.232  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 13:26:07.232  1317  1317 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 13:26:07.232  1317  1317 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 13:26:07.242  1317  1317 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-17 13:26:07.242  1317  1317 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,03-17 13:26:07.242  1317  1317 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,03-17 13:26:07.242  1317  1317 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,03-17 13:26:07.242  1317  1317 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,03-17 13:26:07.242  1317  1317 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,03-17 13:26:07.242  1317  1317 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,03-17 13:26:07.242  1317  1317 D daemonapp: [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
,03-17 13:26:07.252  1018  1231 D SettingsProvider: name = aw_daemon_service_key_version_check
03-17 13:26:07.252  1018  1231 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 13:26:07.252  1018  1231 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 13:26:07.252  1018  1231 D SettingsProvider: selectionArgs: false
03-17 13:26:07.252  1018  1231 D SettingsProvider: selectionArgs: 10162
03-17 13:26:07.252  1018  1231 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 13:26:07.252  1018  1231 D SettingsProvider: ret = -1
,03-17 13:26:07.252  3232  3343 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,03-17 13:26:07.262  3319  3360 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,03-17 13:26:07.272  3298  3298 E UpdateRequestReceiver: ignoring update request
,03-17 13:26:07.272  3268  3268 I DBG_DM  : [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
,03-17 13:26:07.272  1018  1231 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10162
,03-17 13:26:07.282  1317  1317 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 13:26:07.282  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-17 13:26:07.282  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:07.292  3298  3298 E UpdateRequestReceiver: ignoring update request
,03-17 13:26:07.292  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 13:26:07.292  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-17 13:26:07.292  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-17 13:26:07.292  1317  1317 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 13:26:07.302  3298  3298 E UpdateRequestReceiver: ignoring update request
,03-17 13:26:07.302  1317  1317 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-17 13:26:07.302  1317  1317 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 13:26:07.302  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1458217567313
,03-17 13:26:07.302  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1458239160000
,03-17 13:26:07.302  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
03-17 13:26:07.302  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
,03-17 13:26:07.312  3319  3360 I DBG_POLICYDM: [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,03-17 13:26:07.312  1317  1317 D daemonapp: [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1458239160000
,03-17 13:26:07.312  3232  3232 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 13:26:07.312  3268  3268 I DBG_DM  : [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
,03-17 13:26:07.312  3298  3298 E UpdateRequestReceiver: ignoring update request
,03-17 13:26:07.312  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.dropbox.android, hostingType: broadcast
,03-17 13:26:07.312  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.312  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.312  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.312  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:07.322  1317  1317 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 10
,03-17 13:26:07.322  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1458239160000
,03-17 13:26:07.332  3393  3393 E Zygote  : MountEmulatedStorage()
03-17 13:26:07.332  3393  3393 I libpersona: KNOX_SDCARD checking this for 10092
03-17 13:26:07.332  3393  3393 E Zygote  : v2
03-17 13:26:07.332  3393  3393 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:07.332  3393  3393 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:07.332  3393  3393 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:07.332  3393  3393 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 13:26:07.342  1018  1030 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3393 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 13:26:07.352  3232  3232 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 13:26:07.362   315   315 I art     : Explicit concurrent mark sweep GC freed 8743(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 651us total 20.665ms
,03-17 13:26:07.362  3232  3232 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 13:26:07.362  3232  3232 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-17 13:26:07.372  3232  3232 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-17 13:26:07.382   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 659us total 17.036ms
,03-17 13:26:07.392  3393  3393 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:07.392  3393  3393 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:07.392  3232  3232 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 13:26:07.392  3232  3232 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 13:26:07.392   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 16.655ms
,03-17 13:26:07.432  1317  1317 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
03-17 13:26:07.432  1317  1317 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-17 13:26:07.432  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.google.android.youtube, hostingType: broadcast
,03-17 13:26:07.432  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:07.432  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.432  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.432  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:07.442  3268  3268 I DBG_DM  : [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,03-17 13:26:07.442  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
,03-17 13:26:07.442  3268  3268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
,03-17 13:26:07.452  3412  3412 E Zygote  : MountEmulatedStorage(),
03-17 13:26:07.452  3412  3412 E Zygote  : v2
03-17 13:26:07.452  3412  3412 I libpersona: KNOX_SDCARD checking this for 10166
03-17 13:26:07.452  3412  3412 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:07.452  3412  3412 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 13:26:07.452  1018  1030 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3412 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 13:26:07.452  1018  1388 D ActivityManager: startService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm
03-17 13:26:07.452  1018  1388 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
03-17 13:26:07.452  3412  3412 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:07.462  1018  1388 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:07.462  1018  1388 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:07.462  1018  1388 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 13:26:07.462  3412  3412 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 13:26:07.462  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
,03-17 13:26:07.462  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
03-17 13:26:07.462  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
,03-17 13:26:07.472  1191  1191 D OverheatReceiver: onReceive() getAction : android.intent.action.BOOT_COMPLETED
03-17 13:26:07.472  1191  1191 D OverheatReceiver: into the SAFE_MODE_ACTION
03-17 13:26:07.472  1191  1191 D OverheatReceiver: VZW on -> change to Global UX [safe mode]
03-17 13:26:07.472  1191  1191 D OverheatReceiver: isSafeMode = false
,03-17 13:26:07.472  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
,03-17 13:26:07.472  3268  3268 I DBG_DM  : [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,03-17 13:26:07.482  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
,03-17 13:26:07.482  3268  3268 I DBG_DM  : [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
03-17 13:26:07.482  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
03-17 13:26:07.482  3268  3268 I DBG_DM  : [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
,03-17 13:26:07.492  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
03-17 13:26:07.492  1467  1467 D BootupListener: intent.getAction() = android.intent.action.BOOT_COMPLETED
03-17 13:26:07.492  1018  1031 D SettingsProvider: name = internet_call_settings_visibility
03-17 13:26:07.492  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 13:26:07.492  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 13:26:07.492  1018  1031 D SettingsProvider: selectionArgs: false
03-17 13:26:07.492  1018  1031 D SettingsProvider: selectionArgs: 1001
03-17 13:26:07.492  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 13:26:07.492  1018  1031 D SettingsProvider: ret = -1
03-17 13:26:07.492  3268  3268 I DBG_DM  : [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
03-17 13:26:07.492  1467  1467 D PhoneUtilsCommon: isSupportVoLTE is false.
,03-17 13:26:07.492  3268  3373 I DBG_DM  : [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
03-17 13:26:07.492  3268  3268 I DBG_DM  : [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
,03-17 13:26:07.502  3319  3360 I DBG_POLICYDM: [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-17 13:26:07.502  3412  3412 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:07.502  3319  3360 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
03-17 13:26:07.502  3412  3412 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:07.502  1441  1441 I Telecom : InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
,03-17 13:26:07.502  1018  3004 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: android.telecom.InCallService
03-17 13:26:07.502  1018  3004 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.InCallServiceImpl; callingUser = 0; userId(target) = -2
,03-17 13:26:07.512  1018  3004 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:07.512  1018  3004 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:07.512  1018  3004 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
,03-17 13:26:07.512  3268  3268 I DBG_DM  : [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,03-17 13:26:07.512  3268  3373 I DBG_DM  : [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
,03-17 13:26:07.512  3268  3373 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
,03-17 13:26:07.512  1018  3000 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.incallui, action: com.samsung.incallui.SEC_IN_CALL_SERVICE
03-17 13:26:07.512  1018  3000 D ActivityManager: retrieveServiceLocked(): component = com.android.incallui/com.android.incallui.SecInCallService; callingUser = 0; userId(target) = -2
,03-17 13:26:07.512  3268  3268 I DBG_DM  : [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
,03-17 13:26:07.522  1018  3000 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:07.522  1018  3000 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:07.522  1018  3000 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
03-17 13:26:07.522  3268  3268 I DBG_DM  : [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
,03-17 13:26:07.522  3319  3360 I DBG_POLICYDM: [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,03-17 13:26:07.522  1018  3001 D ActivityManager: bindService callerProcessName:com.wssyncmldm, calleePkgName: com.wssyncmldm, action: null
03-17 13:26:07.522  1018  3001 D ActivityManager: retrieveServiceLocked(): component = com.wssyncmldm/com.wssyncmldm.XDMService; callingUser = 0; userId(target) = 0
03-17 13:26:07.522  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
,03-17 13:26:07.522  1018  3001 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:07.522  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
,03-17 13:26:07.522  1018  3001 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:07.522  1018  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 13:26:07.522  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMService(155/onStartCommand)] 
03-17 13:26:07.522  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.fmm.dm, hostingType: broadcast
03-17 13:26:07.522  3319  3360 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,03-17 13:26:07.522  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:07.532  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.532  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.532  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.532  3319  3360 I DBG_POLICYDM: [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,03-17 13:26:07.542  3432  3432 E Zygote  : MountEmulatedStorage()
03-17 13:26:07.542  3432  3432 E Zygote  : v2
03-17 13:26:07.542  3432  3432 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:07.542  3432  3432 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:07.542  3432  3432 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:07.542  1018  1030 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3432 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 13:26:07.542  1018  1030 I ActivityManager: Killing 2523:com.sec.android.app.camera/u0a139 (adj 15): empty #31
03-17 13:26:07.552  1018  1030 I ActivityManager: Killing 2489:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #32
03-17 13:26:07.552  1018  1030 I ActivityManager: Killing 2477:com.sec.android.widgetapp.digitalclock/u0a88 (adj 15): empty #33
,03-17 13:26:07.552  3432  3432 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:07.552  3432  3432 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:07.552  1018  2999 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 13:26:07.552  1018  2999 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:07.552  1018  2999 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:07.552  1018  2999 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.gms
,03-17 13:26:07.552  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,03-17 13:26:07.552  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:07.552  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.552  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.552  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:07.572  3432  3432 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:07.572  3432  3432 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:07.582  3449  3449 E Zygote  : MountEmulatedStorage()
,03-17 13:26:07.582  3449  3449 E Zygote  : v2
03-17 13:26:07.582  3449  3449 I libpersona: KNOX_SDCARD checking this for 10057
03-17 13:26:07.582  3449  3449 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:07.582  3449  3449 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 13:26:07.582  1018  1030 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3449 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
03-17 13:26:07.582  3449  3449 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:07.582  3449  3449 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:07.602  3232  3462 D OpenGLRenderer: Render dirty regions requested: true
,03-17 13:26:07.602  3268  3268 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-17 13:26:07.602  1018  1152 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 13:26:07.602  1018  1152 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 13:26:07.602  1018  1152 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-17 13:26:07.602  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 13:26:07.602  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 13:26:07.612  1018  3004 I ActivityManager: Killing 2554:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,03-17 13:26:07.612  3449  3449 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:07.612  3232  3232 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 13:26:07.612  3232  3232 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 13:26:07.612  3449  3449 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:07.622  3319  3360 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,03-17 13:26:07.622   258   258 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,03-17 13:26:07.642  3319  3360 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-17 13:26:07.642  3268  3373 I DBG_DM  : [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,03-17 13:26:07.642  1018  3000 D InputDispatcher: Focus entered window: 3232
,03-17 13:26:07.652  1018  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 13:26:07.652  1018  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 13:26:07.652  3232  3232 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 13:26:07.652  3232  3462 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 13:26:07.662  3232  3462 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-17 13:26:07.662  3232  3462 D OpenGLRenderer: Enabling debug mode 0
,03-17 13:26:07.662  3319  3360 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-17 13:26:07.662  3319  3360 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,03-17 13:26:07.662  3319  3360 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,03-17 13:26:07.672  3319  3362 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-17 13:26:07.672  3319  3362 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 13:26:07.672  3319  3360 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/03/18/16:12:11
,03-17 13:26:07.672  3319  3360 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/03/17/13:26:07
,03-17 13:26:07.682  3319  3362 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 13:26:07.682  1018  1043 W libprocessgroup: failed to open /acct/uid_10142/pid_2489/cgroup.procs: No such file or directory
,03-17 13:26:07.682  3319  3360 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
03-17 13:26:07.682  1018  1043 W libprocessgroup: failed to open /acct/uid_10088/pid_2477/cgroup.procs: No such file or directory
03-17 13:26:07.682  1018  1043 W libprocessgroup: failed to open /acct/uid_10139/pid_2523/cgroup.procs: No such file or directory
,03-17 13:26:07.682  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2554/cgroup.procs: No such file or directory
,03-17 13:26:07.682  3319  3362 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-17 13:26:07.692  3319  3360 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,03-17 13:26:07.692  3432  3432 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
03-17 13:26:07.692  3319  3362 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-17 13:26:07.692  3319  3362 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-17 13:26:07.692  3319  3362 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-17 13:26:07.692  3319  3362 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,03-17 13:26:07.692  3319  3362 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,03-17 13:26:07.702  3319  3362 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-17 13:26:07.702  3432  3432 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,03-17 13:26:07.702  3432  3432 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-17 13:26:07.702  3432  3432 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=,
,03-17 13:26:07.712  3319  3360 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,03-17 13:26:07.732  3268  3268 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
,03-17 13:26:07.732  1441  1441 I Telecom : InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
,03-17 13:26:07.762  1018  1231 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:07.772  1018  1231 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:07.772  1018  1231 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:07.772  1018  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:07.782  1018  1030 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 13:26:07.792  1018  3468 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:26:07.792  1191  1191 I StatusBar: Icon Only
03-17 13:26:07.792  1191  1191 D PanelView: There is/are notification(s) 
,03-17 13:26:07.802  1018  1052 I ActivityManager: Displayed Component not be shown by security: +1s349ms
,03-17 13:26:07.802  3232  3232 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@b6bde9b time:38562
,03-17 13:26:07.802  1018  1052 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 13:26:07.802  1018  1052 W ActivityManager: mDVFSHelper.release()
,03-17 13:26:07.802  1018  1044 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 13:26:07.802  1018  1052 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2bd814ec u0 com.test.thalitest/.MainActivity t12} time:38566
,03-17 13:26:07.812  1777  1777 I SamsungIME: getCurrentCandidateView
,03-17 13:26:07.842  1018  3000 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.partnersetup
,03-17 13:26:07.842  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:07.842  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.842  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.842  2147  2147 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
03-17 13:26:07.842  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.842  2147  2147 I dhcpcd  : wlan0: no IPv6 Routers available
,03-17 13:26:07.862  3472  3472 E Zygote  : MountEmulatedStorage()
03-17 13:26:07.862  3472  3472 E Zygote  : v2
03-17 13:26:07.862  3472  3472 I libpersona: KNOX_SDCARD checking this for 10015
03-17 13:26:07.862  3472  3472 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:07.862  3472  3472 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 13:26:07.862  1018  3000 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3472 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,03-17 13:26:07.862  3319  3362 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-17 13:26:07.862  3472  3472 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:07.862  1018  1505 D ActivityManager: getContentProviderImpl callerProcessName:com.fmm.dm, calleePkgName: com.sec.pcw.device
03-17 13:26:07.862  3472  3472 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 13:26:07.872  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.872  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.872  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:07.872  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:07.872  1018  1030 D LocationManagerService: getProviders()=[passive]
,03-17 13:26:07.892  3490  3490 E Zygote  : MountEmulatedStorage()
03-17 13:26:07.892  3490  3490 E Zygote  : v2
03-17 13:26:07.892  3490  3490 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:07.892  3490  3490 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:07.892  3490  3490 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:07.892  3472  3472 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:07.892  3472  3472 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:07.892  1018  1505 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3490 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 13:26:07.892  3490  3490 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:07.892  3490  3490 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 13:26:07.922  3490  3490 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:07.922  3490  3490 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:07.932  1018  2749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.cB:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-17 13:26:07.982  3490  3490 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,03-17 13:26:07.982  3490  3490 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-17 13:26:07.992  3490  3490 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-17 13:26:08.002   258  1040 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
03-17 13:26:08.002  1018  3004 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
03-17 13:26:08.002  1018  3004 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
,03-17 13:26:08.002   258  1841 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
03-17 13:26:08.002  1018  3004 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:08.002  1018  3004 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:08.002  1018  3004 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-17 13:26:08.002  3490  3499 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 13:26:08.002  1018  3001 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
03-17 13:26:08.002  1018  3001 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,03-17 13:26:08.012  1018  3001 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:08.012  1018  3001 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:08.012  1018  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-17 13:26:08.022  1018  2734 I ActivityManager: Killing 2610:com.example.hello/u0a174 (adj 15): empty #31
,03-17 13:26:08.022   331   331 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-17 13:26:08.032  3432  3432 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-17 13:26:08.032  3449  3514 W TRThreadPoolExecutor: Task "NotifyOnDoneFutureTask[refresh_auth_tokens]" is a x. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-17 13:26:08.032  3432  3432 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 13:26:08.032  3432  3432 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-17 13:26:08.032  1018  1505 D ActivityManager: startProcessLocked calleePkgName: com.fmm.ds, hostingType: broadcast
,03-17 13:26:08.042  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.042  3449  3515 W TRThreadPoolExecutor: Task "p[Get token]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-17 13:26:08.042  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.042  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.042  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.052  3517  3517 E Zygote  : MountEmulatedStorage(),
03-17 13:26:08.052  3517  3517 E Zygote  : v2
03-17 13:26:08.052  3517  3517 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:08.052  3517  3517 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:08.052  1018  1505 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3517 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 13:26:08.062  1018  1505 I ActivityManager: Killing 2681:com.android.keychain/1000 (adj 15): empty #31
,03-17 13:26:08.062  1018  1505 I ActivityManager: Killing 2570:com.android.calendar/u0a135 (adj 15): empty #32
03-17 13:26:08.062  1018  2999 D ActivityManager: bindService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.gms, action: null
03-17 13:26:08.062  1018  2999 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-17 13:26:08.062  1018  2999 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:08.062  1018  2999 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:08.062  1018  2999 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-17 13:26:08.082  3517  3517 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:08.082  3517  3517 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:08.092  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast,
,03-17 13:26:08.092  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.092  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.092  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.092  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.092  3517  3517 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:08.102  3528  3528 E Zygote  : MountEmulatedStorage()
03-17 13:26:08.102  3528  3528 E Zygote  : v2
03-17 13:26:08.102  3528  3528 I libpersona: KNOX_SDCARD checking this for 10003
03-17 13:26:08.102  3528  3528 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:08.112  3528  3528 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:08.112  3319  3362 I DBG_POLICYDM: [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,03-17 13:26:08.112  1018  1018 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3528 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a,
03-17 13:26:08.112  3528  3528 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:08.112  1018  1018 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
03-17 13:26:08.112  3528  3528 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:08.112  1018  1485 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:08.122  1018  1485 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:08.122  1018  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:08.122  1018  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:08.122  3517  3517 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:08.122  3517  3517 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:08.142  3528  3528 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:08.142  3528  3528 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:08.152  1018  1043 W libprocessgroup: failed to open /acct/uid_10174/pid_2610/cgroup.procs: No such file or directory
03-17 13:26:08.152  1018  1043 W libprocessgroup: failed to open /acct/uid_10135/pid_2570/cgroup.procs: No such file or directory
03-17 13:26:08.152  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2681/cgroup.procs: No such file or directory
,03-17 13:26:08.182  3528  3528 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-17 13:26:08.232  3517  3517 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-17 13:26:08.242  3517  3517 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,03-17 13:26:08.262  3490  3499 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-17 13:26:08.272  3517  3517 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-17 13:26:08.272  3517  3517 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-17 13:26:08.322   286   841 V audio_hw_primary: adev_get_parameters: enter: keys - call_forwarding
03-17 13:26:08.322   286   841 D audio_hw_extn: audio_extn_get_parameters: returns 
03-17 13:26:08.322   286   841 V msm8974_platform: platform_get_parameters: exit: returns - 
03-17 13:26:08.322   286   841 V audio_hw_primary: adev_get_parameters: exit: returns - call_forwarding=false
03-17 13:26:08.322   286   841 I str_params: key: 'call_forwarding' value: ''
,03-17 13:26:08.322  1976  1976 V InCall  : ProximitySensor -  - screenonImmediately: false
03-17 13:26:08.322  1976  1976 V InCall  : ProximitySensor -  - mFromRcsShare: false
03-17 13:26:08.322  3528  3528 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-17 13:26:08.322  3528  3528 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-17 13:26:08.322  3528  3528 D UserAnalysis: Create SecureDbHelper
,03-17 13:26:08.322  1976  1976 I InCall  : ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
,03-17 13:26:08.332  1976  1976 D ScoverManager: serviceVersion : 16908288
03-17 13:26:08.332  1018  2999 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 13:26:08.332  1976  1976 D InCall  : InCallUtils - isCoverClosed false
,03-17 13:26:08.332  1441  1441 I Telecom : ProximitySensorManager: Proximity wake lock already released
,03-17 13:26:08.332  1018  1505 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 13:26:08.332  1976  1976 D InCall  : InCallUtils - isCoverClosed false
,03-17 13:26:08.332  1976  1976 I InCall  : InCallPresenter -  - InCallState = NO_CALLS
,03-17 13:26:08.332  3412  3549 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 13:26:08.332  3412  3549 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 13:26:08.332  1976  1976 I InCall  : InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
,03-17 13:26:08.332  1976  1976 D InCall  : InCallPresenter -  - dismissCoverDialog()...
,03-17 13:26:08.342  3528  3528 D IntelligenceServiceApplication: onCreate()
,03-17 13:26:08.342  3528  3528 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,03-17 13:26:08.342  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,03-17 13:26:08.342  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.342  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.342  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.342  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.342  1976  1976 I InCall  : CallSContextMotion - stopPutDownListening
,03-17 13:26:08.352  1976  1976 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
,03-17 13:26:08.352  1191  1191 D PhoneStatusBarView: setCallBackground:0
,03-17 13:26:08.362  3551  3551 E Zygote  : MountEmulatedStorage()
,03-17 13:26:08.362  3551  3551 E Zygote  : v2
03-17 13:26:08.362  3551  3551 I libpersona: KNOX_SDCARD checking this for 10060
03-17 13:26:08.362  3551  3551 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:08.362  3551  3551 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:08.362  1018  1031 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3551 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 13:26:08.362  3551  3551 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:08.362  3551  3551 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:08.362  3412  3549 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 13:26:08.372  1018  1505 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 13:26:08.372  1976  1976 D InCall  : InCallUtils - isCoverClosed false
03-17 13:26:08.382  1018  2828 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-17 13:26:08.382  3551  3551 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:08.382  3551  3551 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:08.402  1777  1777 D SamsungIME: Dismiss ExpandCandiate
,03-17 13:26:08.412  1018  3004 D ActivityManager: startService callerProcessName:com.dropbox.android, calleePkgName: com.dropbox.android
03-17 13:26:08.412  1018  3004 D ActivityManager: retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,03-17 13:26:08.412  1018  3004 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:08.412  1018  3004 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,03-17 13:26:08.412  1018  3004 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-17 13:26:08.422  1018  3004 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.422  1018  3004 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.422  1018  3004 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.422  1018  3004 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.432  3568  3568 E Zygote  : MountEmulatedStorage(),
03-17 13:26:08.432  3568  3568 E Zygote  : v2
03-17 13:26:08.432  3568  3568 I libpersona: KNOX_SDCARD checking this for 10092
03-17 13:26:08.432  3568  3568 I libpersona: KNOX_SDCARD not a persona,
03-17 13:26:08.442  1018  3004 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3568 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 13:26:08.442  3568  3568 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 13:26:08.442  3568  3568 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 13:26:08.452  3568  3568 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 13:26:08.462  3319  3360 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,03-17 13:26:08.472  3449  3515 W TRThreadPoolExecutor: Task "p[Get token]" is a o. Failures of FutureTask can not be detected and exceptions will not be propagated by the executor
,03-17 13:26:08.492  1976  1976 D VideoCallManager: Instantiating VideoCallManager
,03-17 13:26:08.492  3568  3568 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:08.492  3568  3568 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:08.492  1976  1976 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 13:26:08.492  1976  1976 I GFX construct_block_size_descriptor_2d second part: took 2.133021ms for 0*0 texture 0
,03-17 13:26:08.502  1976  1976 I GFX generate_partition_tables: took 5.164428ms for 0*0 texture 0
,03-17 13:26:08.512  1976  1976 I GFX raster: took 11.294896ms for 176*144 texture 0
03-17 13:26:08.512  1976  1976 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8567588 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb857f798 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 13:26:08.512  3268  3373 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,03-17 13:26:08.512  1976  1976 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
,03-17 13:26:08.512  1976  1976 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 13:26:08.512  1976  1976 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 13:26:08.512  1976  1976 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 13:26:08.512  1976  1976 I Adreno-EGL: Local Branch: 
03-17 13:26:08.512  1976  1976 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 13:26:08.512  1976  1976 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 13:26:08.512  1976  1976 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 13:26:08.532  1976  1976 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 13:26:08.542  3528  3528 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-17 13:26:08.542  1976  1976 I glCompressedTexImage2D: took 0.269739ms for 320*61440 texture 37809
,03-17 13:26:08.552  1976  1976 I draw setup: took 10.528854ms for 320*240 texture 37809
03-17 13:26:08.552  1976  1976 E GFX GPU raster: drawn
,03-17 13:26:08.552  1976  1976 I GFX GPU raster ASTC: took 41.081094ms for 320*240 texture 12
03-17 13:26:08.552  1976  1976 I GFX raster: took 41.184376ms for 320*240 texture 0
03-17 13:26:08.552  1976  1976 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb857f798 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb8581ad8 counterpartCT=4 counterpartW=320 counterparth=240
,03-17 13:26:08.572  1976  1976 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,03-17 13:26:08.572  1976  1976 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS,
,03-17 13:26:08.572  1976  1976 I glCompressedTexImage2D: took 0.393594ms for 480*122880 texture 37813
03-17 13:26:08.572  1976  1976 I draw setup: took 0.744688ms for 480*640 texture 37813
03-17 13:26:08.572  1976  1976 E GFX GPU raster: drawn
,03-17 13:26:08.582  1976  1976 I GFX GPU raster ASTC: took 8.624323ms for 480*640 texture 12
03-17 13:26:08.582  1976  1976 I GFX raster: took 8.814114ms for 480*640 texture 0
03-17 13:26:08.582  1976  1976 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8581ad8 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb87aff68 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 13:26:08.632  3268  3373 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-17 13:26:08.632  1018  3000 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,03-17 13:26:08.632  1018  3000 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,03-17 13:26:08.642  1018  3000 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:08.642  1018  3000 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:08.642  1018  3000 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:08.642  1976  1976 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,03-17 13:26:08.642  1976  1976 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS,
,03-17 13:26:08.652  1976  1976 I glCompressedTexImage2D: took 0.779166ms for 440*116864 texture 37809
03-17 13:26:08.652  1976  1976 I draw setup: took 1.437604ms for 440*330 texture 37809,
03-17 13:26:08.652  1976  1976 E GFX GPU raster: drawn
,03-17 13:26:08.652  1976  1976 I GFX GPU raster ASTC: took 5.790261ms for 440*330 texture 12
03-17 13:26:08.652  1976  1976 I GFX raster: took 5.886927ms for 440*330 texture 0
03-17 13:26:08.652  1976  1976 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb87aff68 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb87c4358 counterpartCT=4 counterpartW=440 counterparth=330
,03-17 13:26:08.662  1018  1030 I art     : Explicit concurrent mark sweep GC freed 20935(1102KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 26MB/39MB, paused 3.083ms total 192.940ms
,03-17 13:26:08.662  1018  1483 I ActivityManager: Killing 2462:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,03-17 13:26:08.662  3319  3360 I DBG_POLICYDM: [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-17 13:26:08.672  3268  3373 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,03-17 13:26:08.672  3268  3373 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,03-17 13:26:08.692  3412  3549 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 13:26:08.692  1976  1976 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
03-17 13:26:08.692  3412  3549 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@14f5d0d6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 13:26:08.692  3412  3549 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-17 13:26:08.692  1976  1976 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
,03-17 13:26:08.692  1976  1976 I glCompressedTexImage2D: took 0.451719ms for 480*163840 texture 37811
03-17 13:26:08.692  1976  1976 I draw setup: took 0.882240ms for 480*640 texture 37811
03-17 13:26:08.692  1976  1976 E GFX GPU raster: drawn
,03-17 13:26:08.702  1976  1976 I GFX GPU raster ASTC: took 6.083021ms for 480*640 texture 12
03-17 13:26:08.702  1976  1976 I GFX raster: took 6.159168ms for 480*640 texture 0
03-17 13:26:08.702  1976  1976 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb87b4168 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb87c3e90 counterpartCT=4 counterpartW=480 counterparth=640
,03-17 13:26:08.722  3232  3232 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3232
,03-17 13:26:08.742  1018  2734 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,03-17 13:26:08.752  1976  1976 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 13:26:08.752  1976  1976 I GFX construct_block_size_descriptor_2d second part: took 2.131823ms for 0*0 texture 0
,03-17 13:26:08.762  3528  3528 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-17 13:26:08.762  1976  1976 I GFX generate_partition_tables: took 7.406406ms for 0*0 texture 0
,03-17 13:26:08.762  1976  1976 I GFX raster: took 11.530365ms for 176*144 texture 0
03-17 13:26:08.762  1976  1976 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb87ad828 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb87ad948 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 13:26:08.762  1018  1152 I ActivityManager: Killing 2760:com.android.email/u0a145 (adj 15): empty #31
,03-17 13:26:08.782  1976  1976 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,03-17 13:26:08.782  1976  1976 I GFX construct_block_size_descriptor_2d second part: took 2.377656ms for 0*0 texture 0
,03-17 13:26:08.792  3551  3551 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.8.KK_APP
,03-17 13:26:08.792  1018  1043 W libprocessgroup: failed to open /acct/uid_10044/pid_2462/cgroup.procs: No such file or directory
,03-17 13:26:08.802  1976  1976 I GFX generate_partition_tables: took 6.243959ms for 0*0 texture 0
,03-17 13:26:08.802  3528  3528 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-17 13:26:08.802  1976  1976 I GFX raster: took 10.880834ms for 176*144 texture 0
03-17 13:26:08.802  1976  1976 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb87adb68 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb87adb08 counterpartCT=4 counterpartW=176 counterparth=144
,03-17 13:26:08.802  3528  3528 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
,03-17 13:26:08.802  1976  1976 D ScoverManager: registerListener
,03-17 13:26:08.812  1843  1868 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
03-17 13:26:08.812  1843  1868 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-17 13:26:08.812  1843  1868 I System.out: (HTTPLog)-Static: isShipBuild true
03-17 13:26:08.812  1843  1868 I System.out: (HTTPLog)-Thread-155-724459399: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-17 13:26:08.812  1843  1868 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-17 13:26:08.812   278   875 D EnterpriseController: uids 10012
03-17 13:26:08.812   278   875 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 13:26:08.812   278   875 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,03-17 13:26:08.812  1018  1505 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-17 13:26:08.812  1018  1031 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-17 13:26:08.812  1018  1031 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@3e8cdd58, pid : 1976, uid : 1001, type : 1
,03-17 13:26:08.822  3393  3393 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
,03-17 13:26:08.822  1018  2734 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,03-17 13:26:08.822  1018  2734 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.832  1018  2734 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.832  1018  2734 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:08.832  1018  2734 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:08.842  1018  2999 E Tethering: No numeric data
,03-17 13:26:08.852  2643  3174 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3174)  
,03-17 13:26:08.862  3602  3602 E Zygote  : MountEmulatedStorage(),
,03-17 13:26:08.862  3602  3602 E Zygote  : v2
03-17 13:26:08.862  3602  3602 I libpersona: KNOX_SDCARD checking this for 10062
03-17 13:26:08.862  1018  1152 E Tethering: No numeric data
03-17 13:26:08.862  3602  3602 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:08.862  3602  3602 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:08.862  1018  1152 E Tethering: No numeric data,
03-17 13:26:08.862  1018  2734 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3602 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:08.862  3602  3602 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:08.862  3602  3602 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:08.862  1018  1043 W libprocessgroup: failed to kill pid 2760: No such process
03-17 13:26:08.862  1018  2734 I ActivityManager: Killing 2778:com.samsung.android.sm/1000 (adj 15): empty #31
,03-17 13:26:08.872  1018  1369 E Tethering: No numeric data
,03-17 13:26:08.872  1018  3000 E Tethering: No numeric data
,03-17 13:26:08.882  1843  1868 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-17 13:26:08.882  1843  1868 I qtaguid : Tagging socket 70 with tag 3000040100000000{805307393,0} for uid 10012, pid: 1843, getuid(): 10012
,03-17 13:26:08.892  1018  3004 E Tethering: No numeric data
,03-17 13:26:08.892  1976  1976 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
,03-17 13:26:08.892  3393  3393 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,03-17 13:26:08.892  1018  1483 I ActivityManager: Killing 2863:flipboard.boxer.app/u0a99 (adj 15): empty #31
,03-17 13:26:08.912  3602  3602 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:08.912  3602  3602 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:08.922  3393  3393 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
,03-17 13:26:08.942  3517  3517 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,03-17 13:26:08.952  3232  3232 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-17 13:26:08.972  1843  1868 I qtaguid : Tagging socket 73 with tag 3000040100000000{805307393,0} for uid 10012, pid: 1843, getuid(): 10012
,03-17 13:26:08.992  1367  3266 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
,03-17 13:26:08.992  1367  3266 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
,03-17 13:26:09.002  3393  3393 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
,03-17 13:26:09.002  3393  3393 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
,03-17 13:26:09.012  3517  3517 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-17 13:26:09.012  3517  3517 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-17 13:26:09.022  3517  3517 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-17 13:26:09.022  3517  3517 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-17 13:26:09.022  3517  3517 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,03-17 13:26:09.022  3517  3517 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,03-17 13:26:09.022  3393  3393 I dbxyzptlk.db240408.D.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
,03-17 13:26:09.052  1018  1031 E Tethering: No numeric data
,03-17 13:26:09.052  1018  2999 E Tethering: No numeric data
,03-17 13:26:09.052  3393  3393 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,03-17 13:26:09.062  1018  1152 E Tethering: No numeric data
,03-17 13:26:09.102  3602  3602 I ExternalOEMControlProvider: onCreate
03-17 13:26:09.102  3358  3358 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 13:26:09.122  1018  1043 W libprocessgroup: failed to open /acct/uid_10145/pid_2760/cgroup.procs: No such file or directory
,03-17 13:26:09.132  1018  1043 W libprocessgroup: failed to open /acct/uid_10099/pid_2863/cgroup.procs: No such file or directory
03-17 13:26:09.132  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2778/cgroup.procs: No such file or directory
,03-17 13:26:09.142  1018  1369 E Tethering: No numeric data
,03-17 13:26:09.152  3358  3358 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-17 13:26:09.152  3358  3358 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-17 13:26:09.172  1018  3001 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.servicemodeapp, hostingType: broadcast
,03-17 13:26:09.182  1018  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.182  1018  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:09.182  1018  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:09.182  1018  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.192  3319  3362 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0],
,03-17 13:26:09.192  3629  3629 E Zygote  : MountEmulatedStorage(),
,03-17 13:26:09.202  3358  3358 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory,
,03-17 13:26:09.202  3629  3629 E Zygote  : v2,
03-17 13:26:09.202  3629  3629 I libpersona: KNOX_SDCARD checking this for 1000
,03-17 13:26:09.202  3629  3629 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:09.202  1018  3001 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3629 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 13:26:09.212  3629  3629 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 13:26:09.212  1018  3001 I ActivityManager: Killing 2201:flipboard.app/u0a98 (adj 15): empty #31
,03-17 13:26:09.212  3629  3629 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:09.222  1018  3001 D ActivityManager: startProcessLocked calleePkgName: com.google.android.onetimeinitializer, hostingType: broadcast
,03-17 13:26:09.222  3629  3629 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:09.222  1018  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.222  1018  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:09.222  1018  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:09.222  1018  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.222  1018  3000 D SettingsProvider: name = PREVIOUS_SYS_TIME
03-17 13:26:09.222  1018  3000 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 13:26:09.222  1018  3000 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 13:26:09.222  1018  3000 D SettingsProvider: selectionArgs: false
03-17 13:26:09.222  1018  3000 D SettingsProvider: selectionArgs: 10062
03-17 13:26:09.222  1018  3000 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 13:26:09.222  1018  3000 D SettingsProvider: ret = -1
,03-17 13:26:09.232   315   315 I art     : Explicit concurrent mark sweep GC freed 8763(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 642us total 26.712ms
03-17 13:26:09.232  1018  3000 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,03-17 13:26:09.242  1018  1369 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
03-17 13:26:09.242  1018  1369 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 13:26:09.242  1018  1369 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 13:26:09.242  1018  1369 D SettingsProvider: selectionArgs: false
03-17 13:26:09.242  1018  1369 D SettingsProvider: selectionArgs: 10062
03-17 13:26:09.242  1018  1369 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 13:26:09.242  1018  1369 D SettingsProvider: ret = -1
,03-17 13:26:09.252  1018  1369 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,03-17 13:26:09.262   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 736us total 22.137ms
,03-17 13:26:09.262  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:09.282   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 604us total 18.393ms
,03-17 13:26:09.282  3629  3629 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:09.282  3629  3629 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:09.282  1018  1031 V VibratorService: hasVibrator - useVibetonz: true
,03-17 13:26:09.292  3645  3645 E Zygote  : MountEmulatedStorage()
,03-17 13:26:09.292  3645  3645 E Zygote  : v2
03-17 13:26:09.292  3645  3645 I libpersona: KNOX_SDCARD checking this for 10014,
03-17 13:26:09.292  3645  3645 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 13:26:09.292  3645  3645 I libpersona: KNOX_SDCARD not a persona,
03-17 13:26:09.292  1018  3001 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3645 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,03-17 13:26:09.302  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:09.302  1018  3001 I ActivityManager: Killing 2924:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,03-17 13:26:09.302  3645  3645 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:09.302  3645  3645 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:09.312  1843  1868 D GCM     : COMPAT: Multi user not supported
,03-17 13:26:09.312  3319  3362 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,03-17 13:26:09.322  1367  3266 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
,03-17 13:26:09.332  1018  1369 V VibratorService: hasVibrator - useVibetonz: true
,03-17 13:26:09.352  1018  1369 V VibratorService: hasVibrator - useVibetonz: true
,03-17 13:26:09.352  3393  3393 I com.dropbox.sync.android.a: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,03-17 13:26:09.362  1367  3266 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 13:26:09.382  3645  3645 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:09.382  3645  3645 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:09.402  1018  3004 I ActivityManager: Killing 1940:com.android.defcontainer/u0a4 (adj 15): empty #31
,03-17 13:26:09.402  3232  3547 D jxcore_app_log: JniHelper::setJavaVM(0xb819d450), pthread_self() = -1200602184
,03-17 13:26:09.412  3629  3629 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 13:26:09.412  3232  3547 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 13:26:09.412  3232  3547 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 13:26:09.412  3232  3547 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 13:26:09.412  3232  3547 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 13:26:09.412  3232  3547 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-17 13:26:09.412  3232  3547 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ce9226 added. We now have 1 listener(s)
,03-17 13:26:09.412  1018  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
03-17 13:26:09.412  1018  1043 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.EsSyncAdapterService; callingUser = 0; userId(target) = 0
,03-17 13:26:09.422  1777  1777 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 13:26:09.422  3232  3547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,03-17 13:26:09.432  3232  3547 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
,03-17 13:26:09.432  3232  3547 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
,03-17 13:26:09.432  3232  3547 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
,03-17 13:26:09.432  3232  3547 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 13:26:09.442  3232  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 13:26:09.442  3232  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 13:26:09.442  3232  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 13:26:09.442  3232  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
03-17 13:26:09.442  3232  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 13:26:09.442  3232  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 13:26:09.442  3232  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 13:26:09.442  3232  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 13:26:09.442  3232  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 13:26:09.442  3232  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-17 13:26:09.442  3232  3547 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32f364bd added. We now have 1 listener(s)
03-17 13:26:09.442  3232  3547 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 13:26:09.452  1018  1043 W libprocessgroup: failed to open /acct/uid_10098/pid_2201/cgroup.procs: No such file or directory
,03-17 13:26:09.462  3232  3547 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-17 13:26:09.472  3232  3547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,03-17 13:26:09.472  3232  3547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,03-17 13:26:09.472  3232  3547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-17 13:26:09.472  3232  3547 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-17 13:26:09.482  3629  3629 I ServiceMode: received = ACTION_BOOT_COMPLETED
,03-17 13:26:09.482  3232  3547 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-17 13:26:09.482  3629  3629 I ServiceMode: setReferenceIsDumpState : 0
,03-17 13:26:09.482  3232  3547 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,03-17 13:26:09.492  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2924/cgroup.procs: No such file or directory
03-17 13:26:09.492  1018  1043 W libprocessgroup: failed to open /acct/uid_10004/pid_1940/cgroup.procs: No such file or directory
,03-17 13:26:09.492  3232  3547 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 13:26:09.492  3232  3547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 13:26:09.492  3232  3547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 13:26:09.492  3232  3547 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 13:26:09.492  3232  3547 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 13:26:09.492  3232  3547 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 13:26:09.492  3232  3547 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 13:26:09.492  3232  3547 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-17 13:26:09.492  3232  3547 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 13:26:09.492  3232  3547 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 13:26:09.502  3645  3645 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
,03-17 13:26:09.502  1018  1152 D ActivityManager: startService callerProcessName:com.google.android.onetimeinitializer, calleePkgName: com.google.android.onetimeinitializer
,03-17 13:26:09.502  1018  1152 D ActivityManager: retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,03-17 13:26:09.502  1018  1152 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:09.502  1018  1152 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:09.502  1018  1152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,03-17 13:26:09.522  3645  3668 V OneTimeService: OneTimeService.onHandleIntent
,03-17 13:26:09.532  1018  3002 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-17 13:26:09.532  1018  3002 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,03-17 13:26:09.532  1018  3002 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:09.532  1018  3002 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:09.532  1018  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 13:26:09.562  1367  3266 D ScoverManager: serviceVersion : 16908288
,03-17 13:26:09.572  3232  3232 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 13:26:09.572  1018  1152 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-17 13:26:09.572  1018  1152 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,03-17 13:26:09.572  3232  3232 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 13:26:09.582  3232  3232 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-17 13:26:09.582  1018  1152 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:09.582  1018  1152 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:09.582  1018  1152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 13:26:09.592  1018  1483 D ActivityManager: startProcessLocked calleePkgName: com.wssnps, hostingType: broadcast
,03-17 13:26:09.592  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.592  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.592  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.592  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.602  3670  3670 E Zygote  : MountEmulatedStorage()
03-17 13:26:09.602  3670  3670 E Zygote  : v2
03-17 13:26:09.602  3670  3670 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:09.602  3670  3670 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:09.602  3670  3670 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:09.612  3670  3670 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:09.612  3670  3670 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:09.612  1018  1483 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3670 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 13:26:09.612  1018  1483 I ActivityManager: Killing 2940:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,03-17 13:26:09.622  1018  1483 I ActivityManager: Killing 2370:com.sec.modem.settings/1000 (adj 15): empty #31
,03-17 13:26:09.622  1018  2999 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-17 13:26:09.622  1018  2999 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,03-17 13:26:09.622  1018  2999 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:09.622  1018  2999 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:09.622  1018  2999 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 13:26:09.642  3393  3393 I com.dropbox.sync.android.ad: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
,03-17 13:26:09.652  3670  3670 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:09.652  3670  3670 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:09.662  1018  1369 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-17 13:26:09.662  1018  1369 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,03-17 13:26:09.662  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:09.662  1018  1369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:09.662  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 13:26:09.712  1777  1777 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 13:26:09.722  3268  3373 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-17 13:26:09.752  1777  1777 I SamsungIME: KeybaordView init() : load resources
,03-17 13:26:09.782  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2370/cgroup.procs: No such file or directory
03-17 13:26:09.782  1018  1043 W libprocessgroup: failed to open /acct/uid_10152/pid_2940/cgroup.procs: No such file or directory
,03-17 13:26:09.822  3670  3670 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
,03-17 13:26:09.832  1018  1231 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
,03-17 13:26:09.832  1018  1231 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,03-17 13:26:09.832  1018  1231 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:09.832  1018  1231 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:09.832  1018  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 13:26:09.842  3670  3670 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,03-17 13:26:09.842  1018  1152 D ActivityManager: startService callerProcessName:com.wssnps, calleePkgName: com.wssnps
03-17 13:26:09.842  1018  1152 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-17 13:26:09.852  1018  1152 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:09.852  1018  1152 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:09.852  1018  1152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 13:26:09.852  1777  1777 I SamsungIME: getCurrentKeyboard
03-17 13:26:09.852  1777  1777 I SamsungIME: getTextKeyboard
,03-17 13:26:09.852  1018  1483 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,03-17 13:26:09.862  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:09.862  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:09.862  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:09.862  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.862  3670  3670 D NPS_WSSNPS: [] Service onCreate!!
,03-17 13:26:09.872  3693  3693 E Zygote  : MountEmulatedStorage()
,03-17 13:26:09.872  3693  3693 E Zygote  : v2,
03-17 13:26:09.872  3693  3693 I libpersona: KNOX_SDCARD checking this for 1000,
03-17 13:26:09.872  3693  3693 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:09.872  1018  1483 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=3693 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 13:26:09.872  3693  3693 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:09.882  3693  3693 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:09.882  3693  3693 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:09.882  1018  1388 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
03-17 13:26:09.882  1018  1388 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 13:26:09.882  1018  1388 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:09.882  1018  1388 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:09.882  1018  1388 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 13:26:09.882  2587  2587 I Hs20UtilService: Starting #2
,03-17 13:26:09.882  1018  3002 D ActivityManager: startProcessLocked calleePkgName: com.samsung.klmsagent, hostingType: broadcast
,03-17 13:26:09.882  1018  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.882  1018  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:09.892  2587  2604 I Hs20UtilService: Message received 5003
03-17 13:26:09.892  1018  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.892  3670  3699 D NPS_WSSNPS: [50.150621] NpsServiceTask Start
03-17 13:26:09.892  1018  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.902  1018  3002 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3703 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-17 13:26:09.912  3703  3703 E Zygote  : MountEmulatedStorage()
03-17 13:26:09.912  3703  3703 I libpersona: KNOX_SDCARD checking this for 10019
03-17 13:26:09.912  3703  3703 E Zygote  : v2
03-17 13:26:09.912  3703  3703 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:09.912  3703  3703 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 13:26:09.912  3703  3703 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:09.912  3703  3703 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:09.922  3693  3693 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:09.922  3693  3693 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:09.922  1018  1505 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,03-17 13:26:09.932  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:09.932  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:09.932  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:09.932  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:09.932  3670  3670 D NPS_WSSNPS: [50.150621] smlDBHelper
,03-17 13:26:09.932  1777  1777 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 13:26:09.942  3722  3722 E Zygote  : MountEmulatedStorage()
03-17 13:26:09.942  3722  3722 E Zygote  : v2
03-17 13:26:09.942  3722  3722 I libpersona: KNOX_SDCARD checking this for 10094
03-17 13:26:09.942  3722  3722 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:09.942  3722  3722 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:09.942  3722  3722 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:09.942  1018  1505 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3722 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
03-17 13:26:09.942  3722  3722 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:09.952  1018  1505 I ActivityManager: Killing 2961:com.sec.knox.bridge/1000 (adj 15): empty #31
,03-17 13:26:09.962   291   291 E SMD     : DCD OFF
,03-17 13:26:09.992  3670  3670 I NPS_WSSNPS: [50.150621] AsyncBulkFlagCheck
,03-17 13:26:10.012  3693  3693 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:10.032  3670  3745 I NPS_WSSNPS: [50.150621] IsRemain_AsyncBulkCheck
,03-17 13:26:10.032  3722  3722 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:10.032  3670  3745 I NPS_WSSNPS: [50.150621] IsRemain_Asyncing nothing
,03-17 13:26:10.032  3670  3745 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,03-17 13:26:10.032  1018  1152 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-17 13:26:10.042  3722  3722 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:10.042  1018  1152 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:10.042  1018  1152 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:10.042  1018  1152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-17 13:26:10.042  1018  3000 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
03-17 13:26:10.042  1018  3000 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:10.042  1018  3000 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
03-17 13:26:10.042  1018  3000 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:10.042  1018  3000 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-17 13:26:10.042  3670  3670 D NPS_WSSNPS: [50.150621] Service onDestroy
,03-17 13:26:10.062  3670  3670 I NPS_WSSNPS: [50.150621] smlBRConfigurationDelete
,03-17 13:26:10.062  3670  3670 I NPS_WSSNPS: [50.150621] smlBRMessageDelete
,03-17 13:26:10.062  3670  3670 I NPS_WSSNPS: [50.150621] smlBREmailDelete
03-17 13:26:10.062  3670  3670 I NPS_WSSNPS: [50.150621] smlBRNetworkDelete
,03-17 13:26:10.062  3670  3670 I NPS_WSSNPS: [50.150621] smlBRCallLogDelete
03-17 13:26:10.062  3670  3670 I NPS_WSSNPS: [50.150621] smlBRMiniDiaryDelete
,03-17 13:26:10.062  3670  3670 I NPS_WSSNPS: [50.150621] smlBRPenMemoMDelete
03-17 13:26:10.062  3670  3670 I NPS_WSSNPS: [50.150621] smlBRSMemoDelete
,03-17 13:26:10.062  3670  3670 I NPS_WSSNPS: [50.150621] verifier installed? false
03-17 13:26:10.062  3670  3670 I NPS_WSSNPS: [50.150621] cpuBooster release : false
,03-17 13:26:10.062  3703  3703 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:10.072  3703  3703 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:10.102  3412  3596 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-17 13:26:10.102  3412  3596 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 13:26:10.102  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_2961/cgroup.procs: No such file or directory
,03-17 13:26:10.112  3670  3670 D NPS_WSSNPS: [50.150621] dsServerSocket close
,03-17 13:26:10.112  1018  1505 I ActivityManager: Killing 3007:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,03-17 13:26:10.132  3393  3710 I System.out: Thread-454(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 13:26:10.142  3393  3710 I System.out: Thread-454(ApacheHTTPLog):isSBSettingEnabled false
03-17 13:26:10.142  3393  3710 I System.out: Thread-454(ApacheHTTPLog):isShipBuild true
03-17 13:26:10.142  3393  3710 I System.out: Thread-454(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 13:26:10.142  3393  3710 I System.out: Thread-454(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 13:26:10.142   278   875 D EnterpriseController: uids 10092
03-17 13:26:10.142   278   875 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 13:26:10.142   278   875 D Netd    : getNetworkForDns: using netid 502 for uid 10092
,03-17 13:26:10.182  3703  3703 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 13:26:10 GMT+01:00 2016
,03-17 13:26:10.182  1018  1369 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,03-17 13:26:10.182  1018  1369 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-17 13:26:10.192  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:10.192  1018  1369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 13:26:10.192  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 13:26:10.192  3722  3722 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-17 13:26:10.202  3722  3722 D elm:15183: ELMEngine.ELMEngine( context ).
,03-17 13:26:10.202  3722  3722 D elm:15183: MDMBridge.setEnterpriseBridge()
,03-17 13:26:10.202  3703  3703 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-17 13:26:10.212  2661  2731 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-17 13:26:10.212  1018  1485 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
03-17 13:26:10.212  1018  1485 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,03-17 13:26:10.212  1018  1485 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:10.212  1018  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:10.212  1018  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-17 13:26:10.222  3722  3722 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-17 13:26:10.232  1427  1427 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,03-17 13:26:10.232  1018  1231 D ActivityManager: startProcessLocked calleePkgName: com.android.managedprovisioning, hostingType: broadcast
,03-17 13:26:10.232  3472  3472 I RlzPingService: Setting next ping for 1458822370246
,03-17 13:26:10.232  1018  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.242  1018  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.242  1018  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.242  1018  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.232  1018  1043 W libprocessgroup: failed to open /acct/uid_1101/pid_3007/cgroup.procs: No such file or directory,
,03-17 13:26:10.252  3412  3412 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-17 13:26:10.262  3757  3757 E Zygote  : MountEmulatedStorage()
,03-17 13:26:10.262  3757  3757 E Zygote  : v2
03-17 13:26:10.262  3757  3757 I libpersona: KNOX_SDCARD checking this for 10022
03-17 13:26:10.262  3757  3757 I libpersona: KNOX_SDCARD not a persona,
,03-17 13:26:10.262  3722  3722 D elm:15183: ElmAgentService : onCreate(),
03-17 13:26:10.262  3722  3754 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
03-17 13:26:10.262  1018  1231 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3757 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a
03-17 13:26:10.262  3722  3722 D elm:15183: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
03-17 13:26:10.262  3722  3722 D elm:15183: BootCompletedState : startBootCompleted() call,
03-17 13:26:10.262  3703  3703 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
03-17 13:26:10.262  3757  3757 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:10.262  3703  3703 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 13:26:10.272  3703  3703 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false,
,03-17 13:26:10.272  3757  3757 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 13:26:10.272  3757  3757 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:10.272  3703  3755 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-17 13:26:10.282  3703  3755 I KLMS-2.5.183: : KLMSIntentService(): BOOT_COMPLETED
,03-17 13:26:10.292  3722  3722 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 13:26:10.292  3722  3722 I elm:15183: Get License : 0
,03-17 13:26:10.302  3757  3757 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:10.302  3757  3757 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:10.312  3722  3722 D elm:15183: ElmAgentService : onDestroy().
,03-17 13:26:10.312  1427  1427 V EmergencyMode: [EmergencyBase] setBootTime
03-17 13:26:10.312  1427  1427 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
,03-17 13:26:10.312  1018  3000 I ActivityManager: Killing 2336:com.android.mms/u0a46 (adj 15): empty #31
,03-17 13:26:10.322  1018  1505 D ActivityManager: startProcessLocked calleePkgName: com.sec.factory.camera, hostingType: broadcast
,03-17 13:26:10.322  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.322  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.322  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.322  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.322  3703  3703 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-17 13:26:10.332  3753  3753 I dex2oat : ----------------------------------------------------
03-17 13:26:10.332  3753  3753 I dex2oat : <SS>: S T A R T I N G . . .
03-17 13:26:10.332  3753  3753 I dex2oat : <SS>: Zip is absent. Canceled.
,03-17 13:26:10.332  3753  3753 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads822843933.jar --oat-fd=33 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads822843933.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-17 13:26:10.342  3782  3782 E Zygote  : MountEmulatedStorage()
03-17 13:26:10.342  3782  3782 E Zygote  : v2
03-17 13:26:10.342  3782  3782 I libpersona: KNOX_SDCARD checking this for 1000
,03-17 13:26:10.342  3782  3782 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 13:26:10.342  3782  3782 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:10.342  3782  3782 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 13:26:10.342  3782  3782 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:10.342  1018  1505 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3782 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 13:26:10.362  1018  1483 I ActivityManager: Killing 3059:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,03-17 13:26:10.372  3782  3782 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:10.372  3782  3782 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:10.402  3412  3412 I System.out: YouTube MDX: MDX video stage moved to NEW
,03-17 13:26:10.402  3412  3412 I System.out: YouTube MDX: MDX video player state moved to UNSTARTED
,03-17 13:26:10.402  3412  3412 I System.out: YouTube MDX: MDX ad player state moved to UNSTARTED
,03-17 13:26:10.422  1367  3266 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 13:26:10.442  1367  3266 D Settings_Utils: isSupportVNFestival SM-A500FU XEO
,03-17 13:26:10.442  3232  3667 W jxcore-log: Initializing JXcore engine
03-17 13:26:10.442  3232  3667 W jxcore-log: JXcore engine is ready
,03-17 13:26:10.452  1018  1152 D CountryDetector: No listener is left
,03-17 13:26:10.462  3782  3782 I CameraApp: CameraApp.onCreate()... mFeature : null
,03-17 13:26:10.462  3782  3782 I testFeature: Feature.Feature(context)
03-17 13:26:10.462  3782  3782 I testFeature: Feature.readInternalDefaultXml()
03-17 13:26:10.462  3782  3782 I testFeature: ResetFeatureValue
,03-17 13:26:10.462  3782  3782 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
03-17 13:26:10.462  3782  3782 I CameraApp: CameraApp.getAppFeature()...
,03-17 13:26:10.462  1018  3004 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,03-17 13:26:10.462  1018  3004 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.462  1018  3004 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.462  1018  3004 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.462  1018  3004 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.472  3753  3753 I dex2oat : dex2oat took 139.969ms (threads: 4)
,03-17 13:26:10.482  3807  3807 E Zygote  : MountEmulatedStorage(),
,03-17 13:26:10.482  3807  3807 E Zygote  : v2,
03-17 13:26:10.482  3807  3807 I libpersona: KNOX_SDCARD checking this for 10100
03-17 13:26:10.482  3807  3807 I libpersona: KNOX_SDCARD not a persona,
03-17 13:26:10.492  1018  3004 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3807 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-17 13:26:10.492  3807  3807 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 13:26:10.492  3807  3807 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 13:26:10.502  3807  3807 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:10.512  1928  1928 E audit   : type=1400 msg=audit(1458217570.512:205): avc:  denied  { ioctl } for  pid=3667 comm="Thread-434" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
03-17 13:26:10.512  1928  1928 E audit   :  SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:10.512  1928  1928 E audit   : type=1300 msg=audit(1458217570.512:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9c28f8f8 items=0 ppid=315 ppcomm=main pid=3667 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-434" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-17 13:26:10.512  1928  1928 E audit   : type=1320 msg=audit(1458217570.512:205): 
,03-17 13:26:10.532  1018  3004 I ActivityManager: Killing 3078:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31
,03-17 13:26:10.532  3232  3667 W jxcore-log: Starting JXcore engine
,03-17 13:26:10.542  3807  3807 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:10.552  3807  3807 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:10.572  3807  3807 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
,03-17 13:26:10.602  1018  1043 W libprocessgroup: failed to open /acct/uid_10157/pid_3059/cgroup.procs: No such file or directory
,03-17 13:26:10.602  3807  3807 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,03-17 13:26:10.602  1018  1369 D ActivityManager: startProcessLocked calleePkgName: com.google.android.gm, hostingType: broadcast
,03-17 13:26:10.602  1018  1043 W libprocessgroup: failed to open /acct/uid_10046/pid_2336/cgroup.procs: No such file or directory
,03-17 13:26:10.612  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.612  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.612  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.612  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.622  1018  1369 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3826 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 13:26:10.622  3826  3826 E Zygote  : MountEmulatedStorage()
03-17 13:26:10.622  3826  3826 E Zygote  : v2
03-17 13:26:10.622  3826  3826 I libpersona: KNOX_SDCARD checking this for 10101
03-17 13:26:10.622  3826  3826 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:10.622  1018  1369 I ActivityManager: Killing 3102:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,03-17 13:26:10.632  3826  3826 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 13:26:10.632  3826  3826 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:10.632  3826  3826 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:10.652  1018  1483 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,03-17 13:26:10.652  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.652  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.652  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.652  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.672  3836  3836 E Zygote  : MountEmulatedStorage()
,03-17 13:26:10.672  3836  3836 E Zygote  : v2
03-17 13:26:10.672  3836  3836 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:10.672  3836  3836 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:10.672  3836  3836 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 13:26:10.672  1018  1483 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3836 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 13:26:10.672  1018  1483 I ActivityManager: Killing 3045:com.sec.dsm.system/1000 (adj 15): empty #31
03-17 13:26:10.672  3836  3836 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:10.672  3836  3836 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:10.692  3232  3667 W jxcore-log: Platform android
03-17 13:26:10.692  3232  3667 W jxcore-log: 
,03-17 13:26:10.692  3232  3667 W jxcore-log: Process ARCH arm
03-17 13:26:10.692  3232  3667 W jxcore-log: 
,03-17 13:26:10.702  3836  3836 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:10.712  3836  3836 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:10.712  3826  3826 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:10.712  3826  3826 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:10.732  3268  3373 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,03-17 13:26:10.752  1018  1485 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.accesscontrol, hostingType: broadcast
,03-17 13:26:10.752  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.752  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:10.752  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.752  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:10.782  3860  3860 E Zygote  : MountEmulatedStorage()
03-17 13:26:10.782  3860  3860 E Zygote  : v2
03-17 13:26:10.782  3860  3860 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:10.782  3860  3860 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:10.782  3860  3860 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:10.782  3860  3860 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 13:26:10.792  1018  1485 I ActivityManager: Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3860 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
03-17 13:26:10.792  3860  3860 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:10.792  1018  1485 I ActivityManager: Killing 3132:com.sec.usbsettings/1000 (adj 15): empty #31
,03-17 13:26:10.812   315   315 I art     : Explicit concurrent mark sweep GC freed 8743(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 765us total 24.949ms,
,03-17 13:26:10.822  1018  1043 W libprocessgroup: failed to open /acct/uid_10048/pid_3078/cgroup.procs: No such file or directory,
,03-17 13:26:10.832   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 18.482ms,
,03-17 13:26:10.832  3860  3860 D TimaKeyStoreProvider: TimaSignature is unavailable,
03-17 13:26:10.832  3860  3860 D ActivityThread: Added TimaKeyStore provider,
,03-17 13:26:10.842  2643  2643 D FactoryTestApp: [DummyFtClient$onDestroy](2643) Destroy DummyFtClient service,
,03-17 13:26:10.852   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 19.927ms
,03-17 13:26:10.862  2643  2643 D FactoryTestApp: [Support$Values.getString](2643) id=MODEL_COMMUNICATION_MODE, value=gsm
03-17 13:26:10.862  2643  2643 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2643) mConnectionMode = gsm
03-17 13:26:10.862  2643  2643 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2643) RUNNING_FTCLIENT : false
03-17 13:26:10.862  2643  2643 D FactoryTestApp: [DummyFtClient$onDestroy](2643) kill process
03-17 13:26:10.862  2643  2643 I Process : Sending signal. PID: 2643 SIG: 9
,03-17 13:26:10.872  3836  3836 E MTPRx   : In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,03-17 13:26:10.892  1018  1483 D SecContentProvider2: uri = 14 selection = getSealedState
,03-17 13:26:10.892  1018  1483 D SecContentProvider2: mCursor = null
,03-17 13:26:10.902  1018  1388 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
,03-17 13:26:10.902  1018  1388 D SecContentProvider2: mCursor = null
,03-17 13:26:10.902  3836  3836 V MTPRx   : sealedState: false
03-17 13:26:10.902  3836  3836 V MTPRx   : sealedUsbMassStorageState: false
,03-17 13:26:10.902  1018  1485 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:10.902  1018  1485 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:10.912  1018  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:10.912  1018  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 13:26:10.912  1018  1369 D SettingsProvider: name = mtp_usb_connection_status
,03-17 13:26:10.942  1018  3002 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:10.942  1018  3002 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:10.942  1018  3002 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:10.942  1018  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 13:26:10.952  3232  3667 I jxcore-log: JXcore Cordova bridge is ready!
03-17 13:26:10.952  3232  3667 I jxcore-log: 
,03-17 13:26:10.952  3232  3667 W jxcore-log: JXcore engine is started
,03-17 13:26:10.962  3232  3547 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 13:26:10.972  1018  1483 I ActivityManager: Process com.sec.factory (pid 2643)(adj 0) has died(87,1119)
,03-17 13:26:10.972  1018  2734 D SettingsProvider: name = media_player_mode
,03-17 13:26:10.972  1018  3000 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:10.982  1018  3000 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:10.982  1018  3000 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:10.982  1018  3000 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 13:26:10.982  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:10.992  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3045/cgroup.procs: No such file or directory
03-17 13:26:10.992  1018  1043 W libprocessgroup: failed to open /acct/uid_10159/pid_3102/cgroup.procs: No such file or directory
03-17 13:26:10.992  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3132/cgroup.procs: No such file or directory
,03-17 13:26:10.992  3232  3667 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-17 13:26:10.992  3232  3667 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-17 13:26:11.002  1018  2999 D SettingsProvider: name = access_control_enabled
,03-17 13:26:11.002  3232  3232 I chromium: [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,03-17 13:26:11.012  1018  1388 D FocusedStackFrame: Set to : 0
,03-17 13:26:11.012  1018  1388 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-17 13:26:11.012  1018  1388 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
,03-17 13:26:11.012  1018  1388 D InputDispatcher: Focused application set to: xxxx
,03-17 13:26:11.012  1018  1388 D InputDispatcher: Focus left window: 3232
,03-17 13:26:11.022  1018  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 13:26:11.022  1018  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 13:26:11.022   258   447 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (403 us)
,03-17 13:26:11.042  3232  3547 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 37ms. Plugin should use CordovaInterface.getThreadPool().
,03-17 13:26:11.042  1018  1231 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast,
03-17 13:26:11.052  1018  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.052  1018  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.052  1018  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.052  1018  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.062  3880  3880 E Zygote  : MountEmulatedStorage(),
03-17 13:26:11.062  3880  3880 E Zygote  : v2
03-17 13:26:11.062  3880  3880 I libpersona: KNOX_SDCARD checking this for 10069
03-17 13:26:11.062  3880  3880 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:11.062  3880  3880 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:11.062  3880  3880 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:11.062  1018  1231 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3880 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-17 13:26:11.072  3880  3880 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:11.072  1018  1505 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-17 13:26:11.072  1018  1505 W ActivityManager: mDVFSHelper.acquire()
03-17 13:26:11.072  1018  1505 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 13:26:11.072  1018  1505 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 13:26:11.072  1018  1505 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-17 13:26:11.092  1490  1490 D Launcher: onRestart, Launcher: 1003595514
,03-17 13:26:11.092  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-17 13:26:11.092  1018  1018 D SensorService: [SO] activate (ident=0xb8a050e8, enabled=0)
,03-17 13:26:11.092  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-17 13:26:11.092  1490  1490 D Launcher: onStart, Launcher: 1003595514
03-17 13:26:11.092  1490  1490 D Launcher.HomeView: onStart
03-17 13:26:11.092  1490  1490 D Launcher: onResume, Launcher: 1003595514
03-17 13:26:11.092  1018  3002 D SettingsProvider: name = kids_home_mode
03-17 13:26:11.092  1018  3002 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 13:26:11.092  1018  3002 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 13:26:11.092  1018  3002 D SettingsProvider: selectionArgs: false
03-17 13:26:11.092  1018  3002 D SettingsProvider: selectionArgs: 10007
03-17 13:26:11.092  1018  3002 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 13:26:11.092  1018  3002 D SettingsProvider: ret = -1
,03-17 13:26:11.102  1490  1490 D Launcher.HomeView: onResume
03-17 13:26:11.102  1018  3000 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 13:26:11.102  1018  1018 D SensorManager: unregisterListener ::   
,03-17 13:26:11.102  1018  1018 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-17 13:26:11.102  1018  1018 D SensorService: [SO] changed settle time [0]
03-17 13:26:11.102  1018  1018 D SensorService: [SO] setDelay [200000000]
03-17 13:26:11.102  1018  1018 D SensorService: [SO] activate (ident=0xb8a050e8, enabled=1)
03-17 13:26:11.102  1018  1018 D SensorService: [SO] AR_init
03-17 13:26:11.102  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-17 13:26:11.112  3880  3880 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:11.112  1490  1490 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 13:26:11.112  3880  3880 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:11.112  1018  1018 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,03-17 13:26:11.112  1018  1505 D ActivityManager: bindService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube, action: null
03-17 13:26:11.112  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-17 13:26:11.112  1490  1490 D MenuAppsGridFragment: onResume
,03-17 13:26:11.122  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:11.122  1018  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:11.122  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 13:26:11.122  1018  1369 D SettingsProvider: name = mtp_running_status
,03-17 13:26:11.122  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:11.122  1018  1388 D ActivityManager: handle home activity for 0
,03-17 13:26:11.132  1018  1388 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,03-17 13:26:11.132  1018  1388 D KnoxTimeoutHandler: post home show event for user 0
,03-17 13:26:11.132  1018  1018 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
,03-17 13:26:11.132  1018  1388 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-17 13:26:11.132  1018  1018 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
,03-17 13:26:11.132  1018  1388 D KnoxTimeoutHandler: postActiveUserChange for user 0
,03-17 13:26:11.132  1018  1388 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-17 13:26:11.142  1018  3002 D SettingsProvider: name = media_mount_count
,03-17 13:26:11.142  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:11.142  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 13:26:11.142  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 13:26:11.142   258   258 I SurfaceFlinger: id=12 createSurf (720x1280),1 flag=4, Mauncher
,03-17 13:26:11.142  1018  1050 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 13:26:11.152  1018  1050 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 13:26:11.152  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:11.152  1018  2734 D InputDispatcher: Focus entered window: 1490
,03-17 13:26:11.152  1018  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-17 13:26:11.152  1018  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 13:26:11.152  1490  1490 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 13:26:11.162  1018  1152 D SettingsProvider: name = mtp_sync_alive
,03-17 13:26:11.172  1490  1490 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 13:26:11.172  1018  1369 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 13:26:11.182  1018  3900 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:26:11.182  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:11.182   257   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 13:26:11.182   257   529 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:11.182  3412  3412 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 13:26:11.182  3232  3232 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 13:26:11.182  1191  1191 I StatusBar: Icon Only
03-17 13:26:11.182  1191  1191 D PanelView: There is/are notification(s) 
,03-17 13:26:11.202  1777  1777 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-17 13:26:11.202  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:11.212  1018  1388 D SettingsProvider: name = sdcard_launch
,03-17 13:26:11.212  3880  3880 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,03-17 13:26:11.222  1490  1490 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@bd24560 time:41982
,03-17 13:26:11.222  1018  1052 D PersonaManager: isKioskContainerExistOnDevice
,03-17 13:26:11.242  1018  1052 I ActivityManager: Displayed Component not be shown by security: +170ms
,03-17 13:26:11.262  1018  1231 D SettingsProvider: name = boot_time_connected
,03-17 13:26:11.262  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:11.292  1018  2999 D SettingsProvider: name = mtp_open_session
,03-17 13:26:11.312  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:11.312  1018  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-17 13:26:11.322  3490  3490 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-17 13:26:11.322  3490  3490 I PCWCLIENTTRACE_PushUtil: sales region : global
,03-17 13:26:11.332  3490  3490 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 13:26:11.332  3490  3490 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.BOOT_COMPLETED
03-17 13:26:11.332  3490  3490 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Version: 4.82
03-17 13:26:11.332  3490  3490 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Push type: [SPP, GCM]
,03-17 13:26:11.352  3490  3490 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,03-17 13:26:11.392  1018  3000 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 13:26:11.392  1018  3000 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 13:26:11.402  3490  3490 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-17 13:26:11.402  3490  3490 I ReactiveServiceManager: Supported : 1
,03-17 13:26:11.412  1018  3000 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,03-17 13:26:11.412  1018  3000 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 13:26:11.412  1367  3266 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-17 13:26:11.432  1018  3000 D QSEECOMAPI: : Loaded image: APP id = 9
,03-17 13:26:11.452  1018  3000 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-17 13:26:11.452  1018  3000 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 9
,03-17 13:26:11.452  1018  3000 E terrier : handleString: Failed to handle string(-4)
03-17 13:26:11.452  1018  3000 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
03-17 13:26:11.452  3490  3490 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-17 13:26:11.452  3490  3490 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,03-17 13:26:11.452  3490  3490 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 13:26:11.452  3490  3490 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 13:26:11.452  3490  3490 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 13:26:11.452  3490  3490 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,03-17 13:26:11.452  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
,03-17 13:26:11.452  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.452  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.452  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.452  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.472  3910  3910 E Zygote  : MountEmulatedStorage()
,03-17 13:26:11.472  3910  3910 E Zygote  : v2
03-17 13:26:11.472  3910  3910 I libpersona: KNOX_SDCARD checking this for 10031
03-17 13:26:11.472  3910  3910 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:11.472  3910  3910 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:11.472  3910  3910 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:11.472  3910  3910 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:11.472  1018  1030 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3910 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,03-17 13:26:11.482  1018  1030 I ActivityManager: Killing 3150:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,03-17 13:26:11.492  1777  3720 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 13:26:11.502  3393  3710 I System.out: pool-10-thread-1 calls detatch()
,03-17 13:26:11.512  1018  1041 D SensorService: [SO] currT = 42270102534, prevT = 41790056180, diff = 480046354, [0.134 0.402 10.132]
03-17 13:26:11.512  1018  1041 D SensorService: [SO] 0.134 0.402 10.132
03-17 13:26:11.512  1018  1041 D SensorService: [SO] [100 -> 255]
,03-17 13:26:11.512  3910  3910 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:11.512  3910  3910 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:11.552  3910  3910 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 13:26:11.562  1018  1152 I ActivityManager: Killing 3199:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,03-17 13:26:11.572  1018  1044 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 13:26:11.572  1018  1044 W ActivityManager: mDVFSHelper.release()
03-17 13:26:11.572  1018  1044 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 13:26:11.582  1018  1018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,03-17 13:26:11.582  1018  1018 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,03-17 13:26:11.582  1018  1018 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:11.592  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,03-17 13:26:11.592  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.592  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.592  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.592  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.602  3930  3930 E Zygote  : MountEmulatedStorage()
,03-17 13:26:11.602  3930  3930 E Zygote  : v2
03-17 13:26:11.602  3930  3930 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:11.602  3930  3930 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:11.602  3930  3930 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-17 13:26:11.602  1018  1018 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3930 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 13:26:11.612  3930  3930 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:11.612  3930  3930 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:11.622  1018  2734 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 13:26:11.632  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3150/cgroup.procs: No such file or directory
03-17 13:26:11.632  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3199/cgroup.procs: No such file or directory
,03-17 13:26:11.632  1018  1152 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 13:26:11.642  3930  3930 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:11.642  3930  3930 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:11.642  1367  1398 W art     : Suspending all threads took: 7.754ms
,03-17 13:26:11.652  3826  3945 I Gmail   : getAccountsCursor
,03-17 13:26:11.652  1018  1388 I AudioService: getStreamVolume 3 index 0
,03-17 13:26:11.672  1018  1052 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{16cd69de u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t11} time:42433
,03-17 13:26:11.682   258   444 I SurfaceFlinger: id=11 Removed NainActivit (7/8)
,03-17 13:26:11.682   258  1841 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-17 13:26:11.682  1018  1152 D PowerManagerService: [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1191 (0x0)
,03-17 13:26:11.712  1018  1505 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-17 13:26:11.712  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 13:26:11.712  1843  1843 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:26:11.732  3268  3373 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,03-17 13:26:11.752  3930  3930 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,03-17 13:26:11.752  1018  1369 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
03-17 13:26:11.752  1018  1369 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,03-17 13:26:11.762  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:11.762  1018  1369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:11.762  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-17 13:26:11.762  1018  1231 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
,03-17 13:26:11.762  1018  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.762  1018  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.762  1018  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:11.762  1018  1231 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:11.782  1018  1231 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3950 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 13:26:11.782  3950  3950 E Zygote  : MountEmulatedStorage()
03-17 13:26:11.782  3950  3950 E Zygote  : v2
03-17 13:26:11.782  3950  3950 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:11.782  3950  3950 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:11.782  3950  3950 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:11.782  3950  3950 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:11.792  3950  3950 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:11.792  3232  3232 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@181aab2 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 13:26:11.792  3232  3232 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@181aab2 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 13:26:11.792  3232  3232 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@1de41a03 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 13:26:11.792  3232  3232 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@1de41a03 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:11.792  3232  3232 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 13:26:11.812  3950  3950 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:11.812  3950  3950 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:11.812  3319  3335 W art     : Suspending all threads took: 16.664ms
,03-17 13:26:11.832  3826  3826 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-17 13:26:11.832  3319  3360 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-17 13:26:11.832  3319  3360 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-17 13:26:11.842  1018  1485 I art     : Explicit concurrent mark sweep GC freed 32875(1687KB) AllocSpace objects, 2(38KB) LOS objects, 33% free, 29MB/44MB, paused 3.227ms total 178.301ms
,03-17 13:26:11.862  3950  3950 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,03-17 13:26:11.872  1018  1018 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 13:26:11.882  3319  3360 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-17 13:26:11.902  3319  3360 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-17 13:26:11.902  3319  3360 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-17 13:26:11.902  3319  3360 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-17 13:26:11.902  3319  3360 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-17 13:26:11.932  1018  1231 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
03-17 13:26:11.932  1018  1231 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,03-17 13:26:11.932  1018  1231 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:11.932  1018  1231 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:11.932  1018  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 13:26:11.942  1018  1369 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:11.942  1018  1369 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 13:26:11.952  1018  1483 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,03-17 13:26:11.952  1018  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,03-17 13:26:11.952  1018  1483 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:11.952  1018  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
03-17 13:26:11.952  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 13:26:12.022  1018  1505 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
,03-17 13:26:12.022  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,03-17 13:26:12.022  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:12.022  1018  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:12.022  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 13:26:12.032  1018  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:12.032  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:12.032  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:12.032  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-17 13:26:12.032  3826  3973 E Gmail   : Error finding the version of the Email provider.....
03-17 13:26:12.032  3826  3973 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-17 13:26:12.032  3826  3973 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
03-17 13:26:12.032  3826  3973 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
03-17 13:26:12.032  3826  3973 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
03-17 13:26:12.032  3826  3973 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 13:26:12.032  3826  3973 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:12.032  3826  3973 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:12.032  3826  3973 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 13:26:12.032  3826  3973 W EmailMigration: We do not support migrating this version of the Email provider.
,03-17 13:26:12.032   257   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-17 13:26:12.032   257   529 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:12.042  3826  3978 I Gmail   : getAccountsCursor
,03-17 13:26:12.052  3412  3412 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-17 13:26:12.052  1018  1505 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,03-17 13:26:12.052  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 13:26:12.062  1843  1843 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:26:12.062  1018  2734 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,03-17 13:26:12.062  1018  2734 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 13:26:12.062  1018  3004 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
03-17 13:26:12.062  1018  3004 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-17 13:26:12.062  1018  3004 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:12.062  1018  3004 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:12.062  1018  3004 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-17 13:26:12.082  1018  3000 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.syncadapters.contacts
,03-17 13:26:12.082  1018  3000 D ActivityManager: retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
,03-17 13:26:12.082  1018  3000 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:12.082  1018  3000 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:12.082  1018  3000 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,03-17 13:26:12.092   257   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 13:26:12.092   257   529 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:12.092  3412  3412 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-17 13:26:12.102   257   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-17 13:26:12.102   257   529 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:12.102  3412  3412 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-17 13:26:12.102  1018  1231 D TimaService: TIMA: in getTimaVersion
,03-17 13:26:12.102  1018  3004 D TimaService: TIMA3: KeyStore3_init
03-17 13:26:12.102  1018  3004 E TLC_TZ_KEYSTORE: : Inside TZ_KEYSTORE_initialize()
03-17 13:26:12.102  1018  3004 D TimaService: TIMA: in getTimaVersion
03-17 13:26:12.102  1018  3004 I TLC_TZ_KEYSTORE: : creating new keystore context...
03-17 13:26:12.102  1018  3004 I TLC_TZ_KEYSTORE: : initializing ccm context...
03-17 13:26:12.102  1018  3004 I TLC_TZ_KEYSTORE: : root = /firmware/image, root_strlen = 15
03-17 13:26:12.102  1018  3004 I TLC_TZ_KEYSTORE: : process = tima_key, process_strlen = 8
03-17 13:26:12.102  1018  3004 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
03-17 13:26:12.102  1018  3004 I TZ: qc_tlc_communication: process = tima_key, process_strlen = 8
03-17 13:26:12.102  1018  3004 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 1088 = 0x440
03-17 13:26:12.102  1018  3004 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 1088 = 0x440
03-17 13:26:12.102  1018  3004 I TZ: qc_tlc_communication: max_message_size = 2176 = 0x880
03-17 13:26:12.102  1018  3004 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x880
03-17 13:26:12.102  1018  3004 D QSEECOMAPI: : App is not loaded in QSEE
,03-17 13:26:12.112  1018  1152 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,03-17 13:26:12.112  1018  1152 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.112  1018  1152 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.112  1018  1152 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.112  1018  1152 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.132  3910  3910 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
,03-17 13:26:12.132  1018  3004 D QSEECOMAPI: : Loaded image: APP id = 10
,03-17 13:26:12.132  1018  3004 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
03-17 13:26:12.132  1018  3004 I TLC_TZ_KEYSTORE: : ctx = 0xb8aa3970, comm = 0xb8a9c8d8, sendmsg = 0xa009e000, recvmsg = 0xa009e440
03-17 13:26:12.132  1018  3004 I TZ_init: : TZ_init: sending initialization request...
,03-17 13:26:12.132  1018  3004 E TZ_init: : TZ_init Process: Secure memory is not initialized!
03-17 13:26:12.132  1018  3004 E TZ_init: : trustlet initialization failed
03-17 13:26:12.132  1018  3004 I TZ_init: : TZ_init_START...
,03-17 13:26:12.142  1018  3004 I TZ_init: : TZ_init_with_data: sending initialization request...
,03-17 13:26:12.142  1018  3004 I TZ_init: : TZ_init: successful initialization
03-17 13:26:12.142  1018  3004 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-17 13:26:12.142  1018  3004 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 10
03-17 13:26:12.142  1018  3004 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
,03-17 13:26:12.142  3986  3986 E Zygote  : MountEmulatedStorage()
03-17 13:26:12.142  3986  3986 E Zygote  : v2
03-17 13:26:12.142  3986  3986 I libpersona: KNOX_SDCARD checking this for 10104
03-17 13:26:12.142  3986  3986 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:12.142  3986  3986 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:12.142  3986  3986 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:12.142  1018  1152 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3986 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
03-17 13:26:12.142  3986  3986 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 13:26:12.152  1018  1388 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
,03-17 13:26:12.152  1018  1388 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
03-17 13:26:12.152  1018  1485 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 13:26:12.152  1018  1485 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-17 13:26:12.152  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
03-17 13:26:12.152  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,03-17 13:26:12.152  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:12.152  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:12.152  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 13:26:12.152  1647  3984 I GoogleHttpClient: GMS http client unavailable, use old client
,03-17 13:26:12.172  1367  3266 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,03-17 13:26:12.172  1367  3266 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,03-17 13:26:12.172  1367  3266 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
,03-17 13:26:12.182  1018  1030 I ActivityManager: Killing 3119:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,03-17 13:26:12.192  1018  1388 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 13:26:12.192  1018  1388 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 13:26:12.192  3826  3995 I Gmail   : Observing account changes for notifications
,03-17 13:26:12.202  3986  3986 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:12.202  3986  3986 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:12.212  1018  1388 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 13:26:12.212  1018  1388 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-17 13:26:12.222  1018  1485 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-17 13:26:12.222  1018  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 13:26:12.222  1843  1843 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:26:12.232  3910  3910 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
,03-17 13:26:12.242  3986  3986 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 13:26:12.252  3826  3826 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@35bda48b that was originally bound here
03-17 13:26:12.252  3826  3826 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@35bda48b that was originally bound here
03-17 13:26:12.252  3826  3826 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
03-17 13:26:12.252  3826  3826 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
03-17 13:26:12.252  3826  3826 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
03-17 13:26:12.252  3826  3826 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
03-17 13:26:12.252  3826  3826 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
03-17 13:26:12.252  3826  3826 E ActivityThread: 	at com.android.emailcommon.service.ah.a(SourceFile:181)
03-17 13:26:12.252  3826  3826 E ActivityThread: 	at com.android.emailcommon.service.ah.e(SourceFile:224)
03-17 13:26:12.252  3826  3826 E ActivityThread: 	at com.android.email.service.n.c(SourceFile:161)
03-17 13:26:12.252  3826  3826 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:173)
03-17 13:26:12.252  3826  3826 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:117)
03-17 13:26:12.252  3826  3826 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:318)
03-17 13:26:12.252  3826  3826 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1308)
03-17 13:26:12.252  3826  3826 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 13:26:12.252  3826  3826 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:12.252  3826  3826 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:12.252  3826  3826 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 13:26:12.252  1018  1152 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@1d3d26d8
,03-17 13:26:12.262  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
03-17 13:26:12.262  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:12.262  3930  3965 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 13:26:12.262  3930  3965 I AMMetaDataParserService: getResourcePackageName:assistantlist
03-17 13:26:12.262  3930  3965 I AMMetaDataParserService: Resource data:2131165186
,03-17 13:26:12.272  3930  3965 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 13:26:12.272  3930  3965 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:12.272  3930  3965 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 13:26:12.272  3930  3965 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 13:26:12.272  3930  3965 I AMMetaDataParserService: getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
03-17 13:26:12.272  3930  3965 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:12.282  3950  3950 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
,03-17 13:26:12.282  1018  1369 D ActivityManager: startService callerProcessName:com.samsung.android.bbc.bbcagent, calleePkgName: com.samsung.android.bbc.bbcagent
03-17 13:26:12.282  1018  1369 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,03-17 13:26:12.282  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:12.282  1018  1369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:12.282  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,03-17 13:26:12.292  1018  1505 D ActivityManager: startProcessLocked calleePkgName: com.sec.bcservice, hostingType: broadcast
,03-17 13:26:12.292  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.292  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.292  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.292  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.292  3930  3965 I AMMetaDataParserService: Icon data: ResourceEnter URL2131755289android.intent.action.doInputURL2130837509
,03-17 13:26:12.302  1018  1043 W libprocessgroup: failed to open /acct/uid_10072/pid_3119/cgroup.procs: No such file or directory
,03-17 13:26:12.302  4029  4029 E Zygote  : MountEmulatedStorage()
03-17 13:26:12.302  4029  4029 E Zygote  : v2
03-17 13:26:12.302  4029  4029 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:12.302  4029  4029 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:12.302  4029  4029 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:12.312  1018  1505 I ActivityManager: Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=4029 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 13:26:12.312  4029  4029 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:12.312  4029  4029 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:12.322  1018  1231 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
03-17 13:26:12.322  1018  1231 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-17 13:26:12.322  1018  1231 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:12.332  1018  1231 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:12.332  1018  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 13:26:12.332  4029  4029 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:12.342  4029  4029 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:12.352  1018  1483 I ActivityManager: Killing 3023:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,03-17 13:26:12.352  4029  4029 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 13:26:12.362  1018  2734 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 13:26:12.362  3910  3910 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,03-17 13:26:12.362  3910  3910 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,03-17 13:26:12.372  4029  4029 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,03-17 13:26:12.372  1018  1031 D ActivityManager: startService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.bcservice
03-17 13:26:12.372  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,03-17 13:26:12.372  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:12.372  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:12.372  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,03-17 13:26:12.372  3910  3910 D DialogFlow: initQueue()
,03-17 13:26:12.392  4029  4029 I F_PHONE : [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,03-17 13:26:12.392  4029  4029 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,03-17 13:26:12.392  1018  2999 D ActivityManager: bindService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.phone, action: null
03-17 13:26:12.392  1018  2999 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,03-17 13:26:12.392  1018  2999 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:12.392  1018  2999 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:12.392  1018  2999 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,03-17 13:26:12.402  1018  1483 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,03-17 13:26:12.402  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.402  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.402  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.402  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.412  4053  4053 E Zygote  : MountEmulatedStorage()
,03-17 13:26:12.412  4053  4053 I libpersona: KNOX_SDCARD checking this for 10032
03-17 13:26:12.412  4053  4053 E Zygote  : v2
03-17 13:26:12.412  4053  4053 I libpersona: KNOX_SDCARD not a persona,
,03-17 13:26:12.422  4053  4053 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:12.422  1018  1483 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4053 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,03-17 13:26:12.422  4053  4053 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:12.422  4053  4053 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:12.432  3826  3981 E SQLiteLog: (283) recovered 61 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-17 13:26:12.432  4029  4029 D F_PHONE : [[com.sec.bcservice]] onServiceConnected()
03-17 13:26:12.432  4029  4029 I F_PHONE : default registerAction()
03-17 13:26:12.432  4029  4029 I F_PHONE : [[com.sec.bcservice]] sendPendingMessage()
,03-17 13:26:12.452  4053  4053 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:12.452  4053  4053 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:12.462  1018  1505 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
03-17 13:26:12.462  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,03-17 13:26:12.462  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:12.462  1018  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:12.462  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 13:26:12.462  3930  3965 I AMMetaDataParserService: Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,03-17 13:26:12.472  1018  2734 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
03-17 13:26:12.472  1018  2734 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-17 13:26:12.472  1018  2734 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:12.472  1018  2734 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:12.472  1018  2734 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 13:26:12.482  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
,03-17 13:26:12.482  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,03-17 13:26:12.482  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:12.482  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:12.482  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 13:26:12.492  3930  3965 I AMMetaDataParserService: Icon data: ResourceNew Tab2131755460android.intent.action.doNewWindow2130837510
,03-17 13:26:12.502  1955  1955 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,03-17 13:26:12.502  1018  1152 D ActivityManager: startService callerProcessName:com.qualcomm.qti.services.secureui, calleePkgName: com.qualcomm.qti.services.secureui
,03-17 13:26:12.502  1018  1152 D ActivityManager: retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
,03-17 13:26:12.502  1018  1152 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:12.502  1018  1152 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:12.502  1018  1152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,03-17 13:26:12.512  1018  1505 D ActivityManager: startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
03-17 13:26:12.512  1955  1955 D SecUISvc: Service started flags 0 startId 1
,03-17 13:26:12.512  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.512  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.512  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.512  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.512  1955  4070 D SecUISvc: Thread created.
,03-17 13:26:12.522  4072  4072 E Zygote  : MountEmulatedStorage()
03-17 13:26:12.522  4072  4072 E Zygote  : v2
03-17 13:26:12.522  4072  4072 I libpersona: KNOX_SDCARD checking this for 10028
03-17 13:26:12.522  4072  4072 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:12.522  4072  4072 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:12.532  4072  4072 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 13:26:12.532  1018  1505 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4072 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:12.532  4072  4072 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
03-17 13:26:12.532  1018  1043 W libprocessgroup: failed to open /acct/uid_10085/pid_3023/cgroup.procs: No such file or directory,
,03-17 13:26:12.532  1018  1369 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
03-17 13:26:12.532  1018  1369 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
03-17 13:26:12.532  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:12.532  1018  1369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:12.532  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
03-17 13:26:12.552  3930  3965 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.,SelectBookmarkFolderActivity
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
03-17 13:26:12.552  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
03-17 13:26:12.552  4072  4072 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:12.562  4072  4072 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:12.572  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
03-17 13:26:12.572  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:12.572  3930  3965 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:12.572  3930  3965 I AMMetaDataParserService: Resource data:2131034113
03-17 13:26:12.572  3930  3965 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 13:26:12.572  3930  3965 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:12.582  3930  3965 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
03-17 13:26:12.582  3930  3965 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-17 13:26:12.582  3930  3965 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:12.602  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:12.602  3930  3965 I GFX construct_block_size_descriptor_2d second part: took 2.129323ms for 0*0 texture 0
,03-17 13:26:12.612  3930  3965 I GFX generate_partition_tables: took 7.413853ms for 0*0 texture 0
,03-17 13:26:12.612  3930  3965 I GFX raster: took 10.904895ms for 96*96 texture 0
,03-17 13:26:12.612  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb855b708 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8572cb8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:12.632  3930  3965 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-17 13:26:12.672  1018  3004 I ActivityManager: Killing 3286:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,03-17 13:26:12.672  1018  3004 I ActivityManager: Killing 3251:com.samsung.android.app.colorblind/1000 (adj 15): empty #32
,03-17 13:26:12.692  1018  3000 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
,03-17 13:26:12.692  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.692  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.692  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:12.692  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:12.692  3826  3981 E File    : fail readDirectory() errno=2
,03-17 13:26:12.702  3826  4016 I Gmail   : notifyAccountChanged
,03-17 13:26:12.702  1018  1152 W SEAMService:  hashset_to_int_array returning null
,03-17 13:26:12.702  4092  4092 E Zygote  : MountEmulatedStorage()
03-17 13:26:12.702  4092  4092 E Zygote  : v2
03-17 13:26:12.702  4092  4092 I libpersona: KNOX_SDCARD checking this for 10033
03-17 13:26:12.702  4092  4092 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:12.712  4092  4092 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:12.712  4092  4092 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:12.712  1018  3000 I ActivityManager: Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4092 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-17 13:26:12.712  4092  4092 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
03-17 13:26:12.712  1018  3000 I ActivityManager: Killing 3319:com.policydm/1000 (adj 15): empty #31
,03-17 13:26:12.712  3826  4016 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-17 13:26:12.722  1018  1030 W SEAMService:  hashset_to_int_array returning null
,03-17 13:26:12.732  3950  3950 E SQLiteLog: (284) automatic index on seams_container_info(seams_container_id)
,03-17 13:26:12.732  3268  3373 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,03-17 13:26:12.732  3826  4091 I Gmail   : getAccountsCursor
,03-17 13:26:12.742  1018  3000 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-17 13:26:12.742  1018  3000 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 13:26:12.742  3950  3950 E SQLiteLog: (284) automatic index on seams_container_info(sp_id)
,03-17 13:26:12.742  4092  4092 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:12.742  4092  4092 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:12.742  1843  1843 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:26:12.752  1018  2734 W SEAMService:  hashset_to_int_array returning null
,03-17 13:26:12.762  1018  3000 I ActivityManager: Killing 3298:com.google.android.configupdater/u0a86 (adj 15): empty #31
,03-17 13:26:12.792  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3251/cgroup.procs: No such file or directory
03-17 13:26:12.792  1018  1043 W libprocessgroup: failed to open /acct/uid_10150/pid_3286/cgroup.procs: No such file or directory
,03-17 13:26:12.792  1018  3000 D ActivityManager: bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
03-17 13:26:12.792  1018  3000 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-17 13:26:12.792  3826  4016 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
03-17 13:26:12.792  1018  3000 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:12.792  1018  3000 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:12.792  1018  3000 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 13:26:12.822  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3319/cgroup.procs: No such file or directory
03-17 13:26:12.822  1018  1043 W libprocessgroup: failed to open /acct/uid_10086/pid_3298/cgroup.procs: No such file or directory
,03-17 13:26:12.912  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:12.912  1018  2749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,03-17 13:26:12.912  3930  3965 I GFX raster: took 0.924635ms for 96*96 texture 0
,03-17 13:26:12.922  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb855b708 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb857adb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:12.932  3930  3965 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 13:26:12.942  3490  3501 D PCWCLIENTTRACE_AccountAppFacade2_0: unregister AuthInfo UpdateReceiver v2.0
,03-17 13:26:12.962   291   291 E SMD     : DCD OFF,
,03-17 13:26:12.992  3412  4046 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A500FU Build/LRX22G)
,03-17 13:26:12.992  3412  4046 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,03-17 13:26:12.992  3412  4046 I System.out: Thread-512(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 13:26:12.992  3412  4046 I System.out: Thread-512(ApacheHTTPLog):isSBSettingEnabled false
,03-17 13:26:12.992  3412  4046 I System.out: Thread-512(ApacheHTTPLog):isShipBuild true
,03-17 13:26:12.992  3412  4046 I System.out: Thread-512(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 13:26:12.992  3412  4046 I System.out: Thread-512(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-17 13:26:12.992   278   875 D EnterpriseController: uids 10166
03-17 13:26:12.992   278   875 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 13:26:12.992   278   875 D Netd    : getNetworkForDns: using netid 502 for uid 10166
,03-17 13:26:13.012  3826  4016 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 13:26:13.012  3826  4016 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-17 13:26:13.052  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.052  3930  3965 I GFX construct_block_size_descriptor_2d second part: took 2.137917ms for 0*0 texture 0
,03-17 13:26:13.052  4092  4092 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 13:26:13.052  4092  4092 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:13.052  4092  4092 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 13:26:13.082  3930  3965 I GFX generate_partition_tables: took 7.460624ms for 0*0 texture 0
,03-17 13:26:13.082  3930  3965 I GFX raster: took 10.613072ms for 96*96 texture 0
03-17 13:26:13.082  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8577780 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb85778d8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.082  3930  3965 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 13:26:13.102  4092  4092 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 13:26:13.102  1647  1660 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
03-17 13:26:13.102  4092  4092 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:13.102  4092  4092 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:13.102  1647  2755 I art     : Explicit concurrent mark sweep GC freed 4042(182KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 761us total 70.652ms
,03-17 13:26:13.132  1018  2749 D SSRM:n  : SIOP:: AP = 400
,03-17 13:26:13.132  4092  4092 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 13:26:13.132  4092  4092 W ResourcesManager: Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
03-17 13:26:13.132  4092  4092 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 13:26:13.142  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.142  3930  3965 I GFX raster: took 0.720885ms for 96*96 texture 0
03-17 13:26:13.142  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb857c148 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb857c2a0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.152  3930  3965 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 13:26:13.162  4072  4072 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-17 13:26:13.172  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.172  3930  3965 I GFX raster: took 1.010938ms for 96*96 texture 0
03-17 13:26:13.172  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8579fb0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb857a078 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.192  3930  3965 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 13:26:13.202  3986  4123 I Babel   : MmsConfig: mnc/mcc: 0/0
03-17 13:26:13.202  3986  4123 I Babel   : MmsConfig.loadMmsSettings
,03-17 13:26:13.202  3986  4123 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
03-17 13:26:13.202  3986  4123 I Babel   : MmsConfig.loadFromDatabase
,03-17 13:26:13.242  3986  4123 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,03-17 13:26:13.242  3986  4123 I Babel   : MmsConfig.loadFromResources
,03-17 13:26:13.262  3986  4123 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,03-17 13:26:13.262  3986  4123 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,03-17 13:26:13.282  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.282  3826  3945 I Gmail   : getAccountsCursor
03-17 13:26:13.282  3930  3965 I GFX raster: took 0.753802ms for 96*96 texture 0
03-17 13:26:13.282  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb857b838 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb857b990 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.282  1018  3004 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,03-17 13:26:13.282  1018  3004 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-17 13:26:13.282  1843  1843 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:26:13.292  3930  3965 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 13:26:13.312  1018  1485 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
03-17 13:26:13.312  1018  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,03-17 13:26:13.312  1018  1485 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:13.312  1018  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:13.312  1018  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 13:26:13.312  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.312  3930  3965 I GFX raster: took 0.880885ms for 96*96 texture 0
03-17 13:26:13.312  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb857a2d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb857a3a0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.312  3986  3986 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-17 13:26:13.332  3930  3965 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 13:26:13.372  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.372  3930  3965 I GFX raster: took 0.519792ms for 96*96 texture 0
03-17 13:26:13.372  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8579f50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb855b7d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.372  3930  3965 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 13:26:13.382  1018  2828 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:26:13.392  3986  3986 I Babel_StickerModule: App launched.
,03-17 13:26:13.412  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
03-17 13:26:13.412  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:13.412  3930  3965 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:13.412  3930  3965 I AMMetaDataParserService: Resource data:2131034113
,03-17 13:26:13.412  3930  3965 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-17 13:26:13.412  3930  3965 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:13.412  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.412  3930  3965 I GFX raster: took 0.806666ms for 96*96 texture 0
03-17 13:26:13.412  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb855b708 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb855b7d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.422  3930  3965 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-17 13:26:13.442  3986  3986 V Babel   : babel boot account: SMS
,03-17 13:26:13.452  3986  3986 W Babel   : EsDatabaseHelper.static should not be called on main thread [called on main thread]
,03-17 13:26:13.452  3986  3986 W Babel   : java.lang.Exception
03-17 13:26:13.452  3986  3986 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
03-17 13:26:13.452  3986  3986 W Babel   : 	at aes.<clinit>(SourceFile:95)
03-17 13:26:13.452  3986  3986 W Babel   : 	at ckh.<init>(SourceFile:103)
03-17 13:26:13.452  3986  3986 W Babel   : 	at ckh.a(SourceFile:67)
03-17 13:26:13.452  3986  3986 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
03-17 13:26:13.452  3986  3986 W Babel   : 	at bhn.a(SourceFile:301)
03-17 13:26:13.452  3986  3986 W Babel   : 	at bhn.a(SourceFile:137)
03-17 13:26:13.452  3986  3986 W Babel   : 	at bhn.a(SourceFile:126)
03-17 13:26:13.452  3986  3986 W Babel   : 	at bhn.a(SourceFile:159)
03-17 13:26:13.452  3986  3986 W Babel   : 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
03-17 13:26:13.452  3986  3986 W Babel   : 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
03-17 13:26:13.452  3986  3986 W Babel   : 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-17 13:26:13.452  3986  3986 W Babel   : 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-17 13:26:13.452  3986  3986 W Babel   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:13.452  3986  3986 W Babel   : 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:13.452  3986  3986 W Babel   : 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 13:26:13.452  3986  3986 W Babel   : 	at java.lang.reflect.Method.invoke(Native Method)
03-17 13:26:13.452  3986  3986 W Babel   : 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 13:26:13.452  3986  3986 W Babel   : 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 13:26:13.452  3986  3986 W Babel   : 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-17 13:26:13.452  3986  3986 W Babel   : EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,03-17 13:26:13.452  3986  3986 W Babel   : java.lang.Exception
03-17 13:26:13.452  3986  3986 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
03-17 13:26:13.452  3986  3986 W Babel   : 	at aes.a(SourceFile:145)
03-17 13:26:13.452  3986  3986 W Babel   : 	at ckh.<init>(SourceFile:103)
03-17 13:26:13.452  3986  3986 W Babel   : 	at ckh.a(SourceFile:67)
03-17 13:26:13.452  3986  3986 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
03-17 13:26:13.452  3986  3986 W Babel   : 	at bhn.a(SourceFile:301)
03-17 13:26:13.452  3986  3986 W Babel   : 	at bhn.a(SourceFile:137)
03-17 13:26:13.452  3986  3986 W Babel   : 	at bhn.a(SourceFile:126)
03-17 13:26:13.452  3986  3986 W Babel   : 	at bhn.a(SourceFile:159)
03-17 13:26:13.452  3986  3986 W Babel   : 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
03-17 13:26:13.452  3986  3986 W Babel   : 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
03-17 13:26:13.452  3986  3986 W Babel   : 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-17 13:26:13.452  3986  3986 W Babel   : 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-17 13:26:13.452  3986  3986 W Babel   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:13.452  3986  3986 W Babel   : 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:13.452  3986  3986 W Babel   : 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 13:26:13.452  3986  3986 W Babel   : 	at java.lang.reflect.Method.invoke(Native Method)
03-17 13:26:13.452  3986  3986 W Babel   : 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 13:26:13.452  3986  3986 W Babel   : 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 13:26:13.452  3986  3986 W Babel   : 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-17 13:26:13.482  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.482  3930  3965 I GFX raster: took 0.853854ms for 96*96 texture 0
,03-17 13:26:13.482  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb855b708 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb855b7d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.482  3412  4046 I System.out: Thread-512 calls detatch()
,03-17 13:26:13.492  3930  3965 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 13:26:13.502  4072  4072 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,03-17 13:26:13.512  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,03-17 13:26:13.512  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-17 13:26:13.512  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:13.512  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:13.512  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 13:26:13.512  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.512  3930  3965 I GFX raster: took 0.599896ms for 96*96 texture 0
03-17 13:26:13.512  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8577780 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb855b7d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.522  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,03-17 13:26:13.522  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-17 13:26:13.522  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:13.522  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:13.522  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 13:26:13.522  3930  3965 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 13:26:13.522  1018  3001 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
03-17 13:26:13.522  1018  3001 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-17 13:26:13.522  1018  3001 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:13.522  1018  3001 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:13.522  1018  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 13:26:13.522  3986  3986 V Babel   : babel boot account: thalitester@gmail.com
,03-17 13:26:13.542  4072  4072 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 13:26:13.542  4072  4072 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-17 13:26:13.552  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.552  3930  3965 I GFX raster: took 0.724218ms for 96*96 texture 0
03-17 13:26:13.552  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb857c148 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb855b7d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.552  3986  3986 W Babel   : EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,03-17 13:26:13.552  3986  3986 W Babel   : java.lang.Exception
03-17 13:26:13.552  3986  3986 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
03-17 13:26:13.552  3986  3986 W Babel   : 	at aes.a(SourceFile:145)
03-17 13:26:13.552  3986  3986 W Babel   : 	at ckh.<init>(SourceFile:103)
03-17 13:26:13.552  3986  3986 W Babel   : 	at ckh.a(SourceFile:67)
03-17 13:26:13.552  3986  3986 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
03-17 13:26:13.552  3986  3986 W Babel   : 	at bhn.a(SourceFile:301)
03-17 13:26:13.552  3986  3986 W Babel   : 	at bhn.a(SourceFile:137)
03-17 13:26:13.552  3986  3986 W Babel   : 	at bhn.a(SourceFile:126)
03-17 13:26:13.552  3986  3986 W Babel   : 	at bhn.a(SourceFile:159)
03-17 13:26:13.552  3986  3986 W Babel   : 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
03-17 13:26:13.552  3986  3986 W Babel   : 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
03-17 13:26:13.552  3986  3986 W Babel   : 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-17 13:26:13.552  3986  3986 W Babel   : 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-17 13:26:13.552  3986  3986 W Babel   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:13.552  3986  3986 W Babel   : 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:13.552  3986  3986 W Babel   : 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 13:26:13.552  3986  3986 W Babel   : 	at java.lang.reflect.Method.invoke(Native Method)
03-17 13:26:13.552  3986  3986 W Babel   : 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 13:26:13.552  3986  3986 W Babel   : 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 13:26:13.552  3986  3986 W Babel   : 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-17 13:26:13.552  3930  3965 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 13:26:13.582  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.582  3930  3965 I GFX raster: took 0.938230ms for 96*96 texture 0
03-17 13:26:13.582  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8579fb0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb855b7d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.602  3930  3965 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 13:26:13.602  1018  1231 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,03-17 13:26:13.602  1018  1231 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-17 13:26:13.602  1018  1231 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:13.602  1018  1231 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:13.602  1018  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 13:26:13.602  1018  1369 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,03-17 13:26:13.602  1018  1369 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-17 13:26:13.612  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:13.612  1018  1369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:13.612  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 13:26:13.612  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
03-17 13:26:13.612  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-17 13:26:13.612  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:13.612  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:13.612  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 13:26:13.612  1018  3000 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,03-17 13:26:13.612  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.622  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.622  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.622  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.632  4153  4153 E Zygote  : MountEmulatedStorage()
03-17 13:26:13.632  4153  4153 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:13.632  4153  4153 E Zygote  : v2
03-17 13:26:13.632  4153  4153 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:13.632  1018  3000 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4153 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 13:26:13.642  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,03-17 13:26:13.642  3930  3965 I GFX raster: took 0.783490ms for 96*96 texture 0
03-17 13:26:13.642  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb857b838 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb855b7d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.642  4072  4124 D Volley  : [601] DiskBasedCache.clear: Cache cleared.
,03-17 13:26:13.642  4153  4153 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:13.642  3930  3965 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 13:26:13.642  4153  4153 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:13.642  4153  4153 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:13.652  1018  1231 I ActivityManager: Killing 3393:com.dropbox.android/u0a92 (adj 15): empty #31
,03-17 13:26:13.662  4072  4159 D Ads     : Skipping gmscore version check
03-17 13:26:13.662  1018  1388 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:13.662  4072  4134 D Volley  : [608] DiskBasedCache.clear: Cache cleared.
,03-17 13:26:13.662  1018  1388 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:13.662  1018  1388 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:13.662  1018  1388 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:13.682  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.682  4153  4153 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:13.682  3930  3965 I GFX raster: took 0.829114ms for 96*96 texture 0
03-17 13:26:13.682  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb857a2d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8579868 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.682  4153  4153 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:13.692  4092  4092 I Process : Sending signal. PID: 4092 SIG: 9
,03-17 13:26:13.702  1018  1388 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
03-17 13:26:13.702  1018  1388 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,03-17 13:26:13.702  1018  1388 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:13.702  1018  1388 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:13.702  1018  1388 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-17 13:26:13.712  1018  1485 I ActivityManager: Process com.sec.android.app.sns3 (pid 4092)(adj 0) has died(36,1160)
,03-17 13:26:13.712   286   838 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,03-17 13:26:13.712   286   838 W QCamera2Factory: getCameraInfo: X
,03-17 13:26:13.722   286   841 W QCamera2Factory: getCameraInfo: E, camera_id = 1
03-17 13:26:13.722   286   841 W QCamera2Factory: getCameraInfo: X
,03-17 13:26:13.722  1018  1369 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:13.722  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:13.722  1018  1369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:13.722  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-17 13:26:13.722  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,03-17 13:26:13.732  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.732  3930  3965 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
03-17 13:26:13.732  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.732  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.732  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:13.742  3268  3373 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec,
,03-17 13:26:13.752  1018  1044 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4171 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a,
,03-17 13:26:13.752  4171  4171 E Zygote  : MountEmulatedStorage()
03-17 13:26:13.752  4171  4171 E Zygote  : v2
03-17 13:26:13.752  4171  4171 I libpersona: KNOX_SDCARD checking this for 10034
03-17 13:26:13.752  4171  4171 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:13.752  3910  4030 I System.out: INFO:Resource not found:/Common.properties Using default values
03-17 13:26:13.752  4171  4171 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 13:26:13.752  4171  4171 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 13:26:13.752  4171  4171 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:13.762  2079  4168 D FileApkUtils: Optimizing (staging complete)
,03-17 13:26:13.762  2079  4168 D FileApkUtils: Optimizing: DynamiteModules-prod.apk [0224a548494bce36274e23f9f1b42d4fbe3d4d8de53a7872e503f8974e43c3c3]
,03-17 13:26:13.762  4072  4072 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-17 13:26:13.762  2079  4168 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
03-17 13:26:13.762  4072  4072 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,03-17 13:26:13.772   315   315 I art     : Explicit concurrent mark sweep GC freed 8726(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 648us total 26.671ms
,03-17 13:26:13.792  4171  4171 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:13.792  4171  4171 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:13.792  3986  3986 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-17 13:26:13.792   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 648us total 19.637ms
,03-17 13:26:13.802  3986  3986 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 13:26:13.802  3986  3986 W AudioCapabilities: Unsupported mime audio/qcelp
03-17 13:26:13.802  2079  4168 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk appears to be unoptimized.
03-17 13:26:13.802  2079  4168 D DexOptUtils: Lollipop platform, using <isa> directory.
,03-17 13:26:13.802  2079  4168 D DexOptUtils: Instantiating DexClassLoader to force creation of odex.
03-17 13:26:13.802  2079  4168 D DexOptUtils: Primary ABI of odexing process is armeabi-v7a
,03-17 13:26:13.812   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 749us total 19.604ms
,03-17 13:26:13.832  1018  1043 W libprocessgroup: failed to open /acct/uid_10092/pid_3393/cgroup.procs: No such file or directory
,03-17 13:26:13.832  1018  1505 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 13:26:13.832  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.service.recording.FitRecordingBroker; callingUser = 0; userId(target) = 0
,03-17 13:26:13.832  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:13.842  1018  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:13.842  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:13.842  3986  3986 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,03-17 13:26:13.842  3986  3986 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,03-17 13:26:13.852  3986  3986 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,03-17 13:26:13.852  3986  3986 W AudioCapabilities: Unsupported mime audio/x-ima
,03-17 13:26:13.852  3986  3986 W AudioCapabilities: Unsupported mime audio/qcelp
,03-17 13:26:13.852  3986  3986 W AudioCapabilities: Unsupported mime audio/evrc
,03-17 13:26:13.872  3986  3986 W VideoCapabilities: Unsupported mime video/wvc1
,03-17 13:26:13.882  3986  3986 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 13:26:13.902  3986  3986 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es,
,03-17 13:26:13.902  3986  3986 W VideoCapabilities: Unsupported mime video/wvc1,
,03-17 13:26:13.902  3986  3986 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-17 13:26:13.902  4072  4072 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4,
,03-17 13:26:13.902  3986  3986 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,03-17 13:26:13.912  3986  3986 W VideoCapabilities: Unsupported mime video/x-ms-wmv8,
,03-17 13:26:13.932  1018  1505 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,03-17 13:26:13.932  3986  3986 W VideoCapabilities: Unsupported mime video/mp43
,03-17 13:26:13.932  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
03-17 13:26:13.932  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:13.932  3930  3965 I GFX raster: took 0.524844ms for 96*96 texture 0
03-17 13:26:13.932  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8198588 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81990b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:13.932  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:13.932  1018  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:13.942  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-17 13:26:13.942  4053  4087 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 13:26:13.942  3930  3965 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 13:26:13.942  1018  1231 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:13.942  1018  1231 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:13.952  3986  3986 W VideoCapabilities: Unsupported mime video/sorenson
,03-17 13:26:13.952  1018  1231 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:13.952  1018  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:13.962  3986  3986 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,03-17 13:26:13.982  1018  1485 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactShortcut
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activityalias.DialShortcut
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activityalias.MessageShortcut
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 13:26:13.982  3930 , 3965 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: Resource data:2131034112
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_detail
03-17 13:26:13.982  3930  3965 I AMMetaDataParserService: getResourceTypeNamexml
03-17 13:26:13.982  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 13:26:13.982  3930  3965 I GFX raster: took 0.626250ms for 96*96 texture 0
03-17 13:26:13.982  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb855a990 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb853d430 counterpartCT=4 counterpartW=96 counterparth=96
03-17 13:26:13.992  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.992  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.992  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:13.992  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:14.002  4072  4072 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
03-17 13:26:14.002  4053  4087 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 13:26:14.002  4053  4087 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:14.002  4053  4087 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:14.002  4193  4193 E Zygote  : MountEmulatedStorage()
03-17 13:26:14.002  4193  4193 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:14.002  4193  4193 E Zygote  : v2
03-17 13:26:14.002  4193  4193 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:14.002  4193  4193 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 13:26:14.002  1018  1485 I ActivityManager: Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=4193 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 13:26:14.012  4193  4193 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:14.012  4193  4193 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:14.012  1018  1485 D ActivityManager: startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
03-17 13:26:14.012  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:14.012  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:14.012  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:14.012  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:14.022  3930  3965 I AMMetaDataParserService: Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,03-17 13:26:14.022  3986  3986 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-17 13:26:14.022  4188  4188 I dex2oat : ----------------------------------------------------
03-17 13:26:14.022  4188  4188 I dex2oat : <SS>: S T A R T I N G . . .
03-17 13:26:14.022  4188  4188 I dex2oat : <SS>: Zip is absent. Canceled.
,03-17 13:26:14.022  4188  4188 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk --oat-fd=40 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-17 13:26:14.052  4193  4193 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:14.052  4193  4193 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:14.062  4209  4209 E Zygote  : MountEmulatedStorage()
03-17 13:26:14.062  4209  4209 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:14.062  4209  4209 E Zygote  : v2
03-17 13:26:14.062  4209  4209 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:14.072  1018  1485 I ActivityManager: Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4209 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 13:26:14.072  1018  1485 I ActivityManager: Killing 3432:com.fmm.dm/1000 (adj 15): empty #31
,03-17 13:26:14.082  1018  2999 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 13:26:14.082  1018  2999 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,03-17 13:26:14.082  1018  2999 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:14.082  1018  2999 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:14.082  1018  2999 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:14.112  4209  4209 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 13:26:14.112  4209  4209 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 13:26:14.112  4209  4209 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-17 13:26:14.112  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 13:26:14.122  3930  3965 I GFX raster: took 0.674999ms for 96*96 texture 0
03-17 13:26:14.122  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb855a990 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb82a7998 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.122  3930  3965 I AMMetaDataParserService: Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,03-17 13:26:14.132  1843  1843 D ChimeraCfgMgr: Reading stored module config
,03-17 13:26:14.152  1018  1030 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,03-17 13:26:14.152  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,03-17 13:26:14.162  4209  4209 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:14.162  4209  4209 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:14.182  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:14.182  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:14.182  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-17 13:26:14.182  1843  1843 D WearableService: callingUid 10012, callindPid: 1843
,03-17 13:26:14.192  1018  1388 I ActivityManager: Killing 3449:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,03-17 13:26:14.202  1843  1843 E GmsWearableNodeHelper: GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-17 13:26:14.212  4193  4193 D KnoxSetupWizardDbHelper: dbMigrationFlag : false
,03-17 13:26:14.222  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.222  3930  3965 I GFX raster: took 0.670105ms for 96*96 texture 0
03-17 13:26:14.222  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb855b568 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb81990b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.252  4193  4193 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,03-17 13:26:14.262  3930  3965 I AMMetaDataParserService: Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,03-17 13:26:14.272  4193  4193 D KnoxShortcutUtil: getIsShortcutMigrationFor_2_3_0_Done true
,03-17 13:26:14.272  4193  4193 D ShortcutReceiver:  KnoxContainerVersion 2.4.0
,03-17 13:26:14.272  4193  4193 D ShortcutReceiver:  shortcut migration not required 
,03-17 13:26:14.282  1018  3000 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,03-17 13:26:14.282  2079  2079 W InstanceID/Rpc: Found 10012
,03-17 13:26:14.282  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:14.282  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:14.282  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:14.282  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:14.292  4209  4209 I DBG_POLICYDM: [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
03-17 13:26:14.292  4209  4209 I DBG_POLICYDM: [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-17 13:26:14.292  4209  4209 I DBG_POLICYDM: [com.policydm.eng.core.XDMMsg(70/xdmSendMessage)] waiting for DM_TaskHandler create
,03-17 13:26:14.302  4235  4235 E Zygote  : MountEmulatedStorage()
03-17 13:26:14.302  4235  4235 E Zygote  : v2
03-17 13:26:14.302  4235  4235 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:14.302  4235  4235 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:14.302  4235  4235 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 13:26:14.302  1018  3000 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4235 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 13:26:14.302  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.302  4235  4235 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:14.302  4235  4235 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:14.312  3930  3965 I GFX raster: took 0.669114ms for 96*96 texture 0
03-17 13:26:14.312  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb853d430 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb82a7998 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.312  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3432/cgroup.procs: No such file or directory
,03-17 13:26:14.332  1018  1043 W libprocessgroup: failed to open /acct/uid_10057/pid_3449/cgroup.procs: No such file or directory
03-17 13:26:14.332  3930  3965 I AMMetaDataParserService: Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,03-17 13:26:14.332  1018  1231 I ActivityManager: Killing 3517:com.fmm.ds/1000 (adj 15): empty #31
,03-17 13:26:14.332  4235  4235 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:14.332  4235  4235 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
,03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
,03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
,03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
,03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
,03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
,03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
,03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: Resource data:2131034113
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-17 13:26:14.352  3930  3965 I AMMetaDataParserService: getResourceTypeNamexml
03-17 13:26:14.352  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 13:26:14.362  3930  3965 I GFX raster: took 0.859479ms for 96*96 texture 0,
03-17 13:26:14.362  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb82a7998 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb81990b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.372  3930  3965 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-17 13:26:14.382  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.382  3930  3965 I GFX raster: took 0.833957ms for 96*96 texture 0
,03-17 13:26:14.382  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb82a7998 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb81990b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.382  4235  4235 E KnoxSetupWizardClient: isShipMode : 1
03-17 13:26:14.382  4235  4235 I KnoxSetupWizardClient: onReceive : android.intent.action.BOOT_COMPLETED
,03-17 13:26:14.392  1018  1483 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,03-17 13:26:14.392  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:14.392  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:14.392  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:14.392  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:14.402  3930  3965 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-17 13:26:14.412  3986  4230 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id),
,03-17 13:26:14.412  1018  1483 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4255 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
03-17 13:26:14.412  1018  1483 I ActivityManager: Killing 3528:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
03-17 13:26:14.422  4255  4255 E Zygote  : MountEmulatedStorage()
03-17 13:26:14.422  4255  4255 E Zygote  : v2,
03-17 13:26:14.422  4255  4255 I libpersona: KNOX_SDCARD checking this for 10107
03-17 13:26:14.422  4255  4255 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:14.422  4255  4255 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:14.432  4255  4255 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 13:26:14.432  4255  4255 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:14.452  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.452  3930  3965 I GFX raster: took 0.603073ms for 96*96 texture 0
03-17 13:26:14.452  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb81990b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8575568 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.462  4255  4255 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:14.462  4255  4255 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:14.482  3930  3965 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-17 13:26:14.482  4235  4252 W System.err: java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,03-17 13:26:14.482  4235  4252 W System.err: 	at android.os.Parcel.readException(Parcel.java:1544)
,03-17 13:26:14.482  4235  4252 W System.err: 	at android.os.Parcel.readException(Parcel.java:1493)
,03-17 13:26:14.482  4235  4252 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
03-17 13:26:14.482  4235  4252 W System.err: 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
03-17 13:26:14.482  4235  4252 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
,03-17 13:26:14.482  4235  4252 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,03-17 13:26:14.492  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.492  3930  3965 I GFX raster: took 0.605990ms for 96*96 texture 0
,03-17 13:26:14.492  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb855a990 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb853ce38 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.502  3930  3965 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-17 13:26:14.512  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.512  3930  3965 I GFX raster: took 0.836094ms for 96*96 texture 0
,03-17 13:26:14.512  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8575568 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb853ce38 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.522  3930  3965 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-17 13:26:14.532  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.542  3930  3965 I GFX raster: took 0.648125ms for 96*96 texture 0
,03-17 13:26:14.542  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb853d430 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb853ce38 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.542  3930  3965 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-17 13:26:14.552  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3517/cgroup.procs: No such file or directory
03-17 13:26:14.552  1018  1043 W libprocessgroup: failed to open /acct/uid_10003/pid_3528/cgroup.procs: No such file or directory
,03-17 13:26:14.552  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.572  3930  3965 I GFX raster: took 0.745209ms for 96*96 texture 0
03-17 13:26:14.572  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb857a2d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb853ce38 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.572  1018  1231 I art     : Explicit concurrent mark sweep GC freed 34104(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 30MB/45MB, paused 2.630ms total 154.382ms
,03-17 13:26:14.572  3930  3965 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-17 13:26:14.582  1018  1045 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
,03-17 13:26:14.582  1018  1045 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
,03-17 13:26:14.582  1018  3000 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 13:26:14.582  1018  3000 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,03-17 13:26:14.582  1018  3000 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:14.592  1018  3000 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:14.592  1018  3000 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:14.592  1018  1045 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
,03-17 13:26:14.602  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.602  3930  3965 I GFX raster: took 0.548749ms for 96*96 texture 0
,03-17 13:26:14.612  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8198588 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb853ce38 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.612  1018  1483 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 13:26:14.612  1018  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,03-17 13:26:14.612  1018  1483 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:14.612  1018  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:14.612  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:14.622  3986  4230 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-17 13:26:14.632  3986  4230 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-17 13:26:14.632  1018  1369 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 13:26:14.632  1018  1369 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,03-17 13:26:14.632  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:14.632  1018  1369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:14.632  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:14.642  3930  3965 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
03-17 13:26:14.662  3930  3965 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 13:26:14.662  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
03-17 13:26:14.,662  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Welcome
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
03-17 13:26:14.672  1018  1231 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
03-17 13:26:14.672  1018  1231 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.DataConnection
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Debug
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageListXL
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:14.672  3930  3965 I AMMetaDataParserService: Resource data:2131165203
03-17 13:26:14.672  1018  1231 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:14.672  1018  1231 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:14.672  1018  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 13:26:14.682  3930  3965 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-17 13:26:14.682  3930  3965 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:14.682  3930  3965 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 13:26:14.682  3930  3965 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:14.682  3930  3965 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 13:26:14.692  3930  3965 I AMMetaDataParserService: getResourceName:com.android.email:xml/email_assistant_menu
03-17 13:26:14.692  3930  3965 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:14.692  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 13:26:14.692  3986  4230 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
03-17 13:26:14.702  1018  1388 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 13:26:14.702  1018  1388 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
03-17 13:26:14.702  1018  1388 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:14.702  1018  1388 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:14.702  1018  1388 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 13:26:14.722  3930  3965 I GFX construct_block_size_descriptor_2d second part: took 3.406302ms for 0*0 texture 0
03-17 13:26:14.732  3930  3965 I GFX generate_partition_tables: took 10.181036ms for 0*0 texture 0
03-17 13:26:14.732  3930  3965 I GFX raster: took 14.441610ms for 96*96 texture 0
03-17 13:26:14.732  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8559a28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb87299b0 counterpartCT=4 counterpartW=96 counterparth=96
03-17 13:26:14.732  3986  4230 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-17 13:26:14.742  3930  3965 I AMMetaDataParserService: Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,03-17 13:26:14.742  3268  3373 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,03-17 13:26:14.752  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.752  3930  3965 I GFX raster: took 0.773229ms for 96*96 texture 0
03-17 13:26:14.752  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88d0a40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb88d0b60 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.762  1018  1231 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 13:26:14.762  1018  1231 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,03-17 13:26:14.762  1018  1231 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:14.762  1018  1231 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:14.762  1018  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:14.762  2079  4273 D GCM     : COMPAT: Multi user not supported
,03-17 13:26:14.772  1018  1505 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 13:26:14.772  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-17 13:26:14.772  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:14.772  1018  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:14.772  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:14.772  1018  1152 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 13:26:14.772  1018  1152 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,03-17 13:26:14.782  1018  1152 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:14.782  1018  1152 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:14.782  1018  1152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 13:26:14.782  3930  3965 I AMMetaDataParserService: Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,03-17 13:26:14.792  1018  3000 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 13:26:14.792  1018  3000 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
03-17 13:26:14.792  1018  3000 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:14.792  1018  3000 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:14.792  1018  3000 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:14.802  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.802  3930  3965 I GFX raster: took 0.778073ms for 96*96 texture 0
03-17 13:26:14.802  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88d0a40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb88d32f0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.802  4209  4231 I DBG_POLICYDM: [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
03-17 13:26:14.802  4209  4209 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,03-17 13:26:14.802  4209  4231 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,03-17 13:26:14.812  3930  3965 I AMMetaDataParserService: Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
03-17 13:26:14.812  4209  4209 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-17 13:26:14.812  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 13:26:14.812  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 13:26:14.812  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:14.812  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:14.812  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:14.822  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.822  3930  3965 I GFX raster: took 0.776927ms for 96*96 texture 0
03-17 13:26:14.822  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88d0a40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb88d46a0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.832  1018  3001 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 13:26:14.832  1018  3001 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,03-17 13:26:14.832  1018  3001 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:14.832  1018  3001 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:14.832  3930  3965 I AMMetaDataParserService: Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
03-17 13:26:14.832  1018  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:14.842  1018  3004 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 13:26:14.842  1018  3004 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-17 13:26:14.842  1018  3004 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:14.842  1018  3004 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:14.842  1018  3004 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:14.852  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.862  3930  3965 I GFX raster: took 0.689271ms for 96*96 texture 0
03-17 13:26:14.862  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88d5a08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88d5c78 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.862  2079  4273 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,03-17 13:26:14.862  1018  1485 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 13:26:14.862  1018  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,03-17 13:26:14.862  1018  1485 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:14.862  1018  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:14.862  1018  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:14.862  3930  3965 I AMMetaDataParserService: Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,03-17 13:26:14.872  2079  4278 I CheckinService: Disabling old GoogleServicesFramework version
,03-17 13:26:14.892  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.892  3930  3965 I GFX raster: took 0.610625ms for 96*96 texture 0
03-17 13:26:14.892  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88d5a08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88d6f10 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.902  3930  3965 I AMMetaDataParserService: Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,03-17 13:26:14.912  2079  2079 D ChimeraCfgMgr: Reading stored module config
,03-17 13:26:14.912  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
03-17 13:26:14.912  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
03-17 13:26:14.912  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
03-17 13:26:14.912  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
03-17 13:26:14.912  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
03-17 13:26:14.912  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageCompose
03-17 13:26:14.912  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:14.912  3930  3965 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-17 13:26:14.912  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
03-17 13:26:14.912  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
03-17 13:26:14.912  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
03-17 13:26:14.912  3930  3965 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 13:26:14.912  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
03-17 13:26:14.912  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
03-17 13:26:14.912  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.DebugActivity
03-17 13:26:14.912  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
03-17 13:26:14.912  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
03-17 13:26:14.912  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
03-17 13:26:14.912  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SearchActivity
03-17 13:26:14.912  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:14.912  3930  3965 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 13:26:14.912  3930  3965 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 13:26:14.912  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
03-17 13:26:14.912  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
03-17 13:26:14.912  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,03-17 13:26:14.952  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
03-17 13:26:14.952  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
03-17 13:26:14.952  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
03-17 13:26:14.952  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
03-17 13:26:14.952  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
03-17 13:26:14.952  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:14.952  3930  3965 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-17 13:26:14.952  3930  3965 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 13:26:14.952  3930  3965 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:14.952  3930  3965 I AMMetaDataParserService: Resource data:2131099648
,03-17 13:26:14.962  3930  3965 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
03-17 13:26:14.962  3930  3965 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:14.962  3930  3965 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 13:26:14.962  3930  3965 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:14.962  3930  3965 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 13:26:14.962  3930  3965 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 13:26:14.962  3930  3965 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 13:26:14.962  3930  3965 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:14.962  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:14.962  3930  3965 I GFX raster: took 0.724479ms for 96*96 texture 0
,03-17 13:26:14.962  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8a7fa58 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8a7fd30 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:14.972  2079  4279 I CheckinService: Checking schedule, now: 1458217574988 next: 1458246240395
,03-17 13:26:14.972  2079  4279 I CheckinService: active receiver: disabled
,03-17 13:26:14.972  3930  3965 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 13:26:14.982  2079  2079 D BootCompletedReceiver: Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,03-17 13:26:14.982  2079  2079 D BootCompletedReceiver: Got an BootCompleted event.
,03-17 13:26:14.992  4209  4209 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-17 13:26:15.002  2079  2079 D BootCompletedReceiver: Will NOT schedule AdAttestation signal task because it's disabled.
,03-17 13:26:15.002  2079  2079 D SystemUpdateService: onCreate
,03-17 13:26:15.002  4209  4209 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-17 13:26:15.012  4209  4231 I DBG_POLICYDM: [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,03-17 13:26:15.012  1018  1483 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-17 13:26:15.012  1018  1483 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
03-17 13:26:15.012  1018  1483 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,03-17 13:26:15.012  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-17 13:26:15.012   257   519 I SecDataIO: Write to block
,03-17 13:26:15.022  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.022  4209  4209 I DBG_POLICYDM: [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,03-17 13:26:15.022  4209  4209 I DBG_POLICYDM: [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,03-17 13:26:15.022  1018  1018 I MotionRecognitionService: Plugged
,03-17 13:26:15.022  3930  3965 I GFX construct_block_size_descriptor_2d second part: took 2.562397ms for 0*0 texture 0
,03-17 13:26:15.022  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-17 13:26:15.052  4209  4209 I DBG_POLICYDM: [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,03-17 13:26:15.052  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-17 13:26:15.052  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-17 13:26:15.062  1427  1427 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-17 13:26:15.062  1427  1427 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-17 13:26:15.072  3930  3965 I GFX generate_partition_tables: took 23.585213ms for 0*0 texture 0
,03-17 13:26:15.072  3930  3965 I GFX raster: took 27.327557ms for 96*96 texture 0
03-17 13:26:15.072  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8a80aa8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8a80ae0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.072  2627  3247 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,03-17 13:26:15.072  3930  3965 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 13:26:15.082  2661  2661 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-17 13:26:15.082  2661  2744 D HeadsetStateMachine: Disconnected process message: 10
,03-17 13:26:15.092  1018  3000 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,03-17 13:26:15.092  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:26:15.092  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-17 13:26:15.092  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-17 13:26:15.092  2627  3247 I art     : WaitForGcToComplete blocked for 20.247ms for cause DisableMovingGc
,03-17 13:26:15.102  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:15.102  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:15.102  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:15.102  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:15.102  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.102  3930  3965 I GFX raster: took 0.623489ms for 96*96 texture 0
03-17 13:26:15.102  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb857beb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8516460 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.112  3930  3965 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 13:26:15.122  4289  4289 E Zygote  : MountEmulatedStorage(),
03-17 13:26:15.122  4289  4289 I libpersona: KNOX_SDCARD checking this for 10035
03-17 13:26:15.122  4289  4289 E Zygote  : v2
03-17 13:26:15.122  4289  4289 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:15.122  4289  4289 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 13:26:15.122  4289  4289 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:15.122  4289  4289 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-17 13:26:15.132  3268  3268 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
03-17 13:26:15.132  1018  3000 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4289 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:15.132  3268  3268 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
03-17 13:26:15.132  1018  3000 I ActivityManager: Killing 3551:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
03-17 13:26:15.132  3268  3268 E DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,03-17 13:26:15.152  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,03-17 13:26:15.162  2627  2627 I Process : Sending signal. PID: 2627 SIG: 9
,03-17 13:26:15.162  2079  2079 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-17 13:26:15.182  4289  4289 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:15.182  4289  4289 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:15.192  1018  1369 I ActivityManager: Process com.sec.android.app.sysscope (pid 2627)(adj 0) has died(39,1155)
,03-17 13:26:15.212  2079  4305 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
,03-17 13:26:15.212  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.222  3930  3965 I GFX raster: took 0.783749ms for 96*96 texture 0
03-17 13:26:15.222  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb81990b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb82a7998 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.222  1018  1043 W libprocessgroup: failed to open /acct/uid_10060/pid_3551/cgroup.procs: No such file or directory
,03-17 13:26:15.252  3930  3965 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 13:26:15.252  1018  3004 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 13:26:15.252  1018  3004 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 13:26:15.252  1018  3004 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:15.252  1018  3004 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:15.252  1018  3004 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:15.272  2079  4305 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED
,03-17 13:26:15.272  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.272  3930  3965 I GFX raster: took 0.855209ms for 96*96 texture 0
03-17 13:26:15.272  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb856d628 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8516460 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.292  3930  3965 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 13:26:15.302  4209  4231 I DBG_POLICYDM: [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-17 13:26:15.322  2079  4303 I SystemUpdateService: cancelUpdate (empty URL)
03-17 13:26:15.322  2079  4303 I SystemUpdateService: active receiver: disabled
,03-17 13:26:15.322  4209  4231 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 13:26:15.322  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.322  1018  1483 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 13:26:15.322  1018  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,03-17 13:26:15.322  4209  4231 I DBG_POLICYDM: [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,03-17 13:26:15.322  4209  4231 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,03-17 13:26:15.322  3930  3965 I GFX raster: took 1.064688ms for 96*96 texture 0
03-17 13:26:15.322  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8191d38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88d5a08 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.332  1018  1483 W ActivityManager: userId = 0, bbcId = -10000,
03-17 13:26:15.332  1018  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:15.332  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:15.332  4209  4231 I DBG_POLICYDM: [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,03-17 13:26:15.332  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 13:26:15.332  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:15.332  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:15.332  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:15.332  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:15.332  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:15.352  1018  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
03-17 13:26:15.352  1018  1043 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,03-17 13:26:15.362  4209  4231 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,03-17 13:26:15.372  3930  3965 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 13:26:15.382  4209  4231 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-17 13:26:15.392  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
03-17 13:26:15.392  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
03-17 13:26:15.392  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.392  3930  3965 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:15.392  3930  3965 I AMMetaDataParserService: Resource data:2131099648
,03-17 13:26:15.392  3930  3965 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 13:26:15.392  3930  3965 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:15.392  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.392  3930  3965 I GFX raster: took 0.892552ms for 96*96 texture 0
03-17 13:26:15.392  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88d0a40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb855b050 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.402  4289  4311 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,03-17 13:26:15.402  4289  4311 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,03-17 13:26:15.402  3930  3965 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 13:26:15.412  4289  4289 E SPPClientService: [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,03-17 13:26:15.422  4209  4231 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-17 13:26:15.432  2079  4305 W BaseAppContext: Using Auth Proxy for data requests.
03-17 13:26:15.432  4209  4232 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-17 13:26:15.432  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.432  4209  4231 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,03-17 13:26:15.432  3930  3965 I GFX raster: took 0.858541ms for 96*96 texture 0
03-17 13:26:15.432  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8a80aa8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb857a010 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.432  4209  4231 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,03-17 13:26:15.442  4209  4232 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 13:26:15.452  4289  4311 D SPPClientService: PushLog.txt file is not deleted.
,03-17 13:26:15.452  4289  4311 D SPPClientService: PushLog.txt file is not deleted.
03-17 13:26:15.452  4289  4311 D SPPClientService: ============PushLog. stop!
,03-17 13:26:15.472  4209  4231 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/03/18/16:12:11
,03-17 13:26:15.472  4209  4231 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/03/17/13:26:15
,03-17 13:26:15.472  3930  3965 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 13:26:15.472  4209  4231 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,03-17 13:26:15.472  1018  2999 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-17 13:26:15.472  4209  4231 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,03-17 13:26:15.482  1018  2999 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:15.482  1018  2999 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:15.482  1018  2999 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:15.482  4209  4232 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 13:26:15.482  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-17 13:26:15.492  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:15.492  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:15.492  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 13:26:15.492  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.492  3930  3965 I GFX raster: took 1.010156ms for 96*96 texture 0
03-17 13:26:15.492  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb857beb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8575740 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.492  1018  1483 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:15.502  1018  1483 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:15.502  1018  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:15.502  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:15.502  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,03-17 13:26:15.502  4209  4232 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-17 13:26:15.502  4209  4232 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-17 13:26:15.512  4209  4232 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-17 13:26:15.512  4209  4232 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-17 13:26:15.512  4209  4232 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,03-17 13:26:15.512  3930  3965 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 13:26:15.512  4209  4232 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,03-17 13:26:15.522  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:15.522  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:15.522  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:15.522  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:15.532  4209  4232 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0,
,03-17 13:26:15.532  4317  4317 E Zygote  : MountEmulatedStorage()
03-17 13:26:15.532  4317  4317 E Zygote  : v2
03-17 13:26:15.532  4317  4317 I libpersona: KNOX_SDCARD checking this for 10041
03-17 13:26:15.532  4317  4317 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:15.532  4317  4317 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:15.542  1018  1030 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4317 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:15.542  4317  4317 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:15.542  1018  1030 I ActivityManager: Killing 3568:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,03-17 13:26:15.542  4317  4317 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 13:26:15.542  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.552  3930  3965 I GFX raster: took 0.662864ms for 96*96 texture 0
03-17 13:26:15.552  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb81990b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb853d430 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.572  2079  4305 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,03-17 13:26:15.572  4209  4231 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,03-17 13:26:15.582  4317  4317 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:15.592  4317  4317 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:15.592  3930  3965 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 13:26:15.602  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.602  4209  4232 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
03-17 13:26:15.602  3930  3965 I GFX raster: took 0.645417ms for 96*96 texture 0
03-17 13:26:15.602  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb856d628 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8575980 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.602  3930  3965 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 13:26:15.612  1018  1043 W libprocessgroup: failed to open /acct/uid_10092/pid_3568/cgroup.procs: No such file or directory
,03-17 13:26:15.632  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.632  3930  3965 I GFX raster: took 0.781562ms for 96*96 texture 0
03-17 13:26:15.632  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8191d38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb855a948 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.652  3930  3965 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 13:26:15.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
03-17 13:26:15.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
03-17 13:26:15.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
03-17 13:26:15.672  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
03-17 13:26:15.672  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:15.672  3930  3965 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:15.672  3930  3965 I AMMetaDataParserService: Resource data:2131099648
,03-17 13:26:15.672   278   875 D EnterpriseController: uids 10012,
03-17 13:26:15.672   278   875 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 13:26:15.672   278   875 D Netd    : getNetworkForDns: using netid 502 for uid 10012,
,03-17 13:26:15.682  2079  4305 I AuthZen : Fetching signing key...
,03-17 13:26:15.682  4209  4232 I DBG_POLICYDM: [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,03-17 13:26:15.682  3930  3965 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 13:26:15.682  3930  3965 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:15.692  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.692  3930  3965 I GFX raster: took 0.710886ms for 96*96 texture 0
03-17 13:26:15.692  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88d0a40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8575740 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.702  3930  3965 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 13:26:15.712  1843  4339 D GCM     : GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,03-17 13:26:15.722  2079  2079 D SystemUpdateService: onDestroy
,03-17 13:26:15.752  3268  3373 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,03-17 13:26:15.752  3268  3373 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-17 13:26:15.752  3268  3373 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,03-17 13:26:15.762  4255  4255 D StrictMode: StrictMode policy violation; ~duration=1008 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 13:26:15.762  4255  4255 D StrictMode: StrictMode policy violation; ~duration=998 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.,gmm.base.app.a.a(PG:1211)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 13:26:15.762  4255  4255 D StrictMode: StrictMode policy violation; ~duration=860 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.io.File.doAccess(File.java:283)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.io.File.exists(File.java:363)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityT,hread.main(ActivityThread.java:6145)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 13:26:15.762  4255  4255 D StrictMode: StrictMode policy violation; ~duration=859 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 13:26:15.762  4255  4255 D StrictMode: StrictMode policy violation; ~duration=858 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 13:26:15.762  1018  3002 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
03-17 13:26:15.762  4255  4255 D StrictMode: StrictMode policy violation; ~duration=856 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.r.k.c(PG:1187)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.r.k.a(PG:2107)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.r.v.a(PG:1206)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.r.y.a(PG:2233)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.r.e.b(PG:170)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.r.e.b(PG:13188)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 13:26:15.762  1018  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:15.762  4255  4255 D StrictMode: StrictMode policy violation; ~duration=854 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.r.k.c(PG:1187)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.r.k.b(PG:14147)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.r.k.c(PG:583)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.r.v.a(PG:1206)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.r.y.a(PG:2233)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.r.e.b(PG:170)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.r.e.b(PG:13188)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 13:26:15.762  1018  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:15.762  4255  4255 D StrictMode: StrictMode policy violation; ~duration=824 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.io.File.doAccess(File.java:283)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.io.File.exists(File.java:363)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 13:26:15.762  1018  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:15.762  4255  4255 D StrictMode: StrictMode policy violation; ~duration=824 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.io.File.doAccess(File.java:283)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.io.File.exists(File.java:363)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 13:26:15.762  4255  4255 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 13:26:15.762  1018  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:15.782  2079  4305 I AuthZen : Signing key fetched successfully!
03-17 13:26:15.782  1018  3002 I ActivityManager: Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4345 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 13:26:15.782  1018  3002 I ActivityManager: Killing 3602:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
03-17 13:26:15.792  3268  3373 I DBG_DM  : [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
03-17 13:26:15.792  4345  4345 E Zygote  : MountEmulatedStorage()
03-17 13:26:15.792  4345  4345 E Zygote  : v2
03-17 13:26:15.792  1843  1843 I GCoreUlr: DispatchingService.onCreate()
03-17 13:26:15.792  4345  4345 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:15.792  4345  4345 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:15.802  4345  4345 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:15.812  1647  2755 I art     : Explicit concurrent mark sweep GC freed 4212(159KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 832us total 38.686ms
03-17 13:26:15.812  4345  4345 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:15.812  4345  4345 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:15.832  3268  3373 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-17 13:26:15.852  1018  3001 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null,
,03-17 13:26:15.852  1018  3001 W ActivityManager: userId = 0, bbcId = -10000,
03-17 13:26:15.852  1018  3001 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
03-17 13:26:15.852  1018  3001 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:15.852  1018  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:15.862  4345  4345 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:15.862  4345  4345 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:15.862  4209  4231 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,03-17 13:26:15.882  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.882  3930  3965 I GFX raster: took 0.767916ms for 96*96 texture 0
,03-17 13:26:15.882  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8a80aa8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb855b050 counterpartCT=4 counterpartW=96 counterparth=96
03-17 13:26:15.882  3930  3965 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 13:26:15.892  1018  1044 I ActivityManager: Waited long enough for: ServiceRecord{a18f152 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,03-17 13:26:15.892  4209  4231 I DBG_POLICYDM: [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-17 13:26:15.902  3268  3373 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
03-17 13:26:15.912  1018  1043 W libprocessgroup: failed to open /acct/uid_10062/pid_3602/cgroup.procs: No such file or directory
,03-17 13:26:15.912  2079  4305 W BaseAppContext: Using Auth Proxy for data requests.
03-17 13:26:15.912  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.912  3930  3965 I GFX raster: took 0.642552ms for 96*96 texture 0
03-17 13:26:15.912  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb857beb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8576bb8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.922  3930  3965 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 13:26:15.932  3268  3373 I DBG_DM  : [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,03-17 13:26:15.942  3268  3373 I DBG_DM  : [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,03-17 13:26:15.952  4317  4317 I SA      : [SSP] onCreated
,03-17 13:26:15.952  4345  4345 D StatusChecker: onReceive : android.intent.action.BOOT_COMPLETED
,03-17 13:26:15.962  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.962  3930  3965 I GFX raster: took 0.661249ms for 96*96 texture 0
03-17 13:26:15.962  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb81990b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb857a010 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.962   291   291 E SMD     : DCD OFF
,03-17 13:26:15.962  3268  3373 I DBG_DM  : [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,03-17 13:26:15.962  3268  3373 I DBG_DM  : [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,03-17 13:26:15.972  3268  3374 I DBG_DM  : [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,03-17 13:26:15.972  3930  3965 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 13:26:15.972  4345  4345 I StatusChecker: onReceive : net.mt.init : DONE
,03-17 13:26:15.982  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:15.982  3930  3965 I GFX raster: took 0.632031ms for 96*96 texture 0
03-17 13:26:15.982  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb856d628 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88d5a08 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:15.982  3268  3373 I DBG_DM  : [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,03-17 13:26:15.982  2079  4305 D a       : Opening database auth.proximity.permit_store...
,03-17 13:26:15.982  3930  3965 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 13:26:15.992  3268  3374 I DBG_DM  : [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,03-17 13:26:15.992  2079  4305 D AuthZenTransactionCache: Initialized cache in: /data/data/com.google.android.gms/files
,03-17 13:26:15.992  2079  4305 D AuthZenTransactionCache: Clearing transaction cache
,03-17 13:26:16.002  3268  3373 I DBG_DM  : [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,03-17 13:26:16.002  1843  4338 I GCM     : GCM config loaded
,03-17 13:26:16.002  3268  3373 I DBG_DM  : [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,03-17 13:26:16.002  1018  3001 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,03-17 13:26:16.002  1018  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.002  1018  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.012  1018  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:16.012  1018  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.022  4369  4369 E Zygote  : MountEmulatedStorage(),
03-17 13:26:16.022  4369  4369 E Zygote  : v2
03-17 13:26:16.022  4369  4369 I libpersona: KNOX_SDCARD checking this for 10116
03-17 13:26:16.022  4369  4369 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:16.022  4369  4369 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 13:26:16.022  4369  4369 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:16.022  4369  4369 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:16.032  1018  3001 I ActivityManager: Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4369 uid=10116 gids={50116, 9997} abi=armeabi-v7a
,03-17 13:26:16.032  1018  3001 I ActivityManager: Killing 3358:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,03-17 13:26:16.072  4369  4369 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:16.072  4369  4369 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:16.072  4317  4317 I SA      : [TPM] There is no property file
,03-17 13:26:16.082  4317  4317 I SA      : [SCU] isHaveSA() - false
,03-17 13:26:16.092  4317  4317 I SA      : [TPM] getModelProperty : null
03-17 13:26:16.092  4317  4317 I SA      : [TPM] getCSCProperty : null
03-17 13:26:16.092  3268  3374 I DBG_DM  : [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:308289685
03-17 13:26:16.092  3268  3374 I DBG_DM  : [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,03-17 13:26:16.102  4317  4317 I SA      : [DM] FLOATING AMOLED FEATURE: true
03-17 13:26:16.112  4317  4317 I SA      : [DM] PRODUCT AMOLED FEATURE: false
03-17 13:26:16.112  4317  4317 I SA      : [DM] TFT FEATURE: false
,03-17 13:26:16.112  3268  3374 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,03-17 13:26:16.122  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:16.122  3930  3965 I GFX raster: took 0.735313ms for 96*96 texture 0
03-17 13:26:16.122  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8191d38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8576bb8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:16.132  1018  1231 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 13:26:16.132  1843  4338 I art     : Explicit concurrent mark sweep GC freed 41370(2MB) AllocSpace objects, 42(864KB) LOS objects, 39% free, 12MB/20MB, paused 1.329ms total 79.436ms
,03-17 13:26:16.132  1018  1231 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,03-17 13:26:16.132  4317  4317 I SA      : [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0,
03-17 13:26:16.132  4317  4317 I SA      : [DM] init START
,03-17 13:26:16.142  4188  4188 W dex2oat : Verification of void com.google.android.gms.ads.internal.purchase.e.b() took 100.465ms,
,03-17 13:26:16.142  1018  1043 W libprocessgroup: failed to open /acct/uid_10009/pid_3358/cgroup.procs: No such file or directory,
,03-17 13:26:16.162  3930  3965 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 13:26:16.162  1018  1231 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:16.162  1018  1231 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:16.162  1018  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:16.172  1018  3004 I ActivityManager: Killing 3629:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,03-17 13:26:16.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
,03-17 13:26:16.182  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:16.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:16.182  3930  3965 I AMMetaDataParserService: Resource data:2131099648
,03-17 13:26:16.182  3930  3965 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 13:26:16.182  3930  3965 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:16.182  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:16.182  3930  3965 I GFX raster: took 0.694167ms for 96*96 texture 0
03-17 13:26:16.182  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88d0a40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8575740 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:16.182  3268  3374 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,03-17 13:26:16.192  4317  4317 I SA      : [DM] This device is not a Vodafone
,03-17 13:26:16.202  3930  3965 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 13:26:16.212  4317  4317 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,03-17 13:26:16.212  4317  4317 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,03-17 13:26:16.212  4317  4317 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
03-17 13:26:16.212  4317  4317 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,03-17 13:26:16.212  4317  4317 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,03-17 13:26:16.212  4317  4317 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
03-17 13:26:16.212  4317  4317 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,03-17 13:26:16.212  4369  4369 I PageBuddyNotiSvc: Intent received : action=android.intent.action.BOOT_COMPLETED
,03-17 13:26:16.222  4317  4317 W ResourceType: No package identifier when getting value for resource number 0x00000000
,03-17 13:26:16.222  4317  4317 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,03-17 13:26:16.222  4317  4317 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,03-17 13:26:16.222  4317  4317 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,03-17 13:26:16.222  4317  4317 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
03-17 13:26:16.222  4317  4317 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,03-17 13:26:16.222  4317  4317 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,03-17 13:26:16.222  4317  4317 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
03-17 13:26:16.222  4317  4317 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
03-17 13:26:16.222  4317  4317 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,03-17 13:26:16.232  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:16.232  3930  3965 I GFX raster: took 0.674843ms for 96*96 texture 0
,03-17 13:26:16.232  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8a80aa8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8576bb8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:16.242  1843  1843 W Auth    : [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,03-17 13:26:16.242  4317  4317 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,03-17 13:26:16.242  4317  4317 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,03-17 13:26:16.242  1843  4361 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,03-17 13:26:16.242  3930  3965 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 13:26:16.252  4317  4317 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,03-17 13:26:16.252  4317  4317 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,03-17 13:26:16.252  4317  4317 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
03-17 13:26:16.252  4317  4317 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
03-17 13:26:16.252  4317  4317 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
03-17 13:26:16.252  4317  4317 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
03-17 13:26:16.252  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3629/cgroup.procs: No such file or directory
03-17 13:26:16.252  4317  4317 I SA      : [SCU] isHaveSA() - false
03-17 13:26:16.252  4317  4317 I SA      : support phone number id : false
03-17 13:26:16.252  1018  1505 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 13:26:16.252  4317  4317 I SA      : [DM] Supports Ref Jpn : true
03-17 13:26:16.252  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
03-17 13:26:16.252  4317  4317 I SA      : [DM] init END
,03-17 13:26:16.262  4369  4369 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,03-17 13:26:16.262  4209  4232 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-17 13:26:16.262  3268  3374 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,03-17 13:26:16.262  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:16.262  1018  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:16.262  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:16.272  3268  3374 I DBG_DM  : [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 678432842
,03-17 13:26:16.272  1018  2734 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:16.272  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:16.272  3930  3965 I GFX raster: took 0.620364ms for 96*96 texture 0
03-17 13:26:16.272  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb857beb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb853d430 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:16.272  1018  2734 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:16.272  1843  2096 W GCoreFlp: No location to return for getLastLocation()
,03-17 13:26:16.272  1843  1868 W FusedLocationProvider: location=null
,03-17 13:26:16.272  1018  2734 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:16.272  1018  2734 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,03-17 13:26:16.282  3268  3268 I DBG_DM  : [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,03-17 13:26:16.282  4317  4317 I SA      : [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
03-17 13:26:16.282  4317  4317 I SA      : [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,03-17 13:26:16.282  1018  3001 D ActivityManager: startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
03-17 13:26:16.282  1018  3001 D ActivityManager: retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,03-17 13:26:16.282  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
03-17 13:26:16.282  1018  3001 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:16.282  1018  3001 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-17 13:26:16.282  1018  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,03-17 13:26:16.292  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,03-17 13:26:16.292  4317  4317 I SA      : [OR] onReceive END
,03-17 13:26:16.292  1018  1485 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,03-17 13:26:16.292  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,03-17 13:26:16.302  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.302  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:16.302  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:16.302  4369  4369 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,03-17 13:26:16.302  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.312  1843  1843 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
03-17 13:26:16.312  4397  4397 I libpersona: KNOX_SDCARD checking this for 10125
03-17 13:26:16.312  3930  3965 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
03-17 13:26:16.312  4397  4397 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:16.312  4397  4397 E Zygote  : MountEmulatedStorage(),
03-17 13:26:16.312  4397  4397 E Zygote  : v2
,03-17 13:26:16.312  4397  4397 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:16.312  3268  3374 I DBG_DM  : [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
03-17 13:26:16.312  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,03-17 13:26:16.322  4397  4397 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 13:26:16.322  1018  1485 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4397 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 13:26:16.322  4209  4232 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,03-17 13:26:16.332  4397  4397 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:16.332  1018  1485 D ActivityManager: startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,03-17 13:26:16.332  3268  3374 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
03-17 13:26:16.332  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:16.332  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:16.332  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:16.332  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.332  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-17 13:26:16.332  3930  3965 I GFX raster: took 0.655416ms for 96*96 texture 0
03-17 13:26:16.332  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb81990b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8575740 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:16.342  4317  4317 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-17 13:26:16.342  4317  4317 I SA      : [ODM] queryOpenData(key= GEO_IP )
,03-17 13:26:16.352  3930  3965 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 13:26:16.352  1018  1485 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4408 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:16.352  4408  4408 E Zygote  : MountEmulatedStorage()
03-17 13:26:16.352  4408  4408 E Zygote  : v2
03-17 13:26:16.352  4408  4408 I libpersona: KNOX_SDCARD checking this for 10042
03-17 13:26:16.352  4408  4408 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:16.352  4408  4408 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:16.362  4408  4408 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:16.362  4408  4408 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 13:26:16.362  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 13:26:16.362  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:16.362  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:16.362  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:16.362  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:16.362  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:16.362  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:16.362  4397  4397 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:16.372  3930  3965 I GFX raster: took 0.682761ms for 96*96 texture 0
03-17 13:26:16.372  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb856d628 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8576bb8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:16.372  1843  2096 W GCoreFlp: No location to return for getLastLocation()
,03-17 13:26:16.372  4397  4397 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:16.372  1843  2105 W FusedLocationProvider: location=null
,03-17 13:26:16.372  3930  3965 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 13:26:16.372  4317  4317 I SA      : getMccForGalaxyJpn step2 GEO_IP MCC : 260
03-17 13:26:16.372  4317  4317 I SA      : [LBE] REF_JPN : true
03-17 13:26:16.372  4317  4317 I SA      : [BDC] create
,03-17 13:26:16.372  3268  3268 E DBG_DM  : [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,03-17 13:26:16.382  3268  3268 E DBG_DM  : [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@287dd929
,03-17 13:26:16.392  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMService(755/lllllIIlIIIlIlIIIllI)] UI_id:223
,03-17 13:26:16.402  3268  3268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.lllllIIlIIIlIlIIIllI:761 com.wssyncmldm.XDMService.llIIllllIIlllIIIIlll:82 com.wssyncmldm.llIIllllIIlllIIIIlll.handleMessage:1090 
,03-17 13:26:16.402  3268  3268 I Timeline: Timeline: Activity_launch_request id:com.wssyncmldm time:47164
03-17 13:26:16.402  3268  3268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.lllllIIlIIIlIlIIIllI:761 com.wssyncmldm.XDMService.llIIllllIIlllIIIIlll:82 
03-17 13:26:16.402  1018  2734 E PersonaManagerService: inState():  stateMachine is null !!
03-17 13:26:16.402  1018  2734 I PersonaManagerService: PersonaId don't exist
03-17 13:26:16.402  1018  2734 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,03-17 13:26:16.412  1018  2734 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-17 13:26:16.412  4397  4397 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 13:26:16.412  4397  4397 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 13:26:16.412  4397  4397 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-17 13:26:16.412  1018  2734 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:16.412  1018  2734 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:16.412  1018  2734 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 13:26:16.412  4408  4408 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:16.412  1018  2734 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:16.422  4408  4408 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:16.422  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:16.422  3930  3965 I GFX raster: took 0.724532ms for 96*96 texture 0
03-17 13:26:16.422  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8191d38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb857a010 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:16.422  1018  2734 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-17 13:26:16.422  1018  2734 W ActivityManager: mDVFSHelper.acquire()
,03-17 13:26:16.422  1018  2734 D FocusedStackFrame: Set to : 0
,03-17 13:26:16.422  1490  1490 D Launcher.HomeView: onPause
03-17 13:26:16.422  1018  2734 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 13:26:16.422  1018  2734 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-17 13:26:16.422  1018  2734 D InputDispatcher: Focused application set to: xxxx
,03-17 13:26:16.422  3930  3965 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
03-17 13:26:16.422  1018  2734 D InputDispatcher: Focus left window: 1490
,03-17 13:26:16.432  1490  1490 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 13:26:16.432  1018  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-17 13:26:16.442  1018  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 13:26:16.452  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
03-17 13:26:16.452  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:16.452  3930  3965 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:16.452  3930  3965 I AMMetaDataParserService: Resource data:2131099648
,03-17 13:26:16.452  3930  3965 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-17 13:26:16.452  3930  3965 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:16.452  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:16.462  3930  3965 I GFX raster: took 0.786926ms for 96*96 texture 0
03-17 13:26:16.462  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88d0a40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb88d5a08 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:16.462  1018  1485 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:16.462  4317  4317 I SA      : [DBMV2] getEmailID
,03-17 13:26:16.462  1018  1485 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:16.462  1018  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:16.462  1018  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 13:26:16.462  4317  4317 I SA      : [DBMV2] getDataV02ForItems
,03-17 13:26:16.462  4317  4317 I SA      : [SSP] query invoked
03-17 13:26:16.462  3930  3965 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 13:26:16.472  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,03-17 13:26:16.482  1018  1018 D SensorService: [SO] activate (ident=0xb8a050e8, enabled=0)
,03-17 13:26:16.482  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-17 13:26:16.492  1018  1060 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-17 13:26:16.502  1018  1018 D SensorManager: unregisterListener ::   
,03-17 13:26:16.502  1018  1018 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-17 13:26:16.502  4317  4317 I SA      : [SCU] get signed id from samsung account2.0 DB.
03-17 13:26:16.502  1018  1018 D SensorService: [SO] changed settle time [1]
03-17 13:26:16.502  1018  1018 D SensorService: [SO] setDelay [66000000]
03-17 13:26:16.502  1018  1018 D SensorService: [SO] activate (ident=0xb8a050e8, enabled=1)
03-17 13:26:16.502  1018  1018 D SensorService: [SO] AR_init
03-17 13:26:16.502  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-17 13:26:16.502  1018  1018 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-17 13:26:16.512  4408  4408 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-17 13:26:16.522  4397  4397 D QuickConnect: PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,03-17 13:26:16.522  4397  4397 D QuickConnect: Util.setSCRunningSetting - [value]0
,03-17 13:26:16.532  4317  4317 I SA      : [SCU] get signed id from samsung account1.0 DB.
,03-17 13:26:16.542  4317  4317 I SA      : [BDC] destroy
,03-17 13:26:16.542  1018  2999 D SettingsProvider: name = scon_is_running
03-17 13:26:16.542  1018  2999 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 13:26:16.542  1018  2999 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 13:26:16.542  1018  2999 D SettingsProvider: selectionArgs: false
03-17 13:26:16.542  1018  2999 D SettingsProvider: selectionArgs: 10125
03-17 13:26:16.542  1018  2999 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 13:26:16.542  1018  2999 D SettingsProvider: ret = -1
,03-17 13:26:16.552  1843  1843 D PersistentNotificationBroadcastReceiver: Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,03-17 13:26:16.552  3268  3268 I DBG_DM  : [com.wssyncmldm.ui.XUIDialogActivity(2153/onResume)] 
,03-17 13:26:16.552  3268  3268 I DBG_DM  : [com.wssyncmldm.ui.XUIDialogActivity(2195/lllIlIlIIIllIIlIllIl)] id 223
,03-17 13:26:16.552  1018  2734 I ActivityManager: Killing 3645:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,03-17 13:26:16.562  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:16.562  3930  3965 I GFX raster: took 0.632604ms for 96*96 texture 0
03-17 13:26:16.562  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8a80aa8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8575740 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:16.562  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-17 13:26:16.562  3930  3965 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 13:26:16.572  1018  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1],
03-17 13:26:16.572  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 39
,03-17 13:26:16.582  1018  2999 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,03-17 13:26:16.582  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-17 13:26:16.582  1018  1152 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 13:26:16.582  1018  1152 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.focus.ContactsSyncIntentService; callingUser = 0; userId(target) = 0
,03-17 13:26:16.582  1018  1152 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:16.582  1018  1152 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:16.582  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:16.582  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-17 13:26:16.582  3930  3965 I GFX raster: took 0.627708ms for 96*96 texture 0
03-17 13:26:16.582  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb857beb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb857bd18 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:16.582  1018  1152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:16.592  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-17 13:26:16.592  3268  3268 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-17 13:26:16.592  3268  3268 I Timeline: Timeline: Activity_launch_request id:com.wssyncmldm time:47353
,03-17 13:26:16.592  1018  1030 E PersonaManagerService: inState():  stateMachine is null !!
03-17 13:26:16.592  1018  1030 I PersonaManagerService: PersonaId don't exist
03-17 13:26:16.592  1018  1030 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,03-17 13:26:16.592  4397  4397 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,03-17 13:26:16.602  4397  4397 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-17 13:26:16.602  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:16.602  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:16.602  3930  3965 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 13:26:16.602  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-17 13:26:16.612  1018  1030 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 13:26:16.612  1018  1030 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-17 13:26:16.612  1018  1030 W ActivityManager: mDVFSHelper.acquire()
,03-17 13:26:16.612  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
03-17 13:26:16.612  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-17 13:26:16.612  1018  1030 D InputDispatcher: Focused application set to: xxxx
,03-17 13:26:16.632  1018  1369 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,03-17 13:26:16.642  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.642  1018  1041 D SensorService: [SO] currT = 47400065136, prevT = 47080133782, diff = 319931354, [0.134 0.421 10.151]
,03-17 13:26:16.642  1018  1041 D SensorService: [SO] 0.134 0.421 10.151
03-17 13:26:16.642  1018  1041 D SensorService: [SO] [100 -> 255]
03-17 13:26:16.642  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.642  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:16.642  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:16.652  4255  4285 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.,
03-17 13:26:16.652  4408  4408 I CalendarProvider2: CalendarProvider2.onCreate() called
,03-17 13:26:16.662  4433  4433 E Zygote  : MountEmulatedStorage(),
03-17 13:26:16.662  4433  4433 E Zygote  : v2
03-17 13:26:16.662  4433  4433 I libpersona: KNOX_SDCARD checking this for 10131
03-17 13:26:16.662  4433  4433 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:16.662  4433  4433 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:16.662  4433  4433 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 13:26:16.662  4433  4433 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:16.672  1018  1369 I ActivityManager: Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4433 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,03-17 13:26:16.672  1018  1369 I ActivityManager: Killing 2796:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,03-17 13:26:16.682  3268  3268 I DBG_DM  : [com.wssyncmldm.ui.IIllIIIlIllIIIllIIlI(252/llllIIIllIlIIIIllllI)] 
,03-17 13:26:16.682  4433  4433 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:16.682  4433  4433 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:16.692  1018  1152 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 13:26:16.692  1018  1152 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncReceiverService; callingUser = 0; userId(target) = 0
,03-17 13:26:16.692  1018  1152 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:16.692  1018  1152 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:16.692  1018  1152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:16.702  1018  2734 D ActivityManager: post active user change for 0 fullscreen false record.isFloatingActivity() false
,03-17 13:26:16.702  1018  2734 D KnoxTimeoutHandler: postActiveUserChange for user 0
,03-17 13:26:16.702   315   315 I art     : Explicit concurrent mark sweep GC freed 8776(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 853us total 35.878ms
,03-17 13:26:16.702  1018  2734 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 13:26:16.702  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 13:26:16.702  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 13:26:16.702  1018  1018 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
03-17 13:26:16.702  3268  3268 I DBG_DM  : [com.wssyncmldm.ui.XUIDialogActivity(2145/onPause)] 
,03-17 13:26:16.702  1843  4361 I GCoreUlr: WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,03-17 13:26:16.712  1018  3004 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 13:26:16.712  1018  3004 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-17 13:26:16.712  1018  3004 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-17 13:26:16.722  4433  4433 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 13:26:16.722   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 22.205ms
,03-17 13:26:16.732  4433  4433 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:16.732  4433  4433 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 13:26:16.732  4433  4433 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 13:26:16.742   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 19.637ms
,03-17 13:26:16.752  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 39
,03-17 13:26:16.762  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-17 13:26:16.782  1843  4361 I GCoreUlr: Unbound from all location providers
03-17 13:26:16.782  1843  4361 I GCoreUlr: Place inference reporting - stopped
,03-17 13:26:16.812  1018  3001 D ActivityManager: bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,03-17 13:26:16.812  1018  3001 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,03-17 13:26:16.822  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-17 13:26:16.822  3268  3268 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(75/onCreate)] Postpone Count : 39
,03-17 13:26:16.842  1018  3001 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:16.842  1018  3001 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:16.842  1018  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-17 13:26:16.852  3826  3949 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-17 13:26:16.882  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:16.892  3930  3965 I GFX raster: took 1.895051ms for 96*96 texture 0
03-17 13:26:16.892  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb857a010 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb82a7998 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:16.892  1018  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
03-17 13:26:16.892  1018  1043 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncService; callingUser = 0; userId(target) = 0
,03-17 13:26:16.892  3268  3268 D PhoneWindow: *FMB* installDecor mIsFloating : false
,03-17 13:26:16.892  3268  3268 D PhoneWindow: *FMB* installDecor flags : -2139029248
,03-17 13:26:16.892  3930  3965 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 13:26:16.902  4433  4433 D SBrowserFeatureFlag: initialized in static block : loadCscFeatureValue() succeed! 
,03-17 13:26:16.902  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:16.902  3930  3965 I GFX raster: took 0.648750ms for 96*96 texture 0
03-17 13:26:16.902  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88d0a40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8516460 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:16.912  3930  3965 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 13:26:16.922  1018  1043 W libprocessgroup: failed to open /acct/uid_10014/pid_3645/cgroup.procs: No such file or directory
,03-17 13:26:16.922  1018  1043 W libprocessgroup: failed to open /acct/uid_10120/pid_2796/cgroup.procs: No such file or directory
,03-17 13:26:16.942  1843  1843 I GCoreUlr: DispatchingService.onDestroy()
,03-17 13:26:16.942  4433  4433 D ManifestProvider: onCreate()
03-17 13:26:16.942  1843  1843 I GCoreUlr: Stopping handler for UlrDispSvcFast
,03-17 13:26:16.952  1843  1843 I GCoreUlr: Unbound from all location providers
,03-17 13:26:16.952  1843  1843 I GCoreUlr: Place inference reporting - stopped
,03-17 13:26:16.952  4433  4433 E NetworkSettingsReceiver: onReceive: android.intent.action.BOOT_COMPLETED
,03-17 13:26:16.972  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-17 13:26:16.972  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,03-17 13:26:16.982  1018  1054 D PowerManagerService: [s] UserActivityState : 1 -> 2
,03-17 13:26:16.982  1018  1054 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
,03-17 13:26:16.982  1018  1054 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 13:26:16.992  1018  1054 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-17 13:26:16.992  1018  1388 I ActivityManager: Killing 3670:com.wssnps/1000 (adj 15): empty #31
,03-17 13:26:16.992  1018  1172 D lights  : lcd : 46 +
,03-17 13:26:17.012  1018  1054 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
03-17 13:26:17.012  1018  1054 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 13:26:17.012  1018  1172 D lights  : lcd : 46 -
,03-17 13:26:17.012  1018  1172 D lights  : lcd : 19 +
,03-17 13:26:17.012  1018  3004 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:17.012  1018  3004 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.012  1018  3004 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.022  1018  3004 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
03-17 13:26:17.022  4433  4433 E SBrowserFeatureFlag: initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@3bd1a6fa
,03-17 13:26:17.022  4433  4433 D SBrowserFeatureFlag: initialize : initSupportedPkg() succeed! 
03-17 13:26:17.022  4433  4433 I VerificationLog: SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,03-17 13:26:17.032  1018  1172 D lights  : lcd : 19 -
,03-17 13:26:17.032  1018  1054 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
03-17 13:26:17.032  1018  1054 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 13:26:17.032  1018  3000 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
03-17 13:26:17.032  1018  3000 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,03-17 13:26:17.032  1018  3000 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.032  1018  3000 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.032  1018  3000 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-17 13:26:17.042  1018  1152 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,03-17 13:26:17.042  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:17.042  1018  1152 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.042  1018  1152 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.042  1018  1152 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.042  1018  1152 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.042  3268  3268 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,03-17 13:26:17.042  3930  3965 I GFX raster: took 0.828698ms for 96*96 texture 0
03-17 13:26:17.042  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8576bb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb855b050 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:17.052  3930  3965 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524,
,03-17 13:26:17.052  4459  4459 E Zygote  : MountEmulatedStorage()
03-17 13:26:17.052  4459  4459 E Zygote  : v2
03-17 13:26:17.052  4459  4459 I libpersona: KNOX_SDCARD checking this for 10135
03-17 13:26:17.052  4459  4459 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:17.062  4459  4459 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:17.062  1018  1152 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4459 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
03-17 13:26:17.062  4459  4459 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:17.062  4459  4459 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:17.072  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-17 13:26:17.072  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationList
03-17 13:26:17.072  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:17.072  3930  3965 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:17.072  3930  3965 I AMMetaDataParserService: Resource data:2131099648
,03-17 13:26:17.082  3930  3965 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
,03-17 13:26:17.082  3930  3965 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:17.092  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:17.092  4459  4459 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:17.092  4459  4459 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:17.092  3930  3965 I GFX raster: took 0.770989ms for 96*96 texture 0
,03-17 13:26:17.092  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb856d628 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb857bb30 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:17.092  1018  1505 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,03-17 13:26:17.092  1018  1505 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-17 13:26:17.102  1018  1018 D WindowManager: showStatusBarByNotification() mOpenByNotification=false
,03-17 13:26:17.102  1018  1018 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-17 13:26:17.102  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 39
,03-17 13:26:17.112  1191  1887 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:17.112  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-17 13:26:17.122  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-17 13:26:17.122  3268  3268 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-17 13:26:17.132  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 39
,03-17 13:26:17.142  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3670/cgroup.procs: No such file or directory
,03-17 13:26:17.142  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-17 13:26:17.142  3930  3965 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-17 13:26:17.152  4459  4459 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 13:26:17.152  4459  4459 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 13:26:17.152  4459  4459 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:17.162  1191  1191 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,03-17 13:26:17.162  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-17 13:26:17.162  3268  3268 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-17 13:26:17.172  1191  1191 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
,03-17 13:26:17.172  1191  1191 D PersonaManager: PersonaID is invalid or persona doesn't exists. : 0
,03-17 13:26:17.172  1191  1191 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:26:17.172  1191  1191 D PersonaManager: isKioskContainerExistOnDevice
,03-17 13:26:17.172  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 39
03-17 13:26:17.172  1191  1191 I PhoneStatusBar: Icon Only
,03-17 13:26:17.172  1191  1191 I StatusBar: Icon Only
,03-17 13:26:17.172  1191  1191 D PanelView: There is/are notification(s) 
03-17 13:26:17.172  1191  1191 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 13:26:17.172  1191  1191 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:26:17.172  1191  1191 I PhoneStatusBar: Icon Only
03-17 13:26:17.172  1191  1191 I StatusBar: Icon Only
,03-17 13:26:17.182  1191  1191 D PanelView: There is/are notification(s) 
03-17 13:26:17.182  1191  1191 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 13:26:17.182  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-17 13:26:17.192  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-17 13:26:17.192  3268  3268 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-17 13:26:17.192  3268  3268 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,03-17 13:26:17.202  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 39
,03-17 13:26:17.212  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-17 13:26:17.222  1317  1329 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 13:26:17.222  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-17 13:26:17.222  3268  3268 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 39
,03-17 13:26:17.232  1018  1152 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,03-17 13:26:17.232  1018  1152 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,03-17 13:26:17.232  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-17 13:26:17.232  1018  1152 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.232  1018  1152 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 13:26:17.232  1018  1152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-17 13:26:17.242  3268  3268 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
03-17 13:26:17.242  4188  4270 W dex2oat : Verification of maps.dz.l maps.dg.p$2.a(maps.dz.l, android.content.res.Resources) took 100.163ms
,03-17 13:26:17.242  3268  3268 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,03-17 13:26:17.252  1191  1191 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,03-17 13:26:17.252  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:17.252  3930  3965 I GFX raster: took 0.634688ms for 96*96 texture 0
03-17 13:26:17.252  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb856d290 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb88d5a08 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:17.262  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-17 13:26:17.272  1018  1369 I art     : Explicit concurrent mark sweep GC freed 36031(2MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 30MB/45MB, paused 3.601ms total 205.457ms
,03-17 13:26:17.282  1018  1369 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
03-17 13:26:17.282  1018  1369 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,03-17 13:26:17.282  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.282  1018  1369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.282  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
03-17 13:26:17.282  3930  3965 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-17 13:26:17.282  1018  2734 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,03-17 13:26:17.282  1018  2734 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-17 13:26:17.292  1018  1483 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,03-17 13:26:17.292  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.292  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.292  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 39
,03-17 13:26:17.292  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.292  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.302  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-17 13:26:17.312  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:17.312  3930  3965 I GFX raster: took 0.637708ms for 96*96 texture 0
03-17 13:26:17.312  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb857beb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb82a7998 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:17.312  3268  3268 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
03-17 13:26:17.312  4482  4482 I libpersona: KNOX_SDCARD checking this for 10139
03-17 13:26:17.312  4482  4482 E Zygote  : MountEmulatedStorage()
03-17 13:26:17.312  4482  4482 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:17.312  4482  4482 E Zygote  : v2
03-17 13:26:17.312  3268  3268 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
03-17 13:26:17.322  1018  1483 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4482 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,03-17 13:26:17.322  4482  4482 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:17.322  3268  3268 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,03-17 13:26:17.322  3268  3268 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,03-17 13:26:17.322  4482  4482 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:17.322  4482  4482 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:17.332  1018  1018 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-17 13:26:17.352  3268  4489 D OpenGLRenderer: Render dirty regions requested: true
,03-17 13:26:17.352  1191  1191 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-17 13:26:17.352  1191  1191 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:26:17.352  1191  1191 D PersonaManager: isKioskContainerExistOnDevice
03-17 13:26:17.352  1191  1191 I PhoneStatusBar: Icon Only
03-17 13:26:17.352  1191  1191 I StatusBar: Icon Only
,03-17 13:26:17.352  1191  1191 D PanelView: There is/are notification(s) 
03-17 13:26:17.352  1191  1191 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-17 13:26:17.352  1191  1191 D PersonaManager: isKioskContainerExistOnDevice
,03-17 13:26:17.352  1018  3002 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 13:26:17.352  1191  1191 I PhoneStatusBar: Icon Only
03-17 13:26:17.352  1018  3002 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 13:26:17.352  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 13:26:17.352  1018  3002 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 13:26:17.352  1191  1191 I StatusBar: Icon Only
03-17 13:26:17.352  1191  1191 D PanelView: There is/are notification(s) 
03-17 13:26:17.352  1191  1191 D PanelView: kidsfalse mQsExpansionEnabled:true
03-17 13:26:17.352  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-17 13:26:17.352  3930  3965 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-17 13:26:17.362  3268  3268 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 13:26:17.362  3268  3268 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-17 13:26:17.362  4482  4482 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:17.362  1018  2999 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:17.372  4482  4482 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:17.372  1018  2999 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:17.372  1018  2999 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:17.372  1018  2999 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,03-17 13:26:17.392  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:17.392  3930  3965 I GFX raster: took 0.640781ms for 96*96 texture 0
03-17 13:26:17.392  4482  4482 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 13:26:17.392  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb857a010 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb88d6e38 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:17.392  4482  4482 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 13:26:17.392  4482  4482 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 13:26:17.392  4482  4482 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 13:26:17.392  4482  4482 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 13:26:17.402  3930  3965 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-17 13:26:17.412  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:17.412  3930  3965 I GFX raster: took 0.623594ms for 96*96 texture 0
03-17 13:26:17.412  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88d0a40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81990b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:17.422   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, YUIInstallC
,03-17 13:26:17.422  1191  1191 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,03-17 13:26:17.422  1018  1050 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 13:26:17.432  1018  1050 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 13:26:17.432  3930  3965 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-17 13:26:17.442  1018  3002 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,03-17 13:26:17.452  1018  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.452  1018  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.452  1018  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.452  1018  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.452  1018  1030 D InputDispatcher: Focus entered window: 3268
,03-17 13:26:17.462  3268  3268 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-17 13:26:17.462  1018  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 13:26:17.462  1018  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 13:26:17.462  3268  4489 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
03-17 13:26:17.462  3268  4489 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 13:26:17.462  3268  4489 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 13:26:17.462  3268  4489 I Adreno-EGL: Local Branch: 
03-17 13:26:17.462  3268  4489 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 13:26:17.462  3268  4489 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 13:26:17.462  3268  4489 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
03-17 13:26:17.472  1018  3002 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4502 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,03-17 13:26:17.472  3268  4489 I OpenGLRenderer: Initialized EGL, version 1.4
03-17 13:26:17.472  1018  1483 I ActivityManager: Killing 3472:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,03-17 13:26:17.482  4502  4502 E Zygote  : MountEmulatedStorage(),
,03-17 13:26:17.482  4502  4502 E Zygote  : v2
03-17 13:26:17.482  4502  4502 I libpersona: KNOX_SDCARD checking this for 10145
03-17 13:26:17.482  4502  4502 I libpersona: KNOX_SDCARD not a persona,
,03-17 13:26:17.482  4502  4502 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 13:26:17.492  4502  4502 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 13:26:17.492  4502  4502 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:17.492  3268  4489 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-17 13:26:17.492  3268  4489 D OpenGLRenderer: Enabling debug mode 0
,03-17 13:26:17.502  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:17.502  3930  3965 I GFX raster: took 0.773073ms for 96*96 texture 0
,03-17 13:26:17.502  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8576bb8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb857bb30 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:17.522  4502  4502 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:17.522  4502  4502 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:17.522  3930  3965 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
,03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
03-17 13:26:17.532  3930  3965 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
,03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity,
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
,03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
,03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
,03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
,03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
,03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
,03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
,03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
,03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity,
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
,03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
,03-17 13:26:17.532  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
,03-17 13:26:17.562  1018  1043 W libprocessgroup: failed to open /acct/uid_10015/pid_3472/cgroup.procs: No such file or directory
,03-17 13:26:17.572  4502  4502 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 13:26:17.572  4502  4502 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:17.572  4502  4502 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 13:26:17.572  4502  4502 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:17.572  4502  4502 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 13:26:17.572  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
03-17 13:26:17.572  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:17.572  3930  3965 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:17.572  3930  3965 I AMMetaDataParserService: Resource data:2131165197
,03-17 13:26:17.582  3930  3965 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 13:26:17.582  3930  3965 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:17.582  3930  3965 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 13:26:17.582  3930  3965 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:17.582  3930  3965 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 13:26:17.582  3930  3965 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 13:26:17.582  3930  3965 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-17 13:26:17.582  3930  3965 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 13:26:17.592  3930  3965 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-17 13:26:17.592  3930  3965 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:17.602  1018  3002 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 13:26:17.602  3930  3965 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-17 13:26:17.602  1018  1052 D PersonaManager: isKioskContainerExistOnDevice
,03-17 13:26:17.622  1018  1052 I ActivityManager: Displayed Component not be shown by security: +904ms (total +1s181ms)
,03-17 13:26:17.622  1191  1191 I StatusBar: Icon Only
03-17 13:26:17.622  3930  3965 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
03-17 13:26:17.622  1191  1191 D PanelView: There is/are notification(s) 
,03-17 13:26:17.622  1018  4518 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:26:17.642  3268  3268 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2dc847d1 time:48404
,03-17 13:26:17.642  1777  1777 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-17 13:26:17.652  3930  3965 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-17 13:26:17.682  1018  1369 I ActivityManager: Killing 3722:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,03-17 13:26:17.682  1018  1231 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:17.682  3930  3965 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-17 13:26:17.692  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
03-17 13:26:17.692  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:17.692  3930  3965 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 13:26:17.692  3930  3965 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:17.692  3930  3965 I AMMetaDataParserService: Resource data:2131165197
,03-17 13:26:17.702  3930  3965 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-17 13:26:17.702  3930  3965 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:17.702  1018  3002 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:17.702  3930  3965 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-17 13:26:17.722  3930  3965 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 13:26:17.732  3930  3965 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-17 13:26:17.752  1018  1388 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:17.762  3930  3965 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-17 13:26:17.762  1018  3000 D RCPManagerService: exchangeData() failure , invalid userId
03-17 13:26:17.762  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.cooliris.media.Gallery
03-17 13:26:17.762  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
03-17 13:26:17.762  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:17.762  3930  3965 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:17.762  3930  3965 I AMMetaDataParserService: Resource data:2131165197
,03-17 13:26:17.772  3930  3965 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
,03-17 13:26:17.772  3930  3965 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:17.772  3930  3965 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-17 13:26:17.792  3930  3965 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-17 13:26:17.802  1018  1043 W libprocessgroup: failed to open /acct/uid_10094/pid_3722/cgroup.procs: No such file or directory
,03-17 13:26:17.802  3930  3965 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-17 13:26:17.822  3930  3965 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-17 13:26:17.832  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
03-17 13:26:17.832  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:17.832  3930  3965 I AMMetaDataParserService: getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
03-17 13:26:17.832  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
,03-17 13:26:17.832  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 13:26:17.842  1018  1031 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
,03-17 13:26:17.842  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.842  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.842  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.842  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
03-17 13:26:17.842  3930  3965 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
,03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity,
03-17 13:26:17.852  4528  4528 I libpersona: KNOX_SDCARD checking this for 10072
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
03-17 13:26:17.852  4528  4528 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: getResourcePackageName:android.app.searchable,
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
,03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
,03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
03-17 13:26:17.842  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
03-17 13:26:17.852  4528  4528 E Zygote  : MountEmulatedStorage()
03-17 13:26:17.852  4528  4528 E Zygote  : v2
,03-17 13:26:17.852  4528  4528 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:17.862  1018  1031 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4528 uid=10072 gids={50072, 9997} abi=armeabi-v7a,
03-17 13:26:17.862  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camera
03-17 13:26:17.862  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-17 13:26:17.862  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
03-17 13:26:17.862  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-17 13:26:17.862  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.keyguard.layout
03-17 13:26:17.862  3930  3965 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:17.862  3930  3965 I AMMetaDataParserService: Resource data:2131099648
,03-17 13:26:17.862  4528  4528 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 13:26:17.862  3930  3965 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 13:26:17.872  3930  3965 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 13:26:17.872  3930  3965 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 13:26:17.872  3930  3965 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 13:26:17.872  3930  3965 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 13:26:17.872  3930  3965 I AMMetaDataParserService: getResourceName:com.sec.android.app.camera:xml/assistant
03-17 13:26:17.872  3930  3965 I AMMetaDataParserService: getResourceTypeNamexml
03-17 13:26:17.872  4528  4528 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,03-17 13:26:17.882  3930  3965 I AMMetaDataParserService: Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,03-17 13:26:17.892  4528  4528 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:17.892  1018  1152 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:17.892  4528  4528 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:17.902  1018  3002 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:17.912  1018  1485 D ActivityManager: startService callerProcessName:com.android.email, calleePkgName: com.android.email
03-17 13:26:17.912  1018  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-17 13:26:17.912  1018  1485 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:17.912  1018  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:17.912  1018  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,03-17 13:26:17.922  3930  3965 I AMMetaDataParserService: Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,03-17 13:26:17.922  4528  4528 D BadgeProvider: onCreate
,03-17 13:26:17.922  4528  4528 D BadgeProvider: DatabaseHelper
,03-17 13:26:17.932  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
03-17 13:26:17.932  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
03-17 13:26:17.932  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
03-17 13:26:17.932  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,03-17 13:26:17.932  3930  3965 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,03-17 13:26:17.962  4528  4540 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-17 13:26:17.982  1018  1388 D ActivityManager: startProcessLocked calleePkgName: com.android.exchange, hostingType: broadcast
,03-17 13:26:17.982  1018  1388 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:17.982  1018  1388 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.982  1018  1388 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:17.982  1018  1388 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:18.002  4549  4549 E Zygote  : MountEmulatedStorage()
03-17 13:26:18.002  4549  4549 E Zygote  : v2
03-17 13:26:18.002  4549  4549 I libpersona: KNOX_SDCARD checking this for 10146
03-17 13:26:18.002  4549  4549 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:18.002  4549  4549 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:18.002  1018  1388 I ActivityManager: Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4549 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
03-17 13:26:18.002  4549  4549 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:18.002  4549  4549 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:18.002  1018  1388 I ActivityManager: Killing 3782:com.sec.factory.camera/1000 (adj 15): empty #31
,03-17 13:26:18.002  1018  1388 I ActivityManager: Killing 3757:com.android.managedprovisioning/u0a22 (adj 15): empty #32
,03-17 13:26:18.032  1490  1490 D Launcher.Model: reloadBadges entered.
,03-17 13:26:18.032  4528  4542 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-17 13:26:18.032  4528  4542 D BadgeProvider: sendNotify, [notify] : null
03-17 13:26:18.032  4528  4542 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-17 13:26:18.032  4528  4542 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 13:26:18.032  4528  4542 D BadgeProvider: update, [UpdateCount] : 1
,03-17 13:26:18.032  4549  4549 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:18.042  4549  4549 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:18.042  4408  4408 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-17 13:26:18.052  1018  1052 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,03-17 13:26:18.052  1018  1052 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{79941fc u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t13} time:48815
03-17 13:26:18.052  1018  1052 W ActivityManager: mDVFSHelper.release()
,03-17 13:26:18.052  4549  4549 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 13:26:18.062   258   444 I SurfaceFlinger: id=12 Removed Mauncher (5/8)
,03-17 13:26:18.062   258  1040 I SurfaceFlinger: id=12 Removed Mauncher (-2/8)
,03-17 13:26:18.072  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GridSettings
03-17 13:26:18.072  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.072  3930  3965 I AMMetaDataParserService: getResourcePackageName:assistant
03-17 13:26:18.072  3930  3965 I AMMetaDataParserService: Resource data:2131165220
,03-17 13:26:18.072  3930  3965 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-17 13:26:18.072  3930  3965 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 13:26:18.072  3930  3965 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 13:26:18.072  3930  3965 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:18.072  3930  3965 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:18.072  3930  3965 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-17 13:26:18.072  3930  3965 I AMMetaDataParserService: getResourceName:com.android.settings:xml/assistant
03-17 13:26:18.072  3930  3965 I AMMetaDataParserService: getResourceTypeNamexml
,03-17 13:26:18.082  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:18.082  3930  3965 I GFX raster: took 0.705990ms for 96*96 texture 0
03-17 13:26:18.082  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8c765a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8c762d8 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:18.082  1018  1044 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-17 13:26:18.082  1018  3000 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,03-17 13:26:18.082  1018  3000 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:18.082  1018  3000 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:18.082  1018  3000 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-17 13:26:18.092  1018  1369 I ActivityManager: Killing 3807:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,03-17 13:26:18.092  1490  1490 D Launcher.HomeView: onStop
,03-17 13:26:18.092  3930  3965 I AMMetaDataParserService: Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,03-17 13:26:18.102  1490  1490 V ActivityThread: updateVisibility : ActivityRecord{7d01bd6 token=android.os.BinderProxy@bd24560 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-17 13:26:18.102  1490  1490 D Launcher: onTrimMemory. Level: 20
,03-17 13:26:18.112  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3782/cgroup.procs: No such file or directory
,03-17 13:26:18.142  3930  3965 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-17 13:26:18.142  3930  3965 I GFX raster: took 0.694115ms for 96*96 texture 0
03-17 13:26:18.142  3930  3965 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8c784f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8c78628 counterpartCT=4 counterpartW=96 counterparth=96
,03-17 13:26:18.152  1018  1483 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:18.162  1018  1031 D ActivityManager: startService callerProcessName:com.android.exchange, calleePkgName: com.android.exchange
03-17 13:26:18.162  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-17 13:26:18.162  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:18.162  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:18.162  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,03-17 13:26:18.162  3930  3965 I AMMetaDataParserService: Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,03-17 13:26:18.162  1018  3004 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
,03-17 13:26:18.162  1018  3004 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:18.162  1018  3004 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:18.162  1018  3004 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:18.162  1018  3004 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:18.172  4565  4565 E Zygote  : MountEmulatedStorage(),
03-17 13:26:18.182  4565  4565 E Zygote  : v2
03-17 13:26:18.182  1018  1043 W libprocessgroup: failed to open /acct/uid_10022/pid_3757/cgroup.procs: No such file or directory,
03-17 13:26:18.182  1018  1043 W libprocessgroup: failed to open /acct/uid_10100/pid_3807/cgroup.procs: No such file or directory
,03-17 13:26:18.182  4565  4565 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:18.182  4565  4565 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:18.182  4565  4565 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 13:26:18.182  1018  3004 I ActivityManager: Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4565 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SubSettings,
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LabelName
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Password
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED,
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity,
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
,03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
,03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
,03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
,03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
,03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
,03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
,03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
,03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
03-17 13:26:18.182  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TetherSettings
,03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
,03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
03-17 13:26:18.202  1018  3002 I ActivityManager: Killing 3836:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
03-17 13:26:18.212  3930  3965 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 ,I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LanguageSettings
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.1,92  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.HomeSettings
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DisplaySettings
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DockSettings
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ManageApplications
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RunningServices
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LaunchApplication
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.StorageUse
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecuritySettings
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CredentialStorage
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetProfileOwner
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.IccLockSettings
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ApnEditor
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormat
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormatSd
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppPicker
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsbSettings
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
03-,17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActivityPicker
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BatteryInfo
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Display
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RadioInfo
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ProxySelector
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BandMode
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TestingSettings
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper
03-17 13:26:18.192  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
03-17 13:26:18.202  4565  4565 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:18.202  4565  4565 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SoundSettings
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GSensorSettings
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
03-17 13:26:18.272  1018  1505 I ActivityManager: Killing 3860:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreview
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreview
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NewModePreview
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor2014
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewStyleClock
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.WarrantyLegal
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.202  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenHelpActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PhoneVibration
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandHelp
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
03-17 13:26:18.282  1018  2734 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settin,gs.PARENT_FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.282  1018  2734 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.282  1018  2734 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
03-17 13:26:18.282  1018  2734 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
03-17 13:26:18.282  1018  2734 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MagazineCard
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Re,source data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
,03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SearchActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
,03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.AppList
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
,03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
,03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Inside bundle  check
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
03-17 13:26:18.212  3930  3965 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
03-17 13:26:18.222  4565  4565 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:18.222  4565  4565 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:18.322  4582  4582 E Zygote  : MountEmulatedStorage()
03-17 13:26:18.322  4582  4582 E Zygote  : v2
03-17 13:26:18.322  4582  4582 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:18.322  4582  4582 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:18.322  4582  4582 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:18.322  4582  4582 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:18.322  4582  4582 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:18.332  1018  2734 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4582 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 13:26:18.332  1018  2734 I ActivityManager: Killing 3880:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31,
,03-17 13:26:18.332  1018  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
03-17 13:26:18.332  1018  1485 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-17 13:26:18.342  1018  1483 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-17 13:26:18.342  1018  2999 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-17 13:26:18.352  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-17 13:26:18.352  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:18.352  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:18.352  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:18.352  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:18.352  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:18.362  4582  4582 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:18.362  4582  4582 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:18.362  1018  1030 W ActivityManager: getTasks: caller 10146 does not hold GET_TASKS; limiting output
,03-17 13:26:18.372  1018  1485 W ActivityManager: getTasks: caller 10145 does not hold GET_TASKS; limiting output
,03-17 13:26:18.372  4502  4547 I Process : Sending signal. PID: 4502 SIG: 9
03-17 13:26:18.372  4549  4572 I Process : Sending signal. PID: 4549 SIG: 9
,03-17 13:26:18.382  1018  2828 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 13:26:18.382  1018  1018 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,03-17 13:26:18.392  4582  4582 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,03-17 13:26:18.392  4582  4582 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,03-17 13:26:18.402  4582  4582 D SecurityLogAgent: StateMachine : Current State = 1
03-17 13:26:18.402  4582  4582 D SecurityLogAgent: BootReceiver : completed task. Failed to return wakelock . 
,03-17 13:26:18.402  1018  1483 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-17 13:26:18.402   255   255 E lowmemorykiller: Error writing /proc/4549/oom_score_adj; errno=22
,03-17 13:26:18.402   255   255 E lowmemorykiller: Error writing /proc/4502/oom_score_adj; errno=22
,03-17 13:26:18.402  1018  1483 I ActivityManager: Killing 3490:com.sec.pcw.device/1000 (adj 15): empty #31
,03-17 13:26:18.402  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3836/cgroup.procs: No such file or directory
03-17 13:26:18.402  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3860/cgroup.procs: No such file or directory
03-17 13:26:18.402  1018  1043 W libprocessgroup: failed to open /acct/uid_10069/pid_3880/cgroup.procs: No such file or directory
,03-17 13:26:18.402  1018  1044 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:18.402  1018  1044 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:18.402  1018  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:18.412  1018  2999 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,03-17 13:26:18.412  1018  2999 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
,03-17 13:26:18.412  1018  2999 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
03-17 13:26:18.412  1018  2999 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-17 13:26:18.412  1018  2999 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:18.412  1018  2999 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:18.412  1018  2999 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:18.452  1018  3001 I ActivityManager: Process com.android.email (pid 4502)(adj 13) has died(47,1148)
,03-17 13:26:18.472  1018  1152 I ActivityManager: Process com.android.exchange (pid 4549)(adj 11) has died(47,1148)
,03-17 13:26:18.542  4188  4188 I dex2oat : dex2oat took 4.517s (threads: 4)
,03-17 13:26:18.552  2079  4168 D DexOptUtils: Odex created at:/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex
03-17 13:26:18.552  2079  4168 D DexOptUtils: Set odex to world readable.
,03-17 13:26:18.552  2079  4168 D DexOptUtils: Renamed odex to /data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.odex
03-17 13:26:18.552  1018  1388 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:18.552  1018  1388 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:18.552  1018  1388 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:18.572  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:18.572  1018  1369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:18.572  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:18.612  1018  1485 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:18.612  1018  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:18.612  1018  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:18.622  1843  4598 E MDM     : [232] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-17 13:26:18.622  1018  3004 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:18.622  1018  3004 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:18.622  1018  3004 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:18.622  1018  3004 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:18.622  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:18.632  1018  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:18.632  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:18.632  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 13:26:18.632  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-17 13:26:18.632  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:18.632  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:18.632  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:18.642  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 13:26:18.642  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,03-17 13:26:18.642  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:18.642  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:18.642  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:18.642  1018  1388 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:18.642  1018  1388 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:18.642  1018  1388 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:18.652  2079  4599 D LocationInitializer: Restart initialization of location
,03-17 13:26:18.662  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3490/cgroup.procs: No such file or directory
,03-17 13:26:18.662  1018  1388 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:18.662  1018  1388 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:18.662  1018  1388 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:18.672  1018  1388 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 13:26:18.672  1018  1388 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,03-17 13:26:18.672  1018  1388 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:18.672  1018  1388 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:18.672  1018  1388 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:18.712  1018  1316 E Watchdog: !@Sync 1
,03-17 13:26:18.722  1018  2999 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 13:26:18.722  1018  2999 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,03-17 13:26:18.722  1018  2999 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:18.722  1018  2999 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:18.722  1018  2999 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:18.732  1467  1477 D TP/SmsProvider: query,matched:0, calling pid = 2079
,03-17 13:26:18.732  1467  1477 D TP/SmsProvider: match 0:Elapsed time : 2.002 ms
,03-17 13:26:18.732  1018  1151 D SettingsProvider: name = audio_safe_volume_state
,03-17 13:26:18.742  1467  1481 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2079
,03-17 13:26:18.762  1467  1477 D TP/SmsProvider: query,matched:0, calling pid = 2079
,03-17 13:26:18.762  1467  1477 D TP/SmsProvider: match 0:Elapsed time : 1.459 ms
,03-17 13:26:18.772  1018  3002 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,03-17 13:26:18.772  1018  3002 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,03-17 13:26:18.772  1018  3002 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:18.772  1018  3002 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:18.772  1018  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:18.782  1467  1481 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2079
,03-17 13:26:18.792  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,03-17 13:26:18.792  1843  1843 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 13:26:18.802  1843  1843 D a       : Opening database auth.proximity.permit_store...
,03-17 13:26:18.802  1018  3004 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:18.802  1018  3004 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:18.802  1018  3004 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:18.822  1018  2734 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:18.822  1018  2734 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:18.822  1018  2734 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:18.822  1018  2734 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:18.852  1018  1483 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 13:26:18.852  1018  1483 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,03-17 13:26:18.852  1018  1483 W ActivityManager: userId = 0, bbcId = -10000,
03-17 13:26:18.852  1018  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:18.852  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:18.862  2079  4605 W IcingInternalCorpora: getNumBytesRead when not calculated.
,03-17 13:26:18.872  1018  1388 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 13:26:18.872  1018  1388 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,03-17 13:26:18.872  1018  1388 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:18.872  1018  1388 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:18.872  1018  1388 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:18.872  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:18.872  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:18.872  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:18.882  1843  1843 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:26:18.892  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:18.892  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:18.892  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:18.892  1843  2096 W GCoreFlp: No location to return for getLastLocation()
,03-17 13:26:18.892  1843  4610 W FusedLocationProvider: location=null
03-17 13:26:18.892  1018  1152 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 13:26:18.892  1018  1152 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,03-17 13:26:18.892  1018  1152 W ActivityManager: userId = 0, bbcId = -10000,
03-17 13:26:18.892  1018  1152 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:18.902  1018  1152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:18.912  1018  1483 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,03-17 13:26:18.912  1018  1483 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 13:26:18.912  1018  1483 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:18.912  1018  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:18.912  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 13:26:18.912  2587  2587 I Hs20UtilService: Starting #3
,03-17 13:26:18.912  2587  2604 I Hs20UtilService: Message received 5011
,03-17 13:26:18.912  1018  1135 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
03-17 13:26:18.912  1018  1135 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-17 13:26:18.912  1018  1135 E WifiNative-wlan0: invaild command id : 215
,03-17 13:26:18.922  4582  4582 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-17 13:26:18.922  4582  4582 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-17 13:26:18.922  4582  4582 D SecurityLogAgent: StateMachine : Current State = 1
,03-17 13:26:18.922  4582  4582 D SecurityLogAgent: StateMachine : Changed Current State = 1
,03-17 13:26:18.932  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.example.hello, hostingType: broadcast
,03-17 13:26:18.932  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:18.932  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:18.932  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:18.932  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:18.932  4209  4231 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-17 13:26:18.942  4209  4231 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-17 13:26:18.942  4619  4619 E Zygote  : MountEmulatedStorage()
03-17 13:26:18.942  4619  4619 E Zygote  : v2
03-17 13:26:18.942  4619  4619 I libpersona: KNOX_SDCARD checking this for 10174
03-17 13:26:18.942  4619  4619 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:18.942  4619  4619 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:18.942  4209  4231 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-17 13:26:18.952  1018  1031 I ActivityManager: Start proc com.example.hello for broadcast com.example.hello/io.jxcore.node.ConnectivityChangeListener: pid=4619 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,03-17 13:26:18.952  4619  4619 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:18.952  4619  4619 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-17 13:26:18.952  4209  4231 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-17 13:26:18.952  4209  4231 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-17 13:26:18.952  4209  4231 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-17 13:26:18.952  4209  4231 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-17 13:26:18.962   291   291 E SMD     : DCD OFF
,03-17 13:26:18.972  4619  4619 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:18.972  4619  4619 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:19.002  4619  4619 D jxcore_app_log: JniHelper::setJavaVM(0xb819d450), pthread_self() = -1224991032
03-17 13:26:19.002  4619  4619 E JX-Cordova: JXcore wasn't initialized yet
,03-17 13:26:19.002  1367  1367 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,03-17 13:26:19.012  1367  1367 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-17 13:26:19.012  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-17 13:26:19.012  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,03-17 13:26:19.012  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
03-17 13:26:19.012  1367  1367 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 13:26:19.012  1018  3004 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,03-17 13:26:19.012  1018  3004 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:19.012  1018  3004 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.012  1018  3004 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.012  1018  3004 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:19.032  4634  4634 E Zygote  : MountEmulatedStorage(),
03-17 13:26:19.032  4634  4634 E Zygote  : v2
03-17 13:26:19.032  4634  4634 I libpersona: KNOX_SDCARD checking this for 10068,
03-17 13:26:19.032  4634  4634 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:19.032  1018  3004 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=4634 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-17 13:26:19.032  4634  4634 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 13:26:19.032  4634  4634 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:19.032  4634  4634 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:19.052  4634  4634 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:19.052  4634  4634 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:19.062  4634  4634 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-17 13:26:19.072  4634  4634 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,03-17 13:26:19.082  4634  4634 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,03-17 13:26:19.102  4634  4634 D FileShare-Client: Outbound.stopDelayTimer - 
,03-17 13:26:19.112  1018  1369 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,03-17 13:26:19.112  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:19.112  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.112  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.112  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:19.122  4649  4649 E Zygote  : MountEmulatedStorage()
03-17 13:26:19.122  4649  4649 I libpersona: KNOX_SDCARD checking this for 10069
,03-17 13:26:19.122  4649  4649 E Zygote  : v2
03-17 13:26:19.122  4649  4649 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:19.122  4649  4649 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 13:26:19.122  1018  1369 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=4649 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:19.122  1018  1369 I ActivityManager: Killing 3693:com.samsung.android.sm/1000 (adj 15): empty #31
,03-17 13:26:19.132  4649  4649 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:19.132  4649  4649 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:19.142  4649  4649 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:19.142  4649  4649 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:19.162  4649  4649 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,03-17 13:26:19.172  1018  1152 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:19.172  1018  1152 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:19.172  1018  1152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:19.172  1018  1152 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,03-17 13:26:19.172  1018  1152 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
03-17 13:26:19.172  1018  1152 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
,03-17 13:26:19.172  1018  1152 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-17 13:26:19.172  1018  1152 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:19.172  1018  1152 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:19.172  1018  1152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:19.182  1018  1152 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:19.182  1018  1152 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:19.182  1018  1152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:19.182  1018  1231 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:19.192  1018  1231 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:19.192  1018  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:19.192  1018  3002 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:19.192  1018  3002 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:19.192  1018  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:19.192  1018  1483 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:19.202  1843  4664 E MDM     : [247] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-17 13:26:19.202  1018  1483 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:19.202  1018  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:19.202  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:19.212  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:19.212  1018  1369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:19.212  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:19.212  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:19.212  1018  1369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:19.212  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:19.212  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 13:26:19.222  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-17 13:26:19.222  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:19.222  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:19.222  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:19.222  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:19.222  1018  1369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:19.222  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:19.222  2079  4665 D LocationInitializer: Restart initialization of location
,03-17 13:26:19.222  1843  1843 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-17 13:26:19.232  1018  3001 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 13:26:19.232  1018  3001 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,03-17 13:26:19.232  1018  3001 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:19.232  1018  3001 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:19.232  1018  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:19.232  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:19.232  1018  1369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:19.232  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:19.242  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3693/cgroup.procs: No such file or directory
,03-17 13:26:19.242  1018  2999 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 13:26:19.242  1018  2999 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,03-17 13:26:19.242  1018  2999 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:19.242  1018  2999 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:19.242  1018  2999 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:19.242  1018  1152 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:19.242  1018  1152 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:19.242  1018  1152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:19.252  1843  1843 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-17 13:26:19.252  1018  1483 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:19.252  1018  1483 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:19.252  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:19.252  1018  3000 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 13:26:19.252  1018  3000 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,03-17 13:26:19.262  1018  3000 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:19.262  1018  3000 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:19.262  1018  3000 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:19.262  1843  2096 W GCoreFlp: No location to return for getLastLocation()
03-17 13:26:19.262  1843  4666 W FusedLocationProvider: location=null
,03-17 13:26:19.282  1018  3000 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
03-17 13:26:19.282  1018  3000 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 13:26:19.282  1018  3000 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:19.282  1018  3000 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:19.282  1018  3000 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 13:26:19.282  2587  2587 I Hs20UtilService: Starting #4
,03-17 13:26:19.282  2587  2604 I Hs20UtilService: Message received 5007
,03-17 13:26:19.282  1018  1231 I ActivityManager: Killing 3232:com.test.thalitest/u0a155 (adj 15): empty #31
,03-17 13:26:19.282  1367  1367 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 13:26:19.282  1367  1367 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-17 13:26:19.282  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-17 13:26:19.282  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
03-17 13:26:19.292  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
03-17 13:26:19.292  1367  1367 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 13:26:19.292  1018  1152 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,03-17 13:26:19.292  1018  1152 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 13:26:19.292  1018  1152 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:19.292  1018  1152 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:19.292  1018  1152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 13:26:19.292  2587  2587 I Hs20UtilService: Starting #5
,03-17 13:26:19.302  2587  2604 I Hs20UtilService: Message received 5007
,03-17 13:26:19.302  1367  1367 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 13:26:19.302  1367  1367 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 13:26:19.312  1018  3002 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
03-17 13:26:19.312  1018  3002 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 13:26:19.312  1018  3002 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:19.312  1018  3002 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:19.312  1018  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 13:26:19.312  2587  2587 I Hs20UtilService: Starting #6
,03-17 13:26:19.312  2587  2604 I Hs20UtilService: Message received 5007
,03-17 13:26:19.312  1367  1367 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-17 13:26:19.312  1367  1367 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-17 13:26:19.312  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-17 13:26:19.312  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
03-17 13:26:19.312  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
03-17 13:26:19.312  1367  1367 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 13:26:19.322  1018  1483 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,03-17 13:26:19.322  1018  1483 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-17 13:26:19.322  1018  1483 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:19.322  1018  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:19.322  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-17 13:26:19.332  2587  2587 I Hs20UtilService: Starting #7
,03-17 13:26:19.332  1367  1367 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
03-17 13:26:19.332  2587  2604 I Hs20UtilService: Message received 5007
03-17 13:26:19.332  1367  1367 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-17 13:26:19.332  1018  1369 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,03-17 13:26:19.332  1018  3002 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,03-17 13:26:19.342  1018  3002 D SecContentProvider2: mCursor = null
,03-17 13:26:19.342  1018  3000 D SecContentProvider2: uri = 15 selection = getToastGravity
,03-17 13:26:19.342  1018  3000 D SecContentProvider2: mCursor = null
,03-17 13:26:19.342  1018  2999 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,03-17 13:26:19.342  1018  2999 D SecContentProvider2: mCursor = null
,03-17 13:26:19.342  1018  1388 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,03-17 13:26:19.342  1018  1388 D SecContentProvider2: mCursor = null
,03-17 13:26:19.342  1018  3004 D SecContentProvider2: uri = 15 selection = getToastEnabledState
03-17 13:26:19.342  1018  3004 D SecContentProvider2: mCursor = null
,03-17 13:26:19.342  1018  1231 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,03-17 13:26:19.342  1018  1231 D SecContentProvider2: mCursor = null
,03-17 13:26:19.352  1018  1483 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,03-17 13:26:19.352  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:19.352  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:19.352  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.352  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:19.362  1018  1018 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,03-17 13:26:19.362   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,03-17 13:26:19.372  4669  4669 E Zygote  : MountEmulatedStorage()
,03-17 13:26:19.372  4669  4669 E Zygote  : v2
03-17 13:26:19.372  4669  4669 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:19.372  4669  4669 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:19.372  4669  4669 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 13:26:19.372  1018  1483 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=4669 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 13:26:19.382  1018  1369 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
03-17 13:26:19.382  1018  1054 D DisplayPowerController: getFinalBrightness : Summary is 60 -> 60
03-17 13:26:19.382  1018  1054 D DisplayPowerController: animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-17 13:26:19.382  1018  1054 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
03-17 13:26:19.392  4669  4669 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:19.392  4669  4669 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:19.392  1191  1191 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! ,
03-17 13:26:19.392   315   315 I art     : Explicit concurrent mark sweep GC freed 8724(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 742us total 20.743ms
03-17 13:26:19.392  1018  1172 D lights  : lcd : 42 +
,03-17 13:26:19.402  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
03-17 13:26:19.402  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:19.402  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:19.402  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:19.402  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:19.402  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:19.412  1018  1172 D lights  : lcd : 42 -
,03-17 13:26:19.412   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 727us total 18.726ms
,03-17 13:26:19.412  1018  1172 D lights  : lcd : 60 +
03-17 13:26:19.412  1018  1054 D DisplayPowerController: getFinalBrightness : Summary is 60 -> 60
03-17 13:26:19.412  1018  1054 D DisplayPowerController: animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 13:26:19.412  4669  4669 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:19.422  4669  4669 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:19.432   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 17.039ms
,03-17 13:26:19.432  1018  1172 D lights  : lcd : 60 -
03-17 13:26:19.432  1018  1054 D DisplayPowerController: getFinalBrightness : Summary is 60 -> 60
03-17 13:26:19.432  1018  1054 D DisplayPowerController: animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-17 13:26:19.442  1018  1041 D SensorService: [SO] 0.153 0.421 10.113,
,03-17 13:26:19.442  4669  4669 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
03-17 13:26:19.442  4669  4669 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
03-17 13:26:19.442  4669  4669 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-17 13:26:19.452  4669  4669 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true,
03-17 13:26:19.452  4669  4669 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 13:26:19.452  4669  4669 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 13:26:19.452  4669  4669 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,03-17 13:26:19.462  1018  2999 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=10, mSplitNum[1]=17, mSplitNum[2]=26, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=34
03-17 13:26:19.462  1018  2999 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,03-17 13:26:19.462  1018  2999 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,03-17 13:26:19.462  1018  2999 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:19.462  1018  2999 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.462  1018  2999 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.462  1018  2999 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:19.472  4686  4686 E Zygote  : MountEmulatedStorage(),
03-17 13:26:19.472  4686  4686 E Zygote  : v2
,03-17 13:26:19.472  4686  4686 I libpersona: KNOX_SDCARD checking this for 10111
,03-17 13:26:19.472  4686  4686 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:19.482  4686  4686 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:19.482  1018  2999 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4686 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 13:26:19.482  4686  4686 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:19.482  1018  2999 I ActivityManager: Killing 3930:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,03-17 13:26:19.482  4686  4686 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:19.492  1737  1737 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-17 13:26:19.492  3703  3703 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 13:26:19 GMT+01:00 2016
,03-17 13:26:19.492  1018  1485 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
03-17 13:26:19.492  1018  1485 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
03-17 13:26:19.492  4582  4582 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-17 13:26:19.492  4582  4582 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-17 13:26:19.492  4582  4582 D SecurityLogAgent: StateMachine : Current State = 1
03-17 13:26:19.492  4582  4582 D SecurityLogAgent: StateMachine : Changed Current State = 1
,03-17 13:26:19.502  1018  1485 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:19.502  1018  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:19.502  1018  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 13:26:19.502  1018  1043 W libprocessgroup: failed to open /acct/uid_10155/pid_3232/cgroup.procs: No such file or directory
,03-17 13:26:19.502  1018  1483 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,03-17 13:26:19.502  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.502  3703  3703 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-17 13:26:19.502  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.502  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.502  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:19.512  3703  3703 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-17 13:26:19.512  3703  3703 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 13:26:19.512  3703  3703 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 13:26:19.512  4686  4686 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:19.512  3703  4699 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
03-17 13:26:19.512  4686  4686 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:19.522  3703  4699 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,03-17 13:26:19.522  4702  4702 E Zygote  : MountEmulatedStorage(),
03-17 13:26:19.522  4702  4702 E Zygote  : v2
,03-17 13:26:19.522  4702  4702 I libpersona: KNOX_SDCARD checking this for 10159
03-17 13:26:19.522  4702  4702 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:19.522  4702  4702 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 13:26:19.522  1018  1483 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=4702 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-17 13:26:19.522  4702  4702 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:19.522  4702  4702 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,03-17 13:26:19.532  3703  4699 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,03-17 13:26:19.532  3703  4699 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().START
,03-17 13:26:19.542  3703  4699 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().START 
,03-17 13:26:19.542  1317  1338 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 10
,03-17 13:26:19.552  1737  1737 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,03-17 13:26:19.552  1737  1737 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
03-17 13:26:19.552  1737  1737 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
03-17 13:26:19.552  1737  1737 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,03-17 13:26:19.552  3703  4699 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().END 
,03-17 13:26:19.552  3703  4699 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,03-17 13:26:19.552  4702  4702 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:19.552  4702  4702 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:19.562  3703  3703 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-17 13:26:19.572  1737  1737 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-17 13:26:19.572  1737  1737 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-17 13:26:19.572  1018  2999 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,03-17 13:26:19.572  1018  2999 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:19.572  1018  2999 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.572  1018  2999 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.572  1018  2999 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:19.582  4209  4717 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 13:26:19.582  4209  4717 I DBG_POLICYDM: [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 0, current network is 2
,03-17 13:26:19.582  4209  4717 E DBG_POLICYDM: [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... ,
,03-17 13:26:19.602  4718  4718 E Zygote  : MountEmulatedStorage(),
03-17 13:26:19.602  4718  4718 E Zygote  : v2
03-17 13:26:19.602  4718  4718 I libpersona: KNOX_SDCARD checking this for 10081
,03-17 13:26:19.602  4718  4718 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:19.602  4718  4718 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 13:26:19.602  4209  4717 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
03-17 13:26:19.602  4209  4717 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
03-17 13:26:19.602  4718  4718 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:19.612  1018  2999 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=4718 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:19.602  4718  4718 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
03-17 13:26:19.602  4209  4717 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
03-17 13:26:19.602  4209  4717 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-17 13:26:19.612  4209  4717 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-17 13:26:19.612  4209  4717 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-17 13:26:19.612  4209  4717 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
03-17 13:26:19.612  4209  4717 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,03-17 13:26:19.622  4209  4717 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,03-17 13:26:19.632  4289  4289 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,03-17 13:26:19.632  4209  4717 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-17 13:26:19.642  4718  4718 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:19.642  4718  4718 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:19.642  4317  4317 I SA      : [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,03-17 13:26:19.652  4317  4317 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
03-17 13:26:19.652  4317  4317 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,03-17 13:26:19.722  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3930/cgroup.procs: No such file or directory
,03-17 13:26:19.732  4317  4317 I SA      : [SLFUCHKMGR] constructor called
,03-17 13:26:19.742  4317  4317 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
03-17 13:26:19.742  4317  4317 I SA      : [OR] == isSIMCardReady false ==
,03-17 13:26:19.862  2079  4737 I iu.SyncManager: SYNC; picasa accounts
,03-17 13:26:19.892  4317  4317 I SA      : [SCU] == networkStateCheck == true
,03-17 13:26:19.892  4317  4317 I SA      : [DM] getCountryCodeFromCSC : PL
03-17 13:26:19.892  4317  4317 I SA      : isChinaCountryCode : false
03-17 13:26:19.892  4317  4317 I SA      : [SCU] is ChinestModel Data Restricted   : false
03-17 13:26:19.892  4317  4317 I SA      : [OR] == networkStateCheck true ==
,03-17 13:26:19.892  2079  2079 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-17 13:26:19.892  2079  2079 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-17 13:26:19.902  4317  4317 I SA      : [OR] GetMyCountryZoneTask
,03-17 13:26:19.902  4317  4317 I SA      : [OR] onReceive END
,03-17 13:26:19.902  1240  1240 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,03-17 13:26:19.912  1018  1031 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,03-17 13:26:19.912  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,03-17 13:26:19.912  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:19.912  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:19.912  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 13:26:19.932  1018  1152 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 13:26:19.932  1018  1152 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-17 13:26:19.932  1018  1152 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:19.932  1018  1152 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:19.932  1018  1152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:19.932  1018  3004 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,03-17 13:26:19.932  1018  3004 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.932  1018  3004 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.932  1018  3004 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:19.932  1018  3004 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:19.942  1018  3002 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
03-17 13:26:19.942  1018  3002 D SecContentProvider2: mCursor = null
,03-17 13:26:19.952  4742  4742 E Zygote  : MountEmulatedStorage()
,03-17 13:26:19.952  4742  4742 E Zygote  : v2
03-17 13:26:19.952  4742  4742 I libpersona: KNOX_SDCARD checking this for 10010
03-17 13:26:19.952  4742  4742 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:19.952  4742  4742 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:19.952  1018  3004 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4742 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-17 13:26:19.952  4742  4742 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:19.952  4742  4742 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-17 13:26:19.962  2079  4737 I iu.UploadsManager: num queued entries: 0
,03-17 13:26:19.962  2079  4737 I iu.UploadsManager: num updated entries: 0
,03-17 13:26:19.962  2079  4737 I iu.SyncManager: NEXT; no task
,03-17 13:26:19.982  4742  4742 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:19.982  4742  4742 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:19.982  4686  4686 I MusicStore: Database version: 108
,03-17 13:26:20.012  4317  4740 I SA      : [SRS] prepareGetMyCountryZone
,03-17 13:26:20.012  4317  4740 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-17 13:26:20.012  4317  4740 I SA      : [SSP] query invoked
,03-17 13:26:20.102  1018  1231 I art     : Explicit concurrent mark sweep GC freed 31778(1934KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 30MB/45MB, paused 2.375ms total 143.708ms
,03-17 13:26:20.112  4317  4740 I SA      : [TPMU] GetMccFromDB : null
03-17 13:26:20.112  4317  4740 I SA      : [SCU] getMccFromPreferece mcc = 260
03-17 13:26:20.112  4317  4740 I SA      : [TPM] isNoProxy(default) : true
,03-17 13:26:20.112  1018  1483 I ActivityManager: Killing 3826:com.google.android.gm/u0a101 (adj 15): empty #31
,03-17 13:26:20.122  1018  2999 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
03-17 13:26:20.122  1018  2999 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-17 13:26:20.122  1018  2999 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:20.122  1018  2999 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:20.122  1018  2999 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 13:26:20.122  4317  4740 E File    : fail readDirectory() errno=2
,03-17 13:26:20.172  1018  1369 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,03-17 13:26:20.172  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:20.172  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.172  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:20.172  1018  1369 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:20.192  4762  4762 E Zygote  : MountEmulatedStorage()
,03-17 13:26:20.192  4762  4762 E Zygote  : v2
03-17 13:26:20.192  4762  4762 I libpersona: KNOX_SDCARD checking this for 10113
03-17 13:26:20.192  4762  4762 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:20.192  1018  1369 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4762 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 13:26:20.192  4762  4762 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:20.192  1018  1369 I ActivityManager: Killing 3950:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,03-17 13:26:20.192  4762  4762 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:20.192  4762  4762 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-17 13:26:20.222  4762  4762 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:20.222  4762  4762 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:20.272  1018  1044 I ActivityManager: Waited long enough for: ServiceRecord{3f410f18 u0 com.samsung.android.providers.context/.ContextService}
,03-17 13:26:20.312  4686  4686 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-17 13:26:20.312  4686  4686 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-17 13:26:20.322  4742  4742 D WaitQueueForNetworkActivate: notifyNetworkActivated
,03-17 13:26:20.332  1018  1043 W libprocessgroup: failed to open /acct/uid_10101/pid_3826/cgroup.procs: No such file or directory
03-17 13:26:20.332  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3950/cgroup.procs: No such file or directory
,03-17 13:26:20.342  4686  4686 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-17 13:26:20.372  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 13:26:20.372  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:20.372  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:20.372  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:20.372  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:20.372  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:20.392  4686  4686 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-17 13:26:20.402  4686  4686 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@6562462: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-17 13:26:20.402  4686  4686 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-17 13:26:20.402  4686  4686 D AndroidMusic: GMSCore installation verified
,03-17 13:26:20.412  4742  4742 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,03-17 13:26:20.412  1018  3002 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:20.422  1018  3002 W ActivityManager: Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found,
,03-17 13:26:20.462  1018  1485 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
03-17 13:26:20.462  1018  1485 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,03-17 13:26:20.462  1018  1485 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:20.462  1018  1485 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:20.462  1018  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 13:26:20.472  4686  4686 I ConfigStore: Config Database version: 1
,03-17 13:26:20.482   257   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-17 13:26:20.482   257   529 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:20.482  4762  4785 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-17 13:26:20.482   257   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-17 13:26:20.482   257   529 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:20.482  4762  4785 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-17 13:26:20.502   257   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-17 13:26:20.502   257   529 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:20.502  4762  4788 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-17 13:26:20.512   257   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-17 13:26:20.512   257   529 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:20.512  4762  4788 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-17 13:26:20.562   257   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
,03-17 13:26:20.562   257   529 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:20.562  4686  4686 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-17 13:26:20.572   257   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-17 13:26:20.572   257   529 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:20.572  4686  4686 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-17 13:26:20.572   257   529 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-17 13:26:20.572   257   529 W Vold    : Returning OperationFailed - no handler for errno 0
,03-17 13:26:20.572  4686  4686 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-17 13:26:20.572  1018  1505 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,03-17 13:26:20.572  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,03-17 13:26:20.582  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:20.582  1018  1505 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,03-17 13:26:20.582  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,03-17 13:26:20.582  4742  4742 D hcjo    : AutoUpdateManager:IDLE:execute
,03-17 13:26:20.592  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,03-17 13:26:20.592  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,03-17 13:26:20.592  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:20.592  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:20.592  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 13:26:20.592  4742  4742 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,03-17 13:26:20.592  4742  4742 D InitializeManagerStateMachine: exit::IDLE
03-17 13:26:20.592  4742  4742 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,03-17 13:26:20.602  4742  4742 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
03-17 13:26:20.602  4742  4742 D InitializeManagerStateMachine: exit::NETWORK_CHECK
03-17 13:26:20.602  4742  4742 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
03-17 13:26:20.602  4742  4742 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
03-17 13:26:20.602  4742  4742 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
03-17 13:26:20.602  4742  4742 D InitializeManagerStateMachine: entry::SUCCESS
03-17 13:26:20.602  4742  4742 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,03-17 13:26:20.602  1018  1030 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
03-17 13:26:20.602  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,03-17 13:26:20.602  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:20.602  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:20.602  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 13:26:20.612  4742  4742 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:345600000
,03-17 13:26:20.612  4742  4742 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
03-17 13:26:20.612  4742  4742 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,03-17 13:26:20.612  4742  4742 D InitializeManagerStateMachine: exit::SUCCESS
03-17 13:26:20.612  4742  4742 D InitializeManagerStateMachine: entry::IDLE
,03-17 13:26:20.642  1018  3000 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 13:26:20.662  1018  1030 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 13:26:20.672  1018  1485 I AudioService: getStreamVolume 3 index 0
,03-17 13:26:20.672  4686  4686 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,03-17 13:26:20.682  4686  4686 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-17 13:26:20.682  1018  2999 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:20.682  1018  2999 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:20.682  1018  2999 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:20.682  1018  2999 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,03-17 13:26:20.682  4686  4686 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-17 13:26:20.712  4762  4762 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-17 13:26:20.722  1018  1369 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
03-17 13:26:20.722  1018  1369 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-17 13:26:20.722  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:20.722  1018  1369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:20.722  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 13:26:20.722  1018  3004 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,03-17 13:26:20.722  1018  3004 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,03-17 13:26:20.722  1018  3004 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:20.722  1018  3004 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:20.722  1018  3004 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 13:26:20.722  4762  4762 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1485-1487)
,03-17 13:26:20.722  4762  4762 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 13:26:20.732  1018  3000 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,03-17 13:26:20.732  1018  3000 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,03-17 13:26:20.732  1018  3000 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:20.732  1018  3000 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-17 13:26:20.732  1018  3000 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 13:26:20.732  4762  4762 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4e68461}
,03-17 13:26:20.732  4762  4762 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-17 13:26:20.732  4762  4762 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,03-17 13:26:20.742  1018  1505 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-17 13:26:20.742  4686  4686 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-17 13:26:20.752  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,03-17 13:26:20.752  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.752  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.752  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.752  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:20.752  4762  4762 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-17 13:26:20.752  4762  4762 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 13:26:20.762  4762  4762 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 13:26:20.762  4811  4811 E Zygote  : MountEmulatedStorage()
,03-17 13:26:20.762  4811  4811 I libpersona: KNOX_SDCARD checking this for 10002
03-17 13:26:20.762  4811  4811 E Zygote  : v2
03-17 13:26:20.762  4811  4811 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:20.762  4811  4811 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:20.762  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4811 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 13:26:20.772  4811  4811 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:20.772  4811  4811 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:20.792  1018  3001 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,03-17 13:26:20.792  1018  3001 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,03-17 13:26:20.792  1018  3001 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:20.792  1018  3001 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:20.792  1018  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,03-17 13:26:20.792  4811  4811 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:20.792  4811  4811 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:20.802  4762  4762 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,03-17 13:26:20.802  4762  4762 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,03-17 13:26:20.802  4762  4762 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
03-17 13:26:20.802  4686  4686 W GoogleHttpClient: Failed to load SSLCertificateSocketFactory from package
03-17 13:26:20.802  4686  4686 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,03-17 13:26:20.802  4686  4686 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,03-17 13:26:20.802  1018  3004 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
03-17 13:26:20.802  1018  3004 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-17 13:26:20.802  1018  3004 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:20.802  1018  3004 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:20.802  1018  3004 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-17 13:26:20.812  4762  4762 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 13:26:20.812  4762  4762 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 13:26:20.812  4762  4762 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 13:26:20.812  4762  4762 I Adreno-EGL: Local Branch: 
03-17 13:26:20.812  4762  4762 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 13:26:20.812  4762  4762 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 13:26:20.812  4762  4762 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 13:26:20.822  1018  1044 I ActivityManager: Waited long enough for: ServiceRecord{1fb897c1 u0 com.android.settings/.wifi.WifiCredService}
,03-17 13:26:20.872  4762  4839 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-17 13:26:20.872  4762  4762 I NSApplication: Starting up...
,03-17 13:26:20.892  1018  3000 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,03-17 13:26:20.892  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:20.892  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.892  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.892  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:20.902  4846  4846 E Zygote  : MountEmulatedStorage()
,03-17 13:26:20.902  4846  4846 E Zygote  : v2
03-17 13:26:20.902  4846  4846 I libpersona: KNOX_SDCARD checking this for 10120
03-17 13:26:20.902  4846  4846 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:20.902  4846  4846 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:20.902  1018  3000 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4846 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-17 13:26:20.912  4846  4846 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:20.912  1018  3000 I ActivityManager: Killing 4153:com.samsung.helphub/1000 (adj 15): empty #31
03-17 13:26:20.912  4846  4846 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-17 13:26:20.912  1018  3000 I ActivityManager: Killing 3412:com.google.android.youtube/u0a166 (adj 15): empty #32
03-17 13:26:20.912  1018  3000 I ActivityManager: Killing 3910:com.vlingo.midas/u0a31 (adj 15): empty #33
,03-17 13:26:20.932  4846  4846 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:20.932  4846  4846 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:20.932  1018  3001 I ActivityManager: Killing 4072:com.android.vending/u0a28 (adj 15): empty #31
,03-17 13:26:20.942  1018  3001 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,03-17 13:26:20.942  1018  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:20.942  1018  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:20.942  1018  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:20.942  1018  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:20.952  4861  4861 E Zygote  : MountEmulatedStorage()
,03-17 13:26:20.952  4861  4861 E Zygote  : v2
03-17 13:26:20.952  4861  4861 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:20.952  4861  4861 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:20.952  1018  3001 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4861 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 13:26:20.952  4861  4861 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:20.962  4861  4861 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:20.962  4861  4861 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:20.982  4846  4846 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 13:26:20.992  4861  4861 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:20.992  4861  4861 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:21.032  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_4153/cgroup.procs: No such file or directory
,03-17 13:26:21.032  1018  1043 W libprocessgroup: failed to open /acct/uid_10028/pid_4072/cgroup.procs: No such file or directory
03-17 13:26:21.032  1018  1043 W libprocessgroup: failed to open /acct/uid_10031/pid_3910/cgroup.procs: No such file or directory
03-17 13:26:21.032  1018  1043 W libprocessgroup: failed to open /acct/uid_10166/pid_3412/cgroup.procs: No such file or directory
,03-17 13:26:21.032  4861  4861 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-17 13:26:21.162  4317  4740 I SA      : [RC New] Execute method=[GET] start
,03-17 13:26:21.172  4861  4861 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-17 13:26:21.182  4861  4861 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-17 13:26:21.192  4861  4861 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,03-17 13:26:21.192  4861  4861 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-17 13:26:21.192  4861  4861 I DIAGMON_AGENT: ./extraInfo: "NG700"
,03-17 13:26:21.192  4861  4861 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-17 13:26:21.192  4317  4740 I SA      : [RC New] Security=[true],
,03-17 13:26:21.192  4317  4740 I System.out: Thread-645(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-17 13:26:21.202  4317  4740 I System.out: Thread-645(ApacheHTTPLog):isSBSettingEnabled false
03-17 13:26:21.202  4317  4740 I System.out: Thread-645(ApacheHTTPLog):isShipBuild true
03-17 13:26:21.202  4317  4740 I System.out: Thread-645(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-17 13:26:21.202  4317  4740 I System.out: Thread-645(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false,
,03-17 13:26:21.202   278   875 D EnterpriseController: uids 10041
,03-17 13:26:21.202   278   875 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-17 13:26:21.202   278   875 D Netd    : getNetworkForDns: using netid 502 for uid 10041
,03-17 13:26:21.292  1018  1388 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,03-17 13:26:21.292  1018  1388 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:21.292  1018  1388 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:21.292  1018  1388 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:21.292  1018  1388 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:21.302  1018  1388 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4884 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:21.302  4884  4884 E Zygote  : MountEmulatedStorage()
03-17 13:26:21.302  4884  4884 I libpersona: KNOX_SDCARD checking this for 10009
03-17 13:26:21.302  4884  4884 E Zygote  : v2
03-17 13:26:21.302  4884  4884 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:21.312  4884  4884 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:21.312  4884  4884 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:21.312  4884  4884 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,03-17 13:26:21.332  4884  4884 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:21.332  4884  4884 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:21.372  4397  4397 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,03-17 13:26:21.372  4397  4397 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,03-17 13:26:21.372  4397  4397 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-17 13:26:21.372  1191  1191 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-17 13:26:21.372  1191  1191 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-17 13:26:21.372  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:21.372  1018  1483 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,03-17 13:26:21.372  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:21.372  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-17 13:26:21.372  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:21.372  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:21.372  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:21.372  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:21.382  1191  1191 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-17 13:26:21.392  4900  4900 E Zygote  : MountEmulatedStorage()
03-17 13:26:21.392  4900  4900 E Zygote  : v2
03-17 13:26:21.392  4900  4900 I libpersona: KNOX_SDCARD checking this for 10145
03-17 13:26:21.392  4900  4900 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:21.392  4900  4900 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 13:26:21.392  1018  1483 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=4900 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,03-17 13:26:21.402  4900  4900 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:21.402  4900  4900 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:21.422  4900  4900 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:21.422  4900  4900 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:21.432  1018  3002 I ActivityManager: Killing 4193:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,03-17 13:26:21.442  4884  4884 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 13:26:21.452  4900  4900 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-17 13:26:21.452  4900  4900 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:21.452  4900  4900 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 13:26:21.452  4900  4900 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:21.452  4900  4900 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 13:26:21.452  4884  4884 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-17 13:26:21.452  4884  4884 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,03-17 13:26:21.462  4884  4884 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-17 13:26:21.462  1018  1483 I ActivityManager: Killing 4235:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,03-17 13:26:21.482  1018  1231 I ActivityManager: Killing 4255:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,03-17 13:26:21.502  1018  3001 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:21.522  1018  1031 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:21.552  1018  3000 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:21.562  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_4193/cgroup.procs: No such file or directory
,03-17 13:26:21.562  1018  3001 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:21.582  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_4235/cgroup.procs: No such file or directory
03-17 13:26:21.582  1018  1043 W libprocessgroup: failed to open /acct/uid_10107/pid_4255/cgroup.procs: No such file or directory
,03-17 13:26:21.622  4528  4542 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-17 13:26:21.632  1490  1490 D Launcher.Model: reloadBadges entered.
,03-17 13:26:21.632  4528  4542 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-17 13:26:21.632  4528  4542 D BadgeProvider: sendNotify, [notify] : null
03-17 13:26:21.632  4528  4542 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-17 13:26:21.632  4528  4542 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-17 13:26:21.632  4528  4542 D BadgeProvider: update, [UpdateCount] : 1
,03-17 13:26:21.652  1018  1030 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:21.652  1018  3000 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:21.662  1018  1483 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:21.662  1018  3004 D RCPManagerService: exchangeData() failure , invalid userId
,03-17 13:26:21.662  1018  3002 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-17 13:26:21.672  1018  3002 I ActivityManager: Killing 4345:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-17 13:26:21.672  1018  1018 I splitIntent: Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=18, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=24
,03-17 13:26:21.672  1018  1018 I splitIntent: finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,03-17 13:26:21.682  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,03-17 13:26:21.682  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:21.682  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:21.682  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:21.682  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:21.692  1018  1044 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4925 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 13:26:21.702  4925  4925 E Zygote  : MountEmulatedStorage()
03-17 13:26:21.702  4925  4925 E Zygote  : v2
03-17 13:26:21.702  4925  4925 I libpersona: KNOX_SDCARD checking this for 10062
03-17 13:26:21.702  4925  4925 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:21.702  4925  4925 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:21.702  4925  4925 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:21.702  4925  4925 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:21.712  4884  4884 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-17 13:26:21.712  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-17 13:26:21.712  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-17 13:26:21.712  1317  1317 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
03-17 13:26:21.712   315   315 I art     : Explicit concurrent mark sweep GC freed 8708(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 20.345ms
,03-17 13:26:21.722  1018  1388 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
03-17 13:26:21.722  1018  1388 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,03-17 13:26:21.722  1018  1388 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.722  1018  1388 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:21.722  1018  1388 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-17 13:26:21.732  1317  1317 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-17 13:26:21.732  4925  4925 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:21.732  4925  4925 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:21.732   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 19.355ms
,03-17 13:26:21.742  1317  1317 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-17 13:26:21.742  4884  4884 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,03-17 13:26:21.752  1018  1485 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
03-17 13:26:21.752  1018  1485 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,03-17 13:26:21.752  1317  1317 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
03-17 13:26:21.752  1018  1485 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.752  1018  1485 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:21.752  1018  1485 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
03-17 13:26:21.752  1317  1317 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 13:26:21.752  1317  1317 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-17 13:26:21.752  1317  1317 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-17 13:26:21.752  1317  1317 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-17 13:26:21.752  1317  1317 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
03-17 13:26:21.752  1317  1317 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 13:26:21.762   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 19.375ms
,03-17 13:26:21.762  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-17 13:26:21.762  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-17 13:26:21.762  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-17 13:26:21.772  1317  1317 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-17 13:26:21.772  4582  4582 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-17 13:26:21.772  4582  4582 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-17 13:26:21.772  4582  4582 D SecurityLogAgent: StateMachine : Current State = 1
,03-17 13:26:21.772  3703  3703 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Thu Mar 17 13:26:21 GMT+01:00 2016
03-17 13:26:21.772  1317  1317 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-17 13:26:21.772  1018  1369 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,03-17 13:26:21.772  1018  1369 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-17 13:26:21.772  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.772  1018  1369 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:21.772  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 13:26:21.782  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,03-17 13:26:21.782  1317  1317 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-17 13:26:21.782  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:21.782  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:21.782  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:21.782  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:21.782  3703  3703 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-17 13:26:21.792  3703  3703 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-17 13:26:21.792  3703  3703 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 13:26:21.792  3703  3703 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
03-17 13:26:21.792  3703  4943 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
03-17 13:26:21.792  4944  4944 E Zygote  : MountEmulatedStorage()
03-17 13:26:21.792  4944  4944 E Zygote  : v2
,03-17 13:26:21.792  4944  4944 I libpersona: KNOX_SDCARD checking this for 10157
03-17 13:26:21.792  4944  4944 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:21.802  4944  4944 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 13:26:21.802  1018  1031 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4944 uid=10157 gids={50157, 9997} abi=armeabi-v7a,
,03-17 13:26:21.802  4944  4944 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:21.802  4944  4944 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:21.802  4925  4925 I ExternalOEMControlProvider: onCreate
,03-17 13:26:21.812  3703  4943 I KLMS-2.5.183: : KLMSIntentService(): TIME_CHANGED
,03-17 13:26:21.812  4317  4317 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,03-17 13:26:21.822  3703  4943 I KLMS-2.5.183: : StateImplV2(): dateTimeChanged().START : Thu Mar 17 13:26:21 GMT+01:00 2016
,03-17 13:26:21.822  4944  4944 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:21.822  1018  1483 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
03-17 13:26:21.822  4944  4944 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:21.832  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:21.832  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:21.832  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:21.832  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:21.832  3703  4943 I KLMS-2.5.183: : StateImplV2(): dateTimeChanged().END
,03-17 13:26:21.832  1317  1317 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
03-17 13:26:21.832  1317  1317 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-17 13:26:21.842  4960  4960 E Zygote  : MountEmulatedStorage()
03-17 13:26:21.842  4960  4960 E Zygote  : v2
03-17 13:26:21.842  4960  4960 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:21.842  4960  4960 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 13:26:21.842  4960  4960 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:21.852  4960  4960 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:21.852  4960  4960 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:21.852  1018  1483 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.contextagent.ContextAgentReceiver: pid=4960 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 13:26:21.862  1018  1483 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,03-17 13:26:21.862  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:21.862  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:21.862  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:21.862  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:21.882  4973  4973 E Zygote  : MountEmulatedStorage()
,03-17 13:26:21.882  4973  4973 I libpersona: KNOX_SDCARD checking this for 10046
,03-17 13:26:21.882  4973  4973 E Zygote  : v2
,03-17 13:26:21.882  4973  4973 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:21.882  4960  4960 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 13:26:21.882  4973  4973 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 13:26:21.882  4960  4960 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:21.882  1018  1483 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=4973 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,03-17 13:26:21.882  4973  4973 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:21.882  4973  4973 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-17 13:26:21.892  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_4345/cgroup.procs: No such file or directory
,03-17 13:26:21.892  3703  3703 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-17 13:26:21.892  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-17 13:26:21.892  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,03-17 13:26:21.892  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.892  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:21.892  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:21.902  4925  4959 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,03-17 13:26:21.902  4960  4960 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:21.912  4973  4973 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:21.912  4973  4973 D ActivityThread: Added TimaKeyStore provider
03-17 13:26:21.912  4944  4944 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:21.942  1018  2999 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,03-17 13:26:21.942  1018  2999 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:21.942  1018  2999 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:21.942  1018  2999 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:21.942  1018  2999 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:21.942  4973  4973 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.,
03-17 13:26:21.942  4973  4973 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 13:26:21.942  4973  4973 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 13:26:21.942  4973  4973 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
03-17 13:26:21.942  4973  4973 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-17 13:26:21.942  4973  4973 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-17 13:26:21.952  4991  4991 E Zygote  : MountEmulatedStorage()
03-17 13:26:21.952  1018  2999 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4991 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-17 13:26:21.952  4991  4991 E Zygote  : v2
03-17 13:26:21.952  4991  4991 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:21.952  4991  4991 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-17 13:26:21.952  4991  4991 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:21.962  1018  1369 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-17 13:26:21.962  4991  4991 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 13:26:21.962  1018  1369 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
03-17 13:26:21.962  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:21.962  1018  1369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
03-17 13:26:21.962  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-17 13:26:21.962  1018  1231 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
03-17 13:26:21.962  4991  4991 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 13:26:21.962  1018  1231 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
03-17 13:26:21.962  1018  1369 I ActivityManager: Killing 4433:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
03-17 13:26:21.962   291   291 E SMD     : DCD OFF
,03-17 13:26:21.972  1018  2999 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-17 13:26:21.972  4317  4740 I SA      : [RC New] [v2liruge] api execute + 781
03-17 13:26:21.972  4317  4740 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,03-17 13:26:21.982  4317  4740 I System.out: AsyncTask #1 calls detatch()
,03-17 13:26:21.982  1018  1099 V AlarmManager: waitForAlarm result :4
03-17 13:26:21.982  1018  1231 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-17 13:26:21.982  1737  1737 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,03-17 13:26:21.982  1737  1737 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-17 13:26:21.992  1018  1388 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,03-17 13:26:21.992  4317  4740 I SA      : [ODM] saveOpenData( GEO_IP, PL )
03-17 13:26:21.992  1018  1388 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:21.992  1018  1388 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:21.992  1018  1388 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:21.992  1018  1388 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:22.002  4991  4991 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:22.002  4991  4991 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:22.012  5007  5007 E Zygote  : MountEmulatedStorage()
03-17 13:26:22.012  5007  5007 E Zygote  : v2
03-17 13:26:22.012  5007  5007 I libpersona: KNOX_SDCARD checking this for 10085
03-17 13:26:22.012  5007  5007 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:22.012  1018  1388 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=5007 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-17 13:26:22.012  5007  5007 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-17 13:26:22.012  5007  5007 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-17 13:26:22.012  4973  4973 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
03-17 13:26:22.012  5007  5007 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:22.032  5007  5007 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:22.042  5007  5007 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:22.042  1018  1369 I ActivityManager: Killing 4482:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,03-17 13:26:22.132  1018  1505 I art     : Explicit concurrent mark sweep GC freed 16999(936KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 30MB/45MB, paused 2.464ms total 143.939ms
,03-17 13:26:22.142  4317  4740 I SA      : [OCP] update openData : PL
,03-17 13:26:22.142  4317  4740 I SA      : [TPMU] getNetworkMcc : 
,03-17 13:26:22.152  1018  1043 W libprocessgroup: failed to open /acct/uid_10131/pid_4433/cgroup.procs: No such file or directory
,03-17 13:26:22.152  1018  1043 W libprocessgroup: failed to open /acct/uid_10139/pid_4482/cgroup.procs: No such file or directory
,03-17 13:26:22.152  4317  4740 I SA      : [SCU] saveMccToPreferece Start
03-17 13:26:22.152  4317  4740 I SA      : [SCU] RegionMCC : 260
03-17 13:26:22.152  4317  4740 I SA      : [SSP] query invoked
,03-17 13:26:22.162  4317  4740 I SA      : [TPMU] GetMccFromDB : null
03-17 13:26:22.162  4317  4740 I SA      : [SCU] getMccFromPreferece mcc = 260
03-17 13:26:22.162  4317  4740 I SA      : [SCU] saveMccToPreferece End
,03-17 13:26:22.162  4317  4740 I SA      : [RC New] executeRequest [v2liruge] end. 999
03-17 13:26:22.162  4317  4740 I SA      : [RC New] Execute end
03-17 13:26:22.162  4317  4317 I SA      : [OR] GetMyCountryZoneTask mcc = 260
03-17 13:26:22.162  4317  4317 I SA      : [OR] GetMyCountryZoneTask Success
,03-17 13:26:22.162  5007  5007 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-17 13:26:22.162  5007  5007 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-17 13:26:22.162  5007  5007 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-17 13:26:22.162  5007  5007 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-17 13:26:22.162  5007  5007 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 13:26:22.162  5007  5007 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,03-17 13:26:22.172  4991  4991 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458217582186
03-17 13:26:22.172  4991  4991 D         : TimeServiceNative: User Time to be set is 1458217582186
03-17 13:26:22.172  4991  4991 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-17 13:26:22.172  4991  4991 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-17 13:26:22.172  4991  4991 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458217582186
,03-17 13:26:22.172   340   423 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-17 13:26:22.172  4991  4991 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-17 13:26:22.172   340  5023 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458217582186
03-17 13:26:22.172   340  5023 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458217582186, operation = 0
03-17 13:26:22.172   340  5023 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS8/16/70 10:31:35
03-17 13:26:22.172   340  5023 D QC-time-services: Daemon:Value read from RTC seconds = 22329095000
03-17 13:26:22.172   340  5023 D QC-time-services: Daemon:new time 1458217582186 
03-17 13:26:22.172   340  5023 D QC-time-services: Daemon: delta 1435888487186 genoff 1435888487186 
03-17 13:26:22.172   340  5023 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1435888487186 to memory
03-17 13:26:22.172   340  5023 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-17 13:26:22.172   340  5023 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-17 13:26:22.202   340  5023 D QC-time-services: Updating the TOD offset
03-17 13:26:22.202   340  5023 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1435888487186 to memory
03-17 13:26:22.202   340  5023 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-17 13:26:22.202   340  5023 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-17 13:26:22.202   340  5023 E QC-time-services: Daemon:Update to modem bit set
03-17 13:26:22.202   340  5023 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-17 13:26:22.202   340  5023 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1119923687186
03-17 13:26:22.202  4991  4991 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,03-17 13:26:22.202  1018  3001 I ActivityManager: Killing 4634:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #31
,03-17 13:26:22.202  1018  3001 I ActivityManager: Killing 4565:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #32
03-17 13:26:22.212   340   418 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
03-17 13:26:22.212   340   423 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-17 13:26:22.222  1018  3002 D SettingsProvider: name = next_alarm_formatted
,03-17 13:26:22.222  1018  3002 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 13:26:22.222  1018  3002 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 13:26:22.222  1018  3002 D SettingsProvider: selectionArgs: false
03-17 13:26:22.222  1018  3002 D SettingsProvider: selectionArgs: 10085
03-17 13:26:22.222  1018  3002 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 13:26:22.222  1018  3002 D SettingsProvider: ret = -1
,03-17 13:26:22.302  4973  4973 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 105.804ms
,03-17 13:26:22.322  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_4565/cgroup.procs: No such file or directory
,03-17 13:26:22.322  1018  1043 W libprocessgroup: failed to open /acct/uid_10068/pid_4634/cgroup.procs: No such file or directory
,03-17 13:26:22.332  5007  5007 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 102.113ms
,03-17 13:26:22.362  4973  5024 D Mms/ArtClassLoader: init before art
,03-17 13:26:22.372  4973  4973 D Mms/TelephonyPermission: start operation mode monitor
,03-17 13:26:22.372  4973  4973 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 13:26:22.382  4973  4973 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
03-17 13:26:22.382  4973  4973 D Mms/TelephonyPermission: isDefault true
,03-17 13:26:22.382  4973  4973 D Mms/MmsApp: onCreate() com.android.mms
,03-17 13:26:22.422  1018  1483 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,03-17 13:26:22.432  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:22.432  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.432  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:22.432  1018  1483 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:22.432  4973  4973 D Mms/MmsApp: [start]    initCountryIso consume time = 417.375625
,03-17 13:26:22.432  1018  1031 D CountryDetector: The first listener is added
,03-17 13:26:22.442  1018  1483 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5026 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,03-17 13:26:22.442  5026  5026 E Zygote  : MountEmulatedStorage()
03-17 13:26:22.442  5026  5026 E Zygote  : v2
03-17 13:26:22.442  5026  5026 I libpersona: KNOX_SDCARD checking this for 10094
03-17 13:26:22.442  5026  5026 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:22.442  5026  5026 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:22.452  5026  5026 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-17 13:26:22.452  1018  1483 I ActivityManager: Killing 4649:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31,
03-17 13:26:22.452  5026  5026 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:22.462  4973  4973 D Mms/MmsApp: [end]    initCountryIso consume time = 26.171562
03-17 13:26:22.462  4973  4973 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.133958
,03-17 13:26:22.462  4973  4973 D Mms/MmsConfig: before partial update
,03-17 13:26:22.472  5026  5026 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:22.472  5026  5026 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:22.482  4973  4973 D Mms/MmsConfig: Load Resize quality : 80
,03-17 13:26:22.482  4973  4973 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,03-17 13:26:22.482  4973  4973 D EasySignUpManager_1.0.1: isAuth is false
,03-17 13:26:22.482  4973  4973 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,03-17 13:26:22.492  1467  1722 D TP/MmsSmsProvider: query,matched:2117, calling pid = 4973
,03-17 13:26:22.492  1467  1722 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.615 ms
,03-17 13:26:22.492  4973  4973 D EasySignUpManager_1.0.1: isAuth is false
03-17 13:26:22.492  4973  4973 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,03-17 13:26:22.502  4973  4973 E CscParser: mps_code.dat does not exist
03-17 13:26:22.502  4973  4973 E CscParser: customer_path =/system/csc/customer.xml
03-17 13:26:22.502  4973  4973 E CscParser: fileName + /system/csc/customer.xml
,03-17 13:26:22.502  5026  5026 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,03-17 13:26:22.502  5026  5026 D elm:15183: ELMEngine.ELMEngine( context ).
,03-17 13:26:22.512  5026  5026 D elm:15183: MDMBridge.setEnterpriseBridge()
,03-17 13:26:22.512  4973  4973 E CscParser: mps_code.dat does not exist
,03-17 13:26:22.512  4973  4973 E CscParser: customer_path =/system/csc/customer.xml
03-17 13:26:22.512  4973  4973 E CscParser: fileName + /system/csc/customer.xml
,03-17 13:26:22.512  1018  1483 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
03-17 13:26:22.512  1018  1483 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,03-17 13:26:22.512  1018  1483 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:22.512  1018  1483 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 13:26:22.512  1018  1483 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-17 13:26:22.512  5026  5026 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,03-17 13:26:22.522  1018  3004 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,03-17 13:26:22.522  5026  5026 D elm:15183: ElmAgentService : onCreate()
,03-17 13:26:22.522  5026  5043 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,03-17 13:26:22.522  1018  3004 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.522  4973  4973 D CscParser: getInstance fileName =/system/csc/customer.xml
,03-17 13:26:22.522  1018  3004 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.522  1018  3004 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.522  1018  3004 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.522  4973  4973 D Mms/MmsConfig:  enable multiwindow = true
,03-17 13:26:22.522  5026  5043 D elm:15183: ELMAgentService.listeningToTimeDateChanges( context, intent ).
,03-17 13:26:22.522  5026  5026 D elm:15183: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,03-17 13:26:22.522  5026  5026 D elm:15183: ModuleBase.ModifySetAlarm()
,03-17 13:26:22.522  5026  5026 D elm:15183: MDMBridge.getInstance()
03-17 13:26:22.522  5026  5026 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,03-17 13:26:22.532  5045  5045 E Zygote  : MountEmulatedStorage()
03-17 13:26:22.532  5045  5045 I libpersona: KNOX_SDCARD checking this for 10134
03-17 13:26:22.532  5045  5045 E Zygote  : v2
03-17 13:26:22.532  5045  5045 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:22.532  5045  5045 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:22.532  5045  5045 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:22.542  4973  4973 E Mms/MessageUtils: setCountryDetector : update country detector info 
03-17 13:26:22.542  4973  4973 E Mms/MessageUtils: updateCountryIso : update country iso info 
,03-17 13:26:22.542  5045  5045 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,03-17 13:26:22.542  1018  3004 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=5045 uid=10134 gids={50134, 9997} abi=armeabi-v7a
,03-17 13:26:22.542  5026  5026 D elm:15183: ElmAgentService : onDestroy().
,03-17 13:26:22.552  4973  4973 D Mms/MmsConfig: [end]    init() consume time = 91.370469
,03-17 13:26:22.552  4973  4973 D Mms/Contact: [start]    init() consume time = 0.989792
,03-17 13:26:22.552  1018  1031 I ActivityManager: Killing 4669:com.sec.pcw.device/1000 (adj 15): empty #31
,03-17 13:26:22.562  5045  5045 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:22.562  5045  5045 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:22.582  1467  1813 D TP/MmsSmsProvider: query,matched:13, calling pid = 4973
,03-17 13:26:22.582  1467  1813 D TP/MmsSmsProvider: match 13:Elapsed time : 1.127 ms
03-17 13:26:22.582  5045  5045 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-17 13:26:22.582  4973  4973 D Mms/Contact: [end]    init consume time = 30.189375
03-17 13:26:22.582  5045  5045 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,03-17 13:26:22.582  1018  1043 W libprocessgroup: failed to open /acct/uid_10069/pid_4649/cgroup.procs: No such file or directory
,03-17 13:26:22.582  4973  5062 D Mms/DraftCache: [start]    rebuildCache consume time = 4.209635
,03-17 13:26:22.592  1467  1477 D TP/MmsSmsProvider: query,matched:12, calling pid = 4973
,03-17 13:26:22.592  1467  1477 D TP/MmsSmsProvider: match 12:Elapsed time : 1.899 ms
,03-17 13:26:22.592  4973  4973 D Mms/MethodReflector: getSubId is called
03-17 13:26:22.592  4973  4973 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-17 13:26:22.602  4973  4973 D Mms/MethodReflector: getTelephonyProperty is called
03-17 13:26:22.602  4973  4973 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-17 13:26:22.602  4973  4973 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-17 13:26:22.602  4973  4973 D Mms/DownloadManager: auto download without roaming -> true
03-17 13:26:22.602  4973  4973 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,03-17 13:26:22.602  4973  4973 D Mms/MethodReflector: getSubId is called
,03-17 13:26:22.602  4973  4973 D Mms/MethodReflector: getDefaultSmsSubId is called
03-17 13:26:22.602  4973  4973 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
03-17 13:26:22.602  4973  4973 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
03-17 13:26:22.602  4973  4973 D Mms/MethodReflector: getTelephonyProperty is called
03-17 13:26:22.602  4973  4973 D Mms/DownloadManager: roaming -> false (slotId = 1)
03-17 13:26:22.602  4973  4973 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
03-17 13:26:22.602  4973  4973 D Mms/DownloadManager: auto download without roaming -> true
03-17 13:26:22.602  4973  4973 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
03-17 13:26:22.602  4973  4973 D Mms/DownloadManager: auto download during roaming secondary -> false
03-17 13:26:22.602  4973  4973 D Mms/DownloadManager: mAutoDownload ------> true
,03-17 13:26:22.602  4973  5062 D Mms/DraftCache: [end]    rebuildCache consume time = 18.120729
,03-17 13:26:22.612  1018  1505 I ActivityManager: Killing 4053:com.samsung.android.app.galaxyfinder:tagService/u0a32 (adj 15): empty #31
,03-17 13:26:22.642  1018  1388 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,03-17 13:26:22.642  1018  1388 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,03-17 13:26:22.642  1018  1388 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:22.642  1018  1388 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,03-17 13:26:22.642  1018  1388 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,03-17 13:26:22.642  4973  4973 D ComposerPerformance: 1458217582655 ms / [DONE] Composer constructor
,03-17 13:26:22.642  4973  4973 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,03-17 13:26:22.642  4973  4973 I Mms/ReservationManager: ReservationManager()
03-17 13:26:22.642  4973  4973 I Mms/ReservationManager: resetAfterConnected()
,03-17 13:26:22.652  1467  1813 D TP/MmsSmsProvider: query,matched:7, calling pid = 4973
,03-17 13:26:22.652  1467  1813 D TP/MmsSmsProvider: match 7:Elapsed time : 2.296 ms
,03-17 13:26:22.652  4973  5064 D Mms/Conversation: [start]    init() consume time = 50.127605
,03-17 13:26:22.652  4973  4973 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,03-17 13:26:22.652  1467  1481 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,03-17 13:26:22.662  1467  1481 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
03-17 13:26:22.662  1467  1481 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,03-17 13:26:22.662  4973  4973 D Mms/MmsApp: [end]    onCreate() consume time = 6.470625
,03-17 13:26:22.662  1467  1481 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,03-17 13:26:22.662  1467  1481 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 13:26:22.662  1467  1481 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 13:26:22.662  1467  1481 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 13:26:22.662  1467  1481 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 13:26:22.662  1467  1481 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-17 13:26:22.662  1467  1481 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-17 13:26:22.672  4973  4973 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
03-17 13:26:22.672  1018  3001 I splitIntent: Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
,03-17 13:26:22.672  4973  4973 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,03-17 13:26:22.672  4973  4973 D Mms/MethodReflector: getSubId is called
03-17 13:26:22.672  4973  4973 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-17 13:26:22.672  4973  4973 D Mms/MethodReflector: getTelephonyProperty is called
,03-17 13:26:22.672  4973  4973 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-17 13:26:22.672  4973  4973 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-17 13:26:22.672  4973  4973 D Mms/DownloadManager: auto download without roaming -> true
03-17 13:26:22.672  4973  4973 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
03-17 13:26:22.672  4973  4973 D Mms/DownloadManager: mAutoDownload ------> true
,03-17 13:26:22.672  1018  3001 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:22.672  1018  3001 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:22.672  1018  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-17 13:26:22.672  1467  1481 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
03-17 13:26:22.672  1467  1481 D TP/MmsSmsProvider: need read changed broadcast:false
,03-17 13:26:22.682  4973  5064 D Mms/Conversation: [end]    init consume time = 18.241822
03-17 13:26:22.682  4973  5064 D Mms/MessagingNotification: [start]    init() consume time = 0.119896
,03-17 13:26:22.682  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_4669/cgroup.procs: No such file or directory
,03-17 13:26:22.682  1018  1231 I ActivityManager: Killing 4171:com.sec.android.soagent/u0a34 (adj 15): empty #31
,03-17 13:26:22.682  1018  1031 D ActivityManager: startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
,03-17 13:26:22.692  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
03-17 13:26:22.692  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:22.692  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:22.692  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-17 13:26:22.692  4973  5064 D Mms/MessagingNotification: [end]    init consume time = 13.452292
,03-17 13:26:22.692  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:22.692  1018  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:22.692  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:22.702  4973  5067 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 1.268125
,03-17 13:26:22.702  4973  5068 D Mms/Synchronizer: [start]    doSync consume time = 8.475469
,03-17 13:26:22.702  1467  1722 D TP/MmsSmsProvider: query,matched:0, calling pid = 4973
,03-17 13:26:22.702  1467  1722 V TP/MmsSmsProvider: getSimpleConversations entered.
03-17 13:26:22.702  1467  1477 D TP/MmsSmsProvider: query,matched:400, calling pid = 4973
03-17 13:26:22.702  1467  1722 D TP/MmsSmsProvider: match 0:Elapsed time : 0.933 ms
,03-17 13:26:22.712  1467  1813 D TP/MmsSmsProvider: update, matched:300, calling pid = 4973
,03-17 13:26:22.712  1467  1813 V TP/MmsSmsProvider: syncDBData start
,03-17 13:26:22.712  1467  1813 V TP/MmsSmsProvider: syncDBData sms end
03-17 13:26:22.712  1467  1813 V TP/MmsSmsProvider: syncDBData mms end
,03-17 13:26:22.712  1467  1813 V TP/MmsSmsProvider: syncDBData end,
03-17 13:26:22.712  4973  5067 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 12.04125
,03-17 13:26:22.712  4973  5068 D Mms/Synchronizer: [end]    doSync consume time = 0.640625
,03-17 13:26:22.712  4973  5024 D Mms/ArtClassLoader: init [DONE] art
,03-17 13:26:22.722  1018  3000 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,03-17 13:26:22.722  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:22.722  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:22.722  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.722  1018  3000 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:22.732  5070  5070 E Zygote  : MountEmulatedStorage()
03-17 13:26:22.732  5070  5070 I libpersona: KNOX_SDCARD checking this for 1000
03-17 13:26:22.732  5070  5070 E Zygote  : v2
03-17 13:26:22.732  5070  5070 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:22.732  1018  3000 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5070 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-17 13:26:22.742  5070  5070 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:22.742  5070  5070 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:22.742  5070  5070 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:22.742  4973  5064 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,03-17 13:26:22.752  1467  1477 D TP/SmsProvider: query,matched:26, calling pid = 4973,
,03-17 13:26:22.752  1467  1477 D TP/SmsProvider: match 26:Elapsed time : 2.644 ms
,03-17 13:26:22.762  1467  1481 D TP/MmsSmsProvider: query,matched:6, calling pid = 4973
,03-17 13:26:22.762  1467  1481 D TP/MmsSmsProvider: match 6:Elapsed time : 1.463 ms
,03-17 13:26:22.772  5070  5070 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:22.772  5070  5070 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:22.792  1018  1485 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,03-17 13:26:22.792  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:22.792  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.802  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:22.802  1018  1485 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.802  5070  5070 E MTPRx   : In MtpReceiverandroid.hardware.usb.action.USB_STATE
,03-17 13:26:22.802  1018  1043 W libprocessgroup: failed to open /acct/uid_10032/pid_4053/cgroup.procs: No such file or directory
03-17 13:26:22.802  1018  1043 W libprocessgroup: failed to open /acct/uid_10034/pid_4171/cgroup.procs: No such file or directory
,03-17 13:26:22.812  1018  1485 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5085 uid=10025 gids={50025, 9997} abi=armeabi-v7a
03-17 13:26:22.812  1018  3004 D SecContentProvider2: uri = 14 selection = getSealedState
03-17 13:26:22.812  1018  3004 D SecContentProvider2: mCursor = null
,03-17 13:26:22.812  1018  1031 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-17 13:26:22.812  1018  1031 D SecContentProvider2: mCursor = null
,03-17 13:26:22.812  5085  5085 E Zygote  : MountEmulatedStorage()
,03-17 13:26:22.812  5070  5070 V MTPRx   : sealedState: false
03-17 13:26:22.812  5070  5070 V MTPRx   : sealedUsbMassStorageState: false
03-17 13:26:22.812  5070  5070 E MTPRx   : check value of boot_completed is1
03-17 13:26:22.812  5070  5070 E MTPRx   : check booting is completed_sys.boot_completed
,03-17 13:26:22.822  5085  5085 I libpersona: KNOX_SDCARD checking this for 10025
03-17 13:26:22.822  5085  5085 E Zygote  : v2
03-17 13:26:22.822  5085  5085 I libpersona: KNOX_SDCARD not a persona
03-17 13:26:22.822  5085  5085 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:22.822  5070  5070 E MTPRx   : Sd-Card path/storage/extSdCard
03-17 13:26:22.822  5070  5070 E MTPRx   : Status for mount/Unmount :removed
03-17 13:26:22.822  5070  5070 E MTPRx   : SDcard is not available
,03-17 13:26:22.822  5070  5070 W MTPRx   : value of connected istrue
03-17 13:26:22.822  5085  5085 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-17 13:26:22.822  5070  5070 W MTPRx   : value of configured istrue
03-17 13:26:22.822  5070  5070 W MTPRx   : value of mtpEnabled istrue
,03-17 13:26:22.822  5070  5070 W MTPRx   : value of ptpEnabled isfalse
03-17 13:26:22.822  5085  5085 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:22.822  5070  5070 E MTPRx   : Received USB_STATE with sdCardLaunch = 0
,03-17 13:26:22.822  5070  5070 E MTPRx   : mFirstTime: false
,03-17 13:26:22.832  5070  5070 D         : MTP: reading debug level property
,03-17 13:26:22.832  5070  5070 E MTPJNIInterface: Getting CryptionKey from JAVA
,03-17 13:26:22.832  5070  5070 E MTPRx   : currentUserId is 0
,03-17 13:26:22.842  5085  5085 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:22.842  5085  5085 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:22.842  5070  5070 E MTPRx   : Start observing USB_STATE_MATCH 
,03-17 13:26:22.842  5070  5070 E MTPRx   : cannot open file : /sys/class/android_usb/android0/bcdUSB
03-17 13:26:22.842  5070  5070 E MTPRx   : is_Privatemode is NOT 1
,03-17 13:26:22.852  1018  1030 D SettingsProvider: name = boot_time_connected
,03-17 13:26:22.852  5070  5070 E MTPRx   : Sending NORMAL_BOOT to stack
03-17 13:26:22.852  1018  1152 I ActivityManager: Killing 4702:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
03-17 13:26:22.852  5070  5070 E MTPJNIInterface: noti = 17
,03-17 13:26:22.852  1018  3000 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 13:26:22.862  1018  1483 D SecContentProvider: uri = 18 selection = isUsbMediaPlayerAvailable,
03-17 13:26:22.862  5070  5070 E MTPRx   : sending MTP_ICON_ENABLED to stack
03-17 13:26:22.862  1018  1152 D ActivityManager: startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
03-17 13:26:22.862  1018  1152 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:22.862  1018  1152 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0,
,03-17 13:26:22.862  1018  1152 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:22.862  1018  1152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-17 13:26:22.862  1018  2999 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1018) eventTime = 53626
03-17 13:26:22.862  1018  2999 D PowerManagerService: [s] UserActivityState : 2 -> 1
03-17 13:26:22.862  1018  2999 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018 (0x0)
03-17 13:26:22.862  1018  2999 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1018, ws=WorkSource{10054}) (elapsedTime=3484)
03-17 13:26:22.862  1018  1031 D SettingsProvider: name = mtp_running_status
,03-17 13:26:22.872  5085  5085 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-17 13:26:22.872  1018  1030 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 13:26:22.872  5070  5070 E MTPRx   : else part ... so first time!!!
,03-17 13:26:22.872  5070  5070 E MTPPlaObsrvr: inside setContext()
03-17 13:26:22.872  5070  5070 E MTPPlaObsrvr:  inside createplafiles
,03-17 13:26:22.882  1191  1191 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-17 13:26:22.882  1018  1018 I ValidateNoPeople: mEvictionCount: 0
,03-17 13:26:22.882  4973  4973 D Mms/Contact: sContactsObserver.onChange(),selfUpdate=false
,03-17 13:26:22.892  5070  5070 E MTPPlaObsrvr: playlist count is0
,03-17 13:26:22.892  4973  4973 D Mms/Contact: performUpdate:widgetCount=0
,03-17 13:26:22.892  5070  5070 E MTPPlaObsrvr:  inside try branch createplafiles
,03-17 13:26:22.892  5070  5070 E MTPPlaObsrvr:  inside deleteing plas createplafiles
,03-17 13:26:22.892  5070  5070 E MTPPlaObsrvr: Inside registerContentObserver
,03-17 13:26:22.892  4973  5102 D Mms/ContactsCache: [start]    invalidate() consume time = 182.787812
,03-17 13:26:22.902  5070  5070 E MtpAdbObserver: inside setContext()
03-17 13:26:22.902  5070  5070 E MtpAdbObserver: Inside registerContentObserver
03-17 13:26:22.902  5070  5070 W Settings: Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,03-17 13:26:22.902  1018  2734 D ActivityManager: startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
03-17 13:26:22.902  5085  5085 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
03-17 13:26:22.902  1018  2734 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
03-17 13:26:22.902  1018  2734 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:22.902  1018  2734 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:22.902  1018  2734 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-17 13:26:22.902  1018  1231 D SettingsProvider: name = mtp_running_status
,03-17 13:26:22.902  4973  5102 D Mms/ContactsCache: [end]    invalidate() consume time = 9.075781
,03-17 13:26:22.902  1018  1505 D SettingsProvider: name = mtp_usb_conditions_met
,03-17 13:26:22.912  5070  5103 V MtpMediaDBManager: inside deleteAllDB
,03-17 13:26:22.912  5070  5070 E MtpService: onCreate.
,03-17 13:26:22.912  1018  1043 W libprocessgroup: failed to open /acct/uid_10159/pid_4702/cgroup.procs: No such file or directory
,03-17 13:26:22.912  1018  3000 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
03-17 13:26:22.912  1018  3000 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,03-17 13:26:22.912  1018  3000 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:22.912  1018  3000 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 13:26:22.912  1018  3000 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-17 13:26:22.922  1240  1240 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,03-17 13:26:22.922  5070  5070 E MtpService: < MTP > Registering BroadCast receiver :::::
,03-17 13:26:22.932  1018  3001 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:22.932  4973  5064 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,03-17 13:26:22.932  1018  3001 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 13:26:22.932  1018  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,03-17 13:26:22.932  5070  5070 E MtpService: < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,03-17 13:26:22.942  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:22.942  1018  1369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-17 13:26:22.942  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,03-17 13:26:22.952  5070  5070 E MtpService: < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::,
03-17 13:26:22.952  5085  5085 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,03-17 13:26:22.952  1018  1369 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:22.952  1018  1369 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-17 13:26:22.952  1018  1369 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
03-17 13:26:22.952  5085  5085 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,03-17 13:26:22.952  5085  5085 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,03-17 13:26:22.952  5085  5085 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
03-17 13:26:22.952  1843  1843 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,03-17 13:26:22.952  5085  5085 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,03-17 13:26:22.952  5070  5070 E MtpService: onStartCommand.
03-17 13:26:22.952  5070  5070 W MTPRx   : calling native method
03-17 13:26:22.952  5070  5070 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::
,03-17 13:26:22.962  5085  5085 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
03-17 13:26:22.962  5070  5104 E MtpService: handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,03-17 13:26:22.962  5070  5103 V MtpMediaDBManager: inside Thread updateDB
,03-17 13:26:22.962  5085  5085 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,03-17 13:26:22.962  1018  3000 W ActivityManager: userId = 0, bbcId = -10000
03-17 13:26:22.962  1018  3000 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-17 13:26:22.962  1018  3000 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,03-17 13:26:22.962  5085  5085 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,03-17 13:26:22.962  5085  5085 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,03-17 13:26:22.962  5085  5085 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,03-17 13:26:22.962  5085  5085 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,03-17 13:26:22.962  5085  5085 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,03-17 13:26:22.962  1018  1231 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-17 13:26:22.972  5085  5085 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,03-17 13:26:22.972  1018  1231 W ActivityManager: userId = 0, bbcId = -10000
,03-17 13:26:22.972  1018  1231 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-17 13:26:22.972  1018  1231 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-17 13:26:22.972  5070  5070 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::::
,03-17 13:26:22.972  5070  5103 E MtpMediaDBManager: count : 27
,03-17 13:26:22.982  5070  5070 E MTPJNIInterface: noti = 10
03-17 13:26:22.982  5070  5070 W MTPRx   : calling native method
03-17 13:26:22.982  5070  5070 E MTPRx   : Checking the driver time out
03-17 13:26:22.982  5070  5070 E MTPJNIInterface: noti = 2
03-17 13:26:22.982  5070  5070 D         : deleting sockets before message queue initialization
,03-17 13:26:22.982  1367  1367 D BluetoothNotiBroadcastReceiver: onReceive
,03-17 13:26:22.982  5070  5070 D         : event handler thread is created, so set the flag
,03-17 13:26:22.992  5070  5070 E MTPRx   : called native method
03-17 13:26:22.992  5070  5070 E MTPJNIInterface: setting Media scanner status0
03-17 13:26:22.992  5070  5070 E MTPJNIInterface: After setting Media scanner status0
03-17 13:26:22.992  5070  5070 E MtpService: onStartCommand.
,03-17 13:26:22.992  5070  5070 W MTPRx   : notification from stack 1
,03-17 13:26:22.992  1191  1191 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
03-17 13:26:22.992  1191  1191 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,03-17 13:26:22.992  5070  5104 E MtpService: handleMessage. msg= { when=-2ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
03-17 13:26:22.992  1018  3001 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast,
03-17 13:26:22.992  5070  5106 E         : Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
03-17 13:26:22.992  5070  5106 E MTPJNIInterface: Getting media scanner status0
,03-17 13:26:22.992  1018  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 13:26:22.992  5070  5106 E MTPJNIInterface: DeviceName is A5-1
03-17 13:26:22.992  1018  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 13:26:22.992  1018  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 13:26:22.992  1018  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 13:26:23.012  5107  5107 E Zygote  : MountEmulatedStorage(),
03-17 13:26:23.012  5107  5107 I libpersona: KNOX_SDCARD checking this for 10003
03-17 13:26:23.012  5107  5107 E Zygote  : v2
03-17 13:26:23.012  5107  5107 I libpersona: KNOX_SDCARD not a persona
,03-17 13:26:23.012  5107  5107 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-17 13:26:23.012  5107  5107 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-17 13:26:23.012  1018  3001 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5107 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
03-17 13:26:23.012  5107  5107 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 13:26:23.032   331   331 I ServiceManager: Waiting for service AtCmdFwd...
,03-17 13:26:23.032  5107  5107 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 13:26:23.032  5107  5107 D ActivityThread: Added TimaKeyStore provider
,03-17 13:26:23.042  5070  5103 W MtpMediaDBManager: sending db update complete noti to stack
03-17 13:26:23.042  5070  5103 E MTPJNIInterface: noti = 29
,03-17 13:26:23.052  5070  5106 E MTPJNIInterface: Status for mount/Unmount :removed
,03-17 13:26:23.052  5070  5106 E MTPJNIInterface: SDcard is not available
,03-17 13:26:23.062  5107  5107 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-17 13:26:23.072  5070  5106 E         : lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,03-17 13:26:23.072  5070  5106 E         : [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,03-17 13:26:23.092  5070  5106 E MTPJNIInterface: Status for mount/Unmount :removed
03-17 13:26:23.092  5070  5106 E MTPJNIInterface: SDcard is not available
,03-17 13:26:23.092  5070  5106 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 13:26:23.092  5070  5106 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
03-17 13:26:23.092  5070  5106 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 13:26:23.092  5070  5106 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-17 13:26:23.092  5070  5106 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 13:26:23.092  5070  5106 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-17 13:26:23.092  5070  5106 E SQLiteLog: (21) API call with NULL database connection pointer
03-17 13:26:23.092  5070  5106 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
03-17 13:26:23.092  5070  5070 W MTPRx   : notification from stack 2
,03-17 13:26:23.092  5070  5124 D         : [mtp_init_device] Library open with 32 bits.
03-17 13:26:23.092  5070  5124 D         : [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,03-17 13:26:23.092  5070  5124 E         : [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
03-17 13:26:23.092  5070  5124 D         : [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
03-17 13:26:23.092  5070  5124 E         :  [sua_support_present:1287] returning false 
03-17 13:26:23.092  5070  5124 D         : [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,03-17 13:26:23.102  5107  5107 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-17 13:26:23.102  5107  5107 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-17 13:26:23.102  5107  5107 D UserAnalysis: Create SecureDbHelper

```
