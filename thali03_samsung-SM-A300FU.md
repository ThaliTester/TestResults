#### Test 82914073b4ce5c2_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
09-13 15:12:33.724  6994  6994 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 15:12:33.724  6994  6994 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 15:12:33.734  6994  6994 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
--------- beginning of system
09-13 15:12:33.734  1016  1221 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.smishing.PackageInstallReceiver: pid=6994 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
09-13 15:12:33.734  1016  1221 I ActivityManager: Killing 6576:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
09-13 15:12:33.734  1016  1221 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
09-13 15:12:33.744  6800  6847 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
09-13 15:12:33.744  6800  6847 I AcmsCertificateMngr: getKeyStoreForApplication success 
09-13 15:12:33.744  6800  6847 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
09-13 15:12:33.744  6800  6847 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 15:12:33.744  6800  6847 D AcmsServiceMonitor: Decrementing - Counter value: 1
09-13 15:12:33.744  6800  6847 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
09-13 15:12:33.744  6800  6847 D AcmsCore: This is NOT a valid MirrorLink app
09-13 15:12:33.744  6800  6847 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
09-13 15:12:33.744  6800  6847 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-13 15:12:33.744  6800  6847 D AcmsServiceMonitor: Decrementing - Counter value: 0
09-13 15:12:33.744  6800  6847 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
09-13 15:12:33.744  1016  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:33.744  1016  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:33.744  1016  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:33.744  1016  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:33.754  3828  6855 I qtaguid : Tagging socket 101 with tag 1000040b00000000{268436491,0} for uid -1, pid: 3828, getuid(): 10011
09-13 15:12:33.754  6994  6994 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 15:12:33.764  6994  6994 D ActivityThread: Added TimaKeyStore provider
09-13 15:12:33.764  7010  7010 E Zygote  : MountEmulatedStorage()
09-13 15:12:33.764  7010  7010 E Zygote  : v2
09-13 15:12:33.764  7010  7010 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 15:12:33.764  7010  7010 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 15:12:33.764  7010  7010 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 15:12:33.764  7010  7010 I libpersona: KNOX_SDCARD checking this for 10148
09-13 15:12:33.764  7010  7010 I libpersona: KNOX_SDCARD not a persona
09-13 15:12:33.764  1016  1221 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7010 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
09-13 15:12:33.774  6800  6800 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
09-13 15:12:33.774  6800  6800 D AcmsService: Enter onDestroy
09-13 15:12:33.774  6800  6800 I AcmsService: cleanUp(): inside service clean up
09-13 15:12:33.774  6800  6800 D AcmsCore: AcmsCore: inside DeInit
09-13 15:12:33.774  6800  6800 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
09-13 15:12:33.774  6800  6800 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
09-13 15:12:33.774  6800  6800 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
09-13 15:12:33.774  6800  6800 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
09-13 15:12:33.774  6800  6800 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
09-13 15:12:33.774  6800  6800 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
09-13 15:12:33.774  6800  6800 D AcmsService: killing acms process
09-13 15:12:33.774  6800  6800 I Process : Sending signal. PID: 6800 SIG: 9
09-13 15:12:33.774  1016  1221 I ActivityManager: Killing 6591:com.wsomacp/u0a23 (adj 15): empty #21
09-13 15:12:33.804  7010  7010 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 15:12:33.804  7010  7010 D ActivityThread: Added TimaKeyStore provider
09-13 15:12:33.804  6955  6955 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
09-13 15:12:33.814  3828  6859 W BaseAppContext: Using Auth Proxy for data requests.
,09-13 15:12:33.814  1016  1463 I ActivityManager: Process ACMS.Process (pid 6800)(adj 0) has died(92,738)
09-13 15:12:33.814  6994  6994 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
09-13 15:12:33.814  6994  6994 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 15:12:33.814  6994  6994 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 15:12:33.814  6994  6994 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-13 15:12:33.814  6994  6994 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
09-13 15:12:33.814  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 15:12:33.824  1016  1028 D PowerManagerService: [api] handleWakeLockDeath : release WakeLock : PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10081, pid=6576, ws=null) (elapsedTime=2832)
09-13 15:12:33.854  6994  6994 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
09-13 15:12:33.874  7010  7010 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
09-13 15:12:33.884  1016  1489 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
09-13 15:12:33.884  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:33.884  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:33.884  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:33.884  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:33.904  7034  7034 E Zygote  : MountEmulatedStorage()
09-13 15:12:33.904  7034  7034 I libpersona: KNOX_SDCARD checking this for 1000
09-13 15:12:33.904  7034  7034 E Zygote  : v2
09-13 15:12:33.904  7034  7034 I libpersona: KNOX_SDCARD not a persona
09-13 15:12:33.904  7034  7034 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 15:12:33.904  7034  7034 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 15:12:33.904  1016  1489 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=7034 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-13 15:12:33.904  7034  7034 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 15:12:33.904  1016  1489 I ActivityManager: Killing 6606:com.sec.esdk.elm/u0a90 (adj 15): empty #21
09-13 15:12:33.924  7034  7034 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 15:12:33.924  7034  7034 D ActivityThread: Added TimaKeyStore provider
09-13 15:12:33.944  7034  7034 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
09-13 15:12:33.964  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 15:12:33.964  1016  1029 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4191, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 15:12:33.964  1016  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 15:12:33.964  1016  1029 D BatteryService: stay LED for charging
09-13 15:12:33.964  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-13 15:12:33.964  1016  1016 I MotionRecognitionService: Plugged
09-13 15:12:33.964  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
09-13 15:12:33.964  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-13 15:12:33.964  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 15:12:33.974  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-13 15:12:33.974  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
09-13 15:12:33.984  3238  3238 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 15:12:33.984  3238  3377 D HeadsetStateMachine: Disconnected process message: 10
09-13 15:12:33.994  3828  6859 W art     : Verification of boolean com.google.android.gms.games.broker.AchievementAgent.flushPendingOp(android.content.Context, com.google.android.gms.common.internal.ClientContext, com.google.android.gms.games.broker.AchievementAgent$AchievementFlushData) took 164.410ms
09-13 15:12:34.004  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-13 15:12:34.004  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-13 15:12:34.004  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-13 15:12:34.024  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 15:12:34.034  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 15:12:34.034  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 15:12:34.034  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 15:12:34.054  1016  1028 E EdmStorageProvider: Admin not in database, something went wrong
09-13 15:12:34.064  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 15:12:34.064  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 15:12:34.064  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 15:12:34.064  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 15:12:34.074  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 15:12:34.074  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 15:12:34.074  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 15:12:34.084  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 15:12:34.084  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 15:12:34.084  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 15:12:34.084  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 15:12:34.094  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 15:12:34.094  6955  6955 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
09-13 15:12:34.094  7032  7032 D AndroidRuntime: 
09-13 15:12:34.094  7032  7032 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-13 15:12:34.094  7032  7032 D AndroidRuntime: CheckJNI is OFF
09-13 15:12:34.094  7032  7032 D AndroidRuntime: readGMSProperty: start
09-13 15:12:34.094  7032  7032 D AndroidRuntime: readGMSProperty: already setted!!
09-13 15:12:34.094  7032  7032 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-13 15:12:34.094  7032  7032 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-13 15:12:34.094  7032  7032 D AndroidRuntime: readGMSProperty: end
09-13 15:12:34.094  7032  7032 D AndroidRuntime: addProductProperty: start
09-13 15:12:34.114  1016  1479 I art     : Explicit concurrent mark sweep GC freed 22266(1286KB) AllocSpace objects, 1(22KB) LOS objects, 33% free, 23MB/34MB, paused 2.616ms total 155.387ms
09-13 15:12:34.114  1016  1479 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-13 15:12:34.124  6955  6955 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-13 15:12:34.124  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:34.124  1016  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 15:12:34.124  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
09-13 15:12:34.134  1016  1847 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
09-13 15:12:34.134  1016  1847 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:34.134  1016  1847 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:34.134  1016  1847 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:34.134  6994  6994 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 238.477ms
09-13 15:12:34.134  1016  1847 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:34.134  6955  6955 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-13 15:12:34.154  7061  7061 E Zygote  : MountEmulatedStorage()
09-13 15:12:34.154  7061  7061 I libpersona: KNOX_SDCARD checking this for 10152
09-13 15:12:34.154  7061  7061 E Zygote  : v2
09-13 15:12:34.154  7061  7061 I libpersona: KNOX_SDCARD not a persona
09-13 15:12:34.154  7061  7061 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 15:12:34.154  7061  7061 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 15:12:34.154  1016  1847 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7061 uid=10152 gids={50152, 9997} abi=armeabi-v7a
09-13 15:12:34.154  7061  7061 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 15:12:34.154  1016  1847 I ActivityManager: Killing 6352:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
09-13 15:12:34.154  1016  1474 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 15:12:34.154  1016  1474 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-13 15:12:34.164  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:34.164  1016  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 15:12:34.164  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-13 15:12:34.224  7061  7061 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 15:12:34.224  1016  1463 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-13 15:12:34.224  1016  1463 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:34.224  1016  1463 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 15:12:34.224  1016  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-13 15:12:34.224  7061  7061 D ActivityThread: Added TimaKeyStore provider
09-13 15:12:34.234  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 15:12:34.244  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
09-13 15:12:34.244  6955  6955 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
09-13 15:12:34.254  7061  7061 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
09-13 15:12:34.254  7061  7061 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
09-13 15:12:34.264  1016  1850 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 15:12:34.264  1016  1850 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-13 15:12:34.264  1016  1850 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:34.264  1016  1850 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 15:12:34.264  1016  1850 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-13 15:12:34.274  7061  7061 I TapandpayWidget:Utils: Clear T&P info.
09-13 15:12:34.284  7061  7061 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
09-13 15:12:34.284  6994  6994 W art     : Verification of com.sec.android.touchwiz.animator.TwDndHorizontalListAnimator com.android.mms.ArtClassLoader.createTwDndHorizontalListAnimator(android.content.Context) took 152.499ms
09-13 15:12:34.294  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
09-13 15:12:34.294  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:34.294  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:34.294  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:34.294  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:34.304  7084  7084 E Zygote  : MountEmulatedStorage()
09-13 15:12:34.304  7084  7084 I libpersona: KNOX_SDCARD checking this for 10009
09-13 15:12:34.304  7084  7084 E Zygote  : v2
09-13 15:12:34.304  7084  7084 I libpersona: KNOX_SDCARD not a persona
09-13 15:12:34.314  7032  7032 E AffinityControl: AffinityControl: registerfunction enter
09-13 15:12:34.314  7084  7084 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 15:12:34.314  7084  7084 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 15:12:34.324  6994  7091 D Mms/ArtClassLoader: init before art
09-13 15:12:34.324  7084  7084 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-13 15:12:34.334  1016  1028 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7084 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
09-13 15:12:34.334  1016  1028 I ActivityManager: Killing 6368:com.android.calendar/u0a131 (adj 15): empty #21
09-13 15:12:34.334  6994  6994 D Mms/TelephonyPermission: start operation mode monitor
09-13 15:12:34.344  1016  1847 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-13 15:12:34.344  7032  7032 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-13 15:12:34.354  1016  1847 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:34.354  1016  1847 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 15:12:34.354  1016  1847 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-13 15:12:34.354  1016  1487 I ActivityManager: Killing 6625:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
09-13 15:12:34.364  6994  6994 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-13 15:12:34.364  7084  7084 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 15:12:34.364  7084  7084 D ActivityThread: Added TimaKeyStore provider
09-13 15:12:34.374  1016  1029 E PersonaManagerService: inState():  stateMachine is null !!
09-13 15:12:34.374  1016  1029 I PersonaManagerService: PersonaId don't exist
09-13 15:12:34.374  1016  1029 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-13 15:12:34.374  1016  1473 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-13 15:12:34.374  6994  6994 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
09-13 15:12:34.374  6994  6994 D Mms/TelephonyPermission: isDefault true
09-13 15:12:34.384  6994  6994 D Mms/MmsApp: onCreate() com.android.mms
09-13 15:12:34.384  1016  1473 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:34.384  1016  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 15:12:34.384  1016  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-13 15:12:34.394  1016  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-13 15:12:34.414  1016  1029 W ActivityManager: mDVFSHelper.acquire()
09-13 15:12:34.424  1016  1029 D FocusedStackFrame: Set to : 0
09-13 15:12:34.434  1016  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-13 15:12:34.434  1016  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-13 15:12:34.434  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:34.434  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:34.434  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:34.434  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:34.454  6994  6994 D Mms/MmsApp: [start]    initCountryIso consume time = 595.292864
09-13 15:12:34.454  7106  7106 E Zygote  : MountEmulatedStorage()
09-13 15:12:34.454  7106  7106 E Zygote  : v2
09-13 15:12:34.454  7106  7106 I libpersona: KNOX_SDCARD checking this for 10170
09-13 15:12:34.454  7106  7106 I libpersona: KNOX_SDCARD not a persona
09-13 15:12:34.454  7106  7106 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 15:12:34.464  7106  7106 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 15:12:34.464  7106  7106 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-13 15:12:34.464  1016  1489 D CountryDetector: The first listener is added
09-13 15:12:34.464  1016  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-13 15:12:34.464  1016  1029 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7106 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-13 15:12:34.464  1016  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-13 15:12:34.464  1016  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-13 15:12:34.464  1016  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-13 15:12:34.464   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
09-13 15:12:34.474  6994  6994 D Mms/MmsApp: [end]    initCountryIso consume time = 23.650886
09-13 15:12:34.474  6994  6994 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.117812
09-13 15:12:34.484  6994  6994 D Mms/MmsConfig: before partial update
09-13 15:12:34.484  1016  1029 D InputDispatcher: Focused application set to: xxxx
09-13 15:12:34.484  1016  1029 D InputDispatcher: Focus left window: 1490
09-13 15:12:34.494   311   311 I art     : Explicit concurrent mark sweep GC freed 8738(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 38.160ms
09-13 15:12:34.504  1016  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-13 15:12:34.504  1016  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 15:12:34.514  1016  1850 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 15:12:34.514  1016  1850 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-13 15:12:34.514  7032  7032 D AndroidRuntime: Shutting down VM
09-13 15:12:34.514  1016  1850 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:34.514  1016  1850 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 15:12:34.514  1016  1850 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-13 15:12:34.514  6994  6994 D Mms/MmsConfig: Load Resize quality : 80
09-13 15:12:34.524   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 580us total 22.535ms
09-13 15:12:34.524  7106  7106 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 15:12:34.534  7106  7106 D ActivityThread: Added TimaKeyStore provider
09-13 15:12:34.534  6994  6994 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
09-13 15:12:34.534  6994  6994 D EasySignUpManager_1.0.1: isAuth is false
09-13 15:12:34.534  6994  6994 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
09-13 15:12:34.544   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 18.161ms
09-13 15:12:34.544  1016  1847 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-13 15:12:34.544  1016  1016 V ActivityManager: Display changed displayId=0
09-13 15:12:34.554  1016  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-13 15:12:34.564  3828  6855 I qtaguid : Untagging socket 97
09-13 15:12:34.574  6784  6854 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 972 ms] updated apps [took 967 ms] 
09-13 15:12:34.574  1016  1847 D PersonaManager: isKioskContainerExistOnDevice
09-13 15:12:34.594  1016  1479 I ActivityManager: Killing 6656:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
09-13 15:12:34.594  6955  7124 D Ads     : Skipping gmscore version check
09-13 15:12:34.604  1447  4740 D TP/MmsSmsProvider: query,matched:2117, calling pid = 6994
09-13 15:12:34.604  1447  4740 D TP/MmsSmsProvider: match 2117:Elapsed time : 6.211 ms
09-13 15:12:34.614  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-13 15:12:34.634  3828  3828 I ConfigFetchService: fetch service done; releasing wakelock
09-13 15:12:34.644  1016  1850 I ActivityManager: Killing 6640:com.android.providers.calendar/u0a37 (adj 15): empty #21
09-13 15:12:34.644  6955  6955 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
09-13 15:12:34.644  1016  1487 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
09-13 15:12:34.644  1016  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
09-13 15:12:34.654  1016  1851 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
09-13 15:12:34.664  1016  1487 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:34.664  1016  1487 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 15:12:34.664  1016  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
09-13 15:12:34.674  1016  1489 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-13 15:12:34.674  3828  3828 I ConfigFetchService: stopping self
09-13 15:12:34.684   259  6265 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
09-13 15:12:34.684   259   447 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
09-13 15:12:34.684  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:34.684  1016  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 15:12:34.684  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
09-13 15:12:34.694  1490  1490 V ActivityThread: updateVisibility : ActivityRecord{43830c token=android.os.BinderProxy@24db2031 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-13 15:12:34.694  1490  1490 D Launcher: onTrimMemory. Level: 20
09-13 15:12:34.694  6994  6994 D EasySignUpManager_1.0.1: isAuth is false
09-13 15:12:34.694  6994  6994 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
09-13 15:12:34.694  6994  6994 E CscParser: mps_code.dat does not exist
09-13 15:12:34.694  6994  6994 E CscParser: customer_path =/system/csc/customer.xml
09-13 15:12:34.694  6994  6994 E CscParser: fileName + /system/csc/customer.xml
09-13 15:12:34.714  6955  6955 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
09-13 15:12:34.714  6994  6994 E CscParser: mps_code.dat does not exist
09-13 15:12:34.714  6994  6994 E CscParser: customer_path =/system/csc/customer.xml
09-13 15:12:34.714  6994  6994 E CscParser: fileName + /system/csc/customer.xml
09-13 15:12:34.724  7032  7032 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-13 15:12:34.724  6994  6994 D CscParser: getInstance fileName =/system/csc/customer.xml
,09-13 15:12:34.724  6994  6994 D Mms/MmsConfig:  enable multiwindow = false
,09-13 15:12:34.734  3828  3846 W art     : Suspending all threads took: 6.337ms
,09-13 15:12:34.754  6994  6994 E Mms/MessageUtils: setCountryDetector : update country detector info 
09-13 15:12:34.754  6994  6994 E Mms/MessageUtils: updateCountryIso : update country iso info 
,09-13 15:12:34.764  6955  6955 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,09-13 15:12:34.764  6994  6994 D Mms/MmsConfig: [end]    init() consume time = 289.596979
,09-13 15:12:34.764  6994  6994 D Mms/Contact: [start]    init() consume time = 1.480157
,09-13 15:12:34.784  1447  1468 D TP/MmsSmsProvider: query,matched:13, calling pid = 6994
,09-13 15:12:34.784  1447  1468 D TP/MmsSmsProvider: match 13:Elapsed time : 1.156 ms
,09-13 15:12:34.794  6994  6994 D Mms/Contact: [end]    init consume time = 23.711614
,09-13 15:12:34.794  6994  7131 D Mms/DraftCache: [start]    rebuildCache consume time = 8.553281
,09-13 15:12:34.814  1447  1475 D TP/MmsSmsProvider: query,matched:12, calling pid = 6994
,09-13 15:12:34.814  6994  6994 D Mms/MethodReflector: getSubId is called
09-13 15:12:34.814  6994  6994 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,09-13 15:12:34.814  1447  1475 D TP/MmsSmsProvider: match 12:Elapsed time : 1.710 ms
,09-13 15:12:34.814  6994  6994 D Mms/MethodReflector: getTelephonyProperty is called
09-13 15:12:34.814  6994  6994 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-13 15:12:34.814  6994  6994 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-13 15:12:34.814  6994  6994 D Mms/DownloadManager: auto download without roaming -> true
09-13 15:12:34.814  6994  6994 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
,09-13 15:12:34.814  6994  6994 D Mms/MethodReflector: getSubId is called
,09-13 15:12:34.814  6994  6994 D Mms/MethodReflector: getDefaultSmsSubId is called
09-13 15:12:34.814  6994  6994 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
09-13 15:12:34.814  6994  6994 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
09-13 15:12:34.814  6994  6994 D Mms/MethodReflector: getTelephonyProperty is called
09-13 15:12:34.814  6994  6994 D Mms/DownloadManager: roaming -> false (slotId = 1)
09-13 15:12:34.814  6994  6994 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
09-13 15:12:34.814  6994  6994 D Mms/DownloadManager: auto download without roaming -> true
09-13 15:12:34.814  6994  6994 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
09-13 15:12:34.814  6994  6994 D Mms/DownloadManager: auto download during roaming secondary -> false
09-13 15:12:34.814  6994  6994 D Mms/DownloadManager: mAutoDownload ------> true
,09-13 15:12:34.824  6994  7131 D Mms/DraftCache: [end]    rebuildCache consume time = 23.199636
,09-13 15:12:34.874  6994  7091 D Mms/ArtClassLoader: init [DONE] art
,09-13 15:12:34.874  6994  6994 D ComposerPerformance: 1473772354890 ms / [DONE] Composer constructor
,09-13 15:12:34.874  6994  6994 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,09-13 15:12:34.874  6994  6994 I Mms/ReservationManager: ReservationManager()
,09-13 15:12:34.874  6994  6994 I Mms/ReservationManager: resetAfterConnected()
,09-13 15:12:34.884  1447  1475 D TP/MmsSmsProvider: query,matched:7, calling pid = 6994
,09-13 15:12:34.884  1447  1475 D TP/MmsSmsProvider: match 7:Elapsed time : 2.303 ms
,09-13 15:12:34.884  7106  7106 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-13 15:12:34.884  6994  6994 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,09-13 15:12:34.894  6994  7132 D Mms/Conversation: [start]    init() consume time = 67.469583
,09-13 15:12:34.894  6994  6994 D Mms/MmsApp: [end]    onCreate() consume time = 1.551615
,09-13 15:12:34.894  1447  4740 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,09-13 15:12:34.894  1447  4740 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
09-13 15:12:34.894  1447  4740 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,09-13 15:12:34.894  6915  6974 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-13 15:12:34.894  6915  6974 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 15:12:34.894  6915  6974 I GAv4    :   adb logcat -s GAv4
,09-13 15:12:34.894  1447  4740 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,09-13 15:12:34.904  1447  4740 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
,09-13 15:12:34.904  1447  4740 D TP/MmsSmsProvider: need read changed broadcast:false
09-13 15:12:34.904  6994  7132 D Mms/Conversation: [end]    init consume time = 14.651041
,09-13 15:12:34.904  6994  7132 D Mms/MessagingNotification: [start]    init() consume time = 3.252084
,09-13 15:12:34.914  6994  7132 D Mms/MessagingNotification: [end]    init consume time = 3.344166
,09-13 15:12:34.914  6994  6994 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=760]
,09-13 15:12:34.914  6994  6994 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,09-13 15:12:34.914  6994  6994 D Mms/MethodReflector: getSubId is called
09-13 15:12:34.914  6994  6994 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
09-13 15:12:34.914  6994  7135 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 5.078802
,09-13 15:12:34.914  6994  6994 D Mms/MethodReflector: getTelephonyProperty is called
,09-13 15:12:34.924  6994  6994 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-13 15:12:34.924  6994  6994 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-13 15:12:34.924  6994  6994 D Mms/DownloadManager: auto download without roaming -> true
09-13 15:12:34.924  6994  6994 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
09-13 15:12:34.924  6994  6994 D Mms/DownloadManager: mAutoDownload ------> true
,09-13 15:12:34.924  7106  7106 I cr.library_loader: Time to load native libraries: 14 ms (timestamps 6857-6871)
09-13 15:12:34.924  7106  7106 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-13 15:12:34.924  1447  1748 D TP/MmsSmsProvider: query,matched:0, calling pid = 6994
09-13 15:12:34.924  1447  1748 V TP/MmsSmsProvider: getSimpleConversations entered.
,09-13 15:12:34.924  1447  1748 D TP/MmsSmsProvider: match 0:Elapsed time : 1.119 ms
,09-13 15:12:34.924  6994  6994 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
,09-13 15:12:34.924  1016  1221 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
,09-13 15:12:34.924  1016  1221 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,09-13 15:12:34.934  1016  1221 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:34.934  1016  1221 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:34.934  1016  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,09-13 15:12:34.934  6994  7136 D Mms/Synchronizer: [start]    doSync consume time = 14.031823
,09-13 15:12:34.934  1016  1489 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,09-13 15:12:34.934  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:34.934  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:34.934  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:34.934  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:34.944  6994  7139 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
,09-13 15:12:34.944  6994  7139 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
,09-13 15:12:34.944  7141  7141 E Zygote  : MountEmulatedStorage()
09-13 15:12:34.944  7141  7141 E Zygote  : v2
09-13 15:12:34.944  7141  7141 I libpersona: KNOX_SDCARD checking this for 10042
09-13 15:12:34.944  7141  7141 I libpersona: KNOX_SDCARD not a persona
09-13 15:12:34.954  7141  7141 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 15:12:34.954  7106  7106 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {eb34b2}
09-13 15:12:34.954  7106  7106 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-13 15:12:34.954  7106  7106 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 15:12:34.954  7141  7141 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 15:12:34.954  1016  1489 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7141 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
09-13 15:12:34.954  7141  7141 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
,09-13 15:12:34.964  6915  6974 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
09-13 15:12:34.964  1016  1851 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
09-13 15:12:34.964  1016  1850 I ActivityManager: Killing 6673:com.qualcomm.timeservice/1000 (adj 15): empty #21
,09-13 15:12:34.974  1447  4740 D TP/MmsSmsProvider: update, matched:300, calling pid = 6994
09-13 15:12:34.974  1447  4740 V TP/MmsSmsProvider: syncDBData start
,09-13 15:12:34.974  1447  4740 V TP/MmsSmsProvider: syncDBData sms end
,09-13 15:12:34.974  1447  4740 V TP/MmsSmsProvider: syncDBData mms end
,09-13 15:12:34.974  1447  4740 V TP/MmsSmsProvider: syncDBData end
,09-13 15:12:34.974  1016  1221 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,09-13 15:12:34.974  1447  1468 D TP/MmsSmsProvider: query,matched:400, calling pid = 6994,
09-13 15:12:34.974  1016  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:34.974  1016  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:34.974  1016  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:34.974  1016  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:34.994  7141  7141 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:12:34.994  7141  7141 D ActivityThread: Added TimaKeyStore provider
,09-13 15:12:34.994  7156  7156 E Zygote  : MountEmulatedStorage()
,09-13 15:12:34.994  7156  7156 E Zygote  : v2
09-13 15:12:34.994  7156  7156 I libpersona: KNOX_SDCARD checking this for 10068
09-13 15:12:34.994  7156  7156 I libpersona: KNOX_SDCARD not a persona
09-13 15:12:34.994  7156  7156 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 15:12:35.004  1016  1221 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7156 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,09-13 15:12:35.004  7156  7156 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 15:12:35.004  6994  7136 D Mms/Synchronizer: [end]    doSync consume time = 70.676094
09-13 15:12:35.004  7156  7156 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-13 15:12:35.014  6915  6974 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-13 15:12:35.014  6994  7135 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 14.910521
,09-13 15:12:35.024  7141  7141 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 15:12:35.024  7141  7141 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-13 15:12:35.024  7141  7141 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-13 15:12:35.024  7156  7156 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:12:35.024  7156  7156 D ActivityThread: Added TimaKeyStore provider
,09-13 15:12:35.034  1016  1850 I ActivityManager: Killing 6443:com.android.defcontainer/u0a3 (adj 15): empty #21
,09-13 15:12:35.034  7106  7106 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-13 15:12:35.034  7106  7106 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 15:12:35.044  7106  7106 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-13 15:12:35.064  7106  7106 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-13 15:12:35.064  7106  7106 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-13 15:12:35.064  7106  7106 I Adreno-EGL: Build Date: 04/06/15 Mon
09-13 15:12:35.064  7106  7106 I Adreno-EGL: Local Branch: 
09-13 15:12:35.064  7106  7106 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-13 15:12:35.064  7106  7106 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-13 15:12:35.064  7106  7106 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-13 15:12:35.064  6915  7172 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-13 15:12:35.074  6915  6974 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
,09-13 15:12:35.074  7156  7156 D BadgeProvider: onCreate
,09-13 15:12:35.074  7156  7156 D BadgeProvider: DatabaseHelper
,09-13 15:12:35.084  1016  1043 W ActivityManager: Activity pause timeout for ActivityRecord{37e09a0d u0 com.test.thalitest/.MainActivity t163}
,09-13 15:12:35.094  6994  7132 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,09-13 15:12:35.104  1447  1475 D TP/SmsProvider: query,matched:26, calling pid = 6994
,09-13 15:12:35.104  1447  1475 D TP/SmsProvider: match 26:Elapsed time : 1.418 ms
,09-13 15:12:35.114  1447  1468 D TP/MmsSmsProvider: query,matched:6, calling pid = 6994
,09-13 15:12:35.114  1447  1468 D TP/MmsSmsProvider: match 6:Elapsed time : 1.478 ms
,09-13 15:12:35.144  7106  7106 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 15:12:35.144  1016  1489 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,09-13 15:12:35.154  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:35.154  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:35.154  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:35.154  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:35.154  7106  7106 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
09-13 15:12:35.154  7106  7106 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-13 15:12:35.164  7106  7106 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-13 15:12:35.164  7106  7106 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-13 15:12:35.164  7189  7189 E Zygote  : MountEmulatedStorage()
09-13 15:12:35.164  7189  7189 E Zygote  : v2
09-13 15:12:35.164  7189  7189 I libpersona: KNOX_SDCARD checking this for 10023
09-13 15:12:35.164  7189  7189 I libpersona: KNOX_SDCARD not a persona
09-13 15:12:35.164  7189  7189 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 15:12:35.164  1016  1489 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=7189 uid=10023 gids={50023, 9997} abi=armeabi-v7a
,09-13 15:12:35.174  7189  7189 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-13 15:12:35.174  7189  7189 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 15:12:35.194  7141  7141 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,09-13 15:12:35.194  1016  1057 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
09-13 15:12:35.194  1016  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-13 15:12:35.194  1016  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:35.194  1016  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:35.194  1016  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:35.194  1016  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:35.214  7204  7204 E Zygote  : MountEmulatedStorage(),
09-13 15:12:35.214  7204  7204 I libpersona: KNOX_SDCARD checking this for 10003
09-13 15:12:35.214  7204  7204 E Zygote  : v2
09-13 15:12:35.214  7204  7204 I libpersona: KNOX_SDCARD not a persona
09-13 15:12:35.214  7204  7204 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 15:12:35.214  1016  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7204 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-13 15:12:35.214  1016  1028 I ActivityManager: Killing 6699:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
,09-13 15:12:35.214  7204  7204 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 15:12:35.214  7204  7204 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 15:12:35.214  7189  7189 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:12:35.214  7189  7189 D ActivityThread: Added TimaKeyStore provider
,09-13 15:12:35.224  1016  1463 I ActivityManager: Killing 6713:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
,09-13 15:12:35.234  7204  7204 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:12:35.234  7204  7204 D ActivityThread: Added TimaKeyStore provider
,09-13 15:12:35.264   285   285 E installd: system dir 0 : /system/app/
,09-13 15:12:35.264   285   285 E installd: system dir 1 : /system/priv-app/
09-13 15:12:35.264   285   285 E installd: system dir 2 : /vendor/app/
09-13 15:12:35.264   285   285 E installd: system dir 3 : /oem/app/
,09-13 15:12:35.274  7189  7189 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,09-13 15:12:35.274  1016  1057 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,09-13 15:12:35.314  6994  7132 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,09-13 15:12:35.334  7189  7189 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,09-13 15:12:35.334  7189  7189 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,09-13 15:12:35.334  7189  7189 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,09-13 15:12:35.334  7189  7189 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,09-13 15:12:35.334  7189  7189 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,09-13 15:12:35.344  7189  7189 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,09-13 15:12:35.344  7189  7189 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,09-13 15:12:35.344  7189  7189 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,09-13 15:12:35.344  7189  7189 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,09-13 15:12:35.344  7189  7189 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,09-13 15:12:35.344  7189  7189 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,09-13 15:12:35.344  7189  7189 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,09-13 15:12:35.344  7189  7189 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,09-13 15:12:35.394  1016  1463 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
09-13 15:12:35.394  1016  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:35.394  1016  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:35.394  1016  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:35.394  1016  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:35.414  1016  1463 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7228 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-13 15:12:35.414  7228  7228 E Zygote  : MountEmulatedStorage()
09-13 15:12:35.414  7228  7228 I libpersona: KNOX_SDCARD checking this for 1000
09-13 15:12:35.414  7228  7228 E Zygote  : v2
09-13 15:12:35.414  7228  7228 I libpersona: KNOX_SDCARD not a persona
09-13 15:12:35.414  1016  1463 I ActivityManager: Killing 5070:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
09-13 15:12:35.414  7228  7228 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 15:12:35.414  7228  7228 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 15:12:35.414  7228  7228 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 15:12:35.434  6915  7223 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-13 15:12:35.434  6915  7223 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-13 15:12:35.444  7228  7228 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 15:12:35.444  7228  7228 D ActivityThread: Added TimaKeyStore provider
09-13 15:12:35.454  7106  7106 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 15:12:35.464  7228  7228 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
09-13 15:12:35.474  7228  7228 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
09-13 15:12:35.474  6915  7223 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
09-13 15:12:35.474  1016  1487 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
09-13 15:12:35.474  7106  7106 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-13 15:12:35.474  1016  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
09-13 15:12:35.474  1016  1487 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:35.474  1016  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:35.474  1016  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
09-13 15:12:35.474  1016  1479 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
09-13 15:12:35.484  1016  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
09-13 15:12:35.484  1016  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:35.484  1016  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:35.484  1016  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:35.484  1016  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:35.494  7106  7106 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-13 15:12:35.494  7245  7245 I libpersona: KNOX_SDCARD checking this for 10130
09-13 15:12:35.494  7106  7106 D PhoneWindow: *FMB* installDecor flags : -2139027200
09-13 15:12:35.494  7245  7245 I libpersona: KNOX_SDCARD not a persona
09-13 15:12:35.494  7245  7245 E Zygote  : MountEmulatedStorage()
09-13 15:12:35.494  7245  7245 E Zygote  : v2
09-13 15:12:35.494  7245  7245 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 15:12:35.494  7245  7245 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 15:12:35.504  7245  7245 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
09-13 15:12:35.504  7106  7106 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
09-13 15:12:35.504  1016  1043 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7245 uid=10130 gids={50130, 9997} abi=armeabi-v7a
09-13 15:12:35.504  7228  7228 I FilterInstaller: FilterPackageService : ACTION_CHANGED
09-13 15:12:35.514  7106  7106 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 15:12:35.514  7106  7106 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 15:12:35.524  7228  7244 E FilterInstaller: installFilters
09-13 15:12:35.524  7228  7244 E FilterInstaller: There is no requred permission
09-13 15:12:35.534  6915  7223 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-13 15:12:35.534  6915  7223 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@225c7f91: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-13 15:12:35.534  6915  7223 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-13 15:12:35.534  1016  1850 I ActivityManager: Killing 6740:com.samsung.helphub/1000 (adj 15): empty #21
09-13 15:12:35.544  7245  7245 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 15:12:35.544  7245  7245 D ActivityThread: Added TimaKeyStore provider
09-13 15:12:35.564  7245  7245 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 15:12:35.564  7245  7245 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
09-13 15:12:35.574  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
09-13 15:12:35.574  3828  4269 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
09-13 15:12:35.574  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:35.574  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:35.574  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:35.574  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:35.594  7264  7264 E Zygote  : MountEmulatedStorage()
09-13 15:12:35.594  7264  7264 E Zygote  : v2
09-13 15:12:35.594  7264  7264 I libpersona: KNOX_SDCARD checking this for 10131
09-13 15:12:35.594  7264  7264 I libpersona: KNOX_SDCARD not a persona
09-13 15:12:35.594  7264  7264 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 15:12:35.594  1016  1028 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7264 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
09-13 15:12:35.594  7264  7264 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 15:12:35.594  1016  1028 I ActivityManager: Killing 6765:com.sec.spp.push/u0a32 (adj 15): empty #21
09-13 15:12:35.594  7264  7264 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 15:12:35.604  7106  7272 D OpenGLRenderer: Render dirty regions requested: true
09-13 15:12:35.614  1016  1489 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-13 15:12:35.614  1016  1489 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-13 15:12:35.614  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
09-13 15:12:35.614  1016  1489 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-13 15:12:35.614  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-13 15:12:35.614  7106  7106 V ActivityThread: updateVisibility : ActivityRecord{2f98779d token=android.os.BinderProxy@4495e47 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-13 15:12:35.614  7106  7182 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
09-13 15:12:35.624  7106  7106 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-13 15:12:35.624  7106  7106 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-13 15:12:35.634  7264  7264 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 15:12:35.634  7264  7264 D ActivityThread: Added TimaKeyStore provider
09-13 15:12:35.644   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
09-13 15:12:35.654  3828  4269 D Icing   : Loaded CLD2 Version V2.0 - 20141016
09-13 15:12:35.664  7264  7264 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-13 15:12:35.664  7264  7264 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 15:12:35.664  7264  7264 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 15:12:35.664  1016  1474 D InputDispatcher: Focus entered window: 7106
09-13 15:12:35.674  7106  7106 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-13 15:12:35.674  7106  7272 I OpenGLRenderer: Initialized EGL, version 1.4
09-13 15:12:35.674  1016  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-13 15:12:35.674  1016  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 15:12:35.674  7106  7272 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-13 15:12:35.674  7106  7272 D OpenGLRenderer: Enabling debug mode 0
09-13 15:12:35.694  1016  1028 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
09-13 15:12:35.704  1173  1173 D PanelView: There is/are notification(s) 
09-13 15:12:35.704  1016  7287 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-13 15:12:35.714  3828  4269 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
09-13 15:12:35.714  2634  2742 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
09-13 15:12:35.714  1016  1048 I ActivityManager: Displayed Component not be shown by security: +1s135ms (total +1s288ms)
09-13 15:12:35.724  1016  1048 W ActivityManager: mDVFSHelper.release()
09-13 15:12:35.724  1016  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{37e09a0d u0 com.test.thalitest/.MainActivity t163} time:97671
09-13 15:12:35.724  7106  7106 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-13 15:12:35.724   259   447 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
09-13 15:12:35.724  7106  7106 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@4495e47 time:97676
09-13 15:12:35.724   259  6265 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
09-13 15:12:35.734  1016  1850 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
09-13 15:12:35.734  1016  1850 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
09-13 15:12:35.734  1016  1850 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:35.734  1016  1850 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:35.734  1016  1850 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
09-13 15:12:35.744  1892  1892 I SamsungIME: getCurrentCandidateView
09-13 15:12:35.754  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
09-13 15:12:35.754  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:35.754  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 15:12:35.754  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-13 15:12:35.754  1016  1489 I ActivityManager: Killing 6729:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
09-13 15:12:35.754  1016  1221 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
09-13 15:12:35.754  1016  1221 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
09-13 15:12:35.764  1016  1221 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:35.764  1016  1221 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:35.764  1016  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
09-13 15:12:35.764   274   274 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8bf27c8
09-13 15:12:35.764   274   274 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
09-13 15:12:35.764   274   274 I rmt_storage: wakelock acquired: 1, error no: 42
09-13 15:12:35.764   274   340 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1195431800)
09-13 15:12:35.804  1016  1463 I ActivityManager: Killing 6816:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
09-13 15:12:35.814   274   340 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
09-13 15:12:35.814   274   340 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
09-13 15:12:35.814   274   340 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1195431800) wakelock released: 1, error no: 0
09-13 15:12:35.814   274   340 I rmt_storage: 
09-13 15:12:35.824   274   274 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb8bf27c8
09-13 15:12:35.834  7106  7106 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7106
09-13 15:12:35.874  1892  1892 D SamsungIME: Dismiss ExpandCandiate
09-13 15:12:36.024  1892  1892 I SamsungIME: getDebugLevel  : 0x4f4c
09-13 15:12:36.044  7106  7106 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-13 15:12:36.064   290   290 E SMD     : DCD OFF
09-13 15:12:36.074  1892  1892 I SamsungIME: getDebugLevel  : 0x4f4c
,09-13 15:12:36.084  1892  1892 I SamsungIME: KeybaordView init() : load resources
,09-13 15:12:36.104  1892  1892 I SamsungIME: getCurrentKeyboard
,09-13 15:12:36.104  1892  1892 I SamsungIME: getTextKeyboard
,09-13 15:12:36.124  1892  1892 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-13 15:12:36.124  1016  3406 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-13 15:12:36.144  7106  7289 D jxcore_app_log: JniHelper::setJavaVM(0xb7b2e2b0), pthread_self() = -1207191656
,09-13 15:12:36.144  7106  7289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 15:12:36.144  7106  7289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 15:12:36.144  7106  7289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 15:12:36.144  7106  7289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 15:12:36.144  7106  7289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-13 15:12:36.144  7106  7289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b0db0f8 added. We now have 1 listener(s)
,09-13 15:12:36.154  7106  7289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,09-13 15:12:36.154  7106  7289 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-13 15:12:36.154  7106  7289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 15:12:36.154  7106  7289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 15:12:36.164  7106  7289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 15:12:36.164  7106  7289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 15:12:36.164  7106  7289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 15:12:36.164  7106  7289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
09-13 15:12:36.164  7106  7289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 15:12:36.164  7106  7289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 15:12:36.164  7106  7289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 15:12:36.164  7106  7289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 15:12:36.164  7106  7289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 15:12:36.164  7106  7289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 15:12:36.164  7106  7289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 15:12:36.164  7106  7289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 15:12:36.164  7106  7289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 15:12:36.164  7106  7289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-13 15:12:36.164  7106  7289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec06737 added. We now have 1 listener(s)
,09-13 15:12:36.164  7106  7289 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 15:12:36.174  7106  7289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 15:12:36.174  7106  7289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-13 15:12:36.174  7106  7289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 15:12:36.174  7106  7289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 15:12:36.174  7106  7289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-13 15:12:36.174  7106  7289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 15:12:36.184  7106  7289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,09-13 15:12:36.184  7106  7289 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-13 15:12:36.184  7106  7289 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:12:36.184  7106  7289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:36.184  7106  7289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:36.184  7106  7289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:12:36.184  7106  7289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:12:36.184  7106  7289 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:12:36.184  7106  7289 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:12:36.184  7106  7289 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 15:12:36.184  7106  7289 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 15:12:36.184  7106  7289 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 15:12:36.194  7106  7289 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 15:12:36.194  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:12:36.194  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:12:36.214  7106  7106 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 15:12:36.764  7106  7300 W jxcore-log: Initializing JXcore engine
09-13 15:12:36.764  7106  7300 W jxcore-log: JXcore engine is ready
,09-13 15:12:36.824  2013  2013 E audit   : type=1400 msg=audit(1473772356.824:205): avc:  denied  { ioctl } for  pid=7300 comm="Thread-1350" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2074 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-13 15:12:36.824  2013  2013 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-13 15:12:36.824  2013  2013 E audit   : type=1300 msg=audit(1473772356.824:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e4838f8 items=0 ppid=311 ppcomm=main pid=7300 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1350" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-13 15:12:36.824  2013  2013 E audit   : type=1320 msg=audit(1473772356.824:205): 
,09-13 15:12:36.834  7106  7300 W jxcore-log: Starting JXcore engine
,09-13 15:12:36.894  6994  6994 I Mms/MmsApp:  start initViewCache mms
,09-13 15:12:36.894  6994  6994 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1876.417395
,09-13 15:12:36.894  6994  6994 D Mms/ComposeMessageFragment: fillCache, easy = false
,09-13 15:12:36.944  7106  7300 W jxcore-log: Platform android
09-13 15:12:36.944  7106  7300 W jxcore-log: 
,09-13 15:12:36.944  7106  7300 W jxcore-log: Process ARCH arm
09-13 15:12:36.944  7106  7300 W jxcore-log: 
,09-13 15:12:37.004  6994  6994 D AbsListView: Get MotionRecognitionManager
,09-13 15:12:37.004  1016  1028 D MotionRecognitionService:  ssp status : false
,09-13 15:12:37.004  6994  6994 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 113.826927
,09-13 15:12:37.084  6994  6994 D Mms/BubbleViewCache: fillCache bubble = 1
,09-13 15:12:37.154  7106  7300 I jxcore-log: JXcore Cordova bridge is ready!
09-13 15:12:37.154  7106  7300 I jxcore-log: 
,09-13 15:12:37.154  7106  7300 W jxcore-log: JXcore engine is started
,09-13 15:12:37.164  7106  7289 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 15:12:37.164  7106  7106 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 15:12:39.064   290   290 E SMD     : DCD OFF,
,09-13 15:12:39.294  1016  3387 D SSRM:n  : SIOP:: AP = 410,
,09-13 15:12:39.694  2654  2654 I ConfigService: onDestroy
,09-13 15:12:41.134  1016  3406 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 15:12:42.064   290   290 E SMD     : DCD OFF
,09-13 15:12:44.004  1016  1850 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 15:12:44.014  1016  1850 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4258, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-13 15:12:44.014  1016  1850 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 15:12:44.014  1016  1850 D BatteryService: stay LED for charging
09-13 15:12:44.014  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 15:12:44.014  1016  1016 I MotionRecognitionService: Plugged,
09-13 15:12:44.014  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 15:12:44.014  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 15:12:44.014  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-13 15:12:44.024  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-13 15:12:44.024  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 15:12:44.024  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 15:12:44.034  3238  3238 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 15:12:44.034  3238  3377 D HeadsetStateMachine: Disconnected process message: 10
,09-13 15:12:44.044  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 15:12:44.044  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 15:12:44.474  1016  1057 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,09-13 15:12:45.074   290   290 E SMD     : DCD OFF
,09-13 15:12:45.284  1016  1057 D PackageManager: [MSG] MCS_UNBIND
,09-13 15:12:45.284  1016  1487 I ActivityManager: Killing 6784:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,09-13 15:12:46.014  1016  1318 E Watchdog: !@Sync 3
,09-13 15:12:47.084   327   327 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-13 15:12:47.084   327   327 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-13 15:12:48.074   290   290 E SMD     : DCD OFF
,09-13 15:12:49.264  1016  1097 V AlarmManager: waitForAlarm result :4
,09-13 15:12:49.264  1016  1097 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,09-13 15:12:49.284  1016  1050 I PowerManagerService: [PWL] Off : 50s ago
,09-13 15:12:49.314  1016  3387 D SSRM:n  : SIOP:: AP = 380
,09-13 15:12:49.514  6955  7059 D Finsky  : [1314] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,09-13 15:12:49.514  6955  6955 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,09-13 15:12:49.664  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 15:12:49.664  7106  7300 I jxcore-log: 
,09-13 15:12:49.664  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 15:12:49.664  7106  7300 I jxcore-log: 
,09-13 15:12:49.664  7106  7300 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:12:49.664  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:49.664  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:49.664  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:12:49.664  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:12:49.664  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:12:49.664  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:12:49.664  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 15:12:49.674  7106  7300 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 15:12:49.674  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 15:12:49.674  7106  7300 I jxcore-log: 
,09-13 15:12:49.674  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 15:12:49.674  7106  7300 I jxcore-log: 
,09-13 15:12:50.354  7106  7300 D executeNativeTests: Running unit tests,
,09-13 15:12:50.444  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:12:50.444  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286e59c8 added. We now have 2 listener(s)
,09-13 15:12:50.444  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-13 15:12:50.444  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:12:50.444  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:12:50.444  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:12:50.444  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 added. We now have 2 listener(s)
09-13 15:12:50.444  7106  7300 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 15:12:50.444  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 15:12:50.444  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 15:12:50.454  7106  7300 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:12:50.454  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:50.454  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:50.454  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:12:50.454  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:12:50.454  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:12:50.454  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:12:50.454  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 15:12:50.454  7106  7300 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 15:12:50.454  7106  7300 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 15:12:50.454  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:12:50.454  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 15:12:50.454  7106  7300 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 15:12:50.454  7106  7300 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 15:12:50.454  7106  7300 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-13 15:12:50.464  7106  7300 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 15:12:50.464  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 15:12:50.464  7106  7300 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 15:12:50.464  7106  7300 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 15:12:50.464  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 15:12:50.464  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:50.464  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:50.464  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:50.464  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.464  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:12:50.464  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:12:50.464  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286e59c8 removed from the list
09-13 15:12:50.464  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.464  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 removed from the list
,09-13 15:12:50.464  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:12:50.464  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:50.464  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:50.464  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.464  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:50.464  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 15:12:50.464  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:50.464  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 15:12:50.464  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
,09-13 15:12:50.464  7106  7300 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-13 15:12:50.474  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:50.474  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:50.474  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
09-13 15:12:50.474  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:50.474  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.474  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.474  7106  7300 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286e59c8 not in the list
09-13 15:12:50.474  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.474  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
,09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:50.474  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.474  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.474  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.474  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:50.474  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:50.474  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:50.474  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.474  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
,09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 15:12:50.474  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:50.474  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:50.474  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:50.474  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:50.474  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-13 15:12:50.474  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.474  7106  7300 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286e59c8 not in the list
09-13 15:12:50.474  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.474  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.474  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 15:12:50.474  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:12:50.474  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.474  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.474  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.474  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 15:12:50.474  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:50.474  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.474  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.474  7106  7300 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-13 15:12:50.484  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 15:12:50.484  7106  7300 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:12:50.484  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,09-13 15:12:50.484  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:50.484  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:12:50.484  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:12:50.484  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:12:50.484  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:12:50.484  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 15:12:50.484  7106  7300 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 15:12:50.484  7106  7300 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 15:12:50.484  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 15:12:50.484  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 15:12:50.484  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 15:12:50.484  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 15:12:50.484  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 15:12:50.494  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:12:50.494  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:12:50.494  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 15:12:50.494  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 15:12:50.504  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 15:12:50.504  7106  7300 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-13 15:12:50.504  7106  7300 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-13 15:12:50.504  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 15:12:50.504  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-13 15:12:50.504  7106  7300 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 15:12:50.514  3238  3254 D BtGatt.GattService: registerClient() - UUID=8a6babe0-5b0d-492d-92dc-76280f2c8c84
,09-13 15:12:50.564  3238  3313 D BtGatt.GattService: onClientRegistered() - UUID=8a6babe0-5b0d-492d-92dc-76280f2c8c84, clientIf=6
,09-13 15:12:50.564  7106  7117 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-13 15:12:50.564  3238  3395 D BtGatt.GattService: start scan with filters
,09-13 15:12:50.564  3238  3370 D BtGatt.ScanManager: handling starting scan
,09-13 15:12:50.564  3238  3370 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
,09-13 15:12:50.574  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 15:12:50.574  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 15:12:50.574  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 15:12:50.574  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 15:12:50.574  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 15:12:50.574  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 15:12:50.574  7106  7106 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 15:12:50.574  3238  3313 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-13 15:12:50.574  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 15:12:50.574  3238  3370 D BtGatt.ScanManager: allow scan with filters
09-13 15:12:50.574  3238  3370 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-13 15:12:50.574  3238  3370 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-13 15:12:50.574  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 15:12:50.584  3238  3313 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-13 15:12:50.584  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:12:50.584  3238  3370 D BtGatt.ScanManager: Starting BLE batch scan
,09-13 15:12:50.584  3238  3370 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-13 15:12:50.584  7106  7300 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 15:12:50.594  3238  3313 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-13 15:12:50.594  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:12:50.594  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 15:12:50.594  7106  7300 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 15:12:50.594  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:50.594  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 15:12:50.594  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.594  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 15:12:50.594  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 15:12:50.594  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 15:12:50.604  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 15:12:50.604  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 15:12:50.604  3238  3313 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-13 15:12:50.604  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:12:50.604  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 15:12:50.604  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 15:12:50.604  3238  3358 D BtGatt.GattService: stopScan() - queue size =1
,09-13 15:12:50.604  3238  3370 D BtGatt.ScanManager: filter size is 1
,09-13 15:12:50.604  3238  3370 D BtGatt.ScanManager: delete FilterIndex - 3
,09-13 15:12:50.614  3238  3262 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 15:12:50.614  3238  3313 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-13 15:12:50.614  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:12:50.614  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 15:12:50.614  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 15:12:50.614  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 15:12:50.614  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 15:12:50.614  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 15:12:50.614  3238  3370 D BtGatt.ScanManager: stopping BLe Batch
09-13 15:12:50.614  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 15:12:50.614  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 15:12:50.614  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 15:12:50.614  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 15:12:50.614  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 15:12:50.614  7106  7106 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 15:12:50.614  7106  7106 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 15:12:50.614  7106  7106 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 15:12:50.624  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:50.624  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.624  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:12:50.624  7106  7300 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286e59c8 not in the list
09-13 15:12:50.624  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.624  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.624  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:50.624  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:50.624  7106  7300 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-13 15:12:50.624  3238  3313 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-13 15:12:50.624  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:12:50.624  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 15:12:50.624  3238  3370 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 15:12:50.624  3238  3313 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-13 15:12:50.624  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:12:50.634  7106  7300 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:12:50.634  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:50.634  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:50.634  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:12:50.634  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:12:50.634  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:12:50.634  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:12:50.634  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 15:12:50.634  7106  7300 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 15:12:50.634  7106  7300 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 15:12:50.634  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:12:50.634  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:12:50.644  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 15:12:50.644  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 15:12:50.644  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 15:12:50.644  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:12:50.644  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 15:12:50.644  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,09-13 15:12:50.644  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 15:12:50.644  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 15:12:50.654  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 15:12:50.654  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 15:12:50.654  7106  7300 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 15:12:50.654  3238  3254 D BtGatt.GattService: registerClient() - UUID=0b2c0f7b-4b65-4b40-a2b8-45c3fff3efa3
,09-13 15:12:50.704  3238  3313 D BtGatt.GattService: onClientRegistered() - UUID=0b2c0f7b-4b65-4b40-a2b8-45c3fff3efa3, clientIf=6
,09-13 15:12:50.704  7106  7114 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-13 15:12:50.704  3238  3358 D BtGatt.GattService: start scan with filters
,09-13 15:12:50.704  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 15:12:50.704  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 15:12:50.704  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 15:12:50.704  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 15:12:50.704  3238  3370 D BtGatt.ScanManager: handling starting scan
,09-13 15:12:50.704  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 15:12:50.704  7106  7106 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 15:12:50.704  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 15:12:50.704  3238  3313 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-13 15:12:50.704  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:12:50.704  3238  3370 D BtGatt.ScanManager: allow scan with filters
,09-13 15:12:50.714  3238  3370 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-13 15:12:50.714  3238  3370 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-13 15:12:50.714  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 15:12:50.714  3238  3313 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-13 15:12:50.714  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:12:50.714  3238  3370 D BtGatt.ScanManager: Starting BLE batch scan
09-13 15:12:50.714  3238  3370 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-13 15:12:50.724  7106  7300 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 15:12:50.724  3238  3313 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-13 15:12:50.724  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:12:50.724  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 15:12:50.724  7106  7300 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 15:12:50.734  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:50.734  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 15:12:50.734  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.734  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 15:12:50.734  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 15:12:50.734  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 15:12:50.734  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 15:12:50.734  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 15:12:50.734  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 15:12:50.734  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 15:12:50.734  3238  3313 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-13 15:12:50.734  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:12:50.734  3238  3358 D BtGatt.GattService: stopScan() - queue size =1
,09-13 15:12:50.734  3238  3370 D BtGatt.ScanManager: filter size is 1
,09-13 15:12:50.734  3238  3370 D BtGatt.ScanManager: delete FilterIndex - 4
,09-13 15:12:50.744  3238  3262 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 15:12:50.744  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 15:12:50.744  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 15:12:50.744  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 15:12:50.744  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 15:12:50.744  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 15:12:50.744  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 15:12:50.744  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 15:12:50.744  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 15:12:50.744  3238  3313 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-13 15:12:50.744  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:12:50.744  3238  3370 D BtGatt.ScanManager: stopping BLe Batch
,09-13 15:12:50.744  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 15:12:50.744  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 15:12:50.754  7106  7106 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-13 15:12:50.754  7106  7106 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 15:12:50.754  7106  7106 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 15:12:50.754  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:50.754  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.754  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 15:12:50.754  7106  7300 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286e59c8 not in the list
09-13 15:12:50.754  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.754  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.754  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:50.754  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:50.754  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.754  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:50.754  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 15:12:50.754  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-13 15:12:50.754  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.754  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
,09-13 15:12:50.754  7106  7300 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 15:12:50.754  3238  3313 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-13 15:12:50.754  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 15:12:50.754  3238  3370 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-13 15:12:50.754  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 15:12:50.764  7106  7300 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:12:50.764  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:50.764  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:50.764  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:12:50.764  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:12:50.764  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:12:50.764  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:12:50.764  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 15:12:50.764  3238  3313 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-13 15:12:50.764  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:12:50.764  7106  7300 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 15:12:50.764  7106  7300 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 15:12:50.764  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 15:12:50.764  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 15:12:50.764  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 15:12:50.764  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:12:50.764  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 15:12:50.764  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:12:50.774  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:12:50.774  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 15:12:50.774  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 15:12:50.774  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 15:12:50.784  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 15:12:50.784  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-13 15:12:50.784  7106  7300 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 15:12:50.784  3238  3358 D BtGatt.GattService: registerClient() - UUID=36333ee6-9033-44cf-874f-e23c7b5cbb39
,09-13 15:12:50.834  3238  3313 D BtGatt.GattService: onClientRegistered() - UUID=36333ee6-9033-44cf-874f-e23c7b5cbb39, clientIf=6
,09-13 15:12:50.834  7106  7114 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-13 15:12:50.834  3238  3360 D BtGatt.GattService: start scan with filters
,09-13 15:12:50.834  3238  3370 D BtGatt.ScanManager: handling starting scan,
,09-13 15:12:50.834  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 15:12:50.834  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-13 15:12:50.834  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-13 15:12:50.834  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 15:12:50.834  3238  3313 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-13 15:12:50.834  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:12:50.834  3238  3370 D BtGatt.ScanManager: allow scan with filters
09-13 15:12:50.844  3238  3370 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-13 15:12:50.844  3238  3370 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-13 15:12:50.844  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 15:12:50.844  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 15:12:50.844  7106  7106 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 15:12:50.844  3238  3313 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-13 15:12:50.844  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:12:50.844  3238  3370 D BtGatt.ScanManager: Starting BLE batch scan
,09-13 15:12:50.844  3238  3370 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-13 15:12:50.844  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 15:12:50.854  3238  3313 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-13 15:12:50.854  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:12:50.854  7106  7300 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 15:12:50.854  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 15:12:50.854  7106  7300 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 15:12:50.854  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:50.854  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 15:12:50.854  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:12:50.864  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 15:12:50.864  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 15:12:50.864  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 15:12:50.864  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 15:12:50.864  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 15:12:50.864  3238  3313 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
,09-13 15:12:50.864  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:12:50.864  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 15:12:50.864  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 15:12:50.874  3238  3254 D BtGatt.GattService: stopScan() - queue size =1
,09-13 15:12:50.874  3238  3370 D BtGatt.ScanManager: filter size is 1
,09-13 15:12:50.874  3238  3370 D BtGatt.ScanManager: delete FilterIndex - 5
,09-13 15:12:50.874  3238  3262 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 15:12:50.874  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 15:12:50.874  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-13 15:12:50.874  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-13 15:12:50.874  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 15:12:50.874  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 15:12:50.884  3238  3313 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-13 15:12:50.884  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:12:50.884  3238  3370 D BtGatt.ScanManager: stopping BLe Batch
,09-13 15:12:50.884  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 15:12:50.884  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 15:12:50.884  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 15:12:50.884  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 15:12:50.884  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 15:12:50.884  7106  7106 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 15:12:50.884  7106  7106 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 15:12:50.884  7106  7106 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 15:12:50.884  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:50.884  7106  7300 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 15:12:50.884  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:50.884  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:50.884  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:50.884  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.884  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:12:50.884  7106  7300 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286e59c8 not in the list
09-13 15:12:50.884  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.884  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.884  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:50.884  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.884  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.884  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:50.884  3238  3313 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-13 15:12:50.884  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 15:12:50.884  3238  3370 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 15:12:50.894  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 15:12:50.894  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:50.894  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.894  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
,09-13 15:12:50.894  7106  7300 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-13 15:12:50.894  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:50.894  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:50.894  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:50.894  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:50.894  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.894  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.894  7106  7300 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286e59c8 not in the list
09-13 15:12:50.894  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.894  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.894  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:50.894  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.894  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.894  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.894  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:50.894  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:50.894  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 15:12:50.894  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.894  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
,09-13 15:12:50.894  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 15:12:50.894  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:50.894  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:50.894  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 15:12:50.894  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:50.894  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.894  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.894  7106  7300 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286e59c8 not in the list
,09-13 15:12:50.894  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.894  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.894  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop,
09-13 15:12:50.894  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.894  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.894  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:12:50.894  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.894  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:50.894  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:50.894  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 15:12:50.894  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.894  3238  3313 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-13 15:12:50.894  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 15:12:50.894  7106  7300 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-13 15:12:50.894  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:50.894  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:50.894  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 15:12:50.894  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:50.894  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.894  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.894  7106  7300 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286e59c8 not in the list
09-13 15:12:50.894  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 15:12:50.894  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.894  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:50.894  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.894  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:50.894  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.894  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.894  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 15:12:50.894  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-13 15:12:50.894  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.894  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
,09-13 15:12:50.904  7106  7300 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 15:12:50.904  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:50.904  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 15:12:50.904  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:50.904  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:50.904  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:12:50.904  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.904  7106  7300 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286e59c8 not in the list
,09-13 15:12:50.904  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.904  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.904  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 15:12:50.904  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.904  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.904  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:12:50.904  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:50.904  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:50.904  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:50.904  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 15:12:50.904  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.904  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 15:12:50.904  7106  7300 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
,09-13 15:12:50.904  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-13 15:12:50.904  7106  7300 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 15:12:50.904  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 15:12:50.904  7106  7300 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 15:12:50.904  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:50.904  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:50.904  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:50.904  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:50.904  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:12:50.904  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.904  7106  7300 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286e59c8 not in the list
09-13 15:12:50.904  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.904  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.904  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:50.904  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.904  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.904  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.904  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.904  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:50.904  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:50.904  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.904  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.904  7106  7300 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 15:12:50.904  7106  7300 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 15:12:50.904  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 15:12:50.914  7106  7300 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 15:12:50.914  7106  7300 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-13 15:12:50.914  7106  7300 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 15:12:50.914  7106  7300 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 15:12:50.914  7106  7300 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 15:12:50.914  7106  7300 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 15:12:50.914  7106  7300 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-13 15:12:50.914  7106  7300 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 15:12:50.914  7106  7300 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 15:12:50.914  7106  7300 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 15:12:50.914  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-13 15:12:50.914  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 15:12:50.914  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-13 15:12:50.914  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 15:12:50.914  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 15:12:50.914  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 15:12:50.914  7106  7300 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 15:12:50.914  7106  7300 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 15:12:50.914  7106  7300 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-13 15:12:50.914  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:50.914  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:50.914  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:50.914  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:50.914  7106  7311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1414)
09-13 15:12:50.914  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.914  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:50.914  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 15:12:50.914  7106  7300 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286e59c8 not in the list
09-13 15:12:50.914  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.914  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.914  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:50.914  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:12:50.914  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.914  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.914  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.914  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:50.914  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:50.914  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.914  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.924  7106  7300 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 15:12:50.924  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:50.924  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:50.924  7106  7312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1414
09-13 15:12:50.924  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:50.924  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:50.924  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.924  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.924  7106  7300 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286e59c8 not in the list
09-13 15:12:50.924  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.924  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.924  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:50.924  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.924  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.924  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.924  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.924  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 15:12:50.924  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:50.924  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.924  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.924  7106  7300 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 15:12:50.924  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:50.924  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
09-13 15:12:50.924  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 15:12:50.924  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:50.924  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.924  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.924  7106  7300 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286e59c8 not in the list
,09-13 15:12:50.924  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.924  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.924  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:50.924  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.924  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.924  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.924  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:50.924  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:50.924  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:50.924  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.924  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.924  7106  7300 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 15:12:50.924  7106  7300 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 15:12:50.924  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-13 15:12:50.924  7106  7300 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 15:12:50.924  7106  7300 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 15:12:50.924  7106  7300 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 15:12:50.924  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 15:12:50.924  7106  7300 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 15:12:50.924  7106  7300 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 15:12:50.924  7106  7300 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 15:12:50.924  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-13 15:12:50.924  7106  7300 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 15:12:50.924  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:50.924  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:50.924  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:50.924  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:50.924  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:12:50.924  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.924  7106  7300 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286e59c8 not in the list
09-13 15:12:50.924  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.924  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.924  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:50.924  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:12:50.924  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.924  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.924  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.934  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:50.934  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:50.934  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.934  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.934  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 15:12:50.934  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.934  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.934  7106  7300 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286e59c8 not in the list
09-13 15:12:50.934  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.934  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.934  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:50.934  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:12:50.934  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.934  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.934  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.934  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:50.934  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.934  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.934  7106  7300 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286e59c8 not in the list
09-13 15:12:50.934  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:50.934  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 15:12:50.934  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:50.934  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:50.934  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.934  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.934  7106  7300 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286e59c8 not in the list
09-13 15:12:50.934  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.934  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.934  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:50.934  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.934  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.934  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.934  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.934  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:50.934  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:50.934  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.934  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.934  7106  7311 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-13 15:12:50.934  7106  7300 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 15:12:50.934  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 15:12:50.934  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 15:12:50.934  7106  7300 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 15:12:50.934  7106  7300 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 15:12:50.934  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 15:12:50.934  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 15:12:50.934  7106  7106 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 15:12:50.934  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:50.934  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 15:12:50.934  7106  7311 D BluetoothSocket: connect(): myUserId = 0
09-13 15:12:50.934  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 15:12:50.934  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 15:12:50.934  7106  7311 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 15:12:50.934  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.934  7106  7300 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 15:12:50.934  7106  7300 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286e59c8 not in the list
,09-13 15:12:50.934  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.934  7106  7106 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 15:12:50.934  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 15:12:50.934  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 15:12:50.934  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 15:12:50.934  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.934  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:50.934  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 15:12:50.934  7106  7106 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 15:12:50.934  7106  7106 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 15:12:50.934  7106  7106 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 15:12:50.934  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.944  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:50.944  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 15:12:50.944  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:50.944  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:50.944  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.944  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.944  7106  7300 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286e59c8 not in the list
09-13 15:12:50.944  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.944  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
,09-13 15:12:50.944  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:50.944  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.944  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.944  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.944  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.944  3238  3262 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:12:50.944  7106  7311 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[105]}
,09-13 15:12:50.944  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:50.944  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:50.944  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.944  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.944  7106  7300 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 15:12:50.944  7106  7300 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 15:12:50.944  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-13 15:12:50.944  7106  7313 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 15:12:50.944  7106  7313 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 15:12:50.944  7106  7300 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 15:12:50.944  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:50.944  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:50.944  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 15:12:50.944  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:50.944  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.944  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.944  7106  7300 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286e59c8 not in the list
09-13 15:12:50.944  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.944  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.944  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:50.944  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.944  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:50.944  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.944  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.944  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:50.944  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:50.944  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.944  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.944  7106  7106 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-13 15:12:50.954  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:50.954  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:50.954  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:50.954  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:50.954  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.954  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.954  7106  7300 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286e59c8 not in the list
09-13 15:12:50.954  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.954  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.954  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:50.954  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.954  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.954  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.954  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:12:50.954  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:50.954  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:50.954  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.954  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
,09-13 15:12:50.954  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:12:50.954  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:12:50.954  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:12:50.954  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:12:50.954  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:12:50.954  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.954  7106  7300 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@286e59c8 not in the list
09-13 15:12:50.954  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.954  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.954  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:12:50.954  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.954  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.954  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:12:50.954  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:12:50.954  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:12:50.954  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:12:50.954  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:12:50.954  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f075a61 not in the list
09-13 15:12:50.954  7106  7300 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 15:12:50.954  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 15:12:50.954  7106  7300 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 15:12:50.954  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 15:12:50.954  7106  7300 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 15:12:50.954  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 15:12:50.954  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 15:12:50.954  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 15:12:50.954  7106  7300 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-13 15:12:50.954  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 15:12:50.954  7106  7300 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 15:12:50.954  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 15:12:50.954  7106  7300 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 15:12:50.954  7106  7300 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 15:12:50.954  7106  7300 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 15:12:50.954  7106  7300 D io.jxcor,e.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-13 15:12:50.954  7106  7300 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 15:12:50.954  7106  7300 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 15:12:50.954  7106  7300 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 15:12:50.954  7106  7300 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-13 15:12:50.954  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:12:50.954  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@19f8045b added. We now have 2 listener(s)
09-13 15:12:50.954  7106  7300 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:12:50.954  7106  7300 D BluetoothAdapter: enable()
,09-13 15:12:50.964  7106  7300 D BluetoothAdapter: enable(): BT is already enabled..!
,09-13 15:12:50.964  1016  1473 D SecContentProvider: uri = 18 selection = isWifiEnabled,
09-13 15:12:50.964  1016  1473 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-13 15:12:50.964  1016  1473 D SecContentProvider2: mCursor = null
,09-13 15:12:50.964  1016  1473 D WifiService: setWifiEnabled: true pid=7106, uid=10170
09-13 15:12:50.964  1016  1473 W ActivityManager: Permission Denial: getCurrentUser() from pid=7106, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-13 15:12:50.964  1016  1473 W WifiService: Failed getting userId using ActivityManagerNative
09-13 15:12:50.964  1016  1473 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7106, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-13 15:12:50.964  1016  1473 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-13 15:12:50.964  1016  1473 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-13 15:12:50.964  1016  1473 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-13 15:12:50.964  1016  1473 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-13 15:12:50.964  1016  1473 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-13 15:12:50.964  1016  1473 D SettingsProvider: name = wifi_on
,09-13 15:12:50.974  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:12:50.974  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@194fc4f8 added. We now have 3 listener(s)
09-13 15:12:50.974  7106  7300 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 15:12:50.974  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-13 15:12:50.974  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24ca9dd1 added. We now have 4 listener(s)
09-13 15:12:50.974  7106  7300 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 15:12:50.974  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:12:50.974  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7011036 added. We now have 5 listener(s)
09-13 15:12:50.974  7106  7300 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 15:12:50.974  1016  1851 D SecContentProvider: uri = 18 selection = isWifiEnabled,
09-13 15:12:50.974  1016  1851 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-13 15:12:50.974  1016  1851 D SecContentProvider2: mCursor = null
,09-13 15:12:50.984  1016  1851 D WifiService: setWifiEnabled: false pid=7106, uid=10170
,09-13 15:12:50.984  1016  1851 D SettingsProvider: name = wifi_on
,09-13 15:12:50.984  1016  1128 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-13 15:12:50.984  1380  1380 I wpa_supplicant: reset timer : RESET_TIMER 0,
09-13 15:12:50.984  1380  1380 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-13 15:12:50.984  1380  1380 I wpa_supplicant: P2P: Current p2p state = IDLE
,09-13 15:12:50.994  1380  1380 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-13 15:12:50.994  7106  7300 D BluetoothAdapter: disable()
,09-13 15:12:50.994  1016  1847 D SettingsProvider: name = bluetooth_on
,09-13 15:12:50.994  1016  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 15:12:51.014  3238  3310 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-13 15:12:51.014  3238  3310 D BluetoothAdapterProperties: Setting state to 13
09-13 15:12:51.014  3238  3310 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 15:12:51.014  1016  1221 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 15:12:51.014  3238  3310 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-13 15:12:51.014  1016  1221 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-13 15:12:51.014  3238  3310 D BluetoothAdapterService: updateAdapterState state is 13
,09-13 15:12:51.024  1380  1380 I wpa_supplicant: nl80211: Received scan results (10 BSSes),
09-13 15:12:51.024  1016  1128 E WifiNative-wlan0: do suspend true
09-13 15:12:51.024  1016  1221 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:51.024  1016  1221 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:51.024  1016  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:12:51.024  3238  3238 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-13 15:12:51.024  3238  3310 D BluetoothAdapterService: Autoconnection is available 
09-13 15:12:51.024  3238  3310 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-13 15:12:51.024  3238  3310 D BluetoothAdapterService: terminating service from this receiver
09-13 15:12:51.024  3238  3238 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@68e087d, channel: 19, state: LISTENING
09-13 15:12:51.024  3238  3238 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@68e087d, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ebbe5c5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1ebde372mSocket: android.net.LocalSocket@e52c3c3 impl:android.net.LocalSocketImpl@3cb4f440 fd:FileDescriptor[80]
,09-13 15:12:51.024  3238  3238 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@e52c3c3 impl:android.net.LocalSocketImpl@3cb4f440 fd:FileDescriptor[80]
09-13 15:12:51.024  1016  1473 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-13 15:12:51.024  1016  1127 D WifiP2pService: InactiveState{ what=147461 }
,09-13 15:12:51.024  1016  1127 D WifiP2pService: P2pEnabledState{ what=147461 }
09-13 15:12:51.024  1016  1473 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:51.024  1016  1127 D WifiP2pService: DefaultState{ what=147461 }
09-13 15:12:51.024  1016  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:51.024  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 15:12:51.024  1016  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:12:51.034  3238  3310 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 15:12:51.034  3238  3310 D BluetoothAdapterProperties: mDiscovering is false
09-13 15:12:51.034  4811  4811 D BluetoothPbap: Proxy object disconnected
09-13 15:12:51.034  4811  4811 D PbapServerProfile: Bluetooth service disconnected
09-13 15:12:51.034  1016  1221 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-13 15:12:51.034  3238  3310 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-13 15:12:51.034  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-13 15:12:51.034  1016  1016 I InputMethodManagerService: [BT Setting State] State =13
09-13 15:12:51.034  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:12:51.034  7106  7300 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:12:51.034  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:51.034  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:51.034  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:12:51.034  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:12:51.034  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:12:51.034  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:12:51.034  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 15:12:51.034  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:12:51.034  7106  7300 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 15:12:51.044  7106  7300 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 15:12:51.044  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,09-13 15:12:51.044  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED,
09-13 15:12:51.044  1173  1765 D BluetoothTile:  handleUpdatestate:false name:null
09-13 15:12:51.044  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-13 15:12:51.044  1173  1173 D BluetoothTile:  getBluetoothState : 13
09-13 15:12:51.044  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:12:51.044  1173  1765 D BluetoothTile:  handleUpdatestate:false name:null
,09-13 15:12:51.044  1892  1892 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-13 15:12:51.054  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:12:51.054  1173  1765 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
09-13 15:12:51.054  4811  4811 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:12:51.054  1016  1079 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-13 15:12:51.054  1016  1474 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-13 15:12:51.054  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-13 15:12:51.064  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 15:12:51.064  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:12:51.064  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:51.064  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:51.064  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:12:51.064  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:12:51.064  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:12:51.064  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:12:51.064  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 15:12:51.064  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 15:12:51.064  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 15:12:51.074  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:12:51.074  3238  3313 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-13 15:12:51.074  3238  3313 D BluetoothAdapterProperties: Scan Mode:20
,09-13 15:12:51.074   290   290 E SMD     : DCD OFF,
09-13 15:12:51.074  3238  3310 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-13 15:12:51.074  3238  3310 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
09-13 15:12:51.074  3238  3310 E bt-btif : cmd socket is not created
09-13 15:12:51.074  3238  3315 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,09-13 15:12:51.074  7106  7311 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@53838a4, channel: -1, state: INIT
09-13 15:12:51.074  7106  7311 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@53838a4, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@d0a460d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@29c5f9c2mSocket: android.net.LocalSocket@970a3d3 impl:android.net.LocalSocketImpl@1f123b10 fd:FileDescriptor[105]
09-13 15:12:51.074  7106  7311 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@970a3d3 impl:android.net.LocalSocketImpl@1f123b10 fd:FileDescriptor[105]
09-13 15:12:51.074  7106  7311 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1414)
09-13 15:12:51.074  3238  3310 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-13 15:12:51.074  3238  5292 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-13 15:12:51.084  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:12:51.084  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:12:51.084  3238  3315 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x2  CID 0x40
,09-13 15:12:51.084  3238  3315 E bt-btif : DISCOVERY_COMP_EVT slot id:4, failed to find channle,                                       status:1, scn:0
09-13 15:12:51.084  3238  3315 W bt-btif : invalid rfc slot id: 4
,09-13 15:12:51.094  3238  3315 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-13 15:12:51.094  3238  3315 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 15:12:51.094  3238  3315 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-13 15:12:51.094  3238  3315 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 15:12:51.094  3238  3315 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 15:12:51.094  3238  3315 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-13 15:12:51.104  1016  1127 D WifiP2pService: InactiveState{ what=143375 }
,09-13 15:12:51.114  1016  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-13 15:12:51.114   279  1015 D CommandListener: Clearing all IP addresses on wlan0,
09-13 15:12:51.114  2654  2688 V NativeCrypto: Read error: ssl=0xb8041df0: I/O error during system call, Connection timed out
,09-13 15:12:51.124  1016  1130 E ConnectivityService: updateNetworkInfo()
09-13 15:12:51.124  1016  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 15:12:51.124  1016  1130 E ConnectivityService: updateNetworkInfo()
09-13 15:12:51.124  1016  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
09-13 15:12:51.124  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 15:12:51.124  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,09-13 15:12:51.124  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-13 15:12:51.124  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:51.124  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:51.124  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:51.124  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:51.134  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 1
09-13 15:12:51.134  1016  1127 D WifiP2pService: InactiveState{ what=131204 }
09-13 15:12:51.134  1016  1151 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:12:51.134  1016  1127 D WifiP2pService: P2pEnabledState{ what=131204 }
09-13 15:12:51.134  1016  1016 D RttService: SCAN_AVAILABLE : 1
09-13 15:12:51.134  1016  1127 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-13 15:12:51.134  1016  1152 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 15:12:51.144  1016  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-13 15:12:51.144  1016  1048 D WifiDisplayAdapter: onP2pDisconnected
,09-13 15:12:51.144  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 15:12:51.144  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 15:12:51.144  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 15:12:51.144  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:51.144  1016  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-13 15:12:51.144  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:51.144  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-13 15:12:51.144  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:51.144  1016  1127 D WifiP2pService: P2pDisablingState
09-13 15:12:51.144  1016  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
,09-13 15:12:51.144  1016  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
09-13 15:12:51.144  1016  1127 D WifiP2pService: P2pDisablingState{ what=147458 }
09-13 15:12:51.144  1016  1127 D WifiP2pService: p2p socket connection lost
09-13 15:12:51.154  1016  1127 D WifiP2pService: P2pDisabledState
,09-13 15:12:51.154  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-13 15:12:51.154  1016  1128 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 15:12:51.154  1016  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-13 15:12:51.154  1016  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-13 15:12:51.154  1016  1048 D WifiDisplayController: disconnect
09-13 15:12:51.154  1016  1048 D WifiDisplayController: updateConnection
09-13 15:12:51.154  1016  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-13 15:12:51.154  1016  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-13 15:12:51.154  1016  1128 E WifiNative-wlan0: do suspend true,
09-13 15:12:51.154  1016  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false],
09-13 15:12:51.154  1016  1048 D WifiDisplayAdapter: onP2pDisconnected,
09-13 15:12:51.154  1016  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
,09-13 15:12:51.154  1016  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-13 15:12:51.164  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-13 15:12:51.164  1016  1851 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-13 15:12:51.164  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-13 15:12:51.184  1016  1127 D WifiP2pService: P2pDisabledState{ what=143375 }
09-13 15:12:51.184  1016  1127 D WifiP2pService: DefaultState{ what=143375 }
,09-13 15:12:51.194  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-13 15:12:51.194  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 15:12:51.194  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-13 15:12:51.194  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:51.194  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:51.194  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:51.194  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:51.204   279  1015 D CommandListener: Clearing all IP addresses on wlan0,
09-13 15:12:51.204  1016  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:12:51.204  1016  1130 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-13 15:12:51.204  1016  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 15:12:51.204  1016  1130 V NetworkStats: updateIfacesLocked()
09-13 15:12:51.204  1016  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-13 15:12:51.204  1016  1130 V NetworkStats: performPollLocked(flags=0x1)
,09-13 15:12:51.204  1016  1130 V NetworkStats: performPollLocked() took 4ms
09-13 15:12:51.204  1016  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:12:51.204  1380  1380 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
09-13 15:12:51.204  1016  1130 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,09-13 15:12:51.214  1016  1463 I art     : Explicit concurrent mark sweep GC freed 31899(1822KB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 23MB/35MB, paused 3.186ms total 163.016ms
,09-13 15:12:51.214  4811  4811 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 15:12:51.214  2654  2688 V NativeCrypto: SSL shutdown failed: ssl=0xb8041df0: I/O error during system call, Broken pipe
,09-13 15:12:51.214  1016  1741 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:12:51.214  1016  1130 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-13 15:12:51.214  1016  1127 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-13 15:12:51.214  1173  1745 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-13 15:12:51.214  1016  1130 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-13 15:12:51.214  1016  1130 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,09-13 15:12:51.214  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-13 15:12:51.214  1447  1447 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-13 15:12:51.224  1447  1447 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-13 15:12:51.224  1016  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 15:12:51.224  1016  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-13 15:12:51.224  1016  1029 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-13 15:12:51.224  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:12:51.224  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:12:51.224  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-13 15:12:51.224  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:12:51.224  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:51.224  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-13 15:12:51.234  1016  1130 D ConnectivityService: nai.networkMonitor.doQuit()
09-13 15:12:51.234  1016  1130 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-13 15:12:51.234  1016  1130 E ConnectivityService: updateNetworkInfo()
,09-13 15:12:51.234  1016  1130 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 15:12:51.234  1016  1130 E ConnectivityService: updateNetworkInfo()
09-13 15:12:51.234  1016  1016 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-13 15:12:51.234  1016  1132 D Tethering: MasterInitialState.processMessage what=3
09-13 15:12:51.234  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 15:12:51.234  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 15:12:51.234  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 15:12:51.234  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:51.234  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:51.234  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:51.234  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:51.234  1016  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-13 15:12:51.234  1016  1125 V NetworkStats: updateIfacesLocked()
09-13 15:12:51.234  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:12:51.234  1016  1125 V NetworkStats: performPollLocked(flags=0x1)
,09-13 15:12:51.234  1016  1128 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-13 15:12:51.234  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 15:12:51.234  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-13 15:12:51.234  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
09-13 15:12:51.234  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-13 15:12:51.234  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-13 15:12:51.234  1173  1173 D StatusBar.NetworkController: updateDataNetType()
,09-13 15:12:51.234  1016  1125 V NetworkStats: performPollLocked() took 5ms
09-13 15:12:51.244  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:12:51.244  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:12:51.244  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:12:51.244  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:12:51.244  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-13 15:12:51.244  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-13 15:12:51.244  1016  1126 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-13 15:12:51.244  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:12:51.244  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-13 15:12:51.244  1016  1128 D SecContentProvider2: mCursor = null
,09-13 15:12:51.244  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-13 15:12:51.244  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 22 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,09-13 15:12:51.244  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-13 15:12:51.244  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,09-13 15:12:51.244  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 15:12:51.254  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 15:12:51.254  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 15:12:51.254  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:51.254  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:51.254  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:51.254  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:51.254  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 15:12:51.254  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:12:51.254  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:51.254  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:51.254  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:12:51.254  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:12:51.254  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:12:51.254  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:12:51.254  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:12:51.254  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-13 15:12:51.254  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 15:12:51.254  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-13 15:12:51.254  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:51.254  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:51.254  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:51.254  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:12:51.254  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:12:51.254  4811  4811 D DockEventReceiver: finishStartingService: stopping service
,09-13 15:12:51.254  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:51.264  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-13 15:12:51.264  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-13 15:12:51.264  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-13 15:12:51.264  1173  1765 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-13 15:12:51.264  1173  1173 D HotspotTile: onReceive : 0, 0
,09-13 15:12:51.264  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-13 15:12:51.264  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:12:51.264  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:51.264  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:51.264  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:12:51.264  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false,
09-13 15:12:51.264  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:12:51.264  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:12:51.264  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 15:12:51.264  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:12:51.264  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:12:51.264  4811  4811 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-13 15:12:51.264  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:12:51.264  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:12:51.264  2654  2654 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 15:12:51.264  3238  3238 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2582c4be, channel: 5, state: LISTENING
09-13 15:12:51.264  3238  3238 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2582c4be, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1610b1a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3993d91fmSocket: android.net.LocalSocket@1d15146c impl:android.net.LocalSocketImpl@5baca35 fd:FileDescriptor[82]
09-13 15:12:51.264  3238  3238 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1d15146c impl:android.net.LocalSocketImpl@5baca35 fd:FileDescriptor[82]
09-13 15:12:51.264  3238  3238 I BtOppRfcommListener: stopping Accept Thread
09-13 15:12:51.264  3238  3238 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@34226eca, channel: 12, state: LISTENING
09-13 15:12:51.264  3238  3238 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@34226eca, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ca0bed4, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2aa6e83bmSocket: android.net.LocalSocket@1c750b58 impl:android.net.LocalSocketImpl@255ad4b1 fd:FileDescriptor[88]
09-13 15:12:51.264  3238  3238 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1c750b58 impl:android.net.LocalSocketImpl@255ad4b1 fd:FileDescriptor[88]
09-13 15:12:51.264  3238  5292 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-13 15:12:51.274  3238  3310 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-13 15:12:51.274  3238  3310 D BtConfig.SecureMode: isSecureModeOn:false
09-13 15:12:51.274  3238  3310 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-13 15:12:51.274  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
09-13 15:12:51.274  3238  3310 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
09-13 15:12:51.274  4811  4811 D BluetoothNotiBroadcastReceiver: onReceive
09-13 15:12:51.274  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-13 15:12:51.274  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-13 15:12:51.274  3238  3310 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-13 15:12:51.284  3238  3238 V BluetoothOppManager: cleanUp...
,09-13 15:12:51.284  1016  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 15:12:51.284  1016  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-13 15:12:51.284  1016  1487 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:51.284  1016  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:51.284  1016  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:12:51.284  3238  3238 D HeadsetService: Received stop request...Stopping profile...
09-13 15:12:51.284  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-13 15:12:51.284  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-13 15:12:51.284  3238  3310 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-13 15:12:51.284  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd,
,09-13 15:12:51.294  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:12:51.294  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-13 15:12:51.294  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-13 15:12:51.294  1016  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 15:12:51.294  1016  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-13 15:12:51.294  4811  4811 D HeadsetProfile: Bluetooth service disconnected
,09-13 15:12:51.294  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:51.294  1016  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 15:12:51.294  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:12:51.294  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-13 15:12:51.294  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-13 15:12:51.294  3238  3310 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-13 15:12:51.294  1016  1489 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-13 15:12:51.294  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:51.294  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:51.294  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:51.294  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:51.314  7322  7322 E Zygote  : MountEmulatedStorage()
,09-13 15:12:51.314  7322  7322 E Zygote  : v2
09-13 15:12:51.314  7322  7322 I libpersona: KNOX_SDCARD checking this for 10055
09-13 15:12:51.314  7322  7322 I libpersona: KNOX_SDCARD not a persona
,09-13 15:12:51.314  7322  7322 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 15:12:51.314  1016  1489 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7322 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
09-13 15:12:51.314  1016  1028 W ActivityManager: userId = 0, bbcId = -10000,
09-13 15:12:51.314  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 15:12:51.314  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:51.314  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-13 15:12:51.314  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-13 15:12:51.314  1016  1847 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 15:12:51.314  7322  7322 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 15:12:51.314  1016  1847 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-13 15:12:51.314  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-13 15:12:51.314  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-13 15:12:51.314  3238  3310 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService,
09-13 15:12:51.314  7322  7322 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-13 15:12:51.314  1016  1847 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:51.314  1016  1847 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 15:12:51.314  1016  1847 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-13 15:12:51.324  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
09-13 15:12:51.324  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-13 15:12:51.324  3238  3310 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-13 15:12:51.324  1016  1850 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 15:12:51.324  1016  1850 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-13 15:12:51.324  1016  1850 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:51.324  1016  1850 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:51.324  1016  1850 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:12:51.324  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-13 15:12:51.324  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService,
09-13 15:12:51.324  3238  3310 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-13 15:12:51.324  1016  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-13 15:12:51.324  1016  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-13 15:12:51.324  1016  1487 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:51.324  1016  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:51.334  1016  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-13 15:12:51.334  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-13 15:12:51.334  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-13 15:12:51.334  3238  3310 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-13 15:12:51.334  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 15:12:51.334  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-13 15:12:51.334  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:51.334  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:51.334  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:12:51.334  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-13 15:12:51.334  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-13 15:12:51.334  3238  3310 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-13 15:12:51.334  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-13 15:12:51.334  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-13 15:12:51.334  3238  3310 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-13 15:12:51.334  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-13 15:12:51.334  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-13 15:12:51.334  7322  7322 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 15:12:51.334  3238  3310 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-13 15:12:51.334  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-13 15:12:51.334  7322  7322 D ActivityThread: Added TimaKeyStore provider
09-13 15:12:51.334  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-13 15:12:51.334  3238  3310 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-13 15:12:51.334  3238  3310 D BluetoothAdapterState: Stopping profile services that were post enabled
09-13 15:12:51.334  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-13 15:12:51.334  3238  3238 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-13 15:12:51.334  3238  3238 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-13 15:12:51.344  3238  3238 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-13 15:12:51.344  3238  3238 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-13 15:12:51.344  3238  3238 D A2dpService: Received stop request...Stopping profile...
,09-13 15:12:51.344  3238  3382 D A2dpStateMachine: Exit Disconnected: -1
,09-13 15:12:51.344  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
,09-13 15:12:51.354  4811  4811 D BluetoothA2dp: Proxy object disconnected
09-13 15:12:51.354  4811  4811 D A2dpProfile: Bluetooth service disconnected
09-13 15:12:51.354  1380  1380 I wpa_supplicant: Blacklist: Clear (all) 
,09-13 15:12:51.354  1016  1016 D BluetoothA2dp: Proxy object disconnected
09-13 15:12:51.354  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-13 15:12:51.354  3238  3238 D HidService: Received stop request...Stopping profile...
09-13 15:12:51.354  3238  3238 D HidService: Stopping Bluetooth HidService
09-13 15:12:51.354  3238  3238 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 15:12:51.354  3238  3238 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-13 15:12:51.354  3238  3238 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 15:12:51.354  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
,09-13 15:12:51.354  4811  4811 D BluetoothInputDevice: Proxy object disconnected
09-13 15:12:51.354  4811  4811 D HidProfile: Bluetooth service disconnected
,09-13 15:12:51.354  3238  3238 D HealthService: Received stop request...Stopping profile...
09-13 15:12:51.354  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
,09-13 15:12:51.364  3238  3238 D PanService: Received stop request...Stopping profile...
,09-13 15:12:51.364  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
09-13 15:12:51.364  1016  1016 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-13 15:12:51.364  3238  3238 D BluetoothMapService: Received stop request...Stopping profile...
,09-13 15:12:51.364  4811  4811 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 15:12:51.364  4811  4811 D PanProfile: Bluetooth service disconnected
,09-13 15:12:51.364  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
,09-13 15:12:51.374  3238  3238 D SapService: Received stop request...Stopping profile...
09-13 15:12:51.374  3238  3238 D SapService: Stopping Bluetooth SapService
09-13 15:12:51.374  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
,09-13 15:12:51.374  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-13 15:12:51.374  3238  3238 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-13 15:12:51.374  3238  3238 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-13 15:12:51.374  3238  3238 D BluetoothA2dp: Proxy object disconnected
09-13 15:12:51.374  3238  3238 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-13 15:12:51.374  3238  3383 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-13 15:12:51.374  3238  3238 I GKI_LINUX: GKI_exit_task 2 done
09-13 15:12:51.374  3238  3238 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-13 15:12:51.374  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-13 15:12:51.374  3238  3238 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-13 15:12:51.374  3238  3238 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-13 15:12:51.374  3238  3238 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-13 15:12:51.374  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-13 15:12:51.374  3238  3238 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-13 15:12:51.374  3238  3238 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-13 15:12:51.374  3238  3238 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-13 15:12:51.374  3238  3238 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 15:12:51.374  3238  3238 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 15:12:51.374  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-13 15:12:51.374  3238  3238 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-13 15:12:51.374  3238  3238 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-13 15:12:51.374  3238  3238 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-13 15:12:51.374  3238  3238 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 15:12:51.374  3238  3238 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-13 15:12:51.384  4811  4811 D BluetoothMap: Proxy object disconnected
09-13 15:12:51.384  4811  4811 D MapProfile: Bluetooth service disconnected
09-13 15:12:51.384  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-13 15:12:51.384  4811  4811 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-13 15:12:51.384  4811  4811 D SapProfile: Bluetooth service disconnected
09-13 15:12:51.384  3238  3238 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-13 15:12:51.384  3238  3238 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-13 15:12:51.384  3238  3238 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-13 15:12:51.384  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-13 15:12:51.384  3238  3238 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-13 15:12:51.384  3238  3238 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-13 15:12:51.384  3238  3238 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-13 15:12:51.384  3238  3310 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-13 15:12:51.384  3238  3310 D BluetoothAdapterProperties: Setting state to 10
09-13 15:12:51.384  3238  3310 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-13 15:12:51.384  3238  3310 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-13 15:12:51.384  3238  3310 D BluetoothAdapterService: updateAdapterState state is 10
,09-13 15:12:51.384  3238  3310 D BluetoothAdapterService: Autoconnection is available 
09-13 15:12:51.384  3238  3310 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-13 15:12:51.384  3238  3310 I BluetoothAdapterState: Entering OffState
09-13 15:12:51.384  7322  7322 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-13 15:12:51.394  1016  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-13 15:12:51.394  1436  1448 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-13 15:12:51.394  1436  1448 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 15:12:51.394  1447  1475 D BluetoothAdapter: onBluetoothStateChange: up=false
09-13 15:12:51.394  1447  1475 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-13 15:12:51.394  7106  7117 D BluetoothAdapter: onBluetoothStateChange: up=false
09-13 15:12:51.394  7106  7117 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-13 15:12:51.394  7106  7117 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-13 15:12:51.394  7106  7117 D BluetoothLeAdvertiser: Exit stop advertising
09-13 15:12:51.394  7106  7117 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-13 15:12:51.394  7106  7117 D BluetoothLeScanner: Exiting stopAllScan
,09-13 15:12:51.394  1447  1447 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-13 15:12:51.404  3238  3262 D BluetoothAdapter: onBluetoothStateChange: up=false
09-13 15:12:51.404  3238  3262 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 15:12:51.404  1447  1447 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-13 15:12:51.404  1447  1447 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-13 15:12:51.404  2654  3046 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-13 15:12:51.404  2654  3046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-13 15:12:51.404  1447  1447 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-13 15:12:51.404  1447  1447 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-13 15:12:51.404  1447  1447 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-13 15:12:51.404  1447  1447 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-13 15:12:51.404  1757  1772 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-13 15:12:51.404  1757  1772 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-13 15:12:51.414  1016  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
09-13 15:12:51.414  1016  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-13 15:12:51.414  4811  4833 D Bluetoothsap: onBluetoothStateChange: up=false
09-13 15:12:51.414  4811  4833 D Bluetoothsap: Unbinding service...
,09-13 15:12:51.414  3238  3254 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 15:12:51.414  4811  4826 D BluetoothAdapter: onBluetoothStateChange: up=false
09-13 15:12:51.414  4811  4826 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 15:12:51.414  4811  4833 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 15:12:51.414  1173  3542 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-13 15:12:51.414  1173  3542 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 15:12:51.414  4811  4826 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 15:12:51.414  1447  1447 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-13 15:12:51.414  1447  1447 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-13 15:12:51.414  4811  4833 D BluetoothMap: onBluetoothStateChange: up=false
09-13 15:12:51.414  4811  4826 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-13 15:12:51.414  1447  1447 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-13 15:12:51.414  1447  1447 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-13 15:12:51.414  1423  1476 D BluetoothAdapter: onBluetoothStateChange: up=false
09-13 15:12:51.414  1423  1476 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-13 15:12:51.414  7322  7322 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-13 15:12:51.414  7322  7322 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-13 15:12:51.414  1447  1447 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-13 15:12:51.414  7322  7322 D UserAnalysis: Create SecureDbHelper
09-13 15:12:51.414  1447  1447 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-13 15:12:51.424  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-13 15:12:51.424  1016  1016 I InputMethodManagerService: [BT Setting State] State =10
09-13 15:12:51.424  1016  1016 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-13 15:12:51.424  1447  1447 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-13 15:12:51.424  1447  1447 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-13 15:12:51.424  1447  1447 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-13 15:12:51.424  1447  1447 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-13 15:12:51.424  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-13 15:12:51.424  1447  1447 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-13 15:12:51.424  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:12:51.424  1173  1173 D BluetoothTile:  getBluetoothState : 10
09-13 15:12:51.424  1447  1447 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-13 15:12:51.424  1892  1892 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-13 15:12:51.434  1447  1447 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-13 15:12:51.434  1447  1447 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-13 15:12:51.434  4811  4811 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:12:51.434  1016  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-13 15:12:51.434  1380  1380 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-13 15:12:51.434  1016  1045 D Tethering: interfaceLinkStateChanged p2p0, false
,09-13 15:12:51.434  1016  1045 D Tethering: interfaceStatusChanged p2p0, false
09-13 15:12:51.434  1447  1447 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-13 15:12:51.434  1447  1447 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-13 15:12:51.434  7322  7322 D IntelligenceServiceApplication: onCreate()
,09-13 15:12:51.434  1016  1028 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-13 15:12:51.434  1016  1029 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-13 15:12:51.434  1447  1447 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-13 15:12:51.434  1447  1447 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-13 15:12:51.434  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:12:51.434  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-13 15:12:51.444  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:12:51.444  1447  1447 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-13 15:12:51.444  7106  7106 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-13 15:12:51.444  1447  1447 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-13 15:12:51.444  1016  1473 I ActivityManager: Killing 6271:com.samsung.android.sm/1000 (adj 15): empty #21,
09-13 15:12:51.444  1447  1447 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-13 15:12:51.444  1447  1447 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-13 15:12:51.444  1447  1447 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-13 15:12:51.444  7322  7322 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-13 15:12:51.444  1016  1473 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-13 15:12:51.454  1016  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:51.454  1016  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:51.454  1016  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:51.454  1016  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:51.454  1380  1380 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-13 15:12:51.454  1380  1380 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-13 15:12:51.454  1380  1380 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,09-13 15:12:51.464  1380  1380 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-13 15:12:51.464  1380  1380 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-13 15:12:51.464  1016  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 15:12:51.464  1016  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-13 15:12:51.464  1016  1045 D Tethering: interfaceStatusChanged wlan0, false
09-13 15:12:51.464  1016  1132 D Tethering: InitialState.processMessage what=4
09-13 15:12:51.464  1016  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 15:12:51.464  1016  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-13 15:12:51.464  1016  1132 E Tethering: No numeric data
,09-13 15:12:51.464  1016  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-13 15:12:51.464  1016  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 15:12:51.464  1016  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-13 15:12:51.464  1016  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-13 15:12:51.474  7354  7354 E Zygote  : MountEmulatedStorage()
09-13 15:12:51.474  7354  7354 I libpersona: KNOX_SDCARD checking this for 10105
09-13 15:12:51.474  7354  7354 E Zygote  : v2
09-13 15:12:51.474  7354  7354 I libpersona: KNOX_SDCARD not a persona
09-13 15:12:51.474  7354  7354 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 15:12:51.474  1016  1473 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7354 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-13 15:12:51.474  7354  7354 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 15:12:51.474  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
09-13 15:12:51.474  1016  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 15:12:51.474  1016  1125 V NetworkStats: performPollLocked(flags=0x1)
09-13 15:12:51.474  1016  1132 D Tethering: clearTetheredNotification()
09-13 15:12:51.474  7354  7354 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-13 15:12:51.474  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:12:51.474  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 15:12:51.474  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-13 15:12:51.474  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-13 15:12:51.474  1173  1173 D HotspotTile: updateTetherState():false, false
09-13 15:12:51.474  7322  7322 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-13 15:12:51.484  1016  1125 V NetworkStats: performPollLocked() took 5ms
09-13 15:12:51.484  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:12:51.484  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:12:51.484  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:12:51.484  7322  7322 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-13 15:12:51.494  7354  7354 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:12:51.494  7354  7354 D ActivityThread: Added TimaKeyStore provider
,09-13 15:12:51.604   258   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-13 15:12:51.604   258   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 15:12:51.604  7354  7373 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-13 15:12:51.604   258   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-13 15:12:51.604   258   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 15:12:51.604  7354  7373 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-13 15:12:51.684  1380  1380 I wpa_supplicant: Blacklist: Clear (all) 
,09-13 15:12:51.704  1380  1380 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,09-13 15:12:51.704  1016  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,09-13 15:12:51.704  1016  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-13 15:12:51.704  1016  1045 D Tethering: interfaceStatusChanged wlan0, false
09-13 15:12:51.704  1016  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-13 15:12:51.714  1016  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-13 15:12:51.714  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 15:12:51.714  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-13 15:12:51.714  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-13 15:12:51.714  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:51.724  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:51.724  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:51.724  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:51.724  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-13 15:12:51.724  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-13 15:12:51.724  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-13 15:12:51.724  1173  1765 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-13 15:12:51.724  1173  1173 D HotspotTile: onReceive : 1, 0
,09-13 15:12:51.724  4811  4811 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-13 15:12:51.724  1757  2196 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 15:12:51.724  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:12:51.724  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:12:51.734  1016  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 15:12:51.734  1016  1016 I ApplicationPolicy: updateDataUsageMap
,09-13 15:12:51.744  1016  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-13 15:12:51.744  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:12:51.754  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:12:51.774  7354  7354 D StrictMode: StrictMode policy violation; ~duration=165 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.io.File.exists(File.java:363)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-13 15:12:51.774  7354  7354 D StrictMode: StrictMode policy violation; ~duration=164 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 15:12:51.774  7354  7354 D StrictMode: StrictMode policy violation; ~duration=163 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 15:12:51.774  7354  7354 D StrictMode: StrictMode policy violation; ~duration=162 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.q.e.b(PG:170)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09,-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 15:12:51.774  7354  7354 D StrictMode: StrictMode policy violation; ~duration=159 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.q.k.d(PG:583)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.q.e.b(PG:170)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 15:12:51.774  7354  7354 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.io.File.exists(File.java:363)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 15:12:51.774  7354  7354 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.io.File.exists(File.java:363)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 15:12:51.774  7354  7354 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 15:12:51.774  7354  7354 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 15:12:51.784  1016  1487 I ActivityManager: Killing 6883:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
09-13 15:12:51.784  1016  1474 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-13 15:12:51.784  1016  1474 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-13 15:12:51.784  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:51.784  1016  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:51.784  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-13 15:12:51.794  4811  4811 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-13 15:12:51.794  1623  1623 I Hs20UtilService: Starting #8
09-13 15:12:51.794  1623  1650 I Hs20UtilService: Message received 5007
09-13 15:12:51.794  4811  4811 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-13 15:12:51.794  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-13 15:12:51.804  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-13 15:12:51.804  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-13 15:12:51.804  4811  4811 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-13 15:12:51.804  4811  4886 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-13 15:12:51.814  4811  4811 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-13 15:12:51.814  4811  4811 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-13 15:12:51.814  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-13 15:12:51.814  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-13 15:12:51.814  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-13 15:12:51.814  4811  4811 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-13 15:12:51.824  4811  4886 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-13 15:12:51.824  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
09-13 15:12:51.824  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:51.824  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:51.824  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:51.824  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:51.834  7384  7384 E Zygote  : MountEmulatedStorage()
09-13 15:12:51.834  7384  7384 I libpersona: KNOX_SDCARD checking this for 10064
09-13 15:12:51.834  7384  7384 E Zygote  : v2
09-13 15:12:51.834  7384  7384 I libpersona: KNOX_SDCARD not a persona
09-13 15:12:51.834  7384  7384 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 15:12:51.834  1016  1028 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7384 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 15:12:51.834  7384  7384 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 15:12:51.844  7384  7384 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 15:12:51.854  7384  7384 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:12:51.854  7384  7384 D ActivityThread: Added TimaKeyStore provider
,09-13 15:12:51.864  7354  7380 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-13 15:12:51.874  7384  7384 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-13 15:12:51.894  1016  1221 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-13 15:12:51.894  1016  1221 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:12:51.894  1016  1221 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 15:12:51.894  1016  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-13 15:12:51.894  7384  7384 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-13 15:12:51.904  7384  7384 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-13 15:12:51.924  7384  7384 D FileShare-Client: Outbound.stopDelayTimer - 
,09-13 15:12:51.924  1016  1479 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-13 15:12:51.934  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:51.934  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:51.934  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:51.934  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:51.944  7401  7401 E Zygote  : MountEmulatedStorage(),
09-13 15:12:51.944  7401  7401 E Zygote  : v2
09-13 15:12:51.944  7401  7401 I libpersona: KNOX_SDCARD checking this for 10065,
09-13 15:12:51.944  7401  7401 I libpersona: KNOX_SDCARD not a persona
,09-13 15:12:51.944  7401  7401 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-13 15:12:51.944  1016  1479 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7401 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 15:12:51.944  1016  1479 I ActivityManager: Killing 6867:com.google.android.partnersetup/u0a14 (adj 15): empty #21,
,09-13 15:12:51.954  7401  7401 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 15:12:51.954  7401  7401 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 15:12:51.964   311   311 I art     : Explicit concurrent mark sweep GC freed 8685(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 618us total 20.994ms
,09-13 15:12:51.974  7401  7401 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:12:51.974  7401  7401 D ActivityThread: Added TimaKeyStore provider
,09-13 15:12:51.984   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 570us total 18.147ms
,09-13 15:12:51.994  7401  7401 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
,09-13 15:12:52.004  1016  1221 I ActivityManager: Killing 6915:com.google.android.apps.docs/u0a87 (adj 15): empty #21,
,09-13 15:12:52.004   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 970us total 18.328ms
,09-13 15:12:52.004  1016  1487 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-13 15:12:52.004  1016  1487 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-13 15:12:52.004  1016  1487 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:12:52.004  1016  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 15:12:52.014  1016  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-13 15:12:52.014  1623  1623 I Hs20UtilService: Starting #9
,09-13 15:12:52.014  1623  1650 I Hs20UtilService: Message received 5007
,09-13 15:12:52.014  4811  4811 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-13 15:12:52.014  4811  4811 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-13 15:12:52.014  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-13 15:12:52.024  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-13 15:12:52.024  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-13 15:12:52.024  4811  4811 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-13 15:12:52.024  4811  4886 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-13 15:12:52.024  1016  1847 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-13 15:12:52.024  1016  1847 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-13 15:12:52.024  1016  1847 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:12:52.024  1016  1847 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:52.024  1016  1847 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-13 15:12:52.024  1623  1623 I Hs20UtilService: Starting #10
09-13 15:12:52.024  1623  1650 I Hs20UtilService: Message received 5011
,09-13 15:12:52.024  1016  1487 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,09-13 15:12:52.034  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:52.034  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:52.034  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:52.034  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:52.044  7416  7416 E Zygote  : MountEmulatedStorage(),
09-13 15:12:52.044  7416  7416 E Zygote  : v2
09-13 15:12:52.044  7416  7416 I libpersona: KNOX_SDCARD checking this for 1000
,09-13 15:12:52.044  7416  7416 I libpersona: KNOX_SDCARD not a persona
,09-13 15:12:52.044  7416  7416 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-13 15:12:52.044  7416  7416 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 15:12:52.044  7416  7416 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-13 15:12:52.054  1016  1487 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7416 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-13 15:12:52.064  7416  7416 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:12:52.074  7416  7416 D ActivityThread: Added TimaKeyStore provider
,09-13 15:12:52.094   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 15:12:52.094  7416  7416 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-13 15:12:52.094  7416  7416 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found ,
09-13 15:12:52.094  7416  7416 D SecurityLogAgent: StateMachine : Current State = 1
,09-13 15:12:52.094  7416  7416 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-13 15:12:52.104  1016  1463 I ActivityManager: Killing 6935:com.sec.pcw.device/1000 (adj 15): empty #21
,09-13 15:12:52.104  1016  1850 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:12:52.104  1016  1850 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:52.104  1016  1850 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 15:12:52.114  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:12:52.114  1016  1016 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 15:12:52.114  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
09-13 15:12:52.114  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,09-13 15:12:52.114  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:52.114  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:52.114  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:52.114  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:52.124  7432  7432 E Zygote  : MountEmulatedStorage()
,09-13 15:12:52.124  7432  7432 E Zygote  : v2
09-13 15:12:52.124  1016  1016 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7432 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-13 15:12:52.124  7432  7432 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 15:12:52.124  7432  7432 I libpersona: KNOX_SDCARD checking this for 10102
,09-13 15:12:52.124  7432  7432 I libpersona: KNOX_SDCARD not a persona
,09-13 15:12:52.134  7432  7432 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 15:12:52.134  7432  7432 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,09-13 15:12:52.144  7432  7432 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:12:52.154  7432  7432 D ActivityThread: Added TimaKeyStore provider
,09-13 15:12:52.164  7432  7432 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-13 15:12:52.314  1016  1045 D Tethering: interfaceRemoved wlan0
09-13 15:12:52.314  1016  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-13 15:12:52.364  7432  7452 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-13 15:12:52.364  7432  7452 I Babel_SMS: MmsConfig.loadMmsSettings
,09-13 15:12:52.374  7432  7452 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-13 15:12:52.374  7432  7452 I Babel_SMS: MmsConfig.loadFromDatabase,
,09-13 15:12:52.384  7432  7452 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
09-13 15:12:52.384  7432  7452 I Babel_SMS: MmsConfig.loadFromResources
,09-13 15:12:52.384  7432  7452 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-13 15:12:52.384  7432  7452 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-13 15:12:52.394  1016  1850 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,09-13 15:12:52.394  1016  1850 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
09-13 15:12:52.394  1016  1850 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:12:52.394  1016  1850 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 15:12:52.394  1016  1850 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-13 15:12:52.424  7432  7432 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 15:12:52.424  7432  7432 I Babel_Crash: startup - clean
,09-13 15:12:52.444  1016  1847 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:12:52.454  1016  1847 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:52.454  1016  1847 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 15:12:52.454  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:12:52.454  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:52.454  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 15:12:52.464  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:12:52.464  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:52.464  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 15:12:52.464  1016  1016 W ActivityManager: userId = 0, bbcId = -10000,
09-13 15:12:52.464  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-13 15:12:52.464  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 15:12:52.464  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:52.464  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:52.464  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 15:12:52.474  7432  7432 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 15:12:52.474  7432  7432 W AudioCapabilities: Unsupported mime audio/evrc
,09-13 15:12:52.474  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:52.474  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-13 15:12:52.474  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
09-13 15:12:52.474  1016  1045 D Tethering: interfaceRemoved p2p0
09-13 15:12:52.474  1016  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-13 15:12:52.474  7432  7432 W AudioCapabilities: Unsupported mime audio/qcelp
,09-13 15:12:52.474  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:12:52.474  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:52.474  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 15:12:52.484  7432  7432 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-13 15:12:52.484  7432  7432 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-13 15:12:52.484  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:52.484  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:52.484  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 15:12:52.484  7432  7432 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-13 15:12:52.484  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:52.484  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:52.484  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 15:12:52.484  7432  7432 W AudioCapabilities: Unsupported mime audio/x-ima
,09-13 15:12:52.484  7432  7432 W AudioCapabilities: Unsupported mime audio/qcelp
,09-13 15:12:52.484  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:12:52.484  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:52.484  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
09-13 15:12:52.494  7432  7432 W AudioCapabilities: Unsupported mime audio/evrc
,09-13 15:12:52.494  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:52.494  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:52.494  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 15:12:52.494  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:52.494  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:52.494  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 15:12:52.494  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:52.494  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:52.494  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 15:12:52.494  1016  1016 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:52.504  1016  1016 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:52.504  1016  1016 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-13 15:12:52.504  7432  7432 W VideoCapabilities: Unsupported mime video/wvc1
,09-13 15:12:52.504  7432  7432 W VideoCapabilities: Unsupported mime video/x-ms-wmv
09-13 15:12:52.504  4811  4811 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 15:12:52.504  1016  1850 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-13 15:12:52.504  1016  1850 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-13 15:12:52.504  1016  1850 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:52.504  1016  1850 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:52.504  1016  1850 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-13 15:12:52.514  2654  2654 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 15:12:52.514  4811  4811 D DockEventReceiver: finishStartingService: stopping service
,09-13 15:12:52.514  7432  7432 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-13 15:12:52.524  4811  4811 D BluetoothNotiBroadcastReceiver: onReceive
,09-13 15:12:52.524  7432  7432 W VideoCapabilities: Unsupported mime video/wvc1
,09-13 15:12:52.524  7432  7432 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-13 15:12:52.524  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-13 15:12:52.524  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-13 15:12:52.524  7432  7432 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-13 15:12:52.534  7432  7432 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-13 15:12:52.534  7432  7432 W VideoCapabilities: Unsupported mime video/mp43
,09-13 15:12:52.544  1016  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-13 15:12:52.544  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-13 15:12:52.544  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:52.544  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:52.544  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-13 15:12:52.544  1623  1623 I Hs20UtilService: Starting #11
,09-13 15:12:52.544  1623  1650 I Hs20UtilService: Message received 5011
,09-13 15:12:52.544  7416  7416 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-13 15:12:52.544  7416  7416 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-13 15:12:52.544  7416  7416 D SecurityLogAgent: StateMachine : Current State = 1
09-13 15:12:52.544  7416  7416 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-13 15:12:52.544  7432  7432 W VideoCapabilities: Unsupported mime video/sorenson
,09-13 15:12:52.554  1016  1487 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-13 15:12:52.554  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:52.554  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:52.554  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:52.554  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:52.564  7432  7432 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-13 15:12:52.564  7457  7457 E Zygote  : MountEmulatedStorage()
,09-13 15:12:52.564  7457  7457 I libpersona: KNOX_SDCARD checking this for 1000
09-13 15:12:52.564  7457  7457 E Zygote  : v2
09-13 15:12:52.564  7457  7457 I libpersona: KNOX_SDCARD not a persona
09-13 15:12:52.564  7457  7457 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 15:12:52.564  7457  7457 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-13 15:12:52.564  1016  1487 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7457 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-13 15:12:52.574  7457  7457 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 15:12:52.584  7457  7457 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:12:52.584  7457  7457 D ActivityThread: Added TimaKeyStore provider
09-13 15:12:52.584  7432  7432 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-13 15:12:52.604  7457  7457 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-13 15:12:52.604  7457  7457 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-13 15:12:52.614  7457  7457 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-13 15:12:52.614  7432  7432 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 15:12:52.614  7432  7432 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 15:12:52.614  7432  7432 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 15:12:52.624  7432  7432 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 15:12:52.624  1016  1463 I ActivityManager: Killing 6831:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-13 15:12:52.624  7432  7432 I vclib   : onServiceConnected
,09-13 15:12:52.624  7457  7457 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-13 15:12:52.624  7457  7457 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-13 15:12:52.624  7457  7457 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-13 15:12:52.624  7457  7457 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-13 15:12:52.634  1016  1479 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
09-13 15:12:52.634  1016  1479 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
09-13 15:12:52.634  1016  1479 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
09-13 15:12:52.634  1016  1479 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,09-13 15:12:52.634  7457  7472 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
09-13 15:12:52.634  1016  1479 I ActivityManager: Killing 7010:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,09-13 15:12:52.644  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-13 15:12:52.654  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:52.654  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:52.654  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:52.654  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:52.664  7474  7474 E Zygote  : MountEmulatedStorage()
,09-13 15:12:52.664  7474  7474 E Zygote  : v2
09-13 15:12:52.664  7474  7474 I libpersona: KNOX_SDCARD checking this for 10001
09-13 15:12:52.664  7474  7474 I libpersona: KNOX_SDCARD not a persona
,09-13 15:12:52.664  7474  7474 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 15:12:52.664  1016  1016 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7474 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 15:12:52.664  7474  7474 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 15:12:52.664  7474  7474 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 15:12:52.684  7474  7474 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:12:52.684  7474  7474 D ActivityThread: Added TimaKeyStore provider
,09-13 15:12:52.754  1016  1079 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-13 15:12:52.754  1016  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:52.754  1016  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:52.754  1016  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:52.754  1016  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:52.764  7491  7491 E Zygote  : MountEmulatedStorage()
,09-13 15:12:52.764  1016  1079 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7491 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-13 15:12:52.764  7491  7491 E Zygote  : v2
09-13 15:12:52.764  7491  7491 I libpersona: KNOX_SDCARD checking this for 1000
09-13 15:12:52.764  7491  7491 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 15:12:52.764  7491  7491 I libpersona: KNOX_SDCARD not a persona
09-13 15:12:52.764  1016  1079 I ActivityManager: Killing 7034:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21,
,09-13 15:12:52.774  7491  7491 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 15:12:52.774  7491  7491 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 15:12:52.784  7491  7491 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:12:52.794  7491  7491 D ActivityThread: Added TimaKeyStore provider
,09-13 15:12:52.824  7491  7491 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-13 15:12:52.944  7491  7491 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-13 15:12:52.954  7491  7491 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-13 15:12:52.954  7491  7491 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-13 15:12:52.954  7491  7491 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-13 15:12:52.954  7491  7491 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-13 15:12:52.964  7491  7491 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-13 15:12:52.964  1016  1850 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-13 15:12:52.964  1016  1850 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:52.964  1016  1850 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:52.964  1016  1850 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:52.964  1016  1850 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:52.974  7506  7506 E Zygote  : MountEmulatedStorage(),
09-13 15:12:52.974  7506  7506 I libpersona: KNOX_SDCARD checking this for 10008
09-13 15:12:52.974  7506  7506 E Zygote  : v2
09-13 15:12:52.974  7506  7506 I libpersona: KNOX_SDCARD not a persona
09-13 15:12:52.974  7506  7506 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 15:12:52.974  1016  1850 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7506 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-13 15:12:52.984  1016  1850 I ActivityManager: Killing 7061:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,09-13 15:12:52.984  7506  7506 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 15:12:52.984  7506  7506 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-13 15:12:53.004  7506  7506 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:12:53.004  7506  7506 D ActivityThread: Added TimaKeyStore provider
,09-13 15:12:53.064  1016  1479 I ActivityManager: Killing 7084:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,09-13 15:12:53.064  1016  1221 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-13 15:12:53.064  1016  1221 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-13 15:12:53.064  1016  1221 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:53.064  1016  1221 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 15:12:53.064  1016  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 15:12:53.094  3828  7521 I iu.SyncManager: SYNC; picasa accounts
,09-13 15:12:53.094   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 15:12:53.094  3828  3828 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,09-13 15:12:53.104  1016  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-13 15:12:53.114  1016  1479 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 15:12:53.114  1016  1479 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,09-13 15:12:53.114  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:12:53.114  1016  1479 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 15:12:53.114  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 15:12:53.124  3828  3828 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 15:12:53.124  3828  3828 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,09-13 15:12:53.134  2828  2828 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Sep 13 15:12:53 GMT+02:00 2016
,09-13 15:12:53.134  1016  1851 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent,
09-13 15:12:53.134  1016  1851 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-13 15:12:53.134  1016  1851 W ActivityManager: userId = 0, bbcId = -10000,
,09-13 15:12:53.144  1016  1851 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:53.144  1016  1851 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-13 15:12:53.144  2828  2828 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-13 15:12:53.154  2828  2828 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-13 15:12:53.154  2828  2828 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-13 15:12:53.154  1016  1847 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-13 15:12:53.154  1016  1847 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:53.154  1016  1847 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:53.154  1016  1847 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:53.154  2828  2828 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
09-13 15:12:53.154  1016  1847 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:53.164  2828  7523 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-13 15:12:53.164  2828  7523 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
09-13 15:12:53.164  2828  7523 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
09-13 15:12:53.164  2828  7523 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-13 15:12:53.174  7524  7524 E Zygote  : MountEmulatedStorage()
,09-13 15:12:53.174  7524  7524 I libpersona: KNOX_SDCARD checking this for 10031
09-13 15:12:53.174  7524  7524 E Zygote  : v2
09-13 15:12:53.174  7524  7524 I libpersona: KNOX_SDCARD not a persona
,09-13 15:12:53.184  7524  7524 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 15:12:53.184  1016  1847 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7524 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,09-13 15:12:53.184  7524  7524 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 15:12:53.184  7524  7524 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 15:12:53.194  2828  2828 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-13 15:12:53.214  7524  7524 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:12:53.224  7524  7524 D ActivityThread: Added TimaKeyStore provider
,09-13 15:12:53.254  7524  7524 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-13 15:12:53.254  1016  1463 I ActivityManager: Killing 6994:com.android.mms/u0a41 (adj 15): empty #21
,09-13 15:12:53.274  1016  1221 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-13 15:12:53.274  1016  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:53.274  1016  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:53.274  1016  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:53.274  1016  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:53.284  2766  7540 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-13 15:12:53.284  2766  7540 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-13 15:12:53.284  2766  7540 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-13 15:12:53.284  2766  7540 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-13 15:12:53.294  7541  7541 E Zygote  : MountEmulatedStorage()
09-13 15:12:53.294  7541  7541 E Zygote  : v2
09-13 15:12:53.294  7541  7541 I libpersona: KNOX_SDCARD checking this for 10032
09-13 15:12:53.294  7541  7541 I libpersona: KNOX_SDCARD not a persona
,09-13 15:12:53.294  7541  7541 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 15:12:53.294  2766  7540 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
09-13 15:12:53.294  1016  1221 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7541 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 15:12:53.294  7541  7541 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-13 15:12:53.304  7541  7541 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-13 15:12:53.324  7541  7541 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:12:53.334  7541  7541 D ActivityThread: Added TimaKeyStore provider
,09-13 15:12:53.344  1016  1029 D CountryDetector: No listener is left
,09-13 15:12:53.384  7541  7556 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-13 15:12:53.384  7541  7556 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-13 15:12:53.394  7541  7541 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-13 15:12:53.394  7541  7556 D SPPClientService: PushLog.txt file is not deleted.
,09-13 15:12:53.394  7541  7556 D SPPClientService: PushLog.txt file is not deleted.
09-13 15:12:53.394  7541  7556 D SPPClientService: ============PushLog. stop!
,09-13 15:12:53.394  1016  1079 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-13 15:12:53.394  1016  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:53.394  1016  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:53.394  1016  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:53.394  1016  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:53.414  1016  1079 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7558 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 15:12:53.414  1016  1850 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-13 15:12:53.414  7558  7558 E Zygote  : MountEmulatedStorage()
09-13 15:12:53.414  1016  1850 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
09-13 15:12:53.414  7558  7558 E Zygote  : v2
09-13 15:12:53.414  7558  7558 I libpersona: KNOX_SDCARD checking this for 10036
09-13 15:12:53.414  7558  7558 I libpersona: KNOX_SDCARD not a persona
,09-13 15:12:53.414  1016  1850 W ActivityManager: userId = 0, bbcId = -10000,
09-13 15:12:53.414  1016  1850 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-13 15:12:53.414  1016  1850 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
09-13 15:12:53.414  7558  7558 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 15:12:53.424  7558  7558 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 15:12:53.424  7558  7558 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,09-13 15:12:53.444  7558  7558 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:12:53.444  7558  7558 D ActivityThread: Added TimaKeyStore provider
,09-13 15:12:53.444  7541  7564 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-13 15:12:53.474  1016  1487 I ActivityManager: Killing 7141:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,09-13 15:12:53.494  7558  7558 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@3a72745a
,09-13 15:12:53.504  7558  7558 I SA      : [SSP] onCreated
,09-13 15:12:53.524  7558  7558 I SA      : [TPM] There is no property file
,09-13 15:12:53.524  7558  7558 I SA      : [SCU] isHaveSA() - false
,09-13 15:12:53.524  7558  7558 I SA      : [TPM] getModelProperty : null
,09-13 15:12:53.524  7558  7558 I SA      : [TPM] getCSCProperty : null
,09-13 15:12:53.524  7558  7558 I SA      : [DM] FLOATING AMOLED FEATURE: true
,09-13 15:12:53.534  7558  7558 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-13 15:12:53.534  7558  7558 I SA      : [DM] TFT FEATURE: false
,09-13 15:12:53.534  7558  7558 I SA      : [DM] init START
,09-13 15:12:53.534  7558  7558 I SA      : [DM] This device is not a Vodafone
,09-13 15:12:53.544  7558  7558 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,09-13 15:12:53.544  7558  7558 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,09-13 15:12:53.544  7558  7558 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,09-13 15:12:53.544  7558  7558 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-13 15:12:53.544  7558  7558 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,09-13 15:12:53.544  7558  7558 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,09-13 15:12:53.544  7558  7558 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-13 15:12:53.544  7558  7558 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-13 15:12:53.554  7558  7558 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,09-13 15:12:53.554  7558  7558 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,09-13 15:12:53.554  7558  7558 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,09-13 15:12:53.554  7558  7558 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,09-13 15:12:53.554  7558  7558 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-13 15:12:53.554  7558  7558 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,09-13 15:12:53.554  7558  7558 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,09-13 15:12:53.554  7558  7558 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,09-13 15:12:53.554  7558  7558 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
09-13 15:12:53.554  7558  7558 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,09-13 15:12:53.554  7558  7558 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,09-13 15:12:53.554  7558  7558 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-13 15:12:53.554  7558  7558 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-13 15:12:53.564  7558  7558 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-13 15:12:53.564  7558  7558 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,09-13 15:12:53.564  7558  7558 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,09-13 15:12:53.564  7558  7558 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,09-13 15:12:53.564  7558  7558 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
09-13 15:12:53.564  7558  7558 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
,09-13 15:12:53.564  7558  7558 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-13 15:12:53.564  7558  7558 I SA      : [SCU] isHaveSA() - false
09-13 15:12:53.564  7558  7558 I SA      : support phone number id : false
09-13 15:12:53.564  7558  7558 I SA      : [DM] Supports Ref Jpn : true
,09-13 15:12:53.564  7558  7558 I SA      : [DM] init END
09-13 15:12:53.564  7558  7558 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-13 15:12:53.574  7558  7558 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-13 15:12:53.574  7558  7558 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-13 15:12:53.574  7558  7558 I SA      : [SLFUCHKMGR] constructor called
,09-13 15:12:53.584  7558  7558 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-13 15:12:53.584  7558  7558 I SA      : [OR] == isSIMCardReady false ==
,09-13 15:12:53.584  7558  7558 I SA      : [SCU] == networkStateCheck == false
09-13 15:12:53.584  7558  7558 I SA      : [OR] onReceive END
,09-13 15:12:53.584  1016  1029 I ActivityManager: Killing 7156:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,09-13 15:12:53.584  1232  1232 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-13 15:12:53.594  1793  1793 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-13 15:12:53.594  2634  2645 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,09-13 15:12:53.594  1793  1793 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-13 15:12:53.594  1793  1793 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
09-13 15:12:53.594  1793  1793 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
09-13 15:12:53.594  1793  1793 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-13 15:12:53.604  1793  1793 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-13 15:12:53.604  1793  1793 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-13 15:12:53.604  1016  1489 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-13 15:12:53.604  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-13 15:12:53.604  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:53.604  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:53.604  1016  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:53.624  7580  7580 E Zygote  : MountEmulatedStorage()
09-13 15:12:53.624  7580  7580 E Zygote  : v2
09-13 15:12:53.624  7580  7580 I libpersona: KNOX_SDCARD checking this for 10077
09-13 15:12:53.624  7580  7580 I libpersona: KNOX_SDCARD not a persona
,09-13 15:12:53.624  7580  7580 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 15:12:53.624  7580  7580 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 15:12:53.624  1016  1489 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7580 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 15:12:53.624  7580  7580 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-13 15:12:53.634  7580  7580 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:12:53.644  7580  7580 D ActivityThread: Added TimaKeyStore provider
,09-13 15:12:53.804  1016  1221 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-13 15:12:53.804  1016  1221 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-13 15:12:53.804  1016  1221 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:12:53.804  1016  1221 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 15:12:53.804  1016  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-13 15:12:53.814  1016  1479 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-13 15:12:53.814  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:53.814  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:53.814  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:53.814  1016  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:53.824  7599  7599 E Zygote  : MountEmulatedStorage(),
09-13 15:12:53.824  7599  7599 E Zygote  : v2
09-13 15:12:53.824  7599  7599 I libpersona: KNOX_SDCARD checking this for 10110
,09-13 15:12:53.824  7599  7599 I libpersona: KNOX_SDCARD not a persona
,09-13 15:12:53.824  7599  7599 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-13 15:12:53.834  1016  1479 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7599 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 15:12:53.834  1016  1847 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,09-13 15:12:53.834  1016  1847 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-13 15:12:53.834  7599  7599 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 15:12:53.834  1016  1847 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:53.834  1016  1847 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 15:12:53.834  1016  1847 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
09-13 15:12:53.834  7599  7599 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,09-13 15:12:53.834  7432  7598 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-13 15:12:53.844   311   311 I art     : Explicit concurrent mark sweep GC freed 8692(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 742us total 22.873ms
,09-13 15:12:53.844  1016  1487 I ActivityManager: Killing 7189:com.wsomacp/u0a23 (adj 15): empty #21
,09-13 15:12:53.854  7599  7599 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:12:53.854  7599  7599 D ActivityThread: Added TimaKeyStore provider
,09-13 15:12:53.874   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 693us total 28.894ms
,09-13 15:12:53.894   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 702us total 19.821ms
,09-13 15:12:54.024  1016  1221 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-13 15:12:54.044  1016  1489 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-13 15:12:54.044  1016  1489 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-13 15:12:54.044  1016  1489 D SecContentProvider2: mCursor = null
,09-13 15:12:54.044  1016  1489 D WifiService: setWifiEnabled: true pid=7106, uid=10170
,09-13 15:12:54.044  1016  1489 W ActivityManager: Permission Denial: getCurrentUser() from pid=7106, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-13 15:12:54.044  1016  1489 W WifiService: Failed getting userId using ActivityManagerNative
09-13 15:12:54.044  1016  1489 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7106, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-13 15:12:54.044  1016  1489 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-13 15:12:54.044  1016  1489 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-13 15:12:54.044  1016  1489 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-13 15:12:54.044  1016  1489 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-13 15:12:54.044  1016  1489 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-13 15:12:54.044  1016  1489 D SettingsProvider: name = wifi_on
,09-13 15:12:54.054  1016  1128 E WifiHW  : ##################### set firmware type 0 #####################,
,09-13 15:12:54.064  1016  1851 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 15:12:54.064  1016  1851 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4267, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-13 15:12:54.064  1016  1851 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 15:12:54.064  1016  1851 D BatteryService: stay LED for charging
,09-13 15:12:54.064  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 15:12:54.074  1016  1016 I MotionRecognitionService: Plugged
,09-13 15:12:54.074  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 15:12:54.074  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
09-13 15:12:54.074  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
09-13 15:12:54.074  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 15:12:54.074  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
09-13 15:12:54.074   290   290 E SMD     : DCD OFF
,09-13 15:12:54.084  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 15:12:54.094   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 15:12:54.104  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-13 15:12:54.104  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 15:12:54.184   258   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-13 15:12:54.184   258   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 15:12:54.184  7599  7619 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-13 15:12:54.184   258   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-13 15:12:54.184   258   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 15:12:54.184  7599  7619 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-13 15:12:54.204   258   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-13 15:12:54.204   258   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 15:12:54.204  7599  7620 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-13 15:12:54.204   258   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-13 15:12:54.204   258   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 15:12:54.204  7599  7620 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-13 15:12:54.224  7599  7599 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-13 15:12:54.224  7599  7599 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 15:12:54.224  7599  7599 I GAv4    :   adb logcat -s GAv4
,09-13 15:12:54.244  7599  7599 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-13 15:12:54.244  1016  1474 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-13 15:12:54.254  7599  7599 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-13 15:12:54.264  7599  7622 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-13 15:12:54.454  1016  1045 D Tethering: interfaceAdded wlan0
,09-13 15:12:54.454  1016  1132 E Tethering: No numeric data
,09-13 15:12:54.454  1016  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-13 15:12:54.454  1016  1132 D Tethering: clearTetheredNotification()
,09-13 15:12:54.454  1016  1125 V NetworkStats: performPollLocked(flags=0x1)
,09-13 15:12:54.454  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:12:54.454  1016  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 15:12:54.454  1016  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-13 15:12:54.464  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 15:12:54.464  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-13 15:12:54.464  1016  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-13 15:12:54.464  1016  1132 D Tethering: InitialState.processMessage what=4
,09-13 15:12:54.464  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-13 15:12:54.464  1173  1173 D HotspotTile: updateTetherState():false, false
,09-13 15:12:54.464  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:12:54.464  1016  1125 V NetworkStats: performPollLocked() took 4ms
,09-13 15:12:54.464  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:12:54.464  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-13 15:12:54.464  1016  1132 E Tethering: No numeric data
09-13 15:12:54.464  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-13 15:12:54.464  1016  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 15:12:54.464  1173  1173 D HotspotTile: updateTetherState():false, false
09-13 15:12:54.464  1016  1132 D Tethering: clearTetheredNotification()
09-13 15:12:54.464  1016  1125 V NetworkStats: performPollLocked(flags=0x1)
09-13 15:12:54.464  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:12:54.474  1016  1045 D Tethering: interfaceAdded p2p0
,09-13 15:12:54.474  1016  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
09-13 15:12:54.474   279  1015 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-13 15:12:54.474  1016  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-13 15:12:54.474  1016  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-13 15:12:54.474  1016  1045 D Tethering: interfaceStatusChanged p2p0, false
09-13 15:12:54.474  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 15:12:54.474  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-13 15:12:54.474   279  1015 D SoftapController: Softap fwReload - Ok
09-13 15:12:54.474  1016  1125 V NetworkStats: performPollLocked() took 5ms
09-13 15:12:54.474  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:12:54.474  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:12:54.474  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:12:54.474   279  1015 D CommandListener: Setting iface cfg
09-13 15:12:54.474   279  1015 D CommandListener: Trying to bring down wlan0
,09-13 15:12:54.474   279  1015 D CommandListener: Clearing all IP addresses on wlan0
,09-13 15:12:54.484  1016  1128 E WifiHW  : supplicant_name : p2p_supplicant
,09-13 15:12:54.484  1016  1079 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,09-13 15:12:54.484  1016  1079 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:12:54.484  1016  1079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 15:12:54.484  1016  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-13 15:12:54.484  1016  1128 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-13 15:12:54.504  4811  4811 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-13 15:12:54.504  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-13 15:12:54.504  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 15:12:54.504  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-13 15:12:54.504  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:54.504  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-13 15:12:54.504  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:54.504  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:54.504  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:54.504  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-13 15:12:54.504  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-13 15:12:54.504  1173  1765 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-13 15:12:54.514  1173  1173 D HotspotTile: onReceive : 2, 0
,09-13 15:12:54.514  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-13 15:12:54.514  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:12:54.524  7599  7599 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-13 15:12:54.544  7599  7599 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 6487-6489)
,09-13 15:12:54.544  7599  7599 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-13 15:12:54.574  7599  7599 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {68e087d},
09-13 15:12:54.574  7599  7599 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-13 15:12:54.574  7599  7599 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 15:12:54.574  7643  7643 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-13 15:12:54.574  7643  7643 I wpa_supplicant: Successfully initialized wpa_supplicant
09-13 15:12:54.574  7643  7643 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-13 15:12:54.594  7599  7599 I cr.BrowserStartup: Initializing chromium process, singleProcess=true,
,09-13 15:12:54.594  7599  7599 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 15:12:54.604  7599  7599 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-13 15:12:54.604  7643  7643 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,09-13 15:12:54.614   374   374 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7643
,09-13 15:12:54.614   374   374 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
09-13 15:12:54.614  7643  7643 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-13 15:12:54.614  7643  7643 I wpa_supplicant: ssSupport state is = 1
09-13 15:12:54.614  7643  7643 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-13 15:12:54.614  7643  7643 I SecureStorage: [INFO]: SPID(0x00000000)Processing data,
09-13 15:12:54.614   374   374 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7643
09-13 15:12:54.614   374   374 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,09-13 15:12:54.614  7599  7599 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
09-13 15:12:54.614  7599  7599 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-13 15:12:54.614  7599  7599 I Adreno-EGL: Build Date: 04/06/15 Mon
09-13 15:12:54.614  7599  7599 I Adreno-EGL: Local Branch: 
09-13 15:12:54.614  7599  7599 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-13 15:12:54.614  7599  7599 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-13 15:12:54.614  7599  7599 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC,
,09-13 15:12:54.684  7599  7659 W cr.media: Requires BLUETOOTH permission
,09-13 15:12:54.694  7599  7599 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 15:12:54.704  7599  7599 I NSApplication: Starting up...
,09-13 15:12:54.704  1016  1029 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-13 15:12:54.714  1016  1221 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-13 15:12:54.714  1016  1463 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-13 15:12:54.714  1016  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-13 15:12:54.714  1016  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:54.714  1016  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:54.714  1016  1463 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:54.744  7664  7664 E Zygote  : MountEmulatedStorage(),
09-13 15:12:54.744  7664  7664 E Zygote  : v2
09-13 15:12:54.744  7664  7664 I libpersona: KNOX_SDCARD checking this for 10117
,09-13 15:12:54.744  7664  7664 I libpersona: KNOX_SDCARD not a persona,
,09-13 15:12:54.744  1016  1463 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7664 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-13 15:12:54.744  1016  1463 I ActivityManager: Killing 7228:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,09-13 15:12:54.754  7664  7664 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 15:12:54.754  7664  7664 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 15:12:54.754  7664  7664 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-13 15:12:54.784  7664  7664 D TimaKeyStoreProvider: TimaSignature is unavailable,
,09-13 15:12:54.784  7664  7664 D ActivityThread: Added TimaKeyStore provider
,09-13 15:12:54.794   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,09-13 15:12:54.794  7643  7643 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,09-13 15:12:54.804  7664  7664 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 15:12:54.844  7643  7643 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-13 15:12:54.844  7643  7643 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-13 15:12:54.854  7643  7643 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
09-13 15:12:54.854   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7643,
09-13 15:12:54.854   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,09-13 15:12:54.854  7643  7643 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-13 15:12:54.854  7643  7643 I wpa_supplicant: ssSupport state is = 1
09-13 15:12:54.854  7643  7643 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-13 15:12:54.854  7643  7643 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-13 15:12:54.854  7643  7643 E wpa_supplicant: SIM READ ERROR
09-13 15:12:54.854  7643  7643 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-13 15:12:54.854  7643  7643 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-13 15:12:54.854  7643  7643 E wpa_supplicant: SIM READ ERROR
09-13 15:12:54.854  7643  7643 I wpa_supplicant: Blacklist: Clear (all) 
,09-13 15:12:54.854  7643  7643 I wpa_supplicant: wpa_default_ap_write_once
09-13 15:12:54.854  7643  7643 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-13 15:12:54.854  7643  7643 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-13 15:12:54.854  7643  7643 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-13 15:12:54.854  7643  7643 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-13 15:12:54.854  7643  7643 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-13 15:12:54.854  7643  7643 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-13 15:12:54.864  1016  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 15:12:54.864  1016  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-13 15:12:54.864  1016  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-13 15:12:55.004  7643  7643 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-13 15:12:55.094   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 15:12:55.154  1016  1850 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-13 15:12:55.164  1016  1850 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:55.164  1016  1850 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:55.164  1016  1850 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:55.164  1016  1850 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:55.174  7686  7686 E Zygote  : MountEmulatedStorage()
,09-13 15:12:55.174  7686  7686 E Zygote  : v2
09-13 15:12:55.174  7686  7686 I libpersona: KNOX_SDCARD checking this for 10121
09-13 15:12:55.174  7686  7686 I libpersona: KNOX_SDCARD not a persona
,09-13 15:12:55.174  7686  7686 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-13 15:12:55.174  1016  1850 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7686 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
09-13 15:12:55.174  7686  7686 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 15:12:55.174  1016  1850 I ActivityManager: Killing 7245:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,09-13 15:12:55.174  7686  7686 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 15:12:55.194  7686  7686 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:12:55.194  7686  7686 D ActivityThread: Added TimaKeyStore provider,
,09-13 15:12:55.214  7686  7686 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
09-13 15:12:55.214  7686  7686 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-13 15:12:55.214  7686  7686 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-13 15:12:55.214  7643  7643 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-13 15:12:55.214  7643  7643 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-13 15:12:55.234  7686  7686 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-13 15:12:55.234  7643  7643 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
09-13 15:12:55.234  7686  7686 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
09-13 15:12:55.234   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7643
09-13 15:12:55.234   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-13 15:12:55.234  7643  7643 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-13 15:12:55.234  7643  7643 I wpa_supplicant: ssSupport state is = 1
,09-13 15:12:55.244  7686  7686 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
09-13 15:12:55.244  1016  1474 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
09-13 15:12:55.244  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:55.244  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:55.244  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:55.244  1016  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-13 15:12:55.244  7643  7643 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-13 15:12:55.244  7643  7643 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-13 15:12:55.254  1016  1474 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7705 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
09-13 15:12:55.254  1016  1474 I ActivityManager: Killing 7264:com.android.calendar/u0a131 (adj 15): empty #21
,09-13 15:12:55.264  7643  7643 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,09-13 15:12:55.264   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7643
09-13 15:12:55.264   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-13 15:12:55.264  7643  7643 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-13 15:12:55.264  7643  7643 I wpa_supplicant: ssSupport state is = 1
,09-13 15:12:55.264  7643  7643 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-13 15:12:55.264  7643  7643 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-13 15:12:55.264  7643  7643 E wpa_supplicant: SIM READ ERROR
09-13 15:12:55.264  7643  7643 I wpa_supplicant: wpa_default_ap_write_once
09-13 15:12:55.264  7643  7643 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-13 15:12:55.264  7643  7643 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-13 15:12:55.264  1016  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-13 15:12:55.264  1016  1045 D Tethering: interfaceStatusChanged p2p0, false
09-13 15:12:55.264  1016  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-13 15:12:55.264  7705  7705 E Zygote  : MountEmulatedStorage()
09-13 15:12:55.264  7705  7705 E Zygote  : v2
09-13 15:12:55.264  7705  7705 I libpersona: KNOX_SDCARD checking this for 10141
09-13 15:12:55.264  7705  7705 I libpersona: KNOX_SDCARD not a persona
,09-13 15:12:55.264  1016  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-13 15:12:55.264  1016  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-13 15:12:55.264  1016  1045 D Tethering: interfaceStatusChanged p2p0, false
09-13 15:12:55.264  7705  7705 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 15:12:55.264  7705  7705 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 15:12:55.264  7705  7705 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 15:12:55.284  7705  7705 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:12:55.284  7705  7705 D ActivityThread: Added TimaKeyStore provider
,09-13 15:12:55.294  7705  7705 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-13 15:12:55.304  7705  7705 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 15:12:55.304  7705  7705 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 15:12:55.304  7705  7705 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-13 15:12:55.314  7643  7643 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-13 15:12:55.314  7643  7643 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-13 15:12:55.344  1016  1028 D RCPManagerService: exchangeData() failure , invalid userId,
,09-13 15:12:55.364  1016  1079 D RCPManagerService: exchangeData() failure , invalid userId
,09-13 15:12:55.384  7643  7643 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-13 15:12:55.384  7643  7643 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,09-13 15:12:55.384  7643  7643 I wpa_supplicant: Skip scan - bUseNetwork false
,09-13 15:12:55.394  1016  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-13 15:12:55.394  1016  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-13 15:12:55.394  7643  7643 I wpa_supplicant: HOTSPOT20_ENABLE called
09-13 15:12:55.394  7643  7643 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-13 15:12:55.394  7643  7643 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-13 15:12:55.394  7643  7643 E wpa_supplicant: SIM READ ERROR
09-13 15:12:55.394  7643  7643 I wpa_supplicant: Blacklist: Clear (all) 
,09-13 15:12:55.404  1016  1847 D RCPManagerService: exchangeData() failure , invalid userId
,09-13 15:12:55.424  1016  1479 D RCPManagerService: exchangeData() failure , invalid userId
,09-13 15:12:55.434  7643  7643 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-13 15:12:55.444  7643  7643 I wpa_supplicant: Skip scan - bUseNetwork false
,09-13 15:12:55.454  1016  1128 D WifiConfigStore: Loading config and enabling all networks 
,09-13 15:12:55.454  1016  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-13 15:12:55.454  1016  1045 D Tethering: interfaceStatusChanged p2p0, false
09-13 15:12:55.454  1016  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-13 15:12:55.454  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 15:12:55.454  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 15:12:55.454  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 15:12:55.454  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:55.454  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:55.454  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:55.454  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:55.464  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-13 15:12:55.464  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-13 15:12:55.464  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-13 15:12:55.464  1173  1765 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-13 15:12:55.464  1173  1173 D HotspotTile: onReceive : 3, 0
,09-13 15:12:55.464  4811  4811 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-13 15:12:55.474  1016  1097 V AlarmManager: waitForAlarm result :4
,09-13 15:12:55.474  1016  1128 E WifiConfigStore: Not a HS20
,09-13 15:12:55.474  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:12:55.474  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:12:55.474  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:55.474  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:55.474  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:12:55.474  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:12:55.474  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:12:55.474  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:12:55.474  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:12:55.474  1016  1128 D WifiNative-wlan0: callSECApiInt - ID [65]
09-13 15:12:55.474  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:12:55.474  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 15:12:55.484  1016  1128 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-13 15:12:55.484  7643  7643 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-13 15:12:55.484  7643  7643 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-13 15:12:55.484  7643  7643 I wpa_supplicant: reset timer : RESET_TIMER 0
09-13 15:12:55.484  7643  7643 I wpa_supplicant: P2P: Current p2p state = IDLE
09-13 15:12:55.484  7643  7643 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-13 15:12:55.484  7643  7643 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-13 15:12:55.484  7643  7643 I wpa_supplicant: First Scan Start
09-13 15:12:55.484  7643  7643 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-13 15:12:55.484  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:12:55.484  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:12:55.484  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:55.484  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:55.484  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:12:55.484  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:12:55.484  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:12:55.484  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:12:55.484  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:12:55.484  1016  1128 D WifiNative-wlan0: Setting external_sim to 1
,09-13 15:12:55.484  1016  1128 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 15:12:55.484  1016  1128 I WifiNative-HAL: startHal
09-13 15:12:55.484  1016  1128 E wifi    : getStaticLongField sWifiHalHandle 0x9f5d388c
09-13 15:12:55.484  1016  1128 I WifiNative-HAL: Could not start hal
,09-13 15:12:55.484  1016  1128 E WifiNative-wlan0: do suspend true
,09-13 15:12:55.494  1016  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-13 15:12:55.494  1016  1127 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-13 15:12:55.494   279  1015 D CommandListener: Setting iface cfg
09-13 15:12:55.494   279  1015 D CommandListener: Trying to bring up p2p0
,09-13 15:12:55.494  1016  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-13 15:12:55.494  1016  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-13 15:12:55.494  1016  1128 E WifiNative-wlan0: invaild command id : 215
,09-13 15:12:55.494  7432  7432 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:12:55.494  7643  7643 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-13 15:12:55.494  7643  7643 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-13 15:12:55.504  7643  7643 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-13 15:12:55.504  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:12:55.504  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:12:55.504  1016  1128 E WifiStateMachine: Failed to set frequency band 0
09-13 15:12:55.504  1016  1127 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-13 15:12:55.504  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-13 15:12:55.504  1016  1128 D SecContentProvider2: mCursor = null
,09-13 15:12:55.504  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 3
09-13 15:12:55.504  1016  1127 D WifiP2pService: P2pEnablingState
09-13 15:12:55.504  1016  1151 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 15:12:55.504  1016  1127 D WifiP2pService: P2pEnablingState{ what=143376 }
09-13 15:12:55.504  1016  1151 I WifiNative-HAL: startHal
09-13 15:12:55.504  1016  1127 D WifiP2pService: DefaultState{ what=143376 }
09-13 15:12:55.504  1016  1151 E wifi    : getStaticLongField sWifiHalHandle 0x9e5939bc
,09-13 15:12:55.504  1016  1127 D WifiP2pService: P2pEnablingState{ what=147457 }
09-13 15:12:55.504  1016  1151 I WifiNative-HAL: Could not start hal
09-13 15:12:55.504  1016  1127 D WifiP2pService: P2p socket connection successful
09-13 15:12:55.504  1016  1151 E WifiScanningService: could not start HAL
09-13 15:12:55.504  1016  1127 D WifiP2pService: P2pEnabledState
09-13 15:12:55.504  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-13 15:12:55.504  1016  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-13 15:12:55.504  1016  1128 D SecContentProvider2: mCursor = null
,09-13 15:12:55.504  1016  1473 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
09-13 15:12:55.504  1016  1016 D RttService: SCAN_AVAILABLE : 3
09-13 15:12:55.504  1016  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-13 15:12:55.504  1016  1489 D RCPManagerService: exchangeData() failure , invalid userId
09-13 15:12:55.504  1016  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:55.504  1016  1130 E ConnectivityService: updateNetworkInfo()
09-13 15:12:55.504  1016  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:55.504  1016  1152 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 15:12:55.504  1016  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:55.514  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-13 15:12:55.514  1016  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-13 15:12:55.514  1016  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-13 15:12:55.514  1016  1048 D WifiDisplayController: disconnect
09-13 15:12:55.514  1016  1474 D RCPManagerService: exchangeData() failure , invalid userId,
09-13 15:12:55.514  1016  1048 D WifiDisplayController: updateConnection
09-13 15:12:55.514  1016  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-13 15:12:55.514  1016  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-13 15:12:55.524  7732  7732 E Zygote  : MountEmulatedStorage()
09-13 15:12:55.524  7732  7732 E Zygote  : v2
09-13 15:12:55.524  7732  7732 I libpersona: KNOX_SDCARD checking this for 10068
09-13 15:12:55.524  7732  7732 I libpersona: KNOX_SDCARD not a persona
,09-13 15:12:55.524  7732  7732 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 15:12:55.524  1016  1473 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7732 uid=10068 gids={50068, 9997} abi=armeabi-v7a
09-13 15:12:55.524  7732  7732 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 15:12:55.524  7732  7732 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-13 15:12:55.524  1016  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-13 15:12:55.524  1016  1048 D WifiDisplayAdapter: onP2pDisconnected
09-13 15:12:55.524  1016  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-13 15:12:55.524  1016  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-13 15:12:55.534  1016  1127 D WifiNative-p2p0: p2pGetDeviceAddress
09-13 15:12:55.534  1016  1127 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,09-13 15:12:55.534  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-13 15:12:55.534  1016  1479 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-13 15:12:55.534  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-13 15:12:55.534  1016  1127 D WifiP2pService: DeviceAddress: 0a:75:42
09-13 15:12:55.534  1016  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-13 15:12:55.534  1016  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-13 15:12:55.534  1016  1048 D WifiDisplayController:  primary type: 10-0050F204-5
09-13 15:12:55.534  1016  1048 D WifiDisplayController:  secondary type: null
09-13 15:12:55.534  1016  1048 D WifiDisplayController:  wps: 0
09-13 15:12:55.534  1016  1048 D WifiDisplayController:  grpcapab: 0
09-13 15:12:55.534  1016  1048 D WifiDisplayController:  devcapab: 0
09-13 15:12:55.534  1016  1048 D WifiDisplayController:  status: 3
09-13 15:12:55.534  1016  1048 D WifiDisplayController:  wfdInfo: null
09-13 15:12:55.534  1016  1048 D WifiDisplayController:  groupownerAddress: null
09-13 15:12:55.534  1016  1048 D WifiDisplayController:  GOdeviceName: null
09-13 15:12:55.534  1016  1048 D WifiDisplayController:  interfaceAddress: 
09-13 15:12:55.534  1016  1048 D WifiDisplayController:  SConnectInfo : null
,09-13 15:12:55.544  7732  7732 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:12:55.544  7732  7732 D ActivityThread: Added TimaKeyStore provider
,09-13 15:12:55.544  1016  1079 D RCPManagerService: exchangeData() failure , invalid userId,
,09-13 15:12:55.554  1016  1847 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-13 15:12:55.564  1016  1127 D WifiP2pService: sending p2p persistent groups changed broadcast
09-13 15:12:55.564  1016  1847 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:55.564  1016  1847 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:55.564  1016  1847 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:55.564  1016  1847 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:55.574  7732  7732 D BadgeProvider: onCreate,
09-13 15:12:55.574  7732  7732 D BadgeProvider: DatabaseHelper
,09-13 15:12:55.574  7747  7747 E Zygote  : MountEmulatedStorage()
09-13 15:12:55.574  7747  7747 I libpersona: KNOX_SDCARD checking this for 10009
09-13 15:12:55.574  7747  7747 E Zygote  : v2
09-13 15:12:55.574  7747  7747 I libpersona: KNOX_SDCARD not a persona
09-13 15:12:55.574  7747  7747 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 15:12:55.574  1016  1847 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7747 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
09-13 15:12:55.574  1016  1847 I ActivityManager: Killing 6955:com.android.vending/u0a26 (adj 15): empty #21
09-13 15:12:55.574  1016  1847 I ActivityManager: Killing 7204:com.android.defcontainer/u0a3 (adj 15): empty #22
,09-13 15:12:55.584  7747  7747 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 15:12:55.584  7747  7747 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-13 15:12:55.594  1016  1127 D WifiP2pService: InactiveState
,09-13 15:12:55.594  1016  1127 D WifiP2pService: InactiveState{ what=143376 }
09-13 15:12:55.594  1016  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
09-13 15:12:55.594  7643  7643 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-13 15:12:55.624  7747  7747 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:12:55.624  7747  7747 D ActivityThread: Added TimaKeyStore provider
,09-13 15:12:55.694  1016  1851 I ActivityManager: Killing 7384:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,09-13 15:12:55.704  1016  1079 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-13 15:12:55.704  1016  1079 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-13 15:12:55.704  1016  1079 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:12:55.704  1016  1079 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:55.704  1016  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-13 15:12:55.704  1623  1623 I Hs20UtilService: Starting #12
,09-13 15:12:55.704  1623  1650 I Hs20UtilService: Message received 5011
,09-13 15:12:55.704  7416  7416 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-13 15:12:55.704  7416  7416 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-13 15:12:55.704  7416  7416 D SecurityLogAgent: StateMachine : Current State = 1
09-13 15:12:55.704  7416  7416 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-13 15:12:55.724  1016  1489 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-13 15:12:55.724  1016  1489 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-13 15:12:55.724  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:12:55.724  1016  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:55.724  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-13 15:12:55.724  1623  1623 I Hs20UtilService: Starting #13
,09-13 15:12:55.724  1623  1650 I Hs20UtilService: Message received 5011
,09-13 15:12:55.724  1016  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,09-13 15:12:55.724  1016  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
,09-13 15:12:55.734  1016  1128 E WifiNative-wlan0: invaild command id : 215
,09-13 15:12:55.734  7416  7416 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-13 15:12:55.734  7416  7416 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-13 15:12:55.734  7416  7416 D SecurityLogAgent: StateMachine : Current State = 1
09-13 15:12:55.734  7416  7416 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-13 15:12:55.744  1016  1473 I art     : Explicit concurrent mark sweep GC freed 53849(3MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.748ms total 159.059ms
,09-13 15:12:55.744  1016  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
09-13 15:12:55.744  1016  1487 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-13 15:12:55.744   279  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-13 15:12:55.744   279  1011 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-13 15:12:55.754  1016  1851 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-13 15:12:55.754  4811  4811 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-13 15:12:55.754  4811  4811 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-13 15:12:55.754  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-13 15:12:55.754  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-13 15:12:55.754  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-13 15:12:55.754  4811  4811 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-13 15:12:55.764  1016  1487 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-13 15:12:55.764  4811  4886 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-13 15:12:55.764  7732  7741 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
09-13 15:12:55.764  1016  1487 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.app.FileShareClient/com.samsung.android.app.FileShareClient.ClientBroadcastReceiver}
09-13 15:12:55.764  1016  1487 W BroadcastQueue: android.os.TransactionTooLargeException
09-13 15:12:55.764  1016  1487 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 15:12:55.764  1016  1487 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 15:12:55.764  1016  1487 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-13 15:12:55.764  1016  1487 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-13 15:12:55.764  1016  1487 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-13 15:12:55.764  1016  1487 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
09-13 15:12:55.764  1016  1487 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-13 15:12:55.764  1016  1487 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
09-13 15:12:55.764  1016  1487 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,09-13 15:12:55.764  1016  1487 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-13 15:12:55.764  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:55.764  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:55.764  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:12:55.764  1016  1487 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:12:55.784  7766  7766 E Zygote  : MountEmulatedStorage()
,09-13 15:12:55.784  7766  7766 E Zygote  : v2
09-13 15:12:55.784  7766  7766 I libpersona: KNOX_SDCARD checking this for 10064
09-13 15:12:55.784  7766  7766 I libpersona: KNOX_SDCARD not a persona
,09-13 15:12:55.784  1016  1487 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7766 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-13 15:12:55.784  7766  7766 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 15:12:55.784  1016  1079 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-13 15:12:55.784  7766  7766 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 15:12:55.784  7766  7766 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 15:12:55.794  7732  7741 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-13 15:12:55.794  7732  7741 D BadgeProvider: sendNotify, [notify] : null
09-13 15:12:55.794  7732  7741 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-13 15:12:55.794  7732  7741 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-13 15:12:55.794  7732  7741 D BadgeProvider: update, [UpdateCount] : 1
09-13 15:12:55.794  1490  1490 D Launcher.Model: reloadBadges entered.
,09-13 15:12:55.814  7766  7766 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:12:55.814  7766  7766 D ActivityThread: Added TimaKeyStore provider
,09-13 15:12:55.814  1016  1042 W libprocessgroup: failed to open /acct/uid_10064/pid_7384/cgroup.procs: No such file or directory
,09-13 15:12:55.824  7766  7766 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-13 15:12:55.834  7766  7766 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
,09-13 15:12:55.834  7766  7766 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-13 15:12:55.854  7766  7766 D FileShare-Client: Outbound.stopDelayTimer - 
,09-13 15:12:55.864  7401  7401 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-13 15:12:55.864  1016  1847 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:12:55.864  1016  1847 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 15:12:55.864  1016  1847 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-13 15:12:55.874  1016  1850 I ActivityManager: Killing 7322:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-13 15:12:56.094   327   327 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 15:12:56.404  5944  5944 D FactoryTest: Not factory mode
,09-13 15:12:56.404  5944  5944 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-13 15:12:56.404  5944  5944 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-13 15:12:56.404  5944  5944 D MTPRx   : still no open session command from host, so toast
,09-13 15:12:56.404  5944  5944 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
09-13 15:12:56.404  5944  5944 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-13 15:12:56.414  5944  5944 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:118361,
09-13 15:12:56.414  1016  1479 E PersonaManagerService: inState():  stateMachine is null !!
09-13 15:12:56.414  1016  1479 I PersonaManagerService: PersonaId don't exist
09-13 15:12:56.414  1016  1479 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-13 15:12:56.414  1016  1479 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,09-13 15:12:56.414  1016  1479 W ActivityManager: userId = 0, bbcId = -10000,
09-13 15:12:56.414  1016  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 15:12:56.414  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings,
,09-13 15:12:56.424  1016  1479 W ActivityManager: mDVFSHelper.acquire(),
,09-13 15:12:56.444  1016  1479 D PersonaManager: isKioskContainerExistOnDevice
,09-13 15:12:56.454  1016  1479 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-13 15:12:56.454  1016  1479 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-13 15:12:56.454  1016  1479 D InputDispatcher: Focused application set to: xxxx
,09-13 15:12:56.454  1016  1479 D InputDispatcher: Focus left window: 7106
,09-13 15:12:56.454  5944  5944 E MTPRx   : started activity for popup
,09-13 15:12:56.454  1016  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-13 15:12:56.454  1016  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-13 15:12:56.474  5944  5944 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,09-13 15:12:56.474  5944  5944 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,09-13 15:12:56.474  5944  5944 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-13 15:12:56.474  5944  5944 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 15:12:56.484  5944  5944 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-13 15:12:56.484  5944  5944 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-13 15:12:56.504  5944  5944 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-13 15:12:56.504  1016  1479 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
09-13 15:12:56.504  1016  1479 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-13 15:12:56.504  1016  1479 D InputDispatcher: Focused application set to: xxxx
,09-13 15:12:56.504  1016  1479 D InputDispatcher: Focus entered window: 7106
,09-13 15:12:56.504  1016  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-13 15:12:56.504  1016  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-13 15:12:56.514  1016  1028 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
09-13 15:12:56.514  1016  1028 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@2d34e79e attribute=null, token = android.os.BinderProxy@34481791
,09-13 15:12:56.544  5944  5944 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-13 15:12:56.554  5944  5944 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-13 15:12:56.554  5944  5944 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-13 15:12:56.574  7106  7106 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-13 15:12:56.574  7106  7106 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-13 15:12:56.574  7106  7106 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-13 15:12:56.574  7106  7106 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-13 15:12:56.574  1016  1221 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-13 15:12:56.574  1016  1221 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-13 15:12:56.574  1016  1221 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-13 15:12:56.574  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-13 15:12:56.574  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,09-13 15:12:56.594  7106  7106 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 15:12:56.594  7106  7106 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-13 15:12:56.594  7106  7106 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1affcbf3 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@7223609, 16908290=android.view.AbsSavedState$1@7223609}, android:focusedViewId=100}]}]
09-13 15:12:56.594  7106  7106 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-13 15:12:56.594  7106  7106 V ActivityThread: updateVisibility : ActivityRecord{2f98779d token=android.os.BinderProxy@4495e47 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-13 15:12:56.594  7106  7106 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 15:12:56.594  7106  7106 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-13 15:12:56.594  7106  7106 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@4495e47 time:118547
,09-13 15:12:56.604  1016  1474 D PersonaManager: isKioskContainerExistOnDevice
,09-13 15:12:56.684  7643  7643 I wpa_supplicant: nl80211: Received scan results (26 BSSes),
09-13 15:12:56.684  7643  7643 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-13 15:12:56.684  7643  7643 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-13 15:12:56.684  7643  7643 I wpa_supplicant: Trying to associate with  'G700',
09-13 15:12:56.684  7643  7643 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-13 15:12:56.684  7643  7643 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-13 15:12:56.684  1016  7723 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-13 15:12:56.684  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-13 15:12:56.684  1016  1128 D SecContentProvider2: mCursor = null
,09-13 15:12:56.824  7643  7643 E wpa_supplicant: Cmd 35605 not handled
,09-13 15:12:56.824  7643  7643 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-13 15:12:56.824  7643  7643 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-13 15:12:56.824  1016  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 15:12:56.824  1016  1045 D Tethering: interfaceStatusChanged wlan0, false
09-13 15:12:56.824  7643  7643 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-13 15:12:56.824  1016  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-13 15:12:56.824  7643  7643 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-13 15:12:56.824  7643  7643 I wpa_supplicant: Associated with F4.99.3E,
09-13 15:12:56.834  7643  7643 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-13 15:12:56.834  7643  7643 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE,
,09-13 15:12:56.834  1016  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 15:12:56.834  1016  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-13 15:12:56.834  1016  1045 D Tethering: interfaceStatusChanged wlan0, false
09-13 15:12:56.834  1016  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-13 15:12:56.834  7643  7643 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-13 15:12:56.834  1016  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
09-13 15:12:56.834  1016  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-13 15:12:56.834  1016  1045 D Tethering: interfaceStatusChanged wlan0, false
09-13 15:12:56.834  1016  1045 D Tethering: interfaceLinkStateChanged wlan0, true
09-13 15:12:56.834  1016  1045 D Tethering: interfaceStatusChanged wlan0, true
,09-13 15:12:56.834  1016  1132 E Tethering: No numeric data
09-13 15:12:56.834  1016  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-13 15:12:56.834  1016  1132 D Tethering: clearTetheredNotification()
,09-13 15:12:56.834  1016  1125 V NetworkStats: performPollLocked(flags=0x1)
09-13 15:12:56.834  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:12:56.834  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-13 15:12:56.834  1173  1173 D HotspotTile: updateTetherState():false, false
09-13 15:12:56.834  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 15:12:56.834  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-13 15:12:56.834  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-13 15:12:56.834  1016  1128 D SecContentProvider2: mCursor = null
,09-13 15:12:56.844  1016  1125 V NetworkStats: performPollLocked() took 4ms
,09-13 15:12:56.844  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:12:56.844  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-13 15:12:56.844  1016  1128 D SecContentProvider2: mCursor = null
09-13 15:12:56.844  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:12:56.844  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:12:56.864  7643  7643 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-13 15:12:56.864  7643  7643 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-13 15:12:56.864  7643  7643 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-13 15:12:56.864  7643  7643 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-13 15:12:56.864  7643  7643 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 15:12:56.864  7643  7643 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-13 15:12:56.864  7643  7643 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,09-13 15:12:56.864  7643  7643 I wpa_supplicant: Blacklist: Clear (temp) 
09-13 15:12:56.864  7643  7643 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-13 15:12:56.864  1016  1045 D Tethering: interfaceLinkStateChanged wlan0, true
09-13 15:12:56.864  1016  1045 D Tethering: interfaceStatusChanged wlan0, true
09-13 15:12:56.864  1016  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-13 15:12:56.864  1016  1128 D WifiNative-wlan0: callSECApiVoid - ID [50],
,09-13 15:12:56.864  1016  1128 E WifiConfigStore: setLastSelectedConfiguration -1
,09-13 15:12:56.864  1016  1128 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-13 15:12:56.864  1016  1130 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-13 15:12:56.864  1016  1130 E ConnectivityService: updateNetworkInfo()
09-13 15:12:56.864  1016  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-13 15:12:56.864  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 15:12:56.864  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-13 15:12:56.864  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 15:12:56.864  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:56.864  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:56.864  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:56.864  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:56.874  1016  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 15:12:56.874  1016  1489 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-13 15:12:56.874  1016  1489 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-13 15:12:56.874  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:12:56.874  1016  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:56.874  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-13 15:12:56.884  1623  1623 I Hs20UtilService: Starting #14
,09-13 15:12:56.884  4811  4811 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-13 15:12:56.884  1016  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 15:12:56.884  4811  4811 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-13 15:12:56.884  1623  1650 I Hs20UtilService: Message received 5007
,09-13 15:12:56.884  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-13 15:12:56.884  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-13 15:12:56.884  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-13 15:12:56.884  4811  4811 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-13 15:12:56.884  4811  4886 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-13 15:12:56.894   279  1015 D CommandListener: Setting iface cfg
,09-13 15:12:56.894  1016  1128 E WifiStateMachine: Start Dhcp Watchdog 2
,09-13 15:12:56.894  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-13 15:12:56.894  1016  1128 D SecContentProvider2: mCursor = null
,09-13 15:12:56.904  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 15:12:56.904  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-13 15:12:56.904  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-13 15:12:56.904  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:56.904  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:56.914  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:56.914  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:56.914  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-13 15:12:56.914  1016  1128 D SecContentProvider2: mCursor = null
,09-13 15:12:56.914  1016  1128 E WifiNative-wlan0: do suspend false
,09-13 15:12:56.914  1016  1127 D WifiP2pService: InactiveState{ what=143375 }
,09-13 15:12:56.914  1016  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-13 15:12:57.054  1016  1851 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-13 15:12:57.054  1016  1851 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-13 15:12:57.054  1016  1851 D SecContentProvider2: mCursor = null
,09-13 15:12:57.064  1016  1851 D WifiService: setWifiEnabled: false pid=7106, uid=10170
,09-13 15:12:57.064  1016  1851 D SettingsProvider: name = wifi_on
,09-13 15:12:57.064  1016  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 15:12:57.074   290   290 E SMD     : DCD OFF
,09-13 15:12:57.084  1016  1128 E WifiNative-wlan0: do suspend true
,09-13 15:12:57.094   327   327 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,09-13 15:12:57.104  1016  1127 D WifiP2pService: InactiveState{ what=143375 },
09-13 15:12:57.104  1016  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-13 15:12:57.114   279  1015 D CommandListener: Clearing all IP addresses on wlan0,
,09-13 15:12:57.114  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 15:12:57.114  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 15:12:57.114  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 15:12:57.114  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:57.114  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:57.114  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:57.114  1016  1130 E ConnectivityService: updateNetworkInfo()
,09-13 15:12:57.114  1016  1130 E ConnectivityService: updateNetworkInfo()
09-13 15:12:57.114  1016  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 15:12:57.114   279  1015 E Netd    : no such netId 503
09-13 15:12:57.114  1016  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,09-13 15:12:57.114  1016  1128 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-13 15:12:57.114  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-13 15:12:57.114  1016  1127 D WifiP2pService: InactiveState{ what=131204 }
09-13 15:12:57.114  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:57.114  1016  1127 D WifiP2pService: P2pEnabledState{ what=131204 }
09-13 15:12:57.124  1016  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:12:57.124  1016  1130 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
09-13 15:12:57.124  1016  1130 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-13 15:12:57.124  1016  1130 V NetworkStats: updateIfacesLocked()
,09-13 15:12:57.124  1016  1127 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-13 15:12:57.124  1016  1130 V NetworkStats: performPollLocked(flags=0x1)
09-13 15:12:57.124  1016  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 15:12:57.124  1016  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-13 15:12:57.124  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 1
,09-13 15:12:57.124  1016  1151 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:12:57.124  1016  1130 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-13 15:12:57.124  1016  1130 V NetworkStats: performPollLocked() took 5ms
09-13 15:12:57.124  1016  1016 D RttService: SCAN_AVAILABLE : 1
09-13 15:12:57.124  1016  1152 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:12:57.124  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 15:12:57.124  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 15:12:57.124  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 15:12:57.124  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:57.124  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:57.124  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:57.124  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:57.134  1016  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-13 15:12:57.134  1016  1048 D WifiDisplayAdapter: onP2pDisconnected
09-13 15:12:57.134  1016  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
,09-13 15:12:57.134  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:12:57.134  1016  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
09-13 15:12:57.134  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:57.134  1016  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-13 15:12:57.134  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-13 15:12:57.134  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-13 15:12:57.134  1016  7783 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:12:57.134  1016  1130 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,09-13 15:12:57.134  1016  1130 D ConnectivityService: nai.networkMonitor.doQuit()
09-13 15:12:57.134  1016  1130 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-13 15:12:57.134  1016  1130 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-13 15:12:57.134  1016  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-13 15:12:57.134  1016  1130 E ConnectivityService: updateNetworkInfo()
09-13 15:12:57.134  1016  1130 E ConnectivityService: updateNetworkInfo()
09-13 15:12:57.134  1623  1623 I Hs20UtilService: Starting #15
,09-13 15:12:57.134  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:12:57.134  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:12:57.134  1623  1650 I Hs20UtilService: Message received 5007
09-13 15:12:57.134  7786  7786 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-13 15:12:57.144  1016  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-13 15:12:57.144  1016  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false,
09-13 15:12:57.144  1016  7783 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-13 15:12:57.144  1016  1048 D WifiDisplayController: disconnect
09-13 15:12:57.144  1016  1048 D WifiDisplayController: updateConnection
,09-13 15:12:57.144  1016  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-13 15:12:57.144  1016  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-13 15:12:57.144  1016  1127 D WifiP2pService: P2pDisablingState
09-13 15:12:57.144  1016  1127 D WifiP2pService: P2pDisablingState{ what=147458 }
09-13 15:12:57.144  1016  1127 D WifiP2pService: p2p socket connection lost,
09-13 15:12:57.144  1016  1127 D WifiP2pService: P2pDisabledState
09-13 15:12:57.144  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-13 15:12:57.144  1016  1128 E WifiNative-wlan0: do suspend true
,09-13 15:12:57.144  7786  7786 I dhcpcd  : version 5.5.6 starting
,09-13 15:12:57.144  1016  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-13 15:12:57.144  1016  1048 D WifiDisplayAdapter: onP2pDisconnected
09-13 15:12:57.144  1016  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-13 15:12:57.144  1016  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-13 15:12:57.144  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-13 15:12:57.144  1016  1489 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-13 15:12:57.144  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-13 15:12:57.154  4811  4811 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-13 15:12:57.154  4811  4811 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-13 15:12:57.154  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-13 15:12:57.154  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-13 15:12:57.154  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-13 15:12:57.154  4811  4811 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-13 15:12:57.154  4811  4886 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-13 15:12:57.154  4811  4811 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-13 15:12:57.154  4811  4811 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-13 15:12:57.164  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-13 15:12:57.174  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-13 15:12:57.174  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-13 15:12:57.174  4811  4811 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-13 15:12:57.174  7766  7766 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
09-13 15:12:57.174  7786  7786 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
09-13 15:12:57.174  1016  1127 D WifiP2pService: P2pDisabledState{ what=143375 }
09-13 15:12:57.174  7766  7766 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-13 15:12:57.174  1016  1127 D WifiP2pService: DefaultState{ what=143375 }
09-13 15:12:57.174  7766  7766 D FileShare-Client: Outbound.stopDelayTimer - 
09-13 15:12:57.174  4811  4886 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-13 15:12:57.184   279  1015 D CommandListener: Clearing all IP addresses on wlan0
,09-13 15:12:57.184  7643  7643 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED,
09-13 15:12:57.194  7401  7401 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-13 15:12:57.194  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-13 15:12:57.194  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-13 15:12:57.194  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 15:12:57.194  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 15:12:57.194  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:57.194  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:57.194  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:57.194  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:57.204  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-13 15:12:57.204  1016  1128 D SecContentProvider2: mCursor = null
,09-13 15:12:57.204  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-13 15:12:57.204  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 15:12:57.204  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 15:12:57.204  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:57.204  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:57.204  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:57.204  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:57.214  4811  4811 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-13 15:12:57.214  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-13 15:12:57.214  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 15:12:57.214  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-13 15:12:57.214  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:57.214  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:57.214  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:12:57.214  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:57.214  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-13 15:12:57.214  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-13 15:12:57.214  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-13 15:12:57.214  1173  1765 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-13 15:12:57.224  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 15:12:57.224  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:12:57.224  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:57.224  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,09-13 15:12:57.224  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:12:57.224  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:12:57.224  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:12:57.224  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:12:57.224  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 15:12:57.224  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:12:57.224  1173  1173 D HotspotTile: onReceive : 0, 0
09-13 15:12:57.224  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 15:12:57.224  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 15:12:57.224  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:12:57.224  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:12:57.224  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:12:57.224  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:12:57.224  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:12:57.224  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:12:57.224  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:12:57.224  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:12:57.224  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:12:57.224  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 15:12:57.224  1016  1221 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-13 15:12:57.224  1016  1221 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-13 15:12:57.224  1016  1221 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:12:57.224  1016  1221 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:57.224  1016  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-13 15:12:57.234  1623  1623 I Hs20UtilService: Starting #16
,09-13 15:12:57.234  1623  1650 I Hs20UtilService: Message received 5007
,09-13 15:12:57.234  4811  4811 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
09-13 15:12:57.234  4811  4811 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-13 15:12:57.234  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-13 15:12:57.244  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-13 15:12:57.244  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-13 15:12:57.244  4811  4811 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-13 15:12:57.244  4811  4886 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-13 15:12:57.244  7786  7786 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-13 15:12:57.244  7786  7786 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-13 15:12:57.244  7786  7786 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,09-13 15:12:57.244  7786  7786 I dhcpcd  : bssid match
,09-13 15:12:57.244  7786  7786 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,09-13 15:12:57.254  1016  1489 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-13 15:12:57.254  1016  1489 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-13 15:12:57.254  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:12:57.254  1016  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:57.254  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-13 15:12:57.254  7416  7416 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-13 15:12:57.254  7416  7416 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-13 15:12:57.254  1623  1623 I Hs20UtilService: Starting #17
09-13 15:12:57.254  7416  7416 D SecurityLogAgent: StateMachine : Current State = 1
,09-13 15:12:57.254  1623  1650 I Hs20UtilService: Message received 5011
09-13 15:12:57.264  7416  7416 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-13 15:12:57.344  7786  7786 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,09-13 15:12:57.374  7786  7786 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds,
,09-13 15:12:57.404  7643  7643 I wpa_supplicant: Blacklist: Clear (all) ,
,09-13 15:12:57.504  7643  7643 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
,09-13 15:12:57.504  1016  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-13 15:12:57.504  1016  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
09-13 15:12:57.504  1016  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-13 15:12:57.534  7643  7643 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-13 15:12:57.534  7643  7643 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-13 15:12:57.534  7643  7643 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-13 15:12:57.534  7643  7643 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-13 15:12:57.534  7643  7643 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-13 15:12:57.534  1016  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
09-13 15:12:57.534  1016  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-13 15:12:57.534  1016  1045 D Tethering: interfaceStatusChanged wlan0, false,
09-13 15:12:57.544  1016  1125 V NetworkStats: performPollLocked(flags=0x1)
09-13 15:12:57.534  1016  1132 D Tethering: InitialState.processMessage what=4
09-13 15:12:57.544  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-13 15:12:57.534  1016  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 15:12:57.544  1173  1173 D HotspotTile: updateTetherState():false, false
09-13 15:12:57.534  1016  1045 D Tethering: interfaceStatusChanged wlan0, false
09-13 15:12:57.544  1016  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-13 15:12:57.534  1016  1132 E Tethering: No numeric data
09-13 15:12:57.544  1016  1125 V NetworkStats: performPollLocked() took 3ms
09-13 15:12:57.534  1016  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-13 15:12:57.534  1016  1132 D Tethering: clearTetheredNotification()
,09-13 15:12:57.544  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:12:57.544  1016  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
09-13 15:12:57.544  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 15:12:57.544  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-13 15:12:57.544  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:12:57.544  1016  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 15:12:57.544  1016  1045 D Tethering: interfaceStatusChanged wlan0, false
09-13 15:12:57.544  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:12:57.544  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-13 15:12:57.824  1016  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,09-13 15:12:57.824  1016  1045 D Tethering: interfaceStatusChanged wlan0, false
09-13 15:12:57.824  1016  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-13 15:12:57.884  7643  7643 I wpa_supplicant: Blacklist: Clear (all) 
,09-13 15:12:57.924  7643  7643 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
09-13 15:12:57.924  1016  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 15:12:57.924  1016  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-13 15:12:57.924  1016  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-13 15:12:58.024  1016  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-13 15:12:58.034  1016  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-13 15:12:58.034  7432  7432 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,09-13 15:12:58.044  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 15:12:58.044  1757  2196 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 15:12:58.044  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 15:12:58.044  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-13 15:12:58.044  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:58.044  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:58.044  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:58.044  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:12:58.044  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-13 15:12:58.044  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-13 15:12:58.044  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-13 15:12:58.044  1173  1765 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-13 15:12:58.044  1173  1173 D HotspotTile: onReceive : 1, 0
,09-13 15:12:58.044  4811  4811 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-13 15:12:58.044  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:12:58.044  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:12:58.044  1016  1473 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-13 15:12:58.054  1016  1473 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-13 15:12:58.054  1016  1473 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:12:58.054  1016  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:12:58.054  1016  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-13 15:12:58.054  1623  1623 I Hs20UtilService: Starting #18
09-13 15:12:58.054  1623  1650 I Hs20UtilService: Message received 5011
,09-13 15:12:58.054  7416  7416 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-13 15:12:58.054  7416  7416 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-13 15:12:58.054  7416  7416 D SecurityLogAgent: StateMachine : Current State = 1
,09-13 15:12:58.054  7416  7416 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-13 15:12:58.764   279  1009 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,09-13 15:12:58.764  1016  1045 D Tethering: interfaceRemoved wlan0
,09-13 15:12:58.774  1016  1045 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-13 15:12:58.944  1016  1045 D Tethering: interfaceRemoved p2p0
09-13 15:12:58.944  1016  1045 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-13 15:12:59.334  1016  3387 D SSRM:n  : SIOP:: AP = 370
,09-13 15:12:59.424  1016  1043 W ActivityManager: mDVFSHelper.release()
,09-13 15:12:59.714  1016  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-13 15:12:59.994  1016  1097 V AlarmManager: waitForAlarm result :8,
,09-13 15:13:00.064  7106  7300 D BluetoothAdapter: enable()
,09-13 15:13:00.074  1016  1029 W ActivityManager: Permission Denial: getCurrentUser() from pid=7106, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-13 15:13:00.074  1016  1029 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
09-13 15:13:00.074  1016  1029 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7106, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-13 15:13:00.074  1016  1029 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-13 15:13:00.074  1016  1029 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
,09-13 15:13:00.074  1016  1029 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-13 15:13:00.074  1016  1029 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-13 15:13:00.074  1016  1029 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-13 15:13:00.074   290   290 E SMD     : DCD OFF
09-13 15:13:00.074  1016  1029 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-13 15:13:00.074  1016  1029 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-13 15:13:00.084  1016  1029 D SettingsProvider: name = bluetooth_on,
,09-13 15:13:00.104  1016  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-13 15:13:00.104  1016  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-13 15:13:00.104  1016  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-13 15:13:00.104  3238  3310 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
09-13 15:13:00.114  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-13 15:13:00.104  3238  3310 D BluetoothAdapterProperties: Setting state to 11
09-13 15:13:00.114  1016  1016 I InputMethodManagerService: [BT Setting State] State =11
,09-13 15:13:00.104  3238  3310 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-13 15:13:00.104  3238  3310 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-13 15:13:00.104  3238  3310 D BluetoothAdapterService: updateAdapterState state is 11
09-13 15:13:00.104  3238  3310 D BluetoothAdapterService: Autoconnection is available ,
09-13 15:13:00.104  3238  3310 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-13 15:13:00.104  3238  3310 D BtConfig.SecureMode: isSecureModeOn:false
,09-13 15:13:00.104  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-13 15:13:00.114  3238  3310 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
09-13 15:13:00.114  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-13 15:13:00.114  3238  3310 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
09-13 15:13:00.114  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-13 15:13:00.114  3238  3310 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-13 15:13:00.114  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService,
09-13 15:13:00.114  3238  3310 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-13 15:13:00.114  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-13 15:13:00.114  3238  3310 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-13 15:13:00.114  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-13 15:13:00.114  3238  3310 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-13 15:13:00.114  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-13 15:13:00.114  3238  3310 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-13 15:13:00.114  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-13 15:13:00.114  3238  3310 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-13 15:13:00.114  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-13 15:13:00.114  3238  3310 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-13 15:13:00.114  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-13 15:13:00.114  3238  3310 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-13 15:13:00.114  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-13 15:13:00.114  3238  3310 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-13 15:13:00.114  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-13 15:13:00.114  3238  3310 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-13 15:13:00.114  3238  3310 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-13 15:13:00.114  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-13 15:13:00.114  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-13 15:13:00.114  3238  3310 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-13 15:13:00.134  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-13 15:13:00.134  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:13:00.134  1173  1173 D BluetoothTile:  getBluetoothState : 11
,09-13 15:13:00.134  1173  1765 D BluetoothTile:  handleUpdatestate:false name:null
09-13 15:13:00.134  1173  1765 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-13 15:13:00.134  1892  1892 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0,
,09-13 15:13:00.144  1016  1028 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-13 15:13:00.144  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:00.144  1016  1479 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-13 15:13:00.144  4811  4811 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-13 15:13:00.144  1016  1079 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 15:13:00.144  1016  1079 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-13 15:13:00.154  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-13 15:13:00.154  1016  1079 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:00.154  1016  1079 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:00.154  1016  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-13 15:13:00.154  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:00.154  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-13 15:13:00.154  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-13 15:13:00.154  3238  3310 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-13 15:13:00.154  1016  1221 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 15:13:00.154  1016  1221 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-13 15:13:00.154  1016  1221 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:00.154  1016  1221 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:00.154  1016  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:00.154  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-13 15:13:00.154  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-13 15:13:00.154  3238  3310 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-13 15:13:00.154  1016  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 15:13:00.154  1016  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0,
09-13 15:13:00.154  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:00.154  1016  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:00.154  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-13 15:13:00.154  3238  3238 D HeadsetService: Received start request. Starting profile...
09-13 15:13:00.154  3238  3238 D HeadsetService: start()
09-13 15:13:00.154  3238  3238 D HeadsetStateMachine: make
,09-13 15:13:00.164  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-13 15:13:00.164  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-13 15:13:00.164  3238  3310 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-13 15:13:00.164  3238  3238 E HeadsetStateMachine: # of Max HF connection is 2
,09-13 15:13:00.174  1016  1463 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-13 15:13:00.174  1016  1463 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-13 15:13:00.174  1016  1463 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:00.174  1016  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:00.174  1016  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 15:13:00.174  1016  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-13 15:13:00.174  1016  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-13 15:13:00.174  2654  2654 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 15:13:00.174  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:00.174  1016  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:00.174  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:00.174  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService,
09-13 15:13:00.174  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-13 15:13:00.174  3238  3310 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-13 15:13:00.174  1016  1487 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-13 15:13:00.174  1016  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-13 15:13:00.184  1016  1487 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:13:00.184  1016  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:00.184  1016  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-13 15:13:00.184  1016  1473 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 15:13:00.184  1016  1473 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-13 15:13:00.184  1016  1473 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:00.184  1016  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:00.184  3238  3238 I bluedroid: get_profile_interface handsfree
09-13 15:13:00.184  1016  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-13 15:13:00.184  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-13 15:13:00.184  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-13 15:13:00.184  1016  1473 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 15:13:00.184  3238  3310 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-13 15:13:00.184  1016  1473 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-13 15:13:00.184  1016  1473 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:00.184  1016  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:00.184  1016  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:00.184  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-13 15:13:00.184  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-13 15:13:00.184  3238  3310 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-13 15:13:00.194  1016  1463 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
09-13 15:13:00.194  1016  1463 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-13 15:13:00.194  4811  4811 D BluetoothNotiBroadcastReceiver: onReceive
09-13 15:13:00.194  1016  1463 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:00.194  1016  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:00.194  1016  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:00.194  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-13 15:13:00.194  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-13 15:13:00.194  3238  3310 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-13 15:13:00.194  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-13 15:13:00.194  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-13 15:13:00.194  3238  3310 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-13 15:13:00.194  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-13 15:13:00.194  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-13 15:13:00.194  3238  3310 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-13 15:13:00.194  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-13 15:13:00.194  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-13 15:13:00.194  3238  3310 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-13 15:13:00.194  3238  3310 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-13 15:13:00.194  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:13:00.194  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-13 15:13:00.204  1016  1079 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-13 15:13:00.204  1016  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:13:00.204  1016  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:13:00.204  1016  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:13:00.204  1016  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:13:00.224  1016  1079 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7818 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-13 15:13:00.224  3238  3238 E DualScoManager: Dual Sco Manager already instantiated
,09-13 15:13:00.224  3238  3238 I DualScoManager: Set HeadsetServiceHelper
09-13 15:13:00.224  3238  3238 D BluetoothAtMessage: createCMTIContentObservers
09-13 15:13:00.224  7818  7818 E Zygote  : MountEmulatedStorage()
09-13 15:13:00.224  7818  7818 I libpersona: KNOX_SDCARD checking this for 10055
09-13 15:13:00.224  7818  7818 E Zygote  : v2
09-13 15:13:00.224  7818  7818 I libpersona: KNOX_SDCARD not a persona
,09-13 15:13:00.224  1016  1221 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-13 15:13:00.224  1016  1221 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-13 15:13:00.224  1016  1221 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-13 15:13:00.224  1016  1221 D SettingsProvider: selectionArgs: false
09-13 15:13:00.224  1016  1221 D SettingsProvider: selectionArgs: 1002
09-13 15:13:00.224  7818  7818 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 15:13:00.224  1016  1221 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-13 15:13:00.224  1016  1221 D SettingsProvider: ret = -1
,09-13 15:13:00.224  3238  7817 D HeadsetStateMachine: Enter Disconnected: -2
09-13 15:13:00.224  3238  3238 D HeadsetService: mStartError = false
09-13 15:13:00.224  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
09-13 15:13:00.224  7818  7818 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 15:13:00.234  3238  3238 D A2dpService: Received start request. Starting profile...
09-13 15:13:00.234  3238  3238 D A2dpService: start()
09-13 15:13:00.234  3238  3238 I bluedroid: get_profile_interface avrcp
09-13 15:13:00.234  7818  7818 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 15:13:00.234  3238  7817 D HeadsetStateMachine: Clear mHeadsetBrsf
09-13 15:13:00.234  3238  7817 D HeadsetStateMachine: map size, before remove : 0
09-13 15:13:00.234  3238  7817 D HeadsetStateMachine: map size, after remove: 0
,09-13 15:13:00.234  3238  3238 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-13 15:13:00.234  3238  3238 D Avrcp   : Initialize Media Controller
09-13 15:13:00.234  3238  3238 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-13 15:13:00.244  3238  3238 E Avrcp   : getActiveSessions
09-13 15:13:00.244  3238  3238 D Avrcp   : pick active media Controller
09-13 15:13:00.244  3238  3238 D Avrcp   : Get the active Media Controller 
,09-13 15:13:00.244  3238  3238 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-13 15:13:00.244  3238  7824 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-13 15:13:00.244  3238  3238 D A2dpStateMachine: make
,09-13 15:13:00.244  3238  3238 I bluedroid: get_profile_interface a2dp
09-13 15:13:00.254  3238  7831 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting,
09-13 15:13:00.254  3238  3238 E bt-btif : warning : media task started media_task_refcnt 1 
,09-13 15:13:00.254  3238  3238 D A2dpService: mStartError = false
09-13 15:13:00.254  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
09-13 15:13:00.254  3238  7830 D A2dpStateMachine: Enter Disconnected: -2
,09-13 15:13:00.254  3238  3238 D HidService: Received start request. Starting profile...
09-13 15:13:00.254  3238  3238 D HidService: start()
09-13 15:13:00.254  3238  3238 I bluedroid: get_profile_interface hidhost
09-13 15:13:00.254  3238  3238 D HidService: setHidService(): set to: null
09-13 15:13:00.254  3238  3238 D HidService: mStartError = false
09-13 15:13:00.254  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
09-13 15:13:00.254  3238  3238 D HeadsetStateMachine: Try to query the phonestate on bind
,09-13 15:13:00.254  1423  1476 I Telecom : BluetoothPhoneService: queryPhoneState
,09-13 15:13:00.264  1423  1423 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-13 15:13:00.264  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-13 15:13:00.264  1423  1476 I Telecom : BluetoothPhoneService: Result of Message : true
,09-13 15:13:00.264  3238  3238 D HealthService: Received start request. Starting profile...
09-13 15:13:00.264  3238  3238 D HealthService: start()
,09-13 15:13:00.264  3238  7824 D BluetoothMediaBrowser: no now playing list
09-13 15:13:00.264  3238  7824 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-13 15:13:00.264  3238  3238 I bluedroid: get_profile_interface health
09-13 15:13:00.264  3238  3238 D HealthService: mStartError = false
09-13 15:13:00.264  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
09-13 15:13:00.264  3238  3238 D HeadsetStateMachine: Proxy object connected
,09-13 15:13:00.264  3238  3238 D PanService: Received start request. Starting profile...
09-13 15:13:00.264  3238  3238 D PanService: start()
09-13 15:13:00.264  3238  3238 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 15:13:00.264  3238  3238 I bluedroid: get_profile_interface pan
09-13 15:13:00.264  3238  3238 D PanService: mStartError = false
09-13 15:13:00.264  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
,09-13 15:13:00.264  3238  3238 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-13 15:13:00.274  3238  7817 D HeadsetStateMachine: Disconnected process message: 11
,09-13 15:13:00.274  3238  3238 D BluetoothMapService: Received start request. Starting profile...,
09-13 15:13:00.274  3238  3238 D BluetoothMapService: start()
,09-13 15:13:00.274  3238  3238 D BluetoothMapService: mStartError = false,
09-13 15:13:00.274  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
,09-13 15:13:00.274  3238  3238 D SapService: Received start request. Starting profile...
,09-13 15:13:00.274  3238  3238 D SapService: start()
,09-13 15:13:00.274  3238  3238 D BluetoothSAPServiceJni: initializeNative(L209): sap
,09-13 15:13:00.274  3238  3238 I bluedroid: get_profile_interface sap
09-13 15:13:00.274  3238  3238 D SapService: mStartError = false
09-13 15:13:00.274  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
09-13 15:13:00.274  3238  3238 D HeadsetPhoneState: sendDeviceDataStateChanged
09-13 15:13:00.274  3238  3238 D HeadsetPhoneState: Signal level : previous=0 curr=4
09-13 15:13:00.274  3238  7817 D HeadsetStateMachine: Disconnected process message: 18
09-13 15:13:00.274  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-13 15:13:00.274  3238  3238 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 15:13:00.274  3238  7817 D HeadsetStateMachine: Disconnected process message: 10
09-13 15:13:00.274  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-13 15:13:00.274  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-13 15:13:00.274  3238  7817 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 15:13:00.274  3238  7817 D HeadsetStateMachine: Disconnected process message: 11
,09-13 15:13:00.274  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-13 15:13:00.274  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-13 15:13:00.294  7818  7818 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:13:00.294  7818  7818 D ActivityThread: Added TimaKeyStore provider
,09-13 15:13:00.294  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
09-13 15:13:00.294  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-13 15:13:00.294  3238  3310 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
09-13 15:13:00.294  3238  3310 I bluedroid: enable
,09-13 15:13:00.304  3238  3313 E bt-btif : Calling BTA_HhEnable
,09-13 15:13:00.304  3238  3313 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-13 15:13:00.304  3238  3313 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-13 15:13:00.304  3238  3313 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-13 15:13:00.304  3238  3313 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
09-13 15:13:00.304  3238  3313 E BluetoothServiceJni: populateRssiValuesNative
09-13 15:13:00.304  3238  3313 I bluedroid: getModelRssiValues
09-13 15:13:00.304  3238  3313 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-13 15:13:00.304  3238  3313 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-13 15:13:00.304  3238  3313 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-13 15:13:00.304  1016  1016 D SettingsProvider: name = bluetooth_name
,09-13 15:13:00.304  3238  3313 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-13 15:13:00.304  3238  3313 D BluetoothAdapterProperties: Scan Mode:20
09-13 15:13:00.304  3238  3313 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 15:13:00.304  3238  3313 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
09-13 15:13:00.304  3238  3313 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-13 15:13:00.304  3238  3313 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
09-13 15:13:00.304  3238  3313 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-13 15:13:00.304  3238  3313 E bt-btif : JVenable fails
,09-13 15:13:00.314  3238  3313 D bte_conf: Device ID record 1 : primary
09-13 15:13:00.314  3238  3313 D bte_conf:   vendorId            = 0075
09-13 15:13:00.314  3238  3313 D bte_conf:   vendorIdSource      = 0001
09-13 15:13:00.314  3238  3313 D bte_conf:   product             = 0100
09-13 15:13:00.314  3238  3313 D bte_conf:   version             = 0200
09-13 15:13:00.314  3238  3313 D bte_conf:   clientExecutableURL = 
09-13 15:13:00.314  3238  3313 D bte_conf:   serviceDescription  = 
09-13 15:13:00.314  3238  3313 D bte_conf:   documentationURL    = 
,09-13 15:13:00.314  3238  3313 D bte_conf: bte_load_did_conf no section named DID2.
,09-13 15:13:00.314  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:00.314  3238  3313 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
09-13 15:13:00.314  3238  3313 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-13 15:13:00.314  3238  3310 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-13 15:13:00.314  3238  3310 D BluetoothAdapterProperties: ScanMode =  20
,09-13 15:13:00.314  3238  3310 D BluetoothAdapterProperties: State =  11
,09-13 15:13:00.324  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-13 15:13:00.324  1016  1847 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-13 15:13:00.324  3238  3310 D BluetoothAdapterProperties: Setting state to 12
09-13 15:13:00.324  3238  3310 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-13 15:13:00.324  7818  7818 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-13 15:13:00.324  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:13:00.324  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:00.324  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:00.324  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:13:00.324  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:00.324  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:13:00.324  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:13:00.324  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:13:00.334  3238  3313 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-13 15:13:00.334  3238  3313 D BluetoothAdapterProperties: Scan Mode:21
09-13 15:13:00.334  3238  3313 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 15:13:00.334  1016  1221 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-13 15:13:00.334  1016  1221 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-13 15:13:00.334  1016  1221 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-13 15:13:00.334  1016  1221 D SettingsProvider: selectionArgs: false
09-13 15:13:00.334  1016  1221 D SettingsProvider: selectionArgs: 1002
09-13 15:13:00.334  1016  1221 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-13 15:13:00.334  1016  1221 D SettingsProvider: ret = -1
,09-13 15:13:00.334  3238  3310 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-13 15:13:00.334  3238  3310 D BluetoothAdapterService: updateAdapterState state is 12
,09-13 15:13:00.334  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 15:13:00.334  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-13 15:13:00.334  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:13:00.334  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:00.334  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:00.334  7354  7363 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 15:13:00.334  7354  7363 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-13 15:13:00.334  3238  3310 D BluetoothAdapterService: Autoconnection is available 
09-13 15:13:00.334  3238  3310 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-13 15:13:00.334  3238  3310 D BluetoothAdapterService: starting service from this receiver
,09-13 15:13:00.334  1016  1463 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 15:13:00.334  1016  1463 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-13 15:13:00.334  1016  1463 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:00.334  1016  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:00.334  1016  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:00.334  3238  3238 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-13 15:13:00.344  3238  3238 I BluetoothPbapService: Handler(): got msg=1
,09-13 15:13:00.344  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:13:00.344  1423  1446 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-13 15:13:00.344  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:13:00.344  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:00.344  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:00.344  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:13:00.344  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:00.344  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:13:00.344  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:13:00.344  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:13:00.344  1016  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-13 15:13:00.344  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-13 15:13:00.344  1016  1463 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-13 15:13:00.344  3238  3310 I BluetoothAdapterState: Entering On State from state = 11
09-13 15:13:00.344  1016  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:00.344  1016  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:00.344  1016  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:00.344  1423  1446 E BluetoothHeadset: BluetoothHeadset service is binded
,09-13 15:13:00.344  1016  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 15:13:00.344  1016  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-13 15:13:00.354  1016  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-13 15:13:00.354  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-13 15:13:00.354  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 15:13:00.354  1436  6292 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 15:13:00.354  1436  6292 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-13 15:13:00.354  1016  1047 D BluetoothPan: Binding service...
,09-13 15:13:00.354  1016  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-13 15:13:00.354  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-13 15:13:00.354  1447  1748 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 15:13:00.354  1447  1748 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-13 15:13:00.354  7106  7117 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-13 15:13:00.354  7106  7117 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-13 15:13:00.354  3238  7840 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-13 15:13:00.354  4811  4826 D BluetoothPan: Binding service...
,09-13 15:13:00.354  7818  7818 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-13 15:13:00.364  7818  7818 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-13 15:13:00.364  7818  7818 D UserAnalysis: Create SecureDbHelper
,09-13 15:13:00.364  1016  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-13 15:13:00.364  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-13 15:13:00.364  1016  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:00.364  1016  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:00.364  1016  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:00.364  7818  7818 D IntelligenceServiceApplication: onCreate()
,09-13 15:13:00.374  3238  3395 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 15:13:00.374  3238  3395 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-13 15:13:00.374  3238  7840 D BluetoothSocket: bindListen(): myUserId = 0
09-13 15:13:00.374  1016  1016 D BluetoothA2dp: Proxy object connected
09-13 15:13:00.374  3238  7840 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 15:13:00.374  4811  4811 D BluetoothPan: BluetoothPAN Proxy object connected
,09-13 15:13:00.374  4811  4811 D PanProfile: Bluetooth service connected
,09-13 15:13:00.374  4811  4826 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-13 15:13:00.374  3238  7840 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-13 15:13:00.374  3238  7840 D BluetoothSocket: bindListen(), new LocalSocket 
09-13 15:13:00.374  3238  7840 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-13 15:13:00.374  3238  7840 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c20a6ce
,09-13 15:13:00.374  3238  7840 D BluetoothSocket: channel: 19
,09-13 15:13:00.374  3238  7840 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-13 15:13:00.374  1016  1851 I ActivityManager: Killing 7354:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,09-13 15:13:00.374  1016  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-13 15:13:00.374  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-13 15:13:00.384  7818  7818 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-13 15:13:00.384  1016  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:00.384  1016  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:00.384  1016  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:00.384  4811  4826 E BluetoothHeadset: BluetoothHeadset service is binded
,09-13 15:13:00.384  1016  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-13 15:13:00.384  1016  1016 D BluetoothPan: BluetoothPAN Proxy object connected
,09-13 15:13:00.384  4811  4811 D HeadsetProfile: Bluetooth service connected
,09-13 15:13:00.384  1016  1850 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-13 15:13:00.384  1016  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-13 15:13:00.384  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-13 15:13:00.384  1016  1047 E BluetoothHeadset: BluetoothHeadset service is binded
09-13 15:13:00.394  7818  7818 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-13 15:13:00.394  1423  1446 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-13 15:13:00.394  1016  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-13 15:13:00.394  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-13 15:13:00.394  1016  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:00.394  1016  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:00.394  1016  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:00.394  1423  1446 E BluetoothHeadset: BluetoothHeadset service is binded
,09-13 15:13:00.394  2654  4253 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 15:13:00.394  2654  4253 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-13 15:13:00.394  1757  1774 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 15:13:00.394  1757  1774 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-13 15:13:00.394  1016  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 15:13:00.394  1016  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-13 15:13:00.394  1447  4740 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-13 15:13:00.394  1016  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-13 15:13:00.404  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-13 15:13:00.404  1016  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:00.404  1016  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:00.404  1016  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
09-13 15:13:00.404  1447  4740 E BluetoothHeadset: BluetoothHeadset service is binded
09-13 15:13:00.404  4811  4826 D Bluetoothsap: onBluetoothStateChange: up=true
09-13 15:13:00.404  4811  4826 D Bluetoothsap: Binding service...
,09-13 15:13:00.404  7818  7818 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-13 15:13:00.414  4811  4826 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-13 15:13:00.414  1016  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,09-13 15:13:00.414  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-13 15:13:00.414  1016  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:13:00.414  1016  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:00.414  1016  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:00.414  4811  4826 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-13 15:13:00.424  4811  4811 D Bluetoothsap: BluetoothSAP Proxy object connected
09-13 15:13:00.424  4811  4811 D SapProfile: Bluetooth service connected
09-13 15:13:00.424  4811  4811 D Bluetoothsap: getConnectedDevices()
,09-13 15:13:00.424  3238  3254 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 15:13:00.424  3238  3254 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-13 15:13:00.424  1016  1047 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-13 15:13:00.424  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-13 15:13:00.424  1016  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:13:00.424  1016  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:00.424  1016  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:00.424  3238  3238 D BluetoothA2dp: Proxy object connected
09-13 15:13:00.424  3238  3238 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-13 15:13:00.424  4811  7841 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-13 15:13:00.424  4811  7841 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-13 15:13:00.434  1423  1446 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-13 15:13:00.434  1016  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-13 15:13:00.434  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-13 15:13:00.434  1016  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:13:00.434  1016  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:00.434  1016  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:00.434  1423  1446 E BluetoothHeadset: BluetoothHeadset service is binded
,09-13 15:13:00.434  4811  4833 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 15:13:00.434  1016  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-13 15:13:00.434  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-13 15:13:00.434  1016  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:00.434  1016  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:00.434  1016  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:00.434  1173  2001 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-13 15:13:00.434  1173  2001 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-13 15:13:00.434  4811  4811 D BluetoothPbap: Proxy object connected
09-13 15:13:00.434  4811  4811 D PbapServerProfile: Bluetooth service connected
,09-13 15:13:00.444  4811  7841 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 15:13:00.444  1016  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-13 15:13:00.444  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-13 15:13:00.444  1016  1047 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:13:00.444  1016  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:00.444  1016  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:00.444  4811  4826 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 15:13:00.444  4811  4811 D BluetoothInputDevice: Proxy object connected
,09-13 15:13:00.444  4811  4811 D HidProfile: Bluetooth service connected
,09-13 15:13:00.444  1016  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-13 15:13:00.444  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-13 15:13:00.444  1016  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:00.444  1016  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:00.444  1016  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:00.444  4811  4833 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 15:13:00.454  4811  4833 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-13 15:13:00.454  1016  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-13 15:13:00.454  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-13 15:13:00.454  1016  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:00.454  1016  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:00.454  1016  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:00.454  1423  1446 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-13 15:13:00.454  1423  1446 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-13 15:13:00.454  4811  4811 D BluetoothMap: Proxy object connected
09-13 15:13:00.454  4811  4811 D MapProfile: Bluetooth service connected
09-13 15:13:00.454  4811  4811 D BluetoothMap: getConnectedDevices()
,09-13 15:13:00.454  1016  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-13 15:13:00.454  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-13 15:13:00.454  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-13 15:13:00.454  1016  1016 I InputMethodManagerService: [BT Setting State] State =12
09-13 15:13:00.454  1016  1016 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-13 15:13:00.464  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,09-13 15:13:00.464  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-13 15:13:00.464  1173  1765 D BluetoothTile:  handleUpdatestate:false name:null
,09-13 15:13:00.464  1173  1765 D BluetoothTile:  handleUpdatestate:false name:null
,09-13 15:13:00.464  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-13 15:13:00.464  1173  1173 D BluetoothTile:  getBluetoothState : 12
,09-13 15:13:00.464  1173  1765 D BluetoothTile:  handleUpdatestate:false name:null
,09-13 15:13:00.474  1423  1423 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2b0db0f8, true
09-13 15:13:00.474  1423  1423 D BluetoothHeadset: registerMessageListener
09-13 15:13:00.474  1892  1892 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-13 15:13:00.474  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:13:00.474  4811  4811 D BluetoothA2dp: Proxy object connected
09-13 15:13:00.474  4811  4811 D A2dpProfile: Bluetooth service connected
,09-13 15:13:00.474  3238  3358 D HeadsetService: registerMessageListener
,09-13 15:13:00.474  3238  3358 D HeadsetService: registerMessageListener
,09-13 15:13:00.484  3238  7817 D HeadsetStateMachine: Disconnected process message: 70
09-13 15:13:00.484  3238  7817 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@e0df9ef
09-13 15:13:00.484  1423  1423 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-13 15:13:00.484  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-13 15:13:00.484  1016  1029 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-13 15:13:00.484  1016  1850 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-13 15:13:00.484  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:00.484  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-13 15:13:00.484  3238  7845 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-13 15:13:00.494  1423  1423 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,09-13 15:13:00.494  1423  1423 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-13 15:13:00.494  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-13 15:13:00.494  4811  4811 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-13 15:13:00.494  3238  7817 D HeadsetStateMachine: Disconnected process message: 9,
09-13 15:13:00.494  3238  7817 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
09-13 15:13:00.494  3238  7845 D BluetoothSocket: bindListen(): myUserId = 0
09-13 15:13:00.494  3238  7845 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 15:13:00.494  3238  7845 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
,09-13 15:13:00.494  3238  7845 D BluetoothSocket: bindListen(), new LocalSocket 
,09-13 15:13:00.494  3238  7845 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-13 15:13:00.494  3238  7845 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3bf46cfc
09-13 15:13:00.494  4811  4811 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-13 15:13:00.494  3238  7845 D BluetoothSocket: channel: 5
09-13 15:13:00.494  4811  4811 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,09-13 15:13:00.494  4811  4811 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-13 15:13:00.494  4811  4811 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
09-13 15:13:00.494   284   284 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-13 15:13:00.494   284   284 V voice   : voice_set_parameters: enter: A2dpSuspended=false
,09-13 15:13:00.494   284   284 V voice   : voice_set_parameters: exit with code(-2)
09-13 15:13:00.494   284   284 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-13 15:13:00.494   284   284 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-13 15:13:00.494   284   284 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-13 15:13:00.494   284   284 V audio_hw_primary: adev_set_parameters: exit
,09-13 15:13:00.494  3238  7817 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-13 15:13:00.504  4811  4811 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 15:13:00.504  1016  1479 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-13 15:13:00.504  1016  1479 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-13 15:13:00.504  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:13:00.504  1016  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:00.504  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-13 15:13:00.514  2654  2654 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 15:13:00.524  4811  4811 D DockEventReceiver: finishStartingService: stopping service
,09-13 15:13:00.524  4811  4811 D BluetoothNotiBroadcastReceiver: onReceive
,09-13 15:13:00.524  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:13:00.524  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-13 15:13:00.534  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
,09-13 15:13:00.534  3238  3238 D BtConfig.SecureMode: isSecureModeOn:false
,09-13 15:13:00.534  1016  1851 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-13 15:13:00.534  1016  1851 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-13 15:13:00.534  1016  1851 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:13:00.534  1016  1851 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:00.534  1016  1851 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:00.544  1016  1221 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-13 15:13:00.554  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast,
,09-13 15:13:00.554  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:13:00.554  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:13:00.554  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:13:00.554  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:13:00.564  7851  7851 E Zygote  : MountEmulatedStorage(),
09-13 15:13:00.564  7851  7851 I libpersona: KNOX_SDCARD checking this for 10105
09-13 15:13:00.564  7851  7851 E Zygote  : v2
09-13 15:13:00.564  7851  7851 I libpersona: KNOX_SDCARD not a persona
09-13 15:13:00.564  7851  7851 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-13 15:13:00.564  7851  7851 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 15:13:00.564  7851  7851 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-13 15:13:00.564  1016  1028 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7851 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-13 15:13:00.574  3238  7850 D BluetoothSocket: bindListen(): myUserId = 0
09-13 15:13:00.574  3238  7850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 15:13:00.574  3238  7850 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[85]}
09-13 15:13:00.574  3238  7850 D BluetoothSocket: bindListen(), new LocalSocket 
09-13 15:13:00.574  3238  7850 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-13 15:13:00.574  3238  7850 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@29995ce8
,09-13 15:13:00.574  3238  7850 D BluetoothSocket: channel: 12,
09-13 15:13:00.574  3238  7850 I BtOppRfcommListener: Accept thread started.
,09-13 15:13:00.594  7851  7851 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:13:00.594  7851  7851 D ActivityThread: Added TimaKeyStore provider
,09-13 15:13:00.704   258   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-13 15:13:00.704   258   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 15:13:00.704  7851  7870 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-13 15:13:00.714   258   524 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-13 15:13:00.714   258   524 W Vold    : Returning OperationFailed - no handler for errno 0
,09-13 15:13:00.714  7851  7870 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-13 15:13:00.854  7851  7851 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.io.File.exists(File.java:363)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-13 15:13:00.854  7851  7851 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 15:13:00.854  7851  7851 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 15:13:00.854  7851  7851 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.q.e.b(PG:170)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09,-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 15:13:00.854  7851  7851 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.q.k.d(PG:583)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.q.e.b(PG:170)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 15:13:00.854  7851  7851 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.io.File.exists(File.java:363)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 15:13:00.854  7851  7851 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.io.File.exists(File.java:363)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 15:13:00.864  1016  1079 I ActivityManager: Killing 7457:com.sec.pcw.device/1000 (adj 15): empty #21
09-13 15:13:00.854  7851  7851 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 15:13:00.854  7851  7851 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-13 15:13:00.914  7851  7879 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
09-13 15:13:00.934  1016  1489 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-13 15:13:00.934  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:00.934  1016  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 15:13:00.934  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-13 15:13:01.134  1016  3406 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-13 15:13:02.104   327   327 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 15:13:03.094   290   290 E SMD     : DCD OFF,
,09-13 15:13:03.104  7106  7300 D BluetoothAdapter: disable(),
,09-13 15:13:03.104  1016  1079 D SettingsProvider: name = bluetooth_on,
,09-13 15:13:03.104   327   327 I ServiceManager: Waiting for service AtCmdFwd...,
,09-13 15:13:03.104  3238  3310 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
09-13 15:13:03.104  3238  3310 D BluetoothAdapterProperties: Setting state to 13
09-13 15:13:03.104  3238  3310 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-13 15:13:03.104  3238  3310 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-13 15:13:03.104  3238  3310 D BluetoothAdapterService: updateAdapterState state is 13
,09-13 15:13:03.104  1016  1851 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-13 15:13:03.104  1016  1851 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-13 15:13:03.114  1016  1851 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:13:03.114  1016  1851 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:03.114  1016  1851 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-13 15:13:03.114  3238  3238 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-13 15:13:03.114  3238  3238 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@340b6f01, channel: 19, state: LISTENING
09-13 15:13:03.114  3238  3238 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@340b6f01, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2c20a6ce, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@76c1a6mSocket: android.net.LocalSocket@df537e7 impl:android.net.LocalSocketImpl@c1b5f94 fd:FileDescriptor[80]
09-13 15:13:03.114  3238  3238 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@df537e7 impl:android.net.LocalSocketImpl@c1b5f94 fd:FileDescriptor[80]
09-13 15:13:03.114  3238  3310 D BluetoothAdapterService: Autoconnection is available 
,09-13 15:13:03.114  3238  3310 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-13 15:13:03.114  3238  3310 D BluetoothAdapterService: terminating service from this receiver
,09-13 15:13:03.114  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-13 15:13:03.114  1016  1016 I InputMethodManagerService: [BT Setting State] State =13
,09-13 15:13:03.124  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,09-13 15:13:03.124  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-13 15:13:03.124  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:13:03.124  1173  1173 D BluetoothTile:  getBluetoothState : 13
,09-13 15:13:03.124  1173  1765 D BluetoothTile:  handleUpdatestate:false name:null
,09-13 15:13:03.124  1892  1892 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-13 15:13:03.124  4811  4811 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-13 15:13:03.134  1016  1463 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-13 15:13:03.134  1173  1765 D BluetoothTile:  handleUpdatestate:false name:null
09-13 15:13:03.134  1016  1473 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-13 15:13:03.134  1173  1765 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-13 15:13:03.134  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-13 15:13:03.134  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-13 15:13:03.134  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:13:03.134  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:13:03.134  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:03.134  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:03.134  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:13:03.134  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:13:03.134  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:13:03.134  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:13:03.134  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:13:03.144  4811  4811 D BluetoothPbap: Proxy object disconnected
09-13 15:13:03.144  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:13:03.144  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-13 15:13:03.144  4811  4811 D PbapServerProfile: Bluetooth service disconnected
,09-13 15:13:03.144  3238  3238 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3f3efa3d, channel: 5, state: LISTENING
09-13 15:13:03.144  3238  3238 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3f3efa3d, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3bf46cfc, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@263d5232mSocket: android.net.LocalSocket@3bd36b83 impl:android.net.LocalSocketImpl@e18e100 fd:FileDescriptor[82]
09-13 15:13:03.144  3238  3238 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3bd36b83 impl:android.net.LocalSocketImpl@e18e100 fd:FileDescriptor[82]
09-13 15:13:03.144  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 15:13:03.144  3238  3238 I BtOppRfcommListener: stopping Accept Thread
09-13 15:13:03.144  3238  3238 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1b25fd39, channel: 12, state: LISTENING
,09-13 15:13:03.144  3238  3238 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1b25fd39, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@29995ce8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@356a5f7emSocket: android.net.LocalSocket@d73cdf impl:android.net.LocalSocketImpl@23ab0d2c fd:FileDescriptor[85]
09-13 15:13:03.144  3238  3238 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@d73cdf impl:android.net.LocalSocketImpl@23ab0d2c fd:FileDescriptor[85]
09-13 15:13:03.144  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:03.144  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 15:13:03.144  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-13 15:13:03.144  4811  4811 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 15:13:03.144  3238  7850 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 15:13:03.144  3238  7850 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-13 15:13:03.144  1016  1221 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-13 15:13:03.144  3238  3310 D BluetoothAdapterProperties: onBluetoothDisable()
09-13 15:13:03.144  3238  3310 D BluetoothAdapterProperties: mDiscovering is false
09-13 15:13:03.144  1016  1221 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-13 15:13:03.144  1016  1850 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-13 15:13:03.144  1016  1221 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:13:03.144  1016  1221 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:03.144  1016  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
09-13 15:13:03.144  3238  3310 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-13 15:13:03.144  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:13:03.144  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:13:03.144  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:03.144  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:03.144  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:13:03.144  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 15:13:03.144  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:13:03.144  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:13:03.144  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 15:13:03.154  7106  7106 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 15:13:03.154  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 15:13:03.154  3238  3313 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-13 15:13:03.154  3238  3313 D BluetoothAdapterProperties: Scan Mode:20
,09-13 15:13:03.164  3238  3310 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-13 15:13:03.164  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:13:03.164  3238  3310 E bt-btif : btif_dm_generic_evtsock_thread_handle:6, rfc_init:1, vhci_init:1
,09-13 15:13:03.164  3238  3310 E bt-btif : cmd socket is not created
,09-13 15:13:03.164  3238  3310 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-13 15:13:03.164  3238  3315 W bt-btif : bta_dm_disable_bt BTA_DISABLE_DELAY set to 200 ms
,09-13 15:13:03.164  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:03.164  2654  2654 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 15:13:03.174  3238  3238 V BluetoothOppManager: cleanUp...
,09-13 15:13:03.174  3238  3315 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 15:13:03.174  3238  3315 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 15:13:03.174  3238  3315 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 15:13:03.184  3238  3315 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 15:13:03.184  3238  3315 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 15:13:03.184  3238  3315 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-13 15:13:03.184  4811  4811 D DockEventReceiver: finishStartingService: stopping service
,09-13 15:13:03.184  4811  4811 D BluetoothNotiBroadcastReceiver: onReceive
,09-13 15:13:03.184  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:13:03.184  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-13 15:13:03.374  3238  3310 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-13 15:13:03.374  3238  3310 D BtConfig.SecureMode: isSecureModeOn:false
,09-13 15:13:03.374  3238  3310 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,09-13 15:13:03.374  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
09-13 15:13:03.374  3238  3310 W BluetoothAdapterService: Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
,09-13 15:13:03.374  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,09-13 15:13:03.374  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-13 15:13:03.374  3238  3310 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-13 15:13:03.374  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-13 15:13:03.374  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-13 15:13:03.374  1016  1029 W ActivityManager: userId = 0, bbcId = -10000,
09-13 15:13:03.374  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 15:13:03.374  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-13 15:13:03.374  1016  1463 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 15:13:03.374  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,09-13 15:13:03.374  1016  1463 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-13 15:13:03.374  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-13 15:13:03.374  3238  3310 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-13 15:13:03.374  1016  1463 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:13:03.374  1016  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:03.374  1016  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:03.374  3238  3238 D HeadsetService: Received stop request...Stopping profile...
,09-13 15:13:03.374  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-13 15:13:03.374  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-13 15:13:03.374  3238  3310 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-13 15:13:03.374  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
09-13 15:13:03.374  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 15:13:03.374  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-13 15:13:03.374  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:03.374  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 15:13:03.374  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:03.384  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,09-13 15:13:03.384  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-13 15:13:03.384  3238  3310 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-13 15:13:03.384  1016  1850 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 15:13:03.384  1016  1850 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-13 15:13:03.384  3238  3238 D A2dpService: Received stop request...Stopping profile...
,09-13 15:13:03.384  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-13 15:13:03.384  3238  7830 D A2dpStateMachine: Exit Disconnected: -1
,09-13 15:13:03.384  4811  4811 D HeadsetProfile: Bluetooth service disconnected
,09-13 15:13:03.384  1016  1850 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:03.384  1016  1850 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:03.384  1016  1850 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:03.384  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
,09-13 15:13:03.384  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService,
09-13 15:13:03.384  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-13 15:13:03.384  3238  3310 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-13 15:13:03.384  1016  1016 D BluetoothA2dp: Proxy object disconnected
09-13 15:13:03.384  1016  1016 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-13 15:13:03.394  1016  1487 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 15:13:03.394  4811  4811 D BluetoothA2dp: Proxy object disconnected
09-13 15:13:03.394  1016  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-13 15:13:03.394  4811  4811 D A2dpProfile: Bluetooth service disconnected
,09-13 15:13:03.394  1016  1487 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:13:03.394  1016  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:03.394  1016  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:03.394  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
09-13 15:13:03.394  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-13 15:13:03.394  3238  3310 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-13 15:13:03.394  1016  1851 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 15:13:03.394  1016  1851 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-13 15:13:03.394  1016  1851 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:13:03.394  1016  1851 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:03.394  1016  1851 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:03.394  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,09-13 15:13:03.394  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-13 15:13:03.394  3238  3310 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-13 15:13:03.394  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-13 15:13:03.394  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-13 15:13:03.404  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:13:03.404  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 15:13:03.404  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:03.404  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-13 15:13:03.404  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-13 15:13:03.404  3238  3310 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-13 15:13:03.404  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,09-13 15:13:03.404  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-13 15:13:03.404  3238  3310 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,09-13 15:13:03.404  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-13 15:13:03.404  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-13 15:13:03.404  3238  3310 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,09-13 15:13:03.404  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-13 15:13:03.404  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-13 15:13:03.404  3238  3310 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-13 15:13:03.404  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-13 15:13:03.404  3238  3238 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-13 15:13:03.404  3238  3238 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-13 15:13:03.404  3238  3310 D BluetoothAdapterState: Stopping profile services that were post enabled
09-13 15:13:03.404  3238  3238 D HidService: Received stop request...Stopping profile...
09-13 15:13:03.404  3238  3238 D HidService: Stopping Bluetooth HidService
09-13 15:13:03.404  3238  3238 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 15:13:03.404  3238  3238 W bt-btif : cleanup: HH disabling or disabled already, status = 0
,09-13 15:13:03.404  3238  3238 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 15:13:03.404  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
,09-13 15:13:03.404  4811  4811 D BluetoothInputDevice: Proxy object disconnected
09-13 15:13:03.404  4811  4811 D HidProfile: Bluetooth service disconnected
,09-13 15:13:03.414  3238  3238 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-13 15:13:03.414  3238  3238 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-13 15:13:03.414  3238  3238 D HealthService: Received stop request...Stopping profile...
,09-13 15:13:03.414  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
,09-13 15:13:03.414  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-13 15:13:03.414  3238  3238 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-13 15:13:03.414  3238  3238 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-13 15:13:03.414  3238  3238 D BluetoothA2dp: Proxy object disconnected
09-13 15:13:03.414  3238  3238 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-13 15:13:03.414  3238  7831 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-13 15:13:03.414  3238  3238 I GKI_LINUX: GKI_exit_task 2 done
09-13 15:13:03.414  3238  3238 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-13 15:13:03.414  3238  3238 D PanService: Received stop request...Stopping profile...
09-13 15:13:03.414  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
,09-13 15:13:03.414  1016  1016 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-13 15:13:03.414  4811  4811 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-13 15:13:03.414  4811  4811 D PanProfile: Bluetooth service disconnected
09-13 15:13:03.414  3238  3238 D BluetoothMapService: Received stop request...Stopping profile...
,09-13 15:13:03.424  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
,09-13 15:13:03.424  3238  3238 D SapService: Received stop request...Stopping profile...
,09-13 15:13:03.424  3238  3238 D SapService: Stopping Bluetooth SapService
,09-13 15:13:03.424  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
,09-13 15:13:03.424  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,09-13 15:13:03.424  3238  3238 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
,09-13 15:13:03.424  3238  3238 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-13 15:13:03.424  3238  3238 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-13 15:13:03.424  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,09-13 15:13:03.424  3238  3238 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-13 15:13:03.424  3238  3238 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-13 15:13:03.434  3238  3238 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-13 15:13:03.434  3238  3238 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-13 15:13:03.434  3238  3238 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-13 15:13:03.434  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-13 15:13:03.434  3238  3238 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-13 15:13:03.434  3238  3238 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-13 15:13:03.434  3238  3238 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-13 15:13:03.434  3238  3238 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 15:13:03.434  3238  3238 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-13 15:13:03.434  4811  4811 D BluetoothMap: Proxy object disconnected
09-13 15:13:03.434  4811  4811 D MapProfile: Bluetooth service disconnected
09-13 15:13:03.434  4811  4811 D Bluetoothsap: BluetoothSAP Proxy object disconnected
,09-13 15:13:03.434  4811  4811 D SapProfile: Bluetooth service disconnected
,09-13 15:13:03.434  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-13 15:13:03.434  3238  3238 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-13 15:13:03.434  3238  3238 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-13 15:13:03.434  3238  3238 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-13 15:13:03.434  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-13 15:13:03.434  3238  3238 D BluetoothAdapterService: Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
09-13 15:13:03.434  3238  3238 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-13 15:13:03.434  3238  3238 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-13 15:13:03.434  3238  3310 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-13 15:13:03.434  3238  3310 D BluetoothAdapterProperties: Setting state to 10
09-13 15:13:03.434  3238  3310 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-13 15:13:03.434  3238  3310 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-13 15:13:03.434  3238  3310 D BluetoothAdapterService: updateAdapterState state is 10
,09-13 15:13:03.434  3238  3310 D BluetoothAdapterService: Autoconnection is available 
09-13 15:13:03.434  3238  3310 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-13 15:13:03.434  3238  3310 I BluetoothAdapterState: Entering OffState
,09-13 15:13:03.434  1016  1047 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-13 15:13:03.434  1436  1464 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-13 15:13:03.434  1436  1464 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 15:13:03.434  7851  7859 D BluetoothAdapter: onBluetoothStateChange: up=false
09-13 15:13:03.434  7851  7859 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 15:13:03.434  1447  1475 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-13 15:13:03.444  1447  1475 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 15:13:03.444  7106  7117 D BluetoothAdapter: onBluetoothStateChange: up=false
09-13 15:13:03.444  7106  7117 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 15:13:03.444  7106  7117 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-13 15:13:03.444  7106  7117 D BluetoothLeAdvertiser: Exit stop advertising
09-13 15:13:03.444  7106  7117 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,09-13 15:13:03.444  7106  7117 D BluetoothLeScanner: Exiting stopAllScan
,09-13 15:13:03.444  3238  3262 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-13 15:13:03.444  3238  3262 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 15:13:03.444  2654  4253 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-13 15:13:03.444  2654  4253 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 15:13:03.444  1757  1772 D BluetoothAdapter: onBluetoothStateChange: up=false
09-13 15:13:03.444  1757  1772 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 15:13:03.444  1016  1047 D BluetoothAdapter: onBluetoothStateChange: up=false
09-13 15:13:03.444  1016  1047 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 15:13:03.444  4811  4833 D Bluetoothsap: onBluetoothStateChange: up=false
,09-13 15:13:03.444  4811  4833 D Bluetoothsap: Unbinding service...
,09-13 15:13:03.444  3238  3254 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-13 15:13:03.454  4811  7841 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-13 15:13:03.454  4811  7841 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 15:13:03.454  4811  4826 D BluetoothPbap: onBluetoothStateChange: up=false
,09-13 15:13:03.454  1173  2001 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-13 15:13:03.454  1173  2001 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 15:13:03.454  4811  4833 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-13 15:13:03.454  4811  7841 D BluetoothMap: onBluetoothStateChange: up=false
,09-13 15:13:03.454  4811  4826 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-13 15:13:03.454  1423  7843 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-13 15:13:03.454  1423  7843 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-13 15:13:03.454  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-13 15:13:03.454  1016  1016 I InputMethodManagerService: [BT Setting State] State =10
,09-13 15:13:03.454  1016  1016 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-13 15:13:03.464  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-13 15:13:03.464  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-13 15:13:03.464  1173  1173 D BluetoothTile:  getBluetoothState : 10
,09-13 15:13:03.464  1892  1892 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-13 15:13:03.474  1016  1851 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-13 15:13:03.474  4811  4811 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-13 15:13:03.474  1016  1028 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-13 15:13:03.474  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-13 15:13:03.474  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:03.474  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:03.474  4811  4811 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 15:13:03.474  1016  1079 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-13 15:13:03.474  1016  1079 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-13 15:13:03.474  1016  1079 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:13:03.474  1016  1079 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:03.474  1016  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-13 15:13:03.484  2654  2654 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 15:13:03.484  4811  4811 D DockEventReceiver: finishStartingService: stopping service
,09-13 15:13:03.484  4811  4811 D BluetoothNotiBroadcastReceiver: onReceive
,09-13 15:13:03.494  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-13 15:13:03.494  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-13 15:13:04.114   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 15:13:04.124  1016  1474 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-13 15:13:04.124  1016  1474 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
09-13 15:13:04.124  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,09-13 15:13:04.124  1016  1474 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
09-13 15:13:04.124  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate,
09-13 15:13:04.124  1016  1474 D BatteryService: stay LED for charging
,09-13 15:13:04.124  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
,09-13 15:13:04.124  1016  1016 I MotionRecognitionService: Plugged
,09-13 15:13:04.124  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
09-13 15:13:04.134  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
09-13 15:13:04.134  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 15:13:04.164  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 15:13:04.164  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 15:13:04.164  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 15:13:04.224  1016  1097 V AlarmManager: waitForAlarm result :4
,09-13 15:13:04.234   279  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
09-13 15:13:04.234   279  1011 D Netd    : getNetworkForDns: using netid 0 for uid 10011
,09-13 15:13:04.234  1016  1016 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,09-13 15:13:04.244  1016  1016 V AlarmManagerEXT: <AppSync3 Whitelist>
,09-13 15:13:04.244  1016  1016 V AlarmManagerEXT: (AppSync) ### 0 added ###
,09-13 15:13:04.244  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-13 15:13:04.244  1173  1173 D KeyguardUpdateMonitor: handleTimeUpdate
,09-13 15:13:04.264  1173  1173 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-13 15:13:04.264  1016  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:13:04.264  1016  1043 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-13 15:13:04.264  1016  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-13 15:13:04.264  1173  1173 D SecKeyguardClockView: HomeTimezone(): 1
,09-13 15:13:04.274  1173  1173 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 15:13:04.274  1173  1173 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,09-13 15:13:04.274  1173  1173 I KeyguardEffectViewController: *** don't update sliding image ***
,09-13 15:13:04.294  1173  1173 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 15:13:04.314  1173  1173 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 15:13:04.314  1173  1173 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 15:13:04.334  1173  1173 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-13 15:13:05.114   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 15:13:06.094   290   290 E SMD     : DCD OFF
,09-13 15:13:06.114   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,09-13 15:13:06.114  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 15:13:06.114  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:13:07.114   327   327 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-13 15:13:09.094   290   290 E SMD     : DCD OFF
,09-13 15:13:09.114  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 15:13:09.114  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9fdf00e added. We now have 6 listener(s)
09-13 15:13:09.114  7106  7300 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 15:13:09.114  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 15:13:09.114  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1917aa2f added. We now have 7 listener(s)
,09-13 15:13:09.114  7106  7300 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 15:13:09.114  7106  7300 I System.out: IsBluetoothEnabled
,09-13 15:13:09.124  7106  7300 D BluetoothAdapter: disable()
,09-13 15:13:09.124  1016  1079 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-13 15:13:09.124  7106  7300 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:09.124  7106  7300 D BluetoothAdapter: enable()
,09-13 15:13:09.134  1016  1474 W ActivityManager: Permission Denial: getCurrentUser() from pid=7106, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-13 15:13:09.134  1016  1474 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-13 15:13:09.134  1016  1474 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7106, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-13 15:13:09.134  1016  1474 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-13 15:13:09.134  1016  1474 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-13 15:13:09.134  1016  1474 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-13 15:13:09.134  1016  1474 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-13 15:13:09.134  1016  1474 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-13 15:13:09.134  1016  1474 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-13 15:13:09.134  1016  1474 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-13 15:13:09.144  1016  1474 D SettingsProvider: name = bluetooth_on,
,09-13 15:13:09.144  1016  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-13 15:13:09.144  1016  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-13 15:13:09.154  1016  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-13 15:13:09.154  3238  3310 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
09-13 15:13:09.154  3238  3310 D BluetoothAdapterProperties: Setting state to 11
09-13 15:13:09.154  3238  3310 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-13 15:13:09.154  3238  3310 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-13 15:13:09.154  3238  3310 D BluetoothAdapterService: updateAdapterState state is 11
09-13 15:13:09.154  3238  3310 D BluetoothAdapterService: Autoconnection is available 
,09-13 15:13:09.154  3238  3310 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
09-13 15:13:09.154  3238  3310 D BtConfig.SecureMode: isSecureModeOn:false
,09-13 15:13:09.154  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-13 15:13:09.154  3238  3310 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
09-13 15:13:09.164  1016  1079 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 15:13:09.154  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-13 15:13:09.164  1016  1079 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-13 15:13:09.154  3238  3310 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hfp.HeadsetService, state= 10
09-13 15:13:09.154  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-13 15:13:09.154  3238  3310 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.a2dp.A2dpService, state= 10
09-13 15:13:09.154  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-13 15:13:09.154  3238  3310 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hid.HidService, state= 10
09-13 15:13:09.154  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-13 15:13:09.154  3238  3310 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.hdp.HealthService, state= 10
09-13 15:13:09.154  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-13 15:13:09.154  3238  3310 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.pan.PanService, state= 10
09-13 15:13:09.154  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-13 15:13:09.154  3238  3310 W BluetoothAdapterService: isProfileEnabled(): profile com.android.bluetooth.map.BluetoothMapService, state= 10
09-13 15:13:09.154  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-13 15:13:09.154  3238  3310 W BluetoothAdapterService: isProfileEnabled(): profile com.broadcom.bt.service.sap.SapService, state= 10
09-13 15:13:09.154  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-13 15:13:09.154  3238  3310 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-13 15:13:09.154  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-13 15:13:09.154  3238  3310 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-13 15:13:09.154  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-13 15:13:09.154  3238  3310 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-13 15:13:09.154  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-13 15:13:09.154  3238  3310 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-13 15:13:09.154  3238  3310 W BluetoothAdapterService: Unable to start service com.android.bluetooth.gatt.GattService. Invalid state: 12
09-13 15:13:09.154  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
09-13 15:13:09.154  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-13 15:13:09.154  3238  3310 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-13 15:13:09.164  1016  1079 W ActivityManager: u,serId = 0, bbcId = -10000
09-13 15:13:09.164  1016  1079 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:09.164  1016  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-13 15:13:09.164  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
09-13 15:13:09.164  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-13 15:13:09.164  3238  3310 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-13 15:13:09.164  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-13 15:13:09.164  1016  1016 I InputMethodManagerService: [BT Setting State] State =11
,09-13 15:13:09.164  3238  3238 D HeadsetService: Received start request. Starting profile...
09-13 15:13:09.164  3238  3238 D HeadsetService: start()
09-13 15:13:09.164  3238  3238 D HeadsetStateMachine: make
,09-13 15:13:09.174  3238  3238 E HeadsetStateMachine: # of Max HF connection is 2
,09-13 15:13:09.184  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-13 15:13:09.184  1892  1892 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-13 15:13:09.184  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:13:09.184  1173  1173 D BluetoothTile:  getBluetoothState : 11
,09-13 15:13:09.184  4811  4811 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-13 15:13:09.194  1016  1850 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:13:09.194  1016  1850 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 15:13:09.194  1016  1850 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:09.194  1016  1850 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-13 15:13:09.194  1016  1850 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-13 15:13:09.194  1016  1463 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-13 15:13:09.194  1016  1489 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-13 15:13:09.194  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-13 15:13:09.204  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:09.204  1173  1765 D BluetoothTile:  handleUpdatestate:false name:null
09-13 15:13:09.204  1173  1765 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-13 15:13:09.204  1016  1487 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-13 15:13:09.204  1016  1487 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-13 15:13:09.204  1016  1487 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:13:09.204  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
09-13 15:13:09.204  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-13 15:13:09.204  3238  3310 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-13 15:13:09.204  1016  1487 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:09.204  1016  1487 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-13 15:13:09.204  1016  1463 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 15:13:09.204  1016  1463 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-13 15:13:09.204  1016  1463 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:09.204  1016  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:09.204  1016  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:09.214  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
09-13 15:13:09.214  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-13 15:13:09.214  3238  3310 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-13 15:13:09.214  2654  2654 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 15:13:09.214  1016  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-13 15:13:09.224  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-13 15:13:09.224  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:13:09.224  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 15:13:09.224  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:09.224  1016  1851 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-13 15:13:09.224  1016  1851 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-13 15:13:09.224  1016  1851 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:13:09.234  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,09-13 15:13:09.234  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-13 15:13:09.234  3238  3310 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-13 15:13:09.234  1016  1851 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:09.234  1016  1851 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-13 15:13:09.234  3238  3238 I bluedroid: get_profile_interface handsfree
,09-13 15:13:09.234  1016  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-13 15:13:09.234  1016  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-13 15:13:09.234  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:13:09.234  1016  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 15:13:09.234  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:09.234  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,09-13 15:13:09.244  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-13 15:13:09.244  3238  3310 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-13 15:13:09.244  1016  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 15:13:09.244  1016  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-13 15:13:09.244  4811  4811 D BluetoothNotiBroadcastReceiver: onReceive
09-13 15:13:09.244  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:09.244  1016  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:09.244  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:09.244  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
09-13 15:13:09.244  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-13 15:13:09.244  3238  3310 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-13 15:13:09.254  1016  1847 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-13 15:13:09.254  1016  1847 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-13 15:13:09.254  1016  1847 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:09.254  1016  1847 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:09.254  1016  1847 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-13 15:13:09.254  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:13:09.254  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-13 15:13:09.254  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-13 15:13:09.254  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-13 15:13:09.254  3238  3310 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-13 15:13:09.254  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-13 15:13:09.254  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-13 15:13:09.254  3238  3310 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-13 15:13:09.254  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.sapclient.SapClientService
09-13 15:13:09.254  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-13 15:13:09.254  3238  3310 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-13 15:13:09.254  3238  3310 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidDevService
09-13 15:13:09.254  3238  3310 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-13 15:13:09.254  3238  3310 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-13 15:13:09.254  3238  3310 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-13 15:13:09.254  3238  3238 E DualScoManager: Dual Sco Manager already instantiated
09-13 15:13:09.254  3238  3238 I DualScoManager: Set HeadsetServiceHelper
09-13 15:13:09.254  3238  3238 D BluetoothAtMessage: createCMTIContentObservers
,09-13 15:13:09.254  1016  1473 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-13 15:13:09.254  1016  1473 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-13 15:13:09.254  1016  1473 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-13 15:13:09.254  1016  1473 D SettingsProvider: selectionArgs: false
09-13 15:13:09.254  1016  1473 D SettingsProvider: selectionArgs: 1002
09-13 15:13:09.254  1016  1473 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-13 15:13:09.254  1016  1473 D SettingsProvider: ret = -1
,09-13 15:13:09.254  3238  7896 D HeadsetStateMachine: Enter Disconnected: -2
,09-13 15:13:09.264  3238  3238 D HeadsetService: mStartError = false
,09-13 15:13:09.264  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
,09-13 15:13:09.264  3238  3238 D HeadsetStateMachine: Try to query the phonestate on bind
09-13 15:13:09.264  1423  7843 I Telecom : BluetoothPhoneService: queryPhoneState
09-13 15:13:09.264  3238  7896 D HeadsetStateMachine: Clear mHeadsetBrsf
09-13 15:13:09.264  1423  1423 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-13 15:13:09.264  3238  7896 D HeadsetStateMachine: map size, before remove : 0
09-13 15:13:09.264  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-13 15:13:09.264  3238  7896 D HeadsetStateMachine: map size, after remove: 0
,09-13 15:13:09.264  1423  7843 I Telecom : BluetoothPhoneService: Result of Message : true
,09-13 15:13:09.274  3238  3238 D A2dpService: Received start request. Starting profile...
,09-13 15:13:09.274  3238  3238 D A2dpService: start()
09-13 15:13:09.274  3238  3238 I bluedroid: get_profile_interface avrcp
,09-13 15:13:09.274  3238  3238 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-13 15:13:09.274  3238  3238 D Avrcp   : Initialize Media Controller
09-13 15:13:09.274  3238  3238 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-13 15:13:09.274  3238  3238 E Avrcp   : getActiveSessions
,09-13 15:13:09.274  3238  3238 D Avrcp   : pick active media Controller
09-13 15:13:09.274  3238  3238 D Avrcp   : Get the active Media Controller 
,09-13 15:13:09.284  3238  3238 I Avrcp   :  Updating now playing list upon AVRCP Start,
09-13 15:13:09.284  3238  7897 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-13 15:13:09.284  3238  3238 D A2dpStateMachine: make
09-13 15:13:09.284  3238  3238 I bluedroid: get_profile_interface a2dp
,09-13 15:13:09.284  3238  7899 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-13 15:13:09.284  3238  3238 E bt-btif : warning : media task started media_task_refcnt 1 
,09-13 15:13:09.284  3238  3238 D A2dpService: mStartError = false
09-13 15:13:09.284  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
09-13 15:13:09.294  3238  7898 D A2dpStateMachine: Enter Disconnected: -2,
,09-13 15:13:09.294  3238  3238 D HidService: Received start request. Starting profile...
09-13 15:13:09.294  3238  3238 D HidService: start()
09-13 15:13:09.294  3238  3238 I bluedroid: get_profile_interface hidhost
09-13 15:13:09.294  3238  3238 D HidService: setHidService(): set to: null
09-13 15:13:09.294  3238  3238 D HidService: mStartError = false
09-13 15:13:09.294  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
,09-13 15:13:09.294  3238  3238 D HealthService: Received start request. Starting profile...
09-13 15:13:09.294  3238  3238 D HealthService: start()
,09-13 15:13:09.294  3238  3238 I bluedroid: get_profile_interface health
,09-13 15:13:09.294  3238  3238 D HealthService: mStartError = false
09-13 15:13:09.294  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
,09-13 15:13:09.294  3238  3238 D HeadsetStateMachine: Proxy object connected
,09-13 15:13:09.294  3238  3238 D PanService: Received start request. Starting profile...
09-13 15:13:09.294  3238  3238 D PanService: start()
09-13 15:13:09.294  3238  3238 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 15:13:09.294  3238  3238 I bluedroid: get_profile_interface pan
09-13 15:13:09.294  3238  3238 D PanService: mStartError = false
09-13 15:13:09.294  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
09-13 15:13:09.294  3238  3238 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-13 15:13:09.294  3238  7896 D HeadsetStateMachine: Disconnected process message: 11
09-13 15:13:09.294  3238  3238 D BluetoothMapService: Received start request. Starting profile...
09-13 15:13:09.294  3238  3238 D BluetoothMapService: start()
,09-13 15:13:09.304  3238  3238 D BluetoothMapService: mStartError = false
,09-13 15:13:09.304  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
09-13 15:13:09.304  3238  3238 D HeadsetPhoneState: sendDeviceDataStateChanged
09-13 15:13:09.304  3238  3238 D HeadsetPhoneState: Signal level : previous=0 curr=4
,09-13 15:13:09.304  3238  7897 D BluetoothMediaBrowser: no now playing list
09-13 15:13:09.304  3238  3238 D SapService: Received start request. Starting profile...
09-13 15:13:09.304  3238  3238 D SapService: start()
09-13 15:13:09.304  3238  3238 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-13 15:13:09.304  3238  3238 I bluedroid: get_profile_interface sap
09-13 15:13:09.304  3238  3238 D SapService: mStartError = false
09-13 15:13:09.304  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
09-13 15:13:09.304  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-13 15:13:09.304  3238  3238 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-13 15:13:09.304  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-13 15:13:09.304  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-13 15:13:09.304  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-13 15:13:09.304  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-13 15:13:09.304  3238  7896 D HeadsetStateMachine: Disconnected process message: 18
09-13 15:13:09.304  3238  7896 D HeadsetStateMachine: Disconnected process message: 10
09-13 15:13:09.304  3238  7896 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-13 15:13:09.304  3238  7897 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
09-13 15:13:09.304  3238  7896 D HeadsetStateMachine: Disconnected process message: 11
,09-13 15:13:09.314  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-13 15:13:09.324  3238  3238 E BluetoothAdapterService(323278525): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-13 15:13:09.324  3238  3310 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-13 15:13:09.324  3238  3310 I bluedroid: enable
,09-13 15:13:09.334  3238  3313 E bt-btif : Calling BTA_HhEnable
,09-13 15:13:09.334  3238  3313 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-13 15:13:09.334  3238  3313 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-13 15:13:09.334  3238  3313 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-13 15:13:09.334  3238  3313 D BluetoothAdapterProperties: Address is:08:EC:A9:50:75:41
,09-13 15:13:09.334  3238  3313 E BluetoothServiceJni: populateRssiValuesNative
09-13 15:13:09.334  3238  3313 I bluedroid: getModelRssiValues
09-13 15:13:09.334  3238  3313 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-13 15:13:09.334  3238  3313 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-13 15:13:09.334  1016  1016 D SettingsProvider: name = bluetooth_name
,09-13 15:13:09.334  3238  3313 D BluetoothAdapterProperties: Name is: Galaxy A3
,09-13 15:13:09.344  3238  3313 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-13 15:13:09.344  3238  3313 D BluetoothAdapterProperties: Scan Mode:20
09-13 15:13:09.344  3238  3313 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 15:13:09.344  3238  3313 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EA:82
09-13 15:13:09.344  3238  3313 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
09-13 15:13:09.344  3238  3313 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
,09-13 15:13:09.344  3238  3313 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-13 15:13:09.344  3238  3313 E bt-btif : JVenable fails
,09-13 15:13:09.344  3238  3313 D bte_conf: Device ID record 1 : primary
09-13 15:13:09.344  3238  3313 D bte_conf:   vendorId            = 0075
09-13 15:13:09.344  3238  3313 D bte_conf:   vendorIdSource      = 0001
09-13 15:13:09.344  3238  3313 D bte_conf:   product             = 0100
09-13 15:13:09.344  3238  3313 D bte_conf:   version             = 0200
09-13 15:13:09.344  3238  3313 D bte_conf:   clientExecutableURL = 
09-13 15:13:09.344  3238  3313 D bte_conf:   serviceDescription  = 
09-13 15:13:09.344  3238  3313 D bte_conf:   documentationURL    = 
09-13 15:13:09.344  3238  3313 D bte_conf: bte_load_did_conf no section named DID2.
09-13 15:13:09.344  3238  3313 E bt-btif : btif_config_get(L310): assert failed: section && *section && key && *key && name && *name && bytes && type
,09-13 15:13:09.344  3238  3313 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-13 15:13:09.344  3238  3310 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-13 15:13:09.344  3238  3310 D BluetoothAdapterProperties: ScanMode =  20
09-13 15:13:09.344  3238  3310 D BluetoothAdapterProperties: State =  11
,09-13 15:13:09.344  1016  1028 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-13 15:13:09.344  3238  3310 D BluetoothAdapterProperties: Setting state to 12
09-13 15:13:09.344  3238  3310 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-13 15:13:09.344  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-13 15:13:09.354  3238  3313 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-13 15:13:09.354  3238  3313 D BluetoothAdapterProperties: Scan Mode:21
09-13 15:13:09.354  3238  3313 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 15:13:09.354  1016  1221 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-13 15:13:09.354  1016  1221 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-13 15:13:09.354  1016  1221 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-13 15:13:09.354  1016  1221 D SettingsProvider: selectionArgs: false
09-13 15:13:09.354  1016  1221 D SettingsProvider: selectionArgs: 1002
09-13 15:13:09.354  1016  1221 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-13 15:13:09.354  1016  1221 D SettingsProvider: ret = -1
,09-13 15:13:09.354  3238  3310 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-13 15:13:09.354  3238  3310 D BluetoothAdapterService: updateAdapterState state is 12
,09-13 15:13:09.354  1016  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-13 15:13:09.354  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-13 15:13:09.354  1016  3387 D SSRM:n  : SIOP:: AP = 330
,09-13 15:13:09.354  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:09.354  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 15:13:09.354  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:09.364  3238  3310 D BluetoothAdapterService: Autoconnection is available 
,09-13 15:13:09.364  3238  3310 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,09-13 15:13:09.364  3238  3310 D BluetoothAdapterService: starting service from this receiver
09-13 15:13:09.364  1016  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-13 15:13:09.364  1016  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-13 15:13:09.364  1016  1489 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:09.364  1016  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:09.364  1016  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:09.364  3238  3310 I BluetoothAdapterState: Entering On State from state = 11
,09-13 15:13:09.364  1423  1476 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-13 15:13:09.364  1016  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-13 15:13:09.364  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-13 15:13:09.374  1016  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:09.374  1016  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:09.374  1016  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:09.374  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:13:09.374  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:09.374  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:09.374  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:13:09.374  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:09.374  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:13:09.374  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:13:09.374  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:13:09.374  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 15:13:09.374  3238  3238 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-13 15:13:09.384  1423  1476 E BluetoothHeadset: BluetoothHeadset service is binded
,09-13 15:13:09.384  3238  3238 I BluetoothPbapService: Handler(): got msg=1,
,09-13 15:13:09.384  1016  1221 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-13 15:13:09.384  1016  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-13 15:13:09.384  1016  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 15:13:09.384  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-13 15:13:09.384  1016  1047 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-13 15:13:09.384  1436  1464 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-13 15:13:09.384  1436  1464 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-13 15:13:09.384  7851  7860 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 15:13:09.384  7851  7860 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-13 15:13:09.384  1016  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-13 15:13:09.384  1016  1047 D BluetoothPan: Binding service...
09-13 15:13:09.384  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-13 15:13:09.384  1447  1748 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 15:13:09.384  1447  1748 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-13 15:13:09.394  7106  7114 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 15:13:09.394  7106  7114 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-13 15:13:09.394  4811  7841 D BluetoothPan: Binding service...
,09-13 15:13:09.394  1016  1016 D BluetoothA2dp: Proxy object connected
,09-13 15:13:09.394  3238  7904 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-13 15:13:09.404  1016  1016 D BluetoothPan: BluetoothPAN Proxy object connected
,09-13 15:13:09.404  3238  7904 D BluetoothSocket: bindListen(): myUserId = 0
,09-13 15:13:09.404  3238  7904 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 15:13:09.404  3238  7904 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,09-13 15:13:09.404  3238  7904 D BluetoothSocket: bindListen(), new LocalSocket 
09-13 15:13:09.404  3238  7904 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-13 15:13:09.404  3238  7904 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@127d458d
09-13 15:13:09.404  3238  7904 D BluetoothSocket: channel: 19
09-13 15:13:09.414  3238  7904 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-13 15:13:09.534  1016  1047 I art     : Explicit concurrent mark sweep GC freed 54292(3MB) AllocSpace objects, 10(161KB) LOS objects, 33% free, 23MB/34MB, paused 2.371ms total 144.439ms
09-13 15:13:09.534  1016  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-13 15:13:09.534  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-13 15:13:09.534  1016  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:09.534  1016  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:09.534  1016  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:09.544  4811  4811 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 15:13:09.544  4811  4811 D PanProfile: Bluetooth service connected
,09-13 15:13:09.544  3238  3360 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 15:13:09.544  3238  3360 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-13 15:13:09.544  4811  4826 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-13 15:13:09.544  1016  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-13 15:13:09.544  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-13 15:13:09.544  1016  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:09.544  1016  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:09.544  1016  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:09.544  4811  4826 E BluetoothHeadset: BluetoothHeadset service is binded
,09-13 15:13:09.544  1016  1047 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-13 15:13:09.544  1016  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-13 15:13:09.544  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-13 15:13:09.544  1016  1047 E BluetoothHeadset: BluetoothHeadset service is binded
,09-13 15:13:09.544  4811  4811 D HeadsetProfile: Bluetooth service connected
,09-13 15:13:09.554  1423  7843 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-13 15:13:09.554  1016  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-13 15:13:09.554  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-13 15:13:09.554  1016  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:09.554  1016  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:09.554  1016  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:09.554  1423  7843 E BluetoothHeadset: BluetoothHeadset service is binded
,09-13 15:13:09.554  2654  4252 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 15:13:09.554  2654  4252 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-13 15:13:09.554  1757  1772 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 15:13:09.554  1757  1772 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-13 15:13:09.554  1016  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
09-13 15:13:09.554  1016  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-13 15:13:09.554  1447  1468 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-13 15:13:09.554  1016  1047 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-13 15:13:09.554  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-13 15:13:09.554  1016  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:09.554  1016  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 15:13:09.554  1016  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:09.554  1447  1468 E BluetoothHeadset: BluetoothHeadset service is binded
09-13 15:13:09.554  4811  4833 D Bluetoothsap: onBluetoothStateChange: up=true
09-13 15:13:09.554  4811  4833 D Bluetoothsap: Binding service...
,09-13 15:13:09.554  4811  4833 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-13 15:13:09.564  1016  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,09-13 15:13:09.564  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-13 15:13:09.564  1016  1047 W ActivityManager: userId = 0, bbcId = -10000,
09-13 15:13:09.564  1016  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:09.564  1016  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-13 15:13:09.564  4811  4833 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-13 15:13:09.564  3238  7844 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 15:13:09.564  3238  7844 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-13 15:13:09.564  4811  4811 D Bluetoothsap: BluetoothSAP Proxy object connected
09-13 15:13:09.564  1016  1047 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-13 15:13:09.564  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-13 15:13:09.564  4811  4811 D SapProfile: Bluetooth service connected
09-13 15:13:09.564  4811  4811 D Bluetoothsap: getConnectedDevices()
09-13 15:13:09.564  1016  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:09.564  1016  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:09.564  1016  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:09.564  4811  4826 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-13 15:13:09.564  4811  4826 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-13 15:13:09.564  3238  3238 D BluetoothA2dp: Proxy object connected
09-13 15:13:09.564  3238  3238 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-13 15:13:09.564  1423  1476 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0,
09-13 15:13:09.564  1016  1047 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-13 15:13:09.564  1016  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:09.564  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-13 15:13:09.564  1016  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:09.564  1016  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:09.564  1423  1476 E BluetoothHeadset: BluetoothHeadset service is binded
,09-13 15:13:09.564  4811  4833 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 15:13:09.574  1016  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-13 15:13:09.574  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0,
09-13 15:13:09.574  1016  1047 W ActivityManager: userId = 0, bbcId = -10000,
09-13 15:13:09.574  1016  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:09.574  1016  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:09.574  4811  4811 D BluetoothPbap: Proxy object connected
09-13 15:13:09.574  4811  4811 D PbapServerProfile: Bluetooth service connected
09-13 15:13:09.574  1173  1205 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-13 15:13:09.574  1173  1205 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-13 15:13:09.574  4811  4826 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 15:13:09.574  1016  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-13 15:13:09.574  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-13 15:13:09.574  1016  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:09.574  1016  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:09.574  1016  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:09.574  4811  4833 D BluetoothMap: onBluetoothStateChange: up=true,
09-13 15:13:09.574  4811  4811 D BluetoothInputDevice: Proxy object connected
09-13 15:13:09.574  4811  4811 D HidProfile: Bluetooth service connected
,09-13 15:13:09.574  1016  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-13 15:13:09.574  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-13 15:13:09.574  1016  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:09.574  1016  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:09.574  1016  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:09.584  4811  7841 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 15:13:09.584  4811  7841 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-13 15:13:09.584  1016  1047 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-13 15:13:09.584  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-13 15:13:09.584  4811  4811 D BluetoothMap: Proxy object connected
09-13 15:13:09.584  4811  4811 D MapProfile: Bluetooth service connected
09-13 15:13:09.584  4811  4811 D BluetoothMap: getConnectedDevices()
09-13 15:13:09.584  1016  1047 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:09.584  1016  1047 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:09.584  1016  1047 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:09.584  1423  7843 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-13 15:13:09.584  1423  7843 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-13 15:13:09.584  1016  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-13 15:13:09.584  1016  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-13 15:13:09.584  1016  1016 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-13 15:13:09.584  1016  1016 I InputMethodManagerService: [BT Setting State] State =12
09-13 15:13:09.584  1016  1016 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-13 15:13:09.584  4811  4811 D BluetoothA2dp: Proxy object connected
09-13 15:13:09.584  4811  4811 D A2dpProfile: Bluetooth service connected
,09-13 15:13:09.594  1423  1423 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@189019d1, true
,09-13 15:13:09.594  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,09-13 15:13:09.594  1423  1423 D BluetoothHeadset: registerMessageListener
,09-13 15:13:09.594  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-13 15:13:09.594  1173  1765 D BluetoothTile:  handleUpdatestate:false name:null
09-13 15:13:09.594  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:13:09.594  1173  1173 D BluetoothTile:  getBluetoothState : 12
09-13 15:13:09.594  1173  1765 D BluetoothTile:  handleUpdatestate:false name:null
,09-13 15:13:09.594  1892  1892 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-13 15:13:09.594  1173  1765 D BluetoothTile:  handleUpdatestate:false name:null
,09-13 15:13:09.604  1016  1463 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-13 15:13:09.604  1016  1851 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-13 15:13:09.604  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-13 15:13:09.604  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:09.614  3238  3358 D HeadsetService: registerMessageListener
,09-13 15:13:09.614  3238  3358 D HeadsetService: registerMessageListener
09-13 15:13:09.614  3238  7896 D HeadsetStateMachine: Disconnected process message: 70
,09-13 15:13:09.614  3238  7896 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2295c342,
09-13 15:13:09.614  1423  1423 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-13 15:13:09.614  4811  4811 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:13:09.614  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-13 15:13:09.614  3238  7905 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-13 15:13:09.614  4811  4811 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,09-13 15:13:09.614  1423  1423 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-13 15:13:09.614  4811  4811 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-13 15:13:09.614  1423  1423 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-13 15:13:09.614  4811  4811 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.,
09-13 15:13:09.614  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-13 15:13:09.614  4811  4811 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-13 15:13:09.614  3238  7896 D HeadsetStateMachine: Disconnected process message: 9,
09-13 15:13:09.614  3238  7896 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-13 15:13:09.624   284   680 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-13 15:13:09.624   284   680 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-13 15:13:09.624   284   680 V voice   : voice_set_parameters: exit with code(-2)
09-13 15:13:09.624   284   680 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-13 15:13:09.624   284   680 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-13 15:13:09.624   284   680 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
,09-13 15:13:09.624   284   680 V audio_hw_primary: adev_set_parameters: exit
09-13 15:13:09.624  3238  7905 D BluetoothSocket: bindListen(): myUserId = 0
09-13 15:13:09.624  3238  7905 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 15:13:09.624  3238  7896 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-13 15:13:09.624  3238  7905 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[82]}
09-13 15:13:09.624  3238  7905 D BluetoothSocket: bindListen(), new LocalSocket 
09-13 15:13:09.624  3238  7905 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-13 15:13:09.624  3238  7905 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@224e6f53
09-13 15:13:09.624  3238  7905 D BluetoothSocket: channel: 5
,09-13 15:13:09.624  4811  4811 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 15:13:09.624  1016  1473 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-13 15:13:09.624  1016  1473 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-13 15:13:09.624  1016  1473 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:09.624  1016  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:09.624  1016  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-13 15:13:09.634  2654  2654 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 15:13:09.634  4811  4811 D DockEventReceiver: finishStartingService: stopping service
,09-13 15:13:09.634  4811  4811 D BluetoothNotiBroadcastReceiver: onReceive
,09-13 15:13:09.644  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-13 15:13:09.644  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-13 15:13:09.644  3238  3238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1344d6bd
,09-13 15:13:09.644  3238  3238 D BtConfig.SecureMode: isSecureModeOn:false
,09-13 15:13:09.644  1016  1851 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-13 15:13:09.644  1016  1851 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-13 15:13:09.654  1016  1851 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:13:09.654  1016  1851 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-13 15:13:09.654  1016  1851 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-13 15:13:09.654  1016  1029 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-13 15:13:09.664  3238  7910 D BluetoothSocket: bindListen(): myUserId = 0
09-13 15:13:09.664  3238  7910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 15:13:09.674  3238  7910 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[88]}
09-13 15:13:09.674  3238  7910 D BluetoothSocket: bindListen(), new LocalSocket 
09-13 15:13:09.674  3238  7910 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-13 15:13:09.674  3238  7910 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@cc6adaf
09-13 15:13:09.674  3238  7910 D BluetoothSocket: channel: 12
09-13 15:13:09.674  3238  7910 I BtOppRfcommListener: Accept thread started.
,09-13 15:13:10.164  7106  7300 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:13:10.164  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:10.164  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:10.164  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 15:13:10.164  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:10.164  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:13:10.164  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:13:10.164  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:13:10.164  7106  7300 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 15:13:10.164  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 15:13:10.164  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3447f83c added. We now have 8 listener(s)
,09-13 15:13:10.164  7106  7300 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 15:13:10.164  1016  1850 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-13 15:13:10.164  1016  1850 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-13 15:13:10.164  1016  1850 D SecContentProvider2: mCursor = null
,09-13 15:13:10.164  1016  1850 D WifiService: setWifiEnabled: false pid=7106, uid=10170
,09-13 15:13:10.164  1016  1850 D SettingsProvider: name = wifi_on
,09-13 15:13:10.174  7106  7300 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:10.174  1016  1029 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-13 15:13:10.174  1016  1029 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-13 15:13:10.174  1016  1029 D SecContentProvider2: mCursor = null
,09-13 15:13:10.174  1016  1029 D WifiService: setWifiEnabled: true pid=7106, uid=10170
,09-13 15:13:10.174  1016  1029 W ActivityManager: Permission Denial: getCurrentUser() from pid=7106, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
,09-13 15:13:10.184  1016  1029 W WifiService: Failed getting userId using ActivityManagerNative
09-13 15:13:10.184  1016  1029 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7106, uid=10170 requires android.permission.INTERACT_ACROSS_USERS
09-13 15:13:10.184  1016  1029 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-13 15:13:10.184  1016  1029 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-13 15:13:10.184  1016  1029 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-13 15:13:10.184  1016  1029 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-13 15:13:10.184  1016  1029 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-13 15:13:10.184  1016  1029 D SettingsProvider: name = wifi_on
,09-13 15:13:10.194  1016  1128 E WifiHW  : ##################### set firmware type 0 #####################
,09-13 15:13:10.514  1016  1045 D Tethering: interfaceAdded wlan0
,09-13 15:13:10.524  1016  1132 E Tethering: No numeric data
,09-13 15:13:10.524  1016  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-13 15:13:10.524  1016  1132 D Tethering: clearTetheredNotification()
,09-13 15:13:10.524  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
09-13 15:13:10.524  1016  1125 V NetworkStats: performPollLocked(flags=0x1)
09-13 15:13:10.524  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-13 15:13:10.524  1173  1173 D HotspotTile: updateTetherState():false, false
,09-13 15:13:10.534  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 15:13:10.534  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-13 15:13:10.534  1016  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
09-13 15:13:10.534  1016  1045 D Tethering: interfaceStatusChanged wlan0, false
09-13 15:13:10.534  1016  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-13 15:13:10.534  1016  1132 D Tethering: InitialState.processMessage what=4
,09-13 15:13:10.544  1016  1132 E Tethering: No numeric data,
09-13 15:13:10.544  1016  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0,
09-13 15:13:10.544  1016  1132 D Tethering: clearTetheredNotification(),
09-13 15:13:10.544  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
09-13 15:13:10.544  1016  1125 V NetworkStats: performPollLocked() took 15ms,
,09-13 15:13:10.544  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-13 15:13:10.544  1173  1173 D HotspotTile: updateTetherState():false, false
,09-13 15:13:10.554  1016  1045 D Tethering: interfaceAdded p2p0
09-13 15:13:10.554  1016  1125 V NetworkStats: performPollLocked(flags=0x1)
09-13 15:13:10.554  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:13:10.554  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:13:10.554  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:13:10.554  1016  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-13 15:13:10.554  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 15:13:10.554  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-13 15:13:10.554  1016  1045 D Tethering: interfaceLinkStateChanged p2p0, false
,09-13 15:13:10.554  1016  1045 D Tethering: interfaceStatusChanged p2p0, false
09-13 15:13:10.564  1016  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-13 15:13:10.564   279  1015 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-13 15:13:10.564   279  1015 D SoftapController: Softap fwReload - Ok
,09-13 15:13:10.564  1016  1125 V NetworkStats: performPollLocked() took 13ms
09-13 15:13:10.564   279  1015 D CommandListener: Setting iface cfg
09-13 15:13:10.564   279  1015 D CommandListener: Trying to bring down wlan0
,09-13 15:13:10.564  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:13:10.564   279  1015 D CommandListener: Clearing all IP addresses on wlan0
,09-13 15:13:10.564  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:13:10.564  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:13:10.574  1016  1128 E WifiHW  : supplicant_name : p2p_supplicant
,09-13 15:13:10.584  1016  1128 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-13 15:13:10.594  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 15:13:10.594  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-13 15:13:10.594  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-13 15:13:10.594  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:13:10.594  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:10.594  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:10.594  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:13:10.594  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-13 15:13:10.594  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-13 15:13:10.604  1173  1765 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-13 15:13:10.604  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-13 15:13:10.604  4811  4811 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-13 15:13:10.604  1173  1173 D HotspotTile: onReceive : 2, 0
,09-13 15:13:10.604  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:10.614  1016  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-13 15:13:10.614  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-13 15:13:10.614  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:10.614  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:10.614  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-13 15:13:10.624  1623  1623 I Hs20UtilService: Starting #19
,09-13 15:13:10.624  1623  1650 I Hs20UtilService: Message received 5011
,09-13 15:13:10.624  7416  7416 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-13 15:13:10.624  7416  7416 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-13 15:13:10.624  7416  7416 D SecurityLogAgent: StateMachine : Current State = 1
,09-13 15:13:10.624  7416  7416 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-13 15:13:10.634  7922  7922 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-13 15:13:10.634  7922  7922 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-13 15:13:10.634  7922  7922 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-13 15:13:10.644  7922  7922 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-13 15:13:10.654   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7922
09-13 15:13:10.654   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,09-13 15:13:10.654  7922  7922 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
,09-13 15:13:10.654  7922  7922 I wpa_supplicant: ssSupport state is = 1
09-13 15:13:10.654  7922  7922 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,09-13 15:13:10.654  7922  7922 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,09-13 15:13:10.654   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7922
09-13 15:13:10.654   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-13 15:13:10.814   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,09-13 15:13:10.814  7922  7922 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,09-13 15:13:10.854  7922  7922 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-13 15:13:10.854  7922  7922 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-13 15:13:10.864  7922  7922 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-13 15:13:10.864   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7922
09-13 15:13:10.864   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-13 15:13:10.864  7922  7922 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-13 15:13:10.864  7922  7922 I wpa_supplicant: ssSupport state is = 1
09-13 15:13:10.864  7922  7922 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-13 15:13:10.864  7922  7922 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-13 15:13:10.864  7922  7922 E wpa_supplicant: SIM READ ERROR
09-13 15:13:10.864  7922  7922 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-13 15:13:10.864  7922  7922 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-13 15:13:10.864  7922  7922 E wpa_supplicant: SIM READ ERROR,
09-13 15:13:10.864  7922  7922 I wpa_supplicant: Blacklist: Clear (all) 
09-13 15:13:10.874  7922  7922 I wpa_supplicant: wpa_default_ap_write_once
09-13 15:13:10.874  7922  7922 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-13 15:13:10.874  7922  7922 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-13 15:13:10.874  7922  7922 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-13 15:13:10.874  7922  7922 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-13 15:13:10.874  7922  7922 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-13 15:13:10.874  7922  7922 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-13 15:13:10.874  1016  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
09-13 15:13:10.874  1016  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-13 15:13:10.874  1016  1045 D Tethering: interfaceStatusChanged wlan0, false,
,09-13 15:13:10.954  7922  7922 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-13 15:13:11.094  7922  7922 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-13 15:13:11.094  7922  7922 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-13 15:13:11.104  7922  7922 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-13 15:13:11.104   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7922
09-13 15:13:11.104   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
09-13 15:13:11.114  7922  7922 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-13 15:13:11.114  7922  7922 I wpa_supplicant: ssSupport state is = 1,
09-13 15:13:11.114  7922  7922 I wpa_supplicant: Ctrl_iface: loading cred from phone
,09-13 15:13:11.114  7922  7922 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-13 15:13:11.124  7922  7922 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-13 15:13:11.124   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7922
09-13 15:13:11.124   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-13 15:13:11.124  7922  7922 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-13 15:13:11.124  1016  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-13 15:13:11.124  7922  7922 I wpa_supplicant: ssSupport state is = 1
09-13 15:13:11.124  7922  7922 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-13 15:13:11.124  7922  7922 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-13 15:13:11.124  7922  7922 E wpa_supplicant: SIM READ ERROR
09-13 15:13:11.124  7922  7922 I wpa_supplicant: wpa_default_ap_write_once
09-13 15:13:11.124  7922  7922 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-13 15:13:11.124  7922  7922 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-13 15:13:11.124  1016  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-13 15:13:11.124  1016  1045 D Tethering: interfaceStatusChanged p2p0, false
09-13 15:13:11.134  1016  1045 D Tethering: interfaceLinkStateChanged p2p0, false
09-13 15:13:11.134  1016  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-13 15:13:11.134  1016  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-13 15:13:11.174  7922  7922 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-13 15:13:11.174  7922  7922 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-13 15:13:11.244  7922  7922 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-13 15:13:11.244  7922  7922 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=,
09-13 15:13:11.244  7922  7922 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-13 15:13:11.254  1016  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
09-13 15:13:11.254  1016  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-13 15:13:11.254  7922  7922 I wpa_supplicant: HOTSPOT20_ENABLE called,
09-13 15:13:11.264  7922  7922 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-13 15:13:11.264  7922  7922 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-13 15:13:11.264  7922  7922 E wpa_supplicant: SIM READ ERROR,
09-13 15:13:11.264  7922  7922 I wpa_supplicant: Blacklist: Clear (all) ,
,09-13 15:13:11.284  7922  7922 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-13 15:13:11.294  7922  7922 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-13 15:13:11.304  1016  1128 D WifiConfigStore: Loading config and enabling all networks 
,09-13 15:13:11.304  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 15:13:11.304  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 15:13:11.304  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 15:13:11.304  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:13:11.304  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:11.304  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:13:11.304  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:11.304  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-13 15:13:11.304  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-13 15:13:11.304  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-13 15:13:11.304  1173  1765 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-13 15:13:11.304  1173  1173 D HotspotTile: onReceive : 3, 0
,09-13 15:13:11.314  4811  4811 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-13 15:13:11.314  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:13:11.314  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:11.314  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:11.314  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:13:11.314  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:11.314  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:13:11.314  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:13:11.314  7106  7106 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:13:11.314  7106  7106 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 15:13:11.314  1016  1128 E WifiConfigStore: Not a HS20
,09-13 15:13:11.324  1016  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-13 15:13:11.324  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-13 15:13:11.324  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:13:11.324  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:11.324  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-13 15:13:11.324  1623  1623 I Hs20UtilService: Starting #20
,09-13 15:13:11.324  1016  1128 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-13 15:13:11.324  1623  1650 I Hs20UtilService: Message received 5011
,09-13 15:13:11.324  1016  1128 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-13 15:13:11.324  7922  7922 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-13 15:13:11.324  7922  7922 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-13 15:13:11.334  7922  7922 I wpa_supplicant: reset timer : RESET_TIMER 0
09-13 15:13:11.334  7922  7922 I wpa_supplicant: P2P: Current p2p state = IDLE
09-13 15:13:11.334  7922  7922 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-13 15:13:11.334  7922  7922 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-13 15:13:11.334  7922  7922 I wpa_supplicant: First Scan Start
09-13 15:13:11.334  7922  7922 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-13 15:13:11.334  1016  1128 D WifiNative-wlan0: Setting external_sim to 1
09-13 15:13:11.334  7416  7416 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-13 15:13:11.334  1016  1128 D WifiStateMachine: Setting OUI to DA-A1-19
09-13 15:13:11.334  1016  1128 I WifiNative-HAL: startHal
09-13 15:13:11.334  1016  1128 E wifi    : getStaticLongField sWifiHalHandle 0x9f5d388c
,09-13 15:13:11.334  1016  1128 I WifiNative-HAL: Could not start hal
09-13 15:13:11.334  7416  7416 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-13 15:13:11.334  7416  7416 D SecurityLogAgent: StateMachine : Current State = 1
,09-13 15:13:11.334  7416  7416 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-13 15:13:11.334  7432  7432 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,09-13 15:13:11.334  1016  1128 E WifiNative-wlan0: do suspend true
,09-13 15:13:11.334  1016  1127 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-13 15:13:11.334   279  1015 D CommandListener: Setting iface cfg
09-13 15:13:11.334   279  1015 D CommandListener: Trying to bring up p2p0
,09-13 15:13:11.334  1016  1127 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-13 15:13:11.334  1016  1127 D WifiP2pService: P2pEnablingState
09-13 15:13:11.344  1016  1127 D WifiP2pService: P2pEnablingState{ what=147457 }
09-13 15:13:11.344  1016  1127 D WifiP2pService: P2p socket connection successful
09-13 15:13:11.344  1016  1127 D WifiP2pService: P2pEnabledState
,09-13 15:13:11.344  1016  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-13 15:13:11.344  1016  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-13 15:13:11.344  1016  1130 E ConnectivityService: updateNetworkInfo()
,09-13 15:13:11.344  1016  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,09-13 15:13:11.344  1016  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-13 15:13:11.344  1016  1128 E WifiNative-wlan0: invaild command id : 215
09-13 15:13:11.344  1016  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-13 15:13:11.344  1016  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-13 15:13:11.344  1016  1128 E WifiNative-wlan0: invaild command id : 215
09-13 15:13:11.344  1016  1016 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-13 15:13:11.354  1016  1016 D WifiScanningService: SCAN_AVAILABLE : 3
09-13 15:13:11.354  1016  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-13 15:13:11.354  1016  1151 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 15:13:11.354  1016  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-13 15:13:11.354  1016  1151 I WifiNative-HAL: startHal
09-13 15:13:11.354  1016  1048 D WifiDisplayController: disconnect
09-13 15:13:11.354  1016  1016 D RttService: SCAN_AVAILABLE : 3
09-13 15:13:11.354  1016  1048 D WifiDisplayController: updateConnection
09-13 15:13:11.354  1016  1152 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:13:11.354  1016  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-13 15:13:11.354  7922  7922 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-13 15:13:11.354  1016  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-13 15:13:11.354  7922  7922 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-13 15:13:11.354  1016  1127 D WifiNative-p2p0: p2pGetDeviceAddress
,09-13 15:13:11.354  7922  7922 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-13 15:13:11.354  1016  1128 E WifiStateMachine: Failed to set frequency band 0
09-13 15:13:11.354  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-13 15:13:11.354  4811  4811 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-13 15:13:11.354  1016  1128 D SecContentProvider2: mCursor = null
09-13 15:13:11.354  4811  4811 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-13 15:13:11.354  1016  1151 E wifi    : getStaticLongField sWifiHalHandle 0x9e5939bc
09-13 15:13:11.354  1016  1127 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
09-13 15:13:11.354  1016  1151 I WifiNative-HAL: Could not start hal
09-13 15:13:11.354  1016  1151 E WifiScanningService: could not start HAL
09-13 15:13:11.354  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-13 15:13:11.364  1016  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-13 15:13:11.364  1016  1048 D WifiDisplayAdapter: onP2pDisconnected
,09-13 15:13:11.364  1016  1048 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-13 15:13:11.364  1016  1048 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-13 15:13:11.364  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
09-13 15:13:11.364  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-13 15:13:11.364  1016  1028 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-13 15:13:11.364  1016  1128 D SecContentProvider2: mCursor = null
09-13 15:13:11.364  1016  1127 D WifiP2pService: DeviceAddress: 0a:75:42
09-13 15:13:11.364  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-13 15:13:11.364  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-13 15:13:11.364  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-13 15:13:11.364  1016  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Galaxy A3
09-13 15:13:11.364  1016  1048 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:75:42
09-13 15:13:11.364  1016  1048 D WifiDisplayController:  primary type: 10-0050F204-5
09-13 15:13:11.364  1016  1048 D WifiDisplayController:  secondary type: null
09-13 15:13:11.364  1016  1048 D WifiDisplayController:  wps: 0
09-13 15:13:11.364  1016  1048 D WifiDisplayController:  grpcapab: 0
09-13 15:13:11.364  1016  1048 D WifiDisplayController:  devcapab: 0
09-13 15:13:11.364  1016  1048 D WifiDisplayController:  status: 3
09-13 15:13:11.364  1016  1048 D WifiDisplayController:  wfdInfo: null
09-13 15:13:11.364  1016  1048 D WifiDisplayController:  groupownerAddress: null
09-13 15:13:11.364  1016  1048 D WifiDisplayController:  GOdeviceName: null
09-13 15:13:11.364  1016  1048 D WifiDisplayController:  interfaceAddress: 
09-13 15:13:11.364  1016  1048 D WifiDisplayController:  SConnectInfo : null
,09-13 15:13:11.364  4811  4811 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-13 15:13:11.364  4811  4886 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-13 15:13:11.374  7766  7766 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-13 15:13:11.374  7766  7766 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-13 15:13:11.374  7766  7766 D FileShare-Client: Outbound.stopDelayTimer - 
,09-13 15:13:11.384  7401  7401 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-13 15:13:11.384  1016  1127 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-13 15:13:11.384  1016  1127 D WifiP2pService: InactiveState
,09-13 15:13:11.384  1016  1127 D WifiP2pService: InactiveState{ what=143376 }
,09-13 15:13:11.384  1016  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-13 15:13:11.384  7922  7922 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-13 15:13:11.384  1016  1127 D WifiP2pService: InactiveState{ what=143376 }
,09-13 15:13:11.394  1016  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-13 15:13:11.534  1016  1045 D Tethering: interfaceLinkStateChanged p2p0, false
,09-13 15:13:11.534  1016  1045 D Tethering: interfaceStatusChanged p2p0, false
,09-13 15:13:11.534  1016  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-13 15:13:12.084   290   290 E SMD     : DCD OFF,
,09-13 15:13:12.214  7106  7300 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 15:13:12.214  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:12.214  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:12.214  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:13:12.214  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:12.214  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:13:12.214  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:13:12.214  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:13:12.214  7106  7300 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 15:13:12.214  7106  7300 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-13 15:13:12.214  7106  7300 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-13 15:13:12.214  7106  7300 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1affcbf3 Bundle[{}]
,09-13 15:13:12.214  7106  7300 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 15:13:12.224  7106  7300 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-13 15:13:12.224  7106  7300 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-13 15:13:12.224  7106  7300 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-13 15:13:12.224  7106  7300 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-13 15:13:12.224  7106  7300 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 15:13:12.234  7106  7300 I System.out: Running OutgoingSocketThread
,09-13 15:13:12.234  7106  7931 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1444)
,09-13 15:13:12.234  7106  7931 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 58268
,09-13 15:13:12.234  7106  7931 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 15:13:12.584  7922  7922 I wpa_supplicant: nl80211: Received scan results (30 BSSes),
09-13 15:13:12.584  7922  7922 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-13 15:13:12.584  7922  7922 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-13 15:13:12.584  7922  7922 I wpa_supplicant: Trying to associate with  'G700'
09-13 15:13:12.584  7922  7922 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-13 15:13:12.584  7922  7922 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-13 15:13:12.584  1016  7928 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-13 15:13:12.594  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-13 15:13:12.594  1016  1128 D SecContentProvider2: mCursor = null
,09-13 15:13:12.694  7922  7922 E wpa_supplicant: Cmd 35605 not handled
,09-13 15:13:12.694  7922  7922 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-13 15:13:12.694  7922  7922 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-13 15:13:12.694  7922  7922 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-13 15:13:12.694  1016  1045 D Tethering: interfaceLinkStateChanged wlan0, false
09-13 15:13:12.694  7922  7922 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-13 15:13:12.694  1016  1045 D Tethering: interfaceStatusChanged wlan0, false
09-13 15:13:12.694  7922  7922 I wpa_supplicant: Associated with F4.99.3E
,09-13 15:13:12.694  7922  7922 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-13 15:13:12.694  7922  7922 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-13 15:13:12.694  1016  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-13 15:13:12.694  7922  7922 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030,
09-13 15:13:12.704  1016  1045 D Tethering: interfaceLinkStateChanged wlan0, false,
09-13 15:13:12.704  1016  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-13 15:13:12.704  1016  1045 D Tethering: interfaceStatusChanged wlan0, false
09-13 15:13:12.704  1016  1045 D Tethering: interfaceLinkStateChanged wlan0, false
,09-13 15:13:12.704  1016  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-13 15:13:12.704  1016  1045 D Tethering: interfaceStatusChanged wlan0, false
,09-13 15:13:12.704  1016  1045 D Tethering: interfaceLinkStateChanged wlan0, true,
09-13 15:13:12.704  1016  1045 D Tethering: interfaceStatusChanged wlan0, true
,09-13 15:13:12.704  1016  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-13 15:13:12.704  1016  1132 E Tethering: No numeric data,
09-13 15:13:12.704  1016  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-13 15:13:12.714  1016  1125 V NetworkStats: performPollLocked(flags=0x1)
09-13 15:13:12.704  1016  1132 D Tethering: clearTetheredNotification()
09-13 15:13:12.704  7922  7922 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-13 15:13:12.704  7922  7922 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
09-13 15:13:12.714  7922  7922 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,09-13 15:13:12.714  7922  7922 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-13 15:13:12.714  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:13:12.714  7922  7922 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-13 15:13:12.714  7922  7922 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-13 15:13:12.714  7922  7922 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-13 15:13:12.714  7922  7922 I wpa_supplicant: Blacklist: Clear (temp) 
09-13 15:13:12.714  7922  7922 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,09-13 15:13:12.714  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-13 15:13:12.714  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 15:13:12.714  1016  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-13 15:13:12.714  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-13 15:13:12.714  1173  1173 D HotspotTile: updateTetherState():false, false
,09-13 15:13:12.714  1016  1045 D Tethering: interfaceLinkStateChanged wlan0, true
09-13 15:13:12.714  1016  1045 D Tethering: interfaceStatusChanged wlan0, true
,09-13 15:13:12.724  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-13 15:13:12.724  1016  1128 D SecContentProvider2: mCursor = null
,09-13 15:13:12.724  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:13:12.724  1016  1125 V NetworkStats: performPollLocked() took 10ms
,09-13 15:13:12.724  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:13:12.724  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:13:12.724  1016  1128 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-13 15:13:12.734  1016  1128 E WifiConfigStore: setLastSelectedConfiguration -1
,09-13 15:13:12.744  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 15:13:12.744  1016  1128 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-13 15:13:12.744  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 15:13:12.744  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 15:13:12.744  1016  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 15:13:12.744  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:13:12.744  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:12.744  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:12.744  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:12.744  1016  1130 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-13 15:13:12.744  1016  1130 E ConnectivityService: updateNetworkInfo()
,09-13 15:13:12.744  1016  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 15:13:12.744  1016  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-13 15:13:12.744  1016  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-13 15:13:12.744  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:13:12.744  1016  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:12.744  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-13 15:13:12.744  1623  1623 I Hs20UtilService: Starting #21
,09-13 15:13:12.754  1623  1650 I Hs20UtilService: Message received 5007
,09-13 15:13:12.754  4811  4811 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-13 15:13:12.754  4811  4811 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-13 15:13:12.754  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-13 15:13:12.754  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-13 15:13:12.754  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-13 15:13:12.754  4811  4811 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-13 15:13:12.764  4811  4886 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-13 15:13:12.764  1016  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 15:13:12.774   279  1015 D CommandListener: Setting iface cfg,
09-13 15:13:12.784  1016  1128 E WifiStateMachine: Start Dhcp Watchdog 3
09-13 15:13:12.784  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-13 15:13:12.784  1016  1128 D SecContentProvider2: mCursor = null
09-13 15:13:12.784  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-13 15:13:12.784  1016  1128 D SecContentProvider2: mCursor = null
09-13 15:13:12.794  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-13 15:13:12.794  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 15:13:12.794  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 15:13:12.794  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:12.794  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:12.794  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:12.794  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:12.804  1016  1128 E WifiNative-wlan0: do suspend false
09-13 15:13:12.804  1016  1127 D WifiP2pService: InactiveState{ what=143375 }
09-13 15:13:12.804  1016  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
09-13 15:13:12.804  1016  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-13 15:13:12.804  1016  1128 D SecContentProvider2: mCursor = null
,09-13 15:13:13.014  7934  7934 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-13 15:13:13.024  7934  7934 I dhcpcd  : version 5.5.6 starting
,09-13 15:13:13.024  7934  7934 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-13 15:13:13.074  7934  7934 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-13 15:13:13.074  7934  7934 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-13 15:13:13.074  7934  7934 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-13 15:13:13.074  7934  7934 I dhcpcd  : bssid match
09-13 15:13:13.074  7934  7934 I dhcpcd  : wlan0: rebinding lease of 192.168.1.116
,09-13 15:13:13.164  7934  7934 I dhcpcd  : wlan0: acknowledged 192.168.1.116 from 192.168.1.1
,09-13 15:13:13.244  7106  7300 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1445)
,09-13 15:13:13.244  7106  7300 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1445)
,09-13 15:13:13.244  7106  7300 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1450)
,09-13 15:13:13.244  7106  7300 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-13 15:13:13.244  7106  7300 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1451)
,09-13 15:13:13.244  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 15:13:13.244  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aaf29c5 added. We now have 2 listener(s)
,09-13 15:13:13.244  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-13 15:13:13.244  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 15:13:13.244  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 15:13:13.244  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 15:13:13.244  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eacff1a added. We now have 9 listener(s)
,09-13 15:13:13.244  7106  7300 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 15:13:13.244  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 15:13:13.254  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 15:13:13.254  7106  7300 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:13:13.254  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:13.254  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:13.254  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:13:13.254  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:13.254  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:13:13.254  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:13:13.254  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:13:13.254  7106  7300 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:13:13.254  7106  7300 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 15:13:13.254  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:13.254  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:13:13.254  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cba5c28 added. We now have 3 listener(s)
,09-13 15:13:13.254  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:13.254  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-13 15:13:13.254  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:13:13.254  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:13:13.254  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:13:13.254  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@325d9d41 added. We now have 10 listener(s)
09-13 15:13:13.254  7106  7300 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:13:13.254  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:13:13.254  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:13:13.254  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:13:13.254  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:13:13.254  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:13.254  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:13:13.254  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:13:13.254  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2aaf29c5 removed from the list
09-13 15:13:13.254  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:13.254  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eacff1a removed from the list
09-13 15:13:13.254  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:13:13.264  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:13:13.264  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:13.264  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:13:13.264  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 15:13:13.264  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:13:13.264  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:13.264  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eacff1a not in the list,
09-13 15:13:13.264  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-13 15:13:13.264  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-13 15:13:13.264  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-13 15:13:13.264  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-13 15:13:13.264  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:13.264  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@325d9d41 removed from the list
09-13 15:13:13.264  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:13:13.264  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:13.264  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:13:13.264  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:13:13.264  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cba5c28 removed from the list
09-13 15:13:13.264  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:13:13.264  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@190bf2e6 added. We now have 2 listener(s)
09-13 15:13:13.264  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-13 15:13:13.264  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:13:13.264  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:13:13.264  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:13:13.264  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11fcb027 added. We now have 9 listener(s)
09-13 15:13:13.264  7106  7300 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:13:13.264  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 15:13:13.274  7934  7934 I dhcpcd  : wlan0: leased 192.168.1.116 for 172800 seconds
09-13 15:13:13.274  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 15:13:13.274  7106  7300 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:13:13.274  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:13.274  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:13.274  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:13:13.274  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:13.274  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:13:13.274  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:13:13.274  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:13:13.284  7106  7300 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
09-13 15:13:13.284  7106  7300 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 15:13:13.284  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:13:13.284  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d25cc7d added. We now have 3 listener(s)
,09-13 15:13:13.284  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:13.284  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:13.284  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-13 15:13:13.284  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:13:13.284  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:13:13.284  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:13:13.284  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33145772 added. We now have 10 listener(s)
09-13 15:13:13.284  7106  7300 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:13:13.284  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 15:13:13.284  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 15:13:13.284  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 15:13:13.284  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:13:13.284  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 15:13:13.294  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 15:13:13.294  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 15:13:13.304  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 15:13:13.304  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 15:13:13.304  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 15:13:13.304  7106  7300 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 15:13:13.314  3238  3254 D BtGatt.GattService: registerClient() - UUID=7b4af95f-6b61-4f81-99f0-605c41dc5860
,09-13 15:13:13.354  3238  3313 D BtGatt.GattService: onClientRegistered() - UUID=7b4af95f-6b61-4f81-99f0-605c41dc5860, clientIf=6
,09-13 15:13:13.354  7106  7117 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-13 15:13:13.354  3238  7844 D BtGatt.GattService: start scan with filters
09-13 15:13:13.354  3238  3370 D BtGatt.ScanManager: handling starting scan
09-13 15:13:13.354  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 15:13:13.354  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 15:13:13.354  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 15:13:13.354  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 15:13:13.364  3238  3313 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-13 15:13:13.364  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
09-13 15:13:13.364  3238  3370 D BtGatt.ScanManager: allow scan with filters
09-13 15:13:13.364  3238  3370 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-13 15:13:13.364  3238  3370 D BtGatt.ScanManager: set filter index= 6 for clientIf= 6
09-13 15:13:13.364  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
,09-13 15:13:13.364  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 15:13:13.364  7106  7106 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 15:13:13.364  3238  3313 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-13 15:13:13.364  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:13:13.364  3238  3370 D BtGatt.ScanManager: Starting BLE batch scan
09-13 15:13:13.364  3238  3370 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-13 15:13:13.364  3238  3313 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-13 15:13:13.364  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:13:13.364  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
09-13 15:13:13.374  3238  3313 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-13 15:13:13.374  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:13:13.384  7106  7300 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation,
09-13 15:13:13.384  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 15:13:13.384  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 15:13:13.384  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:13.384  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 15:13:13.384  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 15:13:13.384  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 15:13:13.384  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 15:13:13.384  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 15:13:13.384  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 15:13:13.384  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 15:13:13.384  3238  3262 D BtGatt.GattService: stopScan() - queue size =1
,09-13 15:13:13.384  3238  3370 D BtGatt.ScanManager: filter size is 1
,09-13 15:13:13.384  3238  3370 D BtGatt.ScanManager: delete FilterIndex - 6
,09-13 15:13:13.394  3238  3313 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-13 15:13:13.394  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 15:13:13.394  3238  3360 D BtGatt.GattService: unregisterClient() - clientIf=6
09-13 15:13:13.394  3238  3370 D BtGatt.ScanManager: stopping BLe Batch
,09-13 15:13:13.394  3238  3313 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-13 15:13:13.394  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:13:13.394  3238  3370 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 15:13:13.404  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 15:13:13.404  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 15:13:13.404  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 15:13:13.404  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 15:13:13.404  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 15:13:13.404  3238  3313 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-13 15:13:13.404  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:13:13.404  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
,09-13 15:13:13.404  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 15:13:13.404  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 15:13:13.404  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 15:13:13.404  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 15:13:13.414  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-13 15:13:13.414  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 15:13:13.414  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:13:13.414  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:13:13.414  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:13.414  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 15:13:13.414  7106  7106 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 15:13:13.414  7106  7106 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 15:13:13.414  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:13:13.414  7106  7106 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 15:13:13.414  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@190bf2e6 removed from the list
09-13 15:13:13.414  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:13.414  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11fcb027 removed from the list
09-13 15:13:13.414  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:13:13.414  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:13:13.414  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:13.414  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:13:13.414  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 15:13:13.414  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:13:13.414  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:13.414  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11fcb027 not in the list
09-13 15:13:13.414  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:13:13.414  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:13:13.424  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:13:13.424  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 15:13:13.424  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:13.424  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33145772 removed from the list
09-13 15:13:13.424  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:13:13.424  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:13:13.424  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:13:13.424  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:13:13.424  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d25cc7d removed from the list
,09-13 15:13:13.424  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:13:13.424  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1acc78be added. We now have 2 listener(s)
,09-13 15:13:13.424  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-13 15:13:13.424  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:13:13.424  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:13:13.424  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:13:13.424  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16cd7d1f added. We now have 9 listener(s)
09-13 15:13:13.424  7106  7300 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:13:13.424  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
,09-13 15:13:13.434  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-13 15:13:13.444  7106  7300 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:13:13.444  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
09-13 15:13:13.444  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:13.444  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:13:13.444  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:13.444  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:13:13.444  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:13:13.444  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:13:13.444  7106  7300 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 15:13:13.444  7106  7300 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 15:13:13.444  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:13:13.444  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37070e35 added. We now have 3 listener(s)
,09-13 15:13:13.454  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-13 15:13:13.454  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:13:13.454  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 15:13:13.454  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:13:13.454  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65362ca added. We now have 10 listener(s)
09-13 15:13:13.454  7106  7300 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:13:13.454  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
09-13 15:13:13.454  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 15:13:13.454  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 15:13:13.454  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-13 15:13:13.454  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:13:13.454  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 15:13:13.454  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:13.464  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:13.464  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 15:13:13.474  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 15:13:13.474  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 15:13:13.474  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 15:13:13.474  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 15:13:13.474  7106  7300 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
,09-13 15:13:13.484  3238  7844 D BtGatt.GattService: registerClient() - UUID=8052ed52-0c99-45f2-83b7-e93fd271bc38
,09-13 15:13:13.524  3238  3313 D BtGatt.GattService: onClientRegistered() - UUID=8052ed52-0c99-45f2-83b7-e93fd271bc38, clientIf=6,
09-13 15:13:13.524  7106  7117 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-13 15:13:13.524  3238  3395 D BtGatt.GattService: start scan with filters
09-13 15:13:13.524  3238  3370 D BtGatt.ScanManager: handling starting scan,
09-13 15:13:13.524  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 15:13:13.524  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 15:13:13.524  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
09-13 15:13:13.524  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 15:13:13.524  3238  3313 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-13 15:13:13.524  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:13:13.524  3238  3370 D BtGatt.ScanManager: allow scan with filters
09-13 15:13:13.524  3238  3370 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-13 15:13:13.524  3238  3370 D BtGatt.ScanManager: set filter index= 7 for clientIf= 6
,09-13 15:13:13.534  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 15:13:13.534  7106  7106 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 15:13:13.534  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 15:13:13.534  3238  3313 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-13 15:13:13.534  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 15:13:13.534  3238  3370 D BtGatt.ScanManager: Starting BLE batch scan
09-13 15:13:13.534  3238  3370 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-13 15:13:13.534  3238  3313 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
09-13 15:13:13.534  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:13:13.534  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 15:13:13.534  3238  3313 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-13 15:13:13.544  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:13:13.544  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 15:13:13.544  7106  7300 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 15:13:13.544  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 15:13:13.544  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:13:13.544  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 15:13:13.544  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 15:13:13.544  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:13.544  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 15:13:13.544  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:13:13.544  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1acc78be removed from the list
,09-13 15:13:13.544  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:13.544  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16cd7d1f removed from the list
09-13 15:13:13.544  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 15:13:13.544  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 15:13:13.544  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-13 15:13:13.544  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-13 15:13:13.554  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:13.554  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 15:13:13.554  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 15:13:13.554  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:13:13.554  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 15:13:13.554  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16cd7d1f not in the list
09-13 15:13:13.554  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 15:13:13.554  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 15:13:13.554  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 15:13:13.554  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 15:13:13.554  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 15:13:13.554  3238  3262 D BtGatt.GattService: stopScan() - queue size =1
,09-13 15:13:13.554  3238  3370 D BtGatt.ScanManager: filter size is 1
,09-13 15:13:13.554  3238  3370 D BtGatt.ScanManager: delete FilterIndex - 7
09-13 15:13:13.554  3238  3360 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 15:13:13.554  3238  3313 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-13 15:13:13.554  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 15:13:13.554  3238  3370 D BtGatt.ScanManager: stopping BLe Batch
,09-13 15:13:13.554  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
09-13 15:13:13.554  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 15:13:13.554  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 15:13:13.554  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 15:13:13.554  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 15:13:13.564  3238  3313 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-13 15:13:13.564  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 15:13:13.564  3238  3370 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-13 15:13:13.564  3238  3313 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-13 15:13:13.564  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 15:13:13.564  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 15:13:13.564  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 15:13:13.564  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 15:13:13.564  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 15:13:13.564  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:13:13.564  7106  7106 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 15:13:13.564  7106  7106 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 15:13:13.564  7106  7106 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 15:13:13.564  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:13:13.564  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:13:13.564  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:13.564  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65362ca removed from the list
09-13 15:13:13.564  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:13:13.564  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:13.564  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:13:13.564  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:13:13.564  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37070e35 removed from the list
,09-13 15:13:13.564  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 15:13:13.564  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cace196 added. We now have 2 listener(s)
,09-13 15:13:13.564  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
,09-13 15:13:13.574  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:13:13.574  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:13:13.574  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 15:13:13.574  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@125bf117 added. We now have 9 listener(s)
09-13 15:13:13.574  7106  7300 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:13:13.574  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 15:13:13.574  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 15:13:13.574  7106  7300 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:13:13.574  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:13.574  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:13.574  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:13:13.574  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:13.574  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 15:13:13.574  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 15:13:13.574  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 15:13:13.574  7106  7300 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 15:13:13.574  7106  7300 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 15:13:13.574  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:13:13.574  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2927ceed added. We now have 3 listener(s)
,09-13 15:13:13.574  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:13.584  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:13.584  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-13 15:13:13.584  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:13:13.584  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:13:13.584  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:13:13.584  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f4d8122 added. We now have 10 listener(s)
09-13 15:13:13.584  7106  7300 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:13:13.584  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 15:13:13.584  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 15:13:13.584  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 15:13:13.584  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 15:13:13.584  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 15:13:13.584  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 15:13:13.584  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 15:13:13.584  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 15:13:13.594  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 15:13:13.594  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 15:13:13.594  7106  7300 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 15:13:13.594  3238  7844 D BtGatt.GattService: registerClient() - UUID=a5490eae-6776-4770-a093-4b6c9ab219a1
,09-13 15:13:13.624  1016  1128 E WifiNative-wlan0: do suspend true
,09-13 15:13:13.634  3238  3313 D BtGatt.GattService: onClientRegistered() - UUID=a5490eae-6776-4770-a093-4b6c9ab219a1, clientIf=6
09-13 15:13:13.634  1016  1127 D WifiP2pService: InactiveState{ what=143375 }
,09-13 15:13:13.634  1016  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-13 15:13:13.644  7106  7114 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
09-13 15:13:13.644  1016  1128 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-13 15:13:13.644  1016  1128 E WifiStateMachine: VerifyingLinkState enter
09-13 15:13:13.644  3238  3358 D BtGatt.GattService: start scan with filters
09-13 15:13:13.644  3238  3370 D BtGatt.ScanManager: handling starting scan
09-13 15:13:13.644  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 15:13:13.644  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 15:13:13.644  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
09-13 15:13:13.644  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-13 15:13:13.644  1016  1130 E ConnectivityService: updateNetworkInfo()
,09-13 15:13:13.654  1016  1130 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
09-13 15:13:13.654  1016  1130 D ConnectivityService: Adding iface wlan0 to network 504
,09-13 15:13:13.654  3238  3313 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-13 15:13:13.654  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 15:13:13.654  3238  3370 D BtGatt.ScanManager: allow scan with filters
,09-13 15:13:13.654  3238  3370 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-13 15:13:13.654  3238  3370 D BtGatt.ScanManager: set filter index= 8 for clientIf= 6
09-13 15:13:13.654  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 15:13:13.654  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 15:13:13.654  7106  7106 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 15:13:13.664  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0,
09-13 15:13:13.664  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 15:13:13.664  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 15:13:13.664  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:13.664  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:13.664  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:13.664  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:13:13.664  3238  3313 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-13 15:13:13.664  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 15:13:13.664  3238  3370 D BtGatt.ScanManager: Starting BLE batch scan
09-13 15:13:13.664  3238  3370 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-13 15:13:13.674  1016  1145 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-13 15:13:13.674  1016  1145 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-13 15:13:13.674  1016  1145 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-13 15:13:13.674  1016  1145 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-13 15:13:13.674  3238  3313 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-13 15:13:13.674  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:13:13.674  1016  1145 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-13 15:13:13.684  3238  3313 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
09-13 15:13:13.684  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-13 15:13:13.694  1016  1130 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,09-13 15:13:13.694  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 15:13:13.694  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-13 15:13:13.694  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-13 15:13:13.694  1016  1128 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
09-13 15:13:13.694  1016  1130 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
09-13 15:13:13.694  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 15:13:13.694  1016  1130 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
09-13 15:13:13.694  1016  1474 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-13 15:13:13.694  1016  1474 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-13 15:13:13.694  1016  1130 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-13 15:13:13.694  1016  1130 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
,09-13 15:13:13.694  1016  1130 D ConnectivityService: LTETest block dns file not exists
,09-13 15:13:13.704  1016  1474 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:13.704  1016  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:13.704  1016  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-13 15:13:13.704  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:13.704  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:13.704  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:13.704  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:13:13.704  1623  1623 I Hs20UtilService: Starting #22
09-13 15:13:13.704  1623  1650 I Hs20UtilService: Message received 5007
,09-13 15:13:13.714  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:13:13.714  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:13:13.714  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:13:13.714  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:13:13.714  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:13.714  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 15:13:13.714  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:13:13.714  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cace196 removed from the list
09-13 15:13:13.714  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:13.714  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@125bf117 removed from the list
09-13 15:13:13.714  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:13:13.714  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 15:13:13.714  1016  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:13:13.714  1016  1130 V NetworkStats: updateIfacesLocked()
09-13 15:13:13.714  4811  4811 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-13 15:13:13.714  1016  1130 V NetworkStats: performPollLocked(flags=0x1)
09-13 15:13:13.714  1016  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 15:13:13.714  1016  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-13 15:13:13.714  4811  4811 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-13 15:13:13.714  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:13.714  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-13 15:13:13.714  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:13.714  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 15:13:13.724  1016  1130 V NetworkStats: performPollLocked() took 6ms
,09-13 15:13:13.724  1016  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:13:13.734  1016  1130 E ConnectivityService: updateNetworkInfo()
,09-13 15:13:13.734  1016  1130 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,09-13 15:13:13.734  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:13:13.734  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:13:13.734  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:13.734  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@125bf117 not in the list
09-13 15:13:13.734  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 15:13:13.734  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 15:13:13.734  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 15:13:13.734  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 15:13:13.734  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 15:13:13.734  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:13:13.734  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:13:13.734  3238  3395 D BtGatt.GattService: stopScan() - queue size =1
,09-13 15:13:13.734  3238  3254 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-13 15:13:13.734  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 15:13:13.734  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 15:13:13.734  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 15:13:13.734  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 15:13:13.734  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 15:13:13.744  3238  3370 D BtGatt.ScanManager: filter size is 1
09-13 15:13:13.744  3238  3370 D BtGatt.ScanManager: delete FilterIndex - 8
09-13 15:13:13.744  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 15:13:13.744  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 15:13:13.744  7106  7300 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 15:13:13.744  3238  3313 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-13 15:13:13.744  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
09-13 15:13:13.744  1016  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-13 15:13:13.744  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 15:13:13.744  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:13:13.744  3238  3370 D BtGatt.ScanManager: stopping BLe Batch
09-13 15:13:13.744  1016  1128 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-13 15:13:13.744  1016  1128 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-13 15:13:13.744  1016  1130 E ConnectivityService: updateNetworkInfo()
09-13 15:13:13.744  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-13 15:13:13.744  7106  7106 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 15:13:13.744  7106  7106 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 15:13:13.744  1016  1130 V NetworkStats: updateIfacesLocked()
09-13 15:13:13.744  7106  7106 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 15:13:13.744  1016  1130 V NetworkStats: performPollLocked(flags=0x1)
09-13 15:13:13.744  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:13:13.744  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:13:13.744  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:13.744  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f4d8122 removed from the list
09-13 15:13:13.744  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:13:13.744  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:13.744  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:13:13.744  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:13:13.744  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2927ceed removed from the list
,09-13 15:13:13.744  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:13:13.744  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@668d6e added. We now have 2 listener(s)
09-13 15:13:13.744  3238  3313 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-13 15:13:13.744  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 15:13:13.744  3238  3370 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
09-13 15:13:13.744  1016  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:13:13.744  1016  1130 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 15:13:13.744  1016  1130 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-13 15:13:13.744  1016  1130 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:13:13.744  1016  1130 V NetworkStats: performPollLocked() took 3ms
,09-13 15:13:13.754  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 15:13:13.754  1016  1016 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-13 15:13:13.754  1016  1016 I WifiTrafficPoller: mBoosterFLAG : 0
09-13 15:13:13.754  1016  1016 I WifiTrafficPoller: current booster mode : FullMode
,09-13 15:13:13.754  3238  3313 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=1
09-13 15:13:13.754  3238  3313 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-13 15:13:13.754  3238  3313 D BtGatt.GattService: current time is 135706527551
,09-13 15:13:13.754  3238  3313 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -79, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-13 15:13:13.754  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=4 combinedSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true combinedLabel=No Internet connection mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 15:13:13.754  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-13 15:13:13.754  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:13.754  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:13.754  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:13.754  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:13:13.764  3238  3313 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-13 15:13:13.764  3238  3313 D ScanRecord: parseFromBytes
09-13 15:13:13.764  3238  3313 D ScanRecord: first manudata for manu ID
09-13 15:13:13.764  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 15:13:13.764  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-13 15:13:13.764  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:13.764  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:13.764  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:13:13.764  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:13:13.764  1016  1130 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-13 15:13:13.764  1016  1130 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,09-13 15:13:13.764  1016  7932 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:13:13.764  1016  7932 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
,09-13 15:13:13.764  1016  7932 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-13 15:13:13.764  1016  7932 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
09-13 15:13:13.774  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:13:13.774  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:13:13.774  1016  1130 D ConnectivityService:    accepting network in place of null
09-13 15:13:13.774  1016  1127 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-13 15:13:13.774  1016  1128 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-13 15:13:13.774  1016  1029 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-13 15:13:13.774  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-13 15:13:13.774  1447  1447 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-13 15:13:13.774  1447  1447 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 15:13:13.774  1016  7932 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-13 15:13:13.774  1016  1130 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-13 15:13:13.774  1016  1130 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-13 15:13:13.774  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:13.774  1016  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 15:13:13.774  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:13.774  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-13 15:13:13.774  1623  1623 I Hs20UtilService: Starting #23
09-13 15:13:13.774  1623  1650 I Hs20UtilService: Message received 5007
09-13 15:13:13.774  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-13 15:13:13.774  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:13:13.774  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:13:13.774  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:13:13.774  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bd5ec0f added. We now have 9 listener(s)
09-13 15:13:13.774  7106  7300 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 15:13:13.774  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 15:13:13.774  4811  4811 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-13 15:13:13.774  4811  4811 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-13 15:13:13.774  1016  1016 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-13 15:13:13.774  1016  1130 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.116/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
09-13 15:13:13.774  1016  1132 D Tethering: MasterInitialState.processMessage what=3
,09-13 15:13:13.774  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
09-13 15:13:13.774  1016  1125 V NetworkStats: updateIfacesLocked()
09-13 15:13:13.774  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:13:13.774  1016  1130 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-13 15:13:13.774  1016  1125 V NetworkStats: performPollLocked(flags=0x1)
,09-13 15:13:13.774  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 15:13:13.784  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-13 15:13:13.784  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-13 15:13:13.784  4811  4811 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-13 15:13:13.784  4811  4811 I NearbySettings: MountReceiver.onReceive - Keep current state
09-13 15:13:13.784  1016  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-13 15:13:13.784  1173  1745 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-13 15:13:13.784  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 15:13:13.784   279  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-13 15:13:13.784  1016  1125 V NetworkStats: performPollLocked() took 5ms
09-13 15:13:13.784   279  1011 D Netd    : getNetworkForDns: using netid 504 for uid 1000
09-13 15:13:13.784  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
09-13 15:13:13.784  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-13 15:13:13.784  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-13 15:13:13.784  1173  1173 D StatusBar.NetworkController: updateDataNetType()
09-13 15:13:13.784  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:13:13.784  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:13:13.784  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
09-13 15:13:13.784  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-13 15:13:13.784  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:13:13.784  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:13:13.784  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:13:13.784  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:13:13.784  1016  1126 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-13 15:13:13.784  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:13:13.794  7106  7300 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 15:13:13.794  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 15:13:13.794  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 15:13:13.794  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 15:13:13.794  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 15:13:13.794  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 15:13:13.794  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 15:13:13.794  7106  7300 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 15:13:13.794  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-13 15:13:13.794  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 22 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
09-13 15:13:13.794  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-13 15:13:13.794  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
09-13 15:13:13.794  7106  7300 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 15:13:13.794  7106  7300 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 15:13:13.794  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 15:13:13.794  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e18eea5 added. We now have 3 listener(s)
,09-13 15:13:13.794  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 15:13:13.794  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-13 15:13:13.794  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:13.794  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:13.794  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:13.794  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:13.794  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 15:13:13.794  7106  7106 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 15:13:13.794  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
09-13 15:13:13.794  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 15:13:13.794  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 15:13:13.794  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 15:13:13.794  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f2127a added. We now have 10 listener(s)
09-13 15:13:13.794  7106  7300 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 15:13:13.794  7106  7300 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 15:13:13.804  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 15:13:13.804  7106  7300 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 15:13:13.804  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:13:13.804  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:13.804  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 15:13:13.804  1016  1463 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-13 15:13:13.804  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:13:13.804  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@668d6e removed from the list
09-13 15:13:13.804  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:13.804  1016  1463 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-13 15:13:13.804  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bd5ec0f removed from the list
09-13 15:13:13.804  7106  7300 D io.jxcore.node.ConnectivityMonitor: stop
09-13 15:13:13.804  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:13:13.804  1016  1463 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:13.804  1016  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:13.804  1016  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-13 15:13:13.804  1623  1623 I Hs20UtilService: Starting #24
,09-13 15:13:13.804  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:13.804  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:13:13.804  1623  1650 I Hs20UtilService: Message received 5007
,09-13 15:13:13.804  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:13:13.804  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:13:13.804  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:13.804  7106  7300 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bd5ec0f not in the list
09-13 15:13:13.804  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:13.804  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-13 15:13:13.804  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 15:13:13.804  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 15:13:13.804  7106  7300 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 15:13:13.804  7106  7300 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11f2127a removed from the list
09-13 15:13:13.804  7106  7300 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 15:13:13.804  7106  7300 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 15:13:13.804  7106  7300 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-13 15:13:13.804  7106  7300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 15:13:13.804  7106  7300 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e18eea5 removed from the list
,09-13 15:13:13.804  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 15:13:13.804  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 15:13:13.804  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 15:13:13.804  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 15:13:13.804  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 15:13:13.804  7106  7300 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 15:13:13.804  4811  4811 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-13 15:13:13.804  4811  4811 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-13 15:13:13.814  1016  1473 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-13 15:13:13.814  7106  7970 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1458, name: My test thread name)
09-13 15:13:13.814  7106  7970 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1458, thread name: My test thread name)
09-13 15:13:13.814  7106  7970 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1458, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-13 15:13:13.814  1016  1487 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-13 15:13:13.814  1016  1487 D SecContentProvider2: mCursor = null
,09-13 15:13:13.814  1016  1029 D SecContentProvider2: uri = 15 selection = getToastGravity
,09-13 15:13:13.814  1016  1029 D SecContentProvider2: mCursor = null
09-13 15:13:13.814  7106  7971 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1460, name: My test thread name)
09-13 15:13:13.824  7106  7971 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1460, thread name: My test thread name)
09-13 15:13:13.824  7106  7971 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1460, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-13 15:13:13.824  1016  1028 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
09-13 15:13:13.824  1016  1028 D SecContentProvider2: mCursor = null
,09-13 15:13:13.824  1016  1489 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-13 15:13:13.824  1016  1489 D SecContentProvider2: mCursor = null
,09-13 15:13:13.824  7106  7300 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-13 15:13:13.824  7106  7300 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-13 15:13:13.824  7106  7300 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-13 15:13:13.824  7106  7300 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-13 15:13:13.824  7106  7300 D com.test.thalitest.ThaliTestRunner: Total duration: 23383 ms
,09-13 15:13:13.824  7106  7300 I jxcore-log: *Native tests were executed*
09-13 15:13:13.824  7106  7300 I jxcore-log: 
09-13 15:13:13.824  7106  7300 I jxcore-log: Total number of executed tests:  80
09-13 15:13:13.824  7106  7300 I jxcore-log: 
09-13 15:13:13.824  7106  7300 I jxcore-log: Number of passed tests:  80
09-13 15:13:13.824  7106  7300 I jxcore-log: 
09-13 15:13:13.824  7106  7300 I jxcore-log: Number of failed tests:  0
09-13 15:13:13.824  7106  7300 I jxcore-log: 
09-13 15:13:13.824  7106  7300 I jxcore-log: Number of ignored tests:  0
09-13 15:13:13.824  7106  7300 I jxcore-log: 
09-13 15:13:13.824  7106  7300 I jxcore-log: Total duration:  23383
09-13 15:13:13.824  7106  7300 I jxcore-log: 
09-13 15:13:13.824  7106  7300 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 15:13:13.824  7106  7300 I jxcore-log: 
09-13 15:13:13.824  1016  1479 D SecContentProvider2: uri = 15 selection = getToastEnabledState
09-13 15:13:13.824  1016  1479 D SecContentProvider2: mCursor = null
09-13 15:13:13.824  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:13:13.824  7106  7300 I jxcore-log: 
,09-13 15:13:13.834  1016  1079 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-13 15:13:13.834  1016  1079 D SecContentProvider2: mCursor = null
09-13 15:13:13.834  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:13:13.834  7106  7300 I jxcore-log: 
09-13 15:13:13.834  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:13:13.834  7106  7300 I jxcore-log: 
09-13 15:13:13.834  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:13:13.834  7106  7300 I jxcore-log: 
09-13 15:13:13.834  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:13:13.834  7106  7300 I jxcore-log: 
09-13 15:13:13.834  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:13:13.834  7106  7300 I jxcore-log: 
09-13 15:13:13.834  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:13:13.834  7106  7300 I jxcore-log: 
09-13 15:13:13.834  7106  7106 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-13 15:13:13.844  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 15:13:13.844  7106  7300 I jxcore-log: 
09-13 15:13:13.844  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 15:13:13.844  7106  7300 I jxcore-log: 
09-13 15:13:13.844  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 15:13:13.844  7106  7300 I jxcore-log: 
09-13 15:13:13.844  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 15:13:13.844  7106  7300 I jxcore-log: 
09-13 15:13:13.844  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 15:13:13.844  7106  7300 I jxcore-log: 
09-13 15:13:13.844  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 15:13:13.844  7106  7300 I jxcore-log: 
09-13 15:13:13.844  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 15:13:13.844  7106  7300 I jxcore-log: 
09-13 15:13:13.844  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 15:13:13.844  7106  7300 I jxcore-log: 
09-13 15:13:13.844  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 15:13:13.844  7106  7300 I jxcore-log: 
09-13 15:13:13.844  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 15:13:13.844  7106  7300 I jxcore-log: 
09-13 15:13:13.844  1016  7932 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-13 15:13:13.844  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 15:13:13.844  7106  7300 I jxcore-log: 
09-13 15:13:13.844  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 15:13:13.844  7106  7300 I jxcore-log: 
09-13 15:13:13.854  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 15:13:13.854  7106  7300 I jxcore-log: 
09-13 15:13:13.854  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 15:13:13.854  7106  7300 I jxcore-log: 
09-13 15:13:13.854  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 15:13:13.854  7106  7300 I jxcore-log: 
09-13 15:13:13.854  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 15:13:13.854  7106  7300 I jxcore-log: 
09-13 15:13:13.854  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 15:13:13.854  7106  7300 I jxcore-log: 
09-13 15:13:13.854  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 15:13:13.854  7106  7300 I jxcore-log: 
09-13 15:13:13.854  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 15:13:13.854  7106  7300 I jxcore-log: 
09-13 15:13:13.854  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 15:13:13.854  7106  7300 I jxcore-log: 
09-13 15:13:13.854   259   259 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,09-13 15:13:13.864  1016  1487 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016,
,09-13 15:13:13.864  1173  1173 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-13 15:13:13.894  1016  7932 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 13:13:13 GMT], X-Android-Received-Millis=[1473772393911], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473772393886]}
,09-13 15:13:13.894  1016  7932 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-13 15:13:13.894  1016  7932 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-13 15:13:13.894  1016  1130 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
09-13 15:13:13.894  1016  1130 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-13 15:13:13.894  1016  1130 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-13 15:13:13.894  1016  1130 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,09-13 15:13:13.894  1016  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-13 15:13:13.904  1173  1745 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-13 15:13:13.904  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
,09-13 15:13:13.904  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-13 15:13:13.904  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-13 15:13:13.904  1173  1173 D StatusBar.NetworkController: updateDataNetType()
,09-13 15:13:13.904  1173  1173 D StatusBar.NetworkController: Nothing, mRoamingIconId = 0
,09-13 15:13:13.904  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-13 15:13:13.904  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-13 15:13:13.904  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 22 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
,09-13 15:13:13.904  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
09-13 15:13:13.904  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,09-13 15:13:13.914  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true combinedLabel="NG700" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-13 15:13:13.914  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,09-13 15:13:13.914  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:13.914  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:13.914  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-13 15:13:13.914  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-13 15:13:13.914  7106  7106 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 15:13:13.914  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 15:13:13.914  7106  7300 I jxcore-log: 
,09-13 15:13:14.064  7106  7106 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 15:13:14.064  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false},
09-13 15:13:14.064  7106  7300 I jxcore-log: 
,09-13 15:13:14.104  7973  7973 D AndroidRuntime: ,
09-13 15:13:14.104  7973  7973 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-13 15:13:14.104  7973  7973 D AndroidRuntime: CheckJNI is OFF,
09-13 15:13:14.104  7973  7973 D AndroidRuntime: readGMSProperty: start
,09-13 15:13:14.104  7973  7973 D AndroidRuntime: readGMSProperty: already setted!!
09-13 15:13:14.104  7973  7973 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-13 15:13:14.104  7973  7973 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-13 15:13:14.104  7973  7973 D AndroidRuntime: readGMSProperty: end
09-13 15:13:14.104  7973  7973 D AndroidRuntime: addProductProperty: start
,09-13 15:13:14.164  1016  1847 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-13 15:13:14.164  1016  1847 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4277, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-13 15:13:14.164  1016  1847 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-13 15:13:14.164  1016  1847 D BatteryService: stay LED for charging
09-13 15:13:14.164  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-13 15:13:14.174  1016  1016 I MotionRecognitionService: Plugged
09-13 15:13:14.174  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,09-13 15:13:14.174  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-13 15:13:14.174  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-13 15:13:14.184  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-13 15:13:14.184  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
09-13 15:13:14.184  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 15:13:14.184  3238  3238 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-13 15:13:14.184  3238  7896 D HeadsetStateMachine: Disconnected process message: 10
,09-13 15:13:14.194  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
09-13 15:13:14.194  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-13 15:13:14.224  7973  7973 E AffinityControl: AffinityControl: registerfunction enter
,09-13 15:13:14.244  7106  7106 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-13 15:13:14.244  7106  7300 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 15:13:14.244  7106  7300 I jxcore-log: 
,09-13 15:13:14.254  7973  7973 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 15:13:14.264  1016  1029 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
09-13 15:13:14.264  1016  1029 D PackageManager: START PACKAGE DELETE: observer{1039899029}
09-13 15:13:14.264  1016  1029 D PackageManager: pkg{<packageName>}
09-13 15:13:14.264  1016  1029 D PackageManager: user{0}
09-13 15:13:14.264  1016  1029 D PackageManager: caller{2000}
09-13 15:13:14.264  1016  1029 D PackageManager: flags{2}
09-13 15:13:14.264  1016  1029 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-13 15:13:14.264  1016  1029 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true,
09-13 15:13:14.264  1016  1029 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-13 15:13:14.264  1016  1029 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-13 15:13:14.274  1016  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
09-13 15:13:14.274  1016  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-13 15:13:14.274  1016  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-13 15:13:14.274  1016  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
09-13 15:13:14.274  1016  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-13 15:13:14.274  1016  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 15:13:14.274  1016  1057 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,09-13 15:13:14.284  1016  1043 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
09-13 15:13:14.284  1016  1043 I ActivityManager: Killing 7106:com.test.thalitest/u0a170 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-13 15:13:14.284  1016  1043 I ActivityManager:   Force finishing activity ActivityRecord{37e09a0d u0 com.test.thalitest/.MainActivity t163}
,09-13 15:13:14.284  1016  1050 I PowerManagerService: [PWL] Off : 75s ago
09-13 15:13:14.284  1016  1050 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-13 15:13:14.284  1016  1050 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-13 15:13:14.284  1016  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1016, ws=null) (elapsedTime=23054)
09-13 15:13:14.284  1016  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=3238, ws=null) (elapsedTime=927)
,09-13 15:13:14.294  1016  1043 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{2b29faaa u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{6f251ef 7106 com.test.thalitest/10170/u0 remote:12ff5ece}: filter unregistered
,09-13 15:13:14.414  1016  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-13 15:13:14.414  1016  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:13:14.414  1016  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:13:14.414  1016  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:13:14.414  1016  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:13:14.424  7983  7983 E Zygote  : MountEmulatedStorage()
09-13 15:13:14.424  7983  7983 I libpersona: KNOX_SDCARD checking this for 1000
09-13 15:13:14.424  7983  7983 E Zygote  : v2
09-13 15:13:14.424  7983  7983 I libpersona: KNOX_SDCARD not a persona
,09-13 15:13:14.434  7983  7983 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 15:13:14.434  7983  7983 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-13 15:13:14.434  7983  7983 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-13 15:13:14.434  1016  1043 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7983 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-13 15:13:14.434  1016  1043 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-13 15:13:14.444  1016  1100 W InputDispatcher: channel ~ Consumer closed input channel or an error occurred.  events=0x9
09-13 15:13:14.444  1016  1100 E InputDispatcher: channel ~ Channel is unrecoverably broken and will be disposed!
09-13 15:13:14.444  1016  1043 D InputDispatcher: Focus left window: 7106
09-13 15:13:14.444  1016  1043 W InputDispatcher: Attempted to unregister already unregistered input channel
09-13 15:13:14.444   259  6265 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
09-13 15:13:14.454   259  1099 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,09-13 15:13:14.464  7983  7983 D TimaKeyStoreProvider: TimaSignature is unavailable
09-13 15:13:14.464  7983  7983 D ActivityThread: Added TimaKeyStore provider,
,09-13 15:13:14.474  1016  1043 D InputDispatcher: Focused application released,
,09-13 15:13:14.484  1016  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-13 15:13:14.484  1016  1221 W WindowManager: Failed looking up window,
09-13 15:13:14.484  1016  1221 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@34481791 does not exist
09-13 15:13:14.484  1016  1221 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:11074)
09-13 15:13:14.484  1016  1221 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:11065)
09-13 15:13:14.484  1016  1221 W WindowManager: 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1644)
09-13 15:13:14.484  1016  1221 W WindowManager: 	at android.os.BinderProxy.sendDeathNotice(Binder.java:551)
09-13 15:13:14.484  1016  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
09-13 15:13:14.484  1016  1221 I WindowState: WIN DEATH: null,
09-13 15:13:14.484  1016  1057 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,09-13 15:13:14.504  1016  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also,
,09-13 15:13:14.514  1016  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-13 15:13:14.534  2844  2844 I art     : Explicit concurrent mark sweep GC freed 17329(1021KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 793us total 30.848ms
,09-13 15:13:14.534  1016  1101 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-13 15:13:14.544  1892  1892 E SamsungIME: mOCRHelper is null
,09-13 15:13:14.554  1757  2022 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-13 15:13:14.564  1016  1016 D RCPManagerService: PackageReceiver onReceive()
,09-13 15:13:14.564  1016  1016 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-13 15:13:14.564  1016  1016 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-13 15:13:14.564  1016  1016 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-13 15:13:14.564  1016  1016 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,09-13 15:13:14.584  1016  1016 I OTPFW   : ProvisionData::getAllEntries Enter
,09-13 15:13:14.584  1016  1016 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-13 15:13:14.624  1436  1436 D PersonaManager: isKioskContainerExistOnDevice
,09-13 15:13:14.634  1016  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
,09-13 15:13:14.634  7983  7983 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-13 15:13:14.634  7983  7983 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-13 15:13:14.634  7983  7983 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-13 15:13:14.634  1016  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,09-13 15:13:14.634  1436  1436 D RegisteredServicesCache: empty dynamic service
,09-13 15:13:14.634  1016  1125 V NetworkStats: removeUidsLocked() for UIDs [10170]
09-13 15:13:14.634  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
09-13 15:13:14.634  1016  1125 V NetworkStats: performPollLocked(flags=0x3)
09-13 15:13:14.634  1016  1042 W TextServicesManagerService: no available spell checker services found
,09-13 15:13:14.644  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
09-13 15:13:14.644  1016  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-13 15:13:14.644  1016  1125 V NetworkStats: performPollLocked() took 6ms
,09-13 15:13:14.644  1016  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:13:14.654  1016  1016 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-13 15:13:14.654  1016  1016 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-13 15:13:14.654  7983  7983 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-13 15:13:14.654  7983  7983 I PCWCLIENTTRACE_PushUtil: sales region : global
09-13 15:13:14.654  7983  7983 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-13 15:13:14.654  7983  7983 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-13 15:13:14.664  1016  1221 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=7
09-13 15:13:14.664  1016  1221 I splitIntent: base  index=7, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
09-13 15:13:14.664  1016  1221 I splitIntent: other index=9, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
09-13 15:13:14.664  1016  1221 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,09-13 15:13:14.664  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 15:13:14.664  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-13 15:13:14.664  1016  1016 V EnterpriseBillingPolicy: uID is 10170
09-13 15:13:14.664  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
09-13 15:13:14.664  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-13 15:13:14.664  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-13 15:13:14.664  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-13 15:13:14.664  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-13 15:13:14.664  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-13 15:13:14.664  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-13 15:13:14.674  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 15:13:14.674  1016  1221 I ActivityManager: Killing 7474:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,09-13 15:13:14.674  1016  1016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-13 15:13:14.674  1016  1163 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,09-13 15:13:14.674  1016  1479 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-13 15:13:14.684  1016  1479 D SecContentProvider2: mCursor = null
,09-13 15:13:14.684  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-13 15:13:14.684  1016  1016 V EnterpriseBillingPolicy: uID is 10170
09-13 15:13:14.684  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
09-13 15:13:14.684  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-13 15:13:14.684  1016  3387 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-13 15:13:14.684  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-13 15:13:14.684  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-13 15:13:14.684  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-13 15:13:14.684  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-13 15:13:14.684  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-13 15:13:14.684  1016  1016 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,09-13 15:13:14.684  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 15:13:14.684  1436  1436 D RegisteredComponentCache: Collect Tech packages for Knox
,09-13 15:13:14.694  1436  1436 D PersonaManager: isKioskContainerExistOnDevice
,09-13 15:13:14.694  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 15:13:14.704  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:13:14.704  1016  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,09-13 15:13:14.734  1016  1016 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-13 15:13:14.734  1016  1016 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.sec.android.cloudagent/com.sec.android.cloudagent.detector.DetectorReceiver}
09-13 15:13:14.734  1016  1016 W BroadcastQueue: android.os.TransactionTooLargeException
09-13 15:13:14.734  1016  1016 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 15:13:14.734  1016  1016 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-13 15:13:14.734  1016  1016 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-13 15:13:14.734  1016  1016 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-13 15:13:14.734  1016  1016 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-13 15:13:14.734  1016  1016 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
09-13 15:13:14.734  1016  1016 W BroadcastQueue: 	at android.content.BroadcastReceiver$PendingResult.sendFinished(BroadcastReceiver.java:424)
09-13 15:13:14.734  1016  1016 W BroadcastQueue: 	at android.content.BroadcastReceiver$PendingResult.finish(BroadcastReceiver.java:389)
09-13 15:13:14.734  1016  1016 W BroadcastQueue: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3141)
09-13 15:13:14.734  1016  1016 W BroadcastQueue: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-13 15:13:14.734  1016  1016 W BroadcastQueue: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-13 15:13:14.734  1016  1016 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:13:14.734  1016  1016 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:145)
09-13 15:13:14.734  1016  1016 W BroadcastQueue: 	at com.android.server.SystemServer.run(SystemServer.java:445)
09-13 15:13:14.734  1016  1016 W BroadcastQueue: 	at com.android.server.SystemServer.main(SystemServer.java:329)
09-13 15:13:14.734  1016  1016 W BroadcastQueue: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 15:13:14.734  1016  1016 W BroadcastQueue: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 15:13:14.734  1016  1016 W BroadcastQueue: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-13 15:13:14.734  1016  1016 W BroadcastQueue: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-13 15:13:14.734  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-13 15:13:14.734  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:13:14.734  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:13:14.734  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:13:14.734  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:13:14.744  8000  8000 E Zygote  : MountEmulatedStorage()
09-13 15:13:14.754  8000  8000 E Zygote  : v2
09-13 15:13:14.754  8000  8000 I libpersona: KNOX_SDCARD checking this for 10001
09-13 15:13:14.754  8000  8000 I libpersona: KNOX_SDCARD not a persona
09-13 15:13:14.754  8000  8000 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-13 15:13:14.754  1016  1016 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=8000 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-13 15:13:14.754  8000  8000 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-13 15:13:14.754  8000  8000 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 15:13:14.754  1016  1479 W ActivityManager: Spurious death for ProcessRecord{3879172 8000:com.sec.android.cloudagent/u0a1}, curProc for 7474: null
,09-13 15:13:14.784  1016  1130 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-13 15:13:14.794  1016  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-13 15:13:14.794  8000  8000 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:13:14.794  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 15:13:14.794  8000  8000 D ActivityThread: Added TimaKeyStore provider
,09-13 15:13:14.794  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 15:13:14.804  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 15:13:14.814  1016  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-13 15:13:14.814  1016  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 15:13:14.814  1016  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-13 15:13:14.814  1016  1057 I art     : Explicit concurrent mark sweep GC freed 72500(4MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 23MB/35MB, paused 6.316ms total 246.658ms
,09-13 15:13:14.824  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 15:13:14.834  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 15:13:14.834  1016  1057 D PackageManager: delete codoeFile: 
,09-13 15:13:14.834  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 15:13:14.844  1016  1057 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
,09-13 15:13:14.844  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 15:13:14.844  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-13 15:13:14.844  1016  1057 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,09-13 15:13:14.844  1016  1057 D PackageManager: result of delete: 1{1039899029}
,09-13 15:13:14.854  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 15:13:14.854  7973  7973 D AndroidRuntime: Shutting down VM
,09-13 15:13:14.854  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 15:13:14.854  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-13 15:13:14.854  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-13 15:13:14.854  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-13 15:13:14.864  1016  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-13 15:13:14.864  1016  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
,09-13 15:13:14.864  1016  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-13 15:13:14.864  1016  1042 W libprocessgroup: failed to open /acct/uid_10001/pid_7474/cgroup.procs: No such file or directory
,09-13 15:13:14.874  7491  7491 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-13 15:13:14.874  7491  7491 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-13 15:13:14.874  7491  7491 I DIAGMON_AGENT: ./extraInfo: "NG700"
,09-13 15:13:14.884  7491  7491 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,09-13 15:13:15.034  7506  7506 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,09-13 15:13:15.034  7506  7506 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,09-13 15:13:15.034  7506  7506 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,09-13 15:13:15.044  7506  7506 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,09-13 15:13:15.064  7973  7973 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-13 15:13:15.074  1016  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-13 15:13:15.074  1016  1057 D PackageManager: userId{-1}
09-13 15:13:15.074  1016  1057 D PackageManager: andCode{true}
,09-13 15:13:15.074  1016  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-13 15:13:15.074  1016  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:13:15.074  1016  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:13:15.074  1016  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:13:15.074  1016  1057 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:13:15.084   290   290 E SMD     : DCD OFF,
09-13 15:13:15.094  8024  8024 E Zygote  : MountEmulatedStorage()
,09-13 15:13:15.094  8024  8024 E Zygote  : v2
09-13 15:13:15.094  8024  8024 I libpersona: KNOX_SDCARD checking this for 10003
09-13 15:13:15.094  8024  8024 I libpersona: KNOX_SDCARD not a persona
,09-13 15:13:15.094  8024  8024 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-13 15:13:15.094  8024  8024 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-13 15:13:15.104  8024  8024 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-13 15:13:15.104  1016  1057 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8024 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-13 15:13:15.114  1016  1474 I ActivityManager: Killing 7524:com.sec.android.soagent/u0a31 (adj 15): empty #21
,09-13 15:13:15.124  1016  1847 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 15:13:15.124  1016  1847 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-13 15:13:15.124  1016  1847 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:15.124  1016  1847 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 15:13:15.124  1016  1847 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 15:13:15.134   311   311 I art     : Explicit concurrent mark sweep GC freed 8686(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 839us total 36.200ms
,09-13 15:13:15.144   279  1011 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-13 15:13:15.144   279  1011 D Netd    : getNetworkForDns: using netid 504 for uid 10011
,09-13 15:13:15.144  8024  8024 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-13 15:13:15.144  8024  8024 D ActivityThread: Added TimaKeyStore provider
,09-13 15:13:15.164   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 699us total 20.944ms
,09-13 15:13:15.184   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 768us total 19.782ms
,09-13 15:13:15.194  3828  3828 E MDM     : [1] SitrepService.a: No Google accounts; deferring server state update.
,09-13 15:13:15.224  3828  3828 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-13 15:13:15.234  1016  1463 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-13 15:13:15.234  1016  1463 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,09-13 15:13:15.234  3828  7521 I iu.UploadsManager: num queued entries: 0
,09-13 15:13:15.234  1016  1463 W ActivityManager: userId = 0, bbcId = -10000
,09-13 15:13:15.234  1016  1463 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-13 15:13:15.234  1016  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-13 15:13:15.234  3828  7521 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-13 15:13:15.234  3828  7521 E SQLiteLog: (3850) statement aborts at 61: [UPDATE media_record SET upload_state=? WHERE upload_account_id != -1 AND upload_state = 200] disk I/O error
,09-13 15:13:15.234  3828  3828 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 15:13:15.244  3828  3828 I Kids    : [GCoreUtils] Current gmscore version, 8115234 is smaller than the required version 8400000
,09-13 15:13:15.244  3828  7521 E AndroidRuntime: FATAL EXCEPTION: iu-sync-manager
09-13 15:13:15.244  3828  7521 E AndroidRuntime: Process: com.google.android.gms, PID: 3828
09-13 15:13:15.244  3828  7521 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 15:13:15.244  3828  7521 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 15:13:15.244  3828  7521 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
09-13 15:13:15.244  3828  7521 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 15:13:15.244  3828  7521 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 15:13:15.244  3828  7521 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1714)
09-13 15:13:15.244  3828  7521 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1660)
09-13 15:13:15.244  3828  7521 E AndroidRuntime: 	at com.google.android.libraries.social.autobackup.ae.a(SourceFile:403)
09-13 15:13:15.244  3828  7521 E AndroidRuntime: 	at com.google.android.libraries.social.autobackup.j.a(SourceFile:307)
09-13 15:13:15.244  3828  7521 E AndroidRuntime: 	at com.google.android.libraries.social.autobackup.j.b(SourceFile:43)
09-13 15:13:15.244  3828  7521 E AndroidRuntime: 	at com.google.android.libraries.social.autobackup.l.handleMessage(SourceFile:218)
09-13 15:13:15.244  3828  7521 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 15:13:15.244  3828  7521 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
09-13 15:13:15.244  3828  7521 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-13 15:13:15.244  1016  1479 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
09-13 15:13:15.244  2828  2828 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Sep 13 15:13:15 GMT+02:00 2016
,09-13 15:13:15.254  1016  1851 I ActivityManager: Killing 7541:com.sec.spp.push/u0a32 (adj 15): empty #21
,09-13 15:13:15.254  1016  1463 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-13 15:13:15.254  1016  1463 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-13 15:13:15.254  1016  1463 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:15.254  1016  1463 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:15.254  1016  1463 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-13 15:13:15.254  2828  2828 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-13 15:13:15.264  1016  8044 E DropBoxManagerService: Can't write: system_app_crash
09-13 15:13:15.264  1016  8044 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop190.tmp: open failed: EROFS (Read-only file system)
09-13 15:13:15.264  1016  8044 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-13 15:13:15.264  1016  8044 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 15:13:15.264  1016  8044 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 15:13:15.264  1016  8044 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 15:13:15.264  1016  8044 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-13 15:13:15.264  1016  8044 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
09-13 15:13:15.264  1016  8044 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 15:13:15.264  1016  8044 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 15:13:15.264  1016  8044 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 15:13:15.264  1016  8044 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-13 15:13:15.264  1016  8044 E DropBoxManagerService: 	... 5 more
,09-13 15:13:15.264  2828  2828 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-13 15:13:15.264  3828  7521 I Process : Sending signal. PID: 3828 SIG: 9
,09-13 15:13:15.264  1016  1079 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-13 15:13:15.264  2828  2828 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-13 15:13:15.264  1016  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:13:15.264  1016  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:13:15.264  1016  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-13 15:13:15.264  1016  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-13 15:13:15.274  2828  2828 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-13 15:13:15.274  8046  8046 E Zygote  : MountEmulatedStorage()
,09-13 15:13:15.274  8046  8046 E Zygote  : v2
09-13 15:13:15.274  8046  8046 I libpersona: KNOX_SDCARD checking this for 10031
09-13 15:13:15.274  8046  8046 I libpersona: KNOX_SDCARD not a persona
,09-13 15:13:15.284  8046  8046 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-13 15:13:15.284  1016  1079 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=8046 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
09-13 15:13:15.284  8046  8046 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-13 15:13:15.284  8046  8046 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-13 15:13:15.284  1016  1850 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
09-13 15:13:15.284  1016  1850 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0,
09-13 15:13:15.284  2828  8045 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
09-13 15:13:15.284  1016  1850 W ActivityManager: userId = 0, bbcId = -10000
09-13 15:13:15.284  1016  1850 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-13 15:13:15.284  1016  1850 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,09-13 15:13:15.294  2828  8045 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-13 15:13:15.294  2828  8045 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,09-13 15:13:15.294  2828  8045 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
,09-13 15:13:15.304  1016  1079 I ActivityManager: Process com.google.android.gms (pid 3828)(adj 9) has died(210,658)
,09-13 15:13:15.304  2828  8045 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
09-13 15:13:15.304  1016  1079 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.am.SmartAdjustManager.SPCMLocked:1235 com.android.server.am.ActivityManagerService.updateOomAdjLocked:22618 com.android.server.am.ActivityManagerService.appDiedLocked:6728 com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied:1579 
,09-13 15:13:15.304  2828  8045 E SQLiteLog: (28) failed to open "/data/data/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)

```
