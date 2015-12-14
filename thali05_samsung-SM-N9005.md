#### Test 50650278e3ff7c2_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
E/SMD     (  291): DCD ON
I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/AndroidRuntime( 6354): 
D/AndroidRuntime( 6354): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6354): CheckJNI is OFF
D/AndroidRuntime( 6354): readGMSProperty: start
D/AndroidRuntime( 6354): readGMSProperty: already setted!!
D/AndroidRuntime( 6354): readGMSProperty: end
D/AndroidRuntime( 6354): addProductProperty: start
I/ServiceManager(  330): Waiting for service AtCmdFwd...
E/AffinityControl( 6354): AffinityControl: registerfunction enter
D/AndroidRuntime( 6354): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  896): inState():  stateMachine is null !!
I/PersonaManagerService(  896): PersonaId don't exist
I/ActivityManager(  896): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
I/ActivityManager(  896): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  896): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  896): mDVFSHelper.acquire()
D/FocusedStackFrame(  896): Set to : 0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6370): MountEmulatedStorage()
I/ActivityManager(  896): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6370 uid=10284 gids={50284, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6370): v2
I/libpersona( 6370): KNOX_SDCARD checking this for 10284
I/libpersona( 6370): KNOX_SDCARD not a persona
D/AndroidRuntime( 6354): Shutting down VM
D/PointerIcon(  896): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  896): setMouseCustomIcon IconType is same.101
D/PointerIcon(  896): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  896): setHoveringSpenCustomIcon IconType is same.1
I/SELinux ( 6370): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6370): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6370): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/SSRM:n  (  896): SIOP:: AP = 300, PST = 322, CUR = 450
D/TimaKeyStoreProvider( 6370): TimaSignature is unavailable
D/ActivityThread( 6370): Added TimaKeyStore provider
V/WindowOrientationListener(  896): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  896): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  896): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  896): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  896): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/SurfaceWidgetView( 1432): destroyHardwareResources():517215992
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 6370): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger(  254): id=6 Removed Mauncher (6/8)
I/SurfaceFlinger(  254): id=6 Removed Mauncher (-2/8)
V/ActivityThread( 1432): updateVisibility : ActivityRecord{5583a19 token=android.os.BinderProxy@3faa02aa {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1778): [237392/8] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1432): onTrimMemory. Level: 20
,I/WebViewFactory( 6370): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 6370): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 6370): Loading: webviewchromium
,I/LibraryLoader( 6370): Time to load native libraries: 6 ms (timestamps 9998-4)
I/LibraryLoader( 6370): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6370): Binding Chromium to main looper Looper (main, tid 1) {c9476e3}
,I/LibraryLoader( 6370): Expected native library version number "",actual native library version number ""
,I/chromium( 6370): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6370): Initializing chromium process, renderers=0
,W/art     ( 6370): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6370): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 6370): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6370): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
I/chromium( 6370): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
,D/BluetoothAdapter( 6370): 771881184: getState() :  mService = null. Returning STATE_OFF
,I/Adreno-EGL( 6370): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6370): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6370): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6370): Local Branch: mybranch5813579
I/Adreno-EGL( 6370): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6370): Local Patches: NONE
I/Adreno-EGL( 6370): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,W/chromium( 6370): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6370): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 6370): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6370): onDetachedFromWindow called when already detached. Ignoring
,W/ActivityManager(  896): Activity pause timeout for ActivityRecord{af00a8c u0 com.test.thalitest/.MainActivity t3}
,D/SystemWebViewEngine( 6370): CordovaWebView is running on device made by: samsung
,W/art     ( 6370): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6370): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 6370): performCreate Call secproduct feature valuefalse
D/Activity( 6370): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 6370): Render dirty regions requested: true
,D/Atlas   ( 6370): Validating map...
,D/ActivityManager(  896): post active user change for 0
D/KnoxTimeoutHandler(  896): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  896): handleActiveUserChange for user 0
,V/ActivityThread( 6370): updateVisibility : ActivityRecord{30c86909 token=android.os.BinderProxy@1700ded3 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger(  254): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService(  896): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  896): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  896): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon(  896): setMouseCustomIcon IconType is same.101
I/OpenGLRenderer( 6370): Initialized EGL, version 1.4
,D/PointerIcon(  896): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  896): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 6370): HWUI protection enabled for context ,  &this =0xb3b53b28 ,&mEglDisplay = 1 , &mEglConfig = 8 
,V/AlarmManager(  896): waitForAlarm result :4
,D/NtpTrustedTime(  896): forceRefresh() from cache miss
,D/OpenGLRenderer( 6370): Enabling debug mode 0
,D/NtpTrustedTime(  896): forceRefresh Fail.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/InputMethodManagerService(  896): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): stay LED for fully charged
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
W/ActivityManager(  896): mDVFSHelper.release()
I/Timeline(  896): Timeline: Activity_windows_visible id: ActivityRecord{af00a8c u0 com.test.thalitest/.MainActivity t3} time:160567
W/IInputConnectionWrapper( 6370): showStatusIcon on inactive InputConnection
I/Timeline( 6370): Timeline: Activity_idle id: android.os.BinderProxy@1700ded3 time:160576
I/SamsungIME( 1722): getCurrentCandidateView
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SamsungIME( 1722): Dismiss ExpandCandiate
,D/JsMessageQueue( 6370): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium( 6370): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6370): 
,I/SamsungIME( 1722): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1722): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1722): KeybaordView init() : load resources
,I/SamsungIME( 1722): getCurrentKeyboard
I/SamsungIME( 1722): getTextKeyboard
,D/SamsungIME( 1722): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/jxcore_app_log( 6370): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258381824
,D/JX-Cordova( 6370): jxcore cordova android initializing
,D/SamsungIME( 1722): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/jxcore-log( 6370): Initializing JXcore engine
W/jxcore-log( 6370): JXcore engine is ready
,W/jxcore-log( 6370): Starting JXcore engine
,E/auditd  ( 1831): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  896): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,D/SecurityLogAgent:SEDenialService(  896): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/Zygote  ( 6453): MountEmulatedStorage()
I/ActivityManager(  896): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6453 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 6453): v2
I/libpersona( 6453): KNOX_SDCARD checking this for 1000
I/libpersona( 6453): KNOX_SDCARD not a persona
,I/SELinux ( 6453): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6453): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6453): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6453): TimaSignature is unavailable
,D/ActivityThread( 6453): Added TimaKeyStore provider
,D/ResourcesManager( 6453): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,W/jxcore-log( 6370): Platform android
W/jxcore-log( 6370): 
W/jxcore-log( 6370): Process ARCH arm
W/jxcore-log( 6370): 
,D/SecurityLogAgent( 6453):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6453):  SeDenialReceiver : File path = null
,I/ActivityManager(  896): Killing 4476:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,I/jxcore-log( 6370): JXcore Cordova bridge is ready!
I/jxcore-log( 6370): 
W/jxcore-log( 6370): JXcore engine is started
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 4
,I/jxcore-log( 6370): Toggling radios to true
I/jxcore-log( 6370): 
,D/BluetoothAdapter( 6370): enable()
W/ActivityManager(  896): Permission Denial: getCurrentUser() from pid=6370, uid=10284 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService(  896): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService(  896): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6370, uid=10284 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService(  896): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/BluetoothManagerService(  896): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2141)
W/BluetoothManagerService(  896): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:671)
W/BluetoothManagerService(  896): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService(  896): 	at android.os.Binder.execTransact(Binder.java:446)
E/DevicePolicyManagerService(  896): getAllowBluetoothMode - value retunrs : 2
D/SettingsProvider(  896): name = bluetooth_on
E/DevicePolicyManagerService(  896): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService(  896): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService(  896): getAllowBluetoothMode - value retunrs : 2
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,I/WifiManager( 6370): packageName : com.test.thalitest
D/SecContentProvider(  896): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  896): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  896): mCursor = null
,D/WifiService(  896): setWifiEnabled: true pid=6370, uid=10284
W/WifiService(  896): Failed getting userId using ActivityManagerNative
W/WifiService(  896): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6370, uid=10284 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  896): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/WifiService(  896): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2181)
W/WifiService(  896): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2169)
W/WifiService(  896): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  896): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ActivityManager(  896): Permission Denial: getCurrentUser() from pid=6370, uid=10284 requires android.permission.INTERACT_ACROSS_USERS
D/SettingsProvider(  896): name = wifi_on,
,E/WifiHW  (  896): ##################### set firmware type 0 #####################
,I/WifiHW  (  285): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
I/WifiService(  896): disconnect: pid=6370, uid=10284
I/jxcore-log( 6370): Radios toggled
I/jxcore-log( 6370): 
I/WifiHW  (  285): module is semco
E/WifiHW  (  285): ==========[WIFI] SEMCO MODULE ===========
I/WifiHW  (  285): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
E/WifiHW  (  285): TEMP_FAILURE_RETRY complete
D/SoftapController(  285): Softap fwReload - Ok
,D/CommandListener(  285): Setting iface cfg
D/CommandListener(  285): Trying to bring down wlan0
,D/CommandListener(  285): Clearing all IP addresses on wlan0
,E/WifiHW  (  896): supplicant_name : p2p_supplicant
,E/SMD     (  291): DCD ON
,E/Zygote  ( 6480): MountEmulatedStorage()
,E/Zygote  ( 6480): v2
I/libpersona( 6480): KNOX_SDCARD checking this for 1002
I/libpersona( 6480): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6480 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/jxcore-log( 6370): Got Device Bluetooth address: E0:DB:10:1F:C9:5E
I/jxcore-log( 6370): 
,D/SmartBondingService(  896): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,I/jxcore-log( 6370): Perf Test app loaded loaded
I/jxcore-log( 6370): 
,D/WifiMonitor(  896): startMonitoring(wlan0) with mConnected = false
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,I/jxcore-log( 6370): check test folder
I/jxcore-log( 6370): 
,I/jxcore-log( 6370): found test : ./testFindPeers.js
I/jxcore-log( 6370): 
,E/Zygote  ( 6486): MountEmulatedStorage()
E/Zygote  ( 6486): v2
I/libpersona( 6486): KNOX_SDCARD checking this for 10152
I/libpersona( 6486): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc tv.peel.samsung.app for broadcast tv.peel.samsung.app/com.peel.receiver.ConnectivityActionReceiver: pid=6486 uid=10152 gids={50152, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/wpa_supplicant( 6479): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 6479): Successfully initialized wpa_supplicant
,I/SecureStorage( 6479): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6479): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/SELinux ( 6480): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SecureStorage(  428): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6479
I/SecureStorage(  428): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
I/SecureStorage( 6479): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6479): ssSupport state is = 1
I/wpa_supplicant( 6479): >>>>> GET KEY, IV <<<<<
I/SELinux ( 6480): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6480): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/SecureStorage( 6479): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  428): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6479
I/SecureStorage(  428): [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,D/SmartBondingService(  896): getNetworkEnabled : wifi : false mobile : true
,D/WifiCredService( 1309): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=false enabledDesc:null
D/STATUSBAR-WifiQuickSettingButton( 1185): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1185): Wifi onReceive(2)
D/HotspotTile( 1185): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1185): onStateChanged: Wi-Fi
,I/jxcore-log( 6370): found test : ./testSendData.js
I/jxcore-log( 6370): 
,I/SELinux ( 6486): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6486): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6486): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/HotspotTile( 1185): onReceive : 2, 0
,D/TimaKeyStoreProvider( 6480): TimaSignature is unavailable
,D/ActivityThread( 6480): Added TimaKeyStore provider
,D/ResourcesManager( 6480): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,W/ResourcesManager( 6480): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 6480): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6486): TimaSignature is unavailable
,D/ActivityThread( 6486): Added TimaKeyStore provider
,D/ResourcesManager( 6486): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,I/BluetoothA2dpSinkServiceJni( 6480): register_com_android_bluetooth_a2dp_sink
,I/chromium( 6370): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/chromium( 6370): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/BtSettings.ProfileConfig( 6480): Adding GattService
,D/BtSettings.ProfileConfig( 6480): Adding HeadsetService
D/BtSettings.ProfileConfig( 6480): Adding A2dpService
,D/BtSettings.ProfileConfig( 6480): Adding HidService
D/BtSettings.ProfileConfig( 6480): Adding HealthService
D/BtSettings.ProfileConfig( 6480): Adding PanService
,D/BtSettings.ProfileConfig( 6480): Adding BluetoothMapService
D/BtSettings.ProfileConfig( 6480): Adding SapService
D/BtSettings.ProfileConfig( 6480): Adding HeadsetClientService
,D/BtSettings.ProfileConfig( 6480): Adding A2dpSinkService
D/BtSettings.ProfileConfig( 6480): Adding SapClientService
D/BtSettings.ProfileConfig( 6480): Adding HidDevService
,I/BtSettings.ProfileConfig( 6480): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider(  896): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider(  896): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  896): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  896): selectionArgs: false
D/SettingsProvider(  896): selectionArgs: 1002
D/SecContentProvider(  896): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  896): ret = -1
,W/BackupManagerService(  896): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  896): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider(  896): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  896): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  896): selectionArgs: false
D/SettingsProvider(  896): selectionArgs: 1002
D/SecContentProvider(  896): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  896): ret = -1
,W/BackupManagerService(  896): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  896): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider(  896): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  896): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  896): selectionArgs: false
D/SettingsProvider(  896): selectionArgs: 1002
D/SecContentProvider(  896): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  896): ret = -1
,W/BackupManagerService(  896): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  896): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider(  896): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  896): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  896): selectionArgs: false
D/SettingsProvider(  896): selectionArgs: 1002
D/SecContentProvider(  896): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  896): ret = -1
,W/BackupManagerService(  896): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  896): name = bt_svcst_com.android.bluetooth.hdp.HealthService
,D/SettingsProvider(  896): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  896): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  896): selectionArgs: false
D/SettingsProvider(  896): selectionArgs: 1002
D/SecContentProvider(  896): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  896): ret = -1
,W/BackupManagerService(  896): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  896): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider(  896): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  896): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  896): selectionArgs: false
D/SettingsProvider(  896): selectionArgs: 1002
D/SecContentProvider(  896): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  896): ret = -1
,W/BackupManagerService(  896): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  896): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider(  896): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  896): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  896): selectionArgs: false
D/SettingsProvider(  896): selectionArgs: 1002
D/SecContentProvider(  896): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  896): ret = -1
,W/BackupManagerService(  896): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  896): name = bt_svcst_com.broadcom.bt.service.sap.SapService
,D/SettingsProvider(  896): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  896): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  896): selectionArgs: false
D/SettingsProvider(  896): selectionArgs: 1002
D/SecContentProvider(  896): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  896): ret = -1
,W/BackupManagerService(  896): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  896): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,D/SettingsProvider(  896): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  896): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  896): selectionArgs: false
D/SettingsProvider(  896): selectionArgs: 1002
D/SecContentProvider(  896): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  896): ret = -1
,W/BackupManagerService(  896): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  896): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider(  896): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  896): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  896): selectionArgs: false
D/SettingsProvider(  896): selectionArgs: 1002
D/SecContentProvider(  896): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  896): ret = -1
,W/BackupManagerService(  896): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  896): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider(  896): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  896): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  896): selectionArgs: false
D/SettingsProvider(  896): selectionArgs: 1002
D/SecContentProvider(  896): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  896): ret = -1
,W/BackupManagerService(  896): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  896): name = bt_svcst_com.android.bluetooth.hid.HidDevService
,D/SettingsProvider(  896): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  896): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  896): selectionArgs: false
D/SettingsProvider(  896): selectionArgs: 1002
D/SecContentProvider(  896): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  896): ret = -1
,W/BackupManagerService(  896): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/WebViewFactory( 6486): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 6486): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 6486): Loading: webviewchromium
,I/LibraryLoader( 6486): Time to load native libraries: 5 ms (timestamps 4645-4650)
,I/LibraryLoader( 6486): Expected native library version number "",actual native library version number ""
,D/BluetoothAdapterState( 6480): make
,I/bluedroid( 6480): init
,I/BluetoothAdapterState( 6480): Entering OffState
,I/bte_conf( 6480): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 6480): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6480): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6480): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif ( 6480): btif_fetch_local_ble_random_bdaddr
,I/bluedroid( 6480): get_profile_interface socket
I/GKI_LINUX( 6480): gki_task_entry task_id=1 [BTIF] starting
I/bluedroid( 6480): get_profile_interface map_client
,D/BluetoothAdapterService( 6480): checkAddrForIOP: Loading from conf
,D/BluetoothAdapterProperties( 6480): Address is:E0:DB:10:1F:C9:5E
E/BluetoothServiceJni( 6480): populateRssiValuesNative
I/bluedroid( 6480): getModelRssiValues
E/BluetoothServiceJni( 6480): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 6480): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothAdapterProperties( 6480): Name is: Note3-1
D/SettingsProvider(  896): name = bluetooth_name
,V/WebViewChromiumFactoryProvider( 6486): Binding Chromium to main looper Looper (main, tid 1) {deb6799}
,I/LibraryLoader( 6486): Expected native library version number "",actual native library version number ""
,I/chromium( 6486): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/bluedroid( 6480): config_hci_snoop_log
,D/BluetoothManagerService(  896): Broadcasting onBluetoothServiceUp() to 10 receivers.
,E/DevicePolicyManagerService(  896): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService(  896): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider(  896): uri = 3 selection = isBluetoothEnabled
,I/SecureStorage(  428): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,D/BluetoothAdapterState( 6480): CURRENT_STATE=OFF, MSG = USER_TURN_ON
D/BluetoothAdapterProperties( 6480): Setting state to 11
I/BluetoothAdapterState( 6480): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 6480): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 6480): updateAdapterState state is 11
,D/BluetoothAdapterService( 6480): Autoconnection is available 
D/BluetoothAdapterService( 6480): updateAdapterState prevState = 10newState = 11
,D/BluetoothSecureManager( 6480): getInstant: null
D/BluetoothSecureManager( 6480): calling getMethod for getService
D/BluetoothSecureManager( 6480): calling getService
,D/BluetoothSecureManager( 6480): getService return binder: android.os.BinderProxy@2c8a03f8
D/BluetoothSecureManagerService(  896): isSecureModeEnabled
D/BluetoothSecureManagerService(  896): getSecureModeSetting, name: secure_mode_enable
D/BtConfig.SecureMode( 6480): isSecureModeOn:false
D/BtSettings.ProfileConfig( 6480): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 6480): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 6480): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/InputMethodManagerService(  896): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  896): [BT Setting State] State =11
,W/BluetoothAdapterService( 6480): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 6480): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,I/SamsungIME( 1722): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
W/BluetoothAdapterService( 6480): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 6480): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 6480): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 6480): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 6480): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 6480): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 6480): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BluetoothTile( 1185):  onBluetoothPairedDevicesChanged:
D/BtSettings.ProfileConfig( 6480): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothTile( 1185): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
W/BluetoothAdapterService( 6480): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 6480): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 6480): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 6480): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6480): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 6480): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
D/StatusBarManagerService(  896): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
W/BluetoothAdapterService( 6480): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 6480): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 6480): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 6480): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
D/StatusBarManagerService(  896): setIconVisibility slot=bluetooth visible=false
,W/BluetoothAdapterService( 6480): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
D/PhoneStatusBar( 1185): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 )
,D/BluetoothBondStateMachine( 6480): make
,D/STATUSBAR-QSTileView( 1185): onStateChanged: Bluetooth
,I/BrowserStartupController( 6486): Initializing chromium process, renderers=0
,W/art     ( 6486): Attempt to remove local handle scope entry from IRT, ignoring
,I/BluetoothBondStateMachine( 6480): StableState(): Entering Off State
W/BluetoothAdapterService( 6480): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 6480): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 6480): Not skipping com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 6480): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 6480): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 6480): Not skipping com.android.bluetooth.hfp.HeadsetService
,I/BtGatt.JNI( 6480): classInitNative(L890): classInitNative: Success!
W/BluetoothAdapterService( 6480): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 6480): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 6480): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 6480): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 6480): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 6480): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 6480): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 6480): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 6480): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 6480): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 6480): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 6480): Not skipping com.android.bluetooth.pan.PanService
W/chromium( 6486): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,D/BtGatt.DebugUtils( 6480): handleDebugAction() action=null
D/BtGatt.GattService( 6480): Received start request. Starting profile...
D/BtGatt.GattService( 6480): start()
I/bluedroid( 6480): get_profile_interface gatt
W/BluetoothAdapterService( 6480): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 6480): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 6480): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 6480): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e01f8e0
D/BtGatt.AdvertiseManager( 6480): advertise manager created
,W/BluetoothAdapterService( 6480): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 6480): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 6480): Not skipping com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 6480): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 6480): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6480): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6480): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 6480): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6480): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6480): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 6480): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6480): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6480): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 6480): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 6480): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState( 6480): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,W/chromium( 6486): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6486): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=36 off=46780 len=2953
I/chromium( 6486): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:37 off:229536 len:643667
,D/BluetoothAdapterService( 6480): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e01f8e0
,D/HeadsetService( 6480): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 6480): classInitNative: succeeds
,D/HeadsetStateMachine( 6480): make
,E/HeadsetStateMachine( 6480): # of Max HF connection is 2
,I/bluedroid( 6480): get_profile_interface handsfree
,I/DualScoManager( 6480): Instantiating Dual Sco Manager
I/Adreno-EGL( 6486): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6486): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6486): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6486): Local Branch: mybranch5813579
I/Adreno-EGL( 6486): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6486): Local Patches: NONE
I/Adreno-EGL( 6486): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
I/DualScoManager( 6480): Set HeadsetServiceHelper
,D/BluetoothAtMessage( 6480): createCMTIContentObservers
D/SettingsProvider(  896): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider(  896): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  896): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  896): selectionArgs: false
D/SettingsProvider(  896): selectionArgs: 1002
D/SecContentProvider(  896): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  896): ret = -1
,W/BackupManagerService(  896): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine( 6480): Enter Disconnected: -2
,E/HeadsetStateMachine( 6480): set to mRemoteBrsf = 0
D/BluetoothAdapterService( 6480): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e01f8e0
D/HeadsetStateMachine( 6480): map size, before remove : 0
D/HeadsetStateMachine( 6480): map size, after remove: 0
D/HeadsetStateMachine( 6480): mNextConnectingDevice : null
D/BluetoothA2dp(  896): Proxy object connected
D/BluetoothA2dp( 2934): Proxy object connected
D/A2dpService( 6480): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 6480): classInitNative: succeeds
V/Avrcp   ( 6480): make
V/Avrcp   ( 6480): Avrcp
I/bluedroid( 6480): get_profile_interface avrcp
V/Avrcp   ( 6480): start
E/RemoteController( 6480): Cannot set synchronization mode on an unregistered RemoteController
V/Avrcp   ( 6480): ++registerMediaPlayers++
I/Avrcp   ( 6480): No of Audio players :: 2
I/Avrcp   ( 6480): App Package name is com.google.android.music
D/ResourcesManager( 6480): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/Avrcp   ( 6480): App pkg name is Google Play Music
I/Avrcp   ( 6480): Name::Google Play Music
V/Avrcp   ( 6480): MediaPlayerInfo: mPlayerId=1
I/Avrcp   ( 6480): App Package name is com.sec.android.app.music
D/ResourcesManager( 6480): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
I/Avrcp   ( 6480): App pkg name is Music
I/Avrcp   ( 6480): Name::Music
V/Avrcp   ( 6480): MediaPlayerInfo: mPlayerId=2
I/Avrcp   ( 6480):  set player publishabilty with player id::2 toBePublished ::true
I/Avrcp   ( 6480): No of Video players :: 1
I/Avrcp   ( 6480): Video App Package name is com.sec.android.app.videoplayer
D/ResourcesManager( 6480): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
I/Avrcp   ( 6480): Video App pkg name is Video Player
I/Avrcp   ( 6480): Name::Video Player
V/Avrcp   ( 6480): MediaPlayerInfo: mPlayerId=3
I/Avrcp   ( 6480): Add tempPlayer
V/Avrcp   ( 6480): MediaPlayerInfo: mPlayerId=4
I/Avrcp   ( 6480): Total no of players: 4
V/Avrcp   ( 6480): swapping the samsung player with 1st player
I/Avrcp   ( 6480):  Updating now playing list upon AVRCP Start
V/Avrcp   ( 6480): handleMessage, msg=207
,I/BluetoothA2dpServiceJni( 6480): classInitNative: succeeds
D/BluetoothMediaBrowser( 6480):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
D/A2dpStateMachine( 6480): make
,I/bluedroid( 6480): get_profile_interface a2dp
,I/GKI_LINUX( 6480): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 6480): warning : media task started media_task_refcnt 1 
,D/BluetoothAdapterService( 6480): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e01f8e0
D/A2dpStateMachine( 6480): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 6480): classInitNative: succeeds
,D/HidService( 6480): Received start request. Starting profile...
,I/bluedroid( 6480): get_profile_interface hidhost
D/HidService( 6480): setHidService(): set to: null
D/BluetoothAdapterService( 6480): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e01f8e0
,I/BluetoothHealthServiceJni( 6480): classInitNative: succeeds
,D/HealthService( 6480): Received start request. Starting profile...
,I/bluedroid( 6480): get_profile_interface health
,D/BluetoothAdapterService( 6480): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e01f8e0
D/BluetoothMediaBrowser( 6480): no now playing list
D/BluetoothMediaBrowser( 6480):  getNowPlayingId now playing id : -1
D/Avrcp   ( 6480):  checkNowPlayingList start
,I/BluetoothPanServiceJni( 6480): classInitNative(L105): succeeds
,D/BluetoothPan(  896): BluetoothPAN Proxy object connected
,D/PanService( 6480): Received start request. Starting profile...
,D/BluetoothPanServiceJni( 6480): initializeNative(L110): pan
I/bluedroid( 6480): get_profile_interface pan
,D/BluetoothAdapterService( 6480): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e01f8e0
,D/BluetoothMapService( 6480): Received start request. Starting profile...
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6552): MountEmulatedStorage()
,E/Zygote  ( 6552): v2
I/libpersona( 6552): KNOX_SDCARD checking this for 10186
I/libpersona( 6552): KNOX_SDCARD not a persona
,I/SELinux ( 6552): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6552): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
I/ActivityManager(  896): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=6552 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,E/SELinux ( 6552): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/chromium( 6486): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,D/TimaKeyStoreProvider( 6552): TimaSignature is unavailable
,W/chromium( 6486): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
D/ActivityThread( 6552): Added TimaKeyStore provider
,D/ResourcesManager( 6552): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 6552): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6552): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6552): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6552): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6552): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/art     ( 6486): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6486): onDetachedFromWindow called when already detached. Ignoring
,I/SecureStorage( 6479): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 6479): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6479): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  428): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6479
I/SecureStorage(  428): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
I/SecureStorage( 6479): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6479): ssSupport state is = 1
,I/wpa_supplicant( 6479): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6479): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6479): SIM READ ERROR
I/wpa_supplicant( 6479): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6479): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6479): SIM READ ERROR
I/wpa_supplicant( 6479): Blacklist: Clear (all) 
,I/wpa_supplicant( 6479): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6479): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant( 6479): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6479): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,I/wpa_supplicant( 6479): rfkill: Cannot open RFKILL control device
,D/RCPManagerService(  896): exchangeData() failure , invalid userId
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService(  896): exchangeData() failure , invalid userId
,D/BluetoothAdapterService( 6480): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e01f8e0
,I/BluetoothSAPServiceJni( 6480): classInitNative(L204): succeeds
,D/SapService( 6480): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 6480): initializeNative(L209): sap
I/bluedroid( 6480): get_profile_interface sap
D/BluetoothAdapterService( 6480): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e01f8e0
,E/BluetoothAdapterService(771881184)( 6480): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
D/HeadsetStateMachine( 6480): Proxy object connected
D/HeadsetStateMachine( 6480): Try to query the phonestate on bind
,I/Telecom ( 1399): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 1399): BluetoothPhoneService: updateHeadsetWithCallState
,I/Telecom ( 1399): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,E/Zygote  ( 6582): MountEmulatedStorage()
E/Zygote  ( 6582): v2
I/libpersona( 6582): KNOX_SDCARD checking this for 10092
I/libpersona( 6582): KNOX_SDCARD not a persona
W/BluetoothHeadset( 1399): Proxy not attached to service
,D/HeadsetPhoneState( 6480): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState( 6480): sendDeviceDataStateChanged
D/HeadsetStateMachine( 6480): Disconnected process message: 11
D/HeadsetStateMachine( 6480): Disconnected process message: 18
,D/HeadsetPhoneState( 6480): Signal level : previous=0 curr=0
E/BluetoothAdapterService(771881184)( 6480): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6480): Disconnected process message: 10
D/BluetoothA2dp( 6480): Proxy object connected
D/BluetoothAdapterService( 6480): Bluetooth A2dp source service connected
,E/BluetoothAdapterService(771881184)( 6480): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/HeadsetPhoneState( 6480): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6480): Disconnected process message: 11
E/BluetoothAdapterService(771881184)( 6480): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
E/BluetoothAdapterService(771881184)( 6480): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,I/ActivityManager(  896): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6582 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,D/RCPManagerService(  896): exchangeData() failure , invalid userId
I/SELinux ( 6582): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6582): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/BluetoothAdapterService(771881184)( 6480): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,E/SELinux ( 6582): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  896): Killing 5589:flipboard.app/u0a125 (adj 15): bgCount ##41
,E/BluetoothAdapterService(771881184)( 6480): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(771881184)( 6480): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,D/BluetoothAdapterState( 6480): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 6480): enable
I/GKI_LINUX( 6480): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 6480): init
,I/bt_vendor( 6480): init
I/bt_vnd_conf( 6480): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 6480): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 6480): userial_init
D/bt_vendor( 6480): op for 5
D/bt_vendor( 6480): op for 0
,D/bt_upio ( 6480): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 6480): is_emulator_context : 0
D/bt_upio ( 6480): is_rfkill_disabled ? [0]
D/bt_upio ( 6480): is_rfkill_disabled ? [0]
,D/bt_vendor( 6480): op for 0
D/bt_upio ( 6480): upio_set_bluetooth_power(on: 1)
D/bt_upio ( 6480): is_emulator_context : 0
D/bt_upio ( 6480): is_rfkill_disabled ? [0]
,D/bt_vendor( 6480): op for 3
I/bt_userial_vendor( 6480): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 6480): userial_vendor_open():UART is setup
,I/bt_userial_vendor( 6480): device fd = 65 open
D/bt_vendor( 6480): op for 1
D/bt_userial( 6480): Entering userial_read_thread()
,E/bt_hwcfg( 6480): Start CFG HW, HCI reset
,D/RCPManagerService(  896): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 6582): TimaSignature is unavailable
,D/ActivityThread( 6582): Added TimaKeyStore provider
,I/ActivityManager(  896): Killing 4975:com.google.android.gm/u0a128 (adj 15): bgCount ##41
,D/ResourcesManager( 6582): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,E/SignOutReceiver( 4343): WIFI_STATE_CHANGED_ACTION
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6453): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6453): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6453): StateMachine : Current State = 1
,D/BadgeProvider( 6582): onCreate
,D/BadgeProvider( 6582): DatabaseHelper
,E/bt_hwcfg( 6480): Read Local Name after HCI reset
,D/SecurityLogAgent( 6453): StateMachine : Changed Current State = 1
,I/ActivityManager(  896): Killing 5226:com.sec.android.app.music:service/u0a49 (adj 15): bgCount ##41
,D/BluetoothNotiBroadcastReceiver( 1309): onReceive
,D/BadgeProvider( 6582): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/AuthorizationBluetoothService( 1473): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BadgeProvider( 6582): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6582): sendNotify, [notify] : null
D/BadgeProvider( 6582): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6582): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 6582): update, [UpdateCount] : 1
,D/Launcher.Model( 1432): reloadBadges entered.
,W/ActivityManager(  896): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/Watchdog(  896): !@Sync 5
,E/Tethering(  896): No numeric data
,D/Tethering(  896): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 6479): wlan0: Setting scan request: 0 sec 100000 usec
D/NtpTrustedTime(  896): forceRefresh() from cache miss
,D/NtpTrustedTime(  896): forceRefresh Fail.
V/NetworkStats(  896): performPollLocked(flags=0x1)
D/NetworkStatsFactory(  896): UpdateStatsForKnox
,D/HotspotTile( 1185): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/HotspotTile( 1185): updateTetherState():false, false
,V/NetworkStats(  896): performPollLocked() took 5ms
,D/NtpTrustedTime(  896): forceRefresh() from cache miss
,D/NtpTrustedTime(  896): forceRefresh Fail.
,I/wpa_supplicant( 6479): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/SecureStorage( 6479): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6479): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  428): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6479
I/SecureStorage(  428): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
I/SecureStorage( 6479): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6479): ssSupport state is = 1
,I/SecureStorage( 6479): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6479): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  428): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6479
I/SecureStorage(  428): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
I/SecureStorage( 6479): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6479): ssSupport state is = 1
I/wpa_supplicant( 6479): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6479): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6479): SIM READ ERROR
I/wpa_supplicant( 6479): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant( 6479): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 6479): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 6479): p2p0: State: INACTIVE -> DISCONNECTED
I/wpa_supplicant( 6479): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  896): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative-HAL(  896): callSECApiBoolean - ID [21]
,I/wpa_supplicant( 6479): HOTSPOT20_ENABLE called
I/wpa_supplicant( 6479): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6479): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6479): SIM READ ERROR
I/wpa_supplicant( 6479): Blacklist: Clear (all) 
,I/wpa_supplicant( 6479): Skip scan - bUseNetwork false
,D/WifiNative-HAL(  896): callSECApiInt - ID [210]
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/HotspotTile( 1185): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/STATUSBAR-WifiQuickSettingButton( 1185): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1185): Wifi onReceive(3)
,D/STATUSBAR-QSTileView( 1185): onStateChanged: Wi-Fi
D/WifiConfigStore(  896): Loading config and enabling all networks 
D/SmartBondingService(  896): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
D/HotspotTile( 1185): onReceive : 3, 0
D/SmartBondingService(  896): getNetworkEnabled : wifi : true mobile : true
D/WifiCredService( 1309): Action received :android.net.wifi.WIFI_STATE_CHANGED
E/WifiConfigStore(  896): Not a HS20
E/WifiConfigStore(  896): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
E/SignOutReceiver( 4343): WIFI_STATE_CHANGED_ACTION
D/WifiNative-HAL(  896): callSECApiInt - ID [65]
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 6453): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6453): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6453): StateMachine : Current State = 1
D/SecurityLogAgent( 6453): StateMachine : Changed Current State = 1
D/WifiNative-HAL(  896): callSECApiBoolean - ID [13]
I/wpa_supplicant( 6479): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 6479): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 6479): reset timer : RESET_TIMER 0
I/wpa_supplicant( 6479): P2P: Current p2p state = IDLE
I/wpa_supplicant( 6479): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 6479): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 6479): First Scan Start
W/Settings( 5011): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/wpa_supplicant( 6479): Scan requested (ret=0) - scan timeout 30 seconds
D/WifiNative-HAL(  896): Setting external_sim to 1
D/WifiStateMachine(  896): Setting OUI to DA-A1-19
I/WifiNative-HAL(  896): startHal
E/wifi    (  896): getStaticLongField sWifiHalHandle 0x9d1f386c
D/wifi    (  896): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x90176a
I/WifiNative-HAL(  896): Could not start hal
,E/native  (  896): do suspend true
D/WifiP2pService(  896): P2pDisabledState{ what=131203 }
D/CommandListener(  285): Setting iface cfg
D/CommandListener(  285): Trying to bring up p2p0
D/WifiScanningService(  896): SCAN_AVAILABLE : 3
D/WifiMonitor(  896): startMonitoring(p2p0) with mConnected = true
E/WifiStateMachine(  896): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
D/WifiP2pService(  896): P2pEnablingState
D/RttService(  896): SCAN_AVAILABLE : 3
D/WifiP2pService(  896): P2pEnablingState{ what=147457 }
D/RttService(  896): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  896): P2p socket connection successful
D/WifiP2pService(  896): P2pEnabledState
D/WifiScanningService(  896): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  896): startHal
E/wifi    (  896): getStaticLongField sWifiHalHandle 0x98dfb99c
E/WifiStateMachine(  896): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
D/wifi    (  896): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x40172e
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
I/WifiNative-HAL(  896): Could not start hal
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/WifiScanningService(  896): could not start HAL
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/WifiStateMachine(  896): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiP2pService(  896): sending p2p connection changed broadcast: IDLE
D/WifiNative-HAL(  896): callSECStringApiVoid - ID [215]
E/WifiNative-HAL(  896): invaild command id : 215
D/WifiDisplayController(  896): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  896): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  896): disconnect
D/WifiDisplayController(  896): updateConnection
D/WifiDisplayController(  896): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  896): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/wpa_supplicant( 6479): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
E/Zygote  ( 6617): MountEmulatedStorage()
I/libpersona( 6617): KNOX_SDCARD checking this for 10192
E/Zygote  ( 6617): v2
I/libpersona( 6617): KNOX_SDCARD not a persona
I/ActivityManager(  896): Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=6617 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6617): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/AllShareCastTile( 1185): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/WifiDisplayAdapter(  896): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 1185): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
D/WifiDisplayController(  896): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiP2pService(  896): create mNetworkAgent
I/SELinux ( 6617): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6617): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/wpa_supplicant( 6479): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/SecContentProvider2(  896): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  896): mCursor = null
,D/SecContentProvider2(  896): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  896): mCursor = null
,D/ConnectivityService(  896): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  896): Got NetworkAgent Messenger
,D/ConnectivityService(  896): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  896): updateNetworkInfo()
,D/ConnectivityService(  896): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  896): NetworkAgent connected
E/CSLegacyTypeTracker(  896): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,D/WifiNative-HAL(  896): p2pGetDeviceAddress
,D/WifiNative-HAL(  896): p2pGetDeviceAddress returning ea:50:8b:de:28:a3
D/WifiDisplayController(  896): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
D/WifiDisplayController(  896):  deviceAddress: ea:50:8b:de:28:a3
D/WifiDisplayController(  896):  primary type: 10-0050F204-5
D/WifiDisplayController(  896):  secondary type: null
D/WifiDisplayController(  896):  wps: 0
D/WifiDisplayController(  896):  grpcapab: 0
D/WifiDisplayController(  896):  devcapab: 0
D/WifiDisplayController(  896):  status: 3
D/WifiDisplayController(  896):  wfdInfo: null
D/WifiDisplayController(  896):  groupownerAddress: null
D/WifiDisplayController(  896):  GOdeviceName: null
D/WifiDisplayController(  896):  interfaceAddress: 
D/WifiDisplayController(  896):  SConnectInfo : null
D/WifiP2pService(  896): DeviceAddress: ea:28:a3
,D/TimaKeyStoreProvider( 6617): TimaSignature is unavailable
,D/ActivityThread( 6617): Added TimaKeyStore provider
,D/WifiP2pService(  896): sending p2p persistent groups changed broadcast
,D/WifiP2pService(  896): InactiveState
D/WifiP2pService(  896): InactiveState{ what=143376 }
D/WifiP2pService(  896): P2pEnabledState{ what=143376 }
,D/ResourcesManager( 6617): creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,I/wpa_supplicant( 6479): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/ConnectivityService(  896): updateNetworkInfo()
D/ConnectivityService(  896): ignoring duplicate network state non-change. WIFI_P2P, state = UNKNOWN
D/WifiP2pService(  896): InactiveState{ what=143376 }
,D/WifiP2pService(  896): P2pEnabledState{ what=143376 }
,D/WifiDirectBR( 6617): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,I/ActivityManager(  896): Killing 5291:com.sec.android.app.myfiles/u0a56 (adj 15): bgCount ##41
D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
V/NearbySettings( 1309): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1309): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1309): MountReceiver.mPrefHandler - 7002
,D/FileShare-Server( 5400): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/WifiDirectBR( 6617): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiDirectBR( 6617): WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,W/ContextImpl( 6617): Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
D/WifiDirectBR( 6617): stopServiceTest : false
,I/wpa_supplicant( 6479): nl80211: Received scan results (8 BSSes)
,I/wpa_supplicant( 6479): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 6479): Trying to associate with C0.AA.4A (SSID='4E473730303567' freq=5220 MHz)
,I/wpa_supplicant( 6479): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 6479): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E473730303567
,D/SecContentProvider2(  896): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  896): mCursor = null
,I/wpa_supplicant( 6479): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 6479): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E473730303567
,I/wpa_supplicant( 6479): Associated with C0.AA.4A
,D/SecContentProvider2(  896): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  896): mCursor = null
,I/wpa_supplicant( 6479): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 6479): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.4A SSID=4E473730303567
,D/SecContentProvider2(  896): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  896): mCursor = null
I/wpa_supplicant( 6479): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 6479): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 6479): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.4A SSID=4E473730303567
,I/wpa_supplicant( 6479): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6479): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 6479): CTRL-EVENT-CONNECTED - Connection to C0.AA.4A completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 6479): Blacklist: Clear (temp) 
I/wpa_supplicant( 6479): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.4A SSID=4E473730303567
,D/WifiNative-HAL(  896): callSECApiVoid - ID [50]
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  896): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiConfigStore(  896): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  896): Got NetworkAgent Messenger
,D/ConnectivityService(  896): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  896): updateNetworkInfo()
D/ConnectivityService(  896): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  896): NetworkAgent connected
,E/WifiConfigStore(  896): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  285): Setting iface cfg
,E/Zygote  ( 6648): MountEmulatedStorage()
E/Zygote  ( 6648): v2
I/libpersona( 6648): KNOX_SDCARD checking this for 10038
I/libpersona( 6648): KNOX_SDCARD not a persona
,I/SELinux ( 6648): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6648): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,I/ActivityManager(  896): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=6648 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,E/WifiStateMachine(  896): Start Dhcp Watchdog 1
E/SELinux ( 6648): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/SecContentProvider2(  896): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  896): mCursor = null
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService(  896): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,D/SecContentProvider2(  896): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  896): mCursor = null
,I/art     (  322): Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 1.065ms total 42.576ms
,D/TimaKeyStoreProvider( 6648): TimaSignature is unavailable
,D/ActivityThread( 6648): Added TimaKeyStore provider
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 410us total 16.302ms
,D/ResourcesManager( 6648): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 415us total 14.028ms
,W/ResourcesManager( 6648): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/native  (  896): do suspend false
,D/WifiP2pService(  896): InactiveState{ what=143375 }
,D/WifiP2pService(  896): P2pEnabledState{ what=143375 }
,I/VlingoApplication( 6648): VlingoApplication appVersion ='11.2.2.0.37649', ro.csc.sales_code=XEO
,E/SMD     (  291): DCD ON
,E/dhcpcd  ( 6680): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6680): version 5.5.6 starting
,E/dhcpcd  ( 6680): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/BluetoothHeadset( 6648): BTStateChangeCB is registed
,E/BluetoothHeadset( 6648): BluetoothHeadset service is binded
,I/ActivityManager(  896): Killing 5011:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,I/Hs20UtilService( 1309): Starting #2
,I/Hs20UtilService( 1309): Message received 5007
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1309): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1309): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1309): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 4343): NETWORK_STATE_CHANGED_ACTION
,D/SettingsProvider(  896): name = driving_mode_on
D/SettingsProvider(  896): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  896): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  896): selectionArgs: false
D/SettingsProvider(  896): selectionArgs: 10038
D/SecContentProvider(  896): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  896): ret = -1
,D/BluetoothManager( 6648): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,I/dhcpcd  ( 6680): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  ( 6680): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6680): if(wlan0) info get Success. (MAC : C0.AA.4A)
,I/dhcpcd  ( 6680): bssid match
,I/dhcpcd  ( 6680): wlan0: rebinding lease of 192.168.1.128
,I/dhcpcd  ( 6680): wlan0: acknowledged 192.168.1.128 from 192.168.1.1
,I/dhcpcd  ( 6680): wlan0: leased 192.168.1.128 for 86400 seconds
,D/ConnectivityService(  896): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,E/native  (  896): do suspend true
,D/WifiP2pService(  896): InactiveState{ what=143375 }
,D/WifiP2pService(  896): P2pEnabledState{ what=143375 }
,D/ConnectivityService(  896): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine(  896): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG7005g"WPA_PSK
E/WifiStateMachine(  896): VerifyingLinkState enter
,I/jxcore-log( 6370): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 6370): 
,D/WifiNative-HAL(  896): callSECApiInt - ID [210]
,E/ConnectivityService(  896): updateNetworkInfo()
,D/ConnectivityService(  896): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService(  896): Adding iface wlan0 to network 502
,D/WifiWatchdogStateMachine(  896): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  896): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiWatchdogStateMachine.DnsResolver(  896): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker(  896): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  896): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,E/WifiStateMachine(  896): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,I/Hs20UtilService( 1309): Starting #3
E/WifiStateMachine(  896): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/WifiTrafficPoller(  896): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:null
D/ConnectivityService(  896): Adding Route [fe80::/64 -> :: wlan0] to network 502
,D/ConnectivityService(  896): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,I/WifiTrafficPoller(  896): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  896): mBoosterFLAG : 0
I/WifiTrafficPoller(  896): current booster mode : FullMode
D/WifiNative-HAL(  896): callSECApiVoid - ID [212]
,D/ConnectivityService(  896): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 502
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): applyOpen
E/ConnectivityService(  896): Unexpected mtu value: 0, wlan0
,D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
,D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/Hs20UtilService( 1309): Message received 5007
,I/NearbySettings( 1309): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  896): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  896): updateSourceRoutes : add src route for:192.168.1.128
,V/        (  285): QcRouteController
,D/SmartBondingService(  896): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  896): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  896): getSBEnabled() enabled =false
D/SmartBondingService(  896): getSBEnabled() enabled =false
D/SmartBondingService(  896): getSBEnabled() enabled =false
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 4343): NETWORK_STATE_CHANGED_ACTION
,V/        (  285): QcRouteController
,V/        (  285): QcRouteController
,V/        (  285): QcRouteController
,I/Hs20UtilService( 1309): Starting #4
,I/Hs20UtilService( 1309): Message received 5007
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1309): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1309): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1309): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/        (  285): QcRouteController
,E/SignOutReceiver( 4343): NETWORK_STATE_CHANGED_ACTION
,V/        (  285): QcRouteController
,I/Hs20UtilService( 1309): Starting #5
,I/Hs20UtilService( 1309): Message received 5007
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1309): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine(  896): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        (  285): QcRouteController
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/        (  285): QcRouteController
,E/SignOutReceiver( 4343): NETWORK_STATE_CHANGED_ACTION
,I/SurfaceFlinger(  254): id=14 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService(  896): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=896
,V/        (  285): QcRouteController
,D/ConnectivityService(  896): Setting Dns servers for network 502 to [/192.168.1.1]
,D/ConnectivityService(  896): LTETest block dns file not exists
,V/Nat464Xlat(  896): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  896): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  896): calling update connectivity
,D/EntConnectivity(  896): Not allowed due to - mEnabled false
E/ConnectivityService(  896): updateNetworkInfo()
D/ConnectivityService(  896): ignoring duplicate network state non-change. WIFI, state = CONNECTING
E/ConnectivityService(  896): updateNetworkInfo()
D/ConnectivityService(  896): ignoring duplicate network state non-change. WIFI, state = CONNECTING
D/ConnectivityService(  896): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  896): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  896): calling update connectivity
D/ConnectivityService(  896): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  896):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  896):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  896):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  896): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  896): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  896): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  896): Checking http://clients3.google.com/generate_204 on "NG7005g"
,I/System.out(  896): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out(  896): (HTTPLog)-Static: isShipBuild true
I/System.out(  896): (HTTPLog)-Thread-180-108404594: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(  896): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService(  896): currentScore = 0, newScore = 60
D/ConnectivityService(  896):    accepting network in place of null
D/ConnectivityService(  896): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  896): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
,D/TelephonyNetworkFactory( 1420): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/PackageManager(  896): [MSG] WRITE_PACKAGE_RESTRICTIONS
,E/CSLegacyTypeTracker(  896): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker(  896): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
,D/ConnectivityService(  896): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  896): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  896): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/SmartBondingService(  896): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  896): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  896): getSBEnabled() enabled =false
D/SmartBondingService(  896): getSBEnabled() enabled =false
D/Tethering(  896): MasterInitialState.processMessage what=3
D/SmartBondingService(  896): getSBEnabled() enabled =false
,D/SmartBondingService(  896): getNetworkEnabled : wifi : true mobile : true
V/NetworkStats(  896): updateIfacesLocked()
D/EntConnectivity(  896): Not allowed due to - mEnabled false
D/ConnectivityService(  896): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  896): calling update connectivity
D/ConnectivityService(  896):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  896):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  896): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  896): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=true
,D/ConnectivityService(  896): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityManager.CallbackHandler( 1185): CM callback handler got msg 524290
D/ConnectivityService(  896): identical MTU - not setting
D/ConnectivityService(  896): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  896): updateSourceRoutes : add src route for:fe80::ea50:8bff:fede:28a3
,V/NetworkStats(  896): performPollLocked(flags=0x1)
V/        (  285): QcRouteController
,D/NtpTrustedTime(  896): forceRefresh() from cache miss
,D/NetworkStatsFactory(  896): UpdateStatsForKnox
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1185): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 1185): updateDataNetType()
D/StatusBar.NetworkController( 1185): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1185): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1185): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
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
,V/        (  285): QcRouteController
,W/NetworkManagementService(  896): route cmd failed: 
W/NetworkManagementService(  896): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '52 route replace src v6 wlan0 fe80::ea50:8bff:fede:28a3 2 ::' failed with '400 52 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  896): '
W/NetworkManagementService(  896): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService(  896): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService(  896): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService(  896): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService(  896): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  896): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5625)
W/NetworkManagementService(  896): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5437)
W/NetworkManagementService(  896): 	at com.android.server.ConnectivityService.access$2300(ConnectivityService.java:229)
W/NetworkManagementService(  896): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2382)
W/NetworkManagementService(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  896): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/Nat464Xlat(  896): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  896): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  896): calling update connectivity
D/ConnectivityService(  896):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  896):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  896): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  896): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  896): calling update connectivity
D/ConnectivityService(  896):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  896):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
V/NetworkStats(  896): performPollLocked() took 35ms
D/ConnectivityService(  896): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1185): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1185): CM callback handler got msg 524295
,D/SSRM:n  (  896): SIOP:: AP = 330, PST = 320, CUR = 450
,I/System.out(  896): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NtpTrustedTime(  896): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1450100367313 mCachedNtpElapsedRealtime : 169801 mCachedNtpCertainty : 7
,D/NtpTrustedTime(  896): currentTimeMillis() cache hit
,D/NtpTrustedTime(  896): currentTimeMillis() cache hit
,D/NtpTrustedTime(  896): currentTimeMillis() cache hit
D/NtpTrustedTime(  896): currentTimeMillis() cache hit
D/NtpTrustedTime(  896): currentTimeMillis() cache hit
D/NtpTrustedTime(  896): currentTimeMillis() cache hit
,V/NetworkStats(  896): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  896): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 14 Dec 2015 13:39:27 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450100368550], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450100368527]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  896): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  896): Validated
D/ConnectivityService(  896): Validated NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  896): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  896):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  896):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  896): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService(  896): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  896): calling update connectivity
,D/ConnectivityService(  896):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  896):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  896): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1185): CM callback handler got msg 524290
,D/ConnectivityService(  896): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1185): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 1185): updateDataNetType()
D/StatusBar.NetworkController( 1185): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1185): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1185): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1185): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,D/ConnectivityService(  896): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  896): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  896): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  896): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  896): SmartBondingReceiver: wifi ap is changed, init speed ratio
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  896): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  896): getSBEnabled() enabled =false
D/SmartBondingService(  896): getSBEnabled() enabled =false
,D/SmartBondingService(  896): getSBEnabled() enabled =false
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  896): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  896): currentTimeMillis() cache hit
,D/AlarmManagerService(  896): Setting time of day to sec=1450100367
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/AlarmManagerService(  896): Trying to open a file
,D/AlarmManagerService(  896): File Open Success
,D/AlarmManagerService(  896): File Close Success
I/AlarmManagerService(  896): DRM_TIME_PATH CHMOD 666 for resetState done 
V/AlarmManager(  896): waitForAlarm result :65536
,W/AlarmManagerService(  896): Unable to set rtc to 1450100367: Invalid argument
,W/ContextImpl( 1838): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,W/ContextImpl( 1838): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1838): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 android.content.ContextWrapper.sendBroadcast:391 com.samsung.SMT.aa.a:-1 com.samsung.SMT.UpdateManager.c:-1 com.samsung.SMT.UpdateManager.b:-1 
,E/SMD     (  291): DCD ON
,D/WifiStateMachine(  896): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_SET
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_SET
,D/StatusBar-DoNotDistrub( 1185): Received intent with android.intent.action.TIME_SET action
,D/StatusBar-DoNotDistrub( 1185): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3144): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3144): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 3144): [com.wssyncmldm.llllIIIllIlIIIIllllI(263/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,D/accuweather( 1778): [Accuweather J]>>> SWW:64 [0:0] =============== BR act = androidintentactionTIME_SET
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 1778): [Accuweather J]>>> SWW:645 [0:0] renderUpdateAllCondition : [0] = 1
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/accuweather( 1778): [Accuweather J]>>> WR:452 [0:0] =============== updateAllCondition = 1
,I/DBG_DM  ( 3144): [llIlIIIIlllIlllllIll(224/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,I/PCWCLIENTTRACE_PushUtil( 5973): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5973): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5973): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5973): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5150): type=WIFI subType= reason=null isConnected=true
,I/DBG_DM  ( 3144): [IIllIIllIIIlllIlIIll(403/llllllIllIlIlllIIlIl)] Check completed.
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3144): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3144): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 6807): MountEmulatedStorage()
E/Zygote  ( 6807): v2
I/libpersona( 6807): KNOX_SDCARD checking this for 10014
I/libpersona( 6807): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6807 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/StatusBar-DoNotDistrub( 1185): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,W/Settings(  896): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/SELinux ( 6807): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6807): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6807): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,V/AudioPolicyManager(  298): getOutputsForDevice device 0002 -> 0002
,I/AudioService(  896): getStreamVolume 5 index 0
,D/StatusBar-DoNotDistrub( 1185): The STREAM NOTIFICATION volume is 0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
D/StatusBarManagerService(  896): manageDisableList userId=0 what=0x0 pkg=com.android.systemui
,I/DrmEventService(  896):  no response from SecureClock 
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/DBG_DM  ( 3144): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 3144): [IIIlllIlIIlllIIIIllI(73/llllIIIllIlIIIIllllI)] 
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 6823): MountEmulatedStorage()
I/libpersona( 6823): KNOX_SDCARD checking this for 10004
E/Zygote  ( 6823): v2
I/libpersona( 6823): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6823 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/System.out( 1838): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1838): (HTTPLog)-Static: isShipBuild true
I/System.out( 1838): (HTTPLog)-Thread-154-963992080: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1838): (HTTPLog)-Static: isSBSettingEnabled false
,I/DBG_DM  ( 3144): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/SELinux ( 6823): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6823): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,I/DBG_DM  ( 3144): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,E/SELinux ( 6823): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6807): TimaSignature is unavailable
,D/ActivityThread( 6807): Added TimaKeyStore provider
,I/DBG_DM  ( 3144): [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 2
,I/DBG_DM  ( 3144): [IIllIIllIIIlllIlIIll(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,I/System.out( 1838): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/TimaKeyStoreProvider( 6823): TimaSignature is unavailable
,D/ActivityThread( 6823): Added TimaKeyStore provider
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4303, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): stay LED for fully charged
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/ChimeraCfgMgr( 1754): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1754): Module APK com.google.android.play.games already loaded
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,I/DBG_DM  ( 3144): [IIllIIllIIIlllIlIIll(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/DBG_DM  ( 3144): [IIllIlIIlIlllIIllIII(741/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/DBG_DM  ( 3144): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1273/handleMessage)] event ->220
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/DBG_DM  ( 3144): [llIlIIIIlllIlllllIll(280/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 3144): [llIlIIIIlllIlllllIll(1907/lllIlIlIIIllIIlIllIl)] 
,I/DBG_DM  ( 3144): [com.wssyncmldm.XDMBroadcastReceiver(332/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,D/ResourcesManager( 6807): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3144): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(501/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,I/GoogleURLConnFactory( 1473): Using platform SSLCertificateSocketFactory
,I/DBG_DM  ( 3144): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 3144): [com.wssyncmldm.XDMService(876/IIIIllIlIIlIIIIlllIl)] 
,I/GamesSyncServiceMain( 1754): Found unexpected GCM tag when scheduling; aborting
I/DBG_DM  ( 3144): [com.wssyncmldm.db.file.XDB(4994/IIIlllIlIIlllIIIIllI)] Get Autoinstall status : false
,W/GamesSyncServiceMain( 1754): Failed to execute periodic sync, missing client context - aborting
,I/DBG_DM  ( 3144): [IIllIlIIlIlllIIllIII(695/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,I/DBG_DM  ( 3144): [com.wssyncmldm.XDMService(638/llllIIIllIlIIIIllllI)] 
,E/DBG_DM  ( 3144): [com.wssyncmldm.XDMService(646/llllIIIllIlIIIIllllI)] didn't register
,E/DBG_DM  ( 3144): [com.wssyncmldm.XDMService(647/llllIIIllIlIIIIllllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@3603b97a
,I/DBG_DM  ( 3144): [com.wssyncmldm.XDMService(819/IllIlIIIIlIIlIIIllIl)] Idle Screen : false
,D/ResourcesManager( 6823): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3144): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_en_us_l01
E/Samsung TTS( 1838): result : 2
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_en_us_z01
E/Samsung TTS( 1838): result : 0
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_fr_fr_l01
E/Samsung TTS( 1838): result : 2
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_fr_fr_z01
E/Samsung TTS( 1838): result : 0
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_it_it_l01
E/Samsung TTS( 1838): result : 2
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_it_it_z01
E/Samsung TTS( 1838): result : 0
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_de_de_l01
E/Samsung TTS( 1838): result : 2
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_de_de_z01
E/Samsung TTS( 1838): result : 0
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_en_gb_l01
E/Samsung TTS( 1838): result : 2
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_en_gb_z01
E/Samsung TTS( 1838): result : 0
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_es_es_l01
E/Samsung TTS( 1838): result : 2
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_es_es_z01
E/Samsung TTS( 1838): result : 0
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_ru_ru_l01
E/Samsung TTS( 1838): result : 2
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_ru_ru_z01
E/Samsung TTS( 1838): result : 0
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_pt_br_l01
E/Samsung TTS( 1838): result : 2
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_ko_kr_x01
E/Samsung TTS( 1838): result : 2
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_cs_cz_l01
E/Samsung TTS( 1838): result : 2
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_da_dk_l01
E/Samsung TTS( 1838): result : 2
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_el_gr_l01
E/Samsung TTS( 1838): result : 2
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_fi_fi_l01
E/Samsung TTS( 1838): result : 2
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_hu_hu_l01
E/Samsung TTS( 1838): result : 2
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_nl_nl_l01
E/Samsung TTS( 1838): result : 2
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_nb_no_l01
E/Samsung TTS( 1838): result : 0
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_pl_pl_l01
E/Samsung TTS( 1838): result : 2
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_pt_pt_l01
E/Samsung TTS( 1838): result : 0
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_sk_sk_l01
E/Samsung TTS( 1838): result : 2
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_sv_se_l01
E/Samsung TTS( 1838): result : 2
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_tr_tr_l01
E/Samsung TTS( 1838): result : 2
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_en_au_l01
E/Samsung TTS( 1838): result : 2
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_es_mx_l01
E/Samsung TTS( 1838): result : 2
E/Samsung TTS( 1838): appId : com.samsung.SMT.lang_fr_ca_l01
E/Samsung TTS( 1838): result : 2
,E/Zygote  ( 6860): MountEmulatedStorage()
E/Zygote  ( 6860): v2
I/libpersona( 6860): KNOX_SDCARD checking this for 10104
I/libpersona( 6860): KNOX_SDCARD not a persona
I/ActivityManager(  896): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6860 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6860): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6860): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6860): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/FOTA_Client( 6807): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 6807): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 6860): TimaSignature is unavailable
,D/ActivityThread( 6860): Added TimaKeyStore provider
,E/Zygote  ( 6880): MountEmulatedStorage()
E/Zygote  ( 6880): v2
I/libpersona( 6880): KNOX_SDCARD checking this for 10023
I/libpersona( 6880): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=6880 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6880): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6880): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6880): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 6860): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/PhenotypeConfigurator( 1473): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6880): TimaSignature is unavailable
,D/ActivityThread( 6880): Added TimaKeyStore provider
,I/art     (  896): Explicit concurrent mark sweep GC freed 77295(4MB) AllocSpace objects, 18(288KB) LOS objects, 17% free, 37MB/45MB, paused 1.702ms total 139.613ms
,I/DBG_DM  ( 3144): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/ActivityManager(  896): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6897 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 6897): MountEmulatedStorage()
E/Zygote  ( 6897): v2
I/libpersona( 6897): KNOX_SDCARD checking this for 1000
I/libpersona( 6897): KNOX_SDCARD not a persona
,I/SELinux ( 6897): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6897): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6897): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  896): Killing 5849:com.sec.android.widgetapp.digitalclock/u0a109 (adj 15): bgCount ##41
,D/ResourcesManager( 6880): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,E/GpsLocationProvider(  896): No APN found to select.
,D/TimaKeyStoreProvider( 6897): TimaSignature is unavailable
,D/ActivityThread( 6897): Added TimaKeyStore provider
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6880): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 6880): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1450100368472
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6880): MainReciver(): TIME_CHANGED
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
D/SecContentProvider2(  896): mCursor = null
,I/KLMS-2.4.511: ( 6880): StateImplV2(): dateTimeChanged().START : Mon Dec 14 14:39:28 GMT+01:00 2015
,D/ResourcesManager( 6897): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager(  896): showStatusBarByNotification() mOpenByNotification=false
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6880): StateImplV2(): dateTimeChanged().END
,E/ActivityThread( 1754): Failed to find provider info for com.android.contacts.metadata
,W/System.err( 5991): android.provider.Settings$SettingNotFoundException: TIME_DIFFERENCE
,W/System.err( 5991): 	at android.provider.Settings$System.getLongForUser(Settings.java:1679)
W/System.err( 5991): 	at android.provider.Settings$System.getLong(Settings.java:1669)
W/System.err( 5991): 	at com.sec.android.sCloudSync.g.d.b(SourceFile:83)
W/System.err( 5991): 	at com.sec.android.sCloudSync.Receivers.TimeChangedReceiver.onReceive(SourceFile:64)
W/System.err( 5991): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2991)
W/System.err( 5991): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
W/System.err( 5991): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
W/System.err( 5991): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5991): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5991): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
W/System.err( 5991): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5991): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5991): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
W/System.err( 5991): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
,I/DBG_DM  ( 3144): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3144): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/art     ( 1185): Explicit concurrent mark sweep GC freed 56493(2MB) AllocSpace objects, 8(14MB) LOS objects, 28% free, 39MB/55MB, paused 520us total 55.091ms
,D/ResourcesManager( 1185): creating new AssetManager and set to /system/priv-app/SyncmlDM/SyncmlDM.apk
,V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,I/DIAGMON_AGENT( 6897): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,E/bt-btif ( 6480): ...preload_wait_timeout (retried:0/max-retry:1)...
,D/bt_userial( 6480): RX termination
W/bt_userial( 6480): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 6480): Leaving userial_read_thread()
D/bt_vendor( 6480): op for 4
I/bt_userial_vendor( 6480): device fd = 65 close
,D/bt_vendor( 6480): op for 0
,D/bt_upio ( 6480): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 6480): is_emulator_context : 0
D/bt_upio ( 6480): is_rfkill_disabled ? [0]
,D/bt_vendor( 6480): cleanup
,I/DBG_DM  ( 3144): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 3144): [com.wssyncmldm.ui.XUIFotaPostponeActivity(378/lllIlIlIIIllIIlIllIl)] No idle Postpone
,I/DBG_DM  ( 3144): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
,E/Zygote  ( 6920): MountEmulatedStorage()
I/ActivityManager(  896): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/com.sec.android.fota.osp.time.ServerTimeReceiver: pid=6920 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
E/Zygote  ( 6920): v2
I/libpersona( 6920): KNOX_SDCARD checking this for 10042
I/libpersona( 6920): KNOX_SDCARD not a persona
,D/KnoxNotification( 1185): ----- inflateViews : modified publicViewLocal -----
,D/SyncManager(  896): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 19043, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager(  896): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 203648, reason: UserStart
,I/SELinux ( 6920): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6920): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6920): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DIAGMON_AGENT( 6897): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KnoxNotification( 1185): ----- inflateViews : modified KnoxViewLocal -----
,D/DelayedSyncController( 6860): Delaying sync.
,D/PersonaManager( 1185): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 1185): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@35efd599
,D/TimaKeyStoreProvider( 6920): TimaSignature is unavailable
,D/PersonaManager( 1185): isKioskContainerExistOnDevice
D/ActivityThread( 6920): Added TimaKeyStore provider
,D/PersonaManager( 1185): isKioskContainerExistOnDevice
,D/PanelView( 1185): There is/are notification(s) 
,D/PanelView( 1185): There is/are notification(s) 
,D/ResourcesManager( 6920): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,D/SecContentProvider2(  896): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  896): mCursor = null
,I/bt_hci_bdroid( 6480): init
,I/bt_vendor( 6480): init
I/bt_vnd_conf( 6480): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 6480): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 6480): userial_init
D/bt_vendor( 6480): op for 5
,D/bt_vendor( 6480): op for 0
,D/bt_upio ( 6480): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 6480): is_emulator_context : 0
,D/bt_upio ( 6480): is_rfkill_disabled ? [0]
D/bt_upio ( 6480): is_rfkill_disabled ? [0]
D/bt_vendor( 6480): op for 0
,D/bt_upio ( 6480): upio_set_bluetooth_power(on: 1)
D/bt_upio ( 6480): is_emulator_context : 0
D/bt_upio ( 6480): is_rfkill_disabled ? [0]
,D/bt_vendor( 6480): op for 3
,I/bt_userial_vendor( 6480): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 6480): userial_vendor_open():UART is setup
,I/bt_userial_vendor( 6480): device fd = 65 open
D/bt_vendor( 6480): op for 1
D/bt_userial( 6480): Entering userial_read_thread()
E/bt_hwcfg( 6480): Start CFG HW, HCI reset
,I/ActivityManager(  896): Killing 5865:com.sec.android.widgetapp.dualclockdigital/u0a115 (adj 15): bgCount ##41
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SO_AGENT( 6920): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,I/SA      ( 6053): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,E/Auth.Api.Credentials( 1754): [CredentialSyncAdapter] Unknown sync event.
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/bt_hwcfg( 6480): Read Local Name after HCI reset
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,I/DIAGMON_AGENT( 6897): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6897): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6897): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6897): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
D/bt_hwcfg( 6480): Chipset BCM4335C0
D/bt_hwcfg( 6480): Target name = [BCM4335C0]
,I/bt_hwcfg( 6480): module_type[semco].
I/bt_hwcfg( 6480): not ZERO...
I/bt_hwcfg( 6480): module_type[semco] is invalid.
E/bt_hwcfg( 6480): patchram path ORG . BCM4335C0
E/bt_hwcfg( 6480): patchram path ORG .. BCM4335C0
E/bt_hwcfg( 6480): patchram path ORG bcm2079xB4_firmware.ncd BCM4335C0
E/bt_hwcfg( 6480): patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335C0
E/bt_hwcfg( 6480): patchram path ORG bcm2079xB5_firmware.ncd BCM4335C0
E/bt_hwcfg( 6480): patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335C0
E/bt_hwcfg( 6480): patchram path ORG bcm4335_V0093.0399.hcd BCM4335C0
E/bt_hwcfg( 6480): patchram path ORG bcm4335_V0093.0399_wisol.hcd BCM4335C0
E/bt_hwcfg( 6480): fw ver (org)0.0
E/bt_hwcfg( 6480): vendor lib preload failed to locate firmware patch file
E/bt_hwcfg( 6480): Remove module rev, try again BCM4335
D/bt_hwcfg( 6480): Target name = [BCM4335]
I/bt_hwcfg( 6480): module_type[semco].
I/bt_hwcfg( 6480): not ZERO...
I/bt_hwcfg( 6480): module_type[semco] is invalid.
E/bt_hwcfg( 6480): patchram path ORG . BCM4335
E/bt_hwcfg( 6480): patchram path ORG .. BCM4335
E/bt_hwcfg( 6480): patchram path ORG bcm2079xB4_firmware.ncd BCM4335
E/bt_hwcfg( 6480): patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335
E/bt_hwcfg( 6480): patchram path ORG bcm2079xB5_firmware.ncd BCM4335
E/bt_hwcfg( 6480): patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335
E/bt_hwcfg( 6480): patchram path ORG bcm4335_V0093.0399.hcd BCM4335
I/bt_hwcfg( 6480): patch(org) : bcm4335_V0093.0399.hcd
I/bt_hwcfg( 6480): Found patchfile: /vendor/firmware/bcm4335_V0093.0399.hcd
E/bt_hwcfg( 6480): ORG patchram base 0093
E/bt_hwcfg( 6480): ORG patchram minor 0399
E/bt_hwcfg( 6480): fw ver (org)93.399
E/bt_hwcfg( 6480): Final Patchram is /vendor/firmware/bcm4335_V0093.0399.hcd
,E/Zygote  ( 6941): MountEmulatedStorage()
I/libpersona( 6941): KNOX_SDCARD checking this for 10076
E/Zygote  ( 6941): v2
I/libpersona( 6941): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6941 uid=10076 gids={50076, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6941): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  896): Killing 5805:com.android.defcontainer/u0a7 (adj 15): bgCount ##41
E/lowmemorykiller(  251): Error writing /proc/5805/oom_score_adj; errno=22
I/bt_hwcfg( 6480): Axi patch failure or not include AXI patching
I/SELinux ( 6941): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6941): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/bt_hwcfg( 6480): bt vendor lib: set UART baud 3000000
,D/TimaKeyStoreProvider( 6941): TimaSignature is unavailable
,D/ActivityThread( 6941): Added TimaKeyStore provider
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 6941): creating new AssetManager and set to /system/priv-app/sCloudDataSync/sCloudDataSync.apk
,I/ActivityManager(  896): Killing 5939:com.google.android.partnersetup/u0a19 (adj 15): bgCount ##41
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,I/System.out( 1473): (HTTPLog)-Static: isSBSettingEnabled false
,I/ Time Manager ( 6941): Time Difference not stored. TIME_DIFFERENCE
,E/Zygote  ( 6959): MountEmulatedStorage()
I/libpersona( 6959): KNOX_SDCARD checking this for 10106
E/Zygote  ( 6959): v2
I/libpersona( 6959): KNOX_SDCARD not a persona
,I/SELinux ( 6959): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  896): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6959 uid=10106 gids={50106, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/SELinux ( 6959): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6959): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  896): Killing 5957:com.samsung.groupcast/u0a20 (adj 15): bgCount ##41
,I/FOTA_Client( 6807): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/TimaKeyStoreProvider( 6959): TimaSignature is unavailable
,D/ActivityThread( 6959): Added TimaKeyStore provider
,I/FOTA_Client( 6807): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
I/ActivityManager(  896): Killing 6007:com.policydm/1000 (adj 15): bgCount ##41
,I/System.out( 1473): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1473): Tagging socket 65 with tag 1000120300000000{268440067,0} uid -1, pid: 1473, getuid(): 10015
,D/ResourcesManager( 6959): creating new AssetManager and set to /system/app/ClockPackage_Osup/ClockPackage_Osup.apk
,W/ResourcesManager( 6959): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6959): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6959): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6959): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 6959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6959): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,I/FOTA_Client( 6807): [lIIIIlIlIlIlllllllll(200/lllIlIlIIIllIIlIllIl)] Polling time is not vaild
,I/FOTA_Client( 6807): [com.sec.android.fotaclient.FotaUpdaterReceiver(112/onReceive)] Polling time is already passed. Start device init Immediately
,I/FOTA_Client( 6807): [com.sec.android.fotaclient.llllIIIllIlIIIIllllI(104/handleMessage)] Update State: Check condition to decide next state: 1
,I/FOTA_Client( 6807): [com.sec.android.fotaclient.llllIIIllIlIIIIllllI(121/handleMessage)] Update State: Initialize polling update: 1
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FOTA_Client( 6807): [lllllllIlllIIlllIlIl(88/llllIIIllIlIIIIllllI)] WiFi Network is connected
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6880): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 6880): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450100369064
,I/KLMS-2.4.511: ( 6880): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6880): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 6880): StateImplV2(): networkChangeListener().START
,D/SettingsProvider(  896): name = next_alarm_formatted
D/SettingsProvider(  896): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  896): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  896): selectionArgs: false
D/SettingsProvider(  896): selectionArgs: 10106
D/SecContentProvider(  896): uri = 17 selection = isSettingsChangesAllowed
I/KLMS-2.4.511: ( 6880): NetworkChangeOperations(): uploadRequestLog().START 
D/SettingsProvider(  896): ret = -1
,I/FOTA_Client( 6807): [lIlIIIlllIlIlIlIIIll(31/llIIIIlllllIIllIIllI)] Request Network Connection
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FOTA_Client( 6807): [lllllllIlllIIlllIlIl(88/llllIIIllIlIIIIllllI)] WiFi Network is connected
,I/KLMS-2.4.511: ( 6880): StateImplV2(): networkChangeListener().END
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,I/FOTA_Client( 6807): [com.sec.android.fotaclient.FotaInitUpdateService(352/llllIIIllIlIIIIllllI)] Request NetActionGetPolling
,I/FOTA_Client( 6807): [com.sec.android.fota.osp.time.llIIIIlllllIIllIIllI(82/llIIIIlllllIIllIIllI)] Server time is zero
,I/FOTA_Client( 6807): [com.sec.android.fota.osp.time.llIIIIlllllIIllIIllI(111/llllIIIllIlIIIIllllI)] Request ServerTime
,I/FOTA_Client( 6807): [com.sec.android.fota.osp.http.RestClient(264/llIIIIlllllIIllIIllI)] =====================================================================
,D/ConnectivityService(  896): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  896): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
D/ConnectivityService(  896): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  896): apparently satisfied.  currentScore=60
D/ConnectivityService(  896): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1754): CM callback handler got msg 524290
,E/Zygote  ( 6980): MountEmulatedStorage()
I/libpersona( 6980): KNOX_SDCARD checking this for 10036
E/Zygote  ( 6980): v2
I/libpersona( 6980): KNOX_SDCARD not a persona
,I/qtaguid ( 1473): Tagging socket 70 with tag 1000120300000000{268440067,0} uid -1, pid: 1473, getuid(): 10015
,I/ActivityManager(  896): Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=6980 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FOTA_Client( 6807): [com.sec.android.fota.osp.http.RestClient(277/llIIIIlllllIIllIIllI)] =====================================================================
,I/SELinux ( 6980): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6980): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6980): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 6807): Thread-1058(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6807): Thread-1058(ApacheHTTPLog):isShipBuild true
,I/System.out( 6807): Thread-1058(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/TimaKeyStoreProvider( 6980): TimaSignature is unavailable
,D/ActivityThread( 6980): Added TimaKeyStore provider
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DelayedSyncController( 6860): Delaying sync.
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 6980): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,W/ResourcesManager( 6980): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6980): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/Minikin ( 6980): addFont failed to create font /system/fonts/SamsungSans-light.ttf
,E/Zygote  ( 6998): MountEmulatedStorage()
,E/Zygote  ( 6998): v2
I/libpersona( 6998): KNOX_SDCARD checking this for 10116
I/libpersona( 6998): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6998 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,I/System.out( 6807): AsyncTask #1 calls detatch()
,I/SELinux ( 6998): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/FOTA_Client( 6807): [com.sec.android.fota.osp.time.llIIIIlllllIIllIIllI(139/llllIIIllIlIIIIllllI)] Receive result: success in ServerTime
,I/SELinux ( 6998): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6998): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/FOTA_Client( 6807): [com.sec.android.fota.osp.http.RestClient(264/llIIIIlllllIIllIIllI)] =====================================================================
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/bt_hwcfg( 6480): bt vendor lib: set UART baud 115200
I/bt_hwcfg( 6480): FW Download delta = 556819
D/bt_hwcfg( 6480): Settlement delay -- 100 ms
I/bt_hwcfg( 6480): Setting fw settlement delay to 100 
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 6998): TimaSignature is unavailable
,D/ActivityThread( 6998): Added TimaKeyStore provider
,I/FOTA_Client( 6807): [com.sec.android.fota.osp.http.RestClient(277/llIIIIlllllIIllIIllI)] =====================================================================
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PicasaService( 5241): start picasa sync
,I/SO_AGENT( 6920): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/PicasaService( 5241): end picasa sync
,D/ResourcesManager( 6998): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/elm:14491( 6998): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14491( 6998): ELMEngine.ELMEngine( context ).
,D/elm:14491( 6998): MDMBridge.setEnterpriseBridge()
,I/dhcpcd  ( 6680): wlan0: sending IPv6 Router Solicitation
,D/elm:14491( 6998): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,D/elm:14491( 6998): ElmAgentService : onCreate()
,D/elm:14491( 6998): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/elm:14491( 6998): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:14491( 6998): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:14491( 6998): ModuleBase.ModifySetAlarm()
D/elm:14491( 6998): MDMBridge.getInstance()
D/elm:14491( 6998): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 7022): MountEmulatedStorage()
E/Zygote  ( 7022): v2
I/libpersona( 7022): KNOX_SDCARD checking this for 1000
I/libpersona( 7022): KNOX_SDCARD not a persona
,I/SELinux ( 7022): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7022): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
I/ActivityManager(  896): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7022 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 7022): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:14491( 6998): ElmAgentService : onDestroy().
,I/bt_hwcfg( 6480): bt vendor lib: set UART baud 3000000
,I/art     (  322): Explicit concurrent mark sweep GC freed 8736(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 312us total 13.172ms
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 272us total 10ms
,D/TimaKeyStoreProvider( 7022): TimaSignature is unavailable
,D/ActivityThread( 7022): Added TimaKeyStore provider
,I/System.out( 6807): AsyncTask #1 calls detatch()
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 273us total 9.819ms
I/FOTA_Client( 6807): [IlIIlIIlIllllIlllIII(97/llIIIIlllllIIllIIllI)] result is success
,I/FOTA_Client( 6807): [IIIlIllIlIIIIIlIIIll(78/llIIIIlllllIIllIIllI)] Response Network Connection
,I/FOTA_Client( 6807): [com.sec.android.fotaclient.llIIIIlllllIIllIIllI(304/llIIIIlllllIIllIIllI)] Receive result: success in NetActionGetPolling
,I/bt_hwcfg( 6480): vendor lib fwcfg completed
,I/        ( 6480): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 6480): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6480): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6480): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6480): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6480): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6480): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6480): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6480): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6480): BTE_InitTraceLevels -- TRC_PAN
,I/        ( 6480): BTE_InitTraceLevels -- TRC_SAP
I/        ( 6480): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6480): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6480): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6480): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6480): BTE_InitTraceLevels -- TRC_BTIF
,I/        ( 6480): BTE_InitTraceLevels -- TRC_PROTOCOL
,E/Zygote  ( 7037): MountEmulatedStorage()
E/Zygote  ( 7037): v2
I/libpersona( 7037): KNOX_SDCARD checking this for 10172
I/libpersona( 7037): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7037 uid=10172 gids={50172, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 7037): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  896): Killing 4598:com.sec.spp.push/u0a43 (adj 15): bgCount ##41
,I/SELinux ( 7037): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7037): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  896): Killing 6027:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): bgCount ##41
,D/ResourcesManager( 7022): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,D/TimaKeyStoreProvider( 7037): TimaSignature is unavailable
,D/ActivityThread( 7037): Added TimaKeyStore provider
D/SettingsProvider(  896): name = FOTA_CLIENT_HEARTBEAT_PERIOD
D/SettingsProvider(  896): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  896): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  896): selectionArgs: false
D/SettingsProvider(  896): selectionArgs: 10014
D/SecContentProvider(  896): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  896): ret = -1
,D/SettingsProvider(  896): name = FOTA_CLIENT_HEARTBEAT_ADD
,D/SettingsProvider(  896): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  896): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  896): selectionArgs: false
D/SettingsProvider(  896): selectionArgs: 10014
D/SecContentProvider(  896): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  896): ret = -1
,W/BackupManagerService(  896): dataChanged but no participant pkg='com.android.providers.settings' uid=10014
,I/FOTA_Client( 6807): [lIIIIlIlIlIlllllllll(157/llllIIIllIlIIIIllllI)] Calculate next polling time
,D/ResourcesManager( 7037): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,W/ResourcesManager( 7037): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7037): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/PhenotypeConfigurator( 1473): Server returned 404
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SettingsProvider(  896): name = FOTA_CLIENT_POLLING_TIME
D/SettingsProvider(  896): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  896): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  896): selectionArgs: false
D/SettingsProvider(  896): selectionArgs: 10014
D/SecContentProvider(  896): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  896): ret = -1
,W/BackupManagerService(  896): dataChanged but no participant pkg='com.android.providers.settings' uid=10014
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,W/bt-l2cap( 6480): l2c_link_processs_ble_num_bufs 15
,E/bt-btm  ( 6480): BTM_SecRegister:p_cb_info->p_le_callback == 0xafc4bb05 
E/bt-btm  ( 6480): BTM_SecRegister: btm_cb.api.p_le_callback = 0xafc4bb05 
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7064): MountEmulatedStorage()
E/Zygote  ( 7064): v2
I/libpersona( 7064): KNOX_SDCARD checking this for 10051
I/libpersona( 7064): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7064 uid=10051 gids={50051, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7064): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7064): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7064): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/SecurityLogAgent( 6453): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6453): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6453): StateMachine : Current State = 1
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 7064): TimaSignature is unavailable
,D/ActivityThread( 7064): Added TimaKeyStore provider
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FOTA_Client( 6807): [IlIIlIIlIllllIlllIII(194/llIIllllIIlllIIIIlll)] Find Firmware version in Version List
,E/Zygote  ( 7080): MountEmulatedStorage()
,E/Zygote  ( 7080): v2
I/FOTA_Client( 6807): [com.sec.android.fotaclient.llllIIIllIlIIIIllllI(131/handleMessage)] Update State: Need to polling update: 1
,I/libpersona( 7080): KNOX_SDCARD checking this for 1000
I/libpersona( 7080): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7080 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/FOTA_Client( 6807): [com.sec.android.fotaclient.FotaInitUpdateService(359/lllIlIlIIIllIIlIllIl)] request Polling
,I/SELinux ( 7080): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7080): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7080): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/FOTA_Client( 6807): [com.sec.android.fotaclient.llllIIIllIlIIIIllllI(137/handleMessage)] Update State: Finish update init: 1
,I/ActivityManager(  896): Killing 6074:com.sec.android.app.soundalive/u0a64 (adj 13): bgCount ##41
,D/TimaKeyStoreProvider( 7080): TimaSignature is unavailable
,D/ActivityThread( 7080): Added TimaKeyStore provider
,D/ResourcesManager( 7080): creating new AssetManager and set to /system/app/TimeService/TimeService.apk
,D/ResourcesManager( 7064): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ResourcesManager( 7064): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/TimeService( 7080): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450100369830
D/        ( 7080): TimeServiceNative: User Time to be set is 1450100369831
D/QC-time-services( 7080): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 7080): Lib:time_genoff_operation: pargs->operation = 0
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/QC-time-services( 7080): Lib:time_genoff_operation: pargs->ts_val = 1450100369831
,D/QC-time-services(  340): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 7080): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  340): Daemon:Received base = 2, unit = 1, operation = 0,value = 1450100369831
,D/QC-time-services(  340): Daemon:genoff_opr: Base = 2, val = 1450100369831, operation = 0
D/QC-time-services(  340): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/22/70 20:27:55
D/QC-time-services(  340): Daemon:Value read from RTC seconds = 9664075000
,D/QC-time-services(  340): Daemon:new time 1450100369831 
D/QC-time-services(  340): Daemon: delta 1440436294831 genoff 1440436294831 
D/QC-time-services(  340): Daemon:genoff_persistent_update: Writing genoff = 1440436294831 to memory
D/QC-time-services(  340): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  340): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
D/QC-time-services(  340): Updating the TOD offset
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
D/QC-time-services(  340): Daemon:genoff_persistent_update: Writing genoff = 1440436294831 to memory
D/QC-time-services(  340): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  340): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  340): Daemon:Update to modem bit set
D/QC-time-services(  340): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  340): Daemon: Base = 2, Value being sent to MODEM = 1124471494831
,E/QC-time-services( 7080): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  340): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  340): Daemon: Time-services: Waiting to acceptconnection
,V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityThread( 7022): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/CalendarProvider2( 7064): CalendarProvider2.onCreate() called
,I/System.out( 7022): Thread-1112(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,E/Zygote  ( 7099): MountEmulatedStorage()
E/Zygote  ( 7099): v2
I/libpersona( 7099): KNOX_SDCARD checking this for 10043
I/libpersona( 7099): KNOX_SDCARD not a persona
,I/System.out( 7022): Thread-1112(ApacheHTTPLog):isShipBuild true
,I/ActivityManager(  896): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7099 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7099): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7099): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7099): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/BluetoothAdapterProperties( 6480): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 0 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = false
I/System.out( 7022): Thread-1112(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
E/bt-btif ( 6480): Calling BTA_HhEnable
E/bt-btif ( 6480): btif_storage_get_adapter_property service_mask:0x2120048
D/BluetoothAdapterProperties( 6480): Address is:E0:DB:10:1F:C9:5E
E/BluetoothServiceJni( 6480): populateRssiValuesNative
I/bluedroid( 6480): getModelRssiValues
E/BluetoothServiceJni( 6480): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 6480): modelRssiValuesCallback, low, mid, high = -70,-60,127
,I/ActivityManager(  896): Killing 4960:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##41
,D/TimaKeyStoreProvider( 7099): TimaSignature is unavailable
,D/ActivityThread( 7099): Added TimaKeyStore provider
,I/art     (  896): Explicit concurrent mark sweep GC freed 50624(2MB) AllocSpace objects, 3(48KB) LOS objects, 17% free, 37MB/45MB, paused 1.535ms total 108.704ms
,D/BluetoothAdapterProperties( 6480): Name is: Note3-1
,D/SettingsProvider(  896): name = bluetooth_name
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BluetoothAdapterProperties( 6480): Scan Mode:20
D/BluetoothAdapterProperties( 6480): Discoverable Timeout:120
,D/BluetoothAdapterProperties( 6480): LE Address is:E0:B7:20:3E:93:BC
E/bt-btif ( 6480): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 6480): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
D/bt_vendor( 6480): op for 2
E/bt-btif ( 6480): btif_sock_init: !radio_req && !rfc_init
D/bt_vendor( 6480): op for 6
E/bt-btif ( 6480): btif_sock_init: !vhci_init
,D/IOP_DB_BT( 6480): db_open: file /etc/bluetooth/iop_bt.db
D/bt_vendor( 6480): op for 7
D/bt_upio ( 6480): proc btwrite assertion
,D/IOP_DB_BT( 6480): db_open: db_open : handle 3026214928l, read 14063 bytes onto local cache
D/IOP_DB_BT( 6480): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 6480): db_query: result 1
I/        ( 6480): iop_db_open: iop_db_open status 0
,D/bt_vendor( 6480): op for 7
D/bt_upio ( 6480): BT_WAKE is asserted already
D/bte_conf( 6480): Device ID record 1 : primary
D/bte_conf( 6480):   vendorId            = 0075
D/bte_conf( 6480):   vendorIdSource      = 0001
D/bte_conf( 6480):   product             = 0100
D/bte_conf( 6480):   version             = 0200
D/bte_conf( 6480):   clientExecutableURL = 
D/bte_conf( 6480):   serviceDescription  = 
D/bte_conf( 6480):   documentationURL    = 
D/bte_conf( 6480): bte_load_did_conf no section named DID2.
,D/bt_vendor( 6480): op for 7
D/bt_upio ( 6480): BT_WAKE is asserted already
D/BluetoothPanServiceJni( 6480): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothAdapterState( 6480): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6480): ScanMode =  20
D/BluetoothAdapterProperties( 6480): State =  11
,D/SecContentProvider(  896): uri = 3 selection = isDiscoverableEnabled
,D/BluetoothAdapterProperties( 6480): Setting state to 12
I/BluetoothAdapterState( 6480): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterProperties( 6480): Scan Mode:21
D/BluetoothAdapterProperties( 6480): Discoverable Timeout:120
,D/SettingsProvider(  896): name = bluetooth_a2dp_sink_mode
D/SettingsProvider(  896): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  896): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  896): selectionArgs: false
D/SettingsProvider(  896): selectionArgs: 1002
D/SecContentProvider(  896): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  896): ret = -1
D/comdaemonstockapp( 3413): [Daemon_Stock]>>> Stockclock_DaemonService.java:63 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 3413): [Daemon_Stock]>>> Stockclock_DaemonService.java:64 [0:0] appServiceStatus: 0
D/comdaemonstockapp( 3413): [Daemon_Stock]>>> Stockclock_DaemonService.java:65 [0:0] [AR]: 0
,W/BackupManagerService(  896): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/comdaemonstockapp( 3413): [Daemon_Stock]>>> Stockclock_DaemonService.java:66 [0:0] [AR]: Next time = 0
I/System.out( 7022): Thread-1112 calls detatch()
,D/BluetoothAdapterService( 6480): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 6480): updateAdapterState state is 12
,E/bt_h4   ( 6480): vendor lib postload completed
D/bt_vendor( 6480): op for 7
D/bt_upio ( 6480): BT_WAKE is asserted already
,D/bt_vendor( 6480): op for 7
D/bt_upio ( 6480): BT_WAKE is asserted already
,D/bt_vendor( 6480): op for 7
,D/bt_upio ( 6480): BT_WAKE is asserted already
,D/bt_vendor( 6480): op for 7
,D/BluetoothAdapterService( 6480): Autoconnection is available 
D/BluetoothAdapterService( 6480): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 6480): starting service from this receiver
D/bt_upio ( 6480): BT_WAKE is asserted already
,D/bt_vendor( 6480): op for 7
D/bt_upio ( 6480): BT_WAKE is asserted already
,I/BluetoothAdapterState( 6480): Entering On State from state = 11
,D/bt_vendor( 6480): op for 7
D/bt_upio ( 6480): BT_WAKE is asserted already
,D/bt_vendor( 6480): op for 7
D/bt_upio ( 6480): BT_WAKE is asserted already
,D/bt_vendor( 6480): op for 7
D/bt_upio ( 6480): BT_WAKE is asserted already
,D/bt_vendor( 6480): op for 7
D/bt_upio ( 6480): BT_WAKE is asserted already
,D/daemonapp( 3413): [MSC_Accu_Daemon]>>> AWDS:70 [0:0] Act : androidintentactionTIME_SET, run:true
D/bt_vendor( 6480): op for 7
D/bt_upio ( 6480): BT_WAKE is asserted already
,D/comsamsunglog( 3413): [MSC_Accu_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3413): [MSC_Accu_Daemon]>>> daemonapp [Version : 14123102 ] [ 1 ] 
D/comsamsunglog( 3413): [MSC_Accu_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3413): [MSC_Accu_Daemon]>>> ====================================================================================================================
D/daemonapp( 3413): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/bt_vendor( 6480): op for 7
D/bt_upio ( 6480): BT_WAKE is asserted already
,D/bt_vendor( 6480): op for 7
D/bt_upio ( 6480): BT_WAKE is asserted already
,D/bt_vendor( 6480): op for 7
D/bt_upio ( 6480): BT_WAKE is asserted already
,D/daemonapp( 3413): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
D/daemonapp( 3413): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/ResourcesManager( 7099): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/bt_vendor( 6480): op for 7
D/bt_upio ( 6480): BT_WAKE is asserted already
,D/bt_vendor( 6480): op for 7
D/bt_upio ( 6480): BT_WAKE is asserted already
,D/bt_vendor( 6480): op for 7
D/bt_upio ( 6480): BT_WAKE is asserted already
,D/bt_vendor( 6480): op for 7
D/bt_upio ( 6480): BT_WAKE is asserted already
,D/bt_vendor( 6480): op for 7
D/bt_upio ( 6480): BT_WAKE is asserted already
,D/daemonapp( 3413): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/BluetoothA2dp(  896): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 6480): onBluetoothStateChange: up=true
D/BluetoothA2dp( 2934): onBluetoothStateChange: up=true
,I/BluetoothPbapService( 6480): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,D/daemonapp( 3413): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/InputMethodManagerService(  896): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothManager( 6648): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService(  896): [BT Setting State] State =12
I/InputMethodManagerService(  896): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
D/daemonapp( 3413): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/settings
D/BluetoothHeadset( 1399): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@637281f, true
,I/SamsungIME( 1722): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothHeadset( 1399): registerMessageListener
,D/daemonapp( 3413): [MSC_Accu_Daemon]>>> AWDS:113 [0:0] SerStus:true,TmpS:1,AtRfr:3, checkCurrent: 0
,D/daemonapp( 3413): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/BluetoothPbapService( 6480): Handler(): got msg=1
D/HeadsetService( 6480): registerMessageListener
,D/HeadsetService( 6480): registerMessageListener
,D/HeadsetStateMachine( 6480): Disconnected process message: 70
D/HeadsetStateMachine( 6480): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2c5cd1a5
I/Telecom ( 1399): BluetoothPhoneService: updateHeadsetWithCallState
D/daemonapp( 3413): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
I/Telecom ( 1399): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/SecContentProvider(  896): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/daemonapp( 3413): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/BluetoothTile( 1185):  onBluetoothStateChange:
,D/HeadsetStateMachine( 6480): Disconnected process message: 9
,D/HeadsetStateMachine( 6480): mNumActive: 0 mNumHeld: 0 mCallState: 6
,V/BluetoothPbapService( 6480): PBAP Service initSocket try: 0
,D/BluetoothManagerService(  896): Broadcasting onBluetoothServiceUp() to 0 receivers.
D/BluetoothTile( 1185):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1185): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/daemonapp( 3413): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,D/StatusBarManagerService(  896): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
,D/StatusBarManagerService(  896): setIconVisibility slot=bluetooth visible=true
D/PhoneStatusBar( 1185): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
,D/audio_hw_primary(  298): adev_set_parameters: enter: A2dpSuspended=false
V/voice   (  298): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  298): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  298): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  298): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  298): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  298): adev_set_parameters: exit
E/HeadsetStateMachine( 6480): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/BluetoothTile( 1185):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 1185): onStateChanged: Bluetooth
,W/BluetoothAdapter( 6480): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 6480): set MAP SDP message type : 1
,D/bt_vendor( 6480): op for 7
,D/bt_upio ( 6480): BT_WAKE is asserted already
D/BluetoothSocket( 6480): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
D/BluetoothSocket( 6480): bindListen(), new LocalSocket 
,D/BluetoothSocket( 6480): bindListen(), new LocalSocket.getInputStream() 
W/BluetoothAdapter( 6480): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothSocket( 6480): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3603b97a
D/BluetoothSocket( 6480): channel: 19
D/BluetoothPbapService( 6480): PBAP Socket is BluetoothServerSocket
,D/BluetoothSocket( 6480): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 6480): bindListen(), new LocalSocket 
D/BluetoothSocket( 6480): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6480): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1075552b
,D/bt_vendor( 6480): op for 7
D/BluetoothSocket( 6480): channel: 5
D/bt_upio ( 6480): BT_WAKE is asserted already
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CheckinService( 1754): Checkin interval check for package: unspecified last checkin: 1449576540818 min interval config: 0 actual interval: 523829328
,V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/DriveInitializer( 1754): Awaiting to be initialized
,W/DriveInitializer( 1754): Background init thread started
,E/SPPClientService( 7099): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 7099): [PushClientApplication] Push log off : This is Ship build version
,I/ActivityManager(  896): Killing 6093:com.google.android.apps.docs/u0a112 (adj 13): bgCount ##41
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 1754): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,D/SPPClientService( 7099): PushLog.txt file is not deleted.
D/SPPClientService( 7099): PushLog.txt file is not deleted.
D/SPPClientService( 7099): ============PushLog. stop!
,E/SPPClientService( 7099): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6053): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 6053): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6053): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6053): [SLFUCHKMGR] constructor called
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6053): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6053): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6053): [SCU] == networkStateCheck == true
,I/SA      ( 6053): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6053): isChinaCountryCode : false
I/SA      ( 6053): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6053): [OR] == networkStateCheck true ==
,D/PerfProfileCollectorService( 1754): User is not opt-in to Usage & Diagnostics.
D/PerfProfileCollectorService( 1754): removeStateFiles() called
,D/PerfProfileCollectorService( 1754): User is not opt-in to Usage & Diagnostics.
,I/SA      ( 6053): [OR] GetMyCountryZoneTask
,I/SA      ( 6053): [OR] onReceive END
,I/ActivityManager(  896): Killing 6113:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##41
,I/SA      ( 6053): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,I/SA      ( 6053): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6053): [SSP] query invoked
,I/SA      ( 6053): [TPMU] GetMccFromDB : null
I/SA      ( 6053): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6053): [TPM] isNoProxy(default) : true
,E/WifiStateMachine(  896): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/Zygote  ( 7144): MountEmulatedStorage()
E/Zygote  ( 7144): v2
I/libpersona( 7144): KNOX_SDCARD checking this for 10074
I/libpersona( 7144): KNOX_SDCARD not a persona
,E/File    ( 6053): fail readDirectory() errno=2
,I/ActivityManager(  896): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7144 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7144): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7144): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7144): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7144): TimaSignature is unavailable
,D/ActivityThread( 7144): Added TimaKeyStore provider
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7144): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,W/DriveInitializer( 1754): Background init thread ended
,I/GoogleURLConnFactory( 1754): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  896): Killing 6133:com.samsung.android.app.watchmanagerstub/u0a126 (adj 13): bgCount ##41
,I/System.out( 1473): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1473): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1473): Tagging socket 82 with tag 1000040100000000{268436481,0} uid 10015, pid: 1473, getuid(): 10015
,V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/sCloudBackupApp( 7144): sCloudBackupApp Version Info : 3.13.7.KK_APP
I/SCloudBackupReceiver( 7144): Other Intent
,I/KnoxUsageLogPro( 5419): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 5419): premStatus:2
,I/KnoxUsageLogPro( 5419): isEulaShown : false
I/KnoxUsageLogPro( 5419): KnoxUsageReceiver onReceive : not Processible, just return
,I/qtaguid ( 1473): Tagging socket 86 with tag 1000040100000000{268436481,0} uid 10015, pid: 1473, getuid(): 10015
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7173): MountEmulatedStorage()
E/Zygote  ( 7173): v2
I/libpersona( 7173): KNOX_SDCARD checking this for 10146
I/libpersona( 7173): KNOX_SDCARD not a persona
,I/art     ( 1754): Explicit concurrent mark sweep GC freed 35788(2MB) AllocSpace objects, 30(480KB) LOS objects, 40% free, 22MB/38MB, paused 754us total 48.647ms
,I/ActivityManager(  896): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7173 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  896): Killing 6148:com.samsung.helphub/1000 (adj 13): bgCount ##41
,I/SELinux ( 7173): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7173): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7173): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1754): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1754): (HTTPLog)-Static: isShipBuild true
I/System.out( 1754): (HTTPLog)-Thread-264-816582461: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1754): (HTTPLog)-Static: isSBSettingEnabled false
,I/SurfaceFlinger(  254): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  254): id=14 Removed Uoast (-2/9)
,I/System.out( 1754): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1754): Tagging socket 86 with tag 1000210100000000{268443905,0} uid -1, pid: 1754, getuid(): 10015
D/PowerManagerService(  896): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 896) eventTime = 173109
D/PowerManagerService(  896): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=896 (0x0)
,D/PowerManagerService(  896): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=896, ws=WorkSource{10067}) (elapsedTime=3474)
,D/TimaKeyStoreProvider( 7173): TimaSignature is unavailable
,D/ActivityThread( 7173): Added TimaKeyStore provider
,D/OpenGLRenderer( 3144): Render dirty regions requested: true
,D/ResourcesManager( 7173): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/qtaguid ( 1754): Tagging socket 110 with tag 1000210100000000{268443905,0} uid -1, pid: 1754, getuid(): 10015
,D/Atlas   ( 3144): Validating map...
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  254): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService(  896): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=896
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Adreno-EGL( 3144): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 3144): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 3144): Build Date: 11/19/14 Wed
I/Adreno-EGL( 3144): Local Branch: mybranch5813579
I/Adreno-EGL( 3144): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 3144): Local Patches: NONE
I/Adreno-EGL( 3144): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,I/OpenGLRenderer( 3144): Initialized EGL, version 1.4
,I/OpenGLRenderer( 3144): HWUI protection enabled for context ,  &this =0xaf122088 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 3144): Enabling debug mode 0
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7173): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7173): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/PeopleSync( 1754): onPerformSync() [5005f081]
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7173): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7173): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1473): Vacuum at: now=1450100370799 tag=VacuumService
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  291): DCD ON
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PeopleSync( 1754): Setting subscription: result=true [5005f081]
,I/PeopleSync( 1754): Starting sync, feed=null [5005f081]
,W/BaseAppContext( 1754): Using Auth Proxy for data requests.
,W/BaseAppContext( 1754): Using Auth Proxy for data requests.
,I/dex2oat ( 7219): ----------------------------------------------------
I/dex2oat ( 7219): <SS>: S T A R T I N G . . .
I/dex2oat ( 7219): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 7219): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xnorelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/cache/ads-1117141150.jar --oat-fd=112 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/cache/ads-1117141150.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/BaseAppContext( 1754): Using Auth Proxy for data requests.
,I/PeopleSync( 1754): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,I/WebViewFactory( 7173): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 7173): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7173): Loading: webviewchromium
,I/LibraryLoader( 7173): Time to load native libraries: 5 ms (timestamps 3493-3498)
I/LibraryLoader( 7173): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7173): Binding Chromium to main looper Looper (main, tid 1) {36a7fb27}
,I/LibraryLoader( 7173): Expected native library version number "",actual native library version number ""
,I/chromium( 7173): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/dex2oat ( 7219): dex2oat took 50.357ms (threads: 4)
,I/BrowserStartupController( 7173): Initializing chromium process, renderers=0
,W/art     ( 7173): Attempt to remove local handle scope entry from IRT, ignoring
,I/System.out( 1473): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1473): Tagging socket 82 with tag 1000040100000000{268436481,0} uid 10015, pid: 1473, getuid(): 10015
,W/chromium( 7173): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7173): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46780 len=2953
,W/AudioManagerAndroid( 7173): Requires BLUETOOTH permission
I/chromium( 7173): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229536 len:643667
,I/Adreno-EGL( 7173): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7173): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7173): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7173): Local Branch: mybranch5813579
I/Adreno-EGL( 7173): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7173): Local Patches: NONE
I/Adreno-EGL( 7173): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,I/SA      ( 6053): [RC New] Execute method=[GET] start
,I/NSApplication( 7173): Starting up...
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6053): [RC New] Security=[true]
,I/System.out( 6053): Thread-975(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6053): Thread-975(ApacheHTTPLog):isShipBuild true
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/System.out( 6053): Thread-975(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7248): MountEmulatedStorage()
E/Zygote  ( 7248): v2
I/libpersona( 7248): KNOX_SDCARD checking this for 10158
I/libpersona( 7248): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7248 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  896): Killing 6164:com.sec.kidsplat.installer/u0a189 (adj 13): bgCount ##41
,I/SELinux ( 7248): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7248): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7248): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7248): TimaSignature is unavailable
,D/ActivityThread( 7248): Added TimaKeyStore provider
,D/ResourcesManager( 7248): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7248): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7248): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7248): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7248): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7248): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/System.out( 1754): (HTTPLog)-Static: isSBSettingEnabled false
,I/QuickConnect( 7248): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  896): exchangeData() failure , invalid userId
,D/RCPManagerService(  896): exchangeData() failure , invalid userId
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6453): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6453): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6453): StateMachine : Current State = 1
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6453): StateMachine : Changed Current State = 1
,I/ActivityManager(  896): Killing 6188:com.sec.android.app.samsungapps/u0a45 (adj 13): bgCount ##41
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,I/System.out( 1754): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1754): Tagging socket 113 with tag 1000150000000000{268440832,0} uid 10015, pid: 1754, getuid(): 10015
,E/Zygote  ( 7265): MountEmulatedStorage()
I/libpersona( 7265): KNOX_SDCARD checking this for 10200
E/Zygote  ( 7265): v2
I/libpersona( 7265): KNOX_SDCARD not a persona
,I/CalendarProvider2( 7064): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/ActivityManager(  896): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7265 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/qtaguid ( 1754): Tagging socket 116 with tag 1000150000000000{268440832,0} uid 10015, pid: 1754, getuid(): 10015
,I/SELinux ( 7265): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7265): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7265): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7265): TimaSignature is unavailable
,D/ActivityThread( 7265): Added TimaKeyStore provider
,I/ActivityManager(  896): Killing 6220:com.sec.enterprise.knox.cloudmdm.smdms/u0a201 (adj 13): bgCount ##41
,D/ResourcesManager( 7265): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  896): Killing 5343:sstream.app/u0a25 (adj 13): bgCount ##41
,I/iu.SyncManager( 1754): SYNC; picasa accounts
,I/qtaguid ( 1754): Untagging socket 113
,I/PhenotypeConfigurator( 1473): Scheduling Phenotype for one-off execution 1344 seconds from now (1450100371553)
,D/NetworkLogImpl( 1754): Loaded NetworkSpeedPredictor
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/iu.Environment( 1754): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/iu.UploadsManager( 1754): num queued entries: 0
,I/iu.UploadsManager( 1754): num updated entries: 0
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/iu.SyncManager( 1754): NEXT; no task
,D/GetConfigurationSnapshotOperation( 1473): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7286): MountEmulatedStorage()
E/Zygote  ( 7286): v2
I/libpersona( 7286): KNOX_SDCARD checking this for 10045
I/libpersona( 7286): KNOX_SDCARD not a persona
,I/SELinux ( 7286): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7286): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
I/ActivityManager(  896): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7286 uid=10045 gids={50045, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux ( 7286): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/bt_vendor( 6480): op for 7
,I/PhenotypeFlagCommitter( 1473): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,D/TimaKeyStoreProvider( 7286): TimaSignature is unavailable
,D/ActivityThread( 7286): Added TimaKeyStore provider
,I/GoogleURLConnFactory( 1473): Using platform SSLCertificateSocketFactory
,D/ResourcesManager( 7286): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,I/System.out( 1754): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1754): Untagging socket 86
,I/System.out( 1754): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1754): Tagging socket 121 with tag 1000010400000000{268435716,0} uid -1, pid: 1754, getuid(): 10015
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  896): Killing 5381:com.samsung.android.app.galaxyfinder/u0a39 (adj 13): bgCount ##41
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WaitQueueForNetworkActivate( 7286): notifyNetworkActivated
,E/Zygote  ( 7304): MountEmulatedStorage()
E/Zygote  ( 7304): v2
I/libpersona( 7304): KNOX_SDCARD checking this for 10129
I/libpersona( 7304): KNOX_SDCARD not a persona
,W/ContextImpl( 7286): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,I/ActivityManager(  896): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=7304 uid=10129 gids={50129, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7304): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6053): [RC New] [v2liruge] api execute + 620
I/SA      ( 6053): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6053): AsyncTask #1 calls detatch()
I/SELinux ( 7304): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7304): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 1473): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/SA      ( 6053): [TPMU] getNetworkMcc : 
,I/SA      ( 6053): [SCU] saveMccToPreferece Start
I/SA      ( 6053): [SCU] RegionMCC : 260
I/SA      ( 6053): [SSP] query invoked
,I/GCM     ( 1473): GCM config loaded
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7304): TimaSignature is unavailable
,D/ActivityThread( 7304): Added TimaKeyStore provider
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ActivityManager(  896): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 1754): Untagging socket 121
,I/art     (  896): Explicit concurrent mark sweep GC freed 37761(2MB) AllocSpace objects, 4(64KB) LOS objects, 17% free, 37MB/45MB, paused 1.389ms total 99.388ms
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6053): [TPMU] GetMccFromDB : null
I/SA      ( 6053): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6053): [SCU] saveMccToPreferece End
,I/SA      ( 6053): [RC New] executeRequest [v2liruge] end. 793
I/SA      ( 6053): [RC New] Execute end
,I/SA      ( 6053): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6053): [OR] GetMyCountryZoneTask Success
,D/ResourcesManager( 7304): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1754): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1754): Tagging socket 113 with tag 1000190000000000{268441856,0} uid 10015, pid: 1754, getuid(): 10015
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  896): [PWL] Off : 75s ago
I/PowerManagerService(  896): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  896): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  896): [PWL]       PARTIAL_WAKE_LOCK              'AlarmReceiver' (uid=10106, pid=6959, ws=null) (elapsedTime=2867)
I/PowerManagerService(  896): [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=6480, ws=null) (elapsedTime=2451)
I/PowerManagerService(  896): [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10015, pid=1473, ws=WorkSource{10015 com.google.android.gms}) (elapsedTime=2188)
I/PowerManagerService(  896): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=1804)
I/PowerManagerService(  896): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.gms.people/com.google/eM_ADDR' (uid=1000, pid=896, ws=WorkSource{10015}) (elapsedTime=1257)
I/PowerManagerService(  896): [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10015, pid=1473, ws=WorkSource{10015 com.google.android.gms}) (elapsedTime=674)
I/PowerManagerService(  896): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.android.calendar/com.google/eM_ADDR' (uid=1000, pid=896, ws=WorkSource{10129}) (elapsedTime=207)
I/PowerManagerService(  896): [PWL]       PARTIAL_WAKE_LOCK              'GCM_CONN' (uid=10015, pid=1473, ws=WorkSource{10015 com.google.android.gms}) (elapsedTime=12)
,D/LocationManagerService(  896): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/AbstractGoogleClient( 7304): Application name is not set. Call Builder#setApplicationName.
,I/qtaguid ( 1754): Untagging socket 113
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1473): (HTTPLog)-Static: isSBSettingEnabled false
,D/hcjo    ( 7286): AutoUpdateManager:IDLE:execute
,D/bt_upio ( 6480): ..proc_btwrite_timeout..
,D/InitializeManagerStateMachine( 7286): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7286): exit::IDLE
D/InitializeManagerStateMachine( 7286): entry::NETWORK_CHECK
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7286): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7286): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7286): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7286): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7286): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7286): entry::SUCCESS
D/hcjo    ( 7286): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 7286): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,I/System.out( 1473): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1473): Tagging socket 68 with tag 1000120100000000{268440065,0} uid -1, pid: 1473, getuid(): 10015
,D/hcjo    ( 7286): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 7286): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 7286): exit::SUCCESS
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7286): entry::IDLE
,I/qtaguid ( 1473): Tagging socket 81 with tag 1000120100000000{268440065,0} uid -1, pid: 1473, getuid(): 10015
,I/DBG_DM  ( 3144): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2673/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,I/DBG_DM  ( 3144): [IlIlIlllIIlllIlIlIIl(1859/llIlIIIIlIIIIIlIlIII)] flag is : false
,I/DBG_DM  ( 3144): [com.wssyncmldm.DMSecBroadcastReceiver(194/onReceive)] sec.fota.polling.intent.RECEIVE
,I/DBG_DM  ( 3144): [com.wssyncmldm.DMSecBroadcastReceiver(556/llllIIIllIlIIIIllllI)] nMode : 0
,I/DBG_DM  ( 3144): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3144): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 8
,I/DBG_DM  ( 3144): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3144): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(210/llIIIIlllllIIllIIllI)] 
,I/System.out( 1754): (HTTPLog)-Static: isSBSettingEnabled false
,I/DBG_DM  ( 3144): [com.wssyncmldm.db.file.XDB(3786/IllIIlllIllIIIIIllII)] Wifi_Only_flag : true
I/qtaguid ( 1754): Tagging socket 113 with tag 1000150000000000{268440832,0} uid 10015, pid: 1754, getuid(): 10015
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3144): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 3144): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 3144): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(235/llIIIIlllllIIllIIllI)] bWifiOnly flag : true
,I/DBG_DM  ( 3144): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3144): [IlIlIlllIIlllIlIlIIl(1859/llIlIIIIlIIIIIlIlIII)] flag is : false
,I/DBG_DM  ( 3144): [IIlIlIllIlIIIIIIllll(1846/lIlIIlIlIIlIlIIIIlll)] bUpdateProcessing : false
,I/DBG_DM  ( 3144): [IIllIlIIlIlllIIllIII(741/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/DBG_DM  ( 3144): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1273/handleMessage)] event ->220
,I/DBG_DM  ( 3144): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 3144): [com.wssyncmldm.XDMService(876/IIIIllIlIIlIIIIlllIl)] 
,W/ContextImpl( 1309): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/DBG_DM  ( 3144): [com.wssyncmldm.db.file.XDB(4994/IIIlllIlIIlllIIIIllI)] Get Autoinstall status : false
,I/DBG_DM  ( 3144): [IIllIlIIlIlllIIllIII(695/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,I/DBG_DM  ( 3144): [com.wssyncmldm.XDMService(638/llllIIIllIlIIIIllllI)] 
,E/DBG_DM  ( 3144): [com.wssyncmldm.XDMService(646/llllIIIllIlIIIIllllI)] didn't register
,E/DBG_DM  ( 3144): [com.wssyncmldm.XDMService(647/llllIIIllIlIIIIllllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@3603b97a
,I/DBG_DM  ( 3144): [com.wssyncmldm.XDMService(819/IllIlIIIIlIIlIIIllIl)] Idle Screen : false
,I/DBG_DM  ( 3144): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/LocalBluetoothProfileManager( 1309): Adding local A2DP profile
,I/DBG_DM  ( 3144): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/LocalBluetoothProfileManager( 1309): Adding local HEADSET profile
,E/BluetoothHeadset( 1309): BTStateChangeCB is registed
,D/SecContentProvider2(  896): uri = 14 selection = getSealedState
D/SecContentProvider2(  896): mCursor = null
,E/BluetoothHeadset( 1309): BluetoothHeadset service is binded
,D/ApplicationPolicy(  896): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/DBG_DM  ( 3144): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
,D/StatusBar( 1185): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/ContextImpl( 1309): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/PersonaManager( 1185): isKioskContainerExistOnDevice
D/PersonaManager( 1185): isKioskContainerExistOnDevice
D/PanelView( 1185): There is/are notification(s) 
D/PanelView( 1185): There is/are notification(s) 
,I/DBG_DM  ( 3144): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
D/Bluetoothsap( 1309): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 1309): PANU : true
D/LocalBluetoothProfileManager( 1309): Adding local MAP profile
,D/BluetoothMap( 1309): Create BluetoothMap proxy object
,W/LocalBluetoothProfileManager( 1309): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 1309): LocalBluetoothProfileManager construction complete
,I/qtaguid ( 1754): Untagging socket 113
,D/DockEventReceiver( 1309): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1309): onReceive
,D/BluetoothAdapterService( 6480): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2e01f8e0
D/BtConfig.SecureMode( 6480): isSecureModeOn:false
,D/BluetoothA2dp( 1309): Proxy object connected
D/A2dpProfile( 1309): Bluetooth service connected
,I/DBG_DM  ( 3144): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 3144): [com.wssyncmldm.ui.XUIFotaPostponeActivity(378/lllIlIlIIIllIIlIllIl)] No idle Postpone
,D/HeadsetProfile( 1309): Bluetooth service connected
,I/DBG_DM  ( 3144): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
,D/AuthorizationBluetoothService( 1473): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/Bluetoothsap( 1309): BluetoothSAP Proxy object connected
,D/SapProfile( 1309): Bluetooth service connected
D/Bluetoothsap( 1309): getConnectedDevices()
,D/BluetoothInputDevice( 1309): Proxy object connected
,D/HidProfile( 1309): Bluetooth service connected
,D/BluetoothPan( 1309): BluetoothPAN Proxy object connected
D/PanProfile( 1309): Bluetooth service connected
,D/BluetoothMap( 1309): Proxy object connected
,D/MapProfile( 1309): Bluetooth service connected
D/BluetoothPbap( 1309): Proxy object connected
D/PbapServerProfile( 1309): Bluetooth service connected
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7331): MountEmulatedStorage()
E/Zygote  ( 7331): v2
I/libpersona( 7331): KNOX_SDCARD checking this for 10171
I/libpersona( 7331): KNOX_SDCARD not a persona
,D/LocationManagerService(  896): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/SELinux ( 7331): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SELinux ( 7331): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7331): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  896): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7331 uid=10171 gids={50171, 9997} abi=armeabi-v7a
,D/SecContentProvider(  896): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,I/art     (  322): Explicit concurrent mark sweep GC freed 8732(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 319us total 12.956ms
,I/System.out( 1473): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1473): Tagging socket 82 with tag 1000040100000000{268436481,0} uid 10015, pid: 1473, getuid(): 10015
I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 290us total 9.842ms
,W/BluetoothAdapter( 6480): getBluetoothService() called with no BluetoothManagerCallback
,D/bt_vendor( 6480): op for 7
,D/bt_upio ( 6480): proc btwrite assertion
D/BluetoothSocket( 6480): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
D/BluetoothSocket( 6480): bindListen(), new LocalSocket 
D/BluetoothSocket( 6480): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6480): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@624905d
D/BluetoothSocket( 6480): channel: 12
I/BtOppRfcommListener( 6480): Accept thread started.
,D/TimaKeyStoreProvider( 7331): TimaSignature is unavailable
,D/ActivityThread( 7331): Added TimaKeyStore provider
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 339us total 9.667ms
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1473): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1473): Tagging socket 68 with tag 1000120100000000{268440065,0} uid -1, pid: 1473, getuid(): 10015
,D/ResourcesManager( 7331): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 7331): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7331): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/PeopleSync( 1754): Sync finished, successful=true, took 1419ms
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,D/LocationManagerService(  896): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7351): MountEmulatedStorage()
E/Zygote  ( 7351): v2
I/libpersona( 7351): KNOX_SDCARD checking this for 10131
I/libpersona( 7351): KNOX_SDCARD not a persona
,I/SELinux ( 7351): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7351): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,I/ActivityManager(  896): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RequestWriter$NetworkStateReceiver: pid=7351 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/SELinux ( 7351): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1473): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1473): Tagging socket 68 with tag 1000120100000000{268440065,0} uid -1, pid: 1473, getuid(): 10015
,D/TimaKeyStoreProvider( 7351): TimaSignature is unavailable
,D/ActivityThread( 7351): Added TimaKeyStore provider
,I/ActivityManager(  896): Killing 5475:com.sec.knox.knoxsetupwizardclient/1000 (adj 13): bgCount ##41
,I/PeopleContactsSync( 1754): CP2 sync start [5005f081]
,D/ResourcesManager( 7351): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager( 7351): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/PeopleContactsSync( 1754): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/PeopleContactsSync( 1754): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,D/LocationManagerService(  896): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1473): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1473): Tagging socket 68 with tag 1000120100000000{268440065,0} uid -1, pid: 1473, getuid(): 10015
,I/PeopleContactsSync( 1754): CP2 cleanup done, kept= duration=73 ms
,I/PeopleContactsSync( 1754): ===CP2 sync finished, success=true, time=83,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,I/PeopleSync( 1754): ***Sync finished***, duration: 1865 [5005f081]
,D/LocationManagerService(  896): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/System.out( 7304): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 7304): (HTTPLog)-Static: isShipBuild true
I/System.out( 7304): (HTTPLog)-Thread-1156-664836853: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 7304): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1473): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1473): Tagging socket 68 with tag 1000120100000000{268440065,0} uid -1, pid: 1473, getuid(): 10015
I/System.out( 7304): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 7304): Tagging socket 28 with tag 1100000000000000{285212672,0} uid -1, pid: 7304, getuid(): 10129
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7351): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
I/Babel   ( 7351): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 7351): MmsConfig.loadMmsSettings
I/Babel   ( 7351): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
I/Babel   ( 7351): MmsConfig.loadFromDatabase
W/AudioCapabilities( 7351): Unsupported mime audio/evrc
W/AudioCapabilities( 7351): Unsupported mime audio/qcelp
W/VideoCapabilities( 7351): Unrecognized profile 2130706433 for video/avc
E/Babel   ( 7351): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 7351): MmsConfig.loadFromResources
E/Babel   ( 7351): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 7351): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
W/Settings( 7351): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/AudioCapabilities( 7351): Unsupported mime audio/mpeg-L1
W/AudioCapabilities( 7351): Unsupported mime audio/mpeg-L2
W/AudioCapabilities( 7351): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7351): Unsupported mime audio/x-ima
W/AudioCapabilities( 7351): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7351): Unsupported mime audio/qcelp
W/AudioCapabilities( 7351): Unsupported mime audio/evrc
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/VideoCapabilities( 7351): Unsupported mime video/wvc1
W/VideoCapabilities( 7351): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 7351): Unrecognized profile/level 32768/2 for video/mp4v-es
W/VideoCapabilities( 7351): Unsupported mime video/wvc1
W/VideoCapabilities( 7351): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 7351): Unsupported mime video/x-ms-wmv7
W/VideoCapabilities( 7351): Unsupported mime video/x-ms-wmv8
W/VideoCapabilities( 7351): Unsupported mime video/mp43
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/VideoCapabilities( 7351): Unsupported mime video/sorenson
W/VideoCapabilities( 7351): Unsupported mime video/mp4v-esdp
D/ResourcesManager( 7351): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
W/ResourcesManager( 7351): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7351): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/BaseAppContext( 1473): Using Auth Proxy for data requests.
I/VideoCapabilities( 7351): Unsupported profile 4 for video/mp4v-es
E/BaseAppContext( 1473): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
V/JNIHelp ( 7351): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/System.out( 1473): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1473): Tagging socket 82 with tag 1000040100000000{268436481,0} uid 10015, pid: 1473, getuid(): 10015
I/qtaguid ( 7304): Untagging socket 28
W/ActivityThread( 7351): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7351): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bc15bea: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7351): Installed default security provider GmsCore_OpenSSL
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5973): mConnectivityHandler : connected
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/PCWCLIENTTRACE_AccountUtil( 5973): [hasSamungAccount] - No Samsung Account
I/art     ( 1595): Explicit concurrent mark sweep GC freed 3548(130KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 16MB/21MB, paused 323us total 16.086ms
I/CSTORAGE( 5973): ================================================
I/CSTORAGE( 5973):  CSTORAGE_SKM_LIB v1.0.6
I/CSTORAGE( 5973): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5973): [GetString-S]
E/art     ( 5973): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI( 5973): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5973): [GetString-E]
I/PCWCLIENTTRACE_PushUtil( 5973): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5973): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5973): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5973): [ensureRegistration] - No Samsung account
D/CalendarSyncAdapter( 7304): Found 0 events marked dirty & lastSynced
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  896): Killing 3306:com.android.vending/u0a33 (adj 13): bgCount ##41
I/ActivityManager(  896): Killing 5671:com.sec.android.widgetapp.activeapplicationwidget/u0a182 (adj 13): bgCount ##41
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/System.out( 1473): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1473): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1473): Tagging socket 65 with tag 1000040100000000{268436481,0} uid 10015, pid: 1473, getuid(): 10015
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/qtaguid ( 1473): Tagging socket 88 with tag 1000040100000000{268436481,0} uid 10015, pid: 1473, getuid(): 10015
I/System.out( 1473): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1473): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1473): Tagging socket 89 with tag 1000060200000000{268436994,0} uid 10015, pid: 1473, getuid(): 10015
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
I/qtaguid ( 1473): Tagging socket 91 with tag 1000060200000000{268436994,0} uid 10015, pid: 1473, getuid(): 10015
E/Zygote  ( 7399): MountEmulatedStorage()
I/libpersona( 7399): KNOX_SDCARD checking this for 10128
E/Zygote  ( 7399): v2
I/libpersona( 7399): KNOX_SDCARD not a persona
I/SELinux ( 7399): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7399): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7399): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager(  896): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=7399 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/TimaKeyStoreProvider( 7399): TimaSignature is unavailable
D/ActivityThread( 7399): Added TimaKeyStore provider
D/ResourcesManager( 7399): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ActivityManager(  896): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityThread( 7399): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,W/ActivityManager(  896): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  896): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/System.out( 7351): (HTTPLog)-Static: isSBSettingEnabled false
W/ActivityManager(  896): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/System.out( 7351): (HTTPLog)-Static: isShipBuild true
I/System.out( 7351): (HTTPLog)-Thread-1178-457179134: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 7351): (HTTPLog)-Static: isSBSettingEnabled false
,W/ActivityManager(  896): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/System.out( 7351): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/Gmail   ( 7399): getAccountsCursor
,W/ActivityManager(  896): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7399): Observing account changes for notifications
,V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 7399): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/dhcpcd  ( 6680): wlan0: sending IPv6 Router Solicitation
,I/qtaguid ( 1473): Untagging socket 89
,W/ActivityManager(  896): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GCoreUlr( 1473): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/GCoreUlr( 1473): DispatchingService.onCreate()
,W/Gmail   ( 7399): Sync started for account: account:61035162
,I/Gmail   ( 7399): getAccountsCursor
,E/Gmail   ( 7399): Error finding the version of the Email provider.....
E/Gmail   ( 7399): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7399): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
E/Gmail   ( 7399): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1235)
E/Gmail   ( 7399): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:187)
E/Gmail   ( 7399): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7399): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7399): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 7399): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 7399): We do not support migrating this version of the Email provider.
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 7399): (283) recovered 42 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GCoreUlr( 1473): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1473): Unbound from all location providers
,I/GCoreUlr( 1473): Place inference reporting - stopped
,D/ResourcesManager( 1754): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/GCoreUlr( 1473): DispatchingService.onDestroy()
I/GCoreUlr( 1473): Stopping handler for UlrDispSvcFast
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/File    ( 7399): fail readDirectory() errno=2
,I/GCoreUlr( 1473): Unbound from all location providers
I/GCoreUlr( 1473): Place inference reporting - stopped
,I/Gmail   ( 7399): notifyAccountChanged
,I/Gmail   ( 7399): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Gmail   ( 7399): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7399): notifyAccountChanged
,I/Gmail   ( 7399): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7399): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Gmail   ( 7399): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 12279, normalSync: true
,V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7399): getAccountsCursor
,I/Gmail   ( 7399): getAccountsCursor
,V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 1595): Thread-124(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/ResourcesManager( 7399): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/System.out( 1595): Thread-124(ApacheHTTPLog):isShipBuild true
,I/System.out( 1595): Thread-124(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,W/ResourcesManager( 7399): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7399): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/qtaguid ( 1595): Tagging socket 35 with tag 1244000400000000{306446340,0} uid -1, pid: 1595, getuid(): 10015
,V/JNIHelp ( 7399): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7399): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7399): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@304e33ad: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7399): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 7399): Thread-1188(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7399): Thread-1188(ApacheHTTPLog):isShipBuild true
,I/System.out( 7399): Thread-1188(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 7399): Tagging socket 59 with tag 1010000000000000{269484032,0} uid -1, pid: 7399, getuid(): 10128
,I/qtaguid ( 1595): Tagging socket 41 with tag 1244000400000000{306446340,0} uid -1, pid: 1595, getuid(): 10015
,I/qtaguid ( 7399): Tagging socket 63 with tag 1010000000000000{269484032,0} uid -1, pid: 7399, getuid(): 10128
,E/SMD     (  291): DCD ON
,D/bt_vendor( 6480): op for 7
,I/art     (  896): Explicit concurrent mark sweep GC freed 44137(2MB) AllocSpace objects, 2(32KB) LOS objects, 17% free, 37MB/45MB, paused 1.291ms total 87.565ms
,I/art     ( 7351): Note: end time exceeds epoch: 
,I/Babel   ( 7351): Account registration complete:Redacted-21
,I/qtaguid ( 1595): Untagging socket 35
,I/System.out( 1595): GDataFeedFetcher calls detatch()
,D/Mms/Contact( 4867): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/Contact( 4867): performUpdate:widgetCount=0
,I/qtaguid ( 1595): Tagging socket 35 with tag 1144000400000000{289669124,0} uid -1, pid: 1595, getuid(): 10015
,D/ContactProvider( 5241): getAllContactInfoList Start
,D/ContactProvider( 5241): getAllContactInfoList End
,I/qtaguid ( 1595): Untagging socket 35
I/System.out( 1595): GDataFeedFetcher calls detatch()
,D/Mms/Contact( 4867): sContactsObserver.onChange(),selfUpdate=false
,D/ContactProvider( 5241): getAllContactInfoList Start
,E/SQLiteLog( 1683): (284) automatic index on sqlite_sq_AFB26830(STAT_DATA_ID)
,E/SQLiteLog( 1683): (284) automatic index on sqlite_sq_AFB26A10(STAT_DATA_ID)
,D/ContactProvider( 5241): getAllContactInfoList End
,I/qtaguid ( 7399): Untagging socket 59
I/System.out( 7399): SyncAdapterThread-1 calls detatch()
,E/SQLiteLog( 1683): (284) automatic index on sqlite_sq_AFB26F60(STAT_DATA_ID)
,V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 1683): (284) automatic index on sqlite_sq_AFB26790(STAT_DATA_ID)
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,D/bt_upio ( 6480): ..proc_btwrite_timeout..
,E/Zygote  ( 7463): MountEmulatedStorage()
,E/Zygote  ( 7463): v2
I/libpersona( 7463): KNOX_SDCARD checking this for 10112
I/libpersona( 7463): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=7463 uid=10112 gids={50112, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7463): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7463): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7463): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7463): TimaSignature is unavailable
,D/ActivityThread( 7463): Added TimaKeyStore provider
,D/ResourcesManager( 7463): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/DocsApplication( 7463): Installing DEX configuration.
,D/DexInstaller( 7463): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper( 7463): Provided clientMode=RELEASE, packageInfo=PackageInfo{155b6d61 com.google.android.apps.docs}
,D/TAG     ( 7463): onCreate()
,D/CrossAppStateProvider( 7463): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,I/art     ( 7399): Explicit concurrent mark sweep GC freed 157547(5MB) AllocSpace objects, 12(215KB) LOS objects, 24% free, 19MB/25MB, paused 855us total 44.156ms
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Gmail   ( 7399): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 12811, normalSync: true
,I/Gmail   ( 7399): lowestBackward conversation id 0
,I/Gmail   ( 7399): notifyAccountChanged
,I/Gmail   ( 7399): getAccountsCursor
,V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7399): notifyAccountChanged
,W/Gmail   ( 7399): Sync complete for account: account:61035162
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Gmail   ( 7399): getAccountsCursor
,I/ActivityManager(  896): Killing 6582:com.sec.android.provider.badge/u0a92 (adj 13): bgCount ##41
,V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1754): Explicit concurrent mark sweep GC freed 58288(3MB) AllocSpace objects, 34(1095KB) LOS objects, 40% free, 23MB/39MB, paused 795us total 55.470ms
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SyncAdapterService( 7173): Ignoring sync request for non-current account
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/BaseAppContext( 1754): Using Auth Proxy for data requests.
,W/BaseAppContext( 1754): Using Auth Proxy for data requests.
,W/BaseAppContext( 1754): Using Auth Proxy for data requests.
,W/BaseAppContext( 1754): Using Auth Proxy for data requests.
,W/BaseAppContext( 1754): Using Auth Proxy for data requests.
,W/BaseAppContext( 1754): Using Auth Proxy for data requests.
,W/BaseAppContext( 1754): Using Auth Proxy for data requests.
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GoogleHttpClient( 5150): Falling back to old http client 0 java.lang.NoSuchMethodException: <init> [class android.content.Context, class java.lang.String, boolean, boolean]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5150): Thread-846(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5150): Thread-846(ApacheHTTPLog):isShipBuild true
,I/System.out( 5150): Thread-846(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 5150): SyncAdapterThread-1 calls detatch()
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5150): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5150): SyncAdapterThread-1 calls detatch()
,W/MusicApiClient( 5150): No content in 'data' field in GET sync response for Track
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7489): MountEmulatedStorage()
E/Zygote  ( 7489): v2
I/libpersona( 7489): KNOX_SDCARD checking this for 10033
I/libpersona( 7489): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.ConsumptionAppDataChangedReceiver: pid=7489 uid=10033 gids={50033, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7489): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7489): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7489): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/MusicSyncAdapter( 5150): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
,I/MusicSyncAdapter( 5150): Periodic update
,D/TimaKeyStoreProvider( 7489): TimaSignature is unavailable
,D/ActivityThread( 7489): Added TimaKeyStore provider
,D/ResourcesManager( 7489): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7506): MountEmulatedStorage()
E/Zygote  ( 7506): v2
I/libpersona( 7506): KNOX_SDCARD checking this for 10203
I/libpersona( 7506): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=7506 uid=10203 gids={50203, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 7506): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7506): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7506): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7506): TimaSignature is unavailable
,D/ActivityThread( 7506): Added TimaKeyStore provider
,D/ResourcesManager( 7506): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/ResourcesManager( 7506): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,D/Finsky  ( 7489): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/SurfaceFlinger(  254): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger(  254): id=15 Removed Uoast (-2/9)
,D/PowerManagerService(  896): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 896) eventTime = 178209
D/PowerManagerService(  896): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=896 (0x0)
D/PowerManagerService(  896): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=896, ws=WorkSource{1000}) (elapsedTime=5037)
,I/GAV4    ( 7173): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/GAV2    ( 7463): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/Finsky  ( 7489): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 7489): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7489): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 7463): Thread-1192(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7463): Thread-1192(ApacheHTTPLog):isShipBuild true
,I/System.out( 7463): Thread-1192(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/Ads     ( 7489): Skipping gmscore version check
,D/Finsky  ( 7489): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7489): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7489): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Finsky  ( 7489): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5150): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5150): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5150): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5150): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PlayMovies( 7506): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,W/ArtDownloadService( 5150): Setting cache size 0
,W/ArtDownloadService( 5150): Setting cache size 0
,I/MusicLeanback( 5150): Conditions not met for autocaching.
I/MusicLeanback( 5150): Stop autocaching.
,D/WearableService( 1473): callingUid 10015, callindPid: 1473
,D/WearableClient( 5150): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 5150): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 5150): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,W/AudioCapabilities( 7506): Unsupported mime audio/evrc
I/ActivityManager(  896): Killing 5400:com.samsung.android.app.FileShareServer/u0a88 (adj 13): bgCount ##41
,D/PlayMovies( 7506): TransferService.onCreate:52 creating transfer service
,W/AudioCapabilities( 7506): Unsupported mime audio/qcelp
,W/VideoCapabilities( 7506): Unrecognized profile 2130706433 for video/avc
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5150): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5150): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,W/AudioCapabilities( 7506): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 7506): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 7506): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 7506): Unsupported mime audio/x-ima
,W/AudioCapabilities( 7506): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7506): Unsupported mime audio/qcelp
,W/AudioCapabilities( 7506): Unsupported mime audio/evrc
,D/Mms/Contact( 4867): performUpdate:widgetCount=0
,I/System.out( 7463): SyncManager calls detatch()
,W/VideoCapabilities( 7506): Unsupported mime video/wvc1
D/btif_config_util( 6480): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/VideoCapabilities( 7506): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 7506): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 7506): Unsupported mime video/wvc1
,W/VideoCapabilities( 7506): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 7506): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 7506): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 7506): Unsupported mime video/mp43
,W/VideoCapabilities( 7506): Unsupported mime video/sorenson
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/VideoCapabilities( 7506): Unsupported mime video/mp4v-esdp
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.videos/files/Movies/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7506): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.videos/files/Movies
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 1754): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/VideoCapabilities( 7506): Unsupported profile 4 for video/mp4v-es
,I/System.out( 1473): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1473): Tagging socket 82 with tag 1000040100000000{268436481,0} uid 10015, pid: 1473, getuid(): 10015
,W/ResourcesManager( 1754): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 1473): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1473): Tagging socket 65 with tag 1000040100000000{268436481,0} uid 10015, pid: 1473, getuid(): 10015
,I/PlayMovies( 7506): SyncService.syncAllPurchasesAndWishlist:151 Starting sync for 515013DC511638B0584069811EF28701C0771BF5
,I/System.out( 7506): Thread-1201(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7506): Thread-1201(ApacheHTTPLog):isShipBuild true
,I/System.out( 7506): Thread-1201(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,W/bdH     ( 7463): Application name is not set. Call Builder#setApplicationName.
,I/System.out( 7463): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 7463): (HTTPLog)-Static: isShipBuild true
I/System.out( 7463): (HTTPLog)-Thread-1192-476243916: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 7463): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 7463): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/System.out( 7506): sync-2 calls detatch()
,I/System.out( 7506): sync-2 calls detatch()
,I/PlayMovies( 7506): SyncService.waitForCompletion:177 Sync completed for 515013DC511638B0584069811EF28701C0771BF5 purchases
,W/PsynchoHelperImpl( 7463): Error fetching or saving configuration
W/PsynchoHelperImpl( 7463): bdz: 404 Not Found
W/PsynchoHelperImpl( 7463): {
W/PsynchoHelperImpl( 7463):   "errors": [
W/PsynchoHelperImpl( 7463):     {
W/PsynchoHelperImpl( 7463):       "domain": "global",
W/PsynchoHelperImpl( 7463):       "reason": "notFound",
W/PsynchoHelperImpl( 7463):       "message": "Setting psyncho_auto_backup_promo in namespace FEATURE_SWITCH was not found",
W/PsynchoHelperImpl( 7463):       "locationType": "other",
W/PsynchoHelperImpl( 7463):       "location": "setting"
W/PsynchoHelperImpl( 7463):     }
W/PsynchoHelperImpl( 7463):   ],
W/PsynchoHelperImpl( 7463):   "code": 404,
W/PsynchoHelperImpl( 7463):   "message": "Setting psyncho_auto_backup_promo in namespace FEATURE_SWITCH was not found"
W/PsynchoHelperImpl( 7463): }
W/PsynchoHelperImpl( 7463): 	at bdP.newExceptionOnError(AbstractGoogleJsonClientRequest.java:113)
W/PsynchoHelperImpl( 7463): 	at bdP.newExceptionOnError(AbstractGoogleJsonClientRequest.java:40)
W/PsynchoHelperImpl( 7463): 	at bdK.a(AbstractGoogleClientRequest.java:321)
W/PsynchoHelperImpl( 7463): 	at bei.a(HttpRequest.java:1049)
W/PsynchoHelperImpl( 7463): 	at bdJ.executeUnparsed(AbstractGoogleClientRequest.java:419)
W/PsynchoHelperImpl( 7463): 	at bdJ.executeUnparsed(AbstractGoogleClientRequest.java:352)
W/PsynchoHelperImpl( 7463): 	at bdJ.execute(AbstractGoogleClientRequest.java:469)
W/PsynchoHelperImpl( 7463): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:142)
W/PsynchoHelperImpl( 7463): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:215)
W/PsynchoHelperImpl( 7463): 	at OQ.a(PsynchoHelperImpl.java:60)
W/PsynchoHelperImpl( 7463): 	at agr.a(DriveSpecificSyncManager.java:27)
W/PsynchoHelperImpl( 7463): 	at agO.a(LegacySyncManager.java:678)
W/PsynchoHelperImpl( 7463): 	at agO.b(LegacySyncManager.java:582)
W/PsynchoHelperImpl( 7463): 	at agO.a(LegacySyncManager.java:467)
W/PsynchoHelperImpl( 7463): 	at agO.a(LegacySyncManager.java:97)
W/PsynchoHelperImpl( 7463): 	at agQ.run(LegacySyncManager.java:419)
W/PsynchoHelperImpl( 7463): 	at ami.a(NetworkUtilitiesImpl.java:31)
W/PsynchoHelperImpl( 7463): 	at agP.run(LegacySyncManager.java:416)
,V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  896): waitForAlarm result :4
,I/System.out( 7506): sync-1 calls detatch()
,I/PlayMovies( 7506): SyncService.waitForCompletion:177 Sync completed for 515013DC511638B0584069811EF28701C0771BF5 wishlist
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Finsky  ( 7489): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  291): DCD ON
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  896): Explicit concurrent mark sweep GC freed 42736(2MB) AllocSpace objects, 7(112KB) LOS objects, 17% free, 37MB/45MB, paused 1.294ms total 105.025ms
,D/SecContentProvider2(  896): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  896): mCursor = null
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1595): Explicit concurrent mark sweep GC freed 21797(1049KB) AllocSpace objects, 3(71KB) LOS objects, 24% free, 16MB/21MB, paused 464us total 25.783ms
,I/System.out( 7489): Thread-1188(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7489): Thread-1188(ApacheHTTPLog):isShipBuild true
,I/System.out( 7489): Thread-1188(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 7489): Tagging socket 44 with tag e8d195d100000000{3906049489,0} uid -1, pid: 7489, getuid(): 10033
,E/Auth.Api.Credentials( 1754): [CredentialSyncAdapter] Unknown sync event.
,I/qtaguid ( 7489): Tagging socket 48 with tag e8d195d100000000{3906049489,0} uid -1, pid: 7489, getuid(): 10033
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 7463): SyncManager calls detatch()
,I/System.out( 7304): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 7304): Tagging socket 28 with tag 1000000400000000{268435460,0} uid -1, pid: 7304, getuid(): 10129
I/qtaguid ( 7304): Tagging socket 32 with tag 1000000400000000{268435460,0} uid -1, pid: 7304, getuid(): 10129
,I/qtaguid ( 7489): Untagging socket 44
,I/System.out( 7489): Thread-1188 calls detatch()
,V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/GAV2    ( 7463): SyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/CalendarSyncAdapter( 7304): Saving inProgress state: {calendarId=thalitester@gmail.com, maxAttendees=50, maxResults=200, timeMax=2016-12-25T00:00:00.000Z, updatedMin=2015-11-18T16:31:02.459Z}
,I/qtaguid ( 7304): Untagging socket 28
,D/SSRM:n  (  896): SIOP:: AP = 380, PST = 320, CUR = 450
,I/qtaguid ( 7489): Untagging socket 44
,I/qtaguid ( 7489): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 7489): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 7489): untagSocket(44) failed with errno -22
I/System.out( 7489): Thread-1189 calls detatch()
,D/Finsky  ( 7489): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/CalendarSyncAdapter( 7304): Found 0 events marked dirty & lastSynced
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  896): Killing 6617:com.samsung.shareshot/u0a192 (adj 13): bgCount ##41
,V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 6680): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 6680): wlan0: no IPv6 Routers available
,E/Zygote  ( 7613): MountEmulatedStorage()
E/Zygote  ( 7613): v2
I/libpersona( 7613): KNOX_SDCARD checking this for 10015
I/libpersona( 7613): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=7613 uid=10015 gids={50015, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 7613): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7613): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7613): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7613): TimaSignature is unavailable
,D/ActivityThread( 7613): Added TimaKeyStore provider
,D/ResourcesManager( 7613): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7613): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7613): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 7613): VM with version 2.1.0 has multidex support
,I/MultiDex( 7613): install
I/MultiDex( 7613): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7613): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 7489): Untagging socket 44
,I/qtaguid ( 7489): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 7489): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 7489): untagSocket(44) failed with errno -22
I/System.out( 7489): Thread-1188 calls detatch()
,W/ActivityThread( 7613): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7613): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c5cd1a5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7613): Installed default security provider GmsCore_OpenSSL
,E/MDM     ( 1473): [122] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ChimeraCfgMgr( 7613): Reading stored module config
,D/AuthorizationBluetoothService( 1473): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1754): Restart initialization of location
,D/ChimeraCfgMgr( 7613): Loading module com.google.android.gms.car from APK com.google.android.gms
,V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1473): No location to return for getLastLocation()
,W/FusedLocationProvider( 1473): location=null
,D/CAR.SERVICE( 7613): Connecting to CarCallService...
,I/art     ( 7613): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7613): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 7613): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 7613): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 7613): Creating a new PhoneAdapter instance
,W/ActivityManager(  896): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 7613): setListener: com.google.android.gms.car.dn@316068b8
,W/ActivityManager(  896): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 7613): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 7613): Starting CarCallService with initial phone null
,D/NativeLibraryUtils( 7613): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 7613): Package validated; name: com.android.vending
,V/Finsky  ( 7489): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): stay LED for fully charged
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAV2    ( 7399): Thread[GAThread,5,main]: No campaign data found.
,I/qtaguid ( 7489): Untagging socket 44
,I/qtaguid ( 7489): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 7489): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 7489): untagSocket(44) failed with errno -22
I/System.out( 7489): Thread-1189 calls detatch()
,D/Finsky  ( 7489): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.tripadvisor.tripadvisor to false
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7489): creating new AssetManager and set to /system/framework/framework-res.apk
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7489): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7489): creating new AssetManager and set to /system/app/ANTRadioService/ANTRadioService.apk
,D/ResourcesManager( 7489): creating new AssetManager and set to /system/app/AntHalService/AntHalService.apk
,W/ResourcesManager( 7489): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7489): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7489): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7489): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7489): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7489): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/ResourcesManager( 7489): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Finsky  ( 7489): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 7489): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  896): waitForAlarm result :4
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Finsky  ( 7489): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
,D/Finsky  ( 7489): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
,D/DeviceConnectionService( 1473): client connected with version: 8296000
,D/Finsky  ( 7489): [1211] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 7489): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 7489): (HTTPLog)-Static: isShipBuild true
I/System.out( 7489): (HTTPLog)-Thread-1199-1005298887: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 7489): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 7489): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/ActivityManager(  896): Killing 4343:com.samsung.android.snote/u0a168 (adj 13): bgCount ##41
,I/ActivityManager(  896): Killing 6823:com.sec.android.cloudagent/u0a4 (adj 13): bgCount ##41
I/ActivityManager(  896): Killing 5973:com.sec.pcw.device/1000 (adj 15): bgCount ##42
,E/SMD     (  291): DCD ON
,I/GAV2    ( 7463): Thread[GAThread,5,main]: No campaign data found.
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/PreloadUpdateManagerStateMachine( 7286): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7286): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7286): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7286): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/Volley  ( 7286): RestApi Request Add : 2307
,E/File    ( 7286): fail readDirectory() errno=2
,I/System.out( 7286): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 7286): (HTTPLog)-Static: isShipBuild true
I/System.out( 7286): (HTTPLog)-Thread-1155-719976241: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 7286): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 7286): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 7286): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 7286, getuid(): 10045
,D/CAR.SERVICE( 7613): mConnectedToCar = false, abort
,E/ActivityThread( 7613): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@164b85a0 that was originally bound here
E/ActivityThread( 7613): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@164b85a0 that was originally bound here
E/ActivityThread( 7613): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 7613): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 7613): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2142)
E/ActivityThread( 7613): 	at android.app.ContextImpl.bindService(ContextImpl.java:2125)
E/ActivityThread( 7613): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 7613): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 7613): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 7613): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 7613): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 7613): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 7613): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 7613): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 7613): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 7613): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3146)
E/ActivityThread( 7613): 	at android.app.ActivityThread.access$1900(ActivityThread.java:177)
E/ActivityThread( 7613): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1531)
E/ActivityThread( 7613): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7613): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 7613): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/ActivityThread( 7613): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7613): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7613): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/ActivityThread( 7613): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
,E/SMD     (  291): DCD ON
,E/ActivityThread( 7613): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3499df1b that was originally bound here
E/ActivityThread( 7613): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3499df1b that was originally bound here
E/ActivityThread( 7613): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread( 7613): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread( 7613): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2142)
E/ActivityThread( 7613): 	at android.app.ContextImpl.bindService(ContextImpl.java:2125)
E/ActivityThread( 7613): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 7613): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 7613): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 7613): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 7613): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 7613): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 7613): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 7613): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 7613): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3178)
E/ActivityThread( 7613): 	at android.app.ActivityThread.access$2000(ActivityThread.java:177)
E/ActivityThread( 7613): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1536)
E/ActivityThread( 7613): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7613): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 7613): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/ActivityThread( 7613): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7613): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7613): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/ActivityThread( 7613): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
,W/ActivityManager(  896): Unbind failed: could not find connection for android.os.BinderProxy@c83e02b
,I/qtaguid ( 7286): Untagging socket 26
,D/hcjo    ( 7286): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    ( 7286): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine( 7286): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7286): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 7286): entry::REQ_UPDATE_CHECK
,I/Volley  ( 7286): RestApi Request Add : 2315
,I/System.out( 7286): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 7286): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 7286): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} uid -1, pid: 7286, getuid(): 10045
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/qtaguid ( 7286): Untagging socket -1
,I/qtaguid ( 7286): Failed write_ctrl(u -1) res=-1 errno=9
,I/qtaguid ( 7286): Untagging socket -1 failed errno=-9
,W/NetworkManagementSocketTagger( 7286): untagSocket(-1) failed with errno -9
,D/PreloadUpdateManagerStateMachine( 7286): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
,D/PreloadUpdateManagerStateMachine( 7286): exit::REQ_UPDATE_CHECK
D/PreloadUpdateManagerStateMachine( 7286): entry::NOTIFY_NOTIFICATION
,D/PreloadUpdateManagerStateMachine( 7286): exit::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 7286): entry::FINISH
,D/PreloadUpdateManagerStateMachine( 7286): exit::FINISH
,D/PreloadUpdateManagerStateMachine( 7286): entry::IDLE
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PackageManager(  896): [MSG] SEND_PENDING_BROADCAST
,D/ResourcesManager(  896): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader(  896): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  896): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
,D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/Zygote  ( 7690): MountEmulatedStorage()
,E/Zygote  ( 7690): v2
,I/libpersona( 7690): KNOX_SDCARD checking this for 10025
,I/libpersona( 7690): KNOX_SDCARD not a persona
I/ActivityManager(  896): Start proc sstream.app for broadcast sstream.app/.receiver.ApplicationCompatibleReceiver: pid=7690 uid=10025 gids={50025, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/InputReader(  896): Reconfiguring input devices.  changes=0x00000010
,I/SELinux ( 7690): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7690): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7690): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,D/RegisteredServicesCache( 1408): empty dynamic service
,D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 1432): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,D/RegisteredServicesCache( 1408): empty dynamic service
,D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,W/ResourcesManager( 1432): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/TimaKeyStoreProvider( 7690): TimaSignature is unavailable
,D/ActivityThread( 7690): Added TimaKeyStore provider
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 7690): creating new AssetManager and set to /system/priv-app/MagazineHome/MagazineHome.apk
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  896): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,W/ResourcesManager( 7690): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/SecContentProvider2(  896): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  896): mCursor = null
,D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  896): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  896): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/linker  ( 7690): libdmcAlwaysFD.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/ResourcesManager( 1432): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/MVFD_interface( 7690): <<<  caMVFace_FaceInit
,I/ClearcutLoggerApiImpl( 1473): disconnect managed GoogleApiClient
,D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  896): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7690): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7690): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
,V/ApplicationPolicy(  896): isApplicationStateBlocked userId 0 pkgname com.google.android.talk
,D/BackupManagerService(  896): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(  896): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/SecContentProvider2(  896): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  896): mCursor = null
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,I/art     ( 1683): Explicit concurrent mark sweep GC freed 16955(848KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 16MB/21MB, paused 362us total 24.322ms
,D/BackupManagerService(  896): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,D/HockeyApp( 7690): Current handler class = sstream.app.util.Log$1
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  896): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,W/ResourcesManager(  896): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  896): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  896): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  896): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 7690): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 7690): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ApplicationCompatibleReceiver( 7690): com.sec.chaton Already existed in setting table , SKIP!!!
,D/ResourcesManager( 7690): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7690): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7690): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7690): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7690): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7690): Asset path '/system/framework/videowall.jar' does not exist or contains no resources.
W/ResourcesManager( 7690): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ApplicationCompatibleReceiver( 7690): com.sec.android.app.videoplayer Already existed in setting table , SKIP!!!
,D/ResourcesManager( 7690): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,W/ResourcesManager( 7690): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7690): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7690): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ApplicationCompatibleReceiver( 7690): com.sec.pcw Already existed in setting table , SKIP!!!
,D/ResourcesManager( 7690): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,W/ResourcesManager( 7690): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7690): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ApplicationCompatibleReceiver( 7690): com.samsung.android.app.pinboard Already existed in setting table , SKIP!!!
,D/ResourcesManager( 7690): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,W/ResourcesManager( 7690): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7690): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7690): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SQLiteLog( 7690): (1299) abort at 20 in [INSERT INTO config(selected,category,native_package_names,image_unselected,image_selected,login,application_name,visible,native_app_required,config_id,stream_id,source_icon) VALUES (?,?,?,?,?,?
,E/SQLiteDatabase( 7690): Error inserting selected=1 category=com.android.calendar native_package_names=null image_unselected=2130903040 image_selected=2130903040 login=0 application_name=2131690540 visible=1 native_app_required=0 config_id=com.android.calendar stream_id=null source_icon=0
E/SQLiteDatabase( 7690): android.database.sqlite.SQLiteConstraintException: NOT NULL constraint failed: config.stream_id (code 1299)
E/SQLiteDatabase( 7690): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 7690): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 7690): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 7690): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 7690): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1595)
E/SQLiteDatabase( 7690): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1465)
E/SQLiteDatabase( 7690): 	at sstream.app.provider.StoryProvider.insertOne(StoryProvider.java:352)
E/SQLiteDatabase( 7690): 	at sstream.app.provider.StoryProvider.insert(StoryProvider.java:263)
E/SQLiteDatabase( 7690): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 7690): 	at android.content.ContentResolver.insert(ContentResolver.java:1217)
E/SQLiteDatabase( 7690): 	at sstream.app.provider.DatabaseUtil.storeConfigSetting(DatabaseUtil.java:784)
E/SQLiteDatabase( 7690): 	at sstream.app.receiver.ApplicationCompatibleReceiver.addCompatibleAppsToDB(ApplicationCompatibleReceiver.java:420)
E/SQLiteDatabase( 7690): 	at sstream.app.receiver.ApplicationCompatibleReceiver.getCompatibleApps(ApplicationCompatibleReceiver.java:155)
E/SQLiteDatabase( 7690): 	at sstream.app.StreamManager$1.run(StreamManager.java:177)
,D/ResourcesManager( 7690): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,W/ResourcesManager( 7690): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7690): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7690): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7690): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7690): Asset path '/system/framework/svi.jar' does not exist or contains no resources.
,W/ResourcesManager( 7690): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7690): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ApplicationCompatibleReceiver( 7690): com.sec.android.gallery3d Already existed in setting table , SKIP!!!
,D/ResourcesManager( 7690): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,D/ApplicationCompatibleReceiver( 7690): com.sec.android.app.samsungapps Already existed in setting table , SKIP!!!
,D/ResourcesManager( 7690): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager( 7690): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,D/ApplicationCompatibleReceiver( 7690): com.samsung.android.snote Already existed in setting table , SKIP!!!
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7745): MountEmulatedStorage()
,E/Zygote  ( 7745): v2
I/libpersona( 7745): KNOX_SDCARD checking this for 10039
I/libpersona( 7745): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7745 uid=10039 gids={50039, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager(  896): Killing 6897:com.sec.android.diagmonagent/1000 (adj 13): bgCount ##41
,I/SELinux ( 7745): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7745): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7745): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7745): TimaSignature is unavailable
,D/ActivityThread( 7745): Added TimaKeyStore provider
,D/ResourcesManager( 7745): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/System.out( 7690): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 7690): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 7690): (HTTPLog)-Static: isShipBuild true
I/System.out( 7690): (HTTPLog)-Thread-1202-798692919: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 7690): (HTTPLog)-Static: isShipBuild true
I/System.out( 7690): (HTTPLog)-Thread-1204-798692919: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 7690): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 7690): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 7690): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 7690): (HTTPLog)-Static: isShipBuild true
I/System.out( 7690): (HTTPLog)-Thread-1203-727148452: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 7690): (HTTPLog)-Static: isSBSettingEnabled false
,I/FeatureConfig( 7745): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager( 7745): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,W/ResourcesManager( 7745): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7745): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7745): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 7745): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7745): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7745): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7745): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 7745): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7745): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 7745): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 7745): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 7745): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 7745): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 7745): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,W/ResourcesManager( 7745): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 7745): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,W/ResourcesManager( 7745): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 7745): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,W/ResourcesManager( 7745): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/svi.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7745): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,W/ResourcesManager( 7745): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7745): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7745): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/videowall.jar' does not exist or contains no resources.
,W/ResourcesManager( 7745): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7745): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 7745): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7745): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 7745): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
,W/ResourcesManager( 7745): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 7745): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7745): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7745): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7745): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/System.out( 7690): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/System.out( 7690): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/System.out( 7690): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 7690): Tagging socket 49 with tag 6d6b53b100000000{1835750321,0} uid -1, pid: 7690, getuid(): 10025
,I/qtaguid ( 7690): Tagging socket 51 with tag 6d6b53b100000000{1835750321,0} uid -1, pid: 7690, getuid(): 10025
I/qtaguid ( 7690): Tagging socket 52 with tag 6d6b53b100000000{1835750321,0} uid -1, pid: 7690, getuid(): 10025
D/ResourcesManager( 7745): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,W/ResourcesManager( 7745): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7745): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 7745): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager( 7745): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,D/ResourcesManager( 7745): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7745): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 7745): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 7745): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7745): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager(  896): Killing 4120:com.sec.android.app.shealth/u0a40 (adj 13): bgCount ##41
,I/UpdateIcingCorporaServi( 1575): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7767): MountEmulatedStorage()
,E/Zygote  ( 7767): v2
I/libpersona( 7767): KNOX_SDCARD checking this for 10088
I/libpersona( 7767): KNOX_SDCARD not a persona
,I/ActivityManager(  896): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7767 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ResourcesManager( 1575): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager( 1575): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1575): UpdateCorporaTask done [took 100 ms] updated apps [took 100 ms] 
,I/SELinux ( 7767): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7767): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7767): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7767): TimaSignature is unavailable
,D/ActivityThread( 7767): Added TimaKeyStore provider
,D/SSRM:n  (  896): SIOP:: AP = 350, PST = 320, CUR = 450
,D/ResourcesManager( 7767): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/FileShare-Server( 7767): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.talk
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7782): MountEmulatedStorage()
E/Zygote  ( 7782): v2
,I/libpersona( 7782): KNOX_SDCARD checking this for 1000
I/libpersona( 7782): KNOX_SDCARD not a persona
,I/SELinux ( 7782): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7782): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7782): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  896): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=7782 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  896): Killing 4867:com.android.mms/u0a55 (adj 13): bgCount ##41
,D/TimaKeyStoreProvider( 7782): TimaSignature is unavailable
,D/ActivityThread( 7782): Added TimaKeyStore provider
,D/ResourcesManager( 7782): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,D/CountryDetector(  896): No listener is left
,D/ShortcutReceiver( 7782):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,I/ActivityManager(  896): Killing 6941:com.samsung.android.scloud.sync/u0a76 (adj 13): bgCount ##41
,I/qtaguid ( 7690): Untagging socket 52
,I/qtaguid ( 7690): Untagging socket 49
,I/qtaguid ( 7690): Untagging socket 51
,W/SQLiteConnectionPool( 1754): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/PackageBroadcastService( 1754): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/UpdateIcingCorporaServi( 1575): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,D/ResourcesManager( 1575): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/UpdateIcingCorporaServi( 1575): UpdateCorporaTask done [took 125 ms] updated apps [took 125 ms] 
,I/art     (  896): Explicit concurrent mark sweep GC freed 59996(3MB) AllocSpace objects, 9(144KB) LOS objects, 17% free, 37MB/45MB, paused 1.413ms total 119.150ms
,D/FileShare-Server( 7767): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.videos
,D/ShortcutReceiver( 7782):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/PackageBroadcastService( 1754): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7809): MountEmulatedStorage()
E/Zygote  ( 7809): v2
I/libpersona( 7809): KNOX_SDCARD checking this for 10125
I/libpersona( 7809): KNOX_SDCARD not a persona
,I/SELinux ( 7809): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  896): Start proc flipboard.app for broadcast flipboard.app/flipboard.sstream.SstreamBroadcastReceiver: pid=7809 uid=10125 gids={50125, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7809): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7809): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7809): TimaSignature is unavailable
,D/ActivityThread( 7809): Added TimaKeyStore provider
,I/art     (  322): Explicit concurrent mark sweep GC freed 8751(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 746us total 41.852ms
,D/ResourcesManager( 7809): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 404us total 15.518ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 388us total 13.324ms
,I/MultiDex( 7809): VM with version 2.1.0 has multidex support
I/MultiDex( 7809): install
I/MultiDex( 7809): VM has multidex support, MultiDex support library is disabled.
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/flipboard.app/files/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7809): Failed to ensure directory: /storage/extSdCard/Android/data/flipboard.app/files/cache
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/flipboard.app/files/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7809): Failed to ensure directory: /storage/extSdCard/Android/data/flipboard.app/files/cache
,I/System.out( 7809): Reading bundled version for config.json
,I/System.out( 7809): Reading bundled version for services.json
,I/System.out( 7809): Reading bundled version for dynamicStrings.json
,I/System.out( 7809): Parsed section Cover Stories, private: false
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  896): Killing 6959:com.sec.android.app.clockpackage/u0a106 (adj 13): bgCount ##41
,E/SMD     (  291): DCD ON
,I/Icing   ( 1754): Indexing F944DC6DBF38E5B5A54FB3560A7505412CF0FFB9 from com.google.android.gms
,D/ResourcesManager( 1754): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager( 1754): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager( 1754): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/Icing   ( 1754): Indexing done F944DC6DBF38E5B5A54FB3560A7505412CF0FFB9
,I/ActivityManager(  896): Waited long enough for: ServiceRecord{22308584 u0 com.google.android.music/.download.artwork.ArtDownloadService}
,E/SMD     (  291): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): stay LED for fully charged
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/Watchdog(  896): !@Sync 6
,D/Finsky  ( 7489): [1201] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7489): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 320, PST = 320, CUR = 450,
,E/SMD     (  291): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  896): waitForAlarm result :8
,V/AlarmManager(  896): waitForAlarm result :4
,V/AlarmManager(  896): waitForAlarm result :8
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 105s ago
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,W/IcingInternalCorpora( 1754): getNumBytesRead when not calculated.
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 310, PST = 320, CUR = 450
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,I/Atfwd_Sendcmd(  330): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  330): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 310, PST = 320, CUR = 450
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/Watchdog(  896): !@Sync 7
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  (  896): SIOP:: AP = 300, PST = 320, CUR = 450
,E/SMD     (  291): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityThread( 1754): Failed to find provider info for com.android.contacts.metadata
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  896): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 203648, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  896): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 296463, reason: UserStart
D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  896): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  896): mCursor = null
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 140s ago
,D/SSRM:n  (  896): SIOP:: AP = 300, PST = 320, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/SSRM:n  (  896): SIOP:: AP = 300, PST = 320, CUR = 450
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 8
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 300, PST = 320, CUR = 450
,E/SMD     (  291): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): stay LED for fully charged
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager(  896): waitForAlarm result :8
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/SSRM:n  (  896): SIOP:: AP = 300, PST = 317, CUR = 450
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6480): Disconnected process message: 10
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 180s ago
,D/SSRM:n  (  896): SIOP:: AP = 300, PST = 309, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 9
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 303, CUR = 450
,E/SMD     (  291): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ClearcutLoggerApiImpl( 1754): disconnect managed GoogleApiClient
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 300, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 298, CUR = 450
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService(  896): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  896): TimaServiceHandler.handleMessage what =1
,D/TimaService(  896): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  896): initializing...
,I/TLC_TIMA_PKM_initialize(  896): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  896): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  896): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  896): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  896): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  896): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  896): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  896): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: (  896): App is not loaded in QSEE
,D/QSEECOMAPI: (  896): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  896): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  896): Trustlet response is completed
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 300, PST = 297, CUR = 450
,E/SMD     (  291): DCD ON
,I/Atfwd_Sendcmd(  330): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  330): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  896): [PWL] Off : 225s ago
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 296, CUR = 450
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  896): waitForAlarm result :4
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,I/ActivityManager(  896): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7934 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,E/Zygote  ( 7934): MountEmulatedStorage()
,E/Zygote  ( 7934): v2
I/libpersona( 7934): KNOX_SDCARD checking this for 10096
I/libpersona( 7934): KNOX_SDCARD not a persona
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,I/SELinux ( 7934): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7934): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7934): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 7934): TimaSignature is unavailable
,D/ActivityThread( 7934): Added TimaKeyStore provider
,D/ResourcesManager( 7934): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  896): Killing 6807:com.sec.android.fotaclient/u0a14 (adj 13): bgCount ##41
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 295, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 11
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 294, CUR = 450
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 293, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 292, CUR = 450
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 275s ago
,E/Watchdog(  896): !@Sync 12
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 291, CUR = 450
,V/AlarmManager(  896): waitForAlarm result :8
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 291, CUR = 450
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 13
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 291, CUR = 450
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 330s ago
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 14
,E/SMD     (  291): DCD ON
,I/Atfwd_Sendcmd(  330): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  330): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/jxcore-log( 6370): Connected to the server!
I/jxcore-log( 6370): 
,I/chromium( 6370): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 15
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): stay LED for fully charged
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/bootchecker(  325): bootchecker wake up!!
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 3
,I/PowerManagerService(  896): [PWL] Off : 390s ago
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 16
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  291): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 17
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 289, CUR = 450
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 288, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 287, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,I/PowerManagerService(  896): [PWL] Off : 455s ago
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 18
,E/SMD     (  291): DCD ON
,I/Atfwd_Sendcmd(  330): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  330): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 286, CUR = 450
,V/AlarmManager(  896): waitForAlarm result :8
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 285, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 284, CUR = 450
,I/Atfwd_Daemon(  330): Stop the daemon....
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 19
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService(  896): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  896): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  896): TimaServiceHandler.handleMessage what =1
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 290, PST = 281, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,I/PowerManagerService(  896): [PWL] Off : 525s ago
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,I/ActivityManager(  896): Killing 6880:com.samsung.klmsagent/u0a23 (adj 13): bgCount ##41
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 21
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 22
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 600s ago
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 281, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
E/SMD     (  291): DCD ON
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,E/Watchdog(  896): !@Sync 23
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  896): !@Sync 24
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryService(  896): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 25
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 680s ago
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): stay LED for fully charged
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/LightsService(  896): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  896): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  896): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/Watchdog(  896): !@Sync 26
,I/EventLogService( 1754): Aggregate from 1450099082980 (log), 1450099082980 (data)
,D/LightsService(  896): [SvcLED]  onSensorChanged::light value = 15
E/LightSensor(  896): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  896): unregisterListener ::   
,D/lights  (  896): led_pattern : 5 +
D/lights  (  896): led_pattern : 5 -
D/LightsService(  896): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,V/AlarmManager(  896): waitForAlarm result :8
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 27
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): stay LED for fully charged
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): stay LED for fully charged
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 28
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): stay LED for fully charged
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 765s ago
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 29
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/TimaService(  896): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  896): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  896): TimaServiceHandler.handleMessage what =1
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 30
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,V/AlarmManager(  896): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON,
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 31
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  896): [PWL] Off : 855s ago
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  896): !@Sync 32
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,V/AlarmManager(  896): waitForAlarm result :8
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/Watchdog(  896): !@Sync 33
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  896): !@Sync 34
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 950s ago
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  896): !@Sync 35
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  896): !@Sync 36
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 37
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 1050s ago
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  896): !@Sync 38
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  896): !@Sync 39
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/UsageStatsService(  896): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  896): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  896): Updating Usage Statistics in DB @ 1450101411128
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
,W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  896): ::getAppControlDB: Exception to create DB
W/System.err(  896): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  896): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  896): Done Updating Usage Statistics in DB @ 1450101411274
,D/TimaService(  896): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  896): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  896): TimaServiceHandler.handleMessage what =1
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  896): !@Sync 40
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  896): !@Sync 41
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 1155s ago
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  896): !@Sync 42
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  896): !@Sync 43
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  896): !@Sync 44
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 1265s ago
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 45
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 46
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 47
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 48
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryService(  896): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 1380s ago
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 49
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/TimaService(  896): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  896): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  896): TimaServiceHandler.handleMessage what =1
,E/SMD     (  291): DCD ON
,V/AlarmManager(  896): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/LightsService(  896): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  896): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  896): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog(  896): !@Sync 50
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/LightsService(  896): [SvcLED]  onSensorChanged::light value = 9
,E/LightSensor(  896): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  896): unregisterListener ::   
,D/LightsService(  896): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,V/AlarmManager(  896): waitForAlarm result :8
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 51
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 52
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 1500s ago
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 53
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 54
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 55
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 56
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 1625s ago
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 57
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 58
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 59
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/NetworkStatsFactory(  896): UpdateStatsForKnox
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,D/TimaService(  896): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  896): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  896): TimaServiceHandler.handleMessage what =1
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  896): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  896): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,V/AlarmManager(  896): waitForAlarm result :4
,V/NetworkStats(  896): performPollLocked(flags=0x3)
,D/NtpTrustedTime(  896): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  896): UpdateStatsForKnox
,D/ConnectivityService(  896): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,V/NetworkStats(  896): performPollLocked() took 26ms
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): stay LED for fully charged
,D/NtpTrustedTime(  896): currentTimeMillis() cache hit
,D/NtpTrustedTime(  896): currentTimeMillis() cache hit
,D/NtpTrustedTime(  896): currentTimeMillis() cache hit
,I/ProcessStatsService(  896): Prepared write state in 11ms
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ProcessStatsService(  896): Pruning old procstats: /data/system/procstats/state-2015-12-13-13-10-01.bin
,V/AlarmManager(  896): OOI=Alarm{286b8ba5 type 0 when 1450103832070 com.google.android.gms}
,D/ConnectivityService(  896): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1473): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 1473): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1473): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1473): Tagging socket 62 with tag 1000040100000000{268436481,0} uid 10015, pid: 1473, getuid(): 10015
,I/qtaguid ( 1473): Tagging socket 70 with tag 1000040100000000{268436481,0} uid 10015, pid: 1473, getuid(): 10015
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,E/Watchdog(  896): !@Sync 61
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,I/PowerManagerService(  896): [PWL] Off : 1755s ago
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  896): !@Sync 62
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,V/AlarmManager(  896): waitForAlarm result :8
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  896): stay LED for fully charged
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/Watchdog(  896): !@Sync 63
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
I/MotionRecognitionService(  896): Plugged
I/MotionRecognitionService(  896): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  896): stay LED for fully charged
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  896): !@Sync 64
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  896): Plugged
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  896): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  896): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  896): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  896): Plugged
,I/MotionRecognitionService(  896): setPowerConnected  = true
,D/BatteryService(  896): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6480): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6480): Disconnected process message: 10
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  896): !@Sync 65
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD ON
,D/SSRM:n  (  896): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  291): DCD ON
,E/SMD     (  291): DCD ON
,D/BatteryService(  896): !@BatteryListener : batteryPropertiesChanged!
,TIME-OUT KILL (timeout was 1800000ms),E/SMD     (  291): DCD ON
D/AndroidRuntime( 8133): 
D/AndroidRuntime( 8133): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8133): CheckJNI is OFF
D/AndroidRuntime( 8133): readGMSProperty: start
D/AndroidRuntime( 8133): readGMSProperty: already setted!!
D/AndroidRuntime( 8133): readGMSProperty: end
D/AndroidRuntime( 8133): addProductProperty: start
E/AffinityControl( 8133): AffinityControl: registerfunction enter
D/AndroidRuntime( 8133): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  896): START PACKAGE DELETE: observer{438782975}
D/PackageManager(  896): pkg{<packageName>}
D/PackageManager(  896): user{0}
D/PackageManager(  896): caller{2000}
D/PackageManager(  896): flags{3}
D/PersonaManagerService(  896): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  896): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  896): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  896): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  896): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  896): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  896): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  896): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  896): getApplicationUninstallationEnabled
D/ApplicationPolicy(  896): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  896): !@killApplicatoin: 10284, uninstall pkg
I/ActivityManager(  896): Force stopping com.test.thalitest appid=10284 user=-1: uninstall pkg
I/ActivityManager(  896): Killing 6370:com.test.thalitest/u0a284 (adj 0): stop com.test.thalitest
I/WindowState(  896): WIN DEATH: Window{2c8581f2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  254): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  254): id=13 Removed NainActivit (-2/8)
I/SurfaceFlinger(  254): id=13 Removed NainActivit (-2/8)
D/PointerIcon(  896): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  896): setMouseCustomIcon IconType is same.101
D/PointerIcon(  896): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  896): setHoveringSpenCustomIcon IconType is same.1
W/PackageSettings(  896): Skipping PackageSetting{32f58100 com.example.hello/10268} due to missing metadata
I/ActivityManager(  896): Killing 7286:com.sec.android.app.samsungapps/u0a45 (adj 11): empty for 1802s
I/ActivityManager(  896): Killing 7613:com.google.android.gms:car/u0a15 (adj 11): empty for 1805s
I/ActivityManager(  896): Killing 7304:com.google.android.syncadapters.calendar/u0a129 (adj 11): empty for 1806s
I/ActivityManager(  896): Killing 7064:com.android.providers.calendar/u0a51 (adj 11): empty for 1806s
I/ActivityManager(  896): Killing 7506:com.google.android.videos/u0a203 (adj 11): empty for 1807s
I/ActivityManager(  896): Killing 7173:com.google.android.apps.magazines/u0a146 (adj 11): empty for 1809s
I/ActivityManager(  896): Killing 7399:com.google.android.gm/u0a128 (adj 11): empty for 1809s
I/ActivityManager(  896): Killing 7351:com.google.android.talk/u0a131 (adj 11): empty for 1810s
I/ActivityManager(  896): Killing 7099:com.sec.spp.push/u0a43 (adj 13): empty for 1810s
I/ActivityManager(  896): Killing 7037:com.android.calendar/u0a172 (adj 13): empty for 1811s
I/ActivityManager(  896): Killing 7331:com.sec.android.widgetapp.SPlannerAppWidget/u0a171 (adj 13): empty for 1811s
I/ActivityManager(  896): Killing 7265:com.samsung.android.service.travel/u0a200 (adj 13): empty for 1812s
I/ActivityManager(  896): Killing 6453:com.samsung.android.securitylogagent/1000 (adj 13): empty for 1812s
I/ActivityManager(  896): Killing 6552:com.android.email/u0a186 (adj 13): empty for 1812s
I/ActivityManager(  896): Killing 7248:com.samsung.android.sconnect/u0a158 (adj 13): empty for 1812s
I/ActivityManager(  896): Killing 6486:tv.peel.samsung.app/u0a152 (adj 13): empty for 1812s
I/ActivityManager(  896): Killing 6860:com.android.chrome/u0a104 (adj 13): empty for 1813s
I/ActivityManager(  896): Killing 7144:com.samsung.android.scloud.backup/u0a74 (adj 15): empty for 1813s
I/ActivityManager(  896): Killing 6053:com.osp.app.signin/u0a50 (adj 15): empty for 1813s
I/ActivityManager(  896): Killing 7080:com.qualcomm.timeservice/1000 (adj 15): empty for 1814s
I/ActivityManager(  896): Killing 7022:com.policydm/1000 (adj 15): empty for 1814s
I/ActivityManager(  896): Killing 6998:com.sec.esdk.elm/u0a116 (adj 15): empty for 1814s
I/ActivityManager(  896): Killing 6920:com.sec.android.soagent/u0a42 (adj 15): empty for 1814s
I/ActivityManager(  896): Killing 6648:com.vlingo.midas/u0a38 (adj 15): empty for 1814s
I/ActivityManager(  896): Killing 6980:com.samsung.android.app.pinboard:tagService/u0a36 (adj 15): empty for 1814s
I/ActivityManager(  896):   Force finishing activity ActivityRecord{af00a8c u0 com.test.thalitest/.MainActivity t3}
D/FocusedStackFrame(  896): Set to : 0
W/ActivityManager(  896): Spurious death for ProcessRecord{221d3dcc 6370:com.test.thalitest/u0a284}, curProc for 6370: null
W/libprocessgroup(  896): failed to open /acct/uid_10152/pid_6486/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10104/pid_6860/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10045/pid_7286/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10015/pid_7613/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10129/pid_7304/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10051/pid_7064/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10203/pid_7506/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10146/pid_7173/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10128/pid_7399/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10131/pid_7351/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10043/pid_7099/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10172/pid_7037/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10171/pid_7331/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10200/pid_7265/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_1000/pid_6453/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10186/pid_6552/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10158/pid_7248/cgroup.procs: No such file or directory
D/ConnectivityService(  896): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/libprocessgroup(  896): failed to open /acct/uid_10042/pid_6920/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_1000/pid_7022/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10116/pid_6998/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10038/pid_6648/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10036/pid_6980/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10050/pid_6053/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_10074/pid_7144/cgroup.procs: No such file or directory
W/libprocessgroup(  896): failed to open /acct/uid_1000/pid_7080/cgroup.procs: No such file or directory
I/ActivityManager(  896): Force stopping com.test.thalitest appid=10284 user=0: pkg removed
D/ResourcesManager(  896): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
E/SamsungIME( 1722): mOCRHelper is null
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
I/art     ( 1575): Explicit concurrent mark sweep GC freed 22705(1348KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 19MB/31MB, paused 714us total 73.480ms
E/Zygote  ( 8173): MountEmulatedStorage()
I/libpersona( 8173): KNOX_SDCARD checking this for 10023
E/Zygote  ( 8173): v2
I/libpersona( 8173): KNOX_SDCARD not a persona
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
I/art     ( 5204): Explicit concurrent mark sweep GC freed 43380(2MB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 15MB/26MB, paused 584us total 69.699ms
I/ActivityManager(  896): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8173 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/SELinux ( 8173): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 8173): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 8173): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
W/GeofencerStateMachine( 1473): Ignoring removeGeofence because network location is disabled.
I/InputReader(  896): Reconfiguring input devices.  changes=0x00000010
D/TimaKeyStoreProvider( 8173): TimaSignature is unavailable
D/ActivityThread( 8173): Added TimaKeyStore provider
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
I/art     ( 1754): Explicit concurrent mark sweep GC freed 40802(2MB) AllocSpace objects, 7(112KB) LOS objects, 25% free, 23MB/31MB, paused 1.168ms total 206.836ms
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Books/Books.apk
D/Launcher( 1432): onRestart, Launcher: 876462860
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/Launcher( 1432): onStart, Launcher: 876462860
D/Launcher.HomeView( 1432): onStart
V/ActivityThread( 1432): updateVisibility : ActivityRecord{5583a19 token=android.os.BinderProxy@3faa02aa {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1778): [237392/8] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 1778): [237392/8] SurfaceWidget drawing first frame
D/accuweather( 1778): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
I/SurfaceFlinger(  254): id=16 createSurf (1080x1920),1 flag=4, Mauncher
V/WindowOrientationListener(  896): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  896): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  896): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  896): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  896): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/ResourcesManager( 8173): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/StatusBarManagerService(  896): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  896): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  896): setMouseCustomIcon IconType is same.101
D/PointerIcon(  896): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  896): setHoveringSpenCustomIcon IconType is same.1
D/StatusBarManagerService(  896): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/InputMethodManagerService(  896): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService(  896): Got RemoteException sending setActive(false) notification to pid 6370 uid 10284
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Music2/Music2.apk
W/ContextImpl(  896): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
I/KLMS-2.4.511: ( 8173): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.511: ( 8173): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1450102186191
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
I/KLMS-2.4.511: ( 8173): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.511: ( 8173): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
I/Timeline(  896): Timeline: Activity_windows_visible id: ActivityRecord{2b213b0c u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:1988699
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/SecContentProvider2(  896): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  896): mCursor = null
D/RegisteredServicesCache( 1408): empty dynamic service
D/RCPManagerService(  896): PackageReceiver onReceive()
I/HarmonyEASService(  896): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  896): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  896): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  896): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  896): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  896): uID is 10284
V/EnterpriseBillingPolicy(  896): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  896): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  896): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  896): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  896): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  896): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  896): getBillingProfileForVpnEngine - end - null
D/TaskPersister(  896): removeObsoleteFile: deleting file=3_task.xml
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8199): MountEmulatedStorage()
E/Zygote  ( 8199): v2
I/libpersona( 8199): KNOX_SDCARD checking this for 10116
I/libpersona( 8199): KNOX_SDCARD not a persona
I/art     (  896): Explicit concurrent mark sweep GC freed 26470(2MB) AllocSpace objects, 9(144KB) LOS objects, 17% free, 37MB/45MB, paused 2.229ms total 455.688ms
I/ActivityManager(  896): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8199 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
E/SMD     (  291): DCD ON
D/PackageManager(  896): delete codoeFile: 
I/AASAUninstall(  896):  com.test.thalitest not target!
D/PackageManager(  896): result of delete: 1{438782975}
I/SELinux ( 8199): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/AndroidRuntime( 8133): Shutting down VM
I/SELinux ( 8199): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 8199): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/TimaKeyStoreProvider( 8199): TimaSignature is unavailable
D/ActivityThread( 8199): Added TimaKeyStore provider
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/ResourcesManager( 8199): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/EnterpriseDeviceManagerService(  896): Package has changed for user 0
D/EnterpriseDeviceManagerService(  896): Admin package name: com.google.android.gms
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
D/elm:14491( 8199): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/elm:14491( 8199): ELMEngine.ELMEngine( context ).
D/elm:14491( 8199): MDMBridge.setEnterpriseBridge()
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/elm:14491( 8199): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/elm:14491( 8199): ElmAgentService : onCreate()
D/elm:14491( 8199): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 8199): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 8199): MDMBridge.getInstance()
D/elm:14491( 8199): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491( 8199): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 8215): MountEmulatedStorage()
I/libpersona( 8215): KNOX_SDCARD checking this for 10021
E/Zygote  ( 8215): v2
I/libpersona( 8215): KNOX_SDCARD not a persona
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
I/ActivityManager(  896): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8215 uid=10021 gids={50021, 9997} abi=armeabi-v7a
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
I/SELinux ( 8215): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 8215): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SELinux ( 8215): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/elm:14491( 8199): ElmAgentService : onDestroy().
D/TimaKeyStoreProvider( 8215): TimaSignature is unavailable
D/ActivityThread( 8215): Added TimaKeyStore provider
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager( 8215): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Maps/Maps.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8215): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8215): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8215): onReceive() : package name is not s health. Return !!!
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  896): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
W/ResourcesManager(  896): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  896): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  896): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  896): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
E/Zygote  ( 8231): MountEmulatedStorage()
I/libpersona( 8231): KNOX_SDCARD checking this for 1000
E/Zygote  ( 8231): v2
I/libpersona( 8231): KNOX_SDCARD not a persona
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
I/ActivityManager(  896): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8231 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  896): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/Resources(  896): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager(  896): clearDefaults: com.test.thalitest
I/CrashAnrDetector(  896): onPackageRemoved : com.test.thalitest
I/SELinux ( 8231): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 8231): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 8231): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 8231): TimaSignature is unavailable
D/ActivityThread( 8231): Added TimaKeyStore provider
D/ResourcesManager( 8231): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
I/PCWCLIENTTRACE_LOG( 8231): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 8231): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 8231): new DMDBOpenHelper instance
E/SQLiteLog( 8231): (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 8231): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase( 8231): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8231): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8231): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 8231): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 8231): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8231): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8231): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8231): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 8231): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 8231): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 8231): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 8231): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 8231): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8231): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8231): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/SQLiteDatabase( 8231): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1716)
E/SQLiteDatabase( 8231): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1685)
E/SQLiteDatabase( 8231): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5557)
E/SQLiteDatabase( 8231): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5152)
E/SQLiteDatabase( 8231): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5092)
E/SQLiteDatabase( 8231): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
E/SQLiteDatabase( 8231): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
E/SQLiteDatabase( 8231): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8231): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 8231): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/SQLiteDatabase( 8231): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8231): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8231): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/SQLiteDatabase( 8231): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
D/AndroidRuntime( 8231): Shutting down VM

```
