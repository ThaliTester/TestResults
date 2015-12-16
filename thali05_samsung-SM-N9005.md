#### Test 50650278dbf8a2a_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
,E/SMD     (  288): DCD ON
I/ServiceManager(  326): Waiting for service AtCmdFwd...
D/AndroidRuntime( 6439): 
D/AndroidRuntime( 6439): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6439): CheckJNI is OFF
D/AndroidRuntime( 6439): readGMSProperty: start
D/AndroidRuntime( 6439): readGMSProperty: already setted!!
D/AndroidRuntime( 6439): readGMSProperty: end
D/AndroidRuntime( 6439): addProductProperty: start
E/AffinityControl( 6439): AffinityControl: registerfunction enter
D/AndroidRuntime( 6439): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  772): inState():  stateMachine is null !!
I/PersonaManagerService(  772): PersonaId don't exist
I/ActivityManager(  772): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  772): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
I/ActivityManager(  772): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  772): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  772): mDVFSHelper.acquire()
D/FocusedStackFrame(  772): Set to : 0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  772): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6454 uid=10293 gids={50293, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6454): MountEmulatedStorage()
E/Zygote  ( 6454): v2
I/libpersona( 6454): KNOX_SDCARD checking this for 10293
D/PointerIcon(  772): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  772): setMouseCustomIcon IconType is same.101
D/PointerIcon(  772): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  772): setHoveringSpenCustomIcon IconType is same.1
I/libpersona( 6454): KNOX_SDCARD not a persona
D/AndroidRuntime( 6439): Shutting down VM
I/SELinux ( 6454): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6454): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6454): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6454): TimaSignature is unavailable
D/ActivityThread( 6454): Added TimaKeyStore provider
V/WindowOrientationListener(  772): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  772): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  772): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  772): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  772): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  772): Display changed displayId=0
D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SurfaceWidgetView( 1437): destroyHardwareResources():1072236003
D/ResourcesManager( 6454): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger(  254): id=6 Removed Mauncher (6/8)
I/SurfaceFlinger(  254): id=6 Removed Mauncher (-2/8)
V/ActivityThread( 1437): updateVisibility : ActivityRecord{1da88548 token=android.os.BinderProxy@3bd63dd {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1437): onTrimMemory. Level: 20
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1741): [237392/8] Surface widget visibility changed visibility = false on instance = 1
,I/WebViewFactory( 6454): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 6454): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 6454): Loading: webviewchromium
I/LibraryLoader( 6454): Time to load native libraries: 6 ms (timestamps 9151-9157)
I/LibraryLoader( 6454): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6454): Binding Chromium to main looper Looper (main, tid 1) {b25a7e5}
,I/LibraryLoader( 6454): Expected native library version number "",actual native library version number ""
,I/chromium( 6454): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6454): Initializing chromium process, renderers=0
,W/art     ( 6454): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6454): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 6454): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6454): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
,I/chromium( 6454): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
,D/BluetoothAdapter( 6454): 944665274: getState() :  mService = null. Returning STATE_OFF
,I/Adreno-EGL( 6454): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6454): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6454): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6454): Local Branch: mybranch5813579
I/Adreno-EGL( 6454): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6454): Local Patches: NONE
I/Adreno-EGL( 6454): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,W/chromium( 6454): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6454): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 6454): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  772): Activity pause timeout for ActivityRecord{3e1a00a2 u0 com.test.thalitest/.MainActivity t3}
,W/AwContents( 6454): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6454): CordovaWebView is running on device made by: samsung
,W/art     ( 6454): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6454): Attempt to remove local handle scope entry from IRT, ignoring
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/Activity( 6454): performCreate Call secproduct feature valuefalse
D/Activity( 6454): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 6454): Render dirty regions requested: true
,D/Atlas   ( 6454): Validating map...
,D/ActivityManager(  772): post active user change for 0
D/KnoxTimeoutHandler(  772): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  772): handleActiveUserChange for user 0
,V/ActivityThread( 6454): updateVisibility : ActivityRecord{3cd4cf5b token=android.os.BinderProxy@27a95455 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,V/AlarmManager(  772): waitForAlarm result :4
,D/NtpTrustedTime(  772): forceRefresh() from cache miss
,D/NtpTrustedTime(  772): forceRefresh Fail.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,I/SurfaceFlinger(  254): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService(  772): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  772): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): stay LED for fully charged
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/PointerIcon(  772): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  772): setMouseCustomIcon IconType is same.101
D/PointerIcon(  772): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  772): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 6454): Initialized EGL, version 1.4
,I/OpenGLRenderer( 6454): HWUI protection enabled for context ,  &this =0xafc76038 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 6454): Enabling debug mode 0
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/InputMethodManagerService(  772): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SamsungIME( 1697): getCurrentCandidateView
,W/ActivityManager(  772): mDVFSHelper.release()
,I/Timeline(  772): Timeline: Activity_windows_visible id: ActivityRecord{3e1a00a2 u0 com.test.thalitest/.MainActivity t3} time:159682
,W/IInputConnectionWrapper( 6454): showStatusIcon on inactive InputConnection
,I/Timeline( 6454): Timeline: Activity_idle id: android.os.BinderProxy@27a95455 time:159685
,D/SamsungIME( 1697): Dismiss ExpandCandiate
,I/SamsungIME( 1697): getDebugLevel  : 0x4f4c
,I/PowerManagerService(  772): [PWL] Off : 50s ago
,I/chromium( 6454): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6454): 
,I/SamsungIME( 1697): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1697): KeybaordView init() : load resources
,I/SamsungIME( 1697): getCurrentKeyboard
I/SamsungIME( 1697): getTextKeyboard
,D/JsMessageQueue( 6454): Set native->JS mode to OnlineEventsBridgeMode
,D/SamsungIME( 1697): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/jxcore_app_log( 6454): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258378624
,D/JX-Cordova( 6454): jxcore cordova android initializing
,D/SSRM:n  (  772): SIOP:: AP = 310, PST = 318, CUR = 450
,D/SamsungIME( 1697): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,W/jxcore-log( 6454): Initializing JXcore engine
,W/jxcore-log( 6454): JXcore engine is ready
,W/jxcore-log( 6454): Starting JXcore engine
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/auditd  ( 1782): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  772): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  772): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6541): MountEmulatedStorage()
I/libpersona( 6541): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6541): v2
I/libpersona( 6541): KNOX_SDCARD not a persona
I/ActivityManager(  772): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6541 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6541): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6541): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6541): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/jxcore-log( 6454): Platform android
W/jxcore-log( 6454): 
W/jxcore-log( 6454): Process ARCH arm
W/jxcore-log( 6454): 
,D/TimaKeyStoreProvider( 6541): TimaSignature is unavailable
,D/ActivityThread( 6541): Added TimaKeyStore provider
,D/ResourcesManager( 6541): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 6541):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6541):  SeDenialReceiver : File path = null
,I/ActivityManager(  772): Killing 5465:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,I/jxcore-log( 6454): JXcore Cordova bridge is ready!
I/jxcore-log( 6454): 
,W/jxcore-log( 6454): JXcore engine is started
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/jxcore-log( 6454): Toggling radios to true
I/jxcore-log( 6454): 
,D/BluetoothAdapter( 6454): enable()
,W/ActivityManager(  772): Permission Denial: getCurrentUser() from pid=6454, uid=10293 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService(  772): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService(  772): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6454, uid=10293 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService(  772): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/BluetoothManagerService(  772): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2141)
W/BluetoothManagerService(  772): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:671)
W/BluetoothManagerService(  772): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService(  772): 	at android.os.Binder.execTransact(Binder.java:446)
,E/DevicePolicyManagerService(  772): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService(  772): getAllowBluetoothMode - value retunrs : 2
,D/SettingsProvider(  772): name = bluetooth_on
,E/DevicePolicyManagerService(  772): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService(  772): getAllowBluetoothMode - value retunrs : 2
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,I/WifiManager( 6454): packageName : com.test.thalitest
,D/SecContentProvider(  772): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  772): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  772): mCursor = null
,D/WifiService(  772): setWifiEnabled: true pid=6454, uid=10293
,W/ActivityManager(  772): Permission Denial: getCurrentUser() from pid=6454, uid=10293 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  772): Failed getting userId using ActivityManagerNative
W/WifiService(  772): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6454, uid=10293 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  772): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/WifiService(  772): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2181)
W/WifiService(  772): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2169)
W/WifiService(  772): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  772): 	at android.os.Binder.execTransact(Binder.java:446)
D/SettingsProvider(  772): name = wifi_on
,E/WifiHW  (  772): ##################### set firmware type 0 #####################
,I/WifiHW  (  282): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
I/WifiHW  (  282): module is semco
E/WifiHW  (  282): ==========[WIFI] SEMCO MODULE ===========
I/WifiHW  (  282): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
E/WifiHW  (  282): TEMP_FAILURE_RETRY complete
D/SoftapController(  282): Softap fwReload - Ok
,D/CommandListener(  282): Setting iface cfg
D/CommandListener(  282): Trying to bring down wlan0
,D/CommandListener(  282): Clearing all IP addresses on wlan0
,I/WifiService(  772): disconnect: pid=6454, uid=10293
,I/jxcore-log( 6454): Radios toggled
I/jxcore-log( 6454): 
,E/WifiHW  (  772): supplicant_name : p2p_supplicant
,E/Zygote  ( 6576): MountEmulatedStorage()
,E/Zygote  ( 6576): v2
I/libpersona( 6576): KNOX_SDCARD checking this for 1002
I/libpersona( 6576): KNOX_SDCARD not a persona
,I/ActivityManager(  772): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6576 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/jxcore-log( 6454): Got Device Bluetooth address: E0:DB:10:1F:C9:5E
I/jxcore-log( 6454): 
,D/SmartBondingService(  772): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
D/WifiMonitor(  772): startMonitoring(wlan0) with mConnected = false
,I/jxcore-log( 6454): Perf Test app loaded loaded
I/jxcore-log( 6454): 
,I/art     (  319): Explicit concurrent mark sweep GC freed 8744(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 305us total 27.352ms
,I/jxcore-log( 6454): check test folder
I/jxcore-log( 6454): 
,I/jxcore-log( 6454): found test : ./testFindPeers.js
I/jxcore-log( 6454): 
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 6.195ms total 15.511ms
,I/SELinux ( 6576): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/wpa_supplicant( 6575): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 6575): Successfully initialized wpa_supplicant
I/SELinux ( 6576): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6576): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/SecureStorage( 6575): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6575): [INFO]: SPID(0x00000000)This device supports Secure Storage
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=false enabledDesc:null
D/STATUSBAR-WifiQuickSettingButton( 1185): onReceive : android.net.wifi.WIFI_STATE_CHANGED
I/SecureStorage(  391): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6575
I/SecureStorage(  391): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,I/SecureStorage( 6575): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6575): ssSupport state is = 1
I/wpa_supplicant( 6575): >>>>> GET KEY, IV <<<<<
I/SecureStorage( 6575): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  391): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6575
I/SecureStorage(  391): [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 266us total 19.493ms
D/STATUSBAR-WifiQuickSettingButton( 1185): Wifi onReceive(2)
D/HotspotTile( 1185): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/SmartBondingService(  772): getNetworkEnabled : wifi : false mobile : true
,D/WifiCredService( 1309): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1185): onStateChanged: Wi-Fi
,D/HotspotTile( 1185): onReceive : 2, 0
,I/jxcore-log( 6454): found test : ./testSendData.js
I/jxcore-log( 6454): 
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4
,E/Zygote  ( 6583): MountEmulatedStorage()
,E/Zygote  ( 6583): v2
I/libpersona( 6583): KNOX_SDCARD checking this for 10152
I/libpersona( 6583): KNOX_SDCARD not a persona
,I/ActivityManager(  772): Start proc tv.peel.samsung.app for broadcast tv.peel.samsung.app/com.peel.receiver.ConnectivityActionReceiver: pid=6583 uid=10152 gids={50152, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 6583): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/TimaKeyStoreProvider( 6576): TimaSignature is unavailable
D/ActivityThread( 6576): Added TimaKeyStore provider
I/SELinux ( 6583): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6583): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 6576): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
W/ResourcesManager( 6576): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6576): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6583): TimaSignature is unavailable
D/ActivityThread( 6583): Added TimaKeyStore provider
,I/chromium( 6454): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/ResourcesManager( 6583): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,I/BluetoothA2dpSinkServiceJni( 6576): register_com_android_bluetooth_a2dp_sink
,I/chromium( 6454): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/BtSettings.ProfileConfig( 6576): Adding GattService
,D/BtSettings.ProfileConfig( 6576): Adding HeadsetService
D/BtSettings.ProfileConfig( 6576): Adding A2dpService
,D/BtSettings.ProfileConfig( 6576): Adding HidService
D/BtSettings.ProfileConfig( 6576): Adding HealthService
,D/BtSettings.ProfileConfig( 6576): Adding PanService
D/BtSettings.ProfileConfig( 6576): Adding BluetoothMapService
D/BtSettings.ProfileConfig( 6576): Adding SapService
,D/BtSettings.ProfileConfig( 6576): Adding HeadsetClientService
D/BtSettings.ProfileConfig( 6576): Adding A2dpSinkService
D/BtSettings.ProfileConfig( 6576): Adding SapClientService
,D/BtSettings.ProfileConfig( 6576): Adding HidDevService
I/BtSettings.ProfileConfig( 6576): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider(  772): name = bt_svcst_com.android.bluetooth.gatt.GattService
,D/SettingsProvider(  772): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  772): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  772): selectionArgs: false
D/SettingsProvider(  772): selectionArgs: 1002
D/SecContentProvider(  772): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  772): ret = -1
,W/BackupManagerService(  772): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  772): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider(  772): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  772): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  772): selectionArgs: false
D/SettingsProvider(  772): selectionArgs: 1002
D/SecContentProvider(  772): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  772): ret = -1
,W/BackupManagerService(  772): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  772): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,D/SettingsProvider(  772): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  772): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  772): selectionArgs: false
D/SettingsProvider(  772): selectionArgs: 1002
D/SecContentProvider(  772): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  772): ret = -1
,W/BackupManagerService(  772): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  772): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider(  772): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  772): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  772): selectionArgs: false
D/SettingsProvider(  772): selectionArgs: 1002
D/SecContentProvider(  772): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  772): ret = -1
,W/BackupManagerService(  772): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  772): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider(  772): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  772): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  772): selectionArgs: false
D/SettingsProvider(  772): selectionArgs: 1002
D/SecContentProvider(  772): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  772): ret = -1
,W/BackupManagerService(  772): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  772): name = bt_svcst_com.android.bluetooth.pan.PanService
,D/SettingsProvider(  772): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  772): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  772): selectionArgs: false
D/SettingsProvider(  772): selectionArgs: 1002
D/SecContentProvider(  772): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  772): ret = -1
,W/BackupManagerService(  772): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  772): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider(  772): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  772): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  772): selectionArgs: false
D/SettingsProvider(  772): selectionArgs: 1002
D/SecContentProvider(  772): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  772): ret = -1
,W/BackupManagerService(  772): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  772): name = bt_svcst_com.broadcom.bt.service.sap.SapService
,D/SettingsProvider(  772): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  772): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  772): selectionArgs: false
D/SettingsProvider(  772): selectionArgs: 1002
D/SecContentProvider(  772): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  772): ret = -1
,W/BackupManagerService(  772): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  772): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,D/SettingsProvider(  772): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  772): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  772): selectionArgs: false
D/SettingsProvider(  772): selectionArgs: 1002
D/SecContentProvider(  772): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  772): ret = -1
,W/BackupManagerService(  772): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  772): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,D/SettingsProvider(  772): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  772): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  772): selectionArgs: false
D/SettingsProvider(  772): selectionArgs: 1002
D/SecContentProvider(  772): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  772): ret = -1
,W/BackupManagerService(  772): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  772): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider(  772): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  772): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  772): selectionArgs: false
D/SettingsProvider(  772): selectionArgs: 1002
D/SecContentProvider(  772): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  772): ret = -1
,W/BackupManagerService(  772): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  772): name = bt_svcst_com.android.bluetooth.hid.HidDevService
,D/SettingsProvider(  772): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  772): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  772): selectionArgs: false
D/SettingsProvider(  772): selectionArgs: 1002
D/SecContentProvider(  772): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  772): ret = -1
,W/BackupManagerService(  772): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/WebViewFactory( 6583): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 6583): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 6583): Loading: webviewchromium
,I/SecureStorage(  391): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,D/BluetoothAdapterState( 6576): make
,I/LibraryLoader( 6583): Time to load native libraries: 16 ms (timestamps 3753-3769)
,I/LibraryLoader( 6583): Expected native library version number "",actual native library version number ""
,I/bluedroid( 6576): init
I/BluetoothAdapterState( 6576): Entering OffState
,I/bte_conf( 6576): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 6576): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6576): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6576): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif ( 6576): btif_fetch_local_ble_random_bdaddr
,I/bluedroid( 6576): get_profile_interface socket
I/bluedroid( 6576): get_profile_interface map_client
I/GKI_LINUX( 6576): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterService( 6576): checkAddrForIOP: Loading from conf
,D/BluetoothAdapterProperties( 6576): Address is:E0:DB:10:1F:C9:5E
E/BluetoothServiceJni( 6576): populateRssiValuesNative
I/bluedroid( 6576): getModelRssiValues
E/BluetoothServiceJni( 6576): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 6576): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothAdapterProperties( 6576): Name is: Note3-1
,D/SettingsProvider(  772): name = bluetooth_name
,I/bluedroid( 6576): config_hci_snoop_log
,D/BluetoothManagerService(  772): Broadcasting onBluetoothServiceUp() to 10 receivers.
,E/DevicePolicyManagerService(  772): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService(  772): getAllowBluetoothMode - value retunrs : 2
,V/WebViewChromiumFactoryProvider( 6583): Binding Chromium to main looper Looper (main, tid 1) {1637b56b}
,D/SecContentProvider(  772): uri = 3 selection = isBluetoothEnabled
,I/LibraryLoader( 6583): Expected native library version number "",actual native library version number ""
,I/chromium( 6583): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,D/BluetoothAdapterState( 6576): CURRENT_STATE=OFF, MSG = USER_TURN_ON
D/BluetoothAdapterProperties( 6576): Setting state to 11
I/BluetoothAdapterState( 6576): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 6576): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 6576): updateAdapterState state is 11
,D/BluetoothAdapterService( 6576): Autoconnection is available 
D/BluetoothAdapterService( 6576): updateAdapterState prevState = 10newState = 11
,W/InputMethodManagerService(  772): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  772): [BT Setting State] State =11
,D/BluetoothSecureManager( 6576): getInstant: null
,D/BluetoothSecureManager( 6576): calling getMethod for getService
D/BluetoothSecureManager( 6576): calling getService
,I/SamsungIME( 1697): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothSecureManager( 6576): getService return binder: android.os.BinderProxy@15bc9f12
D/BluetoothSecureManagerService(  772): isSecureModeEnabled
D/BluetoothSecureManagerService(  772): getSecureModeSetting, name: secure_mode_enable
D/BtConfig.SecureMode( 6576): isSecureModeOn:false
D/BtSettings.ProfileConfig( 6576): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 6576): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 6576): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 6576): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 6576): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,D/BluetoothTile( 1185):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1185): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
W/BluetoothAdapterService( 6576): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 6576): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 6576): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 6576): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 6576): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 6576): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 6576): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 6576): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/StatusBarManagerService(  772): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
W/BluetoothAdapterService( 6576): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 6576): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/StatusBarManagerService(  772): setIconVisibility slot=bluetooth visible=false
W/BluetoothAdapterService( 6576): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 6576): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,D/PhoneStatusBar( 1185): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 )
W/BluetoothAdapterService( 6576): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 6576): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6576): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 6576): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
D/STATUSBAR-QSTileView( 1185): onStateChanged: Bluetooth
W/BluetoothAdapterService( 6576): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 6576): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 6576): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,D/BluetoothBondStateMachine( 6576): make
,I/BluetoothBondStateMachine( 6576): StableState(): Entering Off State
W/BluetoothAdapterService( 6576): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 6576): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 6576): Not skipping com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 6576): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 6576): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 6576): Not skipping com.android.bluetooth.hfp.HeadsetService
,I/BtGatt.JNI( 6576): classInitNative(L890): classInitNative: Success!
,I/BrowserStartupController( 6583): Initializing chromium process, renderers=0
W/art     ( 6583): Attempt to remove local handle scope entry from IRT, ignoring
,W/BluetoothAdapterService( 6576): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 6576): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 6576): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 6576): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 6576): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 6576): Not skipping com.android.bluetooth.hid.HidService
,D/BtGatt.DebugUtils( 6576): handleDebugAction() action=null
,D/BtGatt.GattService( 6576): Received start request. Starting profile...
D/BtGatt.GattService( 6576): start()
I/bluedroid( 6576): get_profile_interface gatt
W/BluetoothAdapterService( 6576): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 6576): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 6576): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@384e72ba
D/BtGatt.AdvertiseManager( 6576): advertise manager created
,W/BluetoothAdapterService( 6576): Not skipping com.android.bluetooth.hdp.HealthService
W/chromium( 6583): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/BluetoothAdapterService( 6576): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 6576): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 6576): Not skipping com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 6576): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 6576): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 6576): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/chromium( 6583): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6583): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=36 off=46780 len=2953
,W/BluetoothAdapterService( 6576): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 6576): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 6576): Not skipping com.broadcom.bt.service.sap.SapService
I/chromium( 6583): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:37 off:229536 len:643667
,W/BluetoothAdapterService( 6576): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 6576): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6576): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6576): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 6576): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6576): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6576): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 6576): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6576): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6576): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 6576): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 6576): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState( 6576): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAdapterService( 6576): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@384e72ba
,D/HeadsetService( 6576): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 6576): classInitNative: succeeds
,D/HeadsetStateMachine( 6576): make
,E/HeadsetStateMachine( 6576): # of Max HF connection is 2
,I/Adreno-EGL( 6583): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6583): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6583): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6583): Local Branch: mybranch5813579
I/Adreno-EGL( 6583): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6583): Local Patches: NONE
I/Adreno-EGL( 6583): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,I/bluedroid( 6576): get_profile_interface handsfree
,I/DualScoManager( 6576): Instantiating Dual Sco Manager
I/DualScoManager( 6576): Set HeadsetServiceHelper
,D/BluetoothAtMessage( 6576): createCMTIContentObservers
,D/SettingsProvider(  772): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider(  772): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  772): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  772): selectionArgs: false
D/SettingsProvider(  772): selectionArgs: 1002
D/SecContentProvider(  772): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  772): ret = -1
,W/BackupManagerService(  772): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine( 6576): Enter Disconnected: -2
,E/HeadsetStateMachine( 6576): set to mRemoteBrsf = 0
D/BluetoothAdapterService( 6576): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@384e72ba
,D/HeadsetStateMachine( 6576): map size, before remove : 0
D/HeadsetStateMachine( 6576): map size, after remove: 0
D/HeadsetStateMachine( 6576): mNextConnectingDevice : null
,D/BluetoothA2dp(  772): Proxy object connected
D/BluetoothA2dp( 2941): Proxy object connected
,D/A2dpService( 6576): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 6576): classInitNative: succeeds
,V/Avrcp   ( 6576): make
,V/Avrcp   ( 6576): Avrcp
I/bluedroid( 6576): get_profile_interface avrcp
,V/Avrcp   ( 6576): start
,E/RemoteController( 6576): Cannot set synchronization mode on an unregistered RemoteController
,V/Avrcp   ( 6576): ++registerMediaPlayers++
,I/Avrcp   ( 6576): No of Audio players :: 2
I/Avrcp   ( 6576): App Package name is com.google.android.music
,D/ResourcesManager( 6576): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/Avrcp   ( 6576): App pkg name is Google Play Music
,I/Avrcp   ( 6576): Name::Google Play Music
V/Avrcp   ( 6576): MediaPlayerInfo: mPlayerId=1
I/Avrcp   ( 6576): App Package name is com.sec.android.app.music
,D/ResourcesManager( 6576): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/Avrcp   ( 6576): App pkg name is Music
,I/Avrcp   ( 6576): Name::Music
V/Avrcp   ( 6576): MediaPlayerInfo: mPlayerId=2
I/Avrcp   ( 6576):  set player publishabilty with player id::2 toBePublished ::true
,I/Avrcp   ( 6576): No of Video players :: 1
I/Avrcp   ( 6576): Video App Package name is com.sec.android.app.videoplayer
,D/ResourcesManager( 6576): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/Avrcp   ( 6576): Video App pkg name is Video Player
,I/Avrcp   ( 6576): Name::Video Player
V/Avrcp   ( 6576): MediaPlayerInfo: mPlayerId=3
I/Avrcp   ( 6576): Add tempPlayer
V/Avrcp   ( 6576): MediaPlayerInfo: mPlayerId=4
I/Avrcp   ( 6576): Total no of players: 4
V/Avrcp   ( 6576): swapping the samsung player with 1st player
I/Avrcp   ( 6576):  Updating now playing list upon AVRCP Start
,V/Avrcp   ( 6576): handleMessage, msg=207
D/BluetoothMediaBrowser( 6576):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,I/BluetoothA2dpServiceJni( 6576): classInitNative: succeeds
D/A2dpStateMachine( 6576): make
,I/bluedroid( 6576): get_profile_interface a2dp
,I/GKI_LINUX( 6576): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 6576): warning : media task started media_task_refcnt 1 
,D/BluetoothAdapterService( 6576): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@384e72ba
,I/BluetoothHidServiceJni( 6576): classInitNative: succeeds
,D/A2dpStateMachine( 6576): Enter Disconnected: -2
,D/BluetoothMediaBrowser( 6576): no now playing list
D/BluetoothMediaBrowser( 6576):  getNowPlayingId now playing id : -1
D/Avrcp   ( 6576):  checkNowPlayingList start
,D/HidService( 6576): Received start request. Starting profile...
I/bluedroid( 6576): get_profile_interface hidhost
D/HidService( 6576): setHidService(): set to: null
,D/BluetoothAdapterService( 6576): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@384e72ba
,I/BluetoothHealthServiceJni( 6576): classInitNative: succeeds
,D/HealthService( 6576): Received start request. Starting profile...
,I/bluedroid( 6576): get_profile_interface health
,D/BluetoothAdapterService( 6576): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@384e72ba
I/BluetoothPanServiceJni( 6576): classInitNative(L105): succeeds
,D/BluetoothPan(  772): BluetoothPAN Proxy object connected
,D/PanService( 6576): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6576): initializeNative(L110): pan
I/bluedroid( 6576): get_profile_interface pan
,D/BluetoothAdapterService( 6576): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@384e72ba
,D/BluetoothMapService( 6576): Received start request. Starting profile...
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6650): MountEmulatedStorage()
,E/Zygote  ( 6650): v2
I/libpersona( 6650): KNOX_SDCARD checking this for 10186
I/libpersona( 6650): KNOX_SDCARD not a persona
,I/ActivityManager(  772): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=6650 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 6650): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6650): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6650): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SecureStorage( 6575): [INFO]: SPID(0x00000000)Processing data has been completed
,W/chromium( 6583): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,D/TimaKeyStoreProvider( 6650): TimaSignature is unavailable
,D/ActivityThread( 6650): Added TimaKeyStore provider
,W/chromium( 6583): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,I/SecureStorage( 6575): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6575): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  391): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6575
I/SecureStorage(  391): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
I/SecureStorage( 6575): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6575): ssSupport state is = 1
,I/wpa_supplicant( 6575): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6575): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6575): SIM READ ERROR
I/wpa_supplicant( 6575): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6575): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6575): SIM READ ERROR
I/wpa_supplicant( 6575): Blacklist: Clear (all) 
,I/wpa_supplicant( 6575): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6575): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant( 6575): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6575): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,I/wpa_supplicant( 6575): rfkill: Cannot open RFKILL control device
,D/ResourcesManager( 6650): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 6650): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6650): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6650): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6650): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6650): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/art     ( 6583): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6583): onDetachedFromWindow called when already detached. Ignoring
,D/RCPManagerService(  772): exchangeData() failure , invalid userId
,D/BluetoothAdapterService( 6576): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@384e72ba
,I/BluetoothSAPServiceJni( 6576): classInitNative(L204): succeeds
,D/SapService( 6576): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 6576): initializeNative(L209): sap
I/bluedroid( 6576): get_profile_interface sap
D/BluetoothAdapterService( 6576): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@384e72ba
,E/BluetoothAdapterService(944665274)( 6576): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
D/HeadsetStateMachine( 6576): Try to query the phonestate on bind
,D/BadgeProvider( 6059): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/Telecom ( 1401): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 1401): BluetoothPhoneService: updateHeadsetWithCallState
,E/SignOutReceiver( 6205): WIFI_STATE_CHANGED_ACTION
,D/RCPManagerService(  772): exchangeData() failure , invalid userId
,I/Telecom ( 1401): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 1401): Proxy not attached to service
,D/HeadsetStateMachine( 6576): Proxy object connected
D/HeadsetPhoneState( 6576): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState( 6576): sendDeviceDataStateChanged
D/HeadsetStateMachine( 6576): Disconnected process message: 11
D/HeadsetPhoneState( 6576): Signal level : previous=0 curr=0
V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6576): Disconnected process message: 18
D/HeadsetStateMachine( 6576): Disconnected process message: 10
E/BluetoothAdapterService(944665274)( 6576): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
D/BluetoothA2dp( 6576): Proxy object connected
D/BluetoothAdapterService( 6576): Bluetooth A2dp source service connected
D/HeadsetPhoneState( 6576): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
E/BluetoothAdapterService(944665274)( 6576): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/HeadsetStateMachine( 6576): Disconnected process message: 11
,E/BluetoothAdapterService(944665274)( 6576): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/RCPManagerService(  772): exchangeData() failure , invalid userId
E/BluetoothAdapterService(944665274)( 6576): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
E/BluetoothAdapterService(944665274)( 6576): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,I/ActivityManager(  772): Killing 4888:com.google.android.gm/u0a128 (adj 15): bgCount ##41
,E/BluetoothAdapterService(944665274)( 6576): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(944665274)( 6576): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,D/BluetoothAdapterState( 6576): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 6576): enable
,I/GKI_LINUX( 6576): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 6576): init
,D/BadgeProvider( 6059): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6059): sendNotify, [notify] : null
D/BadgeProvider( 6059): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6059): update, [BadgeCount] : badgecount=0
,D/Launcher.Model( 1437): reloadBadges entered.
D/BadgeProvider( 6059): update, [UpdateCount] : 1
,I/bt_vendor( 6576): init
I/bt_vnd_conf( 6576): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 6576): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 6576): userial_init
D/bt_vendor( 6576): op for 5
,D/bt_vendor( 6576): op for 0
,D/bt_upio ( 6576): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 6576): is_emulator_context : 0
D/bt_upio ( 6576): is_rfkill_disabled ? [0]
D/bt_upio ( 6576): is_rfkill_disabled ? [0]
,D/bt_vendor( 6576): op for 0
D/bt_upio ( 6576): upio_set_bluetooth_power(on: 1)
D/bt_upio ( 6576): is_emulator_context : 0
D/bt_upio ( 6576): is_rfkill_disabled ? [0]
,D/bt_vendor( 6576): op for 3
I/bt_userial_vendor( 6576): userial vendor open: opening /dev/ttyHS0
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/bt_userial_vendor( 6576): userial_vendor_open():UART is setup
I/bt_userial_vendor( 6576): device fd = 65 open
D/bt_vendor( 6576): op for 1
E/bt_hwcfg( 6576): Start CFG HW, HCI reset
,D/SecurityLogAgent( 6541): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6541): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6541): StateMachine : Current State = 1
D/bt_userial( 6576): Entering userial_read_thread()
,D/SecurityLogAgent( 6541): StateMachine : Changed Current State = 1
,I/ActivityManager(  772): Killing 5163:com.sec.android.app.music:service/u0a49 (adj 15): bgCount ##41
,D/RCPManagerService(  772): exchangeData() failure , invalid userId
,D/BluetoothNotiBroadcastReceiver( 1309): onReceive
,E/SMD     (  288): DCD ON
,D/AuthorizationBluetoothService( 1481): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ActivityManager(  772): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/Tethering(  772): No numeric data
,D/Tethering(  772): sendTetherStateChangedBroadcast 1, 0, 0
D/NtpTrustedTime(  772): forceRefresh() from cache miss
,D/HotspotTile( 1185): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/NtpTrustedTime(  772): forceRefresh Fail.
D/HotspotTile( 1185): updateTetherState():false, false
V/NetworkStats(  772): performPollLocked(flags=0x1)
,I/wpa_supplicant( 6575): wlan0: Setting scan request: 0 sec 100000 usec
D/NetworkStatsFactory(  772): UpdateStatsForKnox
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  772): performPollLocked() took 4ms
,D/NtpTrustedTime(  772): forceRefresh() from cache miss
,D/NtpTrustedTime(  772): forceRefresh Fail.
,I/wpa_supplicant( 6575): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/SecureStorage( 6575): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6575): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  391): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6575
I/SecureStorage(  391): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
I/SecureStorage( 6575): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6575): ssSupport state is = 1
,I/SecureStorage( 6575): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6575): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SecureStorage(  391): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6575
I/SecureStorage(  391): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
I/SecureStorage( 6575): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6575): ssSupport state is = 1
I/wpa_supplicant( 6575): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6575): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6575): SIM READ ERROR
I/wpa_supplicant( 6575): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant( 6575): p2p0: State: DISCONNECTED -> INACTIVE
,I/wpa_supplicant( 6575): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 6575): p2p0: State: INACTIVE -> DISCONNECTED
I/wpa_supplicant( 6575): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  772): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative-HAL(  772): callSECApiBoolean - ID [21]
,I/wpa_supplicant( 6575): HOTSPOT20_ENABLE called
I/wpa_supplicant( 6575): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6575): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6575): SIM READ ERROR
I/wpa_supplicant( 6575): Blacklist: Clear (all) 
,I/wpa_supplicant( 6575): Skip scan - bUseNetwork false
,D/WifiNative-HAL(  772): callSECApiInt - ID [210]
,D/WifiConfigStore(  772): Loading config and enabling all networks 
,D/SmartBondingService(  772): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SmartBondingService(  772): getNetworkEnabled : wifi : true mobile : true
,E/WifiConfigStore(  772): Not a HS20
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/HotspotTile( 1185): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-QSTileView( 1185): onStateChanged: Wi-Fi
D/StatusBar.NetworkController( 1185): applyOpen
D/HotspotTile( 1185): onReceive : 3, 0
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/STATUSBAR-WifiQuickSettingButton( 1185): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1185): Wifi onReceive(3)
,E/WifiConfigStore(  772): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/WifiCredService( 1309): Action received :android.net.wifi.WIFI_STATE_CHANGED
D/WifiNative-HAL(  772): callSECApiInt - ID [65]
E/SignOutReceiver( 6205): WIFI_STATE_CHANGED_ACTION
D/WifiNative-HAL(  772): callSECApiBoolean - ID [13]
I/wpa_supplicant( 6575): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 6575): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 6575): reset timer : RESET_TIMER 0
I/wpa_supplicant( 6575): P2P: Current p2p state = IDLE
I/wpa_supplicant( 6575): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 6575): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 6575): First Scan Start
I/wpa_supplicant( 6575): Scan requested (ret=0) - scan timeout 30 seconds
D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 6541): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6541): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6541): StateMachine : Current State = 1
D/SecurityLogAgent( 6541): StateMachine : Changed Current State = 1
D/WifiNative-HAL(  772): Setting external_sim to 1
D/WifiStateMachine(  772): Setting OUI to DA-A1-19
I/WifiNative-HAL(  772): startHal
E/wifi    (  772): getStaticLongField sWifiHalHandle 0x9b21b86c
D/wifi    (  772): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0xc01f6e
I/WifiNative-HAL(  772): Could not start hal
W/Settings( 4959): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/native  (  772): do suspend true
D/WifiP2pService(  772): P2pDisabledState{ what=131203 }
D/WifiScanningService(  772): SCAN_AVAILABLE : 3
D/WifiScanningService(  772): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  282): Setting iface cfg
I/WifiNative-HAL(  772): startHal
D/CommandListener(  282): Trying to bring up p2p0
E/wifi    (  772): getStaticLongField sWifiHalHandle 0x957f999c
D/wifi    (  772): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x401f66
D/WifiMonitor(  772): startMonitoring(p2p0) with mConnected = true
I/WifiNative-HAL(  772): Could not start hal
E/WifiScanningService(  772): could not start HAL
D/RttService(  772): SCAN_AVAILABLE : 3
D/WifiP2pService(  772): P2pEnablingState
D/RttService(  772): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  772): P2pEnablingState{ what=147457 }
D/WifiP2pService(  772): P2p socket connection successful
,E/WifiStateMachine(  772): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
D/WifiP2pService(  772): P2pEnabledState
E/WifiStateMachine(  772): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiP2pService(  772): sending p2p connection changed broadcast: IDLE
D/WifiDisplayController(  772): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  772): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  772): disconnect
D/WifiDisplayController(  772): updateConnection
D/WifiDisplayController(  772): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
D/WifiDisplayAdapter(  772): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/WifiStateMachine(  772): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-HAL(  772): callSECStringApiVoid - ID [215]
E/WifiNative-HAL(  772): invaild command id : 215
E/Zygote  ( 6697): MountEmulatedStorage()
E/Zygote  ( 6697): v2
I/libpersona( 6697): KNOX_SDCARD checking this for 10192
I/libpersona( 6697): KNOX_SDCARD not a persona
I/wpa_supplicant( 6575): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,I/ActivityManager(  772): Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=6697 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6697): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/WifiP2pService(  772): create mNetworkAgent
D/WifiDisplayController(  772): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/AllShareCastTile( 1185): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
I/SELinux ( 6697): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
D/WifiDisplayAdapter(  772): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 1185): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
E/SELinux ( 6697): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  772): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  772): Got NetworkAgent Messenger
D/ConnectivityService(  772): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService(  772): updateNetworkInfo()
,D/ConnectivityService(  772): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  772): NetworkAgent connected
E/CSLegacyTypeTracker(  772): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,I/wpa_supplicant( 6575): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/SecContentProvider2(  772): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  772): mCursor = null
,D/WifiNative-HAL(  772): p2pGetDeviceAddress
,D/SecContentProvider2(  772): uri = 20 selection = getPromptCredentialsEnabled
D/WifiNative-HAL(  772): p2pGetDeviceAddress returning ea:50:8b:de:28:a3
D/SecContentProvider2(  772): mCursor = null
D/WifiP2pService(  772): DeviceAddress: ea:28:a3
,D/WifiDisplayController(  772): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
D/WifiDisplayController(  772):  deviceAddress: ea:50:8b:de:28:a3
D/WifiDisplayController(  772):  primary type: 10-0050F204-5
D/WifiDisplayController(  772):  secondary type: null
D/WifiDisplayController(  772):  wps: 0
D/WifiDisplayController(  772):  grpcapab: 0
D/WifiDisplayController(  772):  devcapab: 0
D/WifiDisplayController(  772):  status: 3
D/WifiDisplayController(  772):  wfdInfo: null
D/WifiDisplayController(  772):  groupownerAddress: null
D/WifiDisplayController(  772):  GOdeviceName: null
D/WifiDisplayController(  772):  interfaceAddress: 
D/WifiDisplayController(  772):  SConnectInfo : null
,D/TimaKeyStoreProvider( 6697): TimaSignature is unavailable
,D/ActivityThread( 6697): Added TimaKeyStore provider
,D/WifiP2pService(  772): sending p2p persistent groups changed broadcast
,D/WifiP2pService(  772): InactiveState
D/WifiP2pService(  772): InactiveState{ what=143376 }
D/WifiP2pService(  772): P2pEnabledState{ what=143376 }
,I/wpa_supplicant( 6575): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/ConnectivityService(  772): updateNetworkInfo()
D/ConnectivityService(  772): ignoring duplicate network state non-change. WIFI_P2P, state = UNKNOWN
D/WifiP2pService(  772): InactiveState{ what=143376 }
D/WifiP2pService(  772): P2pEnabledState{ what=143376 }
,D/ResourcesManager( 6697): creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,D/WifiDirectBR( 6697): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,I/ActivityManager(  772): Killing 5232:com.sec.android.app.myfiles/u0a56 (adj 15): bgCount ##41
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1309): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1309): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1309): MountReceiver.mPrefHandler - 7002
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6713): MountEmulatedStorage()
E/Zygote  ( 6713): v2
I/libpersona( 6713): KNOX_SDCARD checking this for 10088
I/libpersona( 6713): KNOX_SDCARD not a persona
,I/ActivityManager(  772): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6713 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6713): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6713): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6713): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6713): TimaSignature is unavailable
,D/ActivityThread( 6713): Added TimaKeyStore provider
,D/ResourcesManager( 6713): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/FileShare-Server( 6713): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/WifiDirectBR( 6697): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiDirectBR( 6697): WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,W/ContextImpl( 6697): Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,D/WifiDirectBR( 6697): stopServiceTest : false
,I/ActivityManager(  772): Killing 5582:flipboard.app/u0a125 (adj 15): bgCount ##41
,I/wpa_supplicant( 6575): nl80211: Received scan results (6 BSSes)
,I/wpa_supplicant( 6575): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 6575): Trying to associate with C0.AA.4A (SSID='4E473730303567' freq=5220 MHz)
,I/wpa_supplicant( 6575): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 6575): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E473730303567
,E/Watchdog(  772): !@Sync 5
,D/SecContentProvider2(  772): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  772): mCursor = null
,I/wpa_supplicant( 6575): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 6575): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E473730303567
,I/wpa_supplicant( 6575): Associated with C0.AA.4A
,D/SecContentProvider2(  772): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  772): mCursor = null
,I/wpa_supplicant( 6575): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 6575): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.4A SSID=4E473730303567
,D/SecContentProvider2(  772): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  772): mCursor = null
,I/wpa_supplicant( 6575): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 6575): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 6575): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.4A SSID=4E473730303567
,I/wpa_supplicant( 6575): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6575): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,I/wpa_supplicant( 6575): CTRL-EVENT-CONNECTED - Connection to C0.AA.4A completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 6575): Blacklist: Clear (temp) 
I/wpa_supplicant( 6575): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.4A SSID=4E473730303567
,D/WifiNative-HAL(  772): callSECApiVoid - ID [50]
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
D/ConnectivityService(  772): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  772): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  772): Got NetworkAgent Messenger
D/ConnectivityService(  772): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  772): updateNetworkInfo()
D/ConnectivityService(  772): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  772): NetworkAgent connected
,E/WifiConfigStore(  772): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  282): Setting iface cfg
,E/Zygote  ( 6739): MountEmulatedStorage()
I/libpersona( 6739): KNOX_SDCARD checking this for 10038
E/Zygote  ( 6739): v2
I/libpersona( 6739): KNOX_SDCARD not a persona
,E/WifiStateMachine(  772): Start Dhcp Watchdog 1
I/ActivityManager(  772): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=6739 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/SecContentProvider2(  772): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  772): mCursor = null
,I/SELinux ( 6739): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
I/SELinux ( 6739): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6739): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  772): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,D/TimaKeyStoreProvider( 6739): TimaSignature is unavailable
,D/ActivityThread( 6739): Added TimaKeyStore provider
,D/ResourcesManager( 6739): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 6739): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/native  (  772): do suspend false
,D/WifiP2pService(  772): InactiveState{ what=143375 }
,D/WifiP2pService(  772): P2pEnabledState{ what=143375 }
D/SecContentProvider2(  772): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  772): mCursor = null
,I/VlingoApplication( 6739): VlingoApplication appVersion ='11.2.2.0.37649', ro.csc.sales_code=XEO
,E/dhcpcd  ( 6758): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6758): version 5.5.6 starting
,E/dhcpcd  ( 6758): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/BluetoothHeadset( 6739): BTStateChangeCB is registed
,E/BluetoothHeadset( 6739): BluetoothHeadset service is binded
,I/ActivityManager(  772): Killing 4959:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,I/Hs20UtilService( 1309): Starting #2
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1309): DMSUtil.isNetworkConnected - flag-null, state-null
I/Hs20UtilService( 1309): Message received 5007
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1309): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1309): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6205): NETWORK_STATE_CHANGED_ACTION
,I/dhcpcd  ( 6758): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6758): wlan0: sendmsg: Cannot assign requested address
,I/dhcpcd  ( 6758): if(wlan0) info get Success. (MAC : C0.AA.4A)
,I/dhcpcd  ( 6758): bssid match
I/dhcpcd  ( 6758): wlan0: rebinding lease of 192.168.1.128
,D/SettingsProvider(  772): name = driving_mode_on
,D/SettingsProvider(  772): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  772): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  772): selectionArgs: false
D/SettingsProvider(  772): selectionArgs: 10038
,D/SecContentProvider(  772): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  772): ret = -1
,D/BluetoothManager( 6739): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,I/art     (  772): Explicit concurrent mark sweep GC freed 69273(4MB) AllocSpace objects, 32(512KB) LOS objects, 17% free, 37MB/45MB, paused 1.582ms total 130.237ms
,E/SMD     (  288): DCD ON
,I/dhcpcd  ( 6758): wlan0: acknowledged 192.168.1.128 from 192.168.1.1
,I/dhcpcd  ( 6758): wlan0: leased 192.168.1.128 for 86400 seconds
,D/ConnectivityService(  772): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,E/native  (  772): do suspend true
,D/WifiP2pService(  772): InactiveState{ what=143375 }
,D/WifiP2pService(  772): P2pEnabledState{ what=143375 },
,D/ConnectivityService(  772): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine(  772): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG7005g"WPA_PSK
,E/WifiStateMachine(  772): VerifyingLinkState enter
,D/WifiNative-HAL(  772): callSECApiInt - ID [210]
,E/ConnectivityService(  772): updateNetworkInfo()
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiWatchdogStateMachine(  772): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  772): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService(  772): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService(  772): Adding iface wlan0 to network 502
D/WifiWatchdogStateMachine.DnsResolver(  772): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker(  772): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  772): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,I/Hs20UtilService( 1309): Starting #3
,I/Hs20UtilService( 1309): Message received 5007
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  772): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,I/WifiTrafficPoller(  772): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller(  772): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  772): mBoosterFLAG : 0
I/WifiTrafficPoller(  772): current booster mode : FullMode
D/WifiNative-HAL(  772): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): applyOpen
,E/WifiStateMachine(  772): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/NearbySettings( 1309): MountReceiver.onReceive - Keep current state
,D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): applyOpen
,D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
,D/ConnectivityService(  772): Adding Route [fe80::/64 -> :: wlan0] to network 502
,D/ConnectivityService(  772): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,D/ConnectivityService(  772): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 502
,E/ConnectivityService(  772): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  772): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  772): updateSourceRoutes : add src route for:192.168.1.128
,V/        (  282): QcRouteController
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6205): NETWORK_STATE_CHANGED_ACTION
,V/        (  282): QcRouteController
,I/Hs20UtilService( 1309): Starting #4
I/Hs20UtilService( 1309): Message received 5007
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1309): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1309): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1309): MountReceiver.mPrefHandler - 7002
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/        (  282): QcRouteController
,E/SignOutReceiver( 6205): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1309): Starting #5
,I/Hs20UtilService( 1309): Message received 5007
,V/        (  282): QcRouteController
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1309): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine(  772): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6205): NETWORK_STATE_CHANGED_ACTION
,V/        (  282): QcRouteController
,V/        (  282): QcRouteController
,I/SurfaceFlinger(  254): id=14 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService(  772): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=772
,V/        (  282): QcRouteController
,D/ConnectivityService(  772): Setting Dns servers for network 502 to [/192.168.1.1]
D/ConnectivityService(  772): LTETest block dns file not exists
,V/Nat464Xlat(  772): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  772): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  772): calling update connectivity
,E/ConnectivityService(  772): updateNetworkInfo()
D/ConnectivityService(  772): ignoring duplicate network state non-change. WIFI, state = CONNECTING
E/ConnectivityService(  772): updateNetworkInfo()
D/ConnectivityService(  772): ignoring duplicate network state non-change. WIFI, state = CONNECTING
D/EntConnectivity(  772): Not allowed due to - mEnabled false
D/ConnectivityService(  772): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  772): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  772): calling update connectivity
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  772): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  772): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  772): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  772): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  772): rematching NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  772):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  772):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  772):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/System.out(  772): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(  772): (HTTPLog)-Static: isShipBuild true
I/System.out(  772): (HTTPLog)-Thread-180-14438072: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out(  772): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService(  772): currentScore = 0, newScore = 60
,D/ConnectivityService(  772):    accepting network in place of null
,D/ConnectivityService(  772): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  772): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
D/TelephonyNetworkFactory( 1422): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  772): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  772): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
,D/ConnectivityService(  772): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  772): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  772): MasterInitialState.processMessage what=3
D/ConnectivityService(  772): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/SmartBondingService(  772): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  772): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  772): getSBEnabled() enabled =false
D/SmartBondingService(  772): getSBEnabled() enabled =false
D/SmartBondingService(  772): getSBEnabled() enabled =false
,D/ConnectivityService(  772): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  772): calling update connectivity
D/ConnectivityService(  772):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkStats(  772): updateIfacesLocked()
D/ConnectivityService(  772):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/EntConnectivity(  772): Not allowed due to - mEnabled false
V/NetworkStats(  772): performPollLocked(flags=0x1)
,D/ConnectivityService(  772): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkStatsFactory(  772): UpdateStatsForKnox
D/ConnectivityService(  772): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  772): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityManager.CallbackHandler( 1185): CM callback handler got msg 524290
,D/NtpTrustedTime(  772): forceRefresh() from cache miss
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1185): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1185): updateDataNetType()
D/StatusBar.NetworkController( 1185): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1185): updateLTEICONDataNetType:0
,V/NetworkStats(  772): performPollLocked() took 7ms
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
,I/System.out(  772): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NtpTrustedTime(  772): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1450226424737 mCachedNtpElapsedRealtime : 168337 mCachedNtpCertainty : 10
,D/NtpTrustedTime(  772): currentTimeMillis() cache hit
,D/NtpTrustedTime(  772): currentTimeMillis() cache hit
D/NtpTrustedTime(  772): currentTimeMillis() cache hit
D/NtpTrustedTime(  772): currentTimeMillis() cache hit
D/NtpTrustedTime(  772): currentTimeMillis() cache hit
D/NtpTrustedTime(  772): currentTimeMillis() cache hit
V/NetworkStats(  772): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  772): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 00:40:24 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450226425018], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450226425002]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  772): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  772): Validated
,D/ConnectivityService(  772): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  772): rematching NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  772):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  772):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  772): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,D/ConnectivityService(  772): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  772): calling update connectivity
D/ConnectivityManager.CallbackHandler( 1185): CM callback handler got msg 524290
,D/ConnectivityService(  772):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  772):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  772): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  772): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1185): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1185): updateDataNetType()
D/StatusBar.NetworkController( 1185): NoService, mRoamingIconId = 0
,E/StatusBar.NetworkController( 1185): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1185): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,I/jxcore-log( 6454): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6454): 
,D/ConnectivityService(  772): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1872): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,D/SmartBondingService(  772): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 1872): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
D/SmartBondingService(  772): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  772): SmartBondingReceiver: wifi ap is changed, init speed ratio
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  772): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  772): getSBEnabled() enabled =false
D/SmartBondingService(  772): getSBEnabled() enabled =false
,D/SmartBondingService(  772): getSBEnabled() enabled =false
D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  772): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  772): currentTimeMillis() cache hit
,D/AlarmManagerService(  772): Setting time of day to sec=1450226425
D/AlarmManagerService(  772): Trying to open a file
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/AlarmManagerService(  772): File Open Success
D/AlarmManagerService(  772): File Close Success
,I/AlarmManagerService(  772): DRM_TIME_PATH CHMOD 666 for resetState done 
V/AlarmManager(  772): waitForAlarm result :65536
,W/AlarmManagerService(  772): Unable to set rtc to 1450226425: Invalid argument
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PackageManager(  772): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiStateMachine(  772): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_SET
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_SET
,D/StatusBar-DoNotDistrub( 1185): Received intent with android.intent.action.TIME_SET action
,D/GpsLocationProvider(  772): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/NetworkMonitor( 5087): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 1741): [Accuweather J]>>> SWW:64 [0:0] =============== BR act = androidintentactionTIME_SET
,D/accuweather( 1741): [Accuweather J]>>> SWW:645 [0:0] renderUpdateAllCondition : [0] = 1
,D/accuweather( 1741): [Accuweather J]>>> WR:452 [0:0] =============== updateAllCondition = 1
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3156): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 3156): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 3156): [com.wssyncmldm.llllIIIllIlIIIIllllI(263/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_DM  ( 3156): [llIlIIIIlllIlllllIll(224/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,I/DBG_DM  ( 3156): [IIllIIllIIIlllIlIIll(403/llllllIllIlIlllIIlIl)] Check completed.
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3156): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 3156): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar-DoNotDistrub( 1185): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/PCWCLIENTTRACE_PushUtil( 5904): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5904): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5904): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5904): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/Zygote  ( 6883): MountEmulatedStorage()
E/Zygote  ( 6883): v2
I/libpersona( 6883): KNOX_SDCARD checking this for 10014
I/libpersona( 6883): KNOX_SDCARD not a persona
,I/ActivityManager(  772): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6883 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/Settings(  772): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/DBG_DM  ( 3156): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
D/StatusBar-DoNotDistrub( 1185): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,I/DBG_DM  ( 3156): [IIIlllIlIIlllIIIIllI(73/llllIIIllIlIIIIllllI)] 
,I/SELinux ( 6883): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,V/AudioPolicyManager(  295): getOutputsForDevice device 0002 -> 0002
I/AudioService(  772): getStreamVolume 5 index 0
D/StatusBar-DoNotDistrub( 1185): The STREAM NOTIFICATION volume is 0
,D/StatusBarManagerService(  772): manageDisableList userId=0 what=0x0 pkg=com.android.systemui
,I/SELinux ( 6883): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,E/SELinux ( 6883): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/DrmEventService(  772):  no response from SecureClock 
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6883): TimaSignature is unavailable
,D/ActivityThread( 6883): Added TimaKeyStore provider
,I/DBG_DM  ( 3156): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,E/Zygote  ( 6901): MountEmulatedStorage()
E/Zygote  ( 6901): v2
I/libpersona( 6901): KNOX_SDCARD checking this for 10004
I/libpersona( 6901): KNOX_SDCARD not a persona
,I/DBG_DM  ( 3156): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 3
,I/ActivityManager(  772): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6901 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_DM  ( 3156): [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 2
,I/DBG_DM  ( 3156): [IIllIIllIIIlllIlIIll(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,I/SELinux ( 6901): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/DBG_DM  ( 3156): [IIllIIllIIIlllIlIIll(177/lllIlIlIIIllIIlIllIl)] nDownloadPostpone is [3]
,I/SELinux ( 6901): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6901): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3156): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1280/handleMessage)] 
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3156): [com.wssyncmldm.XDMService(849/llIIllllIIlllIIIIlll)] 
,D/ResourcesManager( 6883): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/GoogleURLConnFactory( 1481): Using platform SSLCertificateSocketFactory
,I/DBG_DM  ( 3156): [llIlIIIIlllIlllllIll(280/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 3156): [llIlIIIIlllIlllllIll(1907/lllIlIlIIIllIIlIllIl)] 
,D/TimaKeyStoreProvider( 6901): TimaSignature is unavailable
,D/ActivityThread( 6901): Added TimaKeyStore provider
,I/DBG_DM  ( 3156): [com.wssyncmldm.XDMBroadcastReceiver(332/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 3156): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(501/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3156): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3156): [com.wssyncmldm.ui.XUIFotaPostponeActivity(493/llIIIIlllllIIllIIllI)] 
,D/ResourcesManager( 6901): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/FOTA_Client( 6883): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 6883): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3156): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
,E/Zygote  ( 6924): MountEmulatedStorage()
E/Zygote  ( 6924): v2
I/libpersona( 6924): KNOX_SDCARD checking this for 10023
I/libpersona( 6924): KNOX_SDCARD not a persona
,I/ActivityManager(  772): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6924 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6924): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6924): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,V/AlarmManager(  772): waitForAlarm result :4
,E/SELinux ( 6924): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6924): TimaSignature is unavailable
,D/ActivityThread( 6924): Added TimaKeyStore provider
,E/Zygote  ( 6941): MountEmulatedStorage()
,E/Zygote  ( 6941): v2
I/libpersona( 6941): KNOX_SDCARD checking this for 10104
I/libpersona( 6941): KNOX_SDCARD not a persona
,I/SELinux ( 6941): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6941): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,I/ActivityManager(  772): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6941 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6941): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3156): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
,V/GLSActivity( 1481): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 6924): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/SecContentProvider2(  772): uri = 14 selection = getSealedState
D/SecContentProvider2(  772): mCursor = null
,D/ApplicationPolicy(  772): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy(  772): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager(  772): showStatusBarByNotification() mOpenByNotification=false
,D/TimaKeyStoreProvider( 6941): TimaSignature is unavailable
,D/ActivityThread( 6941): Added TimaKeyStore provider
,I/ActivityManager(  772): Killing 5730:com.google.android.gms:car/u0a15 (adj 15): bgCount ##41
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.511: ( 6924): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 6924): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1450226425746
,I/KLMS-2.4.511: ( 6924): MainReciver(): TIME_CHANGED
,I/KLMS-2.4.511: ( 6924): StateImplV2(): dateTimeChanged().START : Wed Dec 16 01:40:25 GMT+01:00 2015
,I/KLMS-2.4.511: ( 6924): StateImplV2(): dateTimeChanged().END
,E/Zygote  ( 6958): MountEmulatedStorage()
E/Zygote  ( 6958): v2
I/libpersona( 6958): KNOX_SDCARD checking this for 1000
I/libpersona( 6958): KNOX_SDCARD not a persona
,I/ActivityManager(  772): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6958 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6958): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6958): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6958): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 1185): Explicit concurrent mark sweep GC freed 54419(2MB) AllocSpace objects, 8(14MB) LOS objects, 28% free, 39MB/55MB, paused 433us total 72.214ms
,D/ResourcesManager( 1185): creating new AssetManager and set to /system/priv-app/SyncmlDM/SyncmlDM.apk
,D/ResourcesManager( 6941): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/ActivityManager(  772): Killing 5801:com.android.defcontainer/u0a7 (adj 15): bgCount ##41
D/KnoxNotification( 1185): ----- inflateViews : modified publicViewLocal -----
,D/TimaKeyStoreProvider( 6958): TimaSignature is unavailable
,D/ActivityThread( 6958): Added TimaKeyStore provider
,D/KnoxNotification( 1185): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1185): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 1185): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@230baec8
,D/PersonaManager( 1185): isKioskContainerExistOnDevice
,W/System.err( 5923): android.provider.Settings$SettingNotFoundException: TIME_DIFFERENCE
D/PersonaManager( 1185): isKioskContainerExistOnDevice
,W/System.err( 5923): 	at android.provider.Settings$System.getLongForUser(Settings.java:1679)
W/System.err( 5923): 	at android.provider.Settings$System.getLong(Settings.java:1669)
W/System.err( 5923): 	at com.sec.android.sCloudSync.g.d.b(SourceFile:83)
W/System.err( 5923): 	at com.sec.android.sCloudSync.Receivers.TimeChangedReceiver.onReceive(SourceFile:64)
W/System.err( 5923): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2991)
W/System.err( 5923): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
,W/System.err( 5923): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
W/System.err( 5923): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5923): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5923): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
W/System.err( 5923): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5923): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5923): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
,W/System.err( 5923): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
,E/GpsLocationProvider(  772): No APN found to select.
,D/PanelView( 1185): There is/are notification(s) 
D/PanelView( 1185): There is/are notification(s) 
,D/ResourcesManager( 6958): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6975): MountEmulatedStorage()
,E/Zygote  ( 6975): v2
I/libpersona( 6975): KNOX_SDCARD checking this for 10042
I/libpersona( 6975): KNOX_SDCARD not a persona
,I/SELinux ( 6975): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6975): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6975): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  772): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/com.sec.android.fota.osp.time.ServerTimeReceiver: pid=6975 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,D/ConnectivityService(  772): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=true
,D/ConnectivityService(  772): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService(  772): identical MTU - not setting
D/ConnectivityService(  772): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  772): updateSourceRoutes : add src route for:fe80::ea50:8bff:fede:28a3
,V/        (  282): QcRouteController
,D/SmartBondingService(  772): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  772): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  772): getSBEnabled() enabled =false
D/SmartBondingService(  772): getSBEnabled() enabled =false
D/SmartBondingService(  772): getSBEnabled() enabled =false
,V/        (  282): QcRouteController
,I/art     (  319): Explicit concurrent mark sweep GC freed 8743(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 568us total 31.443ms
,W/NetworkManagementService(  772): route cmd failed: 
W/NetworkManagementService(  772): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '54 route replace src v6 wlan0 fe80::ea50:8bff:fede:28a3 2 ::' failed with '400 54 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  772): '
W/NetworkManagementService(  772): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService(  772): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService(  772): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService(  772): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService(  772): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  772): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5625)
W/NetworkManagementService(  772): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5437)
W/NetworkManagementService(  772): 	at com.android.server.ConnectivityService.access$2300(ConnectivityService.java:229)
W/NetworkManagementService(  772): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2382)
W/NetworkManagementService(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  772): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/Nat464Xlat(  772): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  772): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  772): calling update connectivity
D/ConnectivityService(  772):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  772):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  772): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  772): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  772): calling update connectivity
D/ConnectivityService(  772):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  772):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  772): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1185): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1185): CM callback handler got msg 524295
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 403us total 14.508ms
,I/DIAGMON_AGENT( 6958): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,D/TimaKeyStoreProvider( 6975): TimaSignature is unavailable
,D/ActivityThread( 6975): Added TimaKeyStore provider
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 400us total 14.913ms
,D/ResourcesManager( 6975): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): stay LED for fully charged
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/DIAGMON_AGENT( 6958): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6576): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/SO_AGENT( 6975): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,I/SA      ( 5991): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityThread( 1747): Failed to find provider info for com.android.contacts.metadata
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DelayedSyncController( 6941): Delaying sync.
,I/System.out( 1481): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1481): (HTTPLog)-Static: isShipBuild true
I/System.out( 1481): (HTTPLog)-Thread-188-77952145: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1481): (HTTPLog)-Static: isSBSettingEnabled false
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,D/SyncManager(  772): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 19701, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  772): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 200254, reason: UserStart
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7002): MountEmulatedStorage()
I/libpersona( 7002): KNOX_SDCARD checking this for 10076
E/Zygote  ( 7002): v2
I/libpersona( 7002): KNOX_SDCARD not a persona
,I/System.out( 1481): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1481): Tagging socket 66 with tag 1000120300000000{268440067,0} uid -1, pid: 1481, getuid(): 10015
,I/ActivityManager(  772): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=7002 uid=10076 gids={50076, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7002): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  772): Killing 5869:com.google.android.partnersetup/u0a19 (adj 15): bgCount ##41
,I/SELinux ( 7002): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7002): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2(  772): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  772): mCursor = null
,V/GLSActivity( 1481): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7002): TimaSignature is unavailable
,D/ActivityThread( 7002): Added TimaKeyStore provider
,D/ResourcesManager( 7002): creating new AssetManager and set to /system/priv-app/sCloudDataSync/sCloudDataSync.apk
,I/DIAGMON_AGENT( 6958): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DIAGMON_AGENT( 6958): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6958): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6958): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
I/ActivityManager(  772): Killing 5888:com.samsung.groupcast/u0a20 (adj 15): bgCount ##41
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,E/Auth.Api.Credentials( 1747): [CredentialSyncAdapter] Unknown sync event.
,I/qtaguid ( 1481): Tagging socket 70 with tag 1000120300000000{268440067,0} uid -1, pid: 1481, getuid(): 10015
,E/Zygote  ( 7019): MountEmulatedStorage()
I/libpersona( 7019): KNOX_SDCARD checking this for 10106
E/Zygote  ( 7019): v2
I/libpersona( 7019): KNOX_SDCARD not a persona
,I/ActivityManager(  772): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=7019 uid=10106 gids={50106, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/SELinux ( 7019): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  772): Killing 5332:sstream.app/u0a25 (adj 15): bgCount ##41
,I/SELinux ( 7019): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7019): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7019): TimaSignature is unavailable
,D/ActivityThread( 7019): Added TimaKeyStore provider
,I/ Time Manager ( 7002): Time Difference not stored. TIME_DIFFERENCE
,D/ResourcesManager( 7019): creating new AssetManager and set to /system/app/ClockPackage_Osup/ClockPackage_Osup.apk
,W/ResourcesManager( 7019): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7019): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7019): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7019): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7019): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7019): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,I/FOTA_Client( 6883): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 6883): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FOTA_Client( 6883): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/ActivityManager(  772): Killing 5365:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): bgCount ##41
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6924): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/SettingsProvider(  772): name = next_alarm_formatted
D/SettingsProvider(  772): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  772): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  772): selectionArgs: false
D/SettingsProvider(  772): selectionArgs: 10106
D/SecContentProvider(  772): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  772): ret = -1
I/KLMS-2.4.511: ( 6924): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450226426475
,I/KLMS-2.4.511: ( 6924): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6924): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.511: ( 6924): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.511: ( 6924): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.511: ( 6924): StateImplV2(): networkChangeListener().END
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7037): MountEmulatedStorage()
I/libpersona( 7037): KNOX_SDCARD checking this for 10036
E/Zygote  ( 7037): v2
I/libpersona( 7037): KNOX_SDCARD not a persona
,I/ActivityManager(  772): Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7037 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 7037): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7037): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7037): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/bt-btif ( 6576): ...preload_wait_timeout (retried:0/max-retry:1)...
,D/bt_userial( 6576): RX termination
W/bt_userial( 6576): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 6576): Leaving userial_read_thread()
D/bt_vendor( 6576): op for 4
I/bt_userial_vendor( 6576): device fd = 65 close
,D/TimaKeyStoreProvider( 7037): TimaSignature is unavailable
,D/ActivityThread( 7037): Added TimaKeyStore provider
,D/SSRM:n  (  772): SIOP:: AP = 340, PST = 315, CUR = 450
,E/SMD     (  288): DCD ON
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 7037): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,W/ResourcesManager( 7037): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7037): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Minikin ( 7037): addFont failed to create font /system/fonts/SamsungSans-light.ttf
,E/Zygote  ( 7052): MountEmulatedStorage()
E/Zygote  ( 7052): v2
I/libpersona( 7052): KNOX_SDCARD checking this for 10116
I/libpersona( 7052): KNOX_SDCARD not a persona
,D/bt_vendor( 6576): op for 0
,D/bt_upio ( 6576): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 6576): is_emulator_context : 0
D/bt_upio ( 6576): is_rfkill_disabled ? [0]
,D/bt_vendor( 6576): cleanup
,I/SELinux ( 7052): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7052): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7052): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  772): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7052 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  772): Killing 5939:com.policydm/1000 (adj 15): bgCount ##41
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  772): Killing 4671:com.sec.spp.push/u0a43 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7052): TimaSignature is unavailable
,D/ActivityThread( 7052): Added TimaKeyStore provider
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7052): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/elm:14491( 7052): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14491( 7052): ELMEngine.ELMEngine( context ).
,D/elm:14491( 7052): MDMBridge.setEnterpriseBridge()
,I/SO_AGENT( 6975): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,I/bt_hci_bdroid( 6576): init
,I/bt_vendor( 6576): init
,I/bt_vnd_conf( 6576): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 6576): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 6576): userial_init
D/bt_vendor( 6576): op for 5
,D/bt_vendor( 6576): op for 0
,D/bt_upio ( 6576): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 6576): is_emulator_context : 0
D/bt_upio ( 6576): is_rfkill_disabled ? [0]
D/bt_upio ( 6576): is_rfkill_disabled ? [0]
D/bt_vendor( 6576): op for 0
D/bt_upio ( 6576): upio_set_bluetooth_power(on: 1)
,D/bt_upio ( 6576): is_emulator_context : 0
D/bt_upio ( 6576): is_rfkill_disabled ? [0]
D/bt_vendor( 6576): op for 3
,I/bt_userial_vendor( 6576): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 6576): userial_vendor_open():UART is setup
,I/bt_userial_vendor( 6576): device fd = 65 open
D/bt_vendor( 6576): op for 1
D/bt_userial( 6576): Entering userial_read_thread()
E/bt_hwcfg( 6576): Start CFG HW, HCI reset
,D/elm:14491( 7052): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/elm:14491( 7052): ElmAgentService : onCreate()
,D/elm:14491( 7052): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/elm:14491( 7052): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:14491( 7052): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:14491( 7052): ModuleBase.ModifySetAlarm()
D/elm:14491( 7052): MDMBridge.getInstance()
D/elm:14491( 7052): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 7078): MountEmulatedStorage()
,E/Zygote  ( 7078): v2
I/libpersona( 7078): KNOX_SDCARD checking this for 1000
I/libpersona( 7078): KNOX_SDCARD not a persona
,I/SELinux ( 7078): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7078): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7078): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  772): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7078 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/elm:14491( 7052): ElmAgentService : onDestroy().
,E/bt_hwcfg( 6576): Read Local Name after HCI reset
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7078): TimaSignature is unavailable
D/ActivityThread( 7078): Added TimaKeyStore provider
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/bt_hwcfg( 6576): Chipset BCM4335C0
D/bt_hwcfg( 6576): Target name = [BCM4335C0]
D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/bt_hwcfg( 6576): module_type[semco].
I/bt_hwcfg( 6576): not ZERO...
I/bt_hwcfg( 6576): module_type[semco] is invalid.
E/bt_hwcfg( 6576): patchram path ORG . BCM4335C0
E/bt_hwcfg( 6576): patchram path ORG .. BCM4335C0
E/bt_hwcfg( 6576): patchram path ORG bcm2079xB4_firmware.ncd BCM4335C0
E/bt_hwcfg( 6576): patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335C0
E/bt_hwcfg( 6576): patchram path ORG bcm2079xB5_firmware.ncd BCM4335C0
E/bt_hwcfg( 6576): patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335C0
E/bt_hwcfg( 6576): patchram path ORG bcm4335_V0093.0399.hcd BCM4335C0
E/bt_hwcfg( 6576): patchram path ORG bcm4335_V0093.0399_wisol.hcd BCM4335C0
E/bt_hwcfg( 6576): fw ver (org)0.0
E/bt_hwcfg( 6576): vendor lib preload failed to locate firmware patch file
E/bt_hwcfg( 6576): Remove module rev, try again BCM4335
D/bt_hwcfg( 6576): Target name = [BCM4335]
I/bt_hwcfg( 6576): module_type[semco].
I/bt_hwcfg( 6576): not ZERO...
I/bt_hwcfg( 6576): module_type[semco] is invalid.
E/bt_hwcfg( 6576): patchram path ORG . BCM4335
E/bt_hwcfg( 6576): patchram path ORG .. BCM4335
E/bt_hwcfg( 6576): patchram path ORG bcm2079xB4_firmware.ncd BCM4335
E/bt_hwcfg( 6576): patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335
E/bt_hwcfg( 6576): patchram path ORG bcm2079xB5_firmware.ncd BCM4335
E/bt_hwcfg( 6576): patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335
E/bt_hwcfg( 6576): patchram path ORG bcm4335_V0093.0399.hcd BCM4335
I/bt_hwcfg( 6576): patch(org) : bcm4335_V0093.0399.hcd
I/bt_hwcfg( 6576): Found patchfile: /vendor/firmware/bcm4335_V0093.0399.hcd
E/bt_hwcfg( 6576): ORG patchram base 0093
E/bt_hwcfg( 6576): ORG patchram minor 0399
E/bt_hwcfg( 6576): fw ver (org)93.399
E/bt_hwcfg( 6576): Final Patchram is /vendor/firmware/bcm4335_V0093.0399.hcd
,I/bt_hwcfg( 6576): Axi patch failure or not include AXI patching
,I/bt_hwcfg( 6576): bt vendor lib: set UART baud 3000000
,E/Zygote  ( 7093): MountEmulatedStorage()
,E/Zygote  ( 7093): v2
I/libpersona( 7093): KNOX_SDCARD checking this for 10172
I/libpersona( 7093): KNOX_SDCARD not a persona
,I/SELinux ( 7093): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7093): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
I/ActivityManager(  772): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7093 uid=10172 gids={50172, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/SELinux ( 7093): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  772): Killing 5959:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): bgCount ##41
,D/ResourcesManager( 7078): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
I/ActivityManager(  772): Killing 6074:com.sec.android.app.soundalive/u0a64 (adj 13): bgCount ##41
,D/ConnectivityService(  772): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  772): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
D/ConnectivityService(  772): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  772): apparently satisfied.  currentScore=60
,D/ConnectivityService(  772): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1747): CM callback handler got msg 524290
,D/TimaKeyStoreProvider( 7093): TimaSignature is unavailable
,D/ActivityThread( 7093): Added TimaKeyStore provider
,W/PhenotypeConfigurator( 1481): Server returned 404
,D/ResourcesManager( 7093): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,W/ResourcesManager( 7093): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7093): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7093): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PicasaService( 5179): start picasa sync
D/PicasaService( 5179): end picasa sync
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7121): MountEmulatedStorage()
I/libpersona( 7121): KNOX_SDCARD checking this for 10043
E/Zygote  ( 7121): v2
I/libpersona( 7121): KNOX_SDCARD not a persona
,I/ActivityManager(  772): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7121 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 7121): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7121): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7121): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/dhcpcd  ( 6758): wlan0: sending IPv6 Router Solicitation
,E/Zygote  ( 7132): MountEmulatedStorage()
E/Zygote  ( 7132): v2
I/libpersona( 7132): KNOX_SDCARD checking this for 10051
I/libpersona( 7132): KNOX_SDCARD not a persona
,I/ActivityManager(  772): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7132 uid=10051 gids={50051, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7132): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7132): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7132): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/SecurityLogAgent( 6541): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6541): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6541): StateMachine : Current State = 1
D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7121): TimaSignature is unavailable
,D/ActivityThread( 7121): Added TimaKeyStore provider
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 7121): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/TimaKeyStoreProvider( 7132): TimaSignature is unavailable
,D/ActivityThread( 7132): Added TimaKeyStore provider
,E/Zygote  ( 7153): MountEmulatedStorage()
I/libpersona( 7153): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7153): v2
I/libpersona( 7153): KNOX_SDCARD not a persona
,I/ActivityManager(  772): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7153 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SELinux ( 7153): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7153): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7153): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 7132): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager( 7132): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 7153): TimaSignature is unavailable
,D/ActivityThread( 7153): Added TimaKeyStore provider
,E/SPPClientService( 7121): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 7121): [PushClientApplication] Push log off : This is Ship build version
,D/ResourcesManager( 7153): creating new AssetManager and set to /system/app/TimeService/TimeService.apk
,D/SPPClientService( 7121): PushLog.txt file is not deleted.
,D/SPPClientService( 7121): PushLog.txt file is not deleted.
D/SPPClientService( 7121): ============PushLog. stop!
,I/ActivityManager(  772): Killing 4944:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##41
,D/TimeService( 7153): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450226427370
D/        ( 7153): TimeServiceNative: User Time to be set is 1450226427370
D/QC-time-services( 7153): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 7153): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 7153): Lib:time_genoff_operation: pargs->ts_val = 1450226427370
,D/QC-time-services(  329): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 7153): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  329): Daemon:Received base = 2, unit = 1, operation = 0,value = 1450226427370
D/QC-time-services(  329): Daemon:genoff_opr: Base = 2, val = 1450226427370, operation = 0
D/QC-time-services(  329): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/24/70 7:28:52
D/QC-time-services(  329): Daemon:Value read from RTC seconds = 9790132000
D/QC-time-services(  329): Daemon:new time 1450226427370 
D/QC-time-services(  329): Daemon: delta 1440436295370 genoff 1440436295370 
D/QC-time-services(  329): Daemon:genoff_persistent_update: Writing genoff = 1440436295370 to memory
D/QC-time-services(  329): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  329): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  329): Updating the TOD offset
D/QC-time-services(  329): Daemon:genoff_persistent_update: Writing genoff = 1440436295370 to memory
D/QC-time-services(  329): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  329): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  329): Daemon:Update to modem bit set
D/QC-time-services(  329): Daemon:genoff_send_modem: Sending data to MODEM !
E/QC-time-services( 7153): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  329): Daemon: Base = 2, Value being sent to MODEM = 1124471495370
,E/QC-time-services(  329): Daemon: Time-services: Waiting to acceptconnection
E/QC-time-services(  329): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/SPPClientService( 7121): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/CalendarProvider2( 7132): CalendarProvider2.onCreate() called
,I/bt_hwcfg( 6576): bt vendor lib: set UART baud 115200
I/bt_hwcfg( 6576): FW Download delta = 536861
D/bt_hwcfg( 6576): Settlement delay -- 100 ms
I/bt_hwcfg( 6576): Setting fw settlement delay to 100 
,I/SA      ( 5991): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 5991): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5991): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,D/comdaemonstockapp( 3241): [Daemon_Stock]>>> Stockclock_DaemonService.java:63 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 3241): [Daemon_Stock]>>> Stockclock_DaemonService.java:64 [0:0] appServiceStatus: 0
D/comdaemonstockapp( 3241): [Daemon_Stock]>>> Stockclock_DaemonService.java:65 [0:0] [AR]: 0
,D/comdaemonstockapp( 3241): [Daemon_Stock]>>> Stockclock_DaemonService.java:66 [0:0] [AR]: Next time = 0
I/SA      ( 5991): [SLFUCHKMGR] constructor called
,I/SA      ( 5991): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 5991): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 5991): [SCU] == networkStateCheck == true
I/art     (  772): Explicit concurrent mark sweep GC freed 63173(3MB) AllocSpace objects, 11(176KB) LOS objects, 17% free, 37MB/45MB, paused 3.004ms total 133.057ms
,I/SA      ( 5991): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5991): isChinaCountryCode : false
I/SA      ( 5991): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5991): [OR] == networkStateCheck true ==
,I/SA      ( 5991): [OR] GetMyCountryZoneTask
,I/SA      ( 5991): [OR] onReceive END
,D/daemonapp( 3241): [MSC_Accu_Daemon]>>> AWDS:70 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 3241): [MSC_Accu_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3241): [MSC_Accu_Daemon]>>> daemonapp [Version : 14123102 ] [ 1 ] 
,D/comsamsunglog( 3241): [MSC_Accu_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3241): [MSC_Accu_Daemon]>>> ====================================================================================================================
,D/daemonapp( 3241): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 3241): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,D/daemonapp( 3241): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3241): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3241): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,I/ActivityManager(  772): Killing 5430:com.sec.chaton/u0a102 (adj 13): bgCount ##41
,D/daemonapp( 3241): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3241): [MSC_Accu_Daemon]>>> AWDS:113 [0:0] SerStus:true,TmpS:1,AtRfr:3, checkCurrent: 0
D/daemonapp( 3241): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 3241): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
D/daemonapp( 3241): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/SA      ( 5991): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  772): Killing 6111:com.wsomacp/u0a29 (adj 13): bgCount ##41
,D/daemonapp( 3241): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,I/SA      ( 5991): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5991): [SSP] query invoked
,E/Zygote  ( 7177): MountEmulatedStorage()
E/Zygote  ( 7177): v2
I/libpersona( 7177): KNOX_SDCARD checking this for 10074
I/libpersona( 7177): KNOX_SDCARD not a persona
,I/bt_hwcfg( 6576): bt vendor lib: set UART baud 3000000
,I/ActivityManager(  772): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7177 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/bt_hwcfg( 6576): vendor lib fwcfg completed
W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SELinux ( 7177): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SA      ( 5991): [TPMU] GetMccFromDB : null
,I/SELinux ( 7177): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7177): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SA      ( 5991): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5991): [TPM] isNoProxy(default) : true
,I/        ( 6576): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6576): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6576): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6576): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6576): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6576): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6576): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6576): BTE_InitTraceLevels -- TRC_BTM
,I/        ( 6576): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6576): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6576): BTE_InitTraceLevels -- TRC_SAP
I/        ( 6576): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6576): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6576): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6576): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6576): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 6576): BTE_InitTraceLevels -- TRC_PROTOCOL
,E/File    ( 5991): fail readDirectory() errno=2
,D/TimaKeyStoreProvider( 7177): TimaSignature is unavailable
,D/ActivityThread( 7177): Added TimaKeyStore provider
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CheckinService( 1747): Checkin interval check for package: unspecified last checkin: 1450111122452 min interval config: 0 actual interval: 115305172
,I/VacuumService( 1481): Vacuum at: now=1450226427633 tag=VacuumService
,D/ResourcesManager( 7177): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DelayedSyncController( 6941): Delaying sync.
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  772): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/sCloudBackupApp( 7177): sCloudBackupApp Version Info : 3.13.7.KK_APP
,I/SCloudBackupReceiver( 7177): Other Intent
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7204): MountEmulatedStorage()
E/Zygote  ( 7204): v2
I/libpersona( 7204): KNOX_SDCARD checking this for 1000
,I/libpersona( 7204): KNOX_SDCARD not a persona
,W/bt-l2cap( 6576): l2c_link_processs_ble_num_bufs 15
,E/bt-btm  ( 6576): BTM_SecRegister:p_cb_info->p_le_callback == 0xa1bddb05 
E/bt-btm  ( 6576): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa1bddb05 
,I/ActivityManager(  772): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7204 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     (  319): Explicit concurrent mark sweep GC freed 8760(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 310us total 13.331ms
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 276us total 9.731ms
,I/SELinux ( 7204): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7204): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7204): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 279us total 14.700ms
,D/TimaKeyStoreProvider( 7204): TimaSignature is unavailable
,D/ActivityThread( 7204): Added TimaKeyStore provider
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7204): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7204): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KnoxUsageLogPro( 7204): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7204): premStatus:2
I/ActivityManager(  772): Killing 6093:com.google.android.apps.docs/u0a112 (adj 13): bgCount ##41
,I/KnoxUsageLogPro( 7204): isEulaShown : false
I/KnoxUsageLogPro( 7204): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7220): MountEmulatedStorage()
I/libpersona( 7220): KNOX_SDCARD checking this for 10102
E/Zygote  ( 7220): v2
I/libpersona( 7220): KNOX_SDCARD not a persona
,I/ActivityManager(  772): Start proc com.sec.chaton for broadcast com.sec.chaton/.receiver.NetStateReceiver: pid=7220 uid=10102 gids={50102, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  772): Killing 6140:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##41
,I/SELinux ( 7220): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7220): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7220): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7220): TimaSignature is unavailable
,D/ActivityThread( 7220): Added TimaKeyStore provider
,D/BluetoothAdapterProperties( 6576): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 0 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = false
,I/SurfaceFlinger(  254): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  254): id=14 Removed Uoast (-2/9)
,E/bt-btif ( 6576): Calling BTA_HhEnable
,D/PowerManagerService(  772): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 772) eventTime = 171605
,E/bt-btif ( 6576): btif_storage_get_adapter_property service_mask:0x2120048
D/BluetoothAdapterProperties( 6576): Address is:E0:DB:10:1F:C9:5E
E/BluetoothServiceJni( 6576): populateRssiValuesNative
I/bluedroid( 6576): getModelRssiValues
D/PowerManagerService(  772): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=772 (0x0)
E/BluetoothServiceJni( 6576): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/PowerManagerService(  772): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=772, ws=WorkSource{10067}) (elapsedTime=3477)
D/BluetoothAdapterProperties( 6576): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothAdapterProperties( 6576): Name is: Note3-1
,D/SettingsProvider(  772): name = bluetooth_name
D/BluetoothAdapterProperties( 6576): Scan Mode:20
D/BluetoothAdapterProperties( 6576): Discoverable Timeout:120
,D/BluetoothAdapterProperties( 6576): LE Address is:E0:B7:20:3E:93:BC
E/bt-btif ( 6576): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 6576): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 6576): btif_sock_init: !radio_req && !rfc_init
D/bt_vendor( 6576): op for 2
D/bt_vendor( 6576): op for 6
,E/bt-btif ( 6576): btif_sock_init: !vhci_init
,D/IOP_DB_BT( 6576): db_open: file /etc/bluetooth/iop_bt.db
D/bt_vendor( 6576): op for 7
,D/bt_upio ( 6576): proc btwrite assertion
D/IOP_DB_BT( 6576): db_open: db_open : handle 3026198544l, read 14063 bytes onto local cache
D/IOP_DB_BT( 6576): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 6576): db_query: result 1
I/        ( 6576): iop_db_open: iop_db_open status 0
,D/bte_conf( 6576): Device ID record 1 : primary
D/bte_conf( 6576):   vendorId            = 0075
D/bte_conf( 6576):   vendorIdSource      = 0001
D/bte_conf( 6576):   product             = 0100
D/bte_conf( 6576):   version             = 0200
D/bte_conf( 6576):   clientExecutableURL = 
D/bte_conf( 6576):   serviceDescription  = 
D/bte_conf( 6576):   documentationURL    = 
D/bte_conf( 6576): bte_load_did_conf no section named DID2.
D/bt_vendor( 6576): op for 7
D/bt_upio ( 6576): BT_WAKE is asserted already
,D/BluetoothPanServiceJni( 6576): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 6576): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6576): ScanMode =  20
D/BluetoothAdapterProperties( 6576): State =  11
,D/bt_vendor( 6576): op for 7
D/bt_upio ( 6576): BT_WAKE is asserted already
D/SecContentProvider(  772): uri = 3 selection = isDiscoverableEnabled
,D/BluetoothAdapterProperties( 6576): Setting state to 12
I/BluetoothAdapterState( 6576): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterProperties( 6576): Scan Mode:21
D/BluetoothAdapterProperties( 6576): Discoverable Timeout:120
D/ResourcesManager( 7220): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/SettingsProvider(  772): name = bluetooth_a2dp_sink_mode
D/SettingsProvider(  772): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  772): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  772): selectionArgs: false
D/SettingsProvider(  772): selectionArgs: 1002
D/SecContentProvider(  772): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  772): ret = -1
,W/ResourcesManager( 7220): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/BackupManagerService(  772): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService( 6576): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 6576): updateAdapterState state is 12
,D/BluetoothA2dp( 6576): onBluetoothStateChange: up=true
,D/BluetoothAdapterService( 6576): Autoconnection is available 
D/BluetoothAdapterService( 6576): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 6576): starting service from this receiver
,D/BluetoothA2dp( 2941): onBluetoothStateChange: up=true
,I/BluetoothAdapterState( 6576): Entering On State from state = 11
,D/bt_vendor( 6576): op for 7
D/bt_upio ( 6576): BT_WAKE is asserted already
E/bt_h4   ( 6576): vendor lib postload completed
D/bt_vendor( 6576): op for 7
D/bt_upio ( 6576): BT_WAKE is asserted already
D/BluetoothA2dp(  772): onBluetoothStateChange: up=true
D/bt_vendor( 6576): op for 7
D/bt_upio ( 6576): BT_WAKE is asserted already
,D/bt_vendor( 6576): op for 7
D/bt_upio ( 6576): BT_WAKE is asserted already
,W/InputMethodManagerService(  772): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  772): [BT Setting State] State =12
I/InputMethodManagerService(  772): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
D/bt_vendor( 6576): op for 7
D/bt_upio ( 6576): BT_WAKE is asserted already
,D/BluetoothTile( 1185):  onBluetoothStateChange:
,D/bt_vendor( 6576): op for 7
D/bt_upio ( 6576): BT_WAKE is asserted already
,D/bt_vendor( 6576): op for 7
D/bt_upio ( 6576): BT_WAKE is asserted already
,D/BluetoothHeadset( 1401): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@a61a041, true
D/BluetoothHeadset( 1401): registerMessageListener
,D/bt_vendor( 6576): op for 7
D/bt_upio ( 6576): BT_WAKE is asserted already
,D/bt_vendor( 6576): op for 7
D/bt_upio ( 6576): BT_WAKE is asserted already
I/SamsungIME( 1697): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothManager( 6739): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothTile( 1185):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1185): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,W/DriveInitializer( 1747): Awaiting to be initialized
D/bt_vendor( 6576): op for 7
D/bt_upio ( 6576): BT_WAKE is asserted already
,D/HeadsetService( 6576): registerMessageListener
D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/HeadsetService( 6576): registerMessageListener
,D/bt_vendor( 6576): op for 7
D/bt_upio ( 6576): BT_WAKE is asserted already
D/HeadsetStateMachine( 6576): Disconnected process message: 70
I/Telecom ( 1401): BluetoothPhoneService: updateHeadsetWithCallState
,D/HeadsetStateMachine( 6576): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2fe6e76c
I/Telecom ( 1401): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/bt_vendor( 6576): op for 7
D/bt_upio ( 6576): BT_WAKE is asserted already
I/BluetoothPbapService( 6576): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,D/bt_vendor( 6576): op for 7
D/bt_upio ( 6576): BT_WAKE is asserted already
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/HeadsetStateMachine( 6576): Disconnected process message: 9
,D/bt_vendor( 6576): op for 7
D/bt_upio ( 6576): BT_WAKE is asserted already
D/HeadsetStateMachine( 6576): mNumActive: 0 mNumHeld: 0 mCallState: 6
,D/BluetoothTile( 1185):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 1185): onStateChanged: Bluetooth
,D/bt_vendor( 6576): op for 7
D/bt_upio ( 6576): BT_WAKE is asserted already
,I/ActivityManager(  772): Killing 6168:com.samsung.android.app.watchmanagerstub/u0a126 (adj 13): bgCount ##41
,D/StatusBarManagerService(  772): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
D/bt_vendor( 6576): op for 7
D/bt_upio ( 6576): BT_WAKE is asserted already
D/StatusBarManagerService(  772): setIconVisibility slot=bluetooth visible=true
,D/bt_vendor( 6576): op for 7
D/bt_upio ( 6576): BT_WAKE is asserted already
,D/bt_vendor( 6576): op for 7
D/bt_upio ( 6576): BT_WAKE is asserted already
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PhoneStatusBar( 1185): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
,W/DriveInitializer( 1747): Background init thread started
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/audio_hw_primary(  295): adev_set_parameters: enter: A2dpSuspended=false
V/voice   (  295): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  295): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  295): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  295): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  295): audio_extn_hfp_set_parameters: enter
,V/audio_hw_primary(  295): adev_set_parameters: exit
E/HeadsetStateMachine( 6576): terminateScoUsingVirtualVoiceCall:No present call to terminate
,I/BluetoothPbapService( 6576): Handler(): got msg=1
D/BluetoothManagerService(  772): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/SecContentProvider(  772): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,V/BluetoothPbapService( 6576): PBAP Service initSocket try: 0
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BluetoothMapMasInstance( 6576): set MAP SDP message type : 1
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 1747): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,W/BluetoothAdapter( 6576): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6576): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
D/BluetoothSocket( 6576): bindListen(), new LocalSocket 
D/BluetoothSocket( 6576): bindListen(), new LocalSocket.getInputStream() 
D/bt_vendor( 6576): op for 7
D/bt_upio ( 6576): BT_WAKE is asserted already
D/BluetoothSocket( 6576): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39b4b804
D/BluetoothSocket( 6576): channel: 5
,W/BluetoothAdapter( 6576): getBluetoothService() called with no BluetoothManagerCallback
,D/PushModule( 7220): [PushClientApplication] (main) PushClientApplication.onCreate()
,I/PushModule( 7220): [PushClientApplication] (main) PushModule version: 0.9.01.12
,D/bt_vendor( 6576): op for 7
D/bt_upio ( 6576): BT_WAKE is asserted already
,D/BluetoothSocket( 6576): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 6576): bindListen(), new LocalSocket 
D/BluetoothSocket( 6576): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6576): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@391bc1ed
D/BluetoothSocket( 6576): channel: 19
,D/BluetoothPbapService( 6576): PBAP Socket is BluetoothServerSocket
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PushModule( 7220): [PushClientApplication] (main) Discovered public push client. disable in app push client.
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChatON  ( 7220): [1][isApplicationInstalled] com.android.mms was installed
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/DriveInitializer( 1747): Background init thread ended
,I/PhenotypeConfigurator( 1481): Scheduling Phenotype for one-off execution 2302 seconds from now (1450226428177)
,W/ContextImpl( 7220): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
,W/ActivityManager(  772): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,D/GetConfigurationSnapshotOperation( 1481): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ChatON  ( 7220): [1][a] ChatONV isn't installed.
,D/ChatON  ( 7220): [1][a] ChatONVPlugIn.isAvailable()
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,I/PhenotypeFlagCommitter( 1481): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1481): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7264): MountEmulatedStorage()
E/Zygote  ( 7264): v2
I/libpersona( 7264): KNOX_SDCARD checking this for 10146
I/libpersona( 7264): KNOX_SDCARD not a persona
,I/ActivityManager(  772): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7264 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7264): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7264): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7264): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7264): TimaSignature is unavailable
,D/ActivityThread( 7264): Added TimaKeyStore provider
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  772): Killing 6183:com.samsung.helphub/1000 (adj 13): bgCount ##41
,D/ResourcesManager( 7264): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LocationManagerService(  772): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7264): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 5991): [RC New] Execute method=[GET] start
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7264): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7264): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7264): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1481): (HTTPLog)-Static: isSBSettingEnabled false
,I/SA      ( 5991): [RC New] Security=[true]
,I/System.out( 5991): Thread-971(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5991): Thread-971(ApacheHTTPLog):isShipBuild true
,I/System.out( 5991): Thread-971(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1481): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1481): Tagging socket 78 with tag 1000120100000000{268440065,0} uid -1, pid: 1481, getuid(): 10015
,I/qtaguid ( 1481): Tagging socket 81 with tag 1000120100000000{268440065,0} uid -1, pid: 1481, getuid(): 10015
,I/WebViewFactory( 7264): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 7264): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7264): Loading: webviewchromium
,I/LibraryLoader( 7264): Time to load native libraries: 6 ms (timestamps 2232-2238)
I/LibraryLoader( 7264): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7264): Binding Chromium to main looper Looper (main, tid 1) {35d4d909}
,I/LibraryLoader( 7264): Expected native library version number "",actual native library version number ""
,I/chromium( 7264): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,D/LocationManagerService(  772): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1481): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1481): Tagging socket 78 with tag 1000120100000000{268440065,0} uid -1, pid: 1481, getuid(): 10015
,I/BrowserStartupController( 7264): Initializing chromium process, renderers=0
,W/art     ( 7264): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7264): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7264): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46780 len=2953
,I/chromium( 7264): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229536 len:643667
,I/CalendarProvider2( 7132): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/AudioManagerAndroid( 7264): Requires BLUETOOTH permission
,I/Adreno-EGL( 7264): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7264): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7264): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7264): Local Branch: mybranch5813579
I/Adreno-EGL( 7264): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7264): Local Patches: NONE
I/Adreno-EGL( 7264): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,D/LocationManagerService(  772): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1481): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1481): Tagging socket 78 with tag 1000120100000000{268440065,0} uid -1, pid: 1481, getuid(): 10015
,I/NSApplication( 7264): Starting up...
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  772): Killing 6222:com.samsung.android.snote:provider/u0a168 (adj 13): bgCount ##41
,D/LocationManagerService(  772): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7321): MountEmulatedStorage()
E/Zygote  ( 7321): v2
I/libpersona( 7321): KNOX_SDCARD checking this for 10158
I/libpersona( 7321): KNOX_SDCARD not a persona
,I/ActivityManager(  772): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7321 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  772): Killing 6240:com.sec.kidsplat.installer/u0a189 (adj 13): bgCount ##41
,I/SELinux ( 7321): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/System.out( 1481): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1481): Tagging socket 78 with tag 1000120100000000{268440065,0} uid -1, pid: 1481, getuid(): 10015
,I/SELinux ( 7321): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7321): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7321): TimaSignature is unavailable
,D/ActivityThread( 7321): Added TimaKeyStore provider
,D/ResourcesManager( 7321): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7321): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7321): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7321): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7321): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7321): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7321): PeriphStartReceiver.onReceive - no need to start
,D/LocationManagerService(  772): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  772): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  772): exchangeData() failure , invalid userId
,D/RCPManagerService(  772): exchangeData() failure , invalid userId
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6541): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6541): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6541): StateMachine : Current State = 1
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6541): StateMachine : Changed Current State = 1
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  772): Killing 6265:com.sec.android.app.samsungapps/u0a45 (adj 13): bgCount ##41
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7336): MountEmulatedStorage()
,E/Zygote  ( 7336): v2
I/libpersona( 7336): KNOX_SDCARD checking this for 10200
I/libpersona( 7336): KNOX_SDCARD not a persona
,I/ActivityManager(  772): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7336 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7336): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7336): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7336): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/System.out( 1481): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1481): Tagging socket 78 with tag 1000120100000000{268440065,0} uid -1, pid: 1481, getuid(): 10015
,D/TimaKeyStoreProvider( 7336): TimaSignature is unavailable
,D/ActivityThread( 7336): Added TimaKeyStore provider
,D/ResourcesManager( 7336): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,I/ActivityManager(  772): Killing 5500:com.android.vending/u0a33 (adj 13): bgCount ##41
,I/iu.SyncManager( 1747): SYNC; picasa accounts
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 5991): [RC New] [v2liruge] api execute + 620
I/SA      ( 5991): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5991): AsyncTask #1 calls detatch()
,D/NetworkLogImpl( 1747): Loaded NetworkSpeedPredictor
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/iu.Environment( 1747): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/SA      ( 5991): [TPMU] getNetworkMcc : 
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 5991): [SCU] saveMccToPreferece Start
D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 5991): [SCU] RegionMCC : 260
,I/SA      ( 5991): [SSP] query invoked
,I/iu.UploadsManager( 1747): num queued entries: 0
,I/iu.UploadsManager( 1747): num updated entries: 0
,I/SA      ( 5991): [TPMU] GetMccFromDB : null
I/SA      ( 5991): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5991): [SCU] saveMccToPreferece End
,I/SA      ( 5991): [RC New] executeRequest [v2liruge] end. 675
I/SA      ( 5991): [RC New] Execute end
I/SA      ( 5991): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5991): [OR] GetMyCountryZoneTask Success
,I/iu.SyncManager( 1747): NEXT; no task
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7358): MountEmulatedStorage()
E/Zygote  ( 7358): v2
I/libpersona( 7358): KNOX_SDCARD checking this for 10045
I/libpersona( 7358): KNOX_SDCARD not a persona
,I/ActivityManager(  772): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7358 uid=10045 gids={50045, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7358): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7358): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7358): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7358): TimaSignature is unavailable
,D/ActivityThread( 7358): Added TimaKeyStore provider
,D/ResourcesManager( 7358): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7358): notifyNetworkActivated
,W/ContextImpl( 7358): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  772): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 1481): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/GCM     ( 1481): GCM config loaded
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3156): [com.wssyncmldm.lllIlIlIIIllIIlIllIl(350/onReceive)] FotaPostpone callback received
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7358): AutoUpdateManager:IDLE:execute
D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7358): execute::IDLE:EXECUTE
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7358): exit::IDLE
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7358): entry::NETWORK_CHECK
,I/DBG_DM  ( 3156): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 3
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7358): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7358): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7358): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7358): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7358): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7358): entry::SUCCESS
D/hcjo    ( 7358): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/LightsService(  772): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 772) 
,D/LightsService(  772): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/hcjo    ( 7358): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,E/LightSensor(  772): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/hcjo    ( 7358): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7358): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/DBG_DM  ( 3156): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 0
D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7358): exit::SUCCESS
D/InitializeManagerStateMachine( 7358): entry::IDLE
,D/SensorManager(  772): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,I/DBG_DM  ( 3156): [IIllIlIIlIlllIIllIII(741/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/DBG_DM  ( 3156): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1273/handleMessage)] event ->220
D/PersonaManager( 1185): isKioskContainerExistOnDevice
D/PersonaManager( 1185): isKioskContainerExistOnDevice
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3156): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 3156): [com.wssyncmldm.XDMService(876/IIIIllIlIIlIIIIlllIl)] 
,D/PanelView( 1185): There is/are notification(s) 
,I/ActivityManager(  772): Killing 6288:com.sec.android.widgetapp.digitalclock/u0a109 (adj 13): bgCount ##41
D/PanelView( 1185): There is/are notification(s) 
,W/ContextImpl( 1309): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/DBG_DM  ( 3156): [com.wssyncmldm.db.file.XDB(4994/IIIlllIlIIlllIIIIllI)] Get Autoinstall status : false
,I/DBG_DM  ( 3156): [IIllIlIIlIlllIIllIII(695/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,I/DBG_DM  ( 3156): [com.wssyncmldm.XDMService(638/llllIIIllIlIIIIllllI)] 
,E/DBG_DM  ( 3156): [com.wssyncmldm.XDMService(646/llllIIIllIlIIIIllllI)] didn't register
,E/DBG_DM  ( 3156): [com.wssyncmldm.XDMService(647/llllIIIllIlIIIIllllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@3f20907
,I/DBG_DM  ( 3156): [com.wssyncmldm.XDMService(819/IllIlIIIIlIIlIIIllIl)] Idle Screen : false
,I/DBG_DM  ( 3156): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/LocalBluetoothProfileManager( 1309): Adding local A2DP profile
,D/LocalBluetoothProfileManager( 1309): Adding local HEADSET profile
,E/BluetoothHeadset( 1309): BTStateChangeCB is registed
,E/BluetoothHeadset( 1309): BluetoothHeadset service is binded
,W/ContextImpl( 1309): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/Bluetoothsap( 1309): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 1309): PANU : true
,D/LocalBluetoothProfileManager( 1309): Adding local MAP profile
,D/BluetoothMap( 1309): Create BluetoothMap proxy object
,W/LocalBluetoothProfileManager( 1309): Warning: SAP profile was previously added.
,D/LocalBluetoothProfileManager( 1309): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1309): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1309): onReceive
,D/BluetoothA2dp( 1309): Proxy object connected
,D/A2dpProfile( 1309): Bluetooth service connected
,D/BluetoothAdapterService( 6576): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@384e72ba
D/BtConfig.SecureMode( 6576): isSecureModeOn:false
,D/HeadsetProfile( 1309): Bluetooth service connected
,D/Bluetoothsap( 1309): BluetoothSAP Proxy object connected
,D/SapProfile( 1309): Bluetooth service connected
,D/Bluetoothsap( 1309): getConnectedDevices()
,D/BluetoothInputDevice( 1309): Proxy object connected
,D/AuthorizationBluetoothService( 1481): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/HidProfile( 1309): Bluetooth service connected
,D/BluetoothPan( 1309): BluetoothPAN Proxy object connected
,D/PanProfile( 1309): Bluetooth service connected
,D/BluetoothMap( 1309): Proxy object connected
,D/MapProfile( 1309): Bluetooth service connected
,D/BluetoothPbap( 1309): Proxy object connected
D/PbapServerProfile( 1309): Bluetooth service connected
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7383): MountEmulatedStorage()
,E/Zygote  ( 7383): v2
I/libpersona( 7383): KNOX_SDCARD checking this for 10171
I/libpersona( 7383): KNOX_SDCARD not a persona
,I/ActivityManager(  772): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7383 uid=10171 gids={50171, 9997} abi=armeabi-v7a
,I/art     (  772): Explicit concurrent mark sweep GC freed 37069(2MB) AllocSpace objects, 1(16KB) LOS objects, 17% free, 37MB/45MB, paused 1.522ms total 102.904ms
,I/DBG_DM  ( 3156): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/SELinux ( 7383): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7383): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7383): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/SecContentProvider(  772): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/SecContentProvider2(  772): uri = 14 selection = getSealedState
D/SecContentProvider2(  772): mCursor = null
,W/BluetoothAdapter( 6576): getBluetoothService() called with no BluetoothManagerCallback
,D/TimaKeyStoreProvider( 7383): TimaSignature is unavailable
,D/ActivityThread( 7383): Added TimaKeyStore provider
,D/BluetoothSocket( 6576): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
,D/bt_vendor( 6576): op for 7
D/BluetoothSocket( 6576): bindListen(), new LocalSocket 
D/bt_upio ( 6576): BT_WAKE is asserted already
D/BluetoothSocket( 6576): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6576): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3bb2470f
D/BluetoothSocket( 6576): channel: 12
I/BtOppRfcommListener( 6576): Accept thread started.
,D/ApplicationPolicy(  772): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy(  772): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager(  772): showStatusBarByNotification() mOpenByNotification=false
,I/DBG_DM  ( 3156): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
,D/ResourcesManager( 7383): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,I/DBG_DM  ( 3156): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,W/ResourcesManager( 7383): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7383): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/SMD     (  288): DCD ON
,D/OpenGLRenderer( 3156): Render dirty regions requested: true
,D/KnoxNotification( 1185): ----- inflateViews : modified publicViewLocal -----
,D/Atlas   ( 3156): Validating map...
,I/DBG_DM  ( 3156): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 3156): [com.wssyncmldm.ui.XUIFotaPostponeActivity(378/lllIlIlIIIllIIlIllIl)] No idle Postpone
,I/DBG_DM  ( 3156): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
D/KnoxNotification( 1185): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1185): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 1185): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@230baec8
D/PersonaManager( 1185): isKioskContainerExistOnDevice
D/PersonaManager( 1185): isKioskContainerExistOnDevice
,D/PanelView( 1185): There is/are notification(s) 
,D/PanelView( 1185): There is/are notification(s) 
,I/SurfaceFlinger(  254): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService(  772): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=772
,I/Adreno-EGL( 3156): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 3156): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 3156): Build Date: 11/19/14 Wed
I/Adreno-EGL( 3156): Local Branch: mybranch5813579
I/Adreno-EGL( 3156): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 3156): Local Patches: NONE
I/Adreno-EGL( 3156): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,I/OpenGLRenderer( 3156): Initialized EGL, version 1.4
,I/ActivityManager(  772): Killing 6303:com.sec.android.widgetapp.dualclockdigital/u0a115 (adj 13): bgCount ##41
,I/OpenGLRenderer( 3156): HWUI protection enabled for context ,  &this =0xaee22088 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 3156): Enabling debug mode 0
,D/LightsService(  772): [SvcLED]  onSensorChanged::light value = 0
E/LightSensor(  772): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  772): unregisterListener ::   
D/LightsService(  772): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/bt_upio ( 6576): ..proc_btwrite_timeout..
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5904): mConnectivityHandler : connected
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 5904): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 5904): ================================================
,I/CSTORAGE( 5904):  CSTORAGE_SKM_LIB v1.0.6
I/CSTORAGE( 5904): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5904): [GetString-S]
,E/art     ( 5904): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 5904): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5904): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5904): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5904): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5904): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5904): [ensureRegistration] - No Samsung account
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/bt_vendor( 6576): op for 7
I/dhcpcd  ( 6758): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  288): DCD ON,
,I/SurfaceFlinger(  254): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger(  254): id=15 Removed Uoast (-2/9)
,D/PowerManagerService(  772): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 772) eventTime = 176780
,D/PowerManagerService(  772): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=772 (0x0)
D/PowerManagerService(  772): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=772, ws=WorkSource{1000}) (elapsedTime=3492)
,I/GAV4    ( 7264): Thread[GAThread,5,main]: No campaign data found.
,D/btif_config_util( 6576): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/dhcpcd  ( 6758): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 6758): wlan0: no IPv6 Routers available
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): stay LED for fully charged
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/SSRM:n  (  772): SIOP:: AP = 330, PST = 314, CUR = 450
,E/SMD     (  288): DCD ON
,D/PreloadUpdateManagerStateMachine( 7358): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7358): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7358): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7358): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7358): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7358): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7358): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7358): entry::IDLE
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/PowerManagerService(  772): [PWL] Off : 75s ago
,E/SMD     (  288): DCD ON
,I/ActivityManager(  772): Waited long enough for: ServiceRecord{3010ebb7 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  (  772): SIOP:: AP = 310, PST = 314, CUR = 450
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 6
,E/SMD     (  288): DCD ON
,V/AlarmManager(  772): waitForAlarm result :4
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): stay LED for fully charged
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,V/AlarmManager(  772): waitForAlarm result :4
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 300, PST = 312, CUR = 450
,I/ClearcutLoggerApiImpl( 1481): disconnect managed GoogleApiClient
,E/SMD     (  288): DCD ON
,V/AlarmManager(  772): waitForAlarm result :8
,E/SMD     (  288): DCD ON,
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  772): SIOP:: AP = 300, PST = 310, CUR = 450
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  772): [PWL] Off : 105s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 290, PST = 308, CUR = 450
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/Watchdog(  772): !@Sync 7
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,V/AlarmManager(  772): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): stay LED for fully charged
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityThread( 1747): Failed to find provider info for com.android.contacts.metadata
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  772): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 200254, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  772): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 291134, reason: UserStart
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  772): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  772): mCursor = null
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 300, PST = 308, CUR = 450
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  772): SIOP:: AP = 290, PST = 307, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  772): [PWL] Off : 140s ago
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:n  (  772): SIOP:: AP = 290, PST = 306, CUR = 450
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 8
,E/SMD     (  288): DCD ON
,V/AlarmManager(  772): waitForAlarm result :4
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): stay LED for fully charged
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 290, PST = 304, CUR = 450
,E/SMD     (  288): DCD ON
,V/AlarmManager(  772): waitForAlarm result :8
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:n  (  772): SIOP:: AP = 290, PST = 299, CUR = 450
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/BatteryService(  772): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/SSRM:n  (  772): SIOP:: AP = 290, PST = 295, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 9
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  772): [PWL] Off : 180s ago
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,E/SMD     (  288): DCD ON
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/BatteryService(  772): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/SSRM:n  (  772): SIOP:: AP = 290, PST = 293, CUR = 450
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/BatteryService(  772): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/SSRM:n  (  772): SIOP:: AP = 290, PST = 292, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  772): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/SSRM:n  (  772): SIOP:: AP = 290, PST = 291, CUR = 450
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,D/TimaService(  772): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  772): TimaServiceHandler.handleMessage what =1
,D/TimaService(  772): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  772): initializing...
,I/TLC_TIMA_PKM_initialize(  772): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  772): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  772): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  772): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  772): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  772): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  772): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  772): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  772): App is not loaded in QSEE
,D/QSEECOMAPI: (  772): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  772): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  772): Trustlet response is completed
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  772): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  772): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  772): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  772): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  772): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  288): DCD ON
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 290, PST = 290, CUR = 450
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  772): waitForAlarm result :4
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): stay LED for fully charged
,I/ActivityManager(  772): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7462 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,E/Zygote  ( 7462): MountEmulatedStorage()
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,E/Zygote  ( 7462): v2
I/libpersona( 7462): KNOX_SDCARD checking this for 10096
I/libpersona( 7462): KNOX_SDCARD not a persona
I/MotionRecognitionService(  772): Plugged
I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6576): Disconnected process message: 10
I/SELinux ( 7462): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,I/SELinux ( 7462): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7462): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7462): TimaSignature is unavailable
,D/ActivityThread( 7462): Added TimaKeyStore provider
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ResourcesManager( 7462): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  772): Killing 5648:com.sec.android.widgetapp.activeapplicationwidget/u0a182 (adj 13): bgCount ##41
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  772): [PWL] Off : 225s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:n  (  772): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 11
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:n  (  772): SIOP:: AP = 290, PST = 290, CUR = 450
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  (  772): SIOP:: AP = 290, PST = 290, CUR = 450
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 12
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 289, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  772): Plugged
I/MotionRecognitionService(  772): setPowerConnected  = true
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/AlarmManager(  772): waitForAlarm result :8
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/PowerManagerService(  772): [PWL] Off : 275s ago
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD ON
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 288, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 287, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 13
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 286, CUR = 450
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 285, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 284, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 6454): Connected to the server!
I/jxcore-log( 6454): 
,I/chromium( 6454): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 14
,E/SMD     (  288): DCD ON
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  772): [PWL] Off : 330s ago
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 283, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 282, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD ON,
,E/Watchdog(  772): !@Sync 15
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/bootchecker(  322): bootchecker wake up!!
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  772): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 16
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  772): [PWL] Off : 390s ago
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  772): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD ON
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryService(  772): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 17
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryService(  772): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 18
,E/SMD     (  288): DCD ON
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,V/AlarmManager(  772): waitForAlarm result :8
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/BatteryService(  772): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,I/PowerManagerService(  772): [PWL] Off : 455s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/BatteryService(  772): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,I/Atfwd_Daemon(  326): Stop the daemon....
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/BatteryService(  772): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 19
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  772): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/BatteryService(  772): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/TimaService(  772): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  772): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  772): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): setPowerConnected  = true
D/BatteryService(  772): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel(  772): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  772): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  772): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  772): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON,
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450,
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  772): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,I/ActivityManager(  772): Killing 6059:com.sec.android.provider.badge/u0a92 (adj 13): bgCount ##41
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/BatteryService(  772): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,I/PowerManagerService(  772): [PWL] Off : 525s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 21
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 22
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  772): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  772): !@Sync 23
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  772): [PWL] Off : 600s ago
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  772): stay LED for fully charged
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryService(  772): stay LED for fully charged
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryService(  772): stay LED for fully charged
,E/Watchdog(  772): !@Sync 24
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  772): stay LED for fully charged
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  772): stay LED for fully charged
,E/Watchdog(  772): !@Sync 25
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  772): stay LED for fully charged
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  772): [PWL] Off : 680s ago
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 26
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,V/AlarmManager(  772): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): stay LED for fully charged
,D/LightsService(  772): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  772): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  772): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 1747): Aggregate from 1450225201094 (log), 1450225201094 (data)
,D/LightsService(  772): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  772): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  772): unregisterListener ::   
D/LightsService(  772): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,V/AlarmManager(  772): waitForAlarm result :8
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 27
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryService(  772): stay LED for fully charged
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 28
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  772): [PWL] Off : 765s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 29
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450,
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService(  772): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  772): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  772): TimaServiceHandler.handleMessage what =1
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel(  772): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  772): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  772): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  772): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,V/AlarmManager(  772): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 31
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  772): Plugged
I/MotionRecognitionService(  772): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  772): stay LED for fully charged
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  772): [PWL] Off : 855s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 32
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,V/AlarmManager(  772): waitForAlarm result :8
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/Watchdog(  772): !@Sync 33
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  772): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/Watchdog(  772): !@Sync 34
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/BatteryService(  772): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/BatteryService(  772): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  772): [PWL] Off : 950s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/Watchdog(  772): !@Sync 35
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/Watchdog(  772): !@Sync 36
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  772): !@Sync 37
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/BatteryService(  772): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  772): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/Watchdog(  772): !@Sync 38
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  772): [PWL] Off : 1050s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  772): !@Sync 39
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  772): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  772): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/TimaService(  772): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  772): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  772): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  772): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  772): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  772): Updating Usage Statistics in DB @ 1450227470218
,I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
,W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
,W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
,W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
,W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
,W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
,W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
,W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  772): ::getAppControlDB: Exception to create DB
W/System.err(  772): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  772): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  772): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  772): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  772): Done Updating Usage Statistics in DB @ 1450227470400
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): stay LED for fully charged
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): Plugged
I/MotionRecognitionService(  772): setPowerConnected  = true
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  772): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel(  772): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  772): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  772): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  772): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  772): !@Sync 41
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  772): [PWL] Off : 1155s ago
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10,
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  772): !@Sync 42
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 43
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 44
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 45
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  772): [PWL] Off : 1265s ago
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryService(  772): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 46
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 47
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  772): stay LED for fully charged
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 48
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 49
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  772): [PWL] Off : 1380s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/TimaService(  772): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  772): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  772): TimaServiceHandler.handleMessage what =1
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel(  772): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  772): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  772): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  772): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,V/AlarmManager(  772): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/LightsService(  772): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  772): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  772): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/LightsService(  772): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  772): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  772): unregisterListener ::   
,D/LightsService(  772): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,V/AlarmManager(  772): waitForAlarm result :8
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 51
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/BatteryService(  772): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 52
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/BatteryService(  772): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  772): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 53
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  772): Plugged
I/MotionRecognitionService(  772): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,I/PowerManagerService(  772): [PWL] Off : 1500s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  772): stay LED for fully charged
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  772): stay LED for fully charged
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 54
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  772): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 55
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 56
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): Plugged
I/MotionRecognitionService(  772): setPowerConnected  = true
,D/BatteryService(  772): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/BatteryService(  772): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 57
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,I/PowerManagerService(  772): [PWL] Off : 1625s ago
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): stay LED for fully charged
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 58
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 59
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  288): DCD ON
,D/NetworkStatsFactory(  772): UpdateStatsForKnox
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  288): DCD ON
,D/TimaService(  772): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  772): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService(  772): TimaServiceHandler.handleMessage what =1
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel(  772): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  772): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  772): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  772): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): Plugged
I/MotionRecognitionService(  772): setPowerConnected  = true
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,V/AlarmManager(  772): waitForAlarm result :4
,V/NetworkStats(  772): performPollLocked(flags=0x3)
,D/NtpTrustedTime(  772): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  772): UpdateStatsForKnox
,D/ConnectivityService(  772): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): stay LED for fully charged
,V/NetworkStats(  772): performPollLocked() took 49ms
,D/NtpTrustedTime(  772): currentTimeMillis() cache hit
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/ProcessStatsService(  772): Prepared write state in 18ms
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/NtpTrustedTime(  772): currentTimeMillis() cache hit
,D/NtpTrustedTime(  772): currentTimeMillis() cache hit
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  772): OOI=Alarm{b2ddaf6 type 0 when 1450229890533 com.google.android.gms}
,V/GLSActivity( 1481): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  772): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1481): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/System.out( 1481): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1481): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1481): Tagging socket 63 with tag 1000040100000000{268436481,0} uid 10015, pid: 1481, getuid(): 10015
,I/qtaguid ( 1481): Tagging socket 69 with tag 1000040100000000{268436481,0} uid 10015, pid: 1481, getuid(): 10015
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 61
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON,
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  772): [PWL] Off : 1755s ago
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 62
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,V/AlarmManager(  772): waitForAlarm result :8
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/Watchdog(  772): !@Sync 63
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  772): !@Sync 64
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  772): Plugged
I/MotionRecognitionService(  772): setPowerConnected  = true
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  772): !@Sync 65
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD ON
,D/SSRM:n  (  772): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  288): DCD ON
,E/SMD     (  288): DCD ON
,D/BatteryService(  772): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  772): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  772): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450,
,D/BatteryService(  772): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  772): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  772): setPowerConnected  = true
,V/HeadsetService( 6576): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6576): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  772): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7699): 
D/AndroidRuntime( 7699): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7699): CheckJNI is OFF
D/AndroidRuntime( 7699): readGMSProperty: start
D/AndroidRuntime( 7699): readGMSProperty: already setted!!
D/AndroidRuntime( 7699): readGMSProperty: end
D/AndroidRuntime( 7699): addProductProperty: start
E/AffinityControl( 7699): AffinityControl: registerfunction enter
D/AndroidRuntime( 7699): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  772): START PACKAGE DELETE: observer{100203397}
D/PackageManager(  772): pkg{<packageName>}
D/PackageManager(  772): user{0}
D/PackageManager(  772): caller{2000}
D/PackageManager(  772): flags{3}
D/PersonaManagerService(  772): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  772): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  772): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  772): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  772): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService(  772): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager(  772): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  772): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  772): getApplicationUninstallationEnabled
D/ApplicationPolicy(  772): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  772): !@killApplicatoin: 10293, uninstall pkg
I/ActivityManager(  772): Force stopping com.test.thalitest appid=10293 user=-1: uninstall pkg
I/ActivityManager(  772): Killing 6454:com.test.thalitest/u0a293 (adj 0): stop com.test.thalitest
E/SMD     (  288): DCD ON
W/PackageSettings(  772): Skipping PackageSetting{2cfb1fc9 com.example.hello/10292} due to missing metadata
I/WindowState(  772): WIN DEATH: Window{25164538 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  254): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  254): id=13 Removed NainActivit (-2/8)
D/PointerIcon(  772): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  772): setMouseCustomIcon IconType is same.101
D/PointerIcon(  772): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  772): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager(  772): Killing 5480:com.google.android.apps.plus/u0a155 (adj 11): empty for 1813s
I/ActivityManager(  772): Killing 6583:tv.peel.samsung.app/u0a152 (adj 11): empty for 1813s
I/ActivityManager(  772): Killing 7264:com.google.android.apps.magazines/u0a146 (adj 11): empty for 1814s
I/ActivityManager(  772): Killing 6941:com.android.chrome/u0a104 (adj 11): empty for 1814s
I/ActivityManager(  772): Killing 7220:com.sec.chaton/u0a102 (adj 11): empty for 1814s
I/ActivityManager(  772): Killing 7204:com.sec.knox.bridge/1000 (adj 11): empty for 1814s
I/ActivityManager(  772): Killing 7132:com.android.providers.calendar/u0a51 (adj 11): empty for 1814s
I/ActivityManager(  772): Killing 7177:com.samsung.android.scloud.backup/u0a74 (adj 11): empty for 1814s
I/ActivityManager(  772): Killing 5991:com.osp.app.signin/u0a50 (adj 11): empty for 1814s
I/ActivityManager(  772): Killing 7153:com.qualcomm.timeservice/1000 (adj 11): empty for 1814s
I/ActivityManager(  772): Killing 5179:com.sec.android.gallery3d/u0a53 (adj 11): empty for 1815s
I/ActivityManager(  772): Killing 7078:com.policydm/1000 (adj 13): empty for 1815s
I/ActivityManager(  772): Killing 5449:com.sec.android.app.controlpanel/u0a134 (adj 13): empty for 1815s
I/ActivityManager(  772): Killing 7052:com.sec.esdk.elm/u0a116 (adj 13): empty for 1815s
I/ActivityManager(  772): Killing 6975:com.sec.android.soagent/u0a42 (adj 13): empty for 1815s
I/ActivityManager(  772): Killing 6739:com.vlingo.midas/u0a38 (adj 13): empty for 1815s
I/ActivityManager(  772): Killing 7037:com.samsung.android.app.pinboard:tagService/u0a36 (adj 13): empty for 1815s
I/ActivityManager(  772): Killing 6924:com.samsung.klmsagent/u0a23 (adj 13): empty for 1815s
I/ActivityManager(  772): Killing 6883:com.sec.android.fotaclient/u0a14 (adj 13): empty for 1815s
I/ActivityManager(  772): Killing 7019:com.sec.android.app.clockpackage/u0a106 (adj 13): empty for 1815s
I/ActivityManager(  772): Killing 7002:com.samsung.android.scloud.sync/u0a76 (adj 13): empty for 1816s
I/ActivityManager(  772): Killing 6012:com.android.mms/u0a55 (adj 13): empty for 1816s
I/ActivityManager(  772): Killing 4118:com.sec.android.app.shealth/u0a40 (adj 13): empty for 1816s
I/ActivityManager(  772): Killing 6958:com.sec.android.diagmonagent/1000 (adj 13): empty for 1816s
I/ActivityManager(  772): Killing 6901:com.sec.android.cloudagent/u0a4 (adj 15): empty for 1816s
I/ActivityManager(  772): Killing 5904:com.sec.pcw.device/1000 (adj 15): empty for 1817s
I/ActivityManager(  772): Killing 6205:com.samsung.android.snote/u0a168 (adj 15): empty for 1817s
I/ActivityManager(  772): Killing 6697:com.samsung.shareshot/u0a192 (adj 15): empty for 1820s
I/ActivityManager(  772): Killing 6713:com.samsung.android.app.FileShareServer/u0a88 (adj 15): empty for 1820s
I/ActivityManager(  772):   Force finishing activity ActivityRecord{3e1a00a2 u0 com.test.thalitest/.MainActivity t3}
D/FocusedStackFrame(  772): Set to : 0
W/ActivityManager(  772): Spurious death for ProcessRecord{3583cdda 6454:com.test.thalitest/u0a293}, curProc for 6454: null
W/libprocessgroup(  772): failed to open /acct/uid_10038/pid_6739/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_10155/pid_5480/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_10152/pid_6583/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_10146/pid_7264/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_10104/pid_6941/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_10102/pid_7220/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_1000/pid_7204/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_10051/pid_7132/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_10074/pid_7177/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_10050/pid_5991/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_1000/pid_7153/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_10053/pid_5179/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_1000/pid_7078/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_10134/pid_5449/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_10116/pid_7052/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_10042/pid_6975/cgroup.procs: No such file or directory
D/CountryDetector(  772): No listener is left
W/libprocessgroup(  772): failed to open /acct/uid_10040/pid_4118/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_10036/pid_7037/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_10023/pid_6924/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_10014/pid_6883/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_10106/pid_7019/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_10076/pid_7002/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_10055/pid_6012/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_1000/pid_6958/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_10004/pid_6901/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_1000/pid_5904/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_10168/pid_6205/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_10192/pid_6697/cgroup.procs: No such file or directory
W/libprocessgroup(  772): failed to open /acct/uid_10088/pid_6713/cgroup.procs: No such file or directory
D/ConnectivityService(  772): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  772): Force stopping com.test.thalitest appid=10293 user=0: pkg removed
I/art     ( 1620): Explicit concurrent mark sweep GC freed 540(38KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 18MB/31MB, paused 380us total 21.327ms
D/ResourcesManager(  772): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader(  772): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager(  772): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
W/GeofencerStateMachine( 1481): Ignoring removeGeofence because network location is disabled.
E/SamsungIME( 1697): mOCRHelper is null
D/ResourcesManager(  772): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
E/Zygote  ( 7735): MountEmulatedStorage()
E/Zygote  ( 7735): v2
I/libpersona( 7735): KNOX_SDCARD checking this for 10023
I/libpersona( 7735): KNOX_SDCARD not a persona
I/ActivityManager(  772): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7735 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
I/art     ( 1747): Explicit concurrent mark sweep GC freed 6655(383KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 22MB/30MB, paused 926us total 75.825ms
W/SQLiteConnectionPool( 1747): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/art     ( 5141): Explicit concurrent mark sweep GC freed 39725(2MB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 15MB/26MB, paused 591us total 88.585ms
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/SELinux ( 7735): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7735): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7735): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  772): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/SecContentProvider2(  772): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  772): mCursor = null
D/ResourcesManager(  772): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/TimaKeyStoreProvider( 7735): TimaSignature is unavailable
D/ActivityThread( 7735): Added TimaKeyStore provider
D/ResourcesManager(  772): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/SurfaceWidgetView( 1437): destroyHardwareResources():1072236003
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager( 7735): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
V/WindowOrientationListener(  772): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  772): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  772): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  772): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  772): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/Launcher( 1437): onRestart, Launcher: 450953350
D/Launcher( 1437): onStart, Launcher: 450953350
D/Launcher.HomeView( 1437): onStart
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
V/ActivityThread( 1437): updateVisibility : ActivityRecord{1da88548 token=android.os.BinderProxy@3bd63dd {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1741): [237392/8] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1741): [237392/8] SurfaceWidget drawing first frame
D/accuweather( 1741): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
I/SurfaceFlinger(  254): id=16 createSurf (1080x1920),1 flag=4, Mauncher
D/StatusBarManagerService(  772): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  772): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/PointerIcon(  772): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  772): setMouseCustomIcon IconType is same.101
D/PointerIcon(  772): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  772): setHoveringSpenCustomIcon IconType is same.1
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/InputMethodManagerService(  772): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService(  772): Got RemoteException sending setActive(false) notification to pid 6454 uid 10293
D/RegisteredServicesCache( 1416): empty dynamic service
W/ContextImpl(  772): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/KLMS-2.4.511: ( 7735): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/Timeline(  772): Timeline: Activity_windows_visible id: ActivityRecord{166d9547 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:1988003
D/RCPManagerService(  772): PackageReceiver onReceive()
I/HarmonyEASService(  772): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  772): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  772): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  772): Receieved: android.intent.action.PACKAGE_REMOVED
I/KLMS-2.4.511: ( 7735): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1450228244395
V/EnterpriseBillingPolicy(  772): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  772): uID is 10293
V/EnterpriseBillingPolicy(  772): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  772): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  772): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  772): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  772): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  772): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  772): getBillingProfileForVpnEngine - end - null
I/KLMS-2.4.511: ( 7735): MainReciver(): PACKAGE_REMOVED
D/TaskPersister(  772): removeObsoleteFile: deleting file=3_task.xml
I/KLMS-2.4.511: ( 7735): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  772): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/talkback/talkback.apk
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
D/EnterpriseDeviceManagerService(  772): Package has changed for user 0
D/EnterpriseDeviceManagerService(  772): Admin package name: com.google.android.gms
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/art     (  772): Explicit concurrent mark sweep GC freed 24152(1765KB) AllocSpace objects, 9(144KB) LOS objects, 17% free, 37MB/45MB, paused 7.645ms total 298.308ms
D/ResourcesManager(  772): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
E/Zygote  ( 7756): MountEmulatedStorage()
I/ActivityManager(  772): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7756 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
E/Zygote  ( 7756): v2
I/libpersona( 7756): KNOX_SDCARD checking this for 10116
I/libpersona( 7756): KNOX_SDCARD not a persona
I/ActivityManager(  772): Killing 7321:com.samsung.android.sconnect/u0a158 (adj 15): empty for 1815s
W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/PackageManager(  772): delete codoeFile: 
I/AASAUninstall(  772):  com.test.thalitest not target!
D/PackageManager(  772): result of delete: 1{100203397}
I/SELinux ( 7756): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/AndroidRuntime( 7699): Shutting down VM
I/SELinux ( 7756): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7756): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup(  772): failed to open /acct/uid_10158/pid_7321/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 7756): TimaSignature is unavailable
W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityThread( 7756): Added TimaKeyStore provider
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  772): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/ResourcesManager( 7756): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  772): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/elm:14491( 7756): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491( 7756): ELMEngine.ELMEngine( context ).
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/elm:14491( 7756): MDMBridge.setEnterpriseBridge()
D/elm:14491( 7756): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  772): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/elm:14491( 7756): ElmAgentService : onCreate()
D/elm:14491( 7756): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 7756): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 7756): MDMBridge.getInstance()
D/elm:14491( 7756): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491( 7756): MDMBridge.getAllLicenseInfoFromSDK()
W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/Maps/Maps.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
E/Zygote  ( 7773): MountEmulatedStorage()
E/Zygote  ( 7773): v2
I/libpersona( 7773): KNOX_SDCARD checking this for 10021
I/libpersona( 7773): KNOX_SDCARD not a persona
W/ResourcesManager(  772): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  772): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  772): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  772): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/ActivityManager(  772): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=7773 uid=10021 gids={50021, 9997} abi=armeabi-v7a
D/ResourcesManager(  772): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
D/ResourcesManager(  772): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  772): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  772): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  772): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
D/elm:14491( 7756): ElmAgentService : onDestroy().
I/ActivityManager(  772): Killing 6650:com.android.email/u0a186 (adj 15): empty for 1815s
I/SELinux ( 7773): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7773): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SELinux ( 7773): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  772): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  772): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/Resources(  772): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider( 7773): TimaSignature is unavailable
D/ActivityThread( 7773): Added TimaKeyStore provider
D/UsbSettingsManager(  772): clearDefaults: com.test.thalitest

```
