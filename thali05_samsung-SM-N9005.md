#### Test 50650278c17c777_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
E/SMD     (  293): DCD ON
,D/AndroidRuntime( 6572): 
D/AndroidRuntime( 6572): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6572): CheckJNI is OFF
D/AndroidRuntime( 6572): readGMSProperty: start
D/AndroidRuntime( 6572): readGMSProperty: already setted!!
D/AndroidRuntime( 6572): readGMSProperty: end
D/AndroidRuntime( 6572): addProductProperty: start
E/AffinityControl( 6572): AffinityControl: registerfunction enter
D/AndroidRuntime( 6572): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  894): inState():  stateMachine is null !!
I/PersonaManagerService(  894): PersonaId don't exist
I/ActivityManager(  894): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
I/ActivityManager(  894): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  894): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  894): mDVFSHelper.acquire()
D/FocusedStackFrame(  894): Set to : 0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  894): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6587 uid=10278 gids={50278, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/PointerIcon(  894): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  894): setMouseCustomIcon IconType is same.101
D/PointerIcon(  894): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  894): setHoveringSpenCustomIcon IconType is same.1
E/Zygote  ( 6587): MountEmulatedStorage()
E/Zygote  ( 6587): v2
I/libpersona( 6587): KNOX_SDCARD checking this for 10278
I/libpersona( 6587): KNOX_SDCARD not a persona
D/AndroidRuntime( 6572): Shutting down VM
I/SELinux ( 6587): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6587): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6587): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6587): TimaSignature is unavailable
D/ActivityThread( 6587): Added TimaKeyStore provider
V/WindowOrientationListener(  894): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  894): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  894): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  894): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  894): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/ActivityManager(  894): Display changed displayId=0
D/SurfaceWidgetView( 1444): destroyHardwareResources():1011741810
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 6587): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger(  254): id=6 Removed Mauncher (6/8)
I/SurfaceFlinger(  254): id=6 Removed Mauncher (-2/8)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1794): [237392/8] Surface widget visibility changed visibility = false on instance = 1
V/ActivityThread( 1444): updateVisibility : ActivityRecord{2d9312cb token=android.os.BinderProxy@27798bbd {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1444): onTrimMemory. Level: 20
,I/WebViewFactory( 6587): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 6587): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 6587): Loading: webviewchromium
,I/LibraryLoader( 6587): Time to load native libraries: 5 ms (timestamps 7306-7311)
I/LibraryLoader( 6587): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6587): Binding Chromium to main looper Looper (main, tid 1) {3a3bca3c}
,I/LibraryLoader( 6587): Expected native library version number "",actual native library version number ""
,I/chromium( 6587): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6587): Initializing chromium process, renderers=0
,W/art     ( 6587): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 6587): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium( 6587): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 6587): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
,I/chromium( 6587): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
,D/BluetoothAdapter( 6587): 695964613: getState() :  mService = null. Returning STATE_OFF
,I/Adreno-EGL( 6587): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6587): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6587): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6587): Local Branch: mybranch5813579
I/Adreno-EGL( 6587): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6587): Local Patches: NONE
I/Adreno-EGL( 6587): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,W/ActivityManager(  894): Activity pause timeout for ActivityRecord{3438da6d u0 com.test.thalitest/.MainActivity t3}
,W/chromium( 6587): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 6587): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 6587): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6587): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6587): CordovaWebView is running on device made by: samsung
,W/art     ( 6587): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6587): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity( 6587): performCreate Call secproduct feature valuefalse
D/Activity( 6587): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer( 6587): Render dirty regions requested: true
,D/Atlas   ( 6587): Validating map...
,D/ActivityManager(  894): post active user change for 0
,D/KnoxTimeoutHandler(  894): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  894): handleActiveUserChange for user 0
,V/ActivityThread( 6587): updateVisibility : ActivityRecord{3504ca token=android.os.BinderProxy@32243a6c {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger(  254): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService(  894): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  894): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  894): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  894): setMouseCustomIcon IconType is same.101
D/PointerIcon(  894): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  894): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer( 6587): Initialized EGL, version 1.4
,I/OpenGLRenderer( 6587): HWUI protection enabled for context ,  &this =0xaf876038 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 6587): Enabling debug mode 0
,D/InputMethodManagerService(  894): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager(  894): mDVFSHelper.release()
I/Timeline(  894): Timeline: Activity_windows_visible id: ActivityRecord{3438da6d u0 com.test.thalitest/.MainActivity t3} time:157866
,I/SamsungIME( 1729): getCurrentCandidateView
,W/IInputConnectionWrapper( 6587): showStatusIcon on inactive InputConnection
,I/Timeline( 6587): Timeline: Activity_idle id: android.os.BinderProxy@32243a6c time:157877
,D/SamsungIME( 1729): Dismiss ExpandCandiate
,I/chromium( 6587): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6587): 
,D/JsMessageQueue( 6587): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1729): getDebugLevel  : 0x4f4c
,D/jxcore_app_log( 6587): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1356778624
,D/JX-Cordova( 6587): jxcore cordova android initializing
,I/SamsungIME( 1729): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1729): KeybaordView init() : load resources
,I/SamsungIME( 1729): getCurrentKeyboard
I/SamsungIME( 1729): getTextKeyboard
,D/SamsungIME( 1729): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/SMD     (  293): DCD ON
,D/SamsungIME( 1729): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/PowerManagerService(  894): [PWL] Off : 50s ago
,W/jxcore-log( 6587): Initializing JXcore engine
,W/jxcore-log( 6587): JXcore engine is ready
,W/jxcore-log( 6587): Starting JXcore engine
,E/auditd  ( 1862): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  894): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  894): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  894): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6665 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 6665): MountEmulatedStorage()
E/Zygote  ( 6665): v2
I/libpersona( 6665): KNOX_SDCARD checking this for 1000
I/libpersona( 6665): KNOX_SDCARD not a persona
,I/SELinux ( 6665): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6665): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6665): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6665): TimaSignature is unavailable
,D/ActivityThread( 6665): Added TimaKeyStore provider
,W/jxcore-log( 6587): Platform android
W/jxcore-log( 6587): 
,W/jxcore-log( 6587): Process ARCH arm
W/jxcore-log( 6587): 
,D/ResourcesManager( 6665): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SSRM:n  (  894): SIOP:: AP = 330, PST = 328, CUR = 450
,D/SecurityLogAgent( 6665):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6665):  SeDenialReceiver : File path = null
,I/ActivityManager(  894): Killing 4976:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,V/AlarmManager(  894): waitForAlarm result :4
D/NtpTrustedTime(  894): forceRefresh() from cache miss
D/NtpTrustedTime(  894): forceRefresh Fail.
D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1190): handleTimeUpdate
,D/KeyguardEffectViewController( 1190): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1190): *** don't update sliding image ***
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  894): stay LED for fully charged
D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1190): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1190): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/jxcore-log( 6587): JXcore Cordova bridge is ready!
I/jxcore-log( 6587): 
,W/jxcore-log( 6587): JXcore engine is started
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/jxcore-log( 6587): Toggling radios to true
I/jxcore-log( 6587): 
,D/BluetoothAdapter( 6587): enable()
,W/ActivityManager(  894): Permission Denial: getCurrentUser() from pid=6587, uid=10278 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService(  894): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService(  894): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6587, uid=10278 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService(  894): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/BluetoothManagerService(  894): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2141)
W/BluetoothManagerService(  894): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:671)
W/BluetoothManagerService(  894): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService(  894): 	at android.os.Binder.execTransact(Binder.java:446)
E/DevicePolicyManagerService(  894): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService(  894): getAllowBluetoothMode - value retunrs : 2
,D/SettingsProvider(  894): name = bluetooth_on
,E/DevicePolicyManagerService(  894): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService(  894): getAllowBluetoothMode - value retunrs : 2
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,I/WifiManager( 6587): packageName : com.test.thalitest
,D/SecContentProvider(  894): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  894): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  894): mCursor = null
,D/WifiService(  894): setWifiEnabled: true pid=6587, uid=10278
,W/ActivityManager(  894): Permission Denial: getCurrentUser() from pid=6587, uid=10278 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  894): Failed getting userId using ActivityManagerNative
W/WifiService(  894): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6587, uid=10278 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  894): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/WifiService(  894): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2181)
W/WifiService(  894): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2169)
W/WifiService(  894): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  894): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  894): name = wifi_on
,E/WifiHW  (  894): ##################### set firmware type 0 #####################
,I/WifiHW  (  284): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
I/WifiHW  (  284): module is semco
E/WifiHW  (  284): ==========[WIFI] SEMCO MODULE ===========
I/WifiHW  (  284): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
E/WifiHW  (  284): TEMP_FAILURE_RETRY complete
D/SoftapController(  284): Softap fwReload - Ok
,I/WifiService(  894): disconnect: pid=6587, uid=10278
,I/jxcore-log( 6587): Radios toggled
I/jxcore-log( 6587): 
,D/CommandListener(  284): Setting iface cfg
D/CommandListener(  284): Trying to bring down wlan0
,D/CommandListener(  284): Clearing all IP addresses on wlan0
,E/Zygote  ( 6693): MountEmulatedStorage()
E/Zygote  ( 6693): v2
I/libpersona( 6693): KNOX_SDCARD checking this for 1002
I/libpersona( 6693): KNOX_SDCARD not a persona
,E/WifiHW  (  894): supplicant_name : p2p_supplicant
,I/ActivityManager(  894): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6693 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/SmartBondingService(  894): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/WifiMonitor(  894): startMonitoring(wlan0) with mConnected = false
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 6693): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6693): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6693): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/StatusBar.NetworkController( 1190): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1190): onWifiSignalChanged enabled=false enabledDesc:null
D/STATUSBAR-WifiQuickSettingButton( 1190): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1190): Wifi onReceive(2)
D/HotspotTile( 1190): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1190): onStateChanged: Wi-Fi
,D/SmartBondingService(  894): getNetworkEnabled : wifi : false mobile : true
,D/HotspotTile( 1190): onReceive : 2, 0
,D/WifiCredService( 1312): Action received :android.net.wifi.WIFI_STATE_CHANGED
,I/ActivityManager(  894): Start proc tv.peel.samsung.app for broadcast tv.peel.samsung.app/com.peel.receiver.ConnectivityActionReceiver: pid=6706 uid=10152 gids={50152, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,E/Zygote  ( 6706): MountEmulatedStorage()
I/libpersona( 6706): KNOX_SDCARD checking this for 10152
E/Zygote  ( 6706): v2
I/libpersona( 6706): KNOX_SDCARD not a persona
,I/wpa_supplicant( 6699): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 6699): Successfully initialized wpa_supplicant
,I/SecureStorage( 6699): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6699): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  393): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6699
I/SecureStorage(  393): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
I/SecureStorage( 6699): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6699): ssSupport state is = 1
,I/wpa_supplicant( 6699): >>>>> GET KEY, IV <<<<<
,I/SecureStorage( 6699): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  393): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6699
I/SecureStorage(  393): [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,I/SELinux ( 6706): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6706): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6706): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6693): TimaSignature is unavailable
,D/ActivityThread( 6693): Added TimaKeyStore provider
,D/ResourcesManager( 6693): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,W/ResourcesManager( 6693): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 6693): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6706): TimaSignature is unavailable
,D/ActivityThread( 6706): Added TimaKeyStore provider
,D/ResourcesManager( 6706): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,I/BluetoothA2dpSinkServiceJni( 6693): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig( 6693): Adding GattService
,D/BtSettings.ProfileConfig( 6693): Adding HeadsetService
D/BtSettings.ProfileConfig( 6693): Adding A2dpService
,D/BtSettings.ProfileConfig( 6693): Adding HidService
D/BtSettings.ProfileConfig( 6693): Adding HealthService
,D/BtSettings.ProfileConfig( 6693): Adding PanService
D/BtSettings.ProfileConfig( 6693): Adding BluetoothMapService
,D/BtSettings.ProfileConfig( 6693): Adding SapService
D/BtSettings.ProfileConfig( 6693): Adding HeadsetClientService
D/BtSettings.ProfileConfig( 6693): Adding A2dpSinkService
,D/BtSettings.ProfileConfig( 6693): Adding SapClientService
D/BtSettings.ProfileConfig( 6693): Adding HidDevService
I/BtSettings.ProfileConfig( 6693): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider(  894): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider(  894): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  894): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  894): selectionArgs: false
D/SettingsProvider(  894): selectionArgs: 1002
D/SecContentProvider(  894): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  894): ret = -1
,W/BackupManagerService(  894): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  894): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider(  894): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  894): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  894): selectionArgs: false
D/SettingsProvider(  894): selectionArgs: 1002
D/SecContentProvider(  894): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  894): ret = -1
,W/BackupManagerService(  894): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  894): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,D/SettingsProvider(  894): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  894): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  894): selectionArgs: false
D/SettingsProvider(  894): selectionArgs: 1002
D/SecContentProvider(  894): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  894): ret = -1
,W/BackupManagerService(  894): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  894): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider(  894): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  894): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  894): selectionArgs: false
D/SettingsProvider(  894): selectionArgs: 1002
D/SecContentProvider(  894): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  894): ret = -1
,W/BackupManagerService(  894): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  894): name = bt_svcst_com.android.bluetooth.hdp.HealthService
,D/SettingsProvider(  894): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  894): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  894): selectionArgs: false
D/SettingsProvider(  894): selectionArgs: 1002
D/SecContentProvider(  894): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  894): ret = -1
,W/BackupManagerService(  894): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  894): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider(  894): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  894): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  894): selectionArgs: false
D/SettingsProvider(  894): selectionArgs: 1002
D/SecContentProvider(  894): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  894): ret = -1
,W/BackupManagerService(  894): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  894): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,D/SettingsProvider(  894): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  894): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  894): selectionArgs: false
D/SettingsProvider(  894): selectionArgs: 1002
,D/SecContentProvider(  894): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  894): ret = -1
,W/BackupManagerService(  894): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  894): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider(  894): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  894): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  894): selectionArgs: false
D/SettingsProvider(  894): selectionArgs: 1002
D/SecContentProvider(  894): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  894): ret = -1
,W/BackupManagerService(  894): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  894): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,D/SettingsProvider(  894): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  894): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  894): selectionArgs: false
D/SettingsProvider(  894): selectionArgs: 1002
D/SecContentProvider(  894): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  894): ret = -1
,W/BackupManagerService(  894): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  894): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider(  894): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  894): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  894): selectionArgs: false
D/SettingsProvider(  894): selectionArgs: 1002
D/SecContentProvider(  894): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  894): ret = -1
,W/BackupManagerService(  894): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  894): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider(  894): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  894): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  894): selectionArgs: false
D/SettingsProvider(  894): selectionArgs: 1002
D/SecContentProvider(  894): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  894): ret = -1
,W/BackupManagerService(  894): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  894): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider(  894): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  894): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  894): selectionArgs: false
D/SettingsProvider(  894): selectionArgs: 1002
D/SecContentProvider(  894): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  894): ret = -1
,W/BackupManagerService(  894): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterState( 6693): make
,I/bluedroid( 6693): init
I/BluetoothAdapterState( 6693): Entering OffState
,I/bte_conf( 6693): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 6693): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6693): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,I/bte_conf( 6693): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif ( 6693): btif_fetch_local_ble_random_bdaddr
,I/bluedroid( 6693): get_profile_interface socket
I/GKI_LINUX( 6693): gki_task_entry task_id=1 [BTIF] starting
I/bluedroid( 6693): get_profile_interface map_client
,D/BluetoothAdapterService( 6693): checkAddrForIOP: Loading from conf
,D/BluetoothAdapterProperties( 6693): Address is:E0:DB:10:1F:C9:5E
,E/BluetoothServiceJni( 6693): populateRssiValuesNative
,I/bluedroid( 6693): getModelRssiValues
E/BluetoothServiceJni( 6693): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 6693): modelRssiValuesCallback, low, mid, high = -70,-60,127
I/bluedroid( 6693): config_hci_snoop_log
,D/BluetoothManagerService(  894): Broadcasting onBluetoothServiceUp() to 10 receivers.
,D/SettingsProvider(  894): name = bluetooth_name
D/BluetoothAdapterProperties( 6693): Name is: Note3-1
E/DevicePolicyManagerService(  894): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService(  894): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider(  894): uri = 3 selection = isBluetoothEnabled
,D/BluetoothAdapterState( 6693): CURRENT_STATE=OFF, MSG = USER_TURN_ON
D/BluetoothAdapterProperties( 6693): Setting state to 11
,I/BluetoothAdapterState( 6693): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 6693): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 6693): updateAdapterState state is 11
,D/BluetoothAdapterService( 6693): Autoconnection is available 
D/BluetoothAdapterService( 6693): updateAdapterState prevState = 10newState = 11
,D/BluetoothSecureManager( 6693): getInstant: null
D/BluetoothSecureManager( 6693): calling getMethod for getService
D/BluetoothSecureManager( 6693): calling getService
,D/BluetoothSecureManager( 6693): getService return binder: android.os.BinderProxy@27d5767d
D/BluetoothSecureManagerService(  894): isSecureModeEnabled
D/BluetoothSecureManagerService(  894): getSecureModeSetting, name: secure_mode_enable
D/BtConfig.SecureMode( 6693): isSecureModeOn:false
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/InputMethodManagerService(  894): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  894): [BT Setting State] State =11
,D/BluetoothTile( 1190):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1190): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/StatusBarManagerService(  894): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
,D/STATUSBAR-QSTileView( 1190): onStateChanged: Bluetooth
,D/StatusBarManagerService(  894): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1190): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 )
,W/BluetoothAdapterService( 6693): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 6693): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 6693): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 6693): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 6693): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 6693): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 6693): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 6693): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6693): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6693): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6693): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 6693): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,D/BluetoothBondStateMachine( 6693): make
,I/WebViewFactory( 6706): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 6706): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
W/BluetoothAdapterService( 6693): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
I/BluetoothBondStateMachine( 6693): StableState(): Entering Off State
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 6693): Not skipping com.android.bluetooth.gatt.GattService
I/SamsungIME( 1729): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
I/BtGatt.JNI( 6693): classInitNative(L890): classInitNative: Success!
W/BluetoothAdapterService( 6693): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 6693): Not skipping com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 6693): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 6693): Not skipping com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 6693): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 6693): Not skipping com.android.bluetooth.hid.HidService
D/BtGatt.DebugUtils( 6693): handleDebugAction() action=null
I/SecureStorage(  393): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
D/BtGatt.GattService( 6693): Received start request. Starting profile...
W/BluetoothAdapterService( 6693): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 6693): Not skipping com.android.bluetooth.hdp.HealthService
D/BtGatt.GattService( 6693): start()
I/bluedroid( 6693): get_profile_interface gatt
D/BluetoothAdapterService( 6693): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297b93c5
D/BtGatt.AdvertiseManager( 6693): advertise manager created
W/BluetoothAdapterService( 6693): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 6693): Not skipping com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 6693): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 6693): Not skipping com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 6693): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 6693): Not skipping com.broadcom.bt.service.sap.SapService
I/LibraryLoader( 6706): Loading: webviewchromium
W/BluetoothAdapterService( 6693): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6693): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6693): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6693): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6693): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6693): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6693): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 6693): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState( 6693): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
I/LibraryLoader( 6706): Time to load native libraries: 8 ms (timestamps 1066-1074)
I/LibraryLoader( 6706): Expected native library version number "",actual native library version number ""
D/BluetoothAdapterService( 6693): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297b93c5
D/HeadsetService( 6693): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 6693): classInitNative: succeeds
,D/HeadsetStateMachine( 6693): make
,E/HeadsetStateMachine( 6693): # of Max HF connection is 2
,I/bluedroid( 6693): get_profile_interface handsfree
,I/DualScoManager( 6693): Instantiating Dual Sco Manager
I/DualScoManager( 6693): Set HeadsetServiceHelper
,D/BluetoothAtMessage( 6693): createCMTIContentObservers
D/SettingsProvider(  894): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider(  894): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  894): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  894): selectionArgs: false
D/SettingsProvider(  894): selectionArgs: 1002
D/SecContentProvider(  894): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  894): ret = -1
W/BackupManagerService(  894): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine( 6693): Enter Disconnected: -2
,D/BluetoothAdapterService( 6693): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297b93c5
,E/HeadsetStateMachine( 6693): set to mRemoteBrsf = 0
,D/BluetoothA2dp(  894): Proxy object connected
D/A2dpService( 6693): Received start request. Starting profile...
,D/BluetoothA2dp( 2930): Proxy object connected
,I/BluetoothAvrcpServiceJni( 6693): classInitNative: succeeds
,V/Avrcp   ( 6693): make
,V/Avrcp   ( 6693): Avrcp
,I/bluedroid( 6693): get_profile_interface avrcp
D/HeadsetStateMachine( 6693): map size, before remove : 0
D/HeadsetStateMachine( 6693): map size, after remove: 0
D/HeadsetStateMachine( 6693): mNextConnectingDevice : null
,V/Avrcp   ( 6693): start
,V/WebViewChromiumFactoryProvider( 6706): Binding Chromium to main looper Looper (main, tid 1) {2002211a}
,E/RemoteController( 6693): Cannot set synchronization mode on an unregistered RemoteController
,V/Avrcp   ( 6693): ++registerMediaPlayers++
,I/Avrcp   ( 6693): No of Audio players :: 2
,I/Avrcp   ( 6693): App Package name is com.google.android.music
,D/ResourcesManager( 6693): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/Avrcp   ( 6693): App pkg name is Google Play Music
,I/Avrcp   ( 6693): Name::Google Play Music
I/LibraryLoader( 6706): Expected native library version number "",actual native library version number ""
,I/chromium( 6706): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
V/Avrcp   ( 6693): MediaPlayerInfo: mPlayerId=1
I/Avrcp   ( 6693): App Package name is com.sec.android.app.music
,D/ResourcesManager( 6693): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/Avrcp   ( 6693): App pkg name is Music
,I/Avrcp   ( 6693): Name::Music
V/Avrcp   ( 6693): MediaPlayerInfo: mPlayerId=2
I/Avrcp   ( 6693):  set player publishabilty with player id::2 toBePublished ::true
,I/Avrcp   ( 6693): No of Video players :: 1
,I/Avrcp   ( 6693): Video App Package name is com.sec.android.app.videoplayer
,D/ResourcesManager( 6693): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/Avrcp   ( 6693): Video App pkg name is Video Player
,I/Avrcp   ( 6693): Name::Video Player
V/Avrcp   ( 6693): MediaPlayerInfo: mPlayerId=3
I/Avrcp   ( 6693): Add tempPlayer
V/Avrcp   ( 6693): MediaPlayerInfo: mPlayerId=4
,I/Avrcp   ( 6693): Total no of players: 4
V/Avrcp   ( 6693): swapping the samsung player with 1st player
I/Avrcp   ( 6693):  Updating now playing list upon AVRCP Start
V/Avrcp   ( 6693): handleMessage, msg=207
,D/BluetoothMediaBrowser( 6693):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,I/BluetoothA2dpServiceJni( 6693): classInitNative: succeeds
,D/A2dpStateMachine( 6693): make
,I/bluedroid( 6693): get_profile_interface a2dp
,I/GKI_LINUX( 6693): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 6693): warning : media task started media_task_refcnt 1 
,I/BrowserStartupController( 6706): Initializing chromium process, renderers=0
,D/BluetoothAdapterService( 6693): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297b93c5
D/A2dpStateMachine( 6693): Enter Disconnected: -2
,W/art     ( 6706): Attempt to remove local handle scope entry from IRT, ignoring
,I/BluetoothHidServiceJni( 6693): classInitNative: succeeds
,D/BluetoothMediaBrowser( 6693): no now playing list
D/BluetoothMediaBrowser( 6693):  getNowPlayingId now playing id : -1
D/Avrcp   ( 6693):  checkNowPlayingList start
,D/HidService( 6693): Received start request. Starting profile...
,I/bluedroid( 6693): get_profile_interface hidhost
D/HidService( 6693): setHidService(): set to: null
D/BluetoothAdapterService( 6693): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297b93c5
,I/BluetoothHealthServiceJni( 6693): classInitNative: succeeds
,D/HealthService( 6693): Received start request. Starting profile...
,W/chromium( 6706): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,I/bluedroid( 6693): get_profile_interface health
,D/BluetoothAdapterService( 6693): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297b93c5
,I/BluetoothPanServiceJni( 6693): classInitNative(L105): succeeds
,D/BluetoothPan(  894): BluetoothPAN Proxy object connected
,W/chromium( 6706): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
D/PanService( 6693): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6693): initializeNative(L110): pan
I/bluedroid( 6693): get_profile_interface pan
,I/chromium( 6706): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=36 off=46780 len=2953
,I/chromium( 6706): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:37 off:229536 len:643667
,D/BluetoothAdapterService( 6693): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297b93c5
,D/BluetoothMapService( 6693): Received start request. Starting profile...
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,I/Adreno-EGL( 6706): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6706): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6706): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6706): Local Branch: mybranch5813579
I/Adreno-EGL( 6706): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6706): Local Patches: NONE
I/Adreno-EGL( 6706): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,E/Zygote  ( 6765): MountEmulatedStorage()
I/libpersona( 6765): KNOX_SDCARD checking this for 10186
E/Zygote  ( 6765): v2
I/libpersona( 6765): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=6765 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 6765): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6765): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6765): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6765): TimaSignature is unavailable
,D/ActivityThread( 6765): Added TimaKeyStore provider
,D/ResourcesManager( 6765): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 6765): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6765): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6765): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6765): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6765): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/chromium( 6706): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
I/SecureStorage( 6699): [INFO]: SPID(0x00000000)Processing data has been completed
,W/chromium( 6706): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,I/SecureStorage( 6699): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6699): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  393): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6699
I/SecureStorage(  393): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
I/SecureStorage( 6699): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6699): ssSupport state is = 1
I/wpa_supplicant( 6699): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant( 6699): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6699): SIM READ ERROR
I/wpa_supplicant( 6699): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6699): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6699): SIM READ ERROR
I/wpa_supplicant( 6699): Blacklist: Clear (all) 
,I/wpa_supplicant( 6699): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6699): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant( 6699): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6699): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,I/wpa_supplicant( 6699): rfkill: Cannot open RFKILL control device
,W/art     ( 6706): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6706): onDetachedFromWindow called when already detached. Ignoring
,D/RCPManagerService(  894): exchangeData() failure , invalid userId
,D/RCPManagerService(  894): exchangeData() failure , invalid userId
,D/RCPManagerService(  894): exchangeData() failure , invalid userId
,E/SMD     (  293): DCD ON
,D/BluetoothAdapterService( 6693): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297b93c5
,I/BluetoothSAPServiceJni( 6693): classInitNative(L204): succeeds
,D/BadgeProvider( 6061): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/SapService( 6693): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 6693): initializeNative(L209): sap
I/bluedroid( 6693): get_profile_interface sap
D/BluetoothAdapterService( 6693): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297b93c5
,E/BluetoothAdapterService(695964613)( 6693): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
D/HeadsetStateMachine( 6693): Try to query the phonestate on bind
,I/Telecom ( 1399): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 1399): BluetoothPhoneService: updateHeadsetWithCallState
,I/Telecom ( 1399): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 1399): Proxy not attached to service
,D/HeadsetStateMachine( 6693): Proxy object connected
,D/HeadsetPhoneState( 6693): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
D/HeadsetPhoneState( 6693): sendDeviceDataStateChanged
D/HeadsetStateMachine( 6693): Disconnected process message: 11
,D/HeadsetPhoneState( 6693): Signal level : previous=0 curr=0
D/BadgeProvider( 6061): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6061): sendNotify, [notify] : null
D/BadgeProvider( 6061): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6061): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 6061): update, [UpdateCount] : 1
E/BluetoothAdapterService(695964613)( 6693): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,V/HeadsetService( 6693): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BluetoothA2dp( 6693): Proxy object connected
D/Launcher.Model( 1444): reloadBadges entered.
D/BluetoothAdapterService( 6693): Bluetooth A2dp source service connected
D/HeadsetStateMachine( 6693): Disconnected process message: 18
,E/BluetoothAdapterService(695964613)( 6693): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/HeadsetStateMachine( 6693): Disconnected process message: 10
D/HeadsetPhoneState( 6693): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6693): Disconnected process message: 11
,E/BluetoothAdapterService(695964613)( 6693): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/RCPManagerService(  894): exchangeData() failure , invalid userId
,E/BluetoothAdapterService(695964613)( 6693): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
E/BluetoothAdapterService(695964613)( 6693): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,E/BluetoothAdapterService(695964613)( 6693): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,E/BluetoothAdapterService(695964613)( 6693): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState( 6693): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 6693): enable
,I/bt_hci_bdroid( 6693): init
,I/GKI_LINUX( 6693): gki_task_entry task_id=0 [BTU] starting
,I/bt_vendor( 6693): init
I/bt_vnd_conf( 6693): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 6693): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 6693): userial_init
D/bt_vendor( 6693): op for 5
,D/bt_vendor( 6693): op for 0
,D/bt_upio ( 6693): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 6693): is_emulator_context : 0
D/bt_upio ( 6693): is_rfkill_disabled ? [0]
D/bt_upio ( 6693): is_rfkill_disabled ? [0]
,D/bt_vendor( 6693): op for 0
D/bt_upio ( 6693): upio_set_bluetooth_power(on: 1)
D/bt_upio ( 6693): is_emulator_context : 0
D/bt_upio ( 6693): is_rfkill_disabled ? [0]
,D/bt_vendor( 6693): op for 3
I/bt_userial_vendor( 6693): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 6693): userial_vendor_open():UART is setup
I/bt_userial_vendor( 6693): device fd = 65 open
,D/bt_vendor( 6693): op for 1
E/bt_hwcfg( 6693): Start CFG HW, HCI reset
D/bt_userial( 6693): Entering userial_read_thread()
,E/SignOutReceiver( 6207): WIFI_STATE_CHANGED_ACTION
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6665): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6665): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6665): StateMachine : Current State = 1
,D/SecurityLogAgent( 6665): StateMachine : Changed Current State = 1
,I/ActivityManager(  894): Killing 4904:com.google.android.gm/u0a128 (adj 15): bgCount ##41
,I/art     (  894): Explicit concurrent mark sweep GC freed 62373(3MB) AllocSpace objects, 33(528KB) LOS objects, 17% free, 37MB/45MB, paused 1.618ms total 117.937ms
,I/ActivityManager(  894): Killing 5756:com.google.android.gms:car/u0a15 (adj 15): bgCount ##41
,D/BluetoothNotiBroadcastReceiver( 1312): onReceive
,D/AuthorizationBluetoothService( 1481): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/ActivityManager(  894): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/Tethering(  894): No numeric data
,D/Tethering(  894): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  894): forceRefresh() from cache miss
D/HotspotTile( 1190): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1190): updateTetherState():false, false
,D/NtpTrustedTime(  894): forceRefresh Fail.
,V/NetworkStats(  894): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  894): UpdateStatsForKnox
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  894): performPollLocked() took 7ms
,D/NtpTrustedTime(  894): forceRefresh() from cache miss
D/NtpTrustedTime(  894): forceRefresh Fail.
,I/wpa_supplicant( 6699): wlan0: Setting scan request: 0 sec 100000 usec
,I/wpa_supplicant( 6699): wlan0: State: DISCONNECTED -> DISCONNECTED
I/SecureStorage( 6699): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6699): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  393): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6699
I/SecureStorage(  393): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
I/SecureStorage( 6699): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6699): ssSupport state is = 1
,I/SecureStorage( 6699): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage,
I/SecureStorage( 6699): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  393): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6699
I/SecureStorage(  393): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,I/SecureStorage( 6699): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6699): ssSupport state is = 1,
I/wpa_supplicant( 6699): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant( 6699): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6699): SIM READ ERROR
,I/wpa_supplicant( 6699): rfkill: Cannot open RFKILL control device,
,I/wpa_supplicant( 6699): p2p0: State: DISCONNECTED -> INACTIVE
,I/wpa_supplicant( 6699): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 6699): p2p0: State: INACTIVE -> DISCONNECTED
,I/wpa_supplicant( 6699): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant( 6699): Skip scan - bUseNetwork false
,E/WifiStateMachine(  894): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative-HAL(  894): callSECApiBoolean - ID [21]
,I/wpa_supplicant( 6699): HOTSPOT20_ENABLE called,
I/wpa_supplicant( 6699): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant( 6699): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6699): SIM READ ERROR,
I/wpa_supplicant( 6699): Blacklist: Clear (all) 
,I/wpa_supplicant( 6699): wlan0: Setting scan request: 0 sec 0 usec
,D/WifiNative-HAL(  894): callSECApiInt - ID [210]
,I/wpa_supplicant( 6699): Skip scan - bUseNetwork false
,D/WifiConfigStore(  894): Loading config and enabling all networks ,
D/SmartBondingService(  894): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
D/WifiCredService( 1312): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/StatusBar.NetworkController( 1190): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1190): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1190): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1190): applyOpen
D/StatusBar.NetworkController( 1190): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1190): applyOpen
,D/StatusBar.NetworkController( 1190): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1190): applyOpen
D/StatusBar.NetworkController( 1190): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1190): applyOpen
,D/STATUSBAR-WifiQuickSettingButton( 1190): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1190): Wifi onReceive(3)
,D/STATUSBAR-QSTileView( 1190): onStateChanged: Wi-Fi
,D/HotspotTile( 1190): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/SmartBondingService(  894): getNetworkEnabled : wifi : true mobile : true
,D/HotspotTile( 1190): onReceive : 3, 0
,E/WifiConfigStore(  894): Not a HS20
,E/SignOutReceiver( 6207): WIFI_STATE_CHANGED_ACTION
,E/WifiConfigStore(  894): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6665): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6665): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6665): StateMachine : Current State = 1
D/SecurityLogAgent( 6665): StateMachine : Changed Current State = 1
,D/WifiNative-HAL(  894): callSECApiInt - ID [65]
,D/WifiNative-HAL(  894): callSECApiBoolean - ID [13]
I/wpa_supplicant( 6699): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 6699): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 6699): reset timer : RESET_TIMER 0
I/wpa_supplicant( 6699): P2P: Current p2p state = IDLE
I/wpa_supplicant( 6699): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 6699): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 6699): First Scan Start
,I/wpa_supplicant( 6699): Scan requested (ret=0) - scan timeout 30 seconds
,D/WifiNative-HAL(  894): Setting external_sim to 1
,D/WifiStateMachine(  894): Setting OUI to DA-A1-19
I/WifiNative-HAL(  894): startHal
E/wifi    (  894): getStaticLongField sWifiHalHandle 0x9c1ff86c
D/wifi    (  894): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x502366
I/WifiNative-HAL(  894): Could not start hal
,E/native  (  894): do suspend true
,E/WifiStateMachine(  894): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
D/WifiP2pService(  894): P2pDisabledState{ what=131203 }
D/WifiScanningService(  894): SCAN_AVAILABLE : 3
D/RttService(  894): SCAN_AVAILABLE : 3
,D/WifiScanningService(  894): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  894): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  894): startHal
E/wifi    (  894): getStaticLongField sWifiHalHandle 0x9995d99c
D/wifi    (  894): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x202362
I/WifiNative-HAL(  894): Could not start hal
E/WifiScanningService(  894): could not start HAL
,D/CommandListener(  284): Setting iface cfg
D/CommandListener(  284): Trying to bring up p2p0
,D/WifiMonitor(  894): startMonitoring(p2p0) with mConnected = true
,D/WifiP2pService(  894): P2pEnablingState
D/WifiP2pService(  894): P2pEnablingState{ what=147457 }
,D/WifiP2pService(  894): P2p socket connection successful
E/WifiStateMachine(  894): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-HAL(  894): callSECStringApiVoid - ID [215]
E/WifiNative-HAL(  894): invaild command id : 215
D/WifiP2pService(  894): P2pEnabledState
,D/WifiDisplayController(  894): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
E/WifiStateMachine(  894): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/WifiDisplayController(  894): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  894): disconnect
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
D/WifiDisplayController(  894): updateConnection
D/WifiDisplayController(  894): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayAdapter(  894): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiP2pService(  894): sending p2p connection changed broadcast: IDLE
,I/wpa_supplicant( 6699): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/Zygote  ( 6818): MountEmulatedStorage()
E/Zygote  ( 6818): v2
I/libpersona( 6818): KNOX_SDCARD checking this for 10192
I/libpersona( 6818): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=6818 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiDisplayController(  894): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiP2pService(  894): create mNetworkAgent
,D/ConnectivityService(  894): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  894): Got NetworkAgent Messenger
D/ConnectivityService(  894): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  894): updateNetworkInfo()
D/ConnectivityService(  894): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  894): NetworkAgent connected
,E/CSLegacyTypeTracker(  894): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,I/SELinux ( 6818): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/AllShareCastTile( 1190): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter(  894): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 1190): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
I/wpa_supplicant( 6699): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/SELinux ( 6818): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6818): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2(  894): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  894): mCursor = null
,D/WifiNative-HAL(  894): p2pGetDeviceAddress
,D/WifiNative-HAL(  894): p2pGetDeviceAddress returning ea:50:8b:de:28:a3
,D/WifiDisplayController(  894): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
D/WifiDisplayController(  894):  deviceAddress: ea:50:8b:de:28:a3
D/WifiDisplayController(  894):  primary type: 10-0050F204-5
D/WifiDisplayController(  894):  secondary type: null
D/WifiDisplayController(  894):  wps: 0
D/WifiDisplayController(  894):  grpcapab: 0
D/WifiDisplayController(  894):  devcapab: 0
D/WifiDisplayController(  894):  status: 3
D/WifiDisplayController(  894):  wfdInfo: null
D/WifiDisplayController(  894):  groupownerAddress: null
D/WifiDisplayController(  894):  GOdeviceName: null
D/WifiDisplayController(  894):  interfaceAddress: 
D/WifiDisplayController(  894):  SConnectInfo : null
D/WifiP2pService(  894): DeviceAddress: ea:28:a3
,D/SecContentProvider2(  894): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  894): mCursor = null
,D/WifiP2pService(  894): sending p2p persistent groups changed broadcast
,D/WifiP2pService(  894): InactiveState
D/WifiP2pService(  894): InactiveState{ what=143376 }
D/WifiP2pService(  894): P2pEnabledState{ what=143376 }
,I/wpa_supplicant( 6699): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,D/WifiP2pService(  894): InactiveState{ what=143376 }
,E/ConnectivityService(  894): updateNetworkInfo()
D/WifiP2pService(  894): P2pEnabledState{ what=143376 }
D/ConnectivityService(  894): ignoring duplicate network state non-change. WIFI_P2P, state = UNKNOWN
,D/TimaKeyStoreProvider( 6818): TimaSignature is unavailable
,D/ActivityThread( 6818): Added TimaKeyStore provider
,D/ResourcesManager( 6818): creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,D/WifiDirectBR( 6818): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,I/ActivityManager(  894): Killing 5811:com.android.defcontainer/u0a7 (adj 15): bgCount ##41
D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1312): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1312): MountReceiver.mPrefHandler - 7002
D/FileShare-Server( 6410): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/WifiDirectBR( 6818): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiDirectBR( 6818): WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,W/ContextImpl( 6818): Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
D/WifiDirectBR( 6818): stopServiceTest : false
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 6699): nl80211: Received scan results (8 BSSes)
,I/wpa_supplicant( 6699): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 6699): Trying to associate with C0.AA.4A (SSID='4E473730303567' freq=5220 MHz)
,I/wpa_supplicant( 6699): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 6699): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E473730303567
,D/SecContentProvider2(  894): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  894): mCursor = null
,I/wpa_supplicant( 6699): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 6699): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E473730303567
,I/wpa_supplicant( 6699): Associated with C0.AA.4A
,D/SecContentProvider2(  894): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  894): mCursor = null
,I/wpa_supplicant( 6699): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 6699): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.4A SSID=4E473730303567
,D/SecContentProvider2(  894): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  894): mCursor = null
,I/wpa_supplicant( 6699): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 6699): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 6699): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.4A SSID=4E473730303567
,I/wpa_supplicant( 6699): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6699): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 6699): CTRL-EVENT-CONNECTED - Connection to C0.AA.4A completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 6699): Blacklist: Clear (temp) 
I/wpa_supplicant( 6699): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.4A SSID=4E473730303567
,D/WifiNative-HAL(  894): callSECApiVoid - ID [50]
,D/StatusBar.NetworkController( 1190): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,D/STATUSBAR-WifiQuickSettingButton( 1190): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService(  894): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  894): Got NetworkAgent Messenger
D/ConnectivityService(  894): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  894): updateNetworkInfo()
,D/ConnectivityService(  894): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  894): NetworkAgent connected
E/WifiConfigStore(  894): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  894): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  284): Setting iface cfg
,E/Zygote  ( 6835): MountEmulatedStorage()
,E/Zygote  ( 6835): v2
I/libpersona( 6835): KNOX_SDCARD checking this for 10038
I/libpersona( 6835): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=6835 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,E/WifiStateMachine(  894): Start Dhcp Watchdog 1
D/SecContentProvider2(  894): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  894): mCursor = null
,D/ConnectivityService(  894): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,D/StatusBar.NetworkController( 1190): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
I/SELinux ( 6835): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/STATUSBAR-WifiQuickSettingButton( 1190): onWifiSignalChanged enabled=true enabledDesc:null
,I/SELinux ( 6835): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6835): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6835): TimaSignature is unavailable
,D/ActivityThread( 6835): Added TimaKeyStore provider
,D/ResourcesManager( 6835): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 6835): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/native  (  894): do suspend false
,D/SecContentProvider2(  894): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService(  894): InactiveState{ what=143375 }
,D/WifiP2pService(  894): P2pEnabledState{ what=143375 }
D/SecContentProvider2(  894): mCursor = null
,I/VlingoApplication( 6835): VlingoApplication appVersion ='11.2.2.0.37649', ro.csc.sales_code=XEO
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 4
,E/BluetoothHeadset( 6835): BTStateChangeCB is registed
,E/BluetoothHeadset( 6835): BluetoothHeadset service is binded
,I/ActivityManager(  894): Killing 5877:com.google.android.partnersetup/u0a19 (adj 15): bgCount ##41
,E/lowmemorykiller(  251): Error writing /proc/5877/oom_score_adj; errno=22
,I/Hs20UtilService( 1312): Starting #2
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
,I/Hs20UtilService( 1312): Message received 5007
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1312): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1312): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6207): NETWORK_STATE_CHANGED_ACTION
,E/dhcpcd  ( 6856): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6856): version 5.5.6 starting
,E/dhcpcd  ( 6856): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/SettingsProvider(  894): name = driving_mode_on
D/SettingsProvider(  894): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  894): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  894): selectionArgs: false
D/SettingsProvider(  894): selectionArgs: 10038
D/SecContentProvider(  894): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  894): ret = -1
,D/BluetoothManager( 6835): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,I/dhcpcd  ( 6856): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6856): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6856): if(wlan0) info get Success. (MAC : C0.AA.4A)
,I/dhcpcd  ( 6856): bssid match
,I/dhcpcd  ( 6856): wlan0: rebinding lease of 192.168.1.128
,I/dhcpcd  ( 6856): wlan0: acknowledged 192.168.1.128 from 192.168.1.1
,I/dhcpcd  ( 6856): wlan0: leased 192.168.1.128 for 86400 seconds
,D/ConnectivityService(  894): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,E/SMD     (  293): DCD ON
,E/native  (  894): do suspend true
,D/WifiP2pService(  894): InactiveState{ what=143375 }
D/WifiP2pService(  894): P2pEnabledState{ what=143375 }
,D/ConnectivityService(  894): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,D/StatusBar.NetworkController( 1190): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1190): onWifiSignalChanged enabled=true enabledDesc:null
,E/WifiStateMachine(  894): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG7005g"WPA_PSK
,E/WifiStateMachine(  894): VerifyingLinkState enter
,D/WifiNative-HAL(  894): callSECApiInt - ID [210]
,E/ConnectivityService(  894): updateNetworkInfo()
,D/ConnectivityService(  894): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService(  894): Adding iface wlan0 to network 502
,D/WifiWatchdogStateMachine(  894): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  894): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver(  894): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1190): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1190): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiWatchdogStateMachine.SingDnsChecker(  894): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  894): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,E/WifiStateMachine(  894): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,I/WifiTrafficPoller(  894): evaluateTrafficStatsPolling
,I/Hs20UtilService( 1312): Starting #3
,I/Hs20UtilService( 1312): Message received 5007
,D/StatusBar.NetworkController( 1190): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1190): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService(  894): Adding Route [fe80::/64 -> :: wlan0] to network 502
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
D/ConnectivityService(  894): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,D/ConnectivityService(  894): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 502
,E/ConnectivityService(  894): Unexpected mtu value: 0, wlan0
E/WifiStateMachine(  894): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller(  894): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  894): mBoosterFLAG : 0
D/ConnectivityService(  894): updateSourceRoutes : add source routing for type : 1
I/WifiTrafficPoller(  894): current booster mode : FullMode
D/WifiNative-HAL(  894): callSECApiVoid - ID [212]
,D/ConnectivityService(  894): updateSourceRoutes : add src route for:192.168.1.128
,V/        (  284): QcRouteController
,D/StatusBar.NetworkController( 1190): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1190): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1190): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1190): applyOpen
,D/StatusBar.NetworkController( 1190): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1190): applyOpen
D/StatusBar.NetworkController( 1190): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1190): applyOpen
D/StatusBar.NetworkController( 1190): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1190): applyOpen
,V/        (  284): QcRouteController
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6207): NETWORK_STATE_CHANGED_ACTION
,V/        (  284): QcRouteController
,V/        (  284): QcRouteController
,I/Hs20UtilService( 1312): Starting #4
,I/Hs20UtilService( 1312): Message received 5007
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1312): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1312): MountReceiver.mPrefHandler - 7002
,V/        (  284): QcRouteController
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6207): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1312): Starting #5
,V/        (  284): QcRouteController
I/Hs20UtilService( 1312): Message received 5007
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1312): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine(  894): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        (  284): QcRouteController
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/        (  284): QcRouteController
,E/SignOutReceiver( 6207): NETWORK_STATE_CHANGED_ACTION
,V/        (  284): QcRouteController
,I/SurfaceFlinger(  254): id=14 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService(  894): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=894
,D/ConnectivityService(  894): Setting Dns servers for network 502 to [/192.168.1.1]
D/ConnectivityService(  894): LTETest block dns file not exists
,V/Nat464Xlat(  894): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  894): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  894): calling update connectivity
,D/ConnectivityService(  894): ignoring duplicate network state non-change. WIFI, state = CONNECTING
E/ConnectivityService(  894): updateNetworkInfo()
D/ConnectivityService(  894): ignoring duplicate network state non-change. WIFI, state = CONNECTING
E/ConnectivityService(  894): updateNetworkInfo()
,D/EntConnectivity(  894): Not allowed due to - mEnabled false
D/ConnectivityService(  894): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  894): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  894): calling update connectivity
D/ConnectivityService(  894): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  894):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  894):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  894):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Checking http://clients3.google.com/generate_204 on "NG7005g"
,I/System.out(  894): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out(  894): (HTTPLog)-Static: isShipBuild true
I/System.out(  894): (HTTPLog)-Thread-182-293489435: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(  894): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService(  894): currentScore = 0, newScore = 60
D/ConnectivityService(  894):    accepting network in place of null
D/ConnectivityService(  894): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  894): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
D/TelephonyNetworkFactory( 1422): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  894): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker(  894): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  894): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  894): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NtpTrustedTime(  894): forceRefresh() from cache miss
V/NetworkStats(  894): updateIfacesLocked()
V/NetworkStats(  894): performPollLocked(flags=0x1)
D/NetworkStatsFactory(  894): UpdateStatsForKnox
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  894): MasterInitialState.processMessage what=3
D/SmartBondingService(  894): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  894): getSBEnabled() enabled =false
D/SmartBondingService(  894): getSBEnabled() enabled =false
D/SmartBondingService(  894): getSBEnabled() enabled =false
,D/SmartBondingService(  894): getNetworkEnabled : wifi : true mobile : true
,D/NtpTrustedTime(  894): forceRefresh Fail.
,V/NetworkStats(  894): performPollLocked() took 4ms
,D/NtpTrustedTime(  894): forceRefresh() from cache miss
D/EntConnectivity(  894): Not allowed due to - mEnabled false
,D/NtpTrustedTime(  894): forceRefresh Fail.
D/ConnectivityService(  894): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
V/NetworkStats(  894): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/ConnectivityService(  894): calling update connectivity
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  894): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1190): CM callback handler got msg 524290
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1190): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1190): updateDataNetType()
D/StatusBar.NetworkController( 1190): NoService, mRoamingIconId = 0
,E/StatusBar.NetworkController( 1190): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1190): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1190): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1190): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1190): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1190): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1190): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1190): applyOpen
D/StatusBar.NetworkController( 1190): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1190): applyOpen
,D/StatusBar.NetworkController( 1190): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1190): applyOpen
D/StatusBar.NetworkController( 1190): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1190): applyOpen
,I/System.out(  894): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 11:18:17 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449746296793], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449746296776]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Validated
D/ConnectivityService(  894): Validated NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  894): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  894):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  894):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  894): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService(  894): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  894): calling update connectivity
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  894): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1190): CM callback handler got msg 524290
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1190): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1190): updateDataNetType()
D/StatusBar.NetworkController( 1190): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1190): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1190): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1190): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1190): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1190): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1190): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  894): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  894): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  894): SmartBondingReceiver: wifi ap is changed, init speed ratio
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5104): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  894): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  894): getSBEnabled() enabled =false
D/SmartBondingService(  894): getSBEnabled() enabled =false
,D/SmartBondingService(  894): getSBEnabled() enabled =false
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  894): forceRefresh() from cache miss
,D/NtpTrustedTime(  894): forceRefresh Fail.
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  894): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1882): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
I/DBG_DM  ( 3174): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
W/ContextImpl( 1882): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
I/PCWCLIENTTRACE_PushUtil( 5916): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5916): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5916): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5916): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/DBG_DM  ( 3174): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 3174): [com.wssyncmldm.llllIIIllIlIIIIllllI(263/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_DM  ( 3174): [llIlIIIIlllIlllllIll(224/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,I/DBG_DM  ( 3174): [IIllIIllIIIlllIlIIll(403/llllllIllIlIlllIIlIl)] Check completed.
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3174): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3174): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 3174): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 3174): [IIIlllIlIIlllIIIIllI(73/llllIIIllIlIIIIllllI)] 
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3174): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3174): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 8
,E/Zygote  ( 6917): MountEmulatedStorage()
E/Zygote  ( 6917): v2
I/libpersona( 6917): KNOX_SDCARD checking this for 10004
I/libpersona( 6917): KNOX_SDCARD not a persona
,I/DBG_DM  ( 3174): [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 2
,I/DBG_DM  ( 3174): [IIllIIllIIIlllIlIIll(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,I/ActivityManager(  894): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6917 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_DM  ( 3174): [IIllIIllIIIlllIlIIll(177/lllIlIlIIIllIIlIllIl)] nDownloadPostpone is [8]
,I/SELinux ( 6917): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6917): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6917): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3174): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 0
,I/DBG_DM  ( 3174): [IIllIlIIlIlllIIllIII(741/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,I/DBG_DM  ( 3174): [com.wssyncmldm.IIIIllIlIIlIIIIlllIl(1273/handleMessage)] event ->220
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/TimaKeyStoreProvider( 6917): TimaSignature is unavailable
,D/ActivityThread( 6917): Added TimaKeyStore provider
,I/DBG_DM  ( 3174): [llIlIIIIlllIlllllIll(280/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 3174): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/GoogleURLConnFactory( 1481): Using platform SSLCertificateSocketFactory
,I/DBG_DM  ( 3174): [llIlIIIIlllIlllllIll(1907/lllIlIlIIIllIIlIllIl)] 
,I/DBG_DM  ( 3174): [com.wssyncmldm.XDMBroadcastReceiver(332/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 3174): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(501/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,D/ResourcesManager( 6917): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/DBG_DM  ( 3174): [com.wssyncmldm.XDMService(876/IIIIllIlIIlIIIIlllIl)] 
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3174): [com.wssyncmldm.db.file.XDB(4994/IIIlllIlIIlllIIIIllI)] Get Autoinstall status : false
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
I/DBG_DM  ( 3174): [IIllIlIIlIlllIIllIII(695/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3174): [com.wssyncmldm.XDMService(638/llllIIIllIlIIIIllllI)] 
,E/DBG_DM  ( 3174): [com.wssyncmldm.XDMService(646/llllIIIllIlIIIIllllI)] didn't register
,E/DBG_DM  ( 3174): [com.wssyncmldm.XDMService(647/llllIIIllIlIIIIllllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@1af01593
,E/Zygote  ( 6939): MountEmulatedStorage()
E/Zygote  ( 6939): v2
I/libpersona( 6939): KNOX_SDCARD checking this for 10104
I/libpersona( 6939): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=6939 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6939): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,E/Watchdog(  894): !@Sync 5
I/SELinux ( 6939): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 6939): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3174): [com.wssyncmldm.XDMService(819/IllIlIIIIlIIlIIIllIl)] Idle Screen : false
,D/GpsLocationProvider(  894): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3174): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/TimaKeyStoreProvider( 6939): TimaSignature is unavailable
,D/ActivityThread( 6939): Added TimaKeyStore provider
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 6939): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3174): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,E/Zygote  ( 6964): MountEmulatedStorage()
E/Zygote  ( 6964): v2
I/libpersona( 6964): KNOX_SDCARD checking this for 1000
I/libpersona( 6964): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6964 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/ActivityThread( 1749): Failed to find provider info for com.android.contacts.metadata
,I/PhenotypeConfigurator( 1481): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,I/art     (  320): Explicit concurrent mark sweep GC freed 8781(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 306us total 14.946ms
,I/SELinux ( 6964): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/SecContentProvider2(  894): uri = 14 selection = getSealedState
D/SecContentProvider2(  894): mCursor = null
,I/SELinux ( 6964): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6964): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 4.297ms total 13.633ms
,V/GLSActivity( 1481): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 280us total 14.822ms
,D/ApplicationPolicy(  894): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  894): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager(  894): showStatusBarByNotification() mOpenByNotification=false
,D/ResourcesManager( 1190): creating new AssetManager and set to /system/priv-app/SyncmlDM/SyncmlDM.apk
,V/GLSActivity( 1481): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/GpsLocationProvider(  894): No APN found to select.
,D/TimaKeyStoreProvider( 6964): TimaSignature is unavailable
,V/GLSActivity( 1481): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ActivityThread( 6964): Added TimaKeyStore provider
,I/DBG_DM  ( 3174): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
,D/ResourcesManager( 6964): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3174): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/SyncManager(  894): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 18739, reason: UserStart, SyncResult: databaseError: true stats []
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  894): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 198148, reason: UserStart
,D/KnoxNotification( 1190): ----- inflateViews : modified publicViewLocal -----
,I/DBG_DM  ( 3174): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 3174): [com.wssyncmldm.ui.XUIFotaPostponeActivity(378/lllIlIlIIIllIIlIllIl)] No idle Postpone
,I/DBG_DM  ( 3174): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
,D/KnoxNotification( 1190): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1190): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 1190): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@2091d71a
D/PersonaManager( 1190): isKioskContainerExistOnDevice
D/PersonaManager( 1190): isKioskContainerExistOnDevice
,D/PanelView( 1190): There is/are notification(s) 
,D/PanelView( 1190): There is/are notification(s) 
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DIAGMON_AGENT( 6964): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  894): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  894): mCursor = null
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  894): Killing 5895:com.samsung.groupcast/u0a20 (adj 13): bgCount ##41
,I/System.out( 1481): (HTTPLog)-Static: isSBSettingEnabled false
,I/DIAGMON_AGENT( 6964): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,E/Auth.Api.Credentials( 1749): [CredentialSyncAdapter] Unknown sync event.
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DelayedSyncController( 6939): Delaying sync.
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1481): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1481): Tagging socket 66 with tag 1000040100000000{268436481,0} uid 10015, pid: 1481, getuid(): 10015
,I/qtaguid ( 1481): Tagging socket 70 with tag 1000040100000000{268436481,0} uid 10015, pid: 1481, getuid(): 10015
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1481): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  894): Killing 4116:com.sec.android.app.shealth/u0a40 (adj 15): bgCount ##41
,I/System.out( 1481): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1481): Tagging socket 72 with tag 1000120300000000{268440067,0} uid -1, pid: 1481, getuid(): 10015
,I/DIAGMON_AGENT( 6964): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6964): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DIAGMON_AGENT( 6964): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6964): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6989): MountEmulatedStorage()
E/Zygote  ( 6989): v2
I/libpersona( 6989): KNOX_SDCARD checking this for 10014
I/libpersona( 6989): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=6989 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/qtaguid ( 1481): Tagging socket 75 with tag 1000120300000000{268440067,0} uid -1, pid: 1481, getuid(): 10015
,I/SELinux ( 6989): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6989): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 6989): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  894): apparently satisfied.  currentScore=60
,D/ConnectivityService(  894): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,D/ConnectivityManager.CallbackHandler( 1749): CM callback handler got msg 524290
,D/TimaKeyStoreProvider( 6989): TimaSignature is unavailable
,D/ActivityThread( 6989): Added TimaKeyStore provider
,D/DelayedSyncController( 6939): Delaying sync.
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 6989): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PicasaService( 5196): start picasa sync
,D/PicasaService( 5196): end picasa sync
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FOTA_Client( 6989): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 6989): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 6989): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7009): MountEmulatedStorage()
E/Zygote  ( 7009): v2
I/libpersona( 7009): KNOX_SDCARD checking this for 10023
I/libpersona( 7009): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7009 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7009): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7009): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7009): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  894): Killing 5950:com.policydm/1000 (adj 15): bgCount ##41
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7009): TimaSignature is unavailable
,D/ActivityThread( 7009): Added TimaKeyStore provider
,D/ResourcesManager( 7009): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.511: ( 7009): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/dex2oat ( 7012): ----------------------------------------------------
I/dex2oat ( 7012): <SS>: S T A R T I N G . . .
I/dex2oat ( 7012): <SS>: Zip is absent. Canceled.
I/dex2oat ( 7012): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xnorelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/cache/ads1888542373.jar --oat-fd=106 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/cache/ads1888542373.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/KLMS-2.4.511: ( 7009): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449746298422
,I/KLMS-2.4.511: ( 7009): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 7009): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.511: ( 7009): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.511: ( 7009): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.511: ( 7009): StateImplV2(): networkChangeListener().END
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,I/dex2oat ( 7012): dex2oat took 49.470ms (threads: 4)
,E/Zygote  ( 7035): MountEmulatedStorage()
,E/Zygote  ( 7035): v2
I/libpersona( 7035): KNOX_SDCARD checking this for 10036
I/libpersona( 7035): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7035 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 7035): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7035): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7035): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7035): TimaSignature is unavailable
,D/ActivityThread( 7035): Added TimaKeyStore provider
,W/PhenotypeConfigurator( 1481): Server returned 404
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7035): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,W/ResourcesManager( 7035): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7035): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  894): Killing 4667:com.sec.spp.push/u0a43 (adj 15): bgCount ##41
,E/Minikin ( 7035): addFont failed to create font /system/fonts/SamsungSans-light.ttf
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  894): Killing 5970:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): bgCount ##41
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7053): MountEmulatedStorage()
I/libpersona( 7053): KNOX_SDCARD checking this for 10042
E/Zygote  ( 7053): v2
I/libpersona( 7053): KNOX_SDCARD not a persona
,D/PackageManager(  894): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/ActivityManager(  894): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7053 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7053): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7053): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7053): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7053): TimaSignature is unavailable
,D/ActivityThread( 7053): Added TimaKeyStore provider
,W/DriveInitializer( 1749): Awaiting to be initialized
,W/DriveInitializer( 1749): Background init thread started
,D/ResourcesManager( 7053): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 1749): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SO_AGENT( 7053): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1481): Vacuum at: now=1449746298916 tag=VacuumService
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/DriveInitializer( 1749): Background init thread ended
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7089): MountEmulatedStorage()
E/Zygote  ( 7089): v2
I/libpersona( 7089): KNOX_SDCARD checking this for 1000
I/libpersona( 7089): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=7089 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7089): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7089): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7089): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7089): TimaSignature is unavailable
,D/ActivityThread( 7089): Added TimaKeyStore provider
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7089): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  894): Killing 6012:com.osp.app.signin/u0a50 (adj 15): bgCount ##41
,I/ActivityManager(  894): Killing 6076:com.sec.android.app.soundalive/u0a64 (adj 15): bgCount ##41
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  293): DCD ON
,D/ConnectivityService(  894): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=true
D/ConnectivityService(  894): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService(  894): identical MTU - not setting
D/ConnectivityService(  894): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  894): updateSourceRoutes : add src route for:fe80::ea50:8bff:fede:28a3
V/        (  284): QcRouteController
,V/        (  284): QcRouteController
,D/SmartBondingService(  894): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  894): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  894): getSBEnabled() enabled =false
D/SmartBondingService(  894): getSBEnabled() enabled =false
D/SmartBondingService(  894): getSBEnabled() enabled =false
W/NetworkManagementService(  894): route cmd failed: 
W/NetworkManagementService(  894): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '54 route replace src v6 wlan0 fe80::ea50:8bff:fede:28a3 2 ::' failed with '400 54 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  894): '
W/NetworkManagementService(  894): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService(  894): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService(  894): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService(  894): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService(  894): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  894): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5625)
W/NetworkManagementService(  894): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5437)
W/NetworkManagementService(  894): 	at com.android.server.ConnectivityService.access$2300(ConnectivityService.java:229)
W/NetworkManagementService(  894): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2382)
W/NetworkManagementService(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  894): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/Nat464Xlat(  894): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  894): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  894): calling update connectivity
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  894): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1190): CM callback handler got msg 524295
D/ConnectivityService(  894): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityManager.CallbackHandler( 1749): CM callback handler got msg 524295
D/ConnectivityService(  894): calling update connectivity
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  894): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1190): CM callback handler got msg 524295
D/ConnectivityService(  894): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1749): CM callback handler got msg 524295
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/bt-btif ( 6693): ...preload_wait_timeout (retried:0/max-retry:1)...
D/bt_userial( 6693): RX termination
W/bt_userial( 6693): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 6693): Leaving userial_read_thread()
D/bt_vendor( 6693): op for 4
I/bt_userial_vendor( 6693): device fd = 65 close
,E/Zygote  ( 7115): MountEmulatedStorage()
E/Zygote  ( 7115): v2
I/libpersona( 7115): KNOX_SDCARD checking this for 10043
I/libpersona( 7115): KNOX_SDCARD not a persona
I/ActivityManager(  894): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7115 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  894): Killing 4961:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
E/lowmemorykiller(  251): Error writing /proc/4961/oom_score_adj; errno=22
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SELinux ( 7115): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7115): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7115): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7115): TimaSignature is unavailable
,D/ActivityThread( 7115): Added TimaKeyStore provider
,D/bt_vendor( 6693): op for 0
,D/bt_upio ( 6693): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 6693): is_emulator_context : 0
D/bt_upio ( 6693): is_rfkill_disabled ? [0]
,D/bt_vendor( 6693): cleanup
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7115): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  894): Explicit concurrent mark sweep GC freed 109129(5MB) AllocSpace objects, 9(144KB) LOS objects, 17% free, 37MB/45MB, paused 1.536ms total 112.295ms
,E/SPPClientService( 7115): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 7115): [PushClientApplication] Push log off : This is Ship build version
,I/bt_hci_bdroid( 6693): init
,I/bt_vendor( 6693): init
I/bt_vnd_conf( 6693): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 6693): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 6693): userial_init
D/bt_vendor( 6693): op for 5
,D/bt_vendor( 6693): op for 0
D/bt_upio ( 6693): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 6693): is_emulator_context : 0
D/bt_upio ( 6693): is_rfkill_disabled ? [0]
D/bt_upio ( 6693): is_rfkill_disabled ? [0]
,D/bt_vendor( 6693): op for 0
D/bt_upio ( 6693): upio_set_bluetooth_power(on: 1)
D/bt_upio ( 6693): is_emulator_context : 0
D/bt_upio ( 6693): is_rfkill_disabled ? [0]
,D/SPPClientService( 7115): PushLog.txt file is not deleted.
D/SPPClientService( 7115): PushLog.txt file is not deleted.
D/SPPClientService( 7115): ============PushLog. stop!
D/bt_vendor( 6693): op for 3
,I/bt_userial_vendor( 6693): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 6693): userial_vendor_open():UART is setup
I/bt_userial_vendor( 6693): device fd = 65 open
,D/bt_vendor( 6693): op for 1
E/bt_hwcfg( 6693): Start CFG HW, HCI reset
,D/bt_userial( 6693): Entering userial_read_thread()
,I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1749): (HTTPLog)-Static: isShipBuild true
I/System.out( 1749): (HTTPLog)-Thread-238-42513102: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
,E/SPPClientService( 7115): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7136): MountEmulatedStorage()
E/Zygote  ( 7136): v2
I/libpersona( 7136): KNOX_SDCARD checking this for 10050
I/libpersona( 7136): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7136 uid=10050 gids={50050, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 6115:com.wsomacp/u0a29 (adj 15): bgCount ##41
,I/System.out( 1749): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1749): Tagging socket 106 with tag 1000010400000000{268435716,0} uid -1, pid: 1749, getuid(): 10015
,E/bt_hwcfg( 6693): Read Local Name after HCI reset
,I/SELinux ( 7136): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7136): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7136): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7136): TimaSignature is unavailable
,D/ActivityThread( 7136): Added TimaKeyStore provider
,D/bt_hwcfg( 6693): Chipset BCM4335C0
D/bt_hwcfg( 6693): Target name = [BCM4335C0]
,I/bt_hwcfg( 6693): module_type[semco].
I/bt_hwcfg( 6693): not ZERO...
I/bt_hwcfg( 6693): module_type[semco] is invalid.
E/bt_hwcfg( 6693): patchram path ORG . BCM4335C0
E/bt_hwcfg( 6693): patchram path ORG .. BCM4335C0
E/bt_hwcfg( 6693): patchram path ORG bcm2079xB4_firmware.ncd BCM4335C0
E/bt_hwcfg( 6693): patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335C0
E/bt_hwcfg( 6693): patchram path ORG bcm2079xB5_firmware.ncd BCM4335C0
E/bt_hwcfg( 6693): patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335C0
E/bt_hwcfg( 6693): patchram path ORG bcm4335_V0093.0399.hcd BCM4335C0
E/bt_hwcfg( 6693): patchram path ORG bcm4335_V0093.0399_wisol.hcd BCM4335C0
E/bt_hwcfg( 6693): fw ver (org)0.0
E/bt_hwcfg( 6693): vendor lib preload failed to locate firmware patch file
E/bt_hwcfg( 6693): Remove module rev, try again BCM4335
D/bt_hwcfg( 6693): Target name = [BCM4335]
I/bt_hwcfg( 6693): module_type[semco].
I/bt_hwcfg( 6693): not ZERO...
I/bt_hwcfg( 6693): module_type[semco] is invalid.
E/bt_hwcfg( 6693): patchram path ORG . BCM4335
E/bt_hwcfg( 6693): patchram path ORG .. BCM4335
E/bt_hwcfg( 6693): patchram path ORG bcm2079xB4_firmware.ncd BCM4335
E/bt_hwcfg( 6693): patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335
E/bt_hwcfg( 6693): patchram path ORG bcm2079xB5_firmware.ncd BCM4335
E/bt_hwcfg( 6693): patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335
E/bt_hwcfg( 6693): patchram path ORG bcm4335_V0093.0399.hcd BCM4335
I/bt_hwcfg( 6693): patch(org) : bcm4335_V0093.0399.hcd
I/bt_hwcfg( 6693): Found patchfile: /vendor/firmware/bcm4335_V0093.0399.hcd
E/bt_hwcfg( 6693): ORG patchram base 0093
E/bt_hwcfg( 6693): ORG patchram minor 0399
E/bt_hwcfg( 6693): fw ver (org)93.399
E/bt_hwcfg( 6693): Final Patchram is /vendor/firmware/bcm4335_V0093.0399.hcd
,I/bt_hwcfg( 6693): Axi patch failure or not include AXI patching
,I/bt_hwcfg( 6693): bt vendor lib: set UART baud 3000000
,D/ResourcesManager( 7136): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,I/SA      ( 7136): [SSP] onCreated
,I/SA      ( 7136): [TPM] There is no property file
,I/SA      ( 7136): [SCU] isHaveSA() - false
,I/SA      ( 7136): [TPM] getModelProperty : null
I/SA      ( 7136): [TPM] getCSCProperty : null
,I/SA      ( 7136): [DM] init START
,I/SA      ( 7136): [DM] This device is not a Vodafone
,I/SA      ( 7136): checkReactivationActive for LOLLIPOP
,I/SA      ( 7136): checkReactivationActive for reactiveActive
I/SA      ( 7136): setSupportRL : true
,I/SA      ( 7136): [SCU] isHaveSA() - false
I/SA      ( 7136): support phone number id : false
,I/SA      ( 7136): [DM] init END
,I/SA      ( 7136): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 7136): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 7136): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7136): [SLFUCHKMGR] constructor called
,I/SA      ( 7136): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7136): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7136): [SCU] == networkStateCheck == true
I/SA      ( 7136): [DM] getCountryCodeFromCSC : PL
I/SA      ( 7136): isChinaCountryCode : false
I/SA      ( 7136): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7136): [OR] == networkStateCheck true ==
,I/SA      ( 7136): [OR] GetMyCountryZoneTask
,I/SA      ( 7136): [OR] onReceive END
,I/ActivityManager(  894): Killing 6095:com.google.android.apps.docs/u0a112 (adj 15): bgCount ##41
,I/SA      ( 7136): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,I/SA      ( 7136): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7136): [SSP] query invoked
,I/qtaguid ( 1749): Untagging socket 106
,E/Zygote  ( 7159): MountEmulatedStorage()
I/libpersona( 7159): KNOX_SDCARD checking this for 10074
E/Zygote  ( 7159): v2
I/libpersona( 7159): KNOX_SDCARD not a persona
,I/SA      ( 7136): [TPMU] GetMccFromDB : null
I/SA      ( 7136): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 7136): [TPM] isNoProxy(default) : true
,I/ActivityManager(  894): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7159 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/File    ( 7136): fail readDirectory() errno=2
,I/SELinux ( 7159): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7159): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7159): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7159): TimaSignature is unavailable
,D/ActivityThread( 7159): Added TimaKeyStore provider
,D/ResourcesManager( 7159): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  894): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/sCloudBackupApp( 7159): sCloudBackupApp Version Info : 3.13.7.KK_APP
I/SCloudBackupReceiver( 7159): Other Intent
,I/KnoxUsageLogPro( 6425): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 6425): premStatus:2
,I/KnoxUsageLogPro( 6425): isEulaShown : false
I/KnoxUsageLogPro( 6425): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,I/jxcore-log( 6587): Test app app.js loaded
I/jxcore-log( 6587): 
,E/Zygote  ( 7176): MountEmulatedStorage()
E/Zygote  ( 7176): v2
I/libpersona( 7176): KNOX_SDCARD checking this for 10146
I/libpersona( 7176): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7176 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/chromium( 6587): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/SELinux ( 7176): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7176): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7176): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  894): Killing 6143:com.samsung.android.app.filterinstaller/1000 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7176): TimaSignature is unavailable
,D/ActivityThread( 7176): Added TimaKeyStore provider
,I/dhcpcd  ( 6856): wlan0: sending IPv6 Router Solicitation
,I/chromium( 6587): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/ResourcesManager( 7176): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/bt_hwcfg( 6693): bt vendor lib: set UART baud 115200
,I/bt_hwcfg( 6693): FW Download delta = 523381
D/bt_hwcfg( 6693): Settlement delay -- 100 ms
I/bt_hwcfg( 6693): Setting fw settlement delay to 100 
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7176): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7176): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7176): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7176): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/SurfaceFlinger(  254): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  254): id=14 Removed Uoast (-2/9)
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PowerManagerService(  894): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 894) eventTime = 168340
,D/PowerManagerService(  894): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=894 (0x0)
D/PowerManagerService(  894): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=894, ws=WorkSource{10067}) (elapsedTime=3472)
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/OpenGLRenderer( 3174): Render dirty regions requested: true
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Atlas   ( 3174): Validating map...
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/bt_hwcfg( 6693): bt vendor lib: set UART baud 3000000
,I/SurfaceFlinger(  254): id=15 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService(  894): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=894
,I/bt_hwcfg( 6693): vendor lib fwcfg completed
,I/Adreno-EGL( 3174): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 3174): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 3174): Build Date: 11/19/14 Wed
I/Adreno-EGL( 3174): Local Branch: mybranch5813579
I/Adreno-EGL( 3174): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 3174): Local Patches: NONE
I/Adreno-EGL( 3174): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,I/OpenGLRenderer( 3174): Initialized EGL, version 1.4
,I/        ( 6693): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6693): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6693): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6693): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6693): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6693): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6693): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6693): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6693): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6693): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6693): BTE_InitTraceLevels -- TRC_SAP
I/        ( 6693): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6693): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6693): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6693): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6693): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 6693): BTE_InitTraceLevels -- TRC_PROTOCOL
,I/PhenotypeConfigurator( 1481): Scheduling Phenotype for one-off execution 12856 seconds from now (1449746300197)
,I/OpenGLRenderer( 3174): HWUI protection enabled for context ,  &this =0xa1c22088 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 3174): Enabling debug mode 0
,D/GetConfigurationSnapshotOperation( 1481): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1481): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1481): Using platform SSLCertificateSocketFactory
,I/WebViewFactory( 7176): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 7176): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7176): Loading: webviewchromium
,I/LibraryLoader( 7176): Time to load native libraries: 4 ms (timestamps 8516-8520)
,I/LibraryLoader( 7176): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7176): Binding Chromium to main looper Looper (main, tid 1) {11143370}
,I/LibraryLoader( 7176): Expected native library version number "",actual native library version number ""
,I/chromium( 7176): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7176): Initializing chromium process, renderers=0
,W/art     ( 7176): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7176): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7176): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46780 len=2953
I/chromium( 7176): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229536 len:643667
,W/AudioManagerAndroid( 7176): Requires BLUETOOTH permission
,I/Adreno-EGL( 7176): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7176): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7176): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7176): Local Branch: mybranch5813579
I/Adreno-EGL( 7176): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7176): Local Patches: NONE
I/Adreno-EGL( 7176): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,I/SA      ( 7136): [RC New] Execute method=[GET] start
,D/LocationManagerService(  894): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,W/bt-l2cap( 6693): l2c_link_processs_ble_num_bufs 15
,E/bt-btm  ( 6693): BTM_SecRegister:p_cb_info->p_le_callback == 0xafc50b05 
E/bt-btm  ( 6693): BTM_SecRegister: btm_cb.api.p_le_callback = 0xafc50b05 
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NSApplication( 7176): Starting up...
,I/System.out( 1481): (HTTPLog)-Static: isSBSettingEnabled false
,I/SA      ( 7136): [RC New] Security=[true]
,I/System.out( 7136): Thread-1146(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 7136): Thread-1146(ApacheHTTPLog):isShipBuild true
,I/System.out( 7136): Thread-1146(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,I/System.out( 1481): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1481): Tagging socket 83 with tag 1000120100000000{268440065,0} uid -1, pid: 1481, getuid(): 10015
,I/qtaguid ( 1481): Tagging socket 86 with tag 1000120100000000{268440065,0} uid -1, pid: 1481, getuid(): 10015
,E/Zygote  ( 7239): MountEmulatedStorage()
,E/Zygote  ( 7239): v2
I/libpersona( 7239): KNOX_SDCARD checking this for 10158
I/libpersona( 7239): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7239 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  894): Killing 6172:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): bgCount ##41
,I/SELinux ( 7239): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7239): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7239): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7239): TimaSignature is unavailable
,D/ActivityThread( 7239): Added TimaKeyStore provider
,D/ResourcesManager( 7239): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7239): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7239): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7239): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7239): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7239): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7239): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  894): exchangeData() failure , invalid userId
,D/RCPManagerService(  894): exchangeData() failure , invalid userId
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6665): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6665): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6665): StateMachine : Current State = 1
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 6665): StateMachine : Changed Current State = 1
,I/ActivityManager(  894): Killing 6187:com.samsung.helphub/1000 (adj 15): bgCount ##41
,D/BluetoothAdapterProperties( 6693): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 0 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = false
,E/bt-btif ( 6693): Calling BTA_HhEnable
E/bt-btif ( 6693): btif_storage_get_adapter_property service_mask:0x2120048
,D/BluetoothAdapterProperties( 6693): Address is:E0:DB:10:1F:C9:5E
E/BluetoothServiceJni( 6693): populateRssiValuesNative
I/bluedroid( 6693): getModelRssiValues
E/BluetoothServiceJni( 6693): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 6693): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/BluetoothAdapterProperties( 6693): Name is: Note3-1
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SettingsProvider(  894): name = bluetooth_name
,D/BluetoothAdapterProperties( 6693): Scan Mode:20
D/BluetoothAdapterProperties( 6693): Discoverable Timeout:120
,D/BluetoothAdapterProperties( 6693): LE Address is:E0:B7:20:3E:93:BC
E/bt-btif ( 6693): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 6693): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,E/bt-btif ( 6693): btif_sock_init: !radio_req && !rfc_init
D/bt_vendor( 6693): op for 2
D/bt_vendor( 6693): op for 6
E/bt-btif ( 6693): btif_sock_init: !vhci_init
D/IOP_DB_BT( 6693): db_open: file /etc/bluetooth/iop_bt.db
,D/bt_vendor( 6693): op for 7
,D/bt_upio ( 6693): proc btwrite assertion
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
D/IOP_DB_BT( 6693): db_open: db_open : handle 3026161680l, read 14063 bytes onto local cache
D/IOP_DB_BT( 6693): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 6693): db_query: result 1
I/        ( 6693): iop_db_open: iop_db_open status 0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,D/bt_vendor( 6693): op for 7
D/bt_upio ( 6693): BT_WAKE is asserted already
D/bte_conf( 6693): Device ID record 1 : primary
D/bte_conf( 6693):   vendorId            = 0075
D/bte_conf( 6693):   vendorIdSource      = 0001
D/bte_conf( 6693):   product             = 0100
D/bte_conf( 6693):   version             = 0200
D/bte_conf( 6693):   clientExecutableURL = 
D/bte_conf( 6693):   serviceDescription  = 
D/bte_conf( 6693):   documentationURL    = 
D/bte_conf( 6693): bte_load_did_conf no section named DID2.
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
D/BluetoothPanServiceJni( 6693): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 6693): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6693): ScanMode =  20
D/BluetoothAdapterProperties( 6693): State =  11
D/bt_vendor( 6693): op for 7
D/bt_upio ( 6693): BT_WAKE is asserted already
D/SecContentProvider(  894): uri = 3 selection = isDiscoverableEnabled
,D/BluetoothAdapterProperties( 6693): Setting state to 12
I/BluetoothAdapterState( 6693): Bluetooth adapter state changed: 11-> 12
,D/bt_vendor( 6693): op for 7
,D/bt_upio ( 6693): BT_WAKE is asserted already
E/bt_h4   ( 6693): vendor lib postload completed
,D/bt_vendor( 6693): op for 7
D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
,D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
,D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
,D/bt_upio ( 6693): BT_WAKE is asserted already
,E/Zygote  ( 7257): MountEmulatedStorage()
E/Zygote  ( 7257): v2
I/libpersona( 7257): KNOX_SDCARD checking this for 10200
I/libpersona( 7257): KNOX_SDCARD not a persona
,D/bt_vendor( 6693): op for 7
D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
,D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
,D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
D/bt_upio ( 6693): BT_WAKE is asserted already
,I/SELinux ( 7257): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7257): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,I/ActivityManager(  894): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7257 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 7257): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/bt_vendor( 6693): op for 7
,D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
,D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
,D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
,D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
I/art     (  320): Explicit concurrent mark sweep GC freed 8731(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 308us total 14.423ms
D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
D/bt_upio ( 6693): BT_WAKE is asserted already
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 270us total 11.317ms
,I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 281us total 9.739ms
,D/BluetoothAdapterProperties( 6693): Scan Mode:21
,D/BluetoothAdapterProperties( 6693): Discoverable Timeout:120
D/SettingsProvider(  894): name = bluetooth_a2dp_sink_mode
D/SettingsProvider(  894): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  894): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  894): selectionArgs: false
D/SettingsProvider(  894): selectionArgs: 1002
D/SecContentProvider(  894): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  894): ret = -1
,D/TimaKeyStoreProvider( 7257): TimaSignature is unavailable
,D/ActivityThread( 7257): Added TimaKeyStore provider
,W/BackupManagerService(  894): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService( 6693): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 6693): updateAdapterState state is 12
,D/BluetoothAdapterService( 6693): Autoconnection is available 
D/BluetoothAdapterService( 6693): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 6693): starting service from this receiver
,D/BluetoothA2dp( 2930): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 6693): onBluetoothStateChange: up=true
D/BluetoothA2dp(  894): onBluetoothStateChange: up=true
,I/BluetoothAdapterState( 6693): Entering On State from state = 11
,W/InputMethodManagerService(  894): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothTile( 1190):  onBluetoothStateChange:
,I/InputMethodManagerService(  894): [BT Setting State] State =12
I/InputMethodManagerService(  894): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothTile( 1190):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1190): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothHeadset( 1399): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@11370088, true
D/BluetoothHeadset( 1399): registerMessageListener
,D/BluetoothManager( 6835): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,I/SamsungIME( 1729): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,I/BluetoothPbapService( 6693): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,D/StatusBarManagerService(  894): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
,D/HeadsetService( 6693): registerMessageListener
,D/StatusBarManagerService(  894): setIconVisibility slot=bluetooth visible=true
D/HeadsetService( 6693): registerMessageListener
D/PhoneStatusBar( 1190): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
D/HeadsetStateMachine( 6693): Disconnected process message: 70
I/Telecom ( 1399): BluetoothPhoneService: updateHeadsetWithCallState
D/HeadsetStateMachine( 6693): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@20655ecc
,I/Telecom ( 1399): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
D/BluetoothTile( 1190):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 1190): onStateChanged: Bluetooth
,D/HeadsetStateMachine( 6693): Disconnected process message: 9
,D/HeadsetStateMachine( 6693): mNumActive: 0 mNumHeld: 0 mCallState: 6
,D/audio_hw_primary(  298): adev_set_parameters: enter: A2dpSuspended=false
V/voice   (  298): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  298): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  298): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  298): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  298): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  298): adev_set_parameters: exit
,I/BluetoothPbapService( 6693): Handler(): got msg=1
E/HeadsetStateMachine( 6693): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/BluetoothManagerService(  894): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/SecContentProvider(  894): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,V/BluetoothPbapService( 6693): PBAP Service initSocket try: 0
,D/ResourcesManager( 7257): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,W/BluetoothAdapter( 6693): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6693): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
D/BluetoothSocket( 6693): bindListen(), new LocalSocket 
D/BluetoothSocket( 6693): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6693): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22a060f7
D/BluetoothSocket( 6693): channel: 19
D/BluetoothPbapService( 6693): PBAP Socket is BluetoothServerSocket
D/bt_vendor( 6693): op for 7
D/bt_upio ( 6693): BT_WAKE is asserted already
,D/LocationManagerService(  894): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/BluetoothMapMasInstance( 6693): set MAP SDP message type : 1
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/BluetoothAdapter( 6693): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6693): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 6693): bindListen(), new LocalSocket 
D/BluetoothSocket( 6693): bindListen(), new LocalSocket.getInputStream() 
D/bt_vendor( 6693): op for 7
D/BluetoothSocket( 6693): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11debb64
D/bt_upio ( 6693): BT_WAKE is asserted already
D/BluetoothSocket( 6693): channel: 5
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1481): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1481): Tagging socket 83 with tag 1000120100000000{268440065,0} uid -1, pid: 1481, getuid(): 10015
,I/ActivityManager(  894): Killing 6227:com.samsung.android.snote:provider/u0a168 (adj 15): bgCount ##41
,I/iu.SyncManager( 1749): SYNC; picasa accounts
,D/LocationManagerService(  894): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/NetworkLogImpl( 1749): Loaded NetworkSpeedPredictor
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/iu.Environment( 1749): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/iu.UploadsManager( 1749): num queued entries: 0
,I/iu.UploadsManager( 1749): num updated entries: 0
I/iu.SyncManager( 1749): NEXT; no task
I/System.out( 1481): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1481): Tagging socket 83 with tag 1000120100000000{268440065,0} uid -1, pid: 1481, getuid(): 10015
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 6269): notifyNetworkActivated
,W/ContextImpl( 6269): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  894): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/LocationManagerService(  894): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1481): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1481): Tagging socket 83 with tag 1000120100000000{268440065,0} uid -1, pid: 1481, getuid(): 10015
,D/LocationManagerService(  894): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1481): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1481): Tagging socket 83 with tag 1000120100000000{268440065,0} uid -1, pid: 1481, getuid(): 10015
,D/hcjo    ( 6269): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6269): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6269): exit::IDLE
D/InitializeManagerStateMachine( 6269): entry::NETWORK_CHECK
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 6269): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6269): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6269): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6269): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6269): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6269): entry::SUCCESS
D/hcjo    ( 6269): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6269): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/hcjo    ( 6269): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6269): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 6269): exit::SUCCESS
D/InitializeManagerStateMachine( 6269): entry::IDLE
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 1481): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/GCM     ( 1481): GCM config loaded
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7136): [RC New] [v2liruge] api execute + 631
,I/SA      ( 7136): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 7136): AsyncTask #1 calls detatch()
,I/SA      ( 7136): [TPMU] getNetworkMcc : 
,W/ContextImpl( 1312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/SA      ( 7136): [SCU] saveMccToPreferece Start
I/SA      ( 7136): [SCU] RegionMCC : 260
,I/SA      ( 7136): [SSP] query invoked
,I/SA      ( 7136): [TPMU] GetMccFromDB : null
I/SA      ( 7136): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7136): [SCU] saveMccToPreferece End
,I/SA      ( 7136): [RC New] executeRequest [v2liruge] end. 691
I/SA      ( 7136): [RC New] Execute end
,I/SA      ( 7136): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7136): [OR] GetMyCountryZoneTask Success
,D/LocalBluetoothProfileManager( 1312): Adding local A2DP profile
,D/LocalBluetoothProfileManager( 1312): Adding local HEADSET profile
,E/BluetoothHeadset( 1312): BTStateChangeCB is registed
,E/BluetoothHeadset( 1312): BluetoothHeadset service is binded
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ContextImpl( 1312): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/Bluetoothsap( 1312): bindService called to Bluetooth SAP Service
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LocalBluetoothProfileManager( 1312): PANU : true
D/LocalBluetoothProfileManager( 1312): Adding local MAP profile
,D/BluetoothMap( 1312): Create BluetoothMap proxy object
,W/LocalBluetoothProfileManager( 1312): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 1312): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1312): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1312): onReceive
D/BluetoothA2dp( 1312): Proxy object connected
,D/A2dpProfile( 1312): Bluetooth service connected
,D/BluetoothAdapterService( 6693): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297b93c5
D/BtConfig.SecureMode( 6693): isSecureModeOn:false
,D/HeadsetProfile( 1312): Bluetooth service connected
,D/Bluetoothsap( 1312): BluetoothSAP Proxy object connected
,D/SapProfile( 1312): Bluetooth service connected
D/Bluetoothsap( 1312): getConnectedDevices()
,D/BluetoothInputDevice( 1312): Proxy object connected
,D/HidProfile( 1312): Bluetooth service connected
,D/AuthorizationBluetoothService( 1481): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothPan( 1312): BluetoothPAN Proxy object connected
,D/PanProfile( 1312): Bluetooth service connected
,D/BluetoothMap( 1312): Proxy object connected
,D/MapProfile( 1312): Bluetooth service connected
D/BluetoothPbap( 1312): Proxy object connected
D/PbapServerProfile( 1312): Bluetooth service connected
,D/SecContentProvider(  894): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/BluetoothAdapter( 6693): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6693): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
D/BluetoothSocket( 6693): bindListen(), new LocalSocket 
D/BluetoothSocket( 6693): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6693): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b625cce
D/bt_vendor( 6693): op for 7
D/bt_upio ( 6693): BT_WAKE is asserted already
,D/BluetoothSocket( 6693): channel: 12
,I/BtOppRfcommListener( 6693): Accept thread started.
,D/SSRM:n  (  894): SIOP:: AP = 390, PST = 329, CUR = 450
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): stay LED for fully charged
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6693): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6693): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5916): mConnectivityHandler : connected
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
,W/PCWCLIENTTRACE_AccountUtil( 5916): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 5916): ================================================
,I/CSTORAGE( 5916):  CSTORAGE_SKM_LIB v1.0.6
I/CSTORAGE( 5916): ================================================
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5916): [GetString-S]
,E/art     ( 5916): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI( 5916): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5916): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5916): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5916): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5916): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5916): [ensureRegistration] - No Samsung account
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/bt_upio ( 6693): ..proc_btwrite_timeout..
,D/bt_vendor( 6693): op for 7
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SurfaceFlinger(  254): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger(  254): id=15 Removed Uoast (-2/9)
,D/PowerManagerService(  894): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 894) eventTime = 171871
,D/PowerManagerService(  894): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=894 (0x0)
,D/PowerManagerService(  894): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=894, ws=WorkSource{1000}) (elapsedTime=3487)
,I/dhcpcd  ( 6856): wlan0: sending IPv6 Router Solicitation
,I/GAV4    ( 7176): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  293): DCD ON
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7329): MountEmulatedStorage()
,E/Zygote  ( 7329): v2
,I/libpersona( 7329): KNOX_SDCARD checking this for 10051
I/libpersona( 7329): KNOX_SDCARD not a persona
,I/ActivityManager(  894): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7329 uid=10051 gids={50051, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7329): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7329): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7329): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7329): TimaSignature is unavailable
,D/ActivityThread( 7329): Added TimaKeyStore provider
,D/ResourcesManager( 7329): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager( 7329): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/btif_config_util( 6693): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/CalendarProvider2( 7329): CalendarProvider2.onCreate() called
,I/ActivityManager(  894): Killing 6245:com.sec.kidsplat.installer/u0a189 (adj 15): bgCount ##41
,I/art     (  894): Explicit concurrent mark sweep GC freed 28900(1801KB) AllocSpace objects, 4(64KB) LOS objects, 17% free, 37MB/45MB, paused 1.875ms total 144.642ms
,I/CalendarProvider2( 7329): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  894): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7357 uid=10171 gids={50171, 9997} abi=armeabi-v7a
,E/Zygote  ( 7357): MountEmulatedStorage()
,E/Zygote  ( 7357): v2
I/libpersona( 7357): KNOX_SDCARD checking this for 10171
I/libpersona( 7357): KNOX_SDCARD not a persona
,I/SELinux ( 7357): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7357): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7357): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 6856): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6856): wlan0: no IPv6 Routers available
,D/TimaKeyStoreProvider( 7357): TimaSignature is unavailable
,D/ActivityThread( 7357): Added TimaKeyStore provider
,D/ResourcesManager( 7357): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 7357): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7357): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7386): MountEmulatedStorage()
E/Zygote  ( 7386): v2
I/libpersona( 7386): KNOX_SDCARD checking this for 10172
I/libpersona( 7386): KNOX_SDCARD not a persona
,I/SELinux ( 7386): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  894): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7386 uid=10172 gids={50172, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 7386): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7386): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SMD     (  293): DCD ON
,I/ActivityManager(  894): Killing 6350:com.sec.enterprise.knox.cloudmdm.smdms/u0a201 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7386): TimaSignature is unavailable
,D/ActivityThread( 7386): Added TimaKeyStore provider
,D/ResourcesManager( 7386): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,W/ResourcesManager( 7386): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7386): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7386): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager(  894): Killing 5317:sstream.app/u0a25 (adj 15): bgCount ##41
,D/PreloadUpdateManagerStateMachine( 6269): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6269): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6269): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6269): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 6269): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6269): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6269): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6269): entry::IDLE
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 330, PST = 327, CUR = 450
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  894): stay LED for fully charged
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6693): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6693): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/PowerManagerService(  894): [PWL] Off : 75s ago
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON,
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  (  894): SIOP:: AP = 310, PST = 325, CUR = 450
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 6
,V/AlarmManager(  894): waitForAlarm result :4
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 310, PST = 323, CUR = 450,
,E/SMD     (  293): DCD ON
,V/AlarmManager(  894): waitForAlarm result :4
,I/ClearcutLoggerApiImpl( 1481): disconnect managed GoogleApiClient
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,V/HeadsetService( 6693): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6693): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,V/AlarmManager(  894): waitForAlarm result :8
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 310, PST = 321, CUR = 450
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,I/Atfwd_Sendcmd(  332): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  332): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  894): [PWL] Off : 105s ago
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 300, PST = 319, CUR = 450
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/Watchdog(  894): !@Sync 7
,V/AlarmManager(  894): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1190): handleTimeUpdate
,D/KeyguardEffectViewController( 1190): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1190): *** don't update sliding image ***
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  894): stay LED for fully charged
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,V/HeadsetService( 6693): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6693): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/DateView( 1190): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1190): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityThread( 1749): Failed to find provider info for com.android.contacts.metadata
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  894): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, SERVER, currentRunTime 198148, reason: ServiceChanged, SyncResult: databaseError: true stats []
,D/SyncManager(  894): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, SERVER, currentRunTime 290491, reason: ServiceChanged
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  894): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  894): mCursor = null
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  (  894): SIOP:: AP = 300, PST = 318, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6693): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6693): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 300, PST = 318, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6693): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6693): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/PowerManagerService(  894): [PWL] Off : 140s ago
,D/SSRM:n  (  894): SIOP:: AP = 300, PST = 318, CUR = 450
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 8
,V/AlarmManager(  894): waitForAlarm result :4
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 300, PST = 315, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6693): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6693): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  894): stay LED for fully charged
D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,E/SMD     (  293): DCD ON
,V/AlarmManager(  894): waitForAlarm result :8
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:n  (  894): SIOP:: AP = 300, PST = 306, CUR = 450
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6693): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6693): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 300, PST = 303, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 9
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6693): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6693): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
D/BatteryService(  894): stay LED for fully charged
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  894): [PWL] Off : 180s ago
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 301, CUR = 450
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 299, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 6693): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6693): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  894): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 297, CUR = 450
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/TimaService(  894): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  894): TimaServiceHandler.handleMessage what =1
,D/TimaService(  894): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  894): initializing...
,I/TLC_TIMA_PKM_initialize(  894): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  894): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  894): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  894): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication(  894): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  894): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  894): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: (  894): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  894): App is not loaded in QSEE
,D/QSEECOMAPI: (  894): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  894): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  894): Trustlet response is completed
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  894): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  894): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  894): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  894): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6693): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6693): Disconnected process message: 10
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/BatteryService(  894): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 300, PST = 297, CUR = 450
,E/SMD     (  293): DCD ON
,I/Atfwd_Sendcmd(  332): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  332): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 296, CUR = 450
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  894): waitForAlarm result :4
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,I/ActivityManager(  894): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7468 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.TIME_TICK
,E/Zygote  ( 7468): MountEmulatedStorage()
,D/KeyguardUpdateMonitor( 1190): handleTimeUpdate
,D/KeyguardEffectViewController( 1190): onReceive action : android.intent.action.TIME_TICK
,E/Zygote  ( 7468): v2
,I/libpersona( 7468): KNOX_SDCARD checking this for 10096
I/libpersona( 7468): KNOX_SDCARD not a persona
,I/KeyguardEffectViewController( 1190): *** don't update sliding image ***
,I/SELinux ( 7468): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7468): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7468): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/DateView( 1190): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1190): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TimaKeyStoreProvider( 7468): TimaSignature is unavailable
,D/ActivityThread( 7468): Added TimaKeyStore provider
,D/ResourcesManager( 7468): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  894): Killing 5359:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): bgCount ##41
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  894): [PWL] Off : 225s ago
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 295, CUR = 450
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 11
,V/GLSActivity( 1481): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1481): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1481): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5488): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5488): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 294, CUR = 450
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  894): stay LED for fully charged
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6693): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6693): Disconnected process message: 10
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 293, CUR = 450
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 292, CUR = 450
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 12
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 291, CUR = 450
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/PowerManagerService(  894): [PWL] Off : 275s ago
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,V/AlarmManager(  894): waitForAlarm result :8
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  293): DCD ON
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 291, CUR = 450
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 13
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 291, CUR = 450
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6693): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6693): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 14
,E/SMD     (  293): DCD ON
,I/Atfwd_Sendcmd(  332): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  332): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/jxcore-log( 6587): Toggling radios to false
I/jxcore-log( 6587): 
,D/BluetoothAdapter( 6587): disable()
,D/SettingsProvider(  894): name = bluetooth_on
,D/BluetoothAdapterState( 6693): CURRENT_STATE=ON, MSG = USER_TURN_OFF
,D/BluetoothAdapterProperties( 6693): Setting state to 13
I/BluetoothAdapterState( 6693): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 6693): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 6693): updateAdapterState state is 13
,I/BluetoothPbapService( 6693): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,D/BluetoothAdapterService( 6693): Autoconnection is available 
,D/BluetoothAdapterService( 6693): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 6693): terminating service from this receiver
,D/BluetoothSocket( 6693): close() in, this: android.bluetooth.BluetoothSocket@267c77ef, channel: 19, state: LISTENING
,D/BluetoothSocket( 6693): close() this: android.bluetooth.BluetoothSocket@267c77ef, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22a060f7, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@16412fcmSocket: android.net.LocalSocket@4d0d85 impl:android.net.LocalSocketImpl@14cb77da fd:FileDescriptor[72]
D/BluetoothSocket( 6693): Closing mSocket: android.net.LocalSocket@4d0d85 impl:android.net.LocalSocketImpl@14cb77da fd:FileDescriptor[72]
,D/BluetoothAdapterProperties( 6693): onBluetoothDisable()
,D/SecContentProvider(  894): uri = 3 selection = isDiscoverableEnabled
,I/BluetoothAdapterState( 6693): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 6693): Scan Mode:20
,D/BluetoothAdapterState( 6693): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/bt-btif ( 6693): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,D/bt_vendor( 6693): op for 7
,E/bt-btif ( 6693): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,D/bt_upio ( 6693): proc btwrite assertion
,E/bt-btif ( 6693): cmd socket is not created
,E/BtOppRfcommListener( 6693): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 6693): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 6693): btm_ble_start_auto_conn start : 0, 0
,W/bt-btif ( 6693): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,W/bt-l2cap( 6693): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 6693): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6693): L2CAP - PSM: 0x001b not found for deregistration
D/bt_vendor( 6693): op for 7
D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
,D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
,D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
,D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
,D/bt_upio ( 6693): BT_WAKE is asserted already
W/InputMethodManagerService(  894): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  894): [BT Setting State] State =13
,D/BluetoothTile( 1190):  onBluetoothStateChange:
,D/bt_vendor( 6693): op for 7
,D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
,D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
,D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
D/bt_upio ( 6693): BT_WAKE is asserted already
,D/bt_vendor( 6693): op for 7
D/bt_upio ( 6693): BT_WAKE is asserted already
,D/BluetoothTile( 1190):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1190): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/bt_vendor( 6693): op for 7
D/bt_upio ( 6693): BT_WAKE is asserted already
,D/BluetoothTile( 1190):  handleUpdatestate:false name:null
,D/BluetoothTile( 1190):  handleUpdatestate:false name:null
,D/STATUSBAR-QSTileView( 1190): onStateChanged: Bluetooth
,D/BluetoothSocket( 6693): close() in, this: android.bluetooth.BluetoothSocket@d5d62e8, channel: 5, state: LISTENING
,D/BluetoothSocket( 6693): close() this: android.bluetooth.BluetoothSocket@d5d62e8, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11debb64, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@c55fd01mSocket: android.net.LocalSocket@237937a6 impl:android.net.LocalSocketImpl@39f575e7 fd:FileDescriptor[74]
D/BluetoothSocket( 6693): Closing mSocket: android.net.LocalSocket@237937a6 impl:android.net.LocalSocketImpl@39f575e7 fd:FileDescriptor[74]
,D/StatusBarManagerService(  894): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
,D/StatusBarManagerService(  894): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1190): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 )
,I/BtOppRfcommListener( 6693): stopping Accept Thread
,D/BluetoothSocket( 6693): close() in, this: android.bluetooth.BluetoothSocket@f19c594, channel: 12, state: LISTENING
D/BluetoothSocket( 6693): close() this: android.bluetooth.BluetoothSocket@f19c594, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b625cce, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2ca4683dmSocket: android.net.LocalSocket@35f12832 impl:android.net.LocalSocketImpl@3a998983 fd:FileDescriptor[78]
D/BluetoothSocket( 6693): Closing mSocket: android.net.LocalSocket@35f12832 impl:android.net.LocalSocketImpl@3a998983 fd:FileDescriptor[78]
,I/BtOppRfcommListener( 6693): BluetoothSocket listen thread finished
,I/PowerManagerService(  894): [PWL] Off : 330s ago
,I/PowerManagerService(  894): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  894): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  894): [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=6693, ws=null) (elapsedTime=80)
I/SamsungIME( 1729): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothManager( 6835): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,I/WifiManager( 6587): packageName : com.test.thalitest
,D/SecContentProvider(  894): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  894): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2(  894): mCursor = null
,D/BluetoothPbap( 1312): Proxy object disconnected
,D/PbapServerProfile( 1312): Bluetooth service disconnected
V/BluetoothEventManager( 1312): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/WifiService(  894): setWifiEnabled: false pid=6587, uid=10278
,D/SettingsProvider(  894): name = wifi_on
,W/ContextImpl( 1312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/jxcore-log( 6587): Radios toggled
I/jxcore-log( 6587): 
,E/WifiStateMachine(  894): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 6699): reset timer : RESET_TIMER 0
I/wpa_supplicant( 6699): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 6699): P2P: Current p2p state = IDLE
,E/WifiConfigStore(  894): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/wpa_supplicant( 6699): Scan requested (ret=0) - scan timeout 30 seconds
,E/native  (  894): do suspend true
,D/DockEventReceiver( 1312): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1312): onReceive
,D/WifiP2pService(  894): InactiveState{ what=143375 }
,D/WifiP2pService(  894): P2pEnabledState{ what=143375 }
,D/AuthorizationBluetoothService( 1481): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/CommandListener(  284): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1190): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1190): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,V/NativeCrypto( 1481): Read error: ssl=0xb3a66200: I/O error during system call, Connection timed out
,V/NativeCrypto( 1481): SSL shutdown failed: ssl=0xb3a66200: I/O error during system call, Broken pipe
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): ValidatedState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): DefaultState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out(  894): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid (  894): Tagging socket 416 with tag ffffffff00000000{4294967295,0} uid 10015, pid: 894, getuid(): 1000
,I/System.out(  894): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Validated
D/ConnectivityService(  894): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  894): rematching NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  894):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  894):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  894):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService(  894): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  894): calling update connectivity
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  894): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1190): CM callback handler got msg 524290
D/ConnectivityService(  894): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/WifiConfigStore(  894): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/ConnectivityService(  894): updateNetworkInfo()
,D/StatusBar.NetworkController( 1190): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1190): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1190): refreshSignalCluster - setNWBoosterIndicators(false)
,I/WifiTrafficPoller(  894): evaluateTrafficStatsPolling
D/ConnectivityService(  894): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  894): updateNetworkInfo()
D/ConnectivityService(  894): ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
,D/ConnectivityService(  894): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
D/NetUtils(  894): android_net_utils_resetConnections in env=0xa939d320 clazz=0x9bff798c iface=wlan0 mask=0x3
,D/StatusBar.NetworkController( 1190): applyOpen
D/StatusBar.NetworkController( 1190): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1190): applyOpen
D/StatusBar.NetworkController( 1190): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1190): applyOpen
D/StatusBar.NetworkController( 1190): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1190): applyOpen
,D/ConnectivityManager.CallbackHandler( 1749): CM callback handler got msg 524290
,D/WifiP2pService(  894): InactiveState{ what=131204 }
,D/WifiP2pService(  894): P2pEnabledState{ what=131204 }
,D/WifiP2pService(  894): sending p2p connection changed broadcast: FAILED
,D/WifiScanningService(  894): SCAN_AVAILABLE : 1
D/RttService(  894): SCAN_AVAILABLE : 1
D/WifiScanningService(  894): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  894): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiDisplayController(  894): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter(  894): onP2pDisconnected
,D/IpRemoteDisplayController(  894): disconnectWfdBridgeServer
D/IpRemoteDisplayController(  894): WfdBridgeServer is already null
,D/WifiNetworkAgent(  894): NetworkAgent: NetworkAgent channel lost
,I/Hs20UtilService( 1312): Starting #6
D/WifiP2pService(  894): sending p2p connection changed broadcast: DISCONNECTED
I/Hs20UtilService( 1312): Message received 5007
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1312): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1312): MountReceiver.mPrefHandler - 7002
E/WifiStateMachine(  894): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController(  894): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  894): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  894): disconnect
D/WifiDisplayController(  894): updateConnection
D/WifiDisplayController(  894): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  894): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiP2pService(  894): P2pDisablingState
D/WifiP2pService(  894): P2pDisablingState{ what=147458 }
,D/WifiP2pService(  894): p2p socket connection lost
D/WifiP2pService(  894): P2pDisabledState
,D/AllShareCastTile( 1190): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayController(  894): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter(  894): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/AllShareCastTile( 1190): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/bt_vendor( 6693): op for 6
D/WifiDisplayAdapter(  894): onP2pDisconnected
D/IpRemoteDisplayController(  894): disconnectWfdBridgeServer
D/IpRemoteDisplayController(  894): WfdBridgeServer is already null
W/bt-l2cap( 6693): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6693): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6693): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6693): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6693): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6693): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 6693): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 6693): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 6693): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 6693): ag scb idx 1 not allocated
W/bt-btif ( 6693): ag scb idx 2 not allocated
E/bt-btif ( 6693): BTA AG is already disabled, ignoring ...
,D/bt_vendor( 6693): op for 7
D/bt_upio ( 6693): BT_WAKE is asserted already
D/bt_userial( 6693): RX termination
W/bt_userial( 6693): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 6693): Leaving userial_read_thread()
E/native  (  894): do suspend true
,D/bt_userial( 6693): userial_close_reader Joined userial reader thread: 0
D/bt_vendor( 6693): op for 9
D/bt_hwcfg( 6693): hw_epilog_process
D/bt_vendor( 6693): op for 4
I/bt_userial_vendor( 6693): device fd = 65 close
,D/bt_vendor( 6693): op for 0
D/bt_upio ( 6693): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 6693): is_emulator_context : 0
D/bt_upio ( 6693): is_rfkill_disabled ? [0]
,D/bt_vendor( 6693): cleanup
,I/GKI_LINUX( 6693): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 6693): GKI_exit_task 0 done
I/GKI_LINUX( 6693): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 6693): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 6693): isSecureModeOn:false
D/BluetoothAdapterService( 6693): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 6693): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 6693): Not skipping com.android.bluetooth.gatt.GattService
,D/BtGatt.DebugUtils( 6693): handleDebugAction() action=null
W/BluetoothAdapterService( 6693): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 6693): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BtGatt.GattService( 6693): Received stop request...Stopping profile...
D/BtGatt.GattService( 6693): stop()
D/BtGatt.AdvertiseManager( 6693): advertise clients cleared
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiP2pService(  894): P2pDisabledState{ what=143375 }
,D/WifiP2pService(  894): DefaultState{ what=143375 }
E/SignOutReceiver( 6207): NETWORK_STATE_CHANGED_ACTION
,D/BluetoothAdapterService( 6693): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297b93c5
,W/BluetoothAdapterService( 6693): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,D/CommandListener(  284): Clearing all IP addresses on wlan0
W/BluetoothAdapterService( 6693): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 6693): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 6693): Not skipping com.android.bluetooth.hid.HidService
D/StatusBar.NetworkController( 1190): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1190): onWifiSignalChanged enabled=true enabledDesc:null
,I/wpa_supplicant( 6699): p2p0: State: DISCONNECTED -> DISCONNECTED
W/BluetoothAdapterService( 6693): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 6693): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 6693): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 6693): Not skipping com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 6693): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 6693): Not skipping com.android.bluetooth.map.BluetoothMapService
I/WifiTrafficPoller(  894): evaluateTrafficStatsPolling
,D/SecContentProvider2(  894): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  894): mCursor = null
,D/StatusBar.NetworkController( 1190): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/SmartBondingService(  894): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1190): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiCredService( 1312): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/BluetoothAdapterService( 6693): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 6693): Not skipping com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 6693): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,D/SmartBondingService(  894): getNetworkEnabled : wifi : false mobile : true
W/BluetoothAdapterService( 6693): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6693): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6693): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6693): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 6693): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6693): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
D/StatusBar.NetworkController( 1190): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
W/BluetoothAdapterService( 6693): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/STATUSBAR-WifiQuickSettingButton( 1190): onWifiSignalChanged enabled=false enabledDesc:null
D/BluetoothAdapterState( 6693): Stopping profile services that were post enabled
E/BluetoothAdapterService(695964613)( 6693): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,D/StatusBar.NetworkController( 1190): refreshSignalCluster - setNWBoosterIndicators(false)
D/HeadsetService( 6693): Received stop request...Stopping profile...
D/StatusBar.NetworkController( 1190): applyOpen
D/StatusBar.NetworkController( 1190): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1190): applyOpen
,D/StatusBar.NetworkController( 1190): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1190): applyOpen
D/StatusBar.NetworkController( 1190): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1190): applyOpen
,D/STATUSBAR-WifiQuickSettingButton( 1190): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1190): Wifi onReceive(0)
D/HotspotTile( 1190): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 1190): onStateChanged: Wi-Fi
,D/BluetoothAdapterService( 6693): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297b93c5
D/HotspotTile( 1190): onReceive : 0, 0
,D/A2dpService( 6693): Received stop request...Stopping profile...
V/Avrcp   ( 6693): doQuit
,D/A2dpStateMachine( 6693): Exit Disconnected: -1
D/HeadsetProfile( 1312): Bluetooth service disconnected
D/AudioService(  894): onServiceDisconnected: Bluetooth profile: 1
,D/Avrcp   ( 6693): Unregistering previous receiver
,W/BluetoothHeadset( 6835): Proxy not attached to service
,D/BluetoothAdapterService( 6693): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297b93c5
,D/BluetoothA2dp( 1312): Proxy object disconnected
D/A2dpProfile( 1312): Bluetooth service disconnected
D/BluetoothA2dp(  894): Proxy object disconnected
D/AudioService(  894): onServiceDisconnected: Bluetooth profile: 2
,D/HidService( 6693): Received stop request...Stopping profile...
D/HidService( 6693): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 6693): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 6693): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 6693): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 6693): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297b93c5
D/BluetoothA2dp( 2930): Proxy object disconnected
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1312): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1312): MountReceiver.mPrefHandler - 7002
,D/BluetoothInputDevice( 1312): Proxy object disconnected
,D/HidProfile( 1312): Bluetooth service disconnected
,D/HealthService( 6693): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 6693): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297b93c5
,D/PanService( 6693): Received stop request...Stopping profile...
D/BluetoothAdapterService( 6693): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297b93c5
,D/BluetoothPan(  894): BluetoothPAN Proxy object disconnected
,D/FileShare-Server( 6410): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
D/BluetoothPan( 1312): BluetoothPAN Proxy object disconnected
D/PanProfile( 1312): Bluetooth service disconnected
D/BluetoothMapService( 6693): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 6693): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297b93c5
,D/WifiDirectBR( 6818): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiDirectBR( 6818): WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
W/ContextImpl( 6818): Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,D/SapService( 6693): Received stop request...Stopping profile...
D/BluetoothMap( 1312): Proxy object disconnected
D/MapProfile( 1312): Bluetooth service disconnected
D/WifiDirectBR( 6818): stopServiceTest : false
,D/SapService( 6693): Stopping Bluetooth SapService
D/BluetoothAdapterService( 6693): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@297b93c5
,D/Bluetoothsap( 1312): BluetoothSAP Proxy object disconnected
,D/SapProfile( 1312): Bluetooth service disconnected
E/BluetoothAdapterService(695964613)( 6693): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 6693): Profile still running: com.android.bluetooth.hid.HidService
,D/WifiDirectBR( 6818): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,I/wpa_supplicant( 6699): Blacklist: Clear (all) 
,W/BluetoothHeadsetServiceJni( 6693): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 6693): Cleaning up Bluetooth Handsfree callback object
,E/BluetoothAdapterService(695964613)( 6693): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 6693): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 6693): Proxy object disconnected
D/BluetoothAdapterService( 6693): Bluetooth A2dp source service disconnected
I/GKI_LINUX( 6693): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 6693): GKI_exit_task 2 done
I/GKI_LINUX( 6693): GKI_shutdown(): task [A2DP-MEDIA] terminated
V/Avrcp   ( 6693): cleanup
,E/BluetoothAdapterService(695964613)( 6693): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 6693): Profile still running: com.android.bluetooth.map.BluetoothMapService
E/BluetoothAdapterService(695964613)( 6693): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 6693): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 6693): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 6693): Cleaning up Bluetooth Health object
E/BluetoothAdapterService(695964613)( 6693): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 6693): Profile still running: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothPanServiceJni( 6693): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 6693): Cleaning up Bluetooth PAN callback object
,E/BluetoothAdapterService(695964613)( 6693): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 6693): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 6693): Profile still running: com.broadcom.bt.service.sap.SapService
,E/BluetoothAdapterService(695964613)( 6693): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
D/BluetoothAdapterState( 6693): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 6693): Setting state to 10
I/BluetoothAdapterState( 6693): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 6693): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 6693): updateAdapterState state is 10
D/BluetoothAdapterService( 6693): Autoconnection is available 
,D/BluetoothAdapterService( 6693): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 6693): Entering OffState
W/BluetoothSAPServiceJni( 6693): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 6693): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,I/Hs20UtilService( 1312): Starting #7
,I/Hs20UtilService( 1312): Message received 5007
,D/NearbySettings( 1312): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1312): DMSUtil.isNetworkConnected - flag-null, state-null
D/BluetoothMap( 1312): onBluetoothStateChange: up=false
,D/BluetoothPbap( 1312): onBluetoothStateChange: up=false
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/BluetoothA2dp( 2930): onBluetoothStateChange: up=false
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1312): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1312): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1312): MountReceiver.mPrefHandler - 7002
D/BluetoothA2dp( 6693): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 1312): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  894): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 1312): onBluetoothStateChange: up=false
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Bluetoothsap( 1312): onBluetoothStateChange: up=false
,D/Bluetoothsap( 1312): Unbinding service...
,E/SignOutReceiver( 6207): NETWORK_STATE_CHANGED_ACTION
,D/BluetoothManagerService(  894): Broadcasting onBluetoothServiceDown() to 12 receivers.
,D/BluetoothManagerService(  894): Broadcasting onBluetoothServiceUp() to 0 receivers.
,W/InputMethodManagerService(  894): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  894): [BT Setting State] State =10
I/InputMethodManagerService(  894): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/BluetoothAdapter( 1190): 289428186: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothTile( 1190):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1190): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapter( 1190): 289428186: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1190): 289428186: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1190): 289428186: getState() :  mService = null. Returning STATE_OFF
D/STATUSBAR-QSTileView( 1190): onStateChanged: Bluetooth
,I/SamsungIME( 1729): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
D/StatusBarManagerService(  894): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=true num=0 )
D/BluetoothAdapter( 1190): 289428186: getState() :  mService = null. Returning STATE_OFF
D/StatusBarManagerService(  894): setIconVisibility slot=bluetooth visible=false
,I/GKI_LINUX( 6693): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 6693): GKI_exit_task 1 done
I/GKI_LINUX( 6693): GKI_shutdown(): task [BTIF] terminated
D/PhoneStatusBar( 1190): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020319 level=0 visible=false num=0 )
,V/BluetoothEventManager( 1312): Received android.bluetooth.adapter.action.STATE_CHANGED
I/BluetoothServiceJni( 6693): cleanupNative: return from cleanup
,D/BluetoothManager( 6835): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,E/SignOutReceiver( 6207): WIFI_STATE_CHANGED_ACTION
,D/BluetoothAdapter( 1481): 275013299: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1481): 275013299: getState() :  mService = null. Returning STATE_OFF
,I/art     ( 6693): System.exit called, status: 0
,I/AndroidRuntime( 6693): VM exiting with result code 0, cleanup skipped.
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6665): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6665): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6665): StateMachine : Current State = 1
D/SecurityLogAgent( 6665): StateMachine : Changed Current State = 1
,W/ContextImpl( 1312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 1312): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1312): onReceive
,I/ActivityManager(  894): Process com.android.bluetooth (pid 6693)(adj 0) has died(247,1497)
,D/AuthorizationBluetoothService( 1481): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/SMD     (  293): DCD ON
,I/wpa_supplicant( 6699): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 6699): CTRL-EVENT-DISCONNECTED bssid=C0.AA.4A reason=3 locally_generated=1
,I/wpa_supplicant( 6699): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 6699): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.4A SSID=4E473730303567
,I/wpa_supplicant( 6699): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/NetdConnector(  894): NDC Command {60 network destroy 502} took too long (1132ms)
,D/ConnectivityService(  894): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  894): calling update connectivity
,D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/EntConnectivity(  894): Not allowed due to - mEnabled false
,D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  894): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1190): CM callback handler got msg 524292
,D/ConnectivityService(  894):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  894): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  894): Disconnected - quitting
,V/Nat464Xlat(  894): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/ConnectivityService(  894): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  894): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1422): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/wpa_supplicant( 6699): Blacklist: Clear (all) 
,D/CSLegacyTypeTracker(  894): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/CSLegacyTypeTracker(  894): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/SmartBondingService(  894): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NtpTrustedTime(  894): forceRefresh() from cache miss
,D/Tethering(  894): MasterInitialState.processMessage what=3
,V/NetworkStats(  894): updateIfacesLocked()
,D/SmartBondingService(  894): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  894): getSBEnabled() enabled =false
,D/SmartBondingService(  894): getSBEnabled() enabled =false
,D/SmartBondingService(  894): getSBEnabled() enabled =false
,V/NetworkStats(  894): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  894): UpdateStatsForKnox
,D/SmartBondingService(  894): getNetworkEnabled : wifi : false mobile : true
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  894): forceRefresh Fail.
,V/NetworkStats(  894): performPollLocked() took 11ms
,D/ConnectivityService(  894): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  894): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  894): forceRefresh() from cache miss
,D/NtpTrustedTime(  894): forceRefresh Fail.
,E/ConnectivityService(  894): updateNetworkInfo()
,V/NetworkStats(  894): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 1190): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 1190): updateDataNetType()
D/StatusBar.NetworkController( 1190): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1190): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1190): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1190): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1190): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1190): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1190): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1190): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1190): applyOpen
D/StatusBar.NetworkController( 1190): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1190): applyOpen
D/StatusBar.NetworkController( 1190): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1190): applyOpen
,D/StatusBar.NetworkController( 1190): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1190): applyOpen
,D/ConnectivityService(  894): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/ConnectivityService(  894): updateNetworkInfo()
,D/ConnectivityService(  894): ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,D/ConnectivityManager.CallbackHandler( 1749): CM callback handler got msg 524292
,D/Tethering(  894): InitialState.processMessage what=4
,D/FileWriteThread_Telephony( 1422): FileWriteThread : threadType = 3
I/wpa_supplicant( 6699): wlan0: CTRL-EVENT-TERMINATING 
E/Tethering(  894): No numeric data
,D/Tethering(  894): sendTetherStateChangedBroadcast 0, 0, 0
,D/NtpTrustedTime(  894): forceRefresh() from cache miss
,D/NtpTrustedTime(  894): forceRefresh Fail.
,D/HotspotTile( 1190): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/HotspotTile( 1190): updateTetherState():false, false
,D/FileWriteThread_Telephony( 1422): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1422): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1422): FileWriteThread : threadType = 3
,V/NetworkStats(  894): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  894): UpdateStatsForKnox
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/FileWriteThread_Telephony( 1422): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1422): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1422): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1422): FileWriteThread : threadType = 3
V/NetworkStats(  894): performPollLocked() took 8ms
D/FileWriteThread_Telephony( 1422): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1422): FileWriteThread : threadType = 3
,D/NtpTrustedTime(  894): forceRefresh() from cache miss
,D/NtpTrustedTime(  894): forceRefresh Fail.
,D/FileWriteThread_Telephony( 1422): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1422): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1422): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1422): FileWriteThread : threadType = 3
,E/WifiStateMachine(  894): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
D/WifiNative-HAL(  894): callSECApiBoolean - ID [21]
,D/StatusBar.NetworkController( 1190): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1190): onWifiSignalChanged enabled=false enabledDesc:null
,D/WifiCredService( 1312): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1190): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/SmartBondingService(  894): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1190): Wifi onReceive(1)
,D/HotspotTile( 1190): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1190): onStateChanged: Wi-Fi
D/SmartBondingService(  894): getNetworkEnabled : wifi : false mobile : true
,W/Settings( 1481): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HotspotTile( 1190): onReceive : 1, 0
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SignOutReceiver( 6207): WIFI_STATE_CHANGED_ACTION
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6665): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6665): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6665): StateMachine : Current State = 1
D/SecurityLogAgent( 6665): StateMachine : Changed Current State = 1
,E/WifiStateMachine(  894): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,D/ConnectivityService(  894): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  894): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  894): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ApplicationPolicy(  894): updateDataUsageMap
,D/SmartBondingService(  894): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  894): getSBEnabled() enabled =false
D/SmartBondingService(  894): getSBEnabled() enabled =false
,D/SmartBondingService(  894): getSBEnabled() enabled =false
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  894): getNetworkEnabled : wifi : false mobile : true
,I/DBG_DM  ( 3174): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5104): type=WIFI subType= reason=null isConnected=false
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3174): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/PCWCLIENTTRACE_PushUtil( 5916): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5916): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5916): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5916): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver( 5916): noConnectivity : true
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DIAGMON_AGENT( 6964): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6964): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client( 6989): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 6989): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 6989): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.511: ( 7009): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 7009): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449746573660
,I/KLMS-2.4.511: ( 7009): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 7009): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.511: ( 7009): StateImplV2(): networkChangeListener().END
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SO_AGENT( 7053): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 7115): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 7136): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 7136): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 7136): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7136): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7136): [OR] == isSIMCardReady false ==
,I/SA      ( 7136): [SCU] == networkStateCheck == false
I/SA      ( 7136): [OR] onReceive END
,E/SPPClientService( 7115): [[SystemStateMonitorService]] No Active Internet
,I/SCloudBackupReceiver( 7159): Other Intent
,I/KnoxUsageLogPro( 6425): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 6425): premStatus:2
,I/KnoxUsageLogPro( 6425): isEulaShown : false
,I/KnoxUsageLogPro( 6425): KnoxUsageReceiver onReceive : not Processible, just return
,D/QuickConnect( 7239): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7239): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7239): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService(  894): exchangeData() failure , invalid userId
,D/RCPManagerService(  894): exchangeData() failure , invalid userId
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SecurityLogAgent( 6665): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6665): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6665): StateMachine : Current State = 1
D/SecurityLogAgent( 6665): StateMachine : Changed Current State = 1
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  894): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/iu.Environment( 1749): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1749): num queued entries: 0
,I/iu.UploadsManager( 1749): num updated entries: 0
,I/iu.SyncManager( 1749): NEXT; no task
,V/AlarmManager(  894): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1190): handleTimeUpdate
,D/KeyguardEffectViewController( 1190): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1190): *** don't update sliding image ***
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  894): stay LED for fully charged
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/DateView( 1190): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1190): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON,
,V/AlarmManager(  894): waitForAlarm result :8
,E/SMD     (  293): DCD ON
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  894): stay LED for fully charged
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 15
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/bootchecker(  325): bootchecker wake up!!
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 16
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  894): [PWL] Off : 390s ago
,I/PowerManagerService(  894): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  894): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  894): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=894, ws=null) (elapsedTime=58587)
,E/SMD     (  293): DCD ON
,D/ConnectivityService(  894): Failed to find a new network - expiring NetTransition Wakelock
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  293): DCD ON
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 17
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 290, CUR = 450
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 18
,E/SMD     (  293): DCD ON
,I/Atfwd_Sendcmd(  332): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  332): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  894): [PWL] Off : 455s ago
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  894): stay LED for fully charged
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 290, CUR = 450
,I/Atfwd_Daemon(  332): Stop the daemon....
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 19
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 289, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 288, CUR = 450
,D/TimaService(  894): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  894): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  894): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel(  894): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  894): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  894): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  894): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 288, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 288, CUR = 450
,E/SMD     (  293): DCD ON
,I/ActivityManager(  894): Killing 5438:com.sec.android.app.controlpanel/u0a134 (adj 13): bgCount ##41
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService(  894): stay LED for fully charged
,I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  894): [PWL] Off : 525s ago
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 290, PST = 288, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  894): stay LED for fully charged
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  894): !@Sync 21
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 287, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  894): setPowerConnected  = true
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  894): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 286, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  894): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 285, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  894): !@Sync 22
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 284, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 283, CUR = 450
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/BatteryService(  894): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  894): stay LED for fully charged
,E/Watchdog(  894): !@Sync 23
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  894): [PWL] Off : 600s ago
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  894): stay LED for fully charged
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 282, CUR = 450
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  894): stay LED for fully charged
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  894): !@Sync 24
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  894): !@Sync 25
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  894): [PWL] Off : 680s ago
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  894): !@Sync 26
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,V/AlarmManager(  894): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1190): handleTimeUpdate
,D/KeyguardEffectViewController( 1190): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1190): *** don't update sliding image ***
,D/LightsService(  894): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  894): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  894): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,D/DateView( 1190): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1190): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/LightsService(  894): [SvcLED]  onSensorChanged::light value = 49
,E/LightSensor(  894): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  894): unregisterListener ::   
,D/LightsService(  894): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,V/AlarmManager(  894): waitForAlarm result :8
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  894): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  894): !@Sync 27
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 28
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  894): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  894): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  894): [PWL] Off : 765s ago
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  894): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 29
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  894): stay LED for fully charged
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  894): stay LED for fully charged
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/TimaService(  894): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  894): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  894): TimaServiceHandler.handleMessage what =1
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel(  894): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  894): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  894): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  894): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  894): stay LED for fully charged
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 31
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  894): [PWL] Off : 855s ago
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 32
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 33
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 34
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  894): [PWL] Off : 950s ago
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 35
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 36
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  894): !@Sync 37
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  894): !@Sync 38
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  894): [PWL] Off : 1050s ago
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  894): stay LED for fully charged
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  894): !@Sync 39
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/TimaService(  894): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  894): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  894): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  894): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  894): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  894): Updating Usage Statistics in DB @ 1449747345463
,I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
,W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
,W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
,W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  894): ::getAppControlDB: Exception to create DB
W/System.err(  894): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  894): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  894): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  894): Done Updating Usage Statistics in DB @ 1449747345646
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,I/TLC_TIMA_PKM_measure_kernel(  894): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  894): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  894): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  894): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  894): !@Sync 40
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  894): stay LED for fully charged
D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  894): !@Sync 41
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  894): [PWL] Off : 1155s ago
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  894): !@Sync 42
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  894): stay LED for fully charged
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  894): !@Sync 43
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 44
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): stay LED for fully charged
D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  894): stay LED for fully charged
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  894): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 45
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  894): [PWL] Off : 1265s ago
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 46
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 47
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 48
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  894): stay LED for fully charged
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 49
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  894): stay LED for fully charged
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  894): [PWL] Off : 1380s ago
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/TimaService(  894): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  894): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  894): TimaServiceHandler.handleMessage what =1
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel(  894): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  894): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  894): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  894): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 51
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 52
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  894): stay LED for fully charged
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 53
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  894): [PWL] Off : 1500s ago
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): Plugged
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 54
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 55
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 56
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 57
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  894): stay LED for fully charged
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  894): [PWL] Off : 1625s ago
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 58
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 59
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/NetworkStatsFactory(  894): UpdateStatsForKnox
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/TimaService(  894): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  894): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  894): TimaServiceHandler.handleMessage what =1
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel(  894): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  894): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  894): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  894): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,V/AlarmManager(  894): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1190): handleTimeUpdate
,V/AlarmManager(  894): waitForAlarm result :8
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): stay LED for fully charged
,D/KeyguardEffectViewController( 1190): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1190): *** don't update sliding image ***
,D/LightsService(  894): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  894): Light old sensor_state 0, new sensor_state : 512 en : 1
,I/ProcessStatsService(  894): Prepared write state in 15ms
,D/SensorManager(  894): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,I/ProcessStatsService(  894): Prepared write state in 14ms
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/NtpTrustedTime(  894): forceRefresh() from cache miss
,D/NtpTrustedTime(  894): forceRefresh Fail.
,V/NetworkStats(  894): performPollLocked(flags=0x3)
,D/NetworkStatsFactory(  894): UpdateStatsForKnox
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  894): performPollLocked() took 4ms
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/NtpTrustedTime(  894): forceRefresh() from cache miss
,D/NtpTrustedTime(  894): forceRefresh Fail.
,D/DateView( 1190): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1190): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/AlarmManager(  894): OOI=Alarm{23b6ecf7 type 0 when 1449749766312 com.google.android.gms}
,V/GLSActivity( 1481): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1481): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 1481): (HTTPLog)-Static: isSBSettingEnabled false
,E/Auth    ( 1481): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.gms, Service: oauth2: email
,V/NativeCrypto( 1481): SSL shutdown failed: ssl=0xaeed8e00: I/O error during system call, Connection timed out
,D/LightsService(  894): [SvcLED]  onSensorChanged::light value = 45
,E/LightSensor(  894): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  894): unregisterListener ::   
D/LightsService(  894): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/ProcessStatsService(  894): Pruning old procstats: /data/system/procstats/state-2015-12-09-17-15-56.bin
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/BatteryService(  894): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 61
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  894): stay LED for fully charged
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  894): stay LED for fully charged
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  894): [PWL] Off : 1755s ago
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/Watchdog(  894): !@Sync 62
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  894): stay LED for fully charged
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,E/SMD     (  293): DCD ON
,V/AlarmManager(  894): waitForAlarm result :8
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  894): stay LED for fully charged
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  894): !@Sync 63
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  894): !@Sync 64
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  894): Plugged
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/MotionRecognitionService(  894): setPowerConnected  = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  894): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  894): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  894): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  894): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  894): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  894): Plugged
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,I/MotionRecognitionService(  894): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1190):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  894): stay LED for fully charged
D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  894): !@Sync 65
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  894): SIOP:: AP = 280, PST = 280, CUR = 450
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7774): 
D/AndroidRuntime( 7774): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7774): CheckJNI is OFF
D/AndroidRuntime( 7774): readGMSProperty: start
D/AndroidRuntime( 7774): readGMSProperty: already setted!!
D/AndroidRuntime( 7774): readGMSProperty: end
D/AndroidRuntime( 7774): addProductProperty: start
E/AffinityControl( 7774): AffinityControl: registerfunction enter
D/AndroidRuntime( 7774): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  894): START PACKAGE DELETE: observer{99165234}
D/PackageManager(  894): pkg{<packageName>}
D/PackageManager(  894): user{0}
D/PackageManager(  894): caller{2000}
D/PackageManager(  894): flags{3}
D/PersonaManagerService(  894): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  894): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  894): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  894): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  894): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  894): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  894): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  894): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  894): getApplicationUninstallationEnabled
D/ApplicationPolicy(  894): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  894): !@killApplicatoin: 10278, uninstall pkg
I/ActivityManager(  894): Force stopping com.test.thalitest appid=10278 user=-1: uninstall pkg
I/ActivityManager(  894): Killing 6587:com.test.thalitest/u0a278 (adj 0): stop com.test.thalitest
W/PackageSettings(  894): Skipping PackageSetting{1d29ab65 com.example.hello/10268} due to missing metadata
I/WindowState(  894): WIN DEATH: Window{f680b9b u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  254): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  254): id=13 Removed NainActivit (-2/8)
I/SurfaceFlinger(  254): id=13 Removed NainActivit (-2/8)
E/libprocessgroup(  894): failed to kill 1 processes for processgroup 6587
I/ActivityManager(  894): Killing 5196:com.sec.android.gallery3d/u0a53 (adj 13): empty for 1804s
D/PointerIcon(  894): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  894): setMouseCustomIcon IconType is same.101
D/PointerIcon(  894): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  894): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager(  894): Killing 6061:com.sec.android.provider.badge/u0a92 (adj 13): empty for 1809s
I/ActivityManager(  894): Killing 5664:com.sec.android.widgetapp.activeapplicationwidget/u0a182 (adj 13): empty for 1861s
I/ActivityManager(  894): Killing 6308:com.sec.android.widgetapp.dualclockdigital/u0a115 (adj 15): empty for 1865s
I/ActivityManager(  894): Killing 6293:com.sec.android.widgetapp.digitalclock/u0a109 (adj 15): empty for 1865s
I/ActivityManager(  894): Killing 6033:com.android.mms/u0a55 (adj 15): empty for 1865s
E/lowmemorykiller(  251): Error writing /proc/6033/oom_score_adj; errno=22
E/SMD     (  293): DCD ON
D/CountryDetector(  894): No listener is left
I/ActivityManager(  894): Killing 5488:com.android.vending/u0a33 (adj 15): empty for 1869s
I/ActivityManager(  894): Killing 6441:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty for 1871s
I/ActivityManager(  894):   Force finishing activity ActivityRecord{3438da6d u0 com.test.thalitest/.MainActivity t3}
D/FocusedStackFrame(  894): Set to : 0
W/ActivityManager(  894): Spurious death for ProcessRecord{3df7d583 6587:com.test.thalitest/u0a278}, curProc for 6587: null
W/libprocessgroup(  894): failed to open /acct/uid_10053/pid_5196/cgroup.procs: No such file or directory
W/libprocessgroup(  894): failed to open /acct/uid_10092/pid_6061/cgroup.procs: No such file or directory
W/libprocessgroup(  894): failed to open /acct/uid_10182/pid_5664/cgroup.procs: No such file or directory
W/libprocessgroup(  894): failed to open /acct/uid_10115/pid_6308/cgroup.procs: No such file or directory
W/libprocessgroup(  894): failed to open /acct/uid_10109/pid_6293/cgroup.procs: No such file or directory
W/libprocessgroup(  894): failed to open /acct/uid_10055/pid_6033/cgroup.procs: No such file or directory
W/libprocessgroup(  894): failed to open /acct/uid_10033/pid_5488/cgroup.procs: No such file or directory
W/libprocessgroup(  894): failed to open /acct/uid_1000/pid_6441/cgroup.procs: No such file or directory
D/ConnectivityService(  894): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  894): Force stopping com.test.thalitest appid=10278 user=0: pkg removed
I/art     ( 1616): Explicit concurrent mark sweep GC freed 868(50KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 18MB/31MB, paused 1.929ms total 31.896ms
I/art     ( 5159): Explicit concurrent mark sweep GC freed 40695(2MB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 15MB/26MB, paused 571us total 33.007ms
D/ResourcesManager(  894): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader(  894): Reconfiguring input devices.  changes=0x00000010
W/SQLiteConnectionPool( 1749): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/GeofencerStateMachine( 1481): Ignoring removeGeofence because network location is disabled.
E/SamsungIME( 1729): mOCRHelper is null
D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
I/art     ( 1749): Explicit concurrent mark sweep GC freed 6390(276KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 22MB/30MB, paused 7.320ms total 113.724ms
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
I/art     ( 6207): Explicit concurrent mark sweep GC freed 6826(435KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 16MB/21MB, paused 578us total 87.203ms
I/KLMS-2.4.511: ( 7009): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.511: ( 7009): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1449748103212
I/KLMS-2.4.511: ( 7009): MainReciver(): PACKAGE_REMOVED
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
I/KLMS-2.4.511: ( 7009): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/SecContentProvider2(  894): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  894): mCursor = null
D/RegisteredServicesCache( 1407): empty dynamic service
D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
E/Zygote  ( 7821): MountEmulatedStorage()
E/Zygote  ( 7821): v2
I/libpersona( 7821): KNOX_SDCARD checking this for 10116
I/libpersona( 7821): KNOX_SDCARD not a persona
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
I/ActivityManager(  894): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7821 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/SELinux ( 7821): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7821): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7821): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/RCPManagerService(  894): PackageReceiver onReceive()
I/HarmonyEASService(  894): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  894): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  894): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  894): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  894): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  894): uID is 10278
V/EnterpriseBillingPolicy(  894): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  894): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  894): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  894): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  894): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  894): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  894): getBillingProfileForVpnEngine - end - null
D/TaskPersister(  894): removeObsoleteFile: deleting file=3_task.xml
D/TimaKeyStoreProvider( 7821): TimaSignature is unavailable
D/ActivityThread( 7821): Added TimaKeyStore provider
D/ResourcesManager( 7821): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/SurfaceWidgetView( 1444): destroyHardwareResources():1011741810
V/WindowOrientationListener(  894): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  894): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  894): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  894): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  894): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/Launcher( 1444): onRestart, Launcher: 42379073
D/Launcher( 1444): onStart, Launcher: 42379073
D/Launcher.HomeView( 1444): onStart
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1794): [237392/8] Surface widget visibility changed visibility = true on instance = 1
V/ActivityThread( 1444): updateVisibility : ActivityRecord{2d9312cb token=android.os.BinderProxy@27798bbd {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/SurfaceWidget.Renderer( 1794): [237392/8] SurfaceWidget drawing first frame
D/accuweather( 1794): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
I/art     (  894): Explicit concurrent mark sweep GC freed 23024(1758KB) AllocSpace objects, 9(144KB) LOS objects, 17% free, 37MB/45MB, paused 2.207ms total 278.273ms
D/elm:14491( 7821): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
I/SurfaceFlinger(  254): id=16 createSurf (1080x1920),1 flag=4, Mauncher
D/elm:14491( 7821): ELMEngine.ELMEngine( context ).
D/StatusBarManagerService(  894): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/elm:14491( 7821): MDMBridge.setEnterpriseBridge()
D/StatusBarManagerService(  894): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  894): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  894): setMouseCustomIcon IconType is same.101
D/PointerIcon(  894): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  894): setHoveringSpenCustomIcon IconType is same.1
D/elm:14491( 7821): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
D/elm:14491( 7821): ElmAgentService : onCreate()
D/InputMethodManagerService(  894): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/elm:14491( 7821): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 7821): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 7821): MDMBridge.getInstance()
D/elm:14491( 7821): MDMBridge.getAllLicenseInfoFromSDK()
D/PackageManager(  894): delete codoeFile: 
I/AASAUninstall(  894):  com.test.thalitest not target!
D/PackageManager(  894): result of delete: 1{99165234}
D/AndroidRuntime( 7774): Shutting down VM
E/Zygote  ( 7840): MountEmulatedStorage()
E/Zygote  ( 7840): v2
I/libpersona( 7840): KNOX_SDCARD checking this for 10021
I/libpersona( 7840): KNOX_SDCARD not a persona
I/ActivityManager(  894): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=7840 uid=10021 gids={50021, 9997} abi=armeabi-v7a
D/elm:14491( 7821): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux ( 7840): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
W/InputMethodManagerService(  894): Got RemoteException sending setActive(false) notification to pid 6587 uid 10278
I/SELinux ( 7840): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7840): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ContextImpl(  894): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/elm:14491( 7821): ElmAgentService : onDestroy().
D/TimaKeyStoreProvider( 7840): TimaSignature is unavailable
D/ActivityThread( 7840): Added TimaKeyStore provider
D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
I/Timeline(  894): Timeline: Activity_windows_visible id: ActivityRecord{127b9c3 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:1971894
D/ResourcesManager( 7840): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 7840): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 7840): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 7840): onReceive() : package name is not s health. Return !!!
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
D/EnterpriseDeviceManagerService(  894): Package has changed for user 0
D/EnterpriseDeviceManagerService(  894): Admin package name: com.google.android.gms
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Music2/Music2.apk
W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Videos/Videos.apk
E/Zygote  ( 7858): MountEmulatedStorage()
E/Zygote  ( 7858): v2
I/libpersona( 7858): KNOX_SDCARD checking this for 10025
I/libpersona( 7858): KNOX_SDCARD not a persona
I/ActivityManager(  894): Start proc sstream.app for broadcast sstream.app/.receiver.ApplicationCompatibleReceiver: pid=7858 uid=10025 gids={50025, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 7858): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
I/SELinux ( 7858): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7858): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/TimaKeyStoreProvider( 7858): TimaSignature is unavailable
D/ActivityThread( 7858): Added TimaKeyStore provider
W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager( 7858): creating new AssetManager and set to /system/priv-app/MagazineHome/MagazineHome.apk
W/ResourcesManager( 7858): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/linker  ( 7858): libdmcAlwaysFD.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
D/MVFD_interface( 7858): <<<  caMVFace_FaceInit
W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Maps/Maps.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
W/ResourcesManager(  894): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  894): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  894): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  894): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  894): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7858): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7858): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  894): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  894): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/Resources(  894): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager(  894): clearDefaults: com.test.thalitest
I/CrashAnrDetector(  894): onPackageRemoved : com.test.thalitest
E/SharedPreferencesImpl( 7858): Couldn't create directory for SharedPreferences file /data/data/sstream.app/shared_prefs/shared_prefs.xml
D/HockeyApp( 7858): Current handler class = sstream.app.util.Log$1
I/EventHub(  894): Removing device '/dev/input/event6' due to inotify event
I/EventHub(  894): Removing device '/dev/input/event7' due to inotify event
E/SQLiteLog( 7858): (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteLog( 7858): (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 7858): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 7858): (14) os_unix.c:32503: (2) open(/data/data/sstream.app/databases/sstream.db) - 
E/SQLiteDatabase( 7858): Failed to open database '/data/data/sstream.app/databases/sstream.db'.
E/SQLiteDatabase( 7858): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 7858): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7858): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7858): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7858): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7858): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7858): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7858): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7858): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7858): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7858): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7858): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7858): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7858): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7858): 	at sstream.app.provider.StoryProvider.delete(StoryProvider.java:90)
E/SQLiteDatabase( 7858): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:314)
E/SQLiteDatabase( 7858): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/SQLiteDatabase( 7858): 	at sstream.app.provider.DatabaseUtil.deleteConfigSettingForApp(DatabaseUtil.java:985)
E/SQLiteDatabase( 7858): 	at sstream.app.receiver.ApplicationCompatibleReceiver.onReceive(ApplicationCompatibleReceiver.java:216)
E/SQLiteDatabase( 7858): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2991)
E/SQLiteDatabase( 7858): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
E/SQLiteDatabase( 7858): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
E/SQLiteDatabase( 7858): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7858): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7858): 	at android.app.ActivityThread.main(ActivityThread.java:5940)
E/SQLiteDatabase( 7858): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7858): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7858): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1389)
E/SQLiteDatabase( 7858): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1184)
D/AndroidRuntime( 7858): Shutting down VM
D/HockeyApp( 7858): Writing unhandled exception to: /data/data/sstream.app/files/8dd827d9-b531-430b-81a3-dddf5a768e0e.stacktrace
I/PCWCLIENTTRACE_PushUtil( 5916): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5916): sales region : global
E/HockeyApp( 7858): Error saving exception stacktrace!
E/HockeyApp( 7858): 
E/HockeyApp( 7858): java.io.FileNotFoundException: /data/data/sstream.app/files/8dd827d9-b531-430b-81a3-dddf5a768e0e.stacktrace: open failed: EROFS (Read-only file system)
E/HockeyApp( 7858): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/HockeyApp( 7858): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/HockeyApp( 7858): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/HockeyApp( 7858): 	at java.io.FileWriter.<init>(FileWriter.java:80)
E/HockeyApp( 7858): 	at net.hockeyapp.android.internal.ExceptionHandler.saveException(ExceptionHandler.java:83)
E/HockeyApp( 7858): 	at net.hockeyapp.android.internal.ExceptionHandler.uncaughtException(ExceptionHandler.java:108)
E/HockeyApp( 7858): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/HockeyApp( 7858): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
E/HockeyApp( 7858): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/HockeyApp( 7858): 	at libcore.io.Posix.open(Native Method)
E/HockeyApp( 7858): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/HockeyApp( 7858): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/HockeyApp( 7858): 	... 7 more
I/PCWCLIENTTRACE_PushUtil( 5916): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5916): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  894): checkUser: useridlist=null, currentuser=0
I/EventHub(  894): Removing device '/dev/input/event8' due to inotify event
D/ResourcesManager( 7858): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/ResourcesManager( 7858): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/SQLiteLog( 7858): (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteLog( 7858): (28) failed to open "/data/data/sstream.app/databases/sstream.db" with flag (131072) and mode_t (0) due to error (2)
E/SQLiteLog( 7858): (14) cannot open file at line 32503 of [9491ba7d73]
E/SQLiteLog( 7858): (14) os_unix.c:32503: (2) open(/data/data/sstream.app/databases/sstream.db) - 
E/SQLiteDatabase( 7858): Failed to open database '/data/data/sstream.app/databases/sstream.db'.
E/SQLiteDatabase( 7858): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 7858): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7858): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7858): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7858): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7858): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7858): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7858): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7858): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7858): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7858): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7858): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7858): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7858): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7858): 	at sstream.app.provider.StoryProvider.query(StoryProvider.java:386)
E/SQLiteDatabase( 7858): 	at android.content.ContentProvider.query(ContentProvider.java:980)
E/SQLiteDatabase( 7858): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/SQLiteDatabase( 7858): 	at android.content.ContentResolver.query(ContentResolver.java:484)
E/SQLiteDatabase( 7858): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/SQLiteDatabase( 7858): 	at sstream.app.provider.DatabaseUtil.queryConfigSetting(DatabaseUtil.java:685)
E/SQLiteDatabase( 7858): 	at sstream.app.receiver.ApplicationCompatibleReceiver.addCompatibleAppsToDB(ApplicationCompatibleReceiver.java:418)
E/SQLiteDatabase( 7858): 	at sstream.app.receiver.ApplicationCompatibleReceiver.getCompatibleApps(ApplicationCompatibleReceiver.java:155)
E/SQLiteDatabase( 7858): 	at sstream.app.StreamManager$1.run(StreamManager.java:177)

```
