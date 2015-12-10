#### Test 506502784dae475_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system
D/SSRM:n  (  738): SIOP:: AP = 310, PST = 333, CUR = 450
,--------- beginning of main
D/AndroidRuntime( 6494): 
D/AndroidRuntime( 6494): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6494): CheckJNI is OFF
D/AndroidRuntime( 6494): readGMSProperty: start
D/AndroidRuntime( 6494): readGMSProperty: already setted!!
D/AndroidRuntime( 6494): readGMSProperty: end
D/AndroidRuntime( 6494): addProductProperty: start
I/ClearcutLoggerApiImpl( 1401): disconnect managed GoogleApiClient
E/AffinityControl( 6494): AffinityControl: registerfunction enter
D/AndroidRuntime( 6494): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  738): inState():  stateMachine is null !!
I/PersonaManagerService(  738): PersonaId don't exist
I/ActivityManager(  738): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  738): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  738): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  738): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  738): mDVFSHelper.acquire()
D/FocusedStackFrame(  738): Set to : 0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6511): MountEmulatedStorage()
E/Zygote  ( 6511): v2
I/libpersona( 6511): KNOX_SDCARD checking this for 10280
I/libpersona( 6511): KNOX_SDCARD not a persona
I/ActivityManager(  738): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6511 uid=10280 gids={50280, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6511): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6511): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6511): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon(  738): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  738): setMouseCustomIcon IconType is same.101
D/PointerIcon(  738): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  738): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 6494): Shutting down VM
D/TimaKeyStoreProvider( 6511): TimaSignature is unavailable
D/ActivityThread( 6511): Added TimaKeyStore provider
V/WindowOrientationListener(  738): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  738): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  738): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  738): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  738): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 6511): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/SurfaceWidgetView( 1465): destroyHardwareResources():804962691
I/SurfaceFlinger(  254): id=7 Removed Mauncher (6/8)
I/SurfaceFlinger(  254): id=7 Removed Mauncher (-2/8)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1771): [237392/8] Surface widget visibility changed visibility = false on instance = 1
V/ActivityThread( 1465): updateVisibility : ActivityRecord{276fa468 token=android.os.BinderProxy@239dee7d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1465): onTrimMemory. Level: 20
,I/WebViewFactory( 6511): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/ResourcesManager( 6511): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 6511): Loading: webviewchromium
I/LibraryLoader( 6511): Time to load native libraries: 5 ms (timestamps 7844-7849)
I/LibraryLoader( 6511): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6511): Binding Chromium to main looper Looper (main, tid 1) {88f1e85}
I/LibraryLoader( 6511): Expected native library version number "",actual native library version number ""
I/chromium( 6511): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6511): Initializing chromium process, renderers=0
W/art     ( 6511): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 6511): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 6511): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6511): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
I/chromium( 6511): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
D/BluetoothAdapter( 6511): 538621146: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 6511): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6511): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6511): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6511): Local Branch: mybranch5813579
I/Adreno-EGL( 6511): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6511): Local Patches: NONE
I/Adreno-EGL( 6511): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
W/chromium( 6511): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 6511): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6511): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6511): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6511): CordovaWebView is running on device made by: samsung
W/art     ( 6511): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6511): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity( 6511): performCreate Call secproduct feature valuefalse
D/Activity( 6511): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 6511): Render dirty regions requested: true
D/Atlas   ( 6511): Validating map...
D/ActivityManager(  738): post active user change for 0
D/KnoxTimeoutHandler(  738): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  738): handleActiveUserChange for user 0
I/SurfaceFlinger(  254): id=12 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService(  738): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  738): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  738): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  738): setMouseCustomIcon IconType is same.101
D/PointerIcon(  738): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  738): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer( 6511): Initialized EGL, version 1.4
I/OpenGLRenderer( 6511): HWUI protection enabled for context ,  &this =0xb3a5dcb8 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 6511): Enabling debug mode 0
V/ActivityThread( 6511): updateVisibility : ActivityRecord{2b4bdefb token=android.os.BinderProxy@2e2db2f5 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
E/SMD     (  296): DCD ON
D/InputMethodManagerService(  738): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager(  738): mDVFSHelper.release()
I/Timeline(  738): Timeline: Activity_windows_visible id: ActivityRecord{2dcbf811 u0 com.test.thalitest/.MainActivity t3} time:158244
W/IInputConnectionWrapper( 6511): showStatusIcon on inactive InputConnection
I/Timeline( 6511): Timeline: Activity_idle id: android.os.BinderProxy@2e2db2f5 time:158247
I/SamsungIME( 1723): getCurrentCandidateView
D/SamsungIME( 1723): Dismiss ExpandCandiate
I/chromium( 6511): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6511): 
D/JsMessageQueue( 6511): Set native->JS mode to OnlineEventsBridgeMode
I/SamsungIME( 1723): getDebugLevel  : 0x4f4c
I/SamsungIME( 1723): getDebugLevel  : 0x4f4c
D/jxcore_app_log( 6511): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1357818240
D/JX-Cordova( 6511): jxcore cordova android initializing
I/SamsungIME( 1723): KeybaordView init() : load resources
I/SamsungIME( 1723): getCurrentKeyboard
I/SamsungIME( 1723): getTextKeyboard
D/SamsungIME( 1723): [SwiftkeyWrapper] currentLangauge : 1701729619
I/ServiceManager(  370): Waiting for service AtCmdFwd...
D/SamsungIME( 1723): [SwiftkeyWrapper] currentLangauge : 1701729619
I/ServiceManager(  370): Waiting for service AtCmdFwd...
,W/jxcore-log( 6511): Initializing JXcore engine
W/jxcore-log( 6511): JXcore engine is ready
,W/jxcore-log( 6511): Starting JXcore engine
,E/auditd  ( 1835): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  738): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
D/SecurityLogAgent:SEDenialService(  738): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,I/ActivityManager(  738): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6576 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 6576): MountEmulatedStorage()
,E/Zygote  ( 6576): v2
I/libpersona( 6576): KNOX_SDCARD checking this for 1000
I/libpersona( 6576): KNOX_SDCARD not a persona
,I/SELinux ( 6576): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6576): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6576): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6576): TimaSignature is unavailable
,D/ActivityThread( 6576): Added TimaKeyStore provider
,D/ResourcesManager( 6576): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 6576):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6576):  SeDenialReceiver : File path = null
,W/jxcore-log( 6511): Platform android
W/jxcore-log( 6511): 
W/jxcore-log( 6511): Process ARCH arm
W/jxcore-log( 6511): 
,I/ActivityManager(  738): Killing 5615:flipboard.app/u0a125 (adj 15): bgCount ##41
,V/AlarmManager(  738): waitForAlarm result :4
,V/AlarmManager(  738): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager(  738): <AppSync3 Whitelist>
,V/AlarmManager(  738): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/NtpTrustedTime(  738): forceRefresh() from cache miss
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/NtpTrustedTime(  738): forceRefresh Fail.
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4320, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): stay LED for fully charged
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,I/jxcore-log( 6511): JXcore Cordova bridge is ready!
I/jxcore-log( 6511): 
,W/jxcore-log( 6511): JXcore engine is started
,I/jxcore-log( 6511): Toggling radios to true
I/jxcore-log( 6511): 
,D/BluetoothAdapter( 6511): enable()
,W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=6511, uid=10280 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService(  738): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService(  738): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6511, uid=10280 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService(  738): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/BluetoothManagerService(  738): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2141)
W/BluetoothManagerService(  738): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:671)
W/BluetoothManagerService(  738): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService(  738): 	at android.os.Binder.execTransact(Binder.java:446)
E/DevicePolicyManagerService(  738): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService(  738): getAllowBluetoothMode - value retunrs : 2
,D/SettingsProvider(  738): name = bluetooth_on
,E/DevicePolicyManagerService(  738): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService(  738): getAllowBluetoothMode - value retunrs : 2
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,I/WifiManager( 6511): packageName : com.test.thalitest
,D/SecContentProvider(  738): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  738): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  738): mCursor = null
,D/WifiService(  738): setWifiEnabled: true pid=6511, uid=10280
,W/ActivityManager(  738): Permission Denial: getCurrentUser() from pid=6511, uid=10280 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  738): Failed getting userId using ActivityManagerNative
W/WifiService(  738): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6511, uid=10280 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  738): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/WifiService(  738): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2181)
W/WifiService(  738): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2169)
W/WifiService(  738): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  738): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  738): name = wifi_on
,I/WifiService(  738): disconnect: pid=6511, uid=10280
E/WifiHW  (  738): ##################### set firmware type 0 #####################
I/WifiHW  (  288): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
I/WifiHW  (  288): module is semco
E/WifiHW  (  288): ==========[WIFI] SEMCO MODULE ===========
I/WifiHW  (  288): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
E/WifiHW  (  288): TEMP_FAILURE_RETRY complete
D/SoftapController(  288): Softap fwReload - Ok
I/jxcore-log( 6511): Radios toggled
I/jxcore-log( 6511): 
D/CommandListener(  288): Setting iface cfg
D/CommandListener(  288): Trying to bring down wlan0
,E/Zygote  ( 6604): MountEmulatedStorage()
I/libpersona( 6604): KNOX_SDCARD checking this for 1002
E/Zygote  ( 6604): v2
I/libpersona( 6604): KNOX_SDCARD not a persona
D/CommandListener(  288): Clearing all IP addresses on wlan0
,I/ActivityManager(  738): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6604 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,E/WifiHW  (  738): supplicant_name : p2p_supplicant
D/SmartBondingService(  738): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
D/WifiMonitor(  738): startMonitoring(wlan0) with mConnected = false
,I/SELinux ( 6604): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6604): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6604): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=false enabledDesc:null
,D/STATUSBAR-WifiQuickSettingButton( 1185): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1185): Wifi onReceive(2)
,D/SmartBondingService(  738): getNetworkEnabled : wifi : false mobile : true
D/HotspotTile( 1185): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1185): onStateChanged: Wi-Fi
,D/HotspotTile( 1185): onReceive : 2, 0
,D/WifiCredService( 1306): Action received :android.net.wifi.WIFI_STATE_CHANGED
,E/Zygote  ( 6612): MountEmulatedStorage()
,E/Zygote  ( 6612): v2
I/libpersona( 6612): KNOX_SDCARD checking this for 10152
I/libpersona( 6612): KNOX_SDCARD not a persona
,I/ActivityManager(  738): Start proc tv.peel.samsung.app for broadcast tv.peel.samsung.app/com.peel.receiver.ConnectivityActionReceiver: pid=6612 uid=10152 gids={50152, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/wpa_supplicant( 6610): [wpa_supplicant_init]: use SECRIL
,I/wpa_supplicant( 6610): Successfully initialized wpa_supplicant
,I/SecureStorage( 6610): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,I/SecureStorage( 6610): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  446): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6610
,I/SecureStorage(  446): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
I/SecureStorage( 6610): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6610): ssSupport state is = 1
,I/wpa_supplicant( 6610): >>>>> GET KEY, IV <<<<<
,I/SecureStorage( 6610): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  446): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6610
I/SecureStorage(  446): [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,I/SELinux ( 6612): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/TimaKeyStoreProvider( 6604): TimaSignature is unavailable
,D/ActivityThread( 6604): Added TimaKeyStore provider
,I/SELinux ( 6612): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6612): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 6604): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
W/ResourcesManager( 6604): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6604): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/BluetoothA2dpSinkServiceJni( 6604): register_com_android_bluetooth_a2dp_sink
,D/TimaKeyStoreProvider( 6612): TimaSignature is unavailable
,D/ActivityThread( 6612): Added TimaKeyStore provider
,D/ResourcesManager( 6612): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,D/BtSettings.ProfileConfig( 6604): Adding GattService
,D/BtSettings.ProfileConfig( 6604): Adding HeadsetService
D/BtSettings.ProfileConfig( 6604): Adding A2dpService
,D/BtSettings.ProfileConfig( 6604): Adding HidService
D/BtSettings.ProfileConfig( 6604): Adding HealthService
D/BtSettings.ProfileConfig( 6604): Adding PanService
D/BtSettings.ProfileConfig( 6604): Adding BluetoothMapService
,D/BtSettings.ProfileConfig( 6604): Adding SapService
D/BtSettings.ProfileConfig( 6604): Adding HeadsetClientService
D/BtSettings.ProfileConfig( 6604): Adding A2dpSinkService
D/BtSettings.ProfileConfig( 6604): Adding SapClientService
D/BtSettings.ProfileConfig( 6604): Adding HidDevService
I/BtSettings.ProfileConfig( 6604): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider(  738): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider(  738): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  738): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  738): selectionArgs: false
D/SettingsProvider(  738): selectionArgs: 1002
D/SecContentProvider(  738): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  738): ret = -1
,W/BackupManagerService(  738): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  738): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider(  738): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  738): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  738): selectionArgs: false
D/SettingsProvider(  738): selectionArgs: 1002
D/SecContentProvider(  738): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  738): ret = -1
,W/BackupManagerService(  738): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  738): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,D/SettingsProvider(  738): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  738): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  738): selectionArgs: false
D/SettingsProvider(  738): selectionArgs: 1002
D/SecContentProvider(  738): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  738): ret = -1
,E/SMD     (  296): DCD ON
W/BackupManagerService(  738): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  738): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider(  738): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  738): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  738): selectionArgs: false
D/SettingsProvider(  738): selectionArgs: 1002
D/SecContentProvider(  738): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  738): ret = -1
,W/BackupManagerService(  738): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  738): name = bt_svcst_com.android.bluetooth.hdp.HealthService
,D/SettingsProvider(  738): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  738): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  738): selectionArgs: false
D/SettingsProvider(  738): selectionArgs: 1002
D/SecContentProvider(  738): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  738): ret = -1
,W/BackupManagerService(  738): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  738): name = bt_svcst_com.android.bluetooth.pan.PanService
,D/SettingsProvider(  738): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  738): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  738): selectionArgs: false
D/SettingsProvider(  738): selectionArgs: 1002
D/SecContentProvider(  738): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  738): ret = -1
,W/BackupManagerService(  738): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  738): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider(  738): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  738): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  738): selectionArgs: false
D/SettingsProvider(  738): selectionArgs: 1002
D/SecContentProvider(  738): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  738): ret = -1
,W/BackupManagerService(  738): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  738): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider(  738): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  738): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  738): selectionArgs: false
D/SettingsProvider(  738): selectionArgs: 1002
D/SecContentProvider(  738): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  738): ret = -1
,W/BackupManagerService(  738): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  738): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,D/SettingsProvider(  738): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  738): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  738): selectionArgs: false
D/SettingsProvider(  738): selectionArgs: 1002
D/SecContentProvider(  738): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  738): ret = -1
,W/BackupManagerService(  738): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  738): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider(  738): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  738): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  738): selectionArgs: false
D/SettingsProvider(  738): selectionArgs: 1002
D/SecContentProvider(  738): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  738): ret = -1
,W/BackupManagerService(  738): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  738): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider(  738): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  738): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  738): selectionArgs: false
D/SettingsProvider(  738): selectionArgs: 1002
D/SecContentProvider(  738): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  738): ret = -1
,W/BackupManagerService(  738): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  738): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider(  738): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  738): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  738): selectionArgs: false
D/SettingsProvider(  738): selectionArgs: 1002
D/SecContentProvider(  738): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  738): ret = -1
,W/BackupManagerService(  738): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterState( 6604): make
,I/bluedroid( 6604): init
,I/BluetoothAdapterState( 6604): Entering OffState
,I/bte_conf( 6604): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 6604): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6604): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6604): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif ( 6604): btif_fetch_local_ble_random_bdaddr
,I/bluedroid( 6604): get_profile_interface socket
I/bluedroid( 6604): get_profile_interface map_client
,I/GKI_LINUX( 6604): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterService( 6604): checkAddrForIOP: Loading from conf
,D/BluetoothAdapterProperties( 6604): Address is:E0:DB:10:1F:C9:5E
E/BluetoothServiceJni( 6604): populateRssiValuesNative
I/bluedroid( 6604): getModelRssiValues
E/BluetoothServiceJni( 6604): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 6604): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothAdapterProperties( 6604): Name is: Note3-1
,D/SettingsProvider(  738): name = bluetooth_name
,I/bluedroid( 6604): config_hci_snoop_log
,D/BluetoothManagerService(  738): Broadcasting onBluetoothServiceUp() to 10 receivers.
,E/DevicePolicyManagerService(  738): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService(  738): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider(  738): uri = 3 selection = isBluetoothEnabled
,D/BluetoothAdapterState( 6604): CURRENT_STATE=OFF, MSG = USER_TURN_ON
,D/BluetoothAdapterProperties( 6604): Setting state to 11
I/BluetoothAdapterState( 6604): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 6604): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 6604): updateAdapterState state is 11
,D/BluetoothAdapterService( 6604): Autoconnection is available 
D/BluetoothAdapterService( 6604): updateAdapterState prevState = 10newState = 11
,D/BluetoothSecureManager( 6604): getInstant: null
,W/InputMethodManagerService(  738): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService(  738): [BT Setting State] State =11
D/BluetoothSecureManager( 6604): calling getMethod for getService
D/BluetoothSecureManager( 6604): calling getService
,D/BluetoothTile( 1185):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1185): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothSecureManager( 6604): getService return binder: android.os.BinderProxy@432a283
,D/BluetoothSecureManagerService(  738): isSecureModeEnabled
D/BluetoothSecureManagerService(  738): getSecureModeSetting, name: secure_mode_enable
D/BtConfig.SecureMode( 6604): isSecureModeOn:false
D/StatusBarManagerService(  738): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
,D/BtSettings.ProfileConfig( 6604): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 6604): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 6604): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,I/SamsungIME( 1723): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
D/StatusBarManagerService(  738): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1185): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 )
W/BluetoothAdapterService( 6604): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,D/STATUSBAR-QSTileView( 1185): onStateChanged: Bluetooth
D/BtSettings.ProfileConfig( 6604): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 6604): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 6604): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 6604): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 6604): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 6604): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 6604): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 6604): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 6604): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 6604): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 6604): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 6604): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 6604): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 6604): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 6604): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6604): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,D/BtSettings.ProfileConfig( 6604): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6604): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 6604): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 6604): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,D/BluetoothBondStateMachine( 6604): make
,W/BluetoothAdapterService( 6604): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,D/BtSettings.ProfileConfig( 6604): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 6604): Not skipping com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 6604): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 6604): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 6604): Not skipping com.android.bluetooth.hfp.HeadsetService
,I/BtGatt.JNI( 6604): classInitNative(L890): classInitNative: Success!
I/BluetoothBondStateMachine( 6604): StableState(): Entering Off State
W/BluetoothAdapterService( 6604): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 6604): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 6604): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 6604): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 6604): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 6604): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 6604): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 6604): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 6604): Not skipping com.android.bluetooth.hdp.HealthService
,D/BtGatt.DebugUtils( 6604): handleDebugAction() action=null
D/BtGatt.GattService( 6604): Received start request. Starting profile...
D/BtGatt.GattService( 6604): start()
,I/bluedroid( 6604): get_profile_interface gatt
D/BluetoothAdapterService( 6604): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@201ab4da
,D/BtGatt.AdvertiseManager( 6604): advertise manager created
,W/BluetoothAdapterService( 6604): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 6604): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 6604): Not skipping com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 6604): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 6604): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 6604): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 6604): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 6604): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 6604): Not skipping com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 6604): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@201ab4da
,W/BluetoothAdapterService( 6604): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 6604): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6604): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6604): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 6604): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6604): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6604): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 6604): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6604): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6604): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 6604): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 6604): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState( 6604): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetService( 6604): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 6604): classInitNative: succeeds
,D/HeadsetStateMachine( 6604): make
,E/HeadsetStateMachine( 6604): # of Max HF connection is 2
,I/bluedroid( 6604): get_profile_interface handsfree
,I/DualScoManager( 6604): Instantiating Dual Sco Manager
,I/DualScoManager( 6604): Set HeadsetServiceHelper
,D/BluetoothAtMessage( 6604): createCMTIContentObservers
,D/SettingsProvider(  738): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider(  738): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  738): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  738): selectionArgs: false
D/SettingsProvider(  738): selectionArgs: 1002
D/SecContentProvider(  738): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  738): ret = -1
,W/BackupManagerService(  738): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine( 6604): Enter Disconnected: -2
,D/BluetoothAdapterService( 6604): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@201ab4da
,E/HeadsetStateMachine( 6604): set to mRemoteBrsf = 0
,D/A2dpService( 6604): Received start request. Starting profile...
,D/BluetoothA2dp(  738): Proxy object connected
,I/BluetoothAvrcpServiceJni( 6604): classInitNative: succeeds
,V/Avrcp   ( 6604): make
,V/Avrcp   ( 6604): Avrcp
,I/bluedroid( 6604): get_profile_interface avrcp
,D/HeadsetStateMachine( 6604): map size, before remove : 0
D/HeadsetStateMachine( 6604): map size, after remove: 0
D/HeadsetStateMachine( 6604): mNextConnectingDevice : null
,V/Avrcp   ( 6604): start
,E/RemoteController( 6604): Cannot set synchronization mode on an unregistered RemoteController
,V/Avrcp   ( 6604): ++registerMediaPlayers++
,I/Avrcp   ( 6604): No of Audio players :: 2
,I/Avrcp   ( 6604): App Package name is com.google.android.music
,D/ResourcesManager( 6604): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/SecureStorage(  446): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,D/BluetoothA2dp( 2949): Proxy object connected
,I/Avrcp   ( 6604): App pkg name is Google Play Music
,I/PowerManagerService(  738): [PWL] Off : 105s ago
,I/Avrcp   ( 6604): Name::Google Play Music
,V/Avrcp   ( 6604): MediaPlayerInfo: mPlayerId=1
I/Avrcp   ( 6604): App Package name is com.sec.android.app.music
,D/ResourcesManager( 6604): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/Avrcp   ( 6604): App pkg name is Music
,I/Avrcp   ( 6604): Name::Music
V/Avrcp   ( 6604): MediaPlayerInfo: mPlayerId=2
I/Avrcp   ( 6604):  set player publishabilty with player id::2 toBePublished ::true
,I/Avrcp   ( 6604): No of Video players :: 1
,I/Avrcp   ( 6604): Video App Package name is com.sec.android.app.videoplayer
,D/ResourcesManager( 6604): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/Avrcp   ( 6604): Video App pkg name is Video Player
,I/Avrcp   ( 6604): Name::Video Player
V/Avrcp   ( 6604): MediaPlayerInfo: mPlayerId=3
I/Avrcp   ( 6604): Add tempPlayer
V/Avrcp   ( 6604): MediaPlayerInfo: mPlayerId=4
I/Avrcp   ( 6604): Total no of players: 4
V/Avrcp   ( 6604): swapping the samsung player with 1st player
I/Avrcp   ( 6604):  Updating now playing list upon AVRCP Start
I/WebViewFactory( 6612): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,V/Avrcp   ( 6604): handleMessage, msg=207
D/BluetoothMediaBrowser( 6604):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,I/BluetoothA2dpServiceJni( 6604): classInitNative: succeeds
D/A2dpStateMachine( 6604): make
,D/ResourcesManager( 6612): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/bluedroid( 6604): get_profile_interface a2dp
I/GKI_LINUX( 6604): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 6604): warning : media task started media_task_refcnt 1 
,D/BluetoothAdapterService( 6604): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@201ab4da
,D/A2dpStateMachine( 6604): Enter Disconnected: -2
I/BluetoothHidServiceJni( 6604): classInitNative: succeeds
,D/BluetoothMediaBrowser( 6604): no now playing list
D/BluetoothMediaBrowser( 6604):  getNowPlayingId now playing id : -1
D/Avrcp   ( 6604):  checkNowPlayingList start
,D/HidService( 6604): Received start request. Starting profile...
I/bluedroid( 6604): get_profile_interface hidhost
D/HidService( 6604): setHidService(): set to: null
D/BluetoothAdapterService( 6604): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@201ab4da
,I/BluetoothHealthServiceJni( 6604): classInitNative: succeeds
,D/HealthService( 6604): Received start request. Starting profile...
,I/bluedroid( 6604): get_profile_interface health
,D/BluetoothAdapterService( 6604): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@201ab4da
,I/BluetoothPanServiceJni( 6604): classInitNative(L105): succeeds
,D/BluetoothPan(  738): BluetoothPAN Proxy object connected
,D/PanService( 6604): Received start request. Starting profile...
I/LibraryLoader( 6612): Loading: webviewchromium
D/BluetoothPanServiceJni( 6604): initializeNative(L110): pan
I/bluedroid( 6604): get_profile_interface pan
,D/BluetoothAdapterService( 6604): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@201ab4da
,D/BluetoothMapService( 6604): Received start request. Starting profile...
,I/LibraryLoader( 6612): Time to load native libraries: 5 ms (timestamps 1401-1406)
,I/LibraryLoader( 6612): Expected native library version number "",actual native library version number ""
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6662): MountEmulatedStorage()
,E/Zygote  ( 6662): v2
I/libpersona( 6662): KNOX_SDCARD checking this for 10186
I/libpersona( 6662): KNOX_SDCARD not a persona
,I/ActivityManager(  738): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=6662 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 6662): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6662): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6662): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/WebViewChromiumFactoryProvider( 6612): Binding Chromium to main looper Looper (main, tid 1) {9159d0b}
,I/LibraryLoader( 6612): Expected native library version number "",actual native library version number ""
,I/chromium( 6612): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,D/TimaKeyStoreProvider( 6662): TimaSignature is unavailable
,D/ActivityThread( 6662): Added TimaKeyStore provider
,I/BrowserStartupController( 6612): Initializing chromium process, renderers=0
,W/art     ( 6612): Attempt to remove local handle scope entry from IRT, ignoring
,D/ResourcesManager( 6662): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 6662): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6662): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6662): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6662): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6662): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/chromium( 6612): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 6612): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,I/chromium( 6612): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=36 off=46780 len=2953
I/chromium( 6612): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:37 off:229536 len:643667
,I/Adreno-EGL( 6612): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6612): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6612): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6612): Local Branch: mybranch5813579
I/Adreno-EGL( 6612): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6612): Local Patches: NONE
I/Adreno-EGL( 6612): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,D/RCPManagerService(  738): exchangeData() failure , invalid userId
,I/SecureStorage( 6610): [INFO]: SPID(0x00000000)Processing data has been completed
,D/RCPManagerService(  738): exchangeData() failure , invalid userId
,I/SecureStorage( 6610): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6610): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  446): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6610
I/SecureStorage(  446): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
I/SecureStorage( 6610): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6610): ssSupport state is = 1
I/wpa_supplicant( 6610): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6610): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6610): SIM READ ERROR
I/wpa_supplicant( 6610): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6610): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6610): SIM READ ERROR
I/wpa_supplicant( 6610): Blacklist: Clear (all) 
I/wpa_supplicant( 6610): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6610): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant( 6610): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6610): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
D/BluetoothAdapterService( 6604): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@201ab4da
I/wpa_supplicant( 6610): rfkill: Cannot open RFKILL control device
E/BluetoothAdapterService(538621146)( 6604): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
D/RCPManagerService(  738): exchangeData() failure , invalid userId
I/BluetoothSAPServiceJni( 6604): classInitNative(L204): succeeds
D/SapService( 6604): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 6604): initializeNative(L209): sap
I/bluedroid( 6604): get_profile_interface sap
D/BluetoothAdapterService( 6604): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@201ab4da
D/HeadsetStateMachine( 6604): Try to query the phonestate on bind
W/chromium( 6612): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
D/BadgeProvider( 6080): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
I/Telecom ( 1416): BluetoothPhoneService: queryPhoneState
I/Telecom ( 1416): BluetoothPhoneService: updateHeadsetWithCallState
I/Telecom ( 1416): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 1416): Proxy not attached to service
W/chromium( 6612): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
D/HeadsetStateMachine( 6604): Proxy object connected
D/HeadsetPhoneState( 6604): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetPhoneState( 6604): sendDeviceDataStateChanged
,D/HeadsetPhoneState( 6604): Signal level : previous=0 curr=0
V/HeadsetService( 6604): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
E/BluetoothAdapterService(538621146)( 6604): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
D/BluetoothA2dp( 6604): Proxy object connected
D/BluetoothAdapterService( 6604): Bluetooth A2dp source service connected
E/BluetoothAdapterService(538621146)( 6604): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/HeadsetStateMachine( 6604): Disconnected process message: 11
D/HeadsetStateMachine( 6604): Disconnected process message: 18
D/HeadsetStateMachine( 6604): Disconnected process message: 10
,D/HeadsetPhoneState( 6604): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6604): Disconnected process message: 11
,E/BluetoothAdapterService(538621146)( 6604): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
E/BluetoothAdapterService(538621146)( 6604): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
E/BluetoothAdapterService(538621146)( 6604): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
I/ActivityManager(  738): Killing 4985:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,E/BluetoothAdapterService(538621146)( 6604): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(538621146)( 6604): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState( 6604): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 6604): enable
,D/BadgeProvider( 6080): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6080): sendNotify, [notify] : null
D/BadgeProvider( 6080): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6080): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 6080): update, [UpdateCount] : 1
,I/bt_hci_bdroid( 6604): init
D/Launcher.Model( 1465): reloadBadges entered.
,I/GKI_LINUX( 6604): gki_task_entry task_id=0 [BTU] starting
,I/bt_vendor( 6604): init
,I/bt_vnd_conf( 6604): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 6604): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 6604): userial_init
D/bt_vendor( 6604): op for 5
,D/bt_vendor( 6604): op for 0
,D/bt_upio ( 6604): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 6604): is_emulator_context : 0
,D/bt_upio ( 6604): is_rfkill_disabled ? [0]
D/bt_upio ( 6604): is_rfkill_disabled ? [0]
,D/bt_vendor( 6604): op for 0
D/bt_upio ( 6604): upio_set_bluetooth_power(on: 1)
,D/bt_upio ( 6604): is_emulator_context : 0
D/bt_upio ( 6604): is_rfkill_disabled ? [0]
,D/bt_vendor( 6604): op for 3
I/bt_userial_vendor( 6604): userial vendor open: opening /dev/ttyHS0
I/bt_userial_vendor( 6604): userial_vendor_open():UART is setup
I/bt_userial_vendor( 6604): device fd = 65 open
,D/bt_vendor( 6604): op for 1
E/bt_hwcfg( 6604): Start CFG HW, HCI reset
,D/bt_userial( 6604): Entering userial_read_thread()
,W/art     ( 6612): Attempt to remove local handle scope entry from IRT, ignoring
,D/RCPManagerService(  738): exchangeData() failure , invalid userId
,W/AwContents( 6612): onDetachedFromWindow called when already detached. Ignoring
,E/bt_hwcfg( 6604): Read Local Name after HCI reset
,D/bt_hwcfg( 6604): Chipset BCM4335C0
D/bt_hwcfg( 6604): Target name = [BCM4335C0]
,I/bt_hwcfg( 6604): module_type[semco].
I/bt_hwcfg( 6604): not ZERO...
I/bt_hwcfg( 6604): module_type[semco] is invalid.
E/bt_hwcfg( 6604): patchram path ORG . BCM4335C0
E/bt_hwcfg( 6604): patchram path ORG .. BCM4335C0
E/bt_hwcfg( 6604): patchram path ORG bcm2079xB4_firmware.ncd BCM4335C0
E/bt_hwcfg( 6604): patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335C0
E/bt_hwcfg( 6604): patchram path ORG bcm2079xB5_firmware.ncd BCM4335C0
E/bt_hwcfg( 6604): patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335C0
E/bt_hwcfg( 6604): patchram path ORG bcm4335_V0093.0399.hcd BCM4335C0
E/bt_hwcfg( 6604): patchram path ORG bcm4335_V0093.0399_wisol.hcd BCM4335C0
E/bt_hwcfg( 6604): fw ver (org)0.0
E/bt_hwcfg( 6604): vendor lib preload failed to locate firmware patch file
E/bt_hwcfg( 6604): Remove module rev, try again BCM4335
D/bt_hwcfg( 6604): Target name = [BCM4335]
I/bt_hwcfg( 6604): module_type[semco].
I/bt_hwcfg( 6604): not ZERO...
I/bt_hwcfg( 6604): module_type[semco] is invalid.
E/bt_hwcfg( 6604): patchram path ORG . BCM4335
E/bt_hwcfg( 6604): patchram path ORG .. BCM4335
E/bt_hwcfg( 6604): patchram path ORG bcm2079xB4_firmware.ncd BCM4335
E/bt_hwcfg( 6604): patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335
E/bt_hwcfg( 6604): patchram path ORG bcm2079xB5_firmware.ncd BCM4335
E/bt_hwcfg( 6604): patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335
E/bt_hwcfg( 6604): patchram path ORG bcm4335_V0093.0399.hcd BCM4335
I/bt_hwcfg( 6604): patch(org) : bcm4335_V0093.0399.hcd
I/bt_hwcfg( 6604): Found patchfile: /vendor/firmware/bcm4335_V0093.0399.hcd
E/bt_hwcfg( 6604): ORG patchram base 0093
E/bt_hwcfg( 6604): ORG patchram minor 0399
E/bt_hwcfg( 6604): fw ver (org)93.399
E/bt_hwcfg( 6604): Final Patchram is /vendor/firmware/bcm4335_V0093.0399.hcd
,I/bt_hwcfg( 6604): Axi patch failure or not include AXI patching
I/bt_hwcfg( 6604): bt vendor lib: set UART baud 3000000
E/SignOutReceiver( 6232): WIFI_STATE_CHANGED_ACTION
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6576): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6576): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6576): StateMachine : Current State = 1
,D/SecurityLogAgent( 6576): StateMachine : Changed Current State = 1
,I/ActivityManager(  738): Killing 4914:com.google.android.gm/u0a128 (adj 15): bgCount ##41
,D/BluetoothNotiBroadcastReceiver( 1306): onReceive
,D/AuthorizationBluetoothService( 1401): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ActivityManager(  738): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/bt_hwcfg( 6604): bt vendor lib: set UART baud 115200
,I/bt_hwcfg( 6604): FW Download delta = 528943
,D/bt_hwcfg( 6604): Settlement delay -- 100 ms
I/bt_hwcfg( 6604): Setting fw settlement delay to 100 
,E/Tethering(  738): No numeric data
,D/NtpTrustedTime(  738): forceRefresh() from cache miss
,D/NtpTrustedTime(  738): forceRefresh Fail.
V/NetworkStats(  738): performPollLocked(flags=0x1)
,D/HotspotTile( 1185): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1185): updateTetherState():false, false
,D/Tethering(  738): sendTetherStateChangedBroadcast 1, 0, 0
D/NetworkStatsFactory(  738): UpdateStatsForKnox
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  738): performPollLocked() took 4ms
,D/NtpTrustedTime(  738): forceRefresh() from cache miss
,D/NtpTrustedTime(  738): forceRefresh Fail.
,I/bt_hwcfg( 6604): bt vendor lib: set UART baud 3000000
,I/wpa_supplicant( 6610): wlan0: Setting scan request: 0 sec 100000 usec
,I/bt_hwcfg( 6604): vendor lib fwcfg completed
,I/        ( 6604): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6604): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6604): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6604): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6604): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6604): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6604): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6604): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6604): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6604): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6604): BTE_InitTraceLevels -- TRC_SAP
I/        ( 6604): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6604): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6604): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6604): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6604): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 6604): BTE_InitTraceLevels -- TRC_PROTOCOL
,I/wpa_supplicant( 6610): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/SecureStorage( 6610): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6610): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  446): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6610
I/SecureStorage(  446): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
I/SecureStorage( 6610): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6610): ssSupport state is = 1
,I/SecureStorage( 6610): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,I/SecureStorage( 6610): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  446): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6610
I/SecureStorage(  446): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
I/SecureStorage( 6610): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6610): ssSupport state is = 1
,I/wpa_supplicant( 6610): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6610): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6610): SIM READ ERROR
I/wpa_supplicant( 6610): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant( 6610): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 6610): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 6610): p2p0: State: INACTIVE -> DISCONNECTED
I/wpa_supplicant( 6610): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant( 6610): Skip scan - bUseNetwork false
,E/WifiStateMachine(  738): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative-HAL(  738): callSECApiBoolean - ID [21]
,I/wpa_supplicant( 6610): HOTSPOT20_ENABLE called
I/wpa_supplicant( 6610): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6610): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6610): SIM READ ERROR
,I/wpa_supplicant( 6610): Blacklist: Clear (all) 
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 6610): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 6610): Skip scan - bUseNetwork false
,D/WifiNative-HAL(  738): callSECApiInt - ID [210]
,D/SmartBondingService(  738): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
D/WifiConfigStore(  738): Loading config and enabling all networks 
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
,D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
,D/STATUSBAR-WifiQuickSettingButton( 1185): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1185): Wifi onReceive(3)
,D/SmartBondingService(  738): getNetworkEnabled : wifi : true mobile : true
D/WifiCredService( 1306): Action received :android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 1185): onStateChanged: Wi-Fi
,D/HotspotTile( 1185): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1185): onReceive : 3, 0
,E/SignOutReceiver( 6232): WIFI_STATE_CHANGED_ACTION
,E/WifiConfigStore(  738): Not a HS20
,E/WifiConfigStore(  738): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 6576): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6576): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6576): StateMachine : Current State = 1
,D/WifiNative-HAL(  738): callSECApiInt - ID [65]
,D/SecurityLogAgent( 6576): StateMachine : Changed Current State = 1
,D/WifiNative-HAL(  738): callSECApiBoolean - ID [13]
I/wpa_supplicant( 6610): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 6610): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 6610): reset timer : RESET_TIMER 0
I/wpa_supplicant( 6610): P2P: Current p2p state = IDLE
I/wpa_supplicant( 6610): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 6610): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 6610): First Scan Start
,I/wpa_supplicant( 6610): Scan requested (ret=0) - scan timeout 30 seconds
,D/WifiNative-HAL(  738): Setting external_sim to 1
D/WifiStateMachine(  738): Setting OUI to DA-A1-19
I/WifiNative-HAL(  738): startHal
,E/wifi    (  738): getStaticLongField sWifiHalHandle 0x9ac5086c
D/wifi    (  738): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0xc015de
I/WifiNative-HAL(  738): Could not start hal
,E/native  (  738): do suspend true
,D/WifiP2pService(  738): P2pDisabledState{ what=131203 }
,D/CommandListener(  288): Setting iface cfg
D/CommandListener(  288): Trying to bring up p2p0
,D/WifiMonitor(  738): startMonitoring(p2p0) with mConnected = true
,D/WifiP2pService(  738): P2pEnablingState
,D/WifiP2pService(  738): P2pEnablingState{ what=147457 }
D/WifiP2pService(  738): P2p socket connection successful
,D/WifiP2pService(  738): P2pEnabledState
,E/WifiStateMachine(  738): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/WifiDisplayController(  738): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  738): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  738): disconnect
D/WifiDisplayController(  738): updateConnection
D/WifiDisplayController(  738): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayAdapter(  738): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
D/WifiP2pService(  738): sending p2p connection changed broadcast: IDLE
,I/ActivityManager(  738): Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=6724 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6724): MountEmulatedStorage()
E/Zygote  ( 6724): v2
I/libpersona( 6724): KNOX_SDCARD checking this for 10192
I/libpersona( 6724): KNOX_SDCARD not a persona
E/WifiStateMachine(  738): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,E/WifiStateMachine(  738): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-HAL(  738): callSECStringApiVoid - ID [215]
E/WifiNative-HAL(  738): invaild command id : 215
,D/WifiP2pService(  738): create mNetworkAgent
,D/WifiScanningService(  738): SCAN_AVAILABLE : 3
,D/RttService(  738): SCAN_AVAILABLE : 3
,D/WifiDisplayController(  738): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiScanningService(  738): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,D/RttService(  738): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  738): startHal
,D/ConnectivityService(  738): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  738): Got NetworkAgent Messenger
D/ConnectivityService(  738): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService(  738): updateNetworkInfo()
D/ConnectivityService(  738): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  738): NetworkAgent connected
,E/CSLegacyTypeTracker(  738): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,I/SELinux ( 6724): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6724): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6724): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/AllShareCastTile( 1185): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter(  738): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 1185): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,W/bt-l2cap( 6604): l2c_link_processs_ble_num_bufs 15
,E/bt-btm  ( 6604): BTM_SecRegister:p_cb_info->p_le_callback == 0xafa18b05 
E/bt-btm  ( 6604): BTM_SecRegister: btm_cb.api.p_le_callback = 0xafa18b05 
,I/wpa_supplicant( 6610): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,D/TimaKeyStoreProvider( 6724): TimaSignature is unavailable
,D/ActivityThread( 6724): Added TimaKeyStore provider
,I/wpa_supplicant( 6610): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiNative-HAL(  738): p2pGetDeviceAddress
,E/wifi    (  738): getStaticLongField sWifiHalHandle 0x92ef799c
D/WifiNative-HAL(  738): p2pGetDeviceAddress returning ea:50:8b:de:28:a3
D/wifi    (  738): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x80087e
I/WifiNative-HAL(  738): Could not start hal
E/WifiScanningService(  738): could not start HAL
,D/WifiP2pService(  738): DeviceAddress: ea:28:a3
,D/WifiDisplayController(  738): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
D/WifiDisplayController(  738):  deviceAddress: ea:50:8b:de:28:a3
D/WifiDisplayController(  738):  primary type: 10-0050F204-5
D/WifiDisplayController(  738):  secondary type: null
D/WifiDisplayController(  738):  wps: 0
D/WifiDisplayController(  738):  grpcapab: 0
D/WifiDisplayController(  738):  devcapab: 0
D/WifiDisplayController(  738):  status: 3
D/WifiDisplayController(  738):  wfdInfo: null
D/WifiDisplayController(  738):  groupownerAddress: null
D/WifiDisplayController(  738):  GOdeviceName: null
D/WifiDisplayController(  738):  interfaceAddress: 
D/WifiDisplayController(  738):  SConnectInfo : null
,D/SecContentProvider2(  738): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  738): mCursor = null
,D/ResourcesManager( 6724): creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,D/SecContentProvider2(  738): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  738): mCursor = null
,D/WifiP2pService(  738): sending p2p persistent groups changed broadcast
,D/WifiP2pService(  738): InactiveState
E/ConnectivityService(  738): updateNetworkInfo()
D/ConnectivityService(  738): ignoring duplicate network state non-change. WIFI_P2P, state = UNKNOWN
D/WifiP2pService(  738): InactiveState{ what=143376 }
D/WifiP2pService(  738): P2pEnabledState{ what=143376 }
,I/wpa_supplicant( 6610): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,D/WifiP2pService(  738): InactiveState{ what=143376 }
,D/WifiP2pService(  738): P2pEnabledState{ what=143376 }
,D/WifiDirectBR( 6724): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,I/ActivityManager(  738): Killing 5723:com.sec.android.widgetapp.activeapplicationwidget/u0a182 (adj 15): bgCount ##41
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1306): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1306): MountReceiver.mPrefHandler - 7002
,D/FileShare-Server( 6379): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/WifiDirectBR( 6724): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiDirectBR( 6724): WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,W/ContextImpl( 6724): Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,D/WifiDirectBR( 6724): stopServiceTest : false
,D/BluetoothAdapterProperties( 6604): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 0 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = false
,E/bt-btif ( 6604): Calling BTA_HhEnable
,E/bt-btif ( 6604): btif_storage_get_adapter_property service_mask:0x2120048
D/BluetoothAdapterProperties( 6604): Address is:E0:DB:10:1F:C9:5E
E/BluetoothServiceJni( 6604): populateRssiValuesNative
I/bluedroid( 6604): getModelRssiValues
E/BluetoothServiceJni( 6604): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 6604): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothAdapterProperties( 6604): Name is: Note3-1
D/SettingsProvider(  738): name = bluetooth_name
D/BluetoothAdapterProperties( 6604): Scan Mode:20
,D/BluetoothAdapterProperties( 6604): Discoverable Timeout:120
D/BluetoothAdapterProperties( 6604): LE Address is:E0:B7:20:3E:93:BC
E/bt-btif ( 6604): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 6604): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,D/bt_vendor( 6604): op for 2
D/bt_vendor( 6604): op for 6
E/bt-btif ( 6604): btif_sock_init: !radio_req && !rfc_init
E/bt-btif ( 6604): btif_sock_init: !vhci_init
,D/IOP_DB_BT( 6604): db_open: file /etc/bluetooth/iop_bt.db
,D/bt_vendor( 6604): op for 7
,D/IOP_DB_BT( 6604): db_open: db_open : handle 3026210832l, read 14063 bytes onto local cache
D/IOP_DB_BT( 6604): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/bt_upio ( 6604): proc btwrite assertion
,D/IOP_DB_BT( 6604): db_query: result 1
I/        ( 6604): iop_db_open: iop_db_open status 0
D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
,D/bte_conf( 6604): Device ID record 1 : primary
D/bte_conf( 6604):   vendorId            = 0075
D/bte_conf( 6604):   vendorIdSource      = 0001
D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
,D/bte_conf( 6604):   product             = 0100
D/bte_conf( 6604):   version             = 0200
D/bte_conf( 6604):   clientExecutableURL = 
D/bte_conf( 6604):   serviceDescription  = 
D/bte_conf( 6604):   documentationURL    = 
,D/bte_conf( 6604): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 6604): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6604): ScanMode =  20
D/BluetoothAdapterProperties( 6604): State =  11
,D/BluetoothPanServiceJni( 6604): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/SecContentProvider(  738): uri = 3 selection = isDiscoverableEnabled
,D/BluetoothAdapterProperties( 6604): Setting state to 12
I/BluetoothAdapterState( 6604): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterProperties( 6604): Scan Mode:21
D/BluetoothAdapterProperties( 6604): Discoverable Timeout:120
,D/SettingsProvider(  738): name = bluetooth_a2dp_sink_mode
D/SettingsProvider(  738): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  738): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  738): selectionArgs: false
D/SettingsProvider(  738): selectionArgs: 1002
D/SecContentProvider(  738): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  738): ret = -1
,W/BackupManagerService(  738): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService( 6604): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 6604): updateAdapterState state is 12
,D/BluetoothAdapterService( 6604): Autoconnection is available 
,D/BluetoothAdapterService( 6604): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 6604): starting service from this receiver
,D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
,D/BluetoothA2dp(  738): onBluetoothStateChange: up=true
D/BluetoothA2dp( 2949): onBluetoothStateChange: up=true
E/bt_h4   ( 6604): vendor lib postload completed
D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
,D/BluetoothA2dp( 6604): onBluetoothStateChange: up=true
,I/BluetoothAdapterState( 6604): Entering On State from state = 11
,D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
,D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
,W/InputMethodManagerService(  738): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  738): [BT Setting State] State =12
I/InputMethodManagerService(  738): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
,D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
,D/BluetoothHeadset( 1416): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@ee8b0e1, true
,D/BluetoothTile( 1185):  onBluetoothStateChange:
D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
D/BluetoothHeadset( 1416): registerMessageListener
,I/SamsungIME( 1723): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
,D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
,D/HeadsetService( 6604): registerMessageListener
,D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
D/HeadsetService( 6604): registerMessageListener
,D/HeadsetStateMachine( 6604): Disconnected process message: 70
D/HeadsetStateMachine( 6604): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2a33cfd5
,D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
,D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
,I/Telecom ( 1416): BluetoothPhoneService: updateHeadsetWithCallState
D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
,D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
,I/Telecom ( 1416): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
I/BluetoothPbapService( 6604): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,D/HeadsetStateMachine( 6604): Disconnected process message: 9
,D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
D/BluetoothTile( 1185):  onBluetoothPairedDevicesChanged:
D/HeadsetStateMachine( 6604): mNumActive: 0 mNumHeld: 0 mCallState: 6
,D/BluetoothTile( 1185): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
,D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
,D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
,D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
,D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
,D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
,D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
,D/audio_hw_primary(  303): adev_set_parameters: enter: A2dpSuspended=false
V/voice   (  303): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  303): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  303): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  303): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  303): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  303): adev_set_parameters: exit
E/HeadsetStateMachine( 6604): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
D/StatusBarManagerService(  738): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
D/StatusBarManagerService(  738): setIconVisibility slot=bluetooth visible=true
D/PhoneStatusBar( 1185): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
D/BluetoothTile( 1185):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 1185): onStateChanged: Bluetooth
D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
,I/art     (  738): Explicit concurrent mark sweep GC freed 64019(3MB) AllocSpace objects, 30(480KB) LOS objects, 17% free, 37MB/45MB, paused 1.388ms total 92.254ms
,W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/BluetoothPbapService( 6604): Handler(): got msg=1
,D/BluetoothManagerService(  738): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/SecContentProvider(  738): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,V/BluetoothPbapService( 6604): PBAP Service initSocket try: 0
,W/BluetoothAdapter( 6604): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 6604): set MAP SDP message type : 1
,D/BluetoothSocket( 6604): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
D/BluetoothSocket( 6604): bindListen(), new LocalSocket 
D/BluetoothSocket( 6604): bindListen(), new LocalSocket.getInputStream() 
D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
D/BluetoothSocket( 6604): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c2b8124
D/BluetoothSocket( 6604): channel: 19
D/BluetoothPbapService( 6604): PBAP Socket is BluetoothServerSocket
,W/BluetoothAdapter( 6604): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6604): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 6604): bindListen(), new LocalSocket 
D/BluetoothSocket( 6604): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6604): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@5b7248d
D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
D/BluetoothSocket( 6604): channel: 5
,D/LocalBluetoothProfileManager( 1306): Adding local A2DP profile
,D/LocalBluetoothProfileManager( 1306): Adding local HEADSET profile
,E/BluetoothHeadset( 1306): BTStateChangeCB is registed
,E/BluetoothHeadset( 1306): BluetoothHeadset service is binded
,W/ContextImpl( 1306): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/Bluetoothsap( 1306): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 1306): PANU : true
,D/LocalBluetoothProfileManager( 1306): Adding local MAP profile
,D/BluetoothMap( 1306): Create BluetoothMap proxy object
,W/LocalBluetoothProfileManager( 1306): Warning: SAP profile was previously added.
,D/LocalBluetoothProfileManager( 1306): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1306): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1306): onReceive
,D/BluetoothAdapterService( 6604): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@201ab4da
D/BluetoothA2dp( 1306): Proxy object connected
D/BtConfig.SecureMode( 6604): isSecureModeOn:false
,D/A2dpProfile( 1306): Bluetooth service connected
,D/HeadsetProfile( 1306): Bluetooth service connected
,D/AuthorizationBluetoothService( 1401): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/Bluetoothsap( 1306): BluetoothSAP Proxy object connected
,D/SapProfile( 1306): Bluetooth service connected
,D/Bluetoothsap( 1306): getConnectedDevices()
,D/BluetoothInputDevice( 1306): Proxy object connected
,D/HidProfile( 1306): Bluetooth service connected
,D/BluetoothPan( 1306): BluetoothPAN Proxy object connected
,D/PanProfile( 1306): Bluetooth service connected
,D/BluetoothMap( 1306): Proxy object connected
,D/MapProfile( 1306): Bluetooth service connected
D/BluetoothPbap( 1306): Proxy object connected
D/PbapServerProfile( 1306): Bluetooth service connected
,D/SecContentProvider(  738): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/BluetoothAdapter( 6604): getBluetoothService() called with no BluetoothManagerCallback
,D/bt_vendor( 6604): op for 7
D/bt_upio ( 6604): BT_WAKE is asserted already
,D/BluetoothSocket( 6604): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
D/BluetoothSocket( 6604): bindListen(), new LocalSocket 
D/BluetoothSocket( 6604): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6604): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ed994af
D/BluetoothSocket( 6604): channel: 12
I/BtOppRfcommListener( 6604): Accept thread started.
,I/wpa_supplicant( 6610): nl80211: Received scan results (7 BSSes)
I/wpa_supplicant( 6610): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 6610): Trying to associate with C0.AA.4A (SSID='4E473730303567' freq=5220 MHz)
I/wpa_supplicant( 6610): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 6610): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E473730303567
,I/WifiNative-HAL(  738): startHal
E/wifi    (  738): getStaticLongField sWifiHalHandle 0x9ac5088c
D/wifi    (  738): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x3018f2
I/WifiNative-HAL(  738): Could not start hal
,D/SecContentProvider2(  738): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  738): mCursor = null
,I/wpa_supplicant( 6610): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 6610): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E473730303567
,I/wpa_supplicant( 6610): Associated with C0.AA.4A
,D/SecContentProvider2(  738): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  738): mCursor = null
,I/wpa_supplicant( 6610): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 6610): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.4A SSID=4E473730303567
,D/SecContentProvider2(  738): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  738): mCursor = null
,I/wpa_supplicant( 6610): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 6610): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 6610): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.4A SSID=4E473730303567
,I/wpa_supplicant( 6610): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6610): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 6610): CTRL-EVENT-CONNECTED - Connection to C0.AA.4A completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 6610): Blacklist: Clear (temp) 
I/wpa_supplicant( 6610): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.4A SSID=4E473730303567
,D/WifiNative-HAL(  738): callSECApiVoid - ID [50]
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  738): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  738): Got NetworkAgent Messenger
D/ConnectivityService(  738): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  738): updateNetworkInfo()
D/ConnectivityService(  738): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  738): NetworkAgent connected
E/WifiConfigStore(  738): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  738): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  288): Setting iface cfg
,E/Zygote  ( 6755): MountEmulatedStorage()
,E/Zygote  ( 6755): v2
I/libpersona( 6755): KNOX_SDCARD checking this for 10038
I/libpersona( 6755): KNOX_SDCARD not a persona
,I/ActivityManager(  738): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=6755 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,E/WifiStateMachine(  738): Start Dhcp Watchdog 1
,D/SecContentProvider2(  738): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  738): mCursor = null
,D/ConnectivityService(  738): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,W/Atfwd_Sendcmd(  370): AtCmdFwd service not published, waiting... retryCnt : 4
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
I/SELinux ( 6755): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
,I/SELinux ( 6755): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6755): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6755): TimaSignature is unavailable
,D/ActivityThread( 6755): Added TimaKeyStore provider
,D/ResourcesManager( 6755): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 6755): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/native  (  738): do suspend false
,D/SecContentProvider2(  738): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  738): mCursor = null
,D/WifiP2pService(  738): InactiveState{ what=143375 }
,D/WifiP2pService(  738): P2pEnabledState{ what=143375 }
,I/VlingoApplication( 6755): VlingoApplication appVersion ='11.2.2.0.37649', ro.csc.sales_code=XEO
,E/BluetoothHeadset( 6755): BTStateChangeCB is registed
,E/BluetoothHeadset( 6755): BluetoothHeadset service is binded
,I/ActivityManager(  738): Killing 5803:com.google.android.gms:car/u0a15 (adj 15): bgCount ##41
,I/Hs20UtilService( 1306): Starting #2
,I/Hs20UtilService( 1306): Message received 5007
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1306): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1306): MountReceiver.mPrefHandler - 7002
,E/dhcpcd  ( 6774): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6774): version 5.5.6 starting
,D/SettingsProvider(  738): name = driving_mode_on
,D/SettingsProvider(  738): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  738): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  738): selectionArgs: false
D/SettingsProvider(  738): selectionArgs: 10038
D/SecContentProvider(  738): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  738): ret = -1
,D/BluetoothManager( 6755): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,E/dhcpcd  ( 6774): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6232): NETWORK_STATE_CHANGED_ACTION
,I/dhcpcd  ( 6774): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6774): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6774): if(wlan0) info get Success. (MAC : C0.AA.4A)
,I/dhcpcd  ( 6774): bssid match
,I/dhcpcd  ( 6774): wlan0: rebinding lease of 192.168.1.128
,E/SMD     (  296): DCD ON
,D/bt_vendor( 6604): op for 7
,D/bt_upio ( 6604): ..proc_btwrite_timeout..
,I/dhcpcd  ( 6774): wlan0: acknowledged 192.168.1.128 from 192.168.1.1
,I/dhcpcd  ( 6774): wlan0: leased 192.168.1.128 for 86400 seconds
,D/ConnectivityService(  738): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,W/ProcessCpuTracker(  738): Skipping unknown process pid 6788
,W/ProcessCpuTracker(  738): Skipping unknown process pid 6808
,E/native  (  738): do suspend true
,D/WifiP2pService(  738): InactiveState{ what=143375 }
,D/WifiP2pService(  738): P2pEnabledState{ what=143375 }
,D/ConnectivityService(  738): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine(  738): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG7005g"WPA_PSK
,E/WifiStateMachine(  738): VerifyingLinkState enter
,D/WifiNative-HAL(  738): callSECApiInt - ID [210]
,E/ConnectivityService(  738): updateNetworkInfo()
,D/ConnectivityService(  738): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService(  738): Adding iface wlan0 to network 502
,D/WifiWatchdogStateMachine(  738): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  738): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver(  738): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker(  738): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  738): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine(  738): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,I/WifiTrafficPoller(  738): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine(  738): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  738): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  738): mBoosterFLAG : 0
I/WifiTrafficPoller(  738): current booster mode : FullMode
D/WifiNative-HAL(  738): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): applyOpen
,D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
,I/Hs20UtilService( 1306): Starting #3
,I/Hs20UtilService( 1306): Message received 5007
D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1306): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): Adding Route [fe80::/64 -> :: wlan0] to network 502
,D/ConnectivityService(  738): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,D/ConnectivityService(  738): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 502
,E/ConnectivityService(  738): Unexpected mtu value: 0, wlan0
,E/SignOutReceiver( 6232): NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService(  738): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  738): updateSourceRoutes : add src route for:192.168.1.128
,V/        (  288): QcRouteController
,I/Hs20UtilService( 1306): Starting #4
I/Hs20UtilService( 1306): Message received 5007
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1306): DMSUtil.isNetworkConnected - flag-null, state-null
,V/        (  288): QcRouteController
D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1306): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1306): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1306): MountReceiver.mPrefHandler - 7002
,V/        (  288): QcRouteController
,V/        (  288): QcRouteController
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6232): NETWORK_STATE_CHANGED_ACTION
,V/        (  288): QcRouteController
,I/Hs20UtilService( 1306): Starting #5
,I/Hs20UtilService( 1306): Message received 5007
,D/NearbySettings( 1306): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1306): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine(  738): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        (  288): QcRouteController
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/        (  288): QcRouteController
,E/SignOutReceiver( 6232): NETWORK_STATE_CHANGED_ACTION
,V/        (  288): QcRouteController
,I/SurfaceFlinger(  254): id=13 createSurf (1x1),1 flag=4, Uoast
,V/        (  288): QcRouteController
,D/PowerManagerService(  738): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=738
,D/ConnectivityService(  738): Setting Dns servers for network 502 to [/192.168.1.1]
,D/ConnectivityService(  738): LTETest block dns file not exists
,V/Nat464Xlat(  738): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  738): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  738): calling update connectivity
,D/ConnectivityService(  738): ignoring duplicate network state non-change. WIFI, state = CONNECTING
E/ConnectivityService(  738): updateNetworkInfo()
D/ConnectivityService(  738): ignoring duplicate network state non-change. WIFI, state = CONNECTING
E/ConnectivityService(  738): updateNetworkInfo()
D/ConnectivityService(  738): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  738): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  738): calling update connectivity
D/ConnectivityService(  738): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  738):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  738):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  738):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/EntConnectivity(  738): Not allowed due to - mEnabled false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): Checking http://clients3.google.com/generate_204 on "NG7005g"
,I/System.out(  738): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(  738): (HTTPLog)-Static: isShipBuild true
I/System.out(  738): (HTTPLog)-Thread-178-90430789: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(  738): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService(  738): currentScore = 0, newScore = 60
D/ConnectivityService(  738):    accepting network in place of null
D/ConnectivityService(  738): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  738): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
,D/TelephonyNetworkFactory( 1445): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  738): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker(  738): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
D/ConnectivityService(  738): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  738): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  738): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/SmartBondingService(  738): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  738): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/Tethering(  738): MasterInitialState.processMessage what=3
D/SmartBondingService(  738): getSBEnabled() enabled =false
D/SmartBondingService(  738): getSBEnabled() enabled =false
D/SmartBondingService(  738): getSBEnabled() enabled =false
,V/NetworkStats(  738): updateIfacesLocked()
V/NetworkStats(  738): performPollLocked(flags=0x1)
D/SmartBondingService(  738): getNetworkEnabled : wifi : true mobile : true
,D/NetworkStatsFactory(  738): UpdateStatsForKnox
D/ConnectivityService(  738): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  738): forceRefresh() from cache miss
,V/NetworkStats(  738): performPollLocked() took 3ms
,D/NtpTrustedTime(  738): forceRefresh Fail.
,E/Watchdog(  738): !@Sync 5
D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  738): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/EntConnectivity(  738): Not allowed due to - mEnabled false
,D/StatusBar.NetworkController( 1185): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1185): updateDataNetType()
D/StatusBar.NetworkController( 1185): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1185): updateLTEICONDataNetType:0
D/ConnectivityService(  738): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  738): calling update connectivity
D/ConnectivityService(  738):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  738):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/NtpTrustedTime(  738): forceRefresh() from cache miss
D/NtpTrustedTime(  738): forceRefresh Fail.
D/ConnectivityService(  738): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1185): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1185): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
,I/System.out(  738): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 12:37:43 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449751062889], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449751062873]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  738): Validated
D/ConnectivityService(  738): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  738): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  738):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  738):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  738): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService(  738): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  738): calling update connectivity
D/ConnectivityService(  738):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  738):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  738): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1185): CM callback handler got msg 524290
D/ConnectivityService(  738): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1185): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1185): updateDataNetType()
D/StatusBar.NetworkController( 1185): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1185): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1185): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,D/ConnectivityService(  738): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  738): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  738): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  738): SmartBondingReceiver: wifi ap is changed, init speed ratio
D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  738): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  738): getSBEnabled() enabled =false
D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  738): getSBEnabled() enabled =false
D/SmartBondingService(  738): getSBEnabled() enabled =false
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  738): forceRefresh() from cache miss
,D/NtpTrustedTime(  738): forceRefresh Fail.
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  738): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3161): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3161): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 3161): [com.wssyncmldm.llllIIIllIlIIIIllllI(263/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  738): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1870): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
W/ContextImpl( 1870): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,I/DBG_DM  ( 3161): [llIlIIIIlllIlllllIll(224/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,I/DBG_DM  ( 3161): [IIllIIllIIIlllIlIIll(403/llllllIllIlIlllIIlIl)] Check completed.
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 5952): SPPPushClient is installed : true
D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PCWCLIENTTRACE_PushUtil( 5952): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5952): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5952): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 5113): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3161): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3161): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 3161): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 3161): [IIIlllIlIIlllIIIIllI(73/llllIIIllIlIIIIllllI)] 
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6846): MountEmulatedStorage()
E/Zygote  ( 6846): v2
I/libpersona( 6846): KNOX_SDCARD checking this for 10004
I/libpersona( 6846): KNOX_SDCARD not a persona
,I/DBG_DM  ( 3161): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3161): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 8
,I/ActivityManager(  738): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6846 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_DM  ( 3161): [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 2
,I/DBG_DM  ( 3161): [IIllIIllIIIlllIlIIll(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,I/DBG_DM  ( 3161): [IIllIIllIIIlllIlIIll(177/lllIlIlIIIllIIlIllIl)] nDownloadPostpone is [8]
,I/SELinux ( 6846): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6846): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6846): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3161): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 0
,I/DBG_DM  ( 3161): [IIllIlIIlIlllIIllIII(741/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/DBG_DM  ( 3161): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1273/handleMessage)] event ->220
,I/DBG_DM  ( 3161): [llIlIIIIlllIlllllIll(280/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,D/TimaKeyStoreProvider( 6846): TimaSignature is unavailable
,I/DBG_DM  ( 3161): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
D/ActivityThread( 6846): Added TimaKeyStore provider
,I/DBG_DM  ( 3161): [com.wssyncmldm.XDMService(876/IIIIllIlIIlIIIIlllIl)] 
,I/DBG_DM  ( 3161): [llIlIIIIlllIlllllIll(1907/lllIlIlIIIllIIlIllIl)] 
,I/DBG_DM  ( 3161): [com.wssyncmldm.XDMBroadcastReceiver(332/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 3161): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(501/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,D/ResourcesManager( 6846): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/DBG_DM  ( 3161): [com.wssyncmldm.db.file.XDB(4994/IIIlllIlIIlllIIIIllI)] Get Autoinstall status : false
,I/DBG_DM  ( 3161): [IIllIlIIlIlllIIllIII(695/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,I/DBG_DM  ( 3161): [com.wssyncmldm.XDMService(819/IllIlIIIIlIIlIIIllIl)] Idle Screen : false
,I/DBG_DM  ( 3161): [com.wssyncmldm.XDMService(638/llllIIIllIlIIIIllllI)] 
,E/DBG_DM  ( 3161): [com.wssyncmldm.XDMService(646/llllIIIllIlIIIIllllI)] didn't register
,E/DBG_DM  ( 3161): [com.wssyncmldm.XDMService(647/llllIIIllIlIIIIllllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@9318b90
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3161): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3161): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 6869): MountEmulatedStorage()
,E/Zygote  ( 6869): v2
I/libpersona( 6869): KNOX_SDCARD checking this for 10104
I/libpersona( 6869): KNOX_SDCARD not a persona
,I/ActivityManager(  738): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6869 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6869): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/SecContentProvider2(  738): uri = 14 selection = getSealedState
,D/SecContentProvider2(  738): mCursor = null
,I/SELinux ( 6869): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6869): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/ApplicationPolicy(  738): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  738): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager(  738): showStatusBarByNotification() mOpenByNotification=false
,D/ResourcesManager( 1185): creating new AssetManager and set to /system/priv-app/SyncmlDM/SyncmlDM.apk
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DBG_DM  ( 3161): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
,I/DBG_DM  ( 3161): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/TimaKeyStoreProvider( 6869): TimaSignature is unavailable
,D/ActivityThread( 6869): Added TimaKeyStore provider
,I/VacuumService( 1401): Vacuum at: now=1449751063671 tag=VacuumService
,D/KnoxNotification( 1185): ----- inflateViews : modified publicViewLocal -----
,D/ResourcesManager( 6869): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/KnoxNotification( 1185): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1185): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 1185): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@8701b0b
D/PersonaManager( 1185): isKioskContainerExistOnDevice
D/PersonaManager( 1185): isKioskContainerExistOnDevice
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3161): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 3161): [com.wssyncmldm.ui.XUIFotaPostponeActivity(378/lllIlIlIIIllIIlIllIl)] No idle Postpone
,I/DBG_DM  ( 3161): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
,E/Zygote  ( 6887): MountEmulatedStorage()
E/Zygote  ( 6887): v2
I/libpersona( 6887): KNOX_SDCARD checking this for 1000
I/libpersona( 6887): KNOX_SDCARD not a persona
,I/ActivityManager(  738): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6887 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     (  350): Explicit concurrent mark sweep GC freed 8759(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 298us total 12.671ms
,I/art     (  350): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 270us total 9.299ms
,I/art     (  350): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 268us total 9.273ms
,I/SELinux ( 6887): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6887): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6887): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PanelView( 1185): There is/are notification(s) 
D/PanelView( 1185): There is/are notification(s) 
E/GpsLocationProvider(  738): No APN found to select.
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 6887): TimaSignature is unavailable
,D/ActivityThread( 6887): Added TimaKeyStore provider
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityThread( 1743): Failed to find provider info for com.android.contacts.metadata
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 6887): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1401): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  738): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 19631, reason: UserStart, SyncResult: databaseError: true stats []
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  738): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 197254, reason: UserStart
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DIAGMON_AGENT( 6887): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Auth.Api.Credentials( 1743): [CredentialSyncAdapter] Unknown sync event.
,I/DIAGMON_AGENT( 6887): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,D/SecContentProvider2(  738): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  738): mCursor = null
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DelayedSyncController( 6869): Delaying sync.
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:n  (  738): SIOP:: AP = 370, PST = 336, CUR = 450
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  296): DCD ON
,D/PerfProfileCollectorService( 1743): User is not opt-in to Usage & Diagnostics.
,D/PerfProfileCollectorService( 1743): removeStateFiles() called
D/PerfProfileCollectorService( 1743): User is not opt-in to Usage & Diagnostics.
,I/ActivityManager(  738): Killing 5821:com.android.defcontainer/u0a7 (adj 15): bgCount ##41
,E/ConnectivityChangeReceiver( 1743): Ignoring connectivity change
,I/DIAGMON_AGENT( 6887): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DIAGMON_AGENT( 6887): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6887): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6887): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  738): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  738): apparently satisfied.  currentScore=60
D/ConnectivityService(  738): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  738): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,D/ConnectivityManager.CallbackHandler( 1743): CM callback handler got msg 524290
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6919): MountEmulatedStorage()
,E/Zygote  ( 6919): v2
I/libpersona( 6919): KNOX_SDCARD checking this for 10014
I/libpersona( 6919): KNOX_SDCARD not a persona
,I/ActivityManager(  738): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=6919 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6919): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6919): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6919): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 6919): TimaSignature is unavailable
,D/ActivityThread( 6919): Added TimaKeyStore provider
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 6919): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PicasaService( 5204): start picasa sync
,D/DelayedSyncController( 6869): Delaying sync.
,D/PicasaService( 5204): end picasa sync
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=true
,D/ConnectivityService(  738): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService(  738): identical MTU - not setting
D/ConnectivityService(  738): updateSourceRoutes : add source routing for type : 1
,D/ConnectivityService(  738): updateSourceRoutes : add src route for:fe80::ea50:8bff:fede:28a3
D/SmartBondingService(  738): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  738): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  738): getSBEnabled() enabled =false
D/SmartBondingService(  738): getSBEnabled() enabled =false
D/SmartBondingService(  738): getSBEnabled() enabled =false
,V/        (  288): QcRouteController
,V/        (  288): QcRouteController
,W/NetworkManagementService(  738): route cmd failed: 
W/NetworkManagementService(  738): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '54 route replace src v6 wlan0 fe80::ea50:8bff:fede:28a3 2 ::' failed with '400 54 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  738): '
W/NetworkManagementService(  738): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService(  738): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService(  738): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService(  738): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService(  738): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  738): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5625)
W/NetworkManagementService(  738): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5437)
W/NetworkManagementService(  738): 	at com.android.server.ConnectivityService.access$2300(ConnectivityService.java:229)
W/NetworkManagementService(  738): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2382)
W/NetworkManagementService(  738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  738): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  738): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/Nat464Xlat(  738): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  738): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  738): calling update connectivity
D/ConnectivityService(  738):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  738):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  738): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  738):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  738): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1185): CM callback handler got msg 524295
D/ConnectivityService(  738): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityManager.CallbackHandler( 1743): CM callback handler got msg 524295
D/ConnectivityService(  738): calling update connectivity
D/ConnectivityService(  738):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  738):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  738): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  738):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1185): CM callback handler got msg 524295
D/ConnectivityService(  738): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1743): CM callback handler got msg 524295
D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PhenotypeConfigurator( 1401): Scheduling Phenotype for one-off execution 4326 seconds from now (1449751064445)
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GetConfigurationSnapshotOperation( 1401): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
I/FOTA_Client( 6919): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 6919): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,D/PackageManager(  738): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/FOTA_Client( 6919): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/ActivityManager(  738): Killing 5916:com.google.android.partnersetup/u0a19 (adj 15): bgCount ##41
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,I/PhenotypeFlagCommitter( 1401): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1401): Using platform SSLCertificateSocketFactory
,E/Zygote  ( 6948): MountEmulatedStorage()
E/Zygote  ( 6948): v2
I/libpersona( 6948): KNOX_SDCARD checking this for 10023
I/libpersona( 6948): KNOX_SDCARD not a persona
,I/ActivityManager(  738): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6948 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6948): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6948): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6948): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6948): TimaSignature is unavailable
,D/ActivityThread( 6948): Added TimaKeyStore provider
,D/ResourcesManager( 6948): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.511: ( 6948): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6948): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449751064673
,I/KLMS-2.4.511: ( 6948): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6948): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.511: ( 6948): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.511: ( 6948): NetworkChangeOperations(): uploadRequestLog().START 
,W/DriveInitializer( 1743): Awaiting to be initialized
,W/DriveInitializer( 1743): Background init thread started
,I/ActivityManager(  738): Killing 5934:com.samsung.groupcast/u0a20 (adj 15): bgCount ##41
,I/KLMS-2.4.511: ( 6948): StateImplV2(): networkChangeListener().END
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 1743): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,E/Zygote  ( 6966): MountEmulatedStorage()
E/Zygote  ( 6966): v2
I/libpersona( 6966): KNOX_SDCARD checking this for 10036
I/libpersona( 6966): KNOX_SDCARD not a persona
,I/ActivityManager(  738): Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=6966 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  738): Killing 4150:com.sec.android.app.shealth/u0a40 (adj 15): bgCount ##41
,I/SELinux ( 6966): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6966): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6966): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6966): TimaSignature is unavailable
,D/ActivityThread( 6966): Added TimaKeyStore provider
,D/LocationManagerService(  738): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 6966): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,W/ResourcesManager( 6966): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6966): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/DriveInitializer( 1743): Background init thread ended
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Minikin ( 6966): addFont failed to create font /system/fonts/SamsungSans-light.ttf
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,I/System.out( 1401): (HTTPLog)-Static: isSBSettingEnabled false
,E/Zygote  ( 6996): MountEmulatedStorage()
E/Zygote  ( 6996): v2
I/libpersona( 6996): KNOX_SDCARD checking this for 10042
I/libpersona( 6996): KNOX_SDCARD not a persona
,I/ActivityManager(  738): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6996 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6996): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/System.out( 1401): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/SELinux ( 6996): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,I/qtaguid ( 1401): Tagging socket 74 with tag 1000120100000000{268440065,0} uid -1, pid: 1401, getuid(): 10015
E/SELinux ( 6996): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  738): Killing 5986:com.policydm/1000 (adj 15): bgCount ##41
,I/qtaguid ( 1401): Tagging socket 78 with tag 1000120100000000{268440065,0} uid -1, pid: 1401, getuid(): 10015
,D/TimaKeyStoreProvider( 6996): TimaSignature is unavailable
,D/ActivityThread( 6996): Added TimaKeyStore provider
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/dhcpcd  ( 6774): wlan0: sending IPv6 Router Solicitation
,I/ActivityManager(  738): Killing 4695:com.sec.spp.push/u0a43 (adj 15): bgCount ##41
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 6996): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 6996): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,I/jxcore-log( 6511): Test app app.js loaded
I/jxcore-log( 6511): 
,E/Zygote  ( 7016): MountEmulatedStorage()
E/Zygote  ( 7016): v2
I/libpersona( 7016): KNOX_SDCARD checking this for 1000
,I/libpersona( 7016): KNOX_SDCARD not a persona
,I/ActivityManager(  738): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7016 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7016): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7016): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7016): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/chromium( 6511): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  738): Killing 6007:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7016): TimaSignature is unavailable
,D/LocationManagerService(  738): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/ActivityThread( 7016): Added TimaKeyStore provider
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/chromium( 6511): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7016): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,I/System.out( 1401): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1401): Tagging socket 74 with tag 1000120100000000{268440065,0} uid -1, pid: 1401, getuid(): 10015
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,D/LocationManagerService(  738): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7036): MountEmulatedStorage()
E/Zygote  ( 7036): v2
I/libpersona( 7036): KNOX_SDCARD checking this for 10043
I/libpersona( 7036): KNOX_SDCARD not a persona
,I/ActivityManager(  738): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7036 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  738): Killing 6035:com.osp.app.signin/u0a50 (adj 15): bgCount ##41
,I/SELinux ( 7036): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7036): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7036): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7036): TimaSignature is unavailable
,D/ActivityThread( 7036): Added TimaKeyStore provider
,I/System.out( 1401): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1401): Tagging socket 74 with tag 1000120100000000{268440065,0} uid -1, pid: 1401, getuid(): 10015
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7036): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService( 7036): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 7036): [PushClientApplication] Push log off : This is Ship build version
,D/LocationManagerService(  738): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/SPPClientService( 7036): PushLog.txt file is not deleted.
D/SPPClientService( 7036): PushLog.txt file is not deleted.
D/SPPClientService( 7036): ============PushLog. stop!
,E/SPPClientService( 7036): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7053): MountEmulatedStorage()
,E/Zygote  ( 7053): v2
I/libpersona( 7053): KNOX_SDCARD checking this for 10050
I/libpersona( 7053): KNOX_SDCARD not a persona
,I/ActivityManager(  738): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7053 uid=10050 gids={50050, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  738): Killing 6055:com.android.mms/u0a55 (adj 13): bgCount ##41
,I/SELinux ( 7053): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7053): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7053): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/art     (  738): Explicit concurrent mark sweep GC freed 93854(5MB) AllocSpace objects, 10(160KB) LOS objects, 17% free, 37MB/45MB, paused 1.397ms total 100.343ms
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7053): TimaSignature is unavailable
,D/ActivityThread( 7053): Added TimaKeyStore provider
,D/CountryDetector(  738): No listener is left
,I/System.out( 1401): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1401): Tagging socket 74 with tag 1000120100000000{268440065,0} uid -1, pid: 1401, getuid(): 10015
,D/ResourcesManager( 7053): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,I/SA      ( 7053): [SSP] onCreated
,I/SA      ( 7053): [TPM] There is no property file
,I/SA      ( 7053): [SCU] isHaveSA() - false
,I/SA      ( 7053): [TPM] getModelProperty : null
I/SA      ( 7053): [TPM] getCSCProperty : null
,I/SA      ( 7053): [DM] init START
,I/SA      ( 7053): [DM] This device is not a Vodafone
,I/SA      ( 7053): checkReactivationActive for LOLLIPOP
,I/SA      ( 7053): checkReactivationActive for reactiveActive
I/SA      ( 7053): setSupportRL : true
,I/SA      ( 7053): [SCU] isHaveSA() - false
I/SA      ( 7053): support phone number id : false
,I/SA      ( 7053): [DM] init END
I/SA      ( 7053): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 7053): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7053): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7053): [SLFUCHKMGR] constructor called
,I/SA      ( 7053): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7053): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7053): [SCU] == networkStateCheck == true
,I/SA      ( 7053): [DM] getCountryCodeFromCSC : PL
I/SA      ( 7053): isChinaCountryCode : false
I/SA      ( 7053): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7053): [OR] == networkStateCheck true ==
,I/SA      ( 7053): [OR] GetMyCountryZoneTask
,I/SA      ( 7053): [OR] onReceive END
,I/ActivityManager(  738): Killing 6095:com.sec.android.app.soundalive/u0a64 (adj 13): bgCount ##41
,I/SA      ( 7053): [SRS] prepareGetMyCountryZone
,I/SA      ( 7053): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7053): [SSP] query invoked
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7053): [TPMU] GetMccFromDB : null
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7053): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7053): [TPM] isNoProxy(default) : true
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,E/File    ( 7053): fail readDirectory() errno=2
,E/Zygote  ( 7076): MountEmulatedStorage()
,E/Zygote  ( 7076): v2
I/libpersona( 7076): KNOX_SDCARD checking this for 10074
I/libpersona( 7076): KNOX_SDCARD not a persona
,I/ActivityManager(  738): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7076 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7076): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7076): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7076): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/btif_config_util( 6604): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/TimaKeyStoreProvider( 7076): TimaSignature is unavailable
,D/ActivityThread( 7076): Added TimaKeyStore provider
,D/ResourcesManager( 7076): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp( 7076): sCloudBackupApp Version Info : 3.13.7.KK_APP
I/SCloudBackupReceiver( 7076): Other Intent
,I/KnoxUsageLogPro( 6394): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 6394): premStatus:2
,I/KnoxUsageLogPro( 6394): isEulaShown : false
,I/KnoxUsageLogPro( 6394): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7092): MountEmulatedStorage()
,E/Zygote  ( 7092): v2
I/libpersona( 7092): KNOX_SDCARD checking this for 10146
I/libpersona( 7092): KNOX_SDCARD not a persona
,E/WifiStateMachine(  738): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SELinux ( 7092): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7092): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,I/ActivityManager(  738): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7092 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 7092): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  738): Killing 4970:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##41
,D/TimaKeyStoreProvider( 7092): TimaSignature is unavailable
D/ActivityThread( 7092): Added TimaKeyStore provider
,D/ResourcesManager( 7092): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7092): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7092): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7092): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7092): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  254): id=13 Removed Uoast (8/9)
,I/SurfaceFlinger(  254): id=13 Removed Uoast (-2/9)
,D/PowerManagerService(  738): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 738) eventTime = 169306
D/PowerManagerService(  738): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=738 (0x0)
D/PowerManagerService(  738): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=738, ws=WorkSource{10067}) (elapsedTime=3477)
,D/OpenGLRenderer( 3161): Render dirty regions requested: true
,D/Atlas   ( 3161): Validating map...
,I/WebViewFactory( 7092): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 7092): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/SurfaceFlinger(  254): id=14 createSurf (1x1),1 flag=4, Uoast
,I/LibraryLoader( 7092): Loading: webviewchromium
,D/PowerManagerService(  738): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=738
,I/LibraryLoader( 7092): Time to load native libraries: 6 ms (timestamps 9346-9352)
,I/LibraryLoader( 7092): Expected native library version number "",actual native library version number ""
,I/Adreno-EGL( 3161): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 3161): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 3161): Build Date: 11/19/14 Wed
I/Adreno-EGL( 3161): Local Branch: mybranch5813579
I/Adreno-EGL( 3161): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 3161): Local Patches: NONE
I/Adreno-EGL( 3161): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,I/OpenGLRenderer( 3161): Initialized EGL, version 1.4
,V/WebViewChromiumFactoryProvider( 7092): Binding Chromium to main looper Looper (main, tid 1) {20c8f5a9}
,I/LibraryLoader( 7092): Expected native library version number "",actual native library version number ""
,I/chromium( 7092): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7092): Initializing chromium process, renderers=0
,W/art     ( 7092): Attempt to remove local handle scope entry from IRT, ignoring
,I/OpenGLRenderer( 3161): HWUI protection enabled for context ,  &this =0xa1c22088 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 3161): Enabling debug mode 0
,W/chromium( 7092): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7092): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46780 len=2953
,I/chromium( 7092): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229536 len:643667
,W/AudioManagerAndroid( 7092): Requires BLUETOOTH permission
,I/Adreno-EGL( 7092): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7092): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7092): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7092): Local Branch: mybranch5813579
I/Adreno-EGL( 7092): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7092): Local Patches: NONE
I/Adreno-EGL( 7092): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,I/SA      ( 7053): [RC New] Execute method=[GET] start
,I/SA      ( 7053): [RC New] Security=[true]
,I/System.out( 7053): Thread-1145(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7053): Thread-1145(ApacheHTTPLog):isShipBuild true
,I/System.out( 7053): Thread-1145(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/NSApplication( 7092): Starting up...
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7150): MountEmulatedStorage()
I/libpersona( 7150): KNOX_SDCARD checking this for 10158
E/Zygote  ( 7150): v2
I/libpersona( 7150): KNOX_SDCARD not a persona
,I/ActivityManager(  738): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7150 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7150): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  738): Killing 6133:com.wsomacp/u0a29 (adj 13): bgCount ##41
,I/SELinux ( 7150): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7150): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7150): TimaSignature is unavailable
,D/ActivityThread( 7150): Added TimaKeyStore provider
,D/ResourcesManager( 7150): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7150): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7150): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7150): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7150): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7150): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7150): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  738): exchangeData() failure , invalid userId
,D/RCPManagerService(  738): exchangeData() failure , invalid userId
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6576): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6576): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6576): StateMachine : Current State = 1
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 6576): StateMachine : Changed Current State = 1
,I/ActivityManager(  738): Killing 6118:com.google.android.apps.docs/u0a112 (adj 13): bgCount ##41
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  738): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7165): MountEmulatedStorage()
E/Zygote  ( 7165): v2
,I/libpersona( 7165): KNOX_SDCARD checking this for 10200
I/libpersona( 7165): KNOX_SDCARD not a persona
,I/ActivityManager(  738): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7165 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7165): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7165): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7165): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/art     (  350): Explicit concurrent mark sweep GC freed 8723(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 506us total 21.933ms
,D/TimaKeyStoreProvider( 7165): TimaSignature is unavailable
,D/ActivityThread( 7165): Added TimaKeyStore provider
,I/art     (  350): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 310us total 12.562ms
,D/ResourcesManager( 7165): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/art     (  350): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 303us total 11.136ms
,I/iu.SyncManager( 1743): SYNC; picasa accounts
,D/NetworkLogImpl( 1743): Loaded NetworkSpeedPredictor
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/iu.Environment( 1743): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1743): num queued entries: 0
,I/iu.UploadsManager( 1743): num updated entries: 0
,I/iu.SyncManager( 1743): NEXT; no task
D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  738): Killing 6174:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 6292): notifyNetworkActivated
,W/ContextImpl( 6292): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  738): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 1401): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/GCM     ( 1401): GCM config loaded
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 6292): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6292): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6292): exit::IDLE
D/InitializeManagerStateMachine( 6292): entry::NETWORK_CHECK
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 6292): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 6292): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6292): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6292): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 6292): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6292): entry::SUCCESS
D/hcjo    ( 6292): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6292): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 6292): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6292): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 6292): exit::SUCCESS
D/InitializeManagerStateMachine( 6292): entry::IDLE
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7053): [RC New] [v2liruge] api execute + 696
I/SA      ( 7053): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 7053): AsyncTask #1 calls detatch()
,I/SA      ( 7053): [TPMU] getNetworkMcc : 
,I/SA      ( 7053): [SCU] saveMccToPreferece Start
I/SA      ( 7053): [SCU] RegionMCC : 260
I/SA      ( 7053): [SSP] query invoked
,I/SA      ( 7053): [TPMU] GetMccFromDB : null
,I/SA      ( 7053): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7053): [SCU] saveMccToPreferece End
I/SA      ( 7053): [RC New] executeRequest [v2liruge] end. 747
,I/SA      ( 7053): [RC New] Execute end
I/SA      ( 7053): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7053): [OR] GetMyCountryZoneTask Success
,E/SMD     (  296): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  738): stay LED for fully charged
,I/MotionRecognitionService(  738): Plugged,
I/MotionRecognitionService(  738): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/HeadsetService( 6604): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6604): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5952): mConnectivityHandler : connected
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 5952): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 5952): ================================================
,I/CSTORAGE( 5952):  CSTORAGE_SKM_LIB v1.0.6
,I/CSTORAGE( 5952): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5952): [GetString-S]
,E/art     ( 5952): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 5952): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5952): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5952): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5952): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5952): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5952): [ensureRegistration] - No Samsung account
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/dhcpcd  ( 6774): wlan0: sending IPv6 Router Solicitation
,I/SurfaceFlinger(  254): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  254): id=14 Removed Uoast (-2/9)
,D/PowerManagerService(  738): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 738) eventTime = 172832
,D/PowerManagerService(  738): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=738 (0x0)
,D/PowerManagerService(  738): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=738, ws=WorkSource{1000}) (elapsedTime=3486)
,E/SMD     (  296): DCD ON
,I/GAV4    ( 7092): Thread[GAThread,5,main]: No campaign data found.
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  738): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7210 uid=10051 gids={50051, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 7210): MountEmulatedStorage()
,E/Zygote  ( 7210): v2
I/libpersona( 7210): KNOX_SDCARD checking this for 10051
I/libpersona( 7210): KNOX_SDCARD not a persona
,I/SELinux ( 7210): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7210): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7210): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7210): TimaSignature is unavailable
,D/ActivityThread( 7210): Added TimaKeyStore provider
,D/ResourcesManager( 7210): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager( 7210): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 7210): CalendarProvider2.onCreate() called
,E/SMD     (  296): DCD ON
,I/dhcpcd  ( 6774): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 6774): wlan0: no IPv6 Routers available
,I/CalendarProvider2( 7210): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  738): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7236 uid=10171 gids={50171, 9997} abi=armeabi-v7a
,E/Zygote  ( 7236): MountEmulatedStorage()
,E/Zygote  ( 7236): v2
I/libpersona( 7236): KNOX_SDCARD checking this for 10171
I/libpersona( 7236): KNOX_SDCARD not a persona
,I/ActivityManager(  738): Killing 6199:com.samsung.android.app.watchmanagerstub/u0a126 (adj 13): bgCount ##41
,I/SELinux ( 7236): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7236): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7236): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7236): TimaSignature is unavailable
,D/ActivityThread( 7236): Added TimaKeyStore provider
,D/ResourcesManager( 7236): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 7236): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7236): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7266): MountEmulatedStorage()
,E/Zygote  ( 7266): v2
I/libpersona( 7266): KNOX_SDCARD checking this for 10172
I/libpersona( 7266): KNOX_SDCARD not a persona
,I/SELinux ( 7266): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7266): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7266): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  738): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7266 uid=10172 gids={50172, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager(  738): Killing 6214:com.samsung.helphub/1000 (adj 13): bgCount ##41
,D/TimaKeyStoreProvider( 7266): TimaSignature is unavailable
,D/ActivityThread( 7266): Added TimaKeyStore provider
,D/ResourcesManager( 7266): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,W/ResourcesManager( 7266): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7266): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7266): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/SSRM:n  (  738): SIOP:: AP = 340, PST = 332, CUR = 450
,I/ActivityManager(  738): Killing 6249:com.samsung.android.snote:provider/u0a168 (adj 13): bgCount ##41
,E/SMD     (  296): DCD ON,
,D/PreloadUpdateManagerStateMachine( 6292): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6292): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6292): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6292): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 6292): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6292): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6292): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6292): entry::IDLE
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  296): DCD ON
,V/AlarmManager(  738): waitForAlarm result :8
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,D/SSRM:n  (  738): SIOP:: AP = 320, PST = 327, CUR = 450
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,W/Atfwd_Sendcmd(  370): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  296): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD ON
,E/Watchdog(  738): !@Sync 6
,I/PowerManagerService(  738): [PWL] Off : 140s ago
,V/AlarmManager(  738): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 320, PST = 325, CUR = 450
,E/SMD     (  296): DCD ON
,V/AlarmManager(  738): waitForAlarm result :4
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6604): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6604): Disconnected process message: 10
,D/SSRM:n  (  738): SIOP:: AP = 310, PST = 323, CUR = 450
,E/SMD     (  296): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD ON
,I/Atfwd_Sendcmd(  370): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  370): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  296): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6604): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6604): Disconnected process message: 10
,D/BatteryService(  738): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/SSRM:n  (  738): SIOP:: AP = 310, PST = 322, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,E/Watchdog(  738): !@Sync 7
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,V/AlarmManager(  738): waitForAlarm result :4
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  296): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): stay LED for fully charged
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  738): Plugged
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6604): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6604): Disconnected process message: 10
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityThread( 1743): Failed to find provider info for com.android.contacts.metadata
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  738): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, SERVER, currentRunTime 197254, reason: ServiceChanged, SyncResult: databaseError: true stats []
,D/SyncManager(  738): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, SERVER, currentRunTime 287977, reason: ServiceChanged
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:n  (  738): SIOP:: AP = 310, PST = 321, CUR = 450
,D/SecContentProvider2(  738): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  738): mCursor = null
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  370): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  296): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  296): DCD ON
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,I/PowerManagerService(  738): [PWL] Off : 180s ago
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  738): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  738): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6604): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6604): Disconnected process message: 10
,D/SSRM:n  (  738): SIOP:: AP = 310, PST = 321, CUR = 450
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  370): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,V/AlarmManager(  738): waitForAlarm result :8
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 320, CUR = 450
,E/SMD     (  296): DCD ON
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD ON
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  370): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  296): DCD ON
,E/Watchdog(  738): !@Sync 8
,E/SMD     (  296): DCD ON
,V/AlarmManager(  738): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/ConnectivityService(  738): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 319, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  738): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  738): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6604): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6604): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 312, CUR = 450
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  370): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  296): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  738): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  738): setPowerConnected  = true
,D/BatteryService(  738): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6604): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6604): Disconnected process message: 10
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 308, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,I/PowerManagerService(  738): [PWL] Off : 225s ago
,E/SMD     (  296): DCD ON
,E/Watchdog(  738): !@Sync 9
,E/SMD     (  296): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 306, CUR = 450
,E/SMD     (  296): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD ON
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,E/SMD     (  296): DCD ON
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  738): Plugged
I/MotionRecognitionService(  738): setPowerConnected  = true
,I/ServiceManager(  370): Waiting for service AtCmdFwd...
,D/BatteryService(  738): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6604): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6604): Disconnected process message: 10
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 304, CUR = 450
,W/Atfwd_Sendcmd(  370): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,V/AlarmManager(  738): waitForAlarm result :8
,E/SMD     (  296): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  738): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  738): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  738): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  738): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  738): setPowerConnected  = true
D/BatteryService(  738): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6604): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6604): Disconnected process message: 10
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 303, CUR = 450
,E/SMD     (  296): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  296): DCD ON
,D/TimaService(  738): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  738): TimaServiceHandler.handleMessage what =1
,D/TimaService(  738): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  738): initializing...
,I/TLC_TIMA_PKM_initialize(  738): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  738): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  738): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  738): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  738): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  738): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  738): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  738): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  738): App is not loaded in QSEE
,D/QSEECOMAPI: (  738): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  738): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  738): Trustlet response is completed
,E/SMD     (  296): DCD ON
,E/Watchdog(  738): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  738): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  738): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  738): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  738): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  296): DCD ON
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 302, CUR = 450
,E/SMD     (  296): DCD ON
,E/SMD     (  296): DCD ON
,I/Atfwd_Sendcmd(  370): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  370): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  296): DCD ON
,D/SSRM:n  (  738): SIOP:: AP = 300, PST = 301, CUR = 450
,E/SMD     (  296): DCD ON
,W/ContextImpl(  738): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  738): [PWL] Off : 275s ago
,V/AlarmManager(  738): waitForAlarm result :4
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  738): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  738): !@BatteryListener : batteryPropertiesChanged!
,I/ActivityManager(  738): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7337 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 7337): MountEmulatedStorage()
,E/Zygote  ( 7337): v2
I/libpersona( 7337): KNOX_SDCARD checking this for 10096
I/libpersona( 7337): KNOX_SDCARD not a persona
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,I/SELinux ( 7337): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7337): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7337): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 7337): TimaSignature is unavailable
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityThread( 7337): Added TimaKeyStore provider
,D/ResourcesManager( 7337): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,E/SMD     (  296): DCD ON
,I/ActivityManager(  738): Killing 6266:com.sec.kidsplat.installer/u0a189 (adj 13): bgCount ##41
,E/SMD     (  296): DCD ON

```
